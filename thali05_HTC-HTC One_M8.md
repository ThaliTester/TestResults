#### Test 5107482134e3b48_thali05_HTC-HTC One_M8 Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 5763): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5763): ====startRecUseTime====
D/htc.customization.log.level( 5763):  is 
W/CustomizationLogLevel( 5763): Level value is invalid, use default level 2
D/CustomizationManager( 5763):  Read ACC file spent 0.041 (s)
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__203
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__405
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__304
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 5763): Parsing tag item name = HTC__002
V/CustomizationCIDLoader( 5763): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5763): Parsing tag category name = system
I/CustomizationCIDLoader( 5763): Parsing tag category name = application
I/CustomizationCIDLoader( 5763): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5763): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5763): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5763): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5763): Parsing tag category name = ACC
D/CustomizationManager( 5763):  Read CID file spent 0.085 (s)
D/CustomizationManager( 5763):  All configurations done spent 0.085 (s)
E/ActTriggerJNI( 5763): open library fail.
E/MP-Decision( 2109): Update arg 2
--------- beginning of system
I/ActivityManager(  895): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
E/MP-Decision( 2109): Update arg 4
D/PMS     (  895): acquireHCC(2893b7cf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 895 1000 null
D/PMS     (  895): acquireHCC(200855c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 895 1000 null
W/asset   (  895): Copying FileAsset 0xb89e4bc0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/MP-Decision( 2109): Update arg "0 190 240 240".
E/MP-Decision( 2109): Update arg "0 75 400 400".
I/ActivityManager(  895): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5794 uid=10373 gids={50373, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  895): Display changed displayId=0
D/DotMatrix( 1193): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1193): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 5794): Copying FileAsset 0xb8762ce0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1493): [trimMemory] 20
I/WebViewFactory( 5794): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5794): Time to load native libraries: 1 ms (timestamps 1176-1177)
I/LibraryLoader( 5794): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5794): Binding Chromium to main looper Looper (main, tid 1) {84bb899}
I/LibraryLoader( 5794): Expected native library version number "",actual native library version number ""
I/chromium( 5794): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5794): Initializing chromium process, singleProcess=true
W/art     ( 5794): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5794): ApplicationContext is null in ApplicationStatus
W/chromium( 5794): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5794): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5794): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5794): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5794): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 5794): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5794): Build Date: 12/11/14 Thu
I/Adreno-EGL( 5794): Local Branch: 
I/Adreno-EGL( 5794): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 5794): Local Patches: NONE
I/Adreno-EGL( 5794): Reconstruct Branch: NOTHING
,W/System.err(  895): java.lang.Throwable: stack dump
,W/System.err(  895): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  895): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  895): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  895): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  895): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@161b8b60:true
D/BluetoothAdapter( 5794): 263100664: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5794): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5794): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5794): CordovaWebView is running on device made by: HTC
,W/art     ( 5794): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5794): Attempt to remove local handle scope entry from IRT, ignoring
,D/Atlas   ( 5794): Validating map...
,D/HtcSystemUPManager(  895): HtcSystemUPolicy [canLog (default)] category: launch, enable: true,
W/chromium( 5794): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  895): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  895): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  895): hiding MENU key
,D/StatusBarManagerService(  895): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  895): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  895): hiding MENU key
,I/InputMethodManager( 5794): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@10355e4b, mServedView=org.apache.cordova.engine.SystemWebView{22763028 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@15eee141,
,I/InputMethodManagerService(  895): Disable input method client, pid=1493
D/StatusBarManagerService(  895): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 5794): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  895): Displayed com.test.thalitest/.MainActivity: +410ms (total +465ms),
,W/BindingManager( 5794): Cannot call determinedVisibility() - never saw a connection for the pid: 5794,
,D/JsMessageQueue( 5794): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 5794): JniHelper::setJavaVM(0xb76b9b98), pthread_self() = -1198376296
,D/JX-Cordova( 5794): jxcore cordova android initializing
,W/jxcore-log( 5794): Initializing JXcore engine
W/jxcore-log( 5794): JXcore engine is ready
,W/jxcore-log( 5794): Starting JXcore engine,
,D/PMS     (  895): releaseHCC(2893b7cf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  895): releaseHCC(200855c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/MP-Decision( 2109): Update arg 1,
,W/jxcore-log( 5794): Platform android
W/jxcore-log( 5794): 
,W/jxcore-log( 5794): Process ARCH arm
W/jxcore-log( 5794): 
,I/jxcore-log( 5794): JXcore Cordova bridge is ready!,
I/jxcore-log( 5794): 
W/jxcore-log( 5794): JXcore engine is started
,I/chromium( 5794): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5794): Turning radios to true,
I/jxcore-log( 5794): 
D/BluetoothManagerService(  895): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  895): checking for enable restriction...
D/BluetoothManagerService(  895): checkBTEasState, ret=true
D/BluetoothManagerService(  895): enable(): region ID = 6
D/BluetoothManagerService(  895): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  895): MONITOR_LOG
W/Settings:Agent(  895): name: bluetooth_on
W/Settings:Agent(  895): value: 1
W/Settings:Agent(  895): >> traceCallingStack()
W/Settings:Agent(  895): Process.myPid(): 895
W/Settings:Agent(  895): Process.myTid(): 1460
W/Settings:Agent(  895): Process.myUid(): 1000
W/Settings:Agent(  895): ,
W/Settings:Agent(  895): 
W/System.err(  895): java.lang.Throwable: stack dump
W/System.err(  895): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  895): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  895): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  895): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  895): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  895): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  895): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
W/System.err(  895): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:599)
W/System.err(  895): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  895): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  895): 
W/Settings:Agent(  895): << traceCallingStack(): 0(ms)
,D/BluetoothManagerService(  895): Message: MESSAGE_ENABLE,
,D/BluetoothManagerService(  895): MESSAGE_ENABLE: mBluetooth = null,
I/jxcore-log( 5794): toggleBluetooth - 
I/jxcore-log( 5794): 
D/WifiService(  895): New client listening to asynchronous messages
E/WifiTrafficPoller(  895): ADD_CLIENT: 7
D/WifiManager( 5794): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10373
,D/WifiService(  895): setWifiEnabled: true pid=5794, uid=10373
W/Settings:Agent(  895): MONITOR_LOG
E/WifiService(  895): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  895): name: wifi_on
I/WifiService(  895): isSprintWifiRestricted(): false
W/Settings:Agent(  895): value: 2
I/WifiService(  895): isMdmWifiRestricted(): false
W/Settings:Agent(  895): >> traceCallingStack()
W/Settings:Agent(  895): Process.myPid(): 895
W/Settings:Agent(  895): Process.myTid(): 1515
W/Settings:Agent(  895): Process.myUid(): 1000
W/Settings:Agent(  895): 
W/Settings:Agent(  895): 
W/System.err(  895): java.lang.Throwable: stack dump
W/System.err(  895): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  895): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  895): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,W/System.err(  895): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  895): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  895): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  895): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
W/System.err(  895): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  895): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
W/System.err(  895): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  895): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  895): 
W/Settings:Agent(  895): << traceCallingStack(): 0(ms)
,I/jxcore-log( 5794): toggleWiFi
,I/jxcore-log( 5794): ,
D/PMS     (  895): acquireWL(9495da8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 895 1000 null,
,E/WifiStateMachine(  895): setting operational mode to 1,
I/ActivityManager(  895): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5854 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
E/WifiStateMachine(  895): handleMessage: E msg.what=131083
W/ResourcesManager( 5854): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
E/WifiStateMachine(  895): processMsg: InitialState
E/WifiStateMachine(  895):  InitialState CMD_START_SUPPLICANT 0 0
I/art     (  470): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 138us total 10.198ms
I/art     (  470): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 131us total 8.700ms
I/art     (  470): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 130us total 9.088ms
,D/AdapterServiceConfig( 5854): Adding HeadsetService,
D/AdapterServiceConfig( 5854): Adding A2dpService
D/AdapterServiceConfig( 5854): Adding HidService
D/AdapterServiceConfig( 5854): Adding HealthService,
D/AdapterServiceConfig( 5854): Adding PanService
D/AdapterServiceConfig( 5854): Adding GattService
,W/linker  ( 5854): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  895): java.lang.Throwable: stack dump,
W/System.err(  895): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  895): ,	,at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  895): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  895): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  895): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13b2bfa7:true
D/BluetoothAdapterState( 5854): make
,I/BluetoothAdapterState( 5854): Entering OffState
I/BluetoothAdapterState( 5854): notBluetoothOff()
,E/bt_osi_config( 5854): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
D/BluetoothAdapterProperties( 5854): Address is:50:2E:6C:AC:21:50
D/BluetoothManagerService(  895): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  895): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  895): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  895): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  895): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothAdapter( 5854): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@1ed99b6a
D/BluetoothAdapter( 5854): onBluetoothServiceUp done
D/BluetoothAdapter(  895): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1241af43
D/BluetoothAdapter(  895): onBluetoothServiceUp done
D/BluetoothAdapter( 1130): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@6b2e774
D/BluetoothAdapter( 1130): onBluetoothServiceUp done
D/BluetoothAdapter( 3173): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2495640e
D/BluetoothAdapter( 3173): onBluetoothServiceUp done
D/BluetoothAdapter( 1445): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@356bdf6c
D/BluetoothAdapter( 1445): onBluetoothServiceUp done
D/BluetoothAdapter( 1465): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3ff78f10
D/BluetoothAdapter( 1465): onBluetoothServiceUp done
D/BluetoothAdapter( 5794): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@95d923d
D/BluetoothAdapter( 5794): onBluetoothServiceUp done
D/BluetoothAdapter( 1658): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@70e63
D/BluetoothAdapter( 1658): onBluetoothServiceUp done
D/BluetoothManagerService(  895): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 5854): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5854): Setting state to 11
I/BluetoothAdapterState( 5854): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  895): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  895): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  895): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  895): Bluetooth State Change Intent: 10 -> 11
V/BluetoothPbapReceiver( 5854): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5854): ***********state = 11
D/BluetoothBondStateMachine( 5854): make
I/IntentController( 1130): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothAdapterService( 5854): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 5854): checkA2dpState: returning
D/BluetoothAdapterService( 5854): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 5854): checkHfpState: returning
I/BluetoothBondStateMachine( 5854): StableState(): Entering Off State
D/NGFService( 3173): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,D/Tethering(  895): interfaceAdded wlan0,
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
,V/Tethering(  895): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  895): interfaceLinkStateChanged wlan0, false
,I/ActivityManager(  895): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5890 uid=10036 gids={50036, 9997, 3002, 3001} abi=armeabi-v7a
D/Tethering(  895): interfaceStatusChanged wlan0, false
D/PMS     (  895): acquireWL(2a1cef33): PARTIAL_WAKE_LOCK  NetworkStats 0x1 895 1000 null
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  895): releaseWL(2a1cef33): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/Tethering(  895): interfaceAdded p2p0
V/NetworkPolicy(  895): updateNetworkEnabledLocked()
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
V/NetworkPolicy(  895): updateNotificationsLocked()
D/Tethering(  895): p2p0 is not a tetherable iface, ignoring
D/UsbDeviceManager(  895): [USBNET] bCheckSuppFunc: cdc_network
D/Tethering(  895): interfaceLinkStateChanged p2p0, false
,D/UsbDeviceManager(  895): [USBNET] bCheckSuppFunc: cdc_network,
D/Tethering(  895): interfaceStatusChanged p2p0, false
D/PMS     (  895): acquireWL(39e8ee1c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 895 1000 null
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  895): releaseWL(9495da8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/HeadsetService( 5854): Received start request. Starting profile...
V/NetworkPolicy(  895): updateNetworkEnabledLocked()
D/BluetoothHeadset(  895): Proxy object connected
V/NetworkPolicy(  895): updateNotificationsLocked()
D/HeadsetStateMachine( 5854): Version 1.6
D/PMS     (  895): releaseWL(39e8ee1c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/HeadsetStateMachine( 5854): make
D/WIFI_ICON( 1130): updateWifiState: WIFI_STATE_CHANGED disabled
D/BluetoothHeadset( 1130): Proxy object connected
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingMiniLite( 1130): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@146a149d
D/BluetoothHeadset( 1445): Proxy object connected
D/BluetoothHeadset( 1445): Proxy object connected
D/Tethering(  895): sendTetherStateChangedBroadcast 1, 0, 0
D/BluetoothPhoneService( 1445): BluetoothHeadset onServiceConnected
,D/Tethering(  895): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/BluetoothHeadset( 1445): Proxy object connected
V/Tethering(  895): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  895): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 1445): 467251658: getState(). Returning 11
I/QuickSettingBluetooth( 1130): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/Tethering(  895): sendTetherStateChangedBroadcast 0, 0, 0
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  895): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  895): [NET] android_getaddrinfo_proxy+
D/BluetoothAdapter(  895): 793826978: getState(). Returning 11
D/libc    (  895): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  458): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  458): [NET] android_getaddrinfofornet-, err=7
D/libc    (  895): [NET] android_getaddrinfo_proxy-, NODATA
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BluetoothAdapterState( 5854): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
D/UsbnetService(  895): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/UsbnetService(  895): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 5854): max_hf_connections = 2
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
D/HeadsetPhoneState( 5854): listenForPhoneState..for service and signal 
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
,D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
D/HeadsetStateMachine( 5854): Enter Disconnected: -2, size: 0
I/HeadsetStateMachine( 5854): setCurrentDevice, the latest mCurrentDevice is:null
D/BluetoothAdapterService( 5854): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d2675e
D/A2dpService( 5854): Received start request. Starting profile...
E/WifiStateMachine(  895): setWifiState: enabling
,D/BluetoothA2dp(  895): Proxy object connected,
E/WifiStateMachine(  895): Supplicant start successful
D/WifiMonitor(  895): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  895): connecting to supplicant
I/IntentController( 1130): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothAdapter(  895): 793826978: getState(). Returning 11
D/WirelessDisplayService(  895): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/BluetoothHeadset( 3173): Proxy object connected
,D/NGFService( 3173): BluetoothHeadset onServiceConnected: main,
D/BluetoothAdapter( 3173): 149687855: getState(). Returning 11
W/NGFService( 3173): Headset deviceList = 0
D/BluetoothA2dp( 3173): Proxy object connected
D/NGFService( 3173): BluetoothA2dp onServiceConnected: main
E/RemoteController( 5854): Cannot set synchronization mode on an unregistered RemoteController
D/BluetoothAdapter( 3173): 149687855: getState(). Returning 11
W/NGFService( 3173): A2dp deviceList = 0
,D/A2dpStateMachine( 5854): make
,D/wpa_supplicant( 5909): wpa_supplicant v2.3-devel-5.0.1
D/wpa_supplicant( 5909): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 5909): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 5909): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 5909): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 5909): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 5909): Successfully initialized wpa_supplicant
D/wpa_supplicant( 5909): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 5909): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 5909): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/A2dpService( 5854): setA2dpService(): set to: null
D/BluetoothAdapterService( 5854): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d2675e
D/wpa_supplicant( 5909): ctrl_interface='/data/misc/wifi/sockets'
,D/wpa_supplicant( 5909): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 5909): update_config=1
D/wpa_supplicant( 5909): uuid=12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 5909): device_name='Android_d8c3'
D/wpa_supplicant( 5909): manufacturer='HTC'
D/wpa_supplicant( 5909): model_name='HTC_PHONE'
D/wpa_supplicant( 5909): model_number='1234'
D/wpa_supplicant( 5909): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5909): p2p_ssid_postfix='-Android_d8c3'
,D/wpa_supplicant( 5909): persistent_reconnect=1
D/wpa_supplicant( 5909): key_mgmt_offload=1
I/wpa_supplicant( 5909): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 5909): nl80211: RFKILL status not available
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:4,
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 5909): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 5909): nl80211: Using driver-based roaming
D/wpa_supplicant( 5909): nl80211: TDLS supported
D/wpa_supplicant( 5909): nl80211: TDLS external setup
D/wpa_supplicant( 5909): nl80211: Supports Probe Response offload in AP mode
W/ContextImpl( 5072): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
,D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
,D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
,D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
,D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
,D/wpa_supplicant( 5909): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5909): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5909): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 5909): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 5909): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 5909): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 5909): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 5909): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7b68170
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=0104,
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=040a
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=040b
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=040c
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=040d
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=090a
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=090b
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=090c
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=090d
,D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=0409506f9a09
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=7f506f9a09
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=0801
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=040e
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=06
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=0a07
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=0a11
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b68170 match=0a1a
D/wpa_supplicant( 5909): netlink: Operstate: ifindex=23 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5909): nl80211: driver param='use_multi_chan_concurrent=1',
D/wpa_supplicant( 5909): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 5909): htc_wext_command_init +
E/wpa_supplicant( 5909): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 5909): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5909): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5909): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
,D/wpa_supplicant( 5909): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  895): interfaceLinkStateChanged p2p0, false
D/Tethering(  895): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  895): interfaceLinkStateChanged p2p0, false
,D/Tethering(  895): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/A2dpStateMachine( 5854): Enter Disconnected: -2
,D/HidService( 5854): Received start request. Starting profile...
D/BluetoothAdapterService( 5854): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d2675e
D/HealthService( 5854): Received start request. Starting profile...
D/TetherSettings( 5072): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5072): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5072): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5072): Cust_ConnectToPC   : spcsc>false
D/        ( 5072): Cust_ConnectToPC   : IPT>true,
D/        ( 5072): Cust_ConnectToPC   : Singel_USB>false
D/BluetoothAdapterService( 5854): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d2675e
D/PanService( 5854): Received start request. Starting profile...
D/HtcBtWidget_BTWidgetProvider( 5890): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5890): updateWidget(context) for widget: 
W/Settings( 5072): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PanService( 5854): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 5854): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d2675e
E/SmartNS_Utility( 5072): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5072): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false,
D/SmartNS_NSReceiver( 5072): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/BtGatt.DebugUtils( 5854): handleDebugAction() action=null
D/BtGatt.GattService( 5854): Received start request. Starting profile...
D/BtGatt.GattService( 5854): start()
D/BtGatt.AdvertiseManager( 5854): advertise manager created
I/QuickSettingWifi( 1130): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
,D/BluetoothAdapter( 1130): 241541550: getState(). Returning 11,
I/QuickSettingMiniLite( 1130): updateLiteState:no connect device!
I/ActivityManager(  895): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/com.htc.videohub.engine.LiteLRBroadcastReceiver: pid=5925 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/BluetoothAdapterService( 5854): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39d2675e
,I/SmartNS_Utility( 5072): setISNotification
D/SmartNS_Utility( 5072): usb_cable_connect = 1
D/SmartNS_Utility( 5072): usb_denied = 0
I/SmartNS_PSService( 5072): usb notificaiton:true
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
I/ActionCombine( 5072): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/BluetoothAdapter( 1445): 467251658: getState(). Returning 11
W/BluetoothHeadset( 1445): Proxy not attached to service
I/HeadsetPhoneState( 5854): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 5854): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 5854): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5854): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5854): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 5854): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bt-btu  ( 5854): btu_task pending for preload complete event
D/BluetoothHeadset( 1445): java.lang.Throwable
D/BluetoothHeadset( 1445): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1445): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:652)
D/BluetoothHeadset( 1445): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1445): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1445): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1445): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1445): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
D/BluetoothHeadset( 1445): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1445): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1445): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
D/BluetoothHeadset( 1445): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,I/RemoteViews( 1130): reapply : com.android.settings 1 36
,D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/qcom-bluetooth( 5947): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
D/SmartNS_Utility( 5072): usb_cable_connect = 1
D/SmartNS_Utility( 5072): usb_denied = 0
I/SmartNS_PSService( 5072): usb notificaiton:true
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_NSReceiver( 5072): Tethered state change:false isNSOpening:false,
,D/TetherSettings( 5072): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
W/ResourcesManager( 5925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/        ( 5072): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5072): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5072): Cust_ConnectToPC   : spcsc>false
D/        ( 5072): Cust_ConnectToPC   : IPT>true
D/        ( 5072): Cust_ConnectToPC   : Singel_USB>false
D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
W/ResourceType( 5925): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
W/Settings( 5072): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5072): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5072): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 5072): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5072): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/RemoteViews( 1130): reapply : com.android.settings 0 36,
,I/wpa_supplicant( 5909): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 5909):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 5909):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 5909):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 5909): nl80211: Flush PMKIDs
D/wpa_supplicant( 5909): p2p0: State: DISCONNECTED -> INACTIVE
I/SmartNS_Utility( 5072): setISNotification
D/SmartNS_Utility( 5072): usb_cable_connect = 1
D/SmartNS_Utility( 5072): usb_denied = 0
I/SmartNS_PSService( 5072): usb notificaiton:true
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartNS_Utility( 5072): usb_cable_connect = 1
D/SmartNS_Utility( 5072): usb_denied = 0
D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/SmartNS_PSService( 5072): usb notificaiton:true
,E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1130): reapply : com.android.settings 0 36
I/qcom-bluetooth( 5954): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 5072): Tethered state change:false isNSOpening:false
I/qcom-bluetooth( 5955): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5957): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
I/RemoteViews( 1130): reapply : com.android.settings 1 36,
,D/wpa_supplicant( 5909): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 5909): TDLS: Driver uses external link setup
D/wpa_supplicant( 5909): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,I/qcom-bluetooth( 5958): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
D/wpa_supplicant( 5909): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 5909): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 5909): nl80211: Skip set_supp_port(unauthorized) while not associated
,D/wpa_supplicant( 5909): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 5909): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 5909): EAP: EAP entering state DISABLED
D/wpa_supplicant( 5909): Using existing control interface directory.
D/wpa_supplicant( 5909): P2P: Add operating class 81
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
,D/wpa_supplicant( 5909): P2P: Own listen channel: 81:6
,I/wpa_supplicant( 5909): set country (DE) from /data/misc/wifi/countryID.conf,
,I/wpa_supplicant( 5909): Get_p2p_auto_channel: Auto country group 1: ch36,
I/ActivityManager(  895): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=5960 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a
D/wpa_supplicant( 5909): P2P: Get_p2p_auto_channel: op_channel = 36, op_reg_class = 116
I/ActivityManager(  895): Killing 5459:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/wpa_supplicant( 5909): P2P: initialized
I/ActivityManager(  895): Recipient 5459
D/wpa_supplicant( 5909): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 5909): P2P: cli_channels:
D/wpa_supplicant( 5909): p2p0: Added interface p2p0
D/wpa_supplicant( 5909): p2p0: State: INACTIVE -> DISCONNECTED
,D/wpa_supplicant( 5909): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5909): netlink: Operstate: ifindex=23 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5909): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 5909): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5909): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5909): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 5909): disable_scan_offload=1
D/wpa_supplicant( 5909): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 5909): update_config=1
D/wpa_supplicant( 5909): uuid=12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 5909): device_name='htc_europe'
D/wpa_supplicant( 5909): manufacturer='HTC'
D/wpa_supplicant( 5909): model_name='HTC One_M8'
D/wpa_supplicant( 5909): model_number='HTC One_M8'
D/wpa_supplicant( 5909): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 5909): hs20=1
D/wpa_supplicant( 5909): interworking=1
D/wpa_supplicant( 5909): external_sim=1
D/wpa_supplicant( 5909): key_mgmt_offload=1
D/Process (  895): killProcessQuiet, pid=5459
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/qcom-bluetooth( 5959): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 5966): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/wpa_supplicant( 5909): Priority group 136,
D/wpa_supplicant( 5909):    id=3 ssid='NG7005g'
D/wpa_supplicant( 5909): Priority group 31
D/wpa_supplicant( 5909):    id=2 ssid='NG700'
D/wpa_supplicant( 5909): Priority group 5
D/wpa_supplicant( 5909):    id=1 ssid='Ozz'
D/wpa_supplicant( 5909): Priority group 2
D/wpa_supplicant( 5909):    id=0 ssid='huawei mate 7'
I/wpa_supplicant( 5909): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 5909): nl80211: RFKILL status not available
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 5909): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 5909): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 5909): nl80211: Using driver-based roaming
D/wpa_supplicant( 5909): nl80211: TDLS supported
D/wpa_supplicant( 5909): nl80211: TDLS external setup
,D/wpa_supplicant( 5909): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
,D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 5909): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
,D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
,D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5909): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 5909): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5909): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5909): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 5909): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 5909): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 5909): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 5909): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 5909): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7b79060
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0104
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040a
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040b
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040c
,D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040d
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=090a
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=090b
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=090c
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=090d
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0409506f9a09
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=7f506f9a09
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0801
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040e
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=06
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0a07
,D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0a11
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0a1a
D/Tethering(  895): interfaceLinkStateChanged wlan0, false
D/Tethering(  895): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 5909): netlink: Operstate: ifindex=22 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5909): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 5909): nl80211: Use separate P2P group interface
D/wpa_supplicant( 5909): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 5909): htc_wext_command_init +
I/wpa_supplicant( 5909): htc_wext_command_init -
,I/wpa_supplicant( 5909): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 5909): Don't set 00 to countryID.conf
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 5909): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5909): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 5909): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5909): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5909): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
,D/wpa_supplicant( 5909): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5909): P2P: Add operating class 81
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 5909): P2P: Update channel list
D/wpa_supplicant( 5909): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 5909): P2P: cli_channels:
D/wpa_supplicant( 5909): p2p0: Updating hw mode
D/wpa_supplicant( 5909): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5909): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
,D/wpa_supplicant( 5909): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5909): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5909): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5909): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
,D/wpa_supplicant( 5909): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5909): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
,I/ActivityManager(  895): Killing 4391:com.google.android.gms.wearable/u0a25 (adj 15): empty #17,
D/Process (  895): killProcessQuiet, pid=4391
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/qcom-bluetooth( 5980): /system/etc/init.qcom.bt.bluedroid.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 50:2e:6c:ac:21:50 ,
,I/qcom-bluetooth( 5981): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** ,
,I/ActivityManager(  895): Recipient 4391,
,I/wpa_supplicant( 5909): wapi_supplicant_init: Init WAI packet wlan0
,D/wpa_supplicant( 5909):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 5909):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 5909):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5909): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 5909): nl80211: Flush PMKIDs
,D/Process (  895): killProcessQuiet, pid=5459,
W/libprocessgroup(  895): failed to open /acct/uid_10013/pid_5459/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Process (  895): killProcessQuiet, pid=4391
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  895): failed to open /acct/uid_10025/pid_4391/cgroup.procs: No such file or directory
,D/BluetoothMasReceiver( 5854): Bluetooth STATE CHANGED to 11
,V/BluetoothSapReceiver( 5854): SapReceiver onReceive 
,V/BluetoothSapReceiver( 5854): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 5854):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 5854): startService = false
D/AuthorizationBluetoothService( 1753): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HtcWiFiWidget_WiFiWidgetProvider( 5960): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 5960): updateWidget(context) for widget: 
,I/ActivityManager(  895): Killing 5030:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17
,D/Process (  895): killProcessQuiet, pid=5030
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  895): Recipient 5030
,D/wpa_supplicant( 5909): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 5909): TDLS: Driver uses external link setup
D/wpa_supplicant( 5909): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5909): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 5909): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 5909): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 5909): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 5909): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 5909): EAP: EAP entering state DISABLED
D/wpa_supplicant( 5909): Using existing control interface directory.
I/wpa_supplicant( 5909): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 5909): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 5909): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5909): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
,D/wpa_supplicant( 5909): nl80211: Regulatory information - country=DE,
D/wpa_supplicant( 5909): nl80211: 2400-2483 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
D/wpa_supplicant( 5909): nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5909): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5909): P2P: Add operating class 81
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5909): P2P: Add operating class 115
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5909): P2P: Add operating class 116
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5909): P2P: Add operating class 117
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5909): P2P: Update channel list
D/wpa_supplicant( 5909): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5909): P2P: cli_channels:
D/wpa_supplicant( 5909): p2p0: Updating hw mode
D/wpa_supplicant( 5909): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5909): nl80211: 2400-2483 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
D/wpa_supplicant( 5909): nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5909): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 5909): Auto country group 1: ch36
D/wpa_supplicant( 5909): wlan0: Added interface wlan0
D/wpa_supplicant( 5909): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 5909): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5909): netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5909): random: Got 16/20 bytes from /dev/random
D/wpa_supplicant( 5909): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_895-2\x00
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=23 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=23 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5909): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 5909): nl80211: Regulatory domain change
D/wpa_supplicant( 5909):  * initiator=1
D/wpa_supplicant( 5909):  * type=0
D/wpa_supplicant( 5909):  * alpha2=DE
D/wpa_supplicant( 5909): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5909): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 5909): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5909): nl80211: 2400-2483 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
D/wpa_supplicant( 5909): nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5909): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5909): P2P: Add operating class 81
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5909): P2P: Add operating class 115
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5909): P2P: Add operating class 116
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5909): P2P: Add operating class 117
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=2): 28 30
D/PMS     (  895): acquireWL(2ad2164c):, PARTIAL_WAKE_LOCK  WifiSuspend 0x1 895 1000 null
D/wpa_supplicant( 5909): P2P: Update channel list
D/wpa_supplicant( 5909): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5909): P2P: cli_channels:
D/wpa_supplicant( 5909): p2p0: Updating hw mode
D/wpa_supplicant( 5909): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5909): nl80211: 2400-2483 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
D/wpa_supplicant( 5909): nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5909): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  895): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  895): handleMessage: new destination call exit/enter
D/WifiDisplayAdapter(  895): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  895):     Client/Owner: Client
D/WifiDisplayAdapter(  895):     GroupId: 
D/WifiDisplayAdapter(  895):     Passphrase: 
D/WifiDisplayAdapter(  895):     SessionId: 0
D/WifiDisplayAdapter(  895):     IP Address: }
E/WifiStateMachine(  895): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  895): invokeExitMethods: InitialState
E/WifiStateMachine(  895): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  895): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  895): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131144
E/WifiStateMachine(  895): processMsg: SupplicantStartingState
E/WifiStateMachine(  895):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  895): deferMessage: msg=131144
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131085
E/WifiStateMachine(  895): processMsg: SupplicantStartingState
E/WifiStateMachine(  895):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  895): deferMessage: msg=131085
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131149
E/WifiStateMachine(  895): processMsg: SupplicantStartingState
E/WifiStateMachine(  895):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  895): processMsg: DefaultState
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiStateMachine(  895):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiMonitor(  895): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiStateMachine(  895): setSuspendOptimizations: 2 true
E/WifiStateMachine(  895): mSuspendOptNeedsDisabled 0
E/WifiMonitor(  895): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131101
E/WifiStateMachine(  895): processMsg: SupplicantStartingState
E/WifiStateMachine(  895):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  895): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  895): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131101
E/WifiStateMachine(  895): processMsg: SupplicantStartingState
E/WifiStateMachine(  895):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  895): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  895): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=147457
E/WifiStateMachine(  895): processMsg: SupplicantStartingState
E/WifiStateMachine(  895):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiStateMachine(  895): Supplicant connection established
E/WifiStateMachine(  895): setWifiState: enabled
E/WifiStateMachine(  895): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  895):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=true state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 5909): SET_SCREEN_ON:Off
I/wpa_supplicant( 5909): htc_wext_set_keepalive +
I/wpa_supplicant( 5909): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 5909): getPrivFuncNum +	
I/wpa_supplicant( 5909): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 5909): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 5909): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 5909): get_ip_address source addr = d4c4f9b6
I/wpa_supplicant( 5909): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 5909): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  895): startHal
E/wifi    (  895): getStaticLongField sWifiHalHandle 0x9fc1581c
I/WifiNative-HAL(  895): Could not start hal
E/WifiStateMachine(  895): setScanAlarm false period 10000 initial delay 0
D/WirelessDisplayService(  895): getMirrorDisplayStatus:falsecurState:1
D/WifiStateMachine(  895): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  895): handleScreenStateChanged Exit: false
D/wpa_supplicant( 5909): wlan0: Starting delayed sched scan
D/wpa_supplicant( 5909): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 5909): wpa_supplicant_scan enter
D/wpa_supplicant( 5909): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 5909): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 5909): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 5909): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 5909): WPS:  * Request Type
D/wpa_supplicant( 5909): WPS:  * Config Methods (4288)
D/wpa_supplicant( 5909): WPS:  * UUID-E
D/wpa_supplicant( 5909): WPS:  * Primary Device Type
D/wpa_supplicant( 5909): WPS:  * RF Bands (3)
D/wpa_supplicant( 5909): WPS:  * Association State
D/wpa_supplicant( 5909): WPS:  * Configuration Error (0)
D/wpa_supplicant( 5909): WPS:  * Device Password ID (0)
D/wpa_supplicant( 5909): WPS:  * Manufacturer
D/wpa_supplicant( 5909): WPS:  * Model Name
D/wpa_supplicant( 5909): WPS:  * Model Number
D/wpa_supplicant( 5909): WPS:  * Device Name
D/wpa_supplicant( 5909): WPS:  * Version2 (0x20)
D/wpa_supplicant( 5909): P2P: * P2P IE header
D/wpa_supplicant( 5909): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 5909): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 5909): wlan0: Add radio work 'scan'@0xb7b7c158
D/wpa_supplicant( 5909): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 5909): wlan0: Starting radio work 'scan'@0xb7b7c158 after 0.000026 second wait
D/wpa_supplicant( 5909): wlan0: nl80211: scan request
D/wpa_supplicant( 5909): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 5909): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 5909): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 5909): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 5909): wlan0: Own scan request started a scan in 0.000055 seconds
I/wpa_supplicant( 5909): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  895): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  895): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
,D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  895): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  895): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/Process (  895): killProcessQuiet, pid=5030
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  895): failed to open /acct/uid_10089/pid_5030/cgroup.procs: No such file or directory
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER MACADDR'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/WIFI_ICON( 1130): updateWifiState: WIFI_STATE_CHANGED enabled
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET update_config 1'
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 5909): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 5909): update_config=1
D/wpa_supplicant( 5909): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WifiConfigStore(  895): Loading config and enabling all networks 
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 5909): wlan0: Control interface command 'LIST_NETWORKS'
D/WirelessDisplayService(  895): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/IntentController( 1130): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/PMS     (  895): acquireWL(906d695): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1658 10025 WorkSource{1000 android},
D/WifiService(  895): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3988f3aa}
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid",
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 bssid',
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/WifiDisplayAdapter(  895): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  895):     Client/Owner: Client
D/WifiDisplayAdapter(  895):     GroupId: 
D/WifiDisplayAdapter(  895):     Passphrase: 
D/WifiDisplayAdapter(  895):     SessionId: 0
D/WifiDisplayAdapter(  895):     IP Address: }
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='priority'
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/PMS     (  895): acquireWL(1909bb9b): PARTIAL_WAKE_LOCK  *alarm* 0x1 895 1000 WorkSource{10025}
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
V/AlarmManager(  895): sending alarm PendingIntent{15304b38: PendingIntentRecord{21cb4711 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=133364, Int=0
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/PMS     (  895): releaseWL(1909bb9b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10025}
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
,D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='psk'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg",
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg',
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_PSK key null,
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_PSK_HEX key null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert',
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT index null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/HtcWiFiWidget_WiFiWidgetProvider( 5960): onWiFiStateChanged() for widget: 
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT as cert null
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT user cert null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/HtcWiFiWidget_WiFiWidgetProvider( 5960): updateWidget(context) for widget: 
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 eap'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='identity',
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 password'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='engine'
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key",
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  895): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore(  895): readNetworkVariableFromSupplicantFile ssid=["huawei mate 7"] key=psk
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 ssid"
,D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 ssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='ssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 bssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 bssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='bssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 priority"
,D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 priority'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='priority'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 scan_ssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 scan_ssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='scan_ssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_tx_keyidx"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wep_tx_keyidx'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wep_tx_keyidx'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_key0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wep_key0'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wep_key0'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_key1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wep_key1'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wep_key1'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_key2"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wep_key2'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wep_key2'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_key3"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wep_key3'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wep_key3'
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 psk"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 psk'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='psk'
D/wpa_supplicant( 5909): Do not allow key_data field to be exposed
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 proto"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 proto'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='proto'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 key_mgmt"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 key_mgmt'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='key_mgmt'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 auth_alg"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 auth_alg'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='auth_alg'
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 pairwise"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 pairwise'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='pairwise'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 group"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 group'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='group'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_psk"
,D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wapi_psk'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wapi_psk'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_PSK key null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_psk_hex"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wapi_psk_hex'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wapi_psk_hex'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_PSK_HEX key null,
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wapi_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wapi_cert'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT index null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_as_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wapi_as_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wapi_as_cert'
,D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT as cert null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_user_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 wapi_user_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='wapi_user_cert'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT user cert null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 eap"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 eap'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='eap'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 phase2"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 phase2'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='phase2'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 identity"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 identity'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='identity'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 anonymous_identity"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 anonymous_identity'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='anonymous_identity'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 password"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 password'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='password'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 client_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 client_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='client_cert'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 ca_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 ca_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='ca_cert'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 subject_match"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 subject_match'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='subject_match'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 engine"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 engine'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='engine'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 engine_id"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 engine_id'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='engine_id'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 key_id"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 key_id'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='key_id'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 private_key"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 1 private_key'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=1 name='private_key'
E/WifiConfigStore(  895): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore(  895): readNetworkVariableFromSupplicantFile ssid=["Ozz"] key=psk
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 ssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 ssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='ssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 bssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 bssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='bssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 priority"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 priority'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='priority'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 scan_ssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 scan_ssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='scan_ssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_tx_keyidx"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wep_tx_keyidx'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wep_tx_keyidx'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wep_key0'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wep_key0'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wep_key1'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wep_key1'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key2"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wep_key2'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wep_key2'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key3"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wep_key3'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wep_key3'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 psk"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 psk'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='psk'
D/wpa_supplicant( 5909): Do not allow key_data field to be exposed
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 proto"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 proto'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='proto'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 key_mgmt"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 key_mgmt'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='key_mgmt'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 auth_alg"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 auth_alg'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='auth_alg'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 pairwise"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 pairwise'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='pairwise'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 group"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 group'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='group'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_psk"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wapi_psk'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wapi_psk'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_PSK key null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_psk_hex"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wapi_psk_hex'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wapi_psk_hex'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_PSK_HEX key null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wapi_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wapi_cert'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT index null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_as_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wapi_as_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wapi_as_cert'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT as cert null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_user_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 wapi_user_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='wapi_user_cert'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT user cert null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 eap"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 eap'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='eap'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 phase2"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 phase2'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='phase2'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 identity"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 identity'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='identity'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 anonymous_identity"
,D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 anonymous_identity'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='anonymous_identity'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 password"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 password',
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='password'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 client_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 client_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='client_cert'
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 ca_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 ca_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='ca_cert'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 subject_match"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 subject_match'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='subject_match'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 engine"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 engine'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='engine'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 engine_id"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 engine_id'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='engine_id'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 key_id"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 key_id'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='key_id'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 private_key"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 2 private_key'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=2 name='private_key'
E/WifiConfigStore(  895): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore(  895): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 ssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 ssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='ssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 bssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 bssid'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='bssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 priority"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 priority'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='priority'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 scan_ssid"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 scan_ssid'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='scan_ssid'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_tx_keyidx"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wep_tx_keyidx'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wep_tx_keyidx'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_key0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wep_key0'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wep_key0'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_key1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wep_key1'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wep_key1'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_key2"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wep_key2'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wep_key2'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_key3"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wep_key3'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wep_key3'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 psk"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 psk'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='psk'
D/wpa_supplicant( 5909): Do not allow key_data field to be exposed
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 proto"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 proto'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='proto'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 key_mgmt"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 key_mgmt'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='key_mgmt'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 auth_alg"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 auth_alg'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='auth_alg'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 pairwise"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 pairwise'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='pairwise'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 group"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 group'
,D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='group'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_psk"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wapi_psk'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wapi_psk'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_PSK key null
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_psk_hex"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wapi_psk_hex'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wapi_psk_hex'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_PSK_HEX key null
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wapi_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wapi_cert'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT index null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_as_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wapi_as_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wapi_as_cert'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT as cert null
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_user_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 wapi_user_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='wapi_user_cert'
D/WifiConfigStore(  895): ***WAPI : readNetworkVariables WAPI_CERT user cert null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 eap"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 eap'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='eap'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 phase2"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 phase2'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='phase2'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 identity"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 identity'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='identity'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 anonymous_identity"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 anonymous_identity'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='anonymous_identity'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 password"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 password'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='password'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 client_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 client_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='client_cert'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 ca_cert"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 ca_cert'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='ca_cert'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 subject_match"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 subject_match'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='subject_match'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 engine"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 engine'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='engine'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 engine_id"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 engine_id'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='engine_id'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 key_id"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 key_id'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='key_id'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 private_key"
D/wpa_supplicant( 5909): wlan0: Control interface command 'GET_NETWORK 3 private_key'
D/wpa_supplicant( 5909): CTRL_IFACE: GET_NETWORK id=3 name='private_key'
E/WifiConfigStore(  895): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore(  895): readNetworkVariableFromSupplicantFile ssid=["NG7005g"] key=psk
E/WifiConfigStore(  895): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name htc_europe"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET device_name htc_europe'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'device_name'='htc_europe'
D/wpa_supplicant( 5909): device_name='htc_europe'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 5909): ,CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 5909): manufacturer='HTC'
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One_M8"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET model_name HTC One_M8'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'model_name'='HTC One_M8'
D/wpa_supplicant( 5909): model_name='HTC One_M8'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One_M8"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET model_number HTC One_M8'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'model_number'='HTC One_M8'
D/wpa_supplicant( 5909): model_number='HTC One_M8'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 5909): config_methods='physical_display virtual_push_button'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,I/QuickSettingWifi( 1130): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
E/WifiStateMachine(  895): transitionTo: destState=DriverStartedState
,E/WifiStateMachine(  895): handleMessage: new destination call exit/enter
E/WifiStateMachine(  895): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  895): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  895): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  895): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  895): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  895): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SCAN_INTERVAL 15',
D/wpa_supplicant( 5909): wlan0: Setting scan interval: 15 sec
D/WifiNative-HAL(  895): Setting external_sim to 1
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 5909): external_sim=1
D/WifiStateMachine(  895): Setting OUI to DA-A1-19
I/WifiNative-HAL(  895): startHal
,E/wifi    (  895): getStaticLongField sWifiHalHandle 0x9fc1583c
I/WifiNative-HAL(  895): Could not start hal
D/WifiService(  895): New client listening to asynchronous messages
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 5909): wlan0: Control interface command 'STA_AUTOCONNECT 0'
,E/WifiStateMachine(  895): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  895): Driverstarted State enter
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 4096
E/WifiStateMachine(  895): DriverStartedState call setCountryCode()
E/WifiStateMachine(  895): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 0,
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 4096
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 4096
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER RXFILTER-START',
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 4096
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 4096
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 4096
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER RXFILTER-START'
,D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 4096
D/WISPrService( 5072): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  895): setDhcpActive: false
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 5909): wlan0: Control interface command 'STATUS'
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=3 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  895): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange(): SSID,
D/WifiMonitor(  895): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
E/WifiStateMachine(  895): transitionTo: destState=DisconnectedState
E/WifiTrafficPoller(  895): ADD_CLIENT: 8
D/WISPrService( 5072): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/native  (  895): do suspend true,
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 4096
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 5909): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/WifiStateMachine(  895): Driverstarted State enter done
E/WifiStateMachine(  895): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  895): moveDeferredMessageAtFrontOfQueue; what=131144
,E/WifiStateMachine(  895): handleMessage: new destination call exit/enter
E/WifiStateMachine(  895): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  895): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  895): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  895): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  895): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  895): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  895): DisconnectedState call setCountryCode()
E/WifiStateMachine(  895):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 5909): wlan0: Cancelling scan request
D/wpa_supplicant( 5909): wlan0: nl80211: sched_scan request
,D/WifiScanningService(  895): SCAN_AVAILABLE : 3
D/RttService(  895): SCAN_AVAILABLE : 3
D/WifiScanningService(  895): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  895): startHal
D/RttService(  895): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1130): receive.wifiConnect:false wifiAPname:null elapse:1,
,D/wpa_supplicant( 5909): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec,
,D/wpa_supplicant( 5909): Wireless event: cmd=0x8b19 len=8
D/PMS     (  895): releaseWL(2ad2164c): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5909): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 5909): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 5909): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 5909): wlan0: nl80211: New scan results available
,D/wpa_supplicant( 5909): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 5909): wlan0: Event SCAN_RESULTS (3) received
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 5909): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 5909): wlan0: Scan completed in 0.161789 seconds
,D/wpa_supplicant( 5909): nl80211: Received scan results (0 BSSes)
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T],
D/wpa_supplicant( 5909): wlan0: BSS: Start scan result update 1
,D/wpa_supplicant( 5909): BSS: last_scan_res_used=0/0,
,D/wpa_supplicant( 5909): wlan0: New scan results available (own=1 ext=0)
D/WifiDisplayController(  895): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/wpa_supplicant( 5909): wlan0: Radio work 'scan'@0xb7b7c158 done in 0.162151 seconds
D/WifiDisplayController(  895): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/wpa_supplicant( 5909): wlan0: No suitable network found
D/WifiDisplayController(  895): mWfdEnabled :false, networkInfo.isConnected() :false
D/wpa_supplicant( 5909): wlan0: Setting scan request: 15.000000 sec,
D/WifiDisplayAdapter(  895): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  895):     Client/Owner: Client
D/WifiDisplayAdapter(  895):     GroupId: 
D/WifiDisplayAdapter(  895):     Passphrase: 
D/WifiDisplayAdapter(  895):     SessionId: 0
D/WifiDisplayAdapter(  895):     IP Address: }
D/wpa_supplicant( 5909): wlan0: Cancelling sched scan
D/WifiDisplayController(  895): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_d8c3
D/WifiDisplayController(  895):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiDisplayController(  895):  primary type: 10-0050F204-5
D/WifiDisplayController(  895):  secondary type: null
D/WifiDisplayController(  895):  wps: 0
D/WifiDisplayController(  895):  grpcapab: 0
,D/WifiDisplayController(  895):  devcapab: 0
D/WifiDisplayController(  895):  status: 3
D/WifiDisplayController(  895):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  895):  WFD CtrlPort: 0
D/WifiDisplayController(  895):  WFD MaxThroughput: 0
D/wpa_supplicant( 5909): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 5909): wlan0: Cancelling scan request
,D/wpa_supplicant( 5909): p2p0: Updating scan results from sibling
D/wpa_supplicant( 5909): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 5909): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 5909): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 5909): p2p0: New scan results available (own=0 ext=0)
,D/wpa_supplicant( 5909): p2p0: No suitable network found
D/wpa_supplicant( 5909): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 5909): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 5909): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/wifi    (  895): getStaticLongField sWifiHalHandle 0x9ad5897c
I/WifiNative-HAL(  895): Could not start hal,
E/WifiScanningService(  895): could not start HAL
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131144
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131085
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=4 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  895): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/Tethering(  895): interfaceLinkStateChanged wlan0, false
D/Tethering(  895): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  895): processMsg: DriverStartedState
D/WifiMonitor(  895): Dropping event because (p2p0) is stopped
E/WifiStateMachine(  895):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131154
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
,E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  895): processMsg: DriverStartedState
E/WifiStateMachine(  895):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
E/WifiStateMachine(  895):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  895): handleMessage: X
,E/WifiStateMachine(  895): handleMessage: E msg.what=131158
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState CMD_SET_SUSPEND_OPT_ENABLED 1 0
E/WifiStateMachine(  895): processMsg: DriverStartedState
E/WifiStateMachine(  895):  DriverStartedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
E/WifiStateMachine(  895): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/WifiStateMachine(  895): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg,
E/native  (  895): do suspend true
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 4096
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=147462
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=135077  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=135078  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiMonitor(  895): startMonitoring(p2p0) with mConnected = true
,E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 1
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  895): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 5909): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 5909): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 5909): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 5909): persistent_reconnect=1
D/wpa_supplicant( 5909): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5909): P2P: New SSID postfix: -Android_d8c3
W/WifiHW  (  895): QCOM Debug wifi_send_command "SET device_name Android_d8c3"
D/wpa_supplicant( 5909): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 64 38 63 33
D/wpa_supplicant( 5909): GLOBAL_CTRL_IFACE SET 'device_name'='Android_d8c3'
D/wpa_supplicant( 5909): p2p0: Control interface command 'SET device_name Android_d8c3'
,D/wpa_supplicant( 5909): CTRL_IFACE SET 'device_name'='Android_d8c3'
D/wpa_supplicant( 5909): device_name='Android_d8c3'
W/WifiHW  (  895): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_d8c3"
D/wpa_supplicant( 5909): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 64 38 ...
D/wpa_supplicant( 5909): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_d8c3'
D/wpa_supplicant( 5909): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_d8c3'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_d8c3'
D/wpa_supplicant( 5909): p2p_ssid_postfix='-Android_d8c3'
D/wpa_supplicant( 5909): P2P: New SSID postfix: -Android_d8c3
W/WifiHW  (  895): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 5909): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 5909): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 5909): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'device_type'='10-0050F204-5'
W/WifiHW  (  895): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 5909): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
,D/wpa_supplicant( 5909): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5909): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5909): config_methods='virtual_push_button physical_display keypad'
W/WifiHW  (  895): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 5909): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 5909): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 5909): Single channel concurrency preference: sta
D/WifiNative-HAL(  895): p2pGetDeviceAddress
W/WifiHW  (  895): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 5909): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-HAL(  895): p2pGetDeviceAddress returning 02:ee:bd:dd:33:d2
D/WISPrService( 5072): >>>>>WISPrService start isConnected = false<<<<<
V/AudioService(  895): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  895):     Client/Owner: Client
V/AudioService(  895):     GroupId: 
V/AudioService(  895):     Passphrase: 
V/AudioService(  895):     SessionId: 0
V/AudioService(  895):     IP Address: }
D/HtcEffectManagerBase(  895): onEventChanged id=5 status=false
,D/HtcEffectManager(  895): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  895): convertEffect before=902
D/HtcEffectManager(  895): convertEffect after=902
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131323
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  895): processMsg: DriverStartedState
E/WifiStateMachine(  895):  DriverStartedState what:131323 0 0,
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
E/WifiStateMachine(  895):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState what:131323 0 0
E/WifiStateMachine(  895): setOperatorSSID enter
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131143
E/WifiStateMachine(  895): processMsg: DisconnectedState
,D/WISPrService( 5072): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  895):  DisconnectedState CMD_START_SCAN 10025 0 ic=0 proc(ms):123 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:444463954] from screen [on:0 period:444463954]
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  895): processMsg: ConnectModeState
W/WifiHW  (  895): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 5909): p2p0: Control interface command 'P2P_FLUSH'
,I/wpa_supplicant( 5909): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 5909): P2P: Stopping find
D/wpa_supplicant( 5909): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 5909): P2P: State IDLE -> IDLE
D/wpa_supplicant( 5909): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 5909): P2P: Stopping find
D/wpa_supplicant( 5909): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 5909): P2P: State IDLE -> IDLE
D/wpa_supplicant( 5909): wpa_driver_set_ap_wps_p2p_ie: Entry
E/WifiStateMachine(  895):  ConnectModeState CMD_START_SCAN 10025 0 ic=0 proc(ms):124 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:444463956]
E/WifiStateMachine(  895): processMsg: DriverStartedState
W/WifiHW  (  895): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
,D/wpa_supplicant( 5909): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 5909): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  895): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 5909): p2p0: Control interface command 'LIST_NETWORKS'
W/WifiHW  (  895): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/wpa_supplicant( 5909): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 5909): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5909): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5909): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated,
D/wpa_supplicant( 5909): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 5909): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 5909): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  895):  DriverStartedState CMD_START_SCAN 10025 0 ic=0 proc(ms):127 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:444463958]
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 5909): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 5909): wpa_supplicant_scan enter
,D/wpa_supplicant( 5909): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 5909): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 5909): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 5909): WPS:  * Request Type
D/wpa_supplicant( 5909): WPS:  * Config Methods (4288)
D/wpa_supplicant( 5909): WPS:  * UUID-E
D/wpa_supplicant( 5909): WPS:  * Primary Device Type
D/wpa_supplicant( 5909): WPS:  * RF Bands (3)
D/wpa_supplicant( 5909): WPS:  * Association State
,D/wpa_supplicant( 5909): WPS:  * Configuration Error (0)
D/wpa_supplicant( 5909): WPS:  * Device Password ID (0)
D/wpa_supplicant( 5909): WPS:  * Manufacturer
D/wpa_supplicant( 5909): WPS:  * Model Name
D/wpa_supplicant( 5909): WPS:  * Model Number
D/wpa_supplicant( 5909): WPS:  * Device Name
D/wpa_supplicant( 5909): WPS:  * Version2 (0x20)
D/wpa_supplicant( 5909): P2P: * P2P IE header
,D/wpa_supplicant( 5909): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 5909): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 5909): wlan0: Add radio work 'scan'@0xb7b7d230
D/wpa_supplicant( 5909): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 5909): wlan0: Starting radio work 'scan'@0xb7b7d230 after 0.000021 second wait
D/wpa_supplicant( 5909): wlan0: nl80211: scan request
D/wpa_supplicant( 5909): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 5909): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 5909): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 5909): wlan0: Event SCAN_STARTED (49) received,
D/wpa_supplicant( 5909): wlan0: Own scan request started a scan in 0.000047 seconds
I/wpa_supplicant( 5909): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WifiStateMachine(  895): Wifi band: 0, ScanBroadCastCounter: 0
E/WifiMonitor(  895): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  895): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  895): [1,447,848,442,711 ms] noteScanStartWorkSource{1000} uid 10025
I/WifiNative-HAL(  895): startHal
E/wifi    (  895): getStaticLongField sWifiHalHandle 0x9fc157bc
I/WifiNative-HAL(  895): Could not start hal,
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131104
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState what:131104 0 0
W/Settings(  895): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 5909): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 5909): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131162
E/WifiStateMachine(  895): processMsg: DisconnectedState
,E/WifiStateMachine(  895):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  895): processMsg: ConnectModeState
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED disconnected,
E/WifiStateMachine(  895):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  895): processMsg: DriverStartedState
E/WifiStateMachine(  895):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  895): set frequency band 0
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER SETBAND 0'
,D/wpa_supplicant( 5909): SETBAND: 0
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 4096
D/wpa_supplicant( 5909): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5909): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 5909): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5909): nl80211: 2400-2483 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
D/wpa_supplicant( 5909): nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS),
D/wpa_supplicant( 5909): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
,D/wpa_supplicant( 5909): P2P: Add operating class 81
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5909): P2P: Add operating class 115
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5909): P2P: Add operating class 116
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5909): P2P: Add operating class 117
D/wpa_supplicant( 5909): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5909): P2P: Update channel list,
D/wpa_supplicant( 5909): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5909): P2P: cli_channels:
,D/wpa_supplicant( 5909): p2p0: Updating hw mode
D/wpa_supplicant( 5909): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5909): nl80211: 2400-2483 @ 40 MHz 20 mBm
D/wpa_supplicant( 5909): nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor),
D/wpa_supplicant( 5909): nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
D/wpa_supplicant( 5909): nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5909): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5909): nl80211: Added 802.11b mode based on 802.11g information
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  895): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN,
E/WifiMonitor(  895): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiStateMachine(  895): did set frequency band 0
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 5909): Ongoing scan action - reject new request
E/WifiStateMachine(  895): done set frequency band 0
D/WifiStateMachine(  895): [MLHD] enter handleMediaLinkEvent DriverStartedState,
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=147462
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 3 0 rt=135115  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  895): setDetailed state send new extra info0x
,E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 3 0 rt=135116  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=147461
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET pno 1'
,D/wpa_supplicant( 5909): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 5909): wlan0: Cancelling scan request
D/wpa_supplicant( 5909): wlan0: nl80211: sched_scan request
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 2
D/WISPrService( 5072): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5072): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1130): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 5909): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec,
D/wpa_supplicant( 5909): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 5909): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 5909): Wireless event: cmd=0x8b19 len=8
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5909): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 5909): wlan0: nl80211: New scan results available
D/wpa_supplicant( 5909): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
,D/wpa_supplicant( 5909): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 5909): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 5909): wlan0: Scan completed in 0.060107 seconds
D/wpa_supplicant( 5909): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 5909): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 5909): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 5909): wlan0: Scan-only results received
D/wpa_supplicant( 5909): wlan0: Radio work 'scan'@0xb7b7d230 done in 0.060444 seconds
,E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine(  895): processMsg: DriverStartedState
E/WifiStateMachine(  895):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
W/ContextImpl(  895): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:13935 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14100 com.android.server.wifi.WifiStateMachine.access$5400:265 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7908 
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
D/Tethering(  895): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  895):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
D/WifiStateMachine(  895): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 5909): wlan0: Control interface command 'LIST_DONGLES'
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=7 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  895): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/Tethering(  895): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  895): [1,447,848,442,773 ms] noteScanEnd WorkSource{1000}
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 5909): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WirelessDisplayService(  895): getDiscoveryDongleList
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=143371
E/WifiStateMachine(  895): processMsg: DisconnectedState
,D/WirelessDisplayService(  895): getDiscoveryDongleList,
D/WifiManager( 1658): getScanResults: Base Package Name=com.google.android.gms, uid=10025
E/WifiStateMachine(  895):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  895): processMsg: DriverStartedState
E/WifiStateMachine(  895):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
,E/WifiStateMachine(  895):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  895): handleMessage: X
,E/WifiStateMachine(  895): handleMessage: E msg.what=147461
E/WifiStateMachine(  895): processMsg: DisconnectedState
,E/WifiStateMachine(  895):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 dur:62 bcn=0
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 dur:62 bcn=0
E/WifiStateMachine(  895): processMsg: DriverStartedState,
E/WifiStateMachine(  895):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 dur:62 bcn=0
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
E/WifiStateMachine(  895):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 dur:62 bcn=0
,D/WifiStateMachine(  895): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 5909): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  895): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:13935 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14100 com.android.server.wifi.WifiStateMachine.access$5400:265 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7908 
,E/WifiStateMachine(  895): [1,447,848,442,780 ms] noteScanEnd no scan source
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  895): getDiscoveryDongleList
D/wpa_supplicant( 5909): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  895): handleMessage: X
,I/QuickSettingWifi( 1130): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=23 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP]),
D/Tethering(  895): interfaceLinkStateChanged p2p0, false
D/Tethering(  895): interfaceStatusChanged p2p0, false
,E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 5909): EAPOL: disable timer tick,
,I/bt-btu  ( 5854): btu_task received preload complete event,
,W/bt-l2cap( 5854): L2CAP - L2CA_Register() called for PSM: 0x0001
D/PMS     (  895): acquireWL(258c434d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5854 1002 null
W/bt-l2cap( 5854): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 5854): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 5854): L2CAP - L2CA_Register() called for PSM: 0x1487
D/bt-btm  ( 5854): btm_acl_device_down
D/bt-btm  ( 5854): btm_acl_reset_paging
D/bt-btm  ( 5854): btm_acl_set_discing
,I/bt-btm  ( 5854): btm_reset_complete,
I/bt-btm  ( 5854): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 5854): Start reading local supported commands
,D/bt-btm  ( 5854): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 5854): BTM reads next extended features page (1)
,D/bt-btm  ( 5854): BTM reads next extended features page (2)
D/bt-btm  ( 5854): BTM reached last extended features page (2)
D/bt-btm  ( 5854): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
,D/bt-btm  ( 5854): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
D/bt-btm  ( 5854): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 5854): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,D/bt-btm  ( 5854): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
I/bt-btm  ( 5854): btm_vendor_capability_vsc_cmpl_cback: status=255
D/bt-btm  ( 5854): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 5854): btm_read_ble_wl_size 
D/bt-btm  ( 5854): btm_read_white_list_size_complete 
D/bt-btm  ( 5854): btm_get_ble_buffer_size 
D/bt-btm  ( 5854): btm_read_ble_buf_size_complete 
D/bt-btm  ( 5854): btm_read_ble_local_supported_states 
D/bt-btm  ( 5854): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 5854): btm_read_ble_local_supported_features 
D/bt-btm  ( 5854): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 5854): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 5854): btm_decode_ext_features_page page: 0
D/bt-btm  ( 5854): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 5854): Local supported SCO packet types: 0x038f
I/bt-btm  ( 5854): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 5854):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 5854): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 5854): BTM_SetInquiryMode
I/bt-btm  ( 5854): BTM_SetPageScanType
I/bt-btm  ( 5854): BTM_SetInquiryScanType
D/bt-btm  ( 5854): btm_decode_ext_features_page page: 1
D/bt-btm  ( 5854): btm_decode_ext_features_page page: 2
W/bt-btm  ( 5854): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 5854): BTM_BleLoadLocalKeys
D/bt-btm  ( 5854): BTM_BleLoadLocalKeys
I/bt-btm  ( 5854): BTM_Sec: application registered
E/bt-btm  ( 5854): BTM_SecRegister:p_cb_info->p_le_callback == 0xaff79f79 
I/bt-btm  ( 5854): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 5854): SMP_Register state=0
E/bt-btm  ( 5854): BTM_SecRegister: btm_cb.api.p_le_callback = 0xaff79f79 
I/bt-btm  ( 5854): BTM_Sec: application registered
D/bt-btm  ( 5854): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 5854): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 5854): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 5854): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 5854): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 5854): BTM_RegBusyLevelNotif
I/bt-att  ( 5854): GATT_Register
D/bt-att  ( 5854): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 5854): allocated gatt_if=3
I/bt-att  ( 5854): GATT_StartIf gatt_if=3
D/bt-att  ( 5854): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5854): gatt_find_the_connected_bda found=0 found_idx=16
E/bt-btif ( 5854): Calling BTA_HhEnable
I/bt-btif ( 5854): BTA_MceEnable
E/bt-btif ( 5854): btif_storage_get_adapter_property service_mask:0x2140040
I/bt-btif ( 5854): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5854): Address is:50:2E:6C:AC:21:50
D/bt-btm  ( 5854): bta_dm_set_dev_name: name: HTC One_M8 
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btm  ( 5854): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 5854): BTM_AllocateSCN
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 5854): BTM_AllocateSCN
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btm  ( 5854): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5854):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5854):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5854):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5854):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/,bt-l2cap( 5854): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 5854): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5854):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5854):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 5854):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 5854):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5854):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5854):                : sec: 0x80, service name [] (up to 21 chars saved)
,W/bt-l2cap( 5854): L2CAP - L2CA_Register() called for PSM: 0x0017,
I/bt-btm  ( 5854): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
D/PMS     (  895): acquireWL(11354950): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5072 1000 null
I/bt-btm  ( 5854):                : sec: 0x2090, service name [] (up to 21 chars saved)
W/ContextImpl( 5072): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
I/bt-btm  ( 5854): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
,D/PMS     (  895): releaseWL(11354950): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
I/bt-btm  ( 5854):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/PMS     (  895): acquireWL(b9d9b5a): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5072 1000 null
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 5854): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 5854): A2D_AddRecord uuid: 110a
,I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
D/bt-avp  ( 5854): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:7
,I/bt-avp  ( 5854): AVRC_AddRecord uuid: 110e,
,I/bt-btm  ( 5854): Write Extended Inquiry Response to controller,
W/ContextImpl( 5072): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1862 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
I/bt-btm  ( 5854): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5854):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5854):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5854):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5854):                : sec: 0x80, service name [] (up to 21 chars saved),
,I/bt-btm  ( 5854): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
D/PMS     (  895): releaseWL(b9d9b5a): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
I/bt-btm  ( 5854):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5854):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 5854): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 5854): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 5854): GATT_Register
D/bt-att  ( 5854): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 5854): allocated gatt_if=4
I/bt-att  ( 5854): GATT_StartIf gatt_if=4
D/bt-att  ( 5854): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5854): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 5854): Scan Mode:21
D/BluetoothAdapterProperties( 5854): Discoverable Timeout:120
I/bt-btif ( 5854): BTA_JvEnable
I/bt-btif ( 5854): BTA_JvRegisterL2cCback
I/bt-btm  ( 5854): BTM_ReadConnectability
I/bt-btm  ( 5854): BTM_ReadDiscoverability
I/bt-btm  ( 5854): BTM_SetDiscoverability
I/bt-btm  ( 5854): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 5854): disc_mode 0002
D/bt-btm  ( 5854): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 5854): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 5854): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5854): BTM_SetConnectability
I/bt-btm  ( 5854): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5854): disc_mode 0002
I/bt-btm  ( 5854): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 5854): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 5854): BTM_SetDiscoverability
I/bt-btm  ( 5854): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5854): disc_mode 0000
I/bt-btm  ( 5854): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5854): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 5854): BTM_SetConnectability
I/bt-btm  ( 5854): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5854): disc_mode 0000
D/bt-btm  ( 5854): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 5854): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 5854): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 5854): bta_pan_co_init
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 5854): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5854):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5854):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btm  ( 5854): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5854):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5854): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5854):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btif ( 5854): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 5854): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5854): ScanMode =  21
D/BluetoothAdapterProperties( 5854): State = , 11
D/BluetoothAdapterProperties( 5854): Setting state to 12
I/BluetoothAdapterState( 5854): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  895): +onBluetoothStateChange prev=11 new=12
I/bt-btif ( 5854): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  895): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothAdapterProperties( 5854): Discoverable Timeout:120
D/BluetoothManagerService(  895): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  895): Broadcasting onBluetoothStateChange(true) to 8 receivers.
D/BluetoothHeadset( 1445): onBluetoothStateChange: up=true
D/BluetoothHeadset(  895): onBluetoothStateChange: up=true
D/BluetoothA2dp(  895): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 5854): Entering On State
D/BluetoothHeadset( 1445): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1445): onBluetoothStateChange: up=true
D/BluetoothHeadset( 3173): onBluetoothStateChange: up=true
D/BluetoothA2dp( 3173): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1130): onBluetoothStateChange: up=true
D/BluetoothManagerService(  895): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  895): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  895): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  895): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/IntentController( 1130): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3173): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5854): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5854): ***********state = 12
D/NGFService( 3173): Bluetooth Adapter: ON
E/bt_mct  ( 5854): hci lib postload completed
D/BluetoothHeadset(  895): BluetoothHeadset()
D/BluetoothManagerService(  895): registerStateChangeCallback+
D/BluetoothHeadset(  895): Proxy object connected
I/BluetoothAdapterState( 5854): notBluetoothOn()
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  895): Registered receivers: 9
V/BluetoothPbapService( 5854): Pbap Service onCreate
V/BluetoothPbapService( 5854): Starting PBAP service
D/BluetoothAdapter( 5854): 329904984: getState(). Returning 12
V/BluetoothPbapService( 5854): Handler(): got msg=1
V/BluetoothPbapService( 5854): Pbap Service startRfcommSocketListener
D/HtcBtWidget_BTWidgetProvider( 5890): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5890): updateWidget(context) for widget: 
V/BluetoothPbapService( 5854): Pbap Service initSocket
W/System.err(  895): java.lang.Throwable: stack dump
W/System.err(  895): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  895): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  895): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  895): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  895): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29e8f268:true
D/BluetoothManagerService(  895): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 5072): 808333545: getState(). Returning 12
D/BluetoothInputDevice( 5072): BluetoothInputDevice()
D/BluetoothManagerService(  895): registerStateChangeCallback+
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  895): Registered receivers: 10
D/BluetoothPan( 5072): BluetoothPan()
D/BluetoothManagerService(  895): registerStateChangeCallback+
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  895): Registered receivers: 11
D/BluetoothMap( 5072): Create BluetoothMap proxy object
D/BluetoothManagerService(  895): registerStateChangeCallback+
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  895): Registered receivers: 12
E/BluetoothMap( 5072): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/wpa_supplicant( 5909): EAPOL: disable timer tick
W/BluetoothAdapter( 5854): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btm  ( 5854): BTM_SetDiscoverability
I/bt-btm  ( 5854): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5854): disc_mode 0000
I/bt-btm  ( 5854): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5854): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5854): BTM_SetConnectability
I/bt-btif ( 5854): BTA_JvCreateRecordByUser
I/bt-btm  ( 5854): BTA_JvCreateRecordByUser
D/bt-btm  ( 5854): disc_mode 0000
D/bt-btm  ( 5854): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 5854): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 5854): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btif ( 5854): BTA_JvRfcommStartServer
I/bt-btm  ( 5854): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 5854):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,I/bt-btif ( 5854): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5854): Scan Mode:21
D/BluetoothManagerService(  895): registerStateChangeCallback+
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  895): Registered receivers: 13
D/BluetoothSap( 5072): BluetoothSap() call bindService
D/BluetoothPbap( 5072): BluetoothPbap()
D/BluetoothManagerService(  895): registerStateChangeCallback+
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  895): Registered receivers: 14
D/BluetoothManagerService(  895): registerStateChangeCallback+
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  895): Registered receivers: 15
V/BluetoothPbapService( 5854): Succeed to create listening socket 
V/BluetoothPbapService( 5854): Accepting socket connection...
D/BluetoothHeadset( 5072): BluetoothHeadset()
D/BluetoothManagerService(  895): registerStateChangeCallback+
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  895): Registered receivers: 16
D/LocalBluetoothProfileManager( 5072): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 1130): 241541550: getState(). Returning 12
V/BluetoothPbapService( 5854): Pbap Service onBind
D/BluetoothAdapter( 1130): 241541550: getState(). Returning 12
I/QuickSettingBluetooth( 1130): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1130): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ac level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothManagerService(  895): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5854): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 5854): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btif ( 5854): BTA_JvRfcommStartServer
I/bt-btm  ( 5854): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 5854):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 5854): Accept thread started.
D/BluetoothAdapter( 5854): 329904984: getState(). Returning 12
D/DockEventReceiver( 5072): finishStartingService: stopping service
D/BluetoothInputDevice( 5072): Proxy object connected
D/HidProfile( 5072): Bluetooth service connected
D/BluetoothFtpService( 5854): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothMasReceiver( 5854): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 5854):  call MAP start service
D/BluetoothAdapter( 5072): 808333545: getState(). Returning 12
D/BluetoothManagerService(  895): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5854): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothA2dp( 5072): Proxy object connected
D/A2dpProfile( 5072): Bluetooth service connected
I/bt-btif ( 5854): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btif ( 5854): BTA_JvRfcommStartServer
I/bt-btm  ( 5854): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 5854):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 5072): 808333545: getState(). Returning 12
D/BluetoothHeadset( 5072): Proxy object connected
D/HeadsetProfile( 5072): Bluetooth service connected
V/BluetoothFtpService:RfcommSocketAcceptThread( 5854): Run Accept thread
D/BluetoothAdapter( 5072): 808333545: getState(). Returning 12
E/BluetoothMasService( 5854): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothPan( 5072): BluetoothPAN Proxy object connected
D/PanProfile( 5072): Bluetooth, service connected
D/BluetoothPbap( 5072): Proxy object connected
D/PbapServerProfile( 5072): Bluetooth service connected
D/BluetoothMasService( 5854): Add permission for SmsProvider.
V/BluetoothMasService( 5854): Starting MAS instances
D/BluetoothAdapter( 5854): 329904984: getState(). Returning 12
I/MailMessageReceiver( 5854): reg:com.android.bluetooth.btservice.AdapterApp@302e30e9 with com.htc.util.mail.MailMessageReceiver@13c8016e
I/MailManager( 5854): MailManager contruct! com.htc.util.mail.MailMessageReceiver@13c8016e
V/EmailUtils( 5854): Manager Instance is not NULL
,I/ActivityManager(  895): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6032 uid=10065 gids={50065, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/art     (  895): Explicit concurrent mark sweep GC freed 34446(1776KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 16MB/25MB, paused 874us total 74.433ms
,D/HtcAdjCursorFactory( 6032): Set CursorWindow size to: 4194304 KB, Tid: 6049
,D/EmailUtils( 5854): ============NULL aList========
,V/EmailUtils( 5854): <-getEmailAccountIdList
V/BluetoothMasService( 5854): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 5854): 329904984: getState(). Returning 12
V/BluetoothMasService( 5854): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 5854): Manager Instance is not NULL
,D/EmailUtils( 5854): ============NULL aList========
,V/EmailUtils( 5854): <-getEmailAccountIdList
V/BluetoothSapReceiver( 5854): SapReceiver onReceive 
V/BluetoothSapReceiver( 5854): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5854):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 5854): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 5854): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 5854): BluetoothMns: isEmailEnabled: true
,D/AuthorizationBluetoothService( 1753): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  895): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5854): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5854): BTA_JvCreateRecordByUser
D/bt-btm  ( 5854): BTM_AllocateSCN
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btif ( 5854): BTA_JvRfcommStartServer
I/bt-btm  ( 5854): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 5854):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  895): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5854): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 5854): BTA_JvCreateRecordByUser
D/bt-btm  ( 5854): BTM_AllocateSCN
D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btif ( 5854): BTA_JvRfcommStartServer
I/bt-btm  ( 5854): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 5854):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/Process (  895): killProcessQuiet, pid=5418,
I/ActivityManager(  895): Killing 5418:com.htc.cs.dm/u0a105 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,I/ActivityManager(  895): Recipient 5418
,D/Process (  895): killProcessQuiet, pid=5418
,D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  895): failed to open /acct/uid_10105/pid_5418/cgroup.procs: No such file or directory
V/BluetoothSapService( 5854): Sap Service onCreate
V/BluetoothSapService( 5854): initBinder
,V/BluetoothSapService( 5854): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@372ff2a5
V/BluetoothSapService( 5854): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@24e7de2b
,V/BluetoothSapService( 5854): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 5854): state: 12
D/SapServerProfile( 5072): Bluetooth service connected
V/BluetoothSapService( 5854): Starting SAP server process
V/BluetoothSapService( 5854): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 5854): Sap Service initRfcommSocket
,D/BluetoothManagerService(  895): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
W/BluetoothAdapter( 5854): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5854): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 5854): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 5854): Write Extended Inquiry Response to controller
I/bt-btif ( 5854): BTA_JvRfcommStartServer
I/bt-btm  ( 5854): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 5854):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 5854): Succeed to create listening socket 
V/BluetoothSapService( 5854): Accepting socket connection...
,D/A2dpService( 5854): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@1fd21421,
D/A2dpSinkService( 5854): getA2dpSinkService(): service is NULL
,I/jxcore-log( 5794): Attempting to connect to the test coordinator server,
I/jxcore-log( 5794): 
,D/wpa_supplicant( 5909): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0,
,W/ContextImpl(  895): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:13935 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14100 com.android.server.wifi.WifiStateMachine.access$5400:265 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7908 ,
,D/wpa_supplicant( 5909): wlan0: nl80211: New sched scan results available
D/wpa_supplicant( 5909): wlan0: Event SCAN_RESULTS (3) received,
,I/wpa_supplicant( 5909): Got an original EVENT_SCAN_RESULTS
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 5909): nl80211: Received scan results (1 BSSes)
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 5909): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
D/wpa_supplicant( 5909): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 5909): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 5909): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 5909): wlan0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 5909): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 5909): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 5909): wlan0: Selecting BSS from priority group 136
D/wpa_supplicant( 5909): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-52 wps
D/wpa_supplicant( 5909): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 5909): wlan0:    selected based on RSN IE
W/wpa_supplicant( 5909): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 5909):    selected WPA/WAPI AP c0:ff:d4:d3:aa:4a ssid='NG7005g'
D/wpa_supplicant( 5909): wlan0:    selected BSS c0:ff:d4:d3:aa:4a ssid='NG7005g'
D/wpa_supplicant( 5909): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:4a  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7b7a9c8  current_ssid=0x0
D/wpa_supplicant( 5909): wlan0: Request association with c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 5909): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=9): 00 07 4e 47 37 30 30 35 67
D/wpa_supplicant( 5909): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 2c
D/wpa_supplicant( 5909): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 20 01 03
D/wpa_supplicant( 5909): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 2c 0d 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5909): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 5909): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 5909): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 5909): wlan0: Add radio work 'connect'@0xb7b7d230
D/wpa_supplicant( 5909): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 5909): wlan0: Starting radio work 'connect'@0xb7b7d230 after 0.000026 second wait
I/wpa_supplicant( 5909): check if in concurrent case
I/wpa_supplicant( 5909): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
D/wpa_supplicant( 5909): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 5909): wlan0: Cancelling sched scan
D/wpa_supplicant( 5909): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 5909): wlan0: Cancelling scan request
D/wpa_supplicant( 5909): wpas_start_assoc_cb, 1887
D/wpa_supplicant( 5909): wpas_start_assoc_cb, 1890
D/wpa_supplicant( 5909): wpas_start_assoc_cb, 1905
D/wpa_supplicant( 5909): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 5909): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 5909): RSN: PMKSA cache search - network_ctx=0xb7b7a9c8 try_opportunistic=0
D/wpa_supplicant( 5909): RSN: Search for BSSID c0:ff:d4:d3:aa:4a
,D/wpa_supplicant( 5909): RSN: No PMKSA cache entry found
D/wpa_supplicant( 5909): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 5909): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 5909): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 5909): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 5909): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 5909): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 5909): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 5909): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 5909): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 5909): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 5909): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 5909): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5909): netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5909): Limit connection to BSSID c0:ff:d4:d3:aa:4a freq=5220 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 5909): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 5909): nl80211: Unsubscribe mgmt frames handle 0x3f3f18e9 (mode change)
D/wpa_supplicant( 5909): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7b79060
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0104
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040a
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040b
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040c
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040d
,D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=090a
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=090b
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=090c
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=090d
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0409506f9a09
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=7f506f9a09
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0801
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=040e
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=06
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0a07
D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0a11
,D/wpa_supplicant( 5909): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7b79060 match=0a1a
D/wpa_supplicant( 5909): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 5909):   * bssid=c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909):   * bssid_hint=c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909):   * freq=5220
D/wpa_supplicant( 5909):   * freq_hint=5220
D/wpa_supplicant( 5909):   * SSID - hexdump(len=7): 4e 47 37 30 30 35 67
D/wpa_supplicant( 5909):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 5909):   * WPA Versions 0x2
D/wpa_supplicant( 5909):   * pairwise=0xfac04,
D/wpa_supplicant( 5909):   * group=0xfac04
D/wpa_supplicant( 5909):   * akm=0xfac02
D/wpa_supplicant( 5909):   * Auth Type 0
D/wpa_supplicant( 5909): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0xb7b7a9f2
D/wpa_supplicant( 5909): nl80211: Connect request send successfully
D/wpa_supplicant( 5909): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 5909): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 5909): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 5909): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 5909): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 5909): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 5909): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  895): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  895): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiStateMachine(  895): handleMessage: E msg.what=147461
E/WifiStateMachine(  895): processMsg: DisconnectedState
,E/WifiStateMachine(  895):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 dur:62 bcn=0
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  895): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  895): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)]
E/WifiStateMachine(  895): processMsg: ConnectModeState,
E/WifiStateMachine(  895):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 dur:62 bcn=0
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=11 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz),
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=],
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  895): processMsg: DriverStartedState
D/HTCRequest(  895): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine(  895):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 dur:62 bcn=0
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  895): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
E/WifiStateMachine(  895):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 dur:62 bcn=0
D/WifiStateMachine(  895): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 5909): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  895): [1,447,848,444,716 ms] noteScanEnd no scan source,
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 5909): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WirelessDisplayService(  895): getDiscoveryDongleList
E/WifiStateMachine(  895): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@21045a42 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  895): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  895): updateSavedNetworkHistory(): try "NG7005g"WPA_PSK SSID="NG7005g" NG7005g [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  895): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  895): linkConfiguration link due to same gw "NG700" and "NG7005g" GW c0:ff:d4:d3:aa:48
,E/WifiConfigStore(  895): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore(  895): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore(  895): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore(  895): readNetworkVariableFromSupplicantFile ssid=["NG7005g"] key=psk
E/WifiConfigStore(  895): linkConfiguration: will link "NG700"WPA_PSK and "NG7005g"WPA_PSK
E/WifiConfigStore(  895):         got known scan result c0:ff:d4:d3:aa:4a key : "NG7005g"WPA_PSK num: 1 rssi=-52 freq=5220
E/WifiAutoJoinController (  895): ageScanResultsOut delay 40000 size 1 now 1447848444735
E/WifiAutoJoinController (  895): newSupplicantResults size=1 known=1 true
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
,D/wpa_supplicant( 5909): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  895): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  895): p2p_device_address=02:ee:bd:dd:33:d2
E/WifiAutoJoinController (  895): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  895): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  895): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  895):  writeKnownNetworkHistory() num networks:4 needWrite=true
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131213
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState CMD_TARGET_BSSID 11 0 BSSID=c0:ff:d4:d3:aa:4a Target=any roam=0 rt=137121
,E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState CMD_TARGET_BSSID 11 0 BSSID=c0:ff:d4:d3:aa:4a Target=any roam=0 rt=137122
E/WifiStateMachine(  895): processMsg: DriverStartedState
E/WifiStateMachine(  895):  DriverStartedState CMD_TARGET_BSSID 11 0 BSSID=c0:ff:d4:d3:aa:4a Target=any roam=0 rt=137122
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
E/WifiStateMachine(  895):  SupplicantStartedState CMD_TARGET_BSSID 11 0 BSSID=c0:ff:d4:d3:aa:4a Target=any roam=0 rt=137123
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=147462
E/WifiStateMachine(  895): processMsg: DisconnectedState
,E/WifiStateMachine(  895):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=137123  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 3
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=137131  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  895): handleMessage: X
,E/WifiConfigStore(  895): saving network history: "Ozz"WPA_PSK gw: null autojoin-status: 0 ephemeral=false choices:0 link:0 status:2 nid:1
E/WifiConfigStore(  895): writeKnownNetworkHistory write config "Ozz"WPA_PSK
E/WifiConfigStore(  895): saving network history: "huawei mate 7"NONE gw: null autojoin-status: 0 ephemeral=false choices:0 link:0 status:2 nid:0
E/WifiConfigStore(  895): writeKnownNetworkHistory write config "huawei mate 7"NONE
E/WifiConfigStore(  895): saving network history: "NG7005g"WPA_PSK gw: c0:ff:d4:d3:aa:48 autojoin-status: 0 ephemeral=false choices:0 link:1 status:2 nid:3
E/WifiConfigStore(  895): writeKnownNetworkHistory write config "NG7005g"WPA_PSK
E/WifiConfigStore(  895): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  895): saving network history: "NG700"WPA_PSK gw: c0:ff:d4:d3:aa:48 autojoin-status: 0 ephemeral=false choices:0 link:1 status:2 nid:2,
E/WifiConfigStore(  895): writeKnownNetworkHistory write config "NG700"WPA_PSK
E/WifiConfigStore(  895): writeKnownNetworkHistory write linked 1
D/WISPrService( 5072): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5072): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1130): receive.wifiConnect:false wifiAPname:null elapse:0,
,D/Tethering(  895): interfaceLinkStateChanged wlan0, false,
D/Tethering(  895): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 5909): Wireless event: cmd=0x8c02 len=262
I/wpa_supplicant( 5909): WEXT: Custom wireless event: 'BEACONIEs='
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 5909): Wireless event: cmd=0x8b15 len=20
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 5909): Wireless event: cmd=0x8c07 len=30
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x11003 ([UP][LOWER_UP])
D/UsbDeviceManager(  895): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 5909): Wireless event: cmd=0x8c08 len=30
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 5909): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 5909): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 5909): nl80211: Connect event
D/wpa_supplicant( 5909): nl80211: Associated on 5220 MHz
D/wpa_supplicant( 5909): nl80211: Associated with c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909): nl80211: Operating frequency for the associated BSS from scan results: 5220 MHz
D/wpa_supplicant( 5909): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 5909): wlan0: Association info event
D/wpa_supplicant( 5909): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 5909): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 5909): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 5909): wlan0: freq=5220 MHz
D/wpa_supplicant( 5909): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 5909): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 5909): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 5909): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5909): netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5909): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 5909): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 5909): wlan0: Associated with c0:ff:d4:d3:aa:4a ssid='NG7005g' freq=5220
D/wpa_supplicant( 5909): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 5909): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 5909): TDLS: Remove peers on association
D/wpa_supplicant( 5909): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 5909): EAPOL: External notification - portValid=0
D/wpa_supplicant( 5909): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 5909): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 5909): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 5909): EAPOL: enable timer tick
D/wpa_supplicant( 5909): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 5909): wlan0: Setting authentication timeout: 10 sec 0 usec
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 5909): wlan0: Cancelling scan request
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 5909): htc_wext_set_keepalive +
D/PMS     (  895): acquireWL(d3feff8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 895 1000 null
I/wpa_supplicant( 5909): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 5909): getPrivFuncNum +	
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 5909): getPrivFuncNum -, cmd = 0x8bf6
D/WifiDisplayAdapter(  895): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  895):     Client/Owner: Client
D/WifiDisplayAdapter(  895):     GroupId: 
D/WifiDisplayAdapter(  895):     Passphrase: 
D/WifiDisplayAdapter(  895):     SessionId: 0
D/WifiDisplayAdapter(  895):     IP Address: }
I/wpa_supplicant( 5909): htc_wext_set_keepalive fnum = 0x8bf6
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 5909): htc_wext_set_keepalive - ret = 0
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 5909): wlan0: RX EAPOL from c0:ff:d4:d3:aa:4a
D/PMS     (  895): releaseWL(d3feff8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 5909): wlan0: Setting authentication timeout: 10 sec 0 usec
V/NetworkPolicy(  895): updateNetworkEnabledLocked()
D/wpa_supplicant( 5909): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
V/NetworkPolicy(  895): updateNotificationsLocked()
D/wpa_supplicant( 5909): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 5909): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 5909): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 5909):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 5909):   key_nonce - hexdump(len=32): 25 ea 5f f0 61 af 9e fa 4e ed 71 16 5a 29 f9 b2 9d 00 11 9f 9d 14 32 c9 8d de b3 51 2d db 2c 5c
D/wpa_supplicant( 5909):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5909):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5909):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5909):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5909): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 5909): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:4a (ver=2)
D/wpa_supplicant( 5909): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=3 state=6 BSSID=00:00:00:00:00:00 SSID=NG7005g]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=3 state=6 BSSID=00:00:00:00:00:00 SSID=NG7005g
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange():id=3 state=6 BSSID=00:00:00:00:00:00 SSID=NG7005g
D/HTCRequest(  895): WifiMonitor:getSSIDFromString id=3 state=6 BSSID=00:00:00:00:00:00 SSID=NG7005g
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange(): SSIDNG7005g
D/WifiMonitor(  895): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  895): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:4a ssid='NG7005g' freq=5220]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=14 dispatchEvent: Associated with c0:ff:d4:d3:aa:4a ssid='NG7005g' freq=5220
D/WifiMonitor(  895): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:4a ssid='NG7005g' freq=5220
D/WifiMonitor(  895): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:4a ss,id='NG7005g' freq=5220
D/HTCRequest(  895): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:4a ssid='NG7005g' freq=5220
D/HTCRequest(  895): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:4a ssid='NG7005g' freq=5220
D/HTCRequest(  895): WifiMonitor:getFreqFromEventString() 5220
D/HTCRequest(  895): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:4a ssid='NG7005g' freq=5220
D/WifiMonitor(  895): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:4a
D/ConnectivityService(  895): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/WifiMonitor(  895): handleAssociatedWithEvent. bLFR =false
,D/ConnectivityService(  895): Got NetworkAgent Messenger
D/WifiMonitor(  895): handleAssociatedWithEvent. wifiSsid ='NG7005g' freq=5220
W/ContextImpl( 5072): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 5909): WPA: Renewed SNonce - hexdump(len=32): ba f6 0b de b3 67 65 35 40 31 79 bc f0 e0 6f 7a 9f 3c 6d 58 d5 51 d1 ee 67 37 3b 98 cf 8a 2d 28
D/wpa_supplicant( 5909): WPA: Nonce1 - hexdump(len=32): ba f6 0b de b3 67 65 35 40 31 79 bc f0 e0 6f 7a 9f 3c 6d 58 d5 51 d1 ee 67 37 3b 98 cf 8a 2d 28
D/wpa_supplicant( 5909): WPA: Nonce2 - hexdump(len=32): 25 ea 5f f0 61 af 9e fa 4e ed 71 16 5a 29 f9 b2 9d 00 11 9f 9d 14 32 c9 8d de b3 51 2d db 2c 5c
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=3 state=7 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g]
D/wpa_supplicant( 5909): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 5909): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 5909): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/ConnectivityService(  895): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=3 state=7 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/wpa_supplicant( 5909): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 5909): wlan0: WPA: Sending EAPOL-Key 2/4
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange():id=3 state=7 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/ConnectivityService(  895): NetworkAgent connected
D/HTCRequest(  895): WifiMonitor:getSSIDFromString id=3 state=7 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/wpa_supplicant( 5909): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 5909): WPA: Derived Key MIC - hexdump(len=16): d5 f9 fd 43 8e 6a ed bd 69 b0 43 6c 91 d2 f5 6e
E/WifiStateMachine(  895): handleMessage: E msg.what=147462
E/WifiStateMachine(  895): processMsg: DisconnectedState
D/Tethering(  895): interfaceLinkStateChanged wlan0, false
D/Tethering(  895): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  895):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=137200  SSID: NG7005g BSSID: 00:00:00:00:00:00 nid: 3 state: ASSOCIATED
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  895): processMsg: ConnectModeState
D/Tethering(  895): interfaceLinkStateChanged wlan0, true
D/Tethering(  895): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  895):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=137200  SSID: NG7005g BSSID: 00:00:00:00:00:00 nid: 3 state: ASSOCIATED
D/Tethering(  895): interfaceLinkStateChanged wlan0, true
E/WifiStateMachine(  895): handleMessage: X
D/Tethering(  895): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  895): handleMessage: E msg.what=147500
E/WifiStateMachine(  895): processMsg: DisconnectedState
D/Tethering(  895): interfaceLinkStateChanged wlan0, true
D/Tethering(  895): interfaceStatusChanged wlan0, true
,E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  895):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  895): processMsg: ConnectModeState
D/Tethering(  895): interfaceLinkStateChanged wlan0, true
D/Tethering(  895): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  895): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  895):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  895): Enter handleAssociatedWithEvent
D/WifiStateMachine(  895): Setting MAC Address to c0:ff:d4:d3:aa:4a
D/WifiStateMachine(  895): Associated
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange(): SSIDNG7005g
D/WifiMonitor(  895): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  895): mAssociatedMacAddress = c0:ff:d4:d3:aa:4a
D/WifiStateMachine(  895): Exit handleAssociatedWithEvent
,E/WifiStateMachine(  895): handleMessage: X
,E/WifiStateMachine(  895): handleMessage: E msg.what=147462
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=137202  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  895): setDetailed state send new extra info"NG7005g"
E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG7005g, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 3, Metered hint: false
E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG7005g, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 3, Metered hint: false
D/wpa_supplicant( 5909): wlan0: RX EAPOL from c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 5909): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 5909): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 5909): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 5909):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 5909):   key_nonce - hexdump(len=32): 25 ea 5f f0 61 af 9e fa 4e ed 71 16 5a 29 f9 b2 9d 00 11 9f 9d 14 32 c9 8d de b3 51 2d db 2c 5c
D/wpa_supplicant( 5909):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5909):   key_rsc - hexdump(len=8): b8 04 00 00 00 00 00 00
D/wpa_supplicant( 5909):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5909):   key_mic - hexdump(len=16): 84 1a 96 e9 d2 e9 da 8c 11 9d 9c 3d d9 53 d4 57
D/wpa_supplicant( 5909): RSN: encrypted key data - hexdump(len=56): c7 e4 fd 3c 24 6a 80 2a 13 ec b3 ea 6b 54 57 9b 1c b6 1d cf 01 a4 fa 8f 62 53 56 93 a3 b1 b8 76 ...
D/wpa_supplicant( 5909): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 5909): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 5909): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:4a (ver=2)
D/wpa_supplicant( 5909): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 4d f0 ...
D/wpa_supplicant( 5909): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 5909): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 5909): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 5909): WPA: KCK - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 5909): WPA: Derived Key MIC - hexdump(len=16): 9f 22 4f bf a5 39 3b 77 84 3b 47 d7 37 44 e0 d9
D/wpa_supplicant( 5909): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7b7af7c key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 5909): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 5909): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 5909):    addr=c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909): EAPOL: External notification - portValid=1
D/wpa_supplicant( 5909): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 5909): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 5909): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 5909): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 5909): WPA: RSC - hexdump(len=6): b8 04 00 00 00 00
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 4
D/wpa_supplicant( 5909): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f0e50a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 5909): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 5909): nl80211: KEY_SEQ - hexdump(len=6): b8 04 00 00 00 00
D/wpa_supplicant( 5909):    broadcast key
D/ConnectivityService(  895): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/wpa_supplicant( 5909): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 5909): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 5909): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 5909): wlan0: Radio work 'connect'@0xb7b7d230 done in 0.114633 seconds
I/wpa_supplicant( 5909): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=3 id_str=]
I/wpa_supplicant( 5909): setConcurrentAPChannel: Set wifi.hotspot.channel to 44
E/wpa_supplicant( 5909): wlan0: Connect to SSID: NG7005g
D/wpa_supplicant( 5909): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 5909): netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 5909): set send_ind_to_ndc = 0
I/wpa_supplicant( 5909): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 5909): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 5909): EAPOL: External notification - portValid=1
D/wpa_supplicant( 5909): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 5909): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 5909): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 5909): EAP: EAP entering state DISABLED
D/wpa_supplicant( 5909): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 5909): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 5909): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 5909): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 5909): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 5909): RTM_NEWLINK: ifi_index=22 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/Tethering(  895): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  895): handlePreDhcpSetup Held wake lock during DHCP
D/Tethering(  895): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  895): acquireWL(b25ea72): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 895 1000 null
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  895): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 5
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
D/Tethering(  895): sendTetherStateChangedBroadca,st 1, 0, 0
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=3 state=8 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=3 state=8 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange():id=3 state=8 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  895): WifiMonitor:getSSIDFromString id=3 state=8 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange(): SSIDNG7005g
D/WifiMonitor(  895): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  895): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=17 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  895): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  895): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=18 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:4a
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=3 id_str=]]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=3 id_str=]
E/WifiMonitor(  895): handleEvent 1  Connection to c0:ff:d4:d3:aa:4a completed [id=3 id_str=]
D/WifiMonitor(  895): Event [IFNAME=wlan0 Connect to SSID: NG7005g]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=20 dispatchEvent: Connect to SSID: NG7005g
W/WifiMonitor(  895): couldn't identify event type - Connect to SSID: NG7005g
D/WifiMonitor(  895): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=3 state=9 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=3 state=9 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange():id=3 state=9 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  895): WifiMonitor:getSSIDFromString id=3 state=9 BSSID=c0:ff:d4:d3:aa:4a SSID=NG7005g
D/HTCRequest(  895): WifiMonitor:handleSupplicantStateChange(): SSIDNG7005g
D/WifiMonitor(  895): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=137210  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: FOUR_WAY_HANDSHAKE
,E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=147462
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=137210  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: GROUP_HANDSHAKE
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=137211  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: GROUP_HANDSHAKE
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=147459
E/WifiStateMachine(  895): processMsg: DisconnectedState
E/WifiStateMachine(  895):  DisconnectedState NETWORK_CONNECTION_EVENT 3 0 null nid=-1 rt=137211
E/WifiStateMachine(  895): processMsg: ConnectModeState
,D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/UsbnetService(  895): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  895): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  895): [NET] android_getaddrinfo_proxy+
D/libc    (  895): [NET] android_getaddrinfo_proxy get netid:0
E/WifiStateMachine(  895):  ConnectModeState NETWORK_CONNECTION_EVENT 3 0 null nid=-1 rt=137215
E/WifiStateMachine(  895): Network connection established
D/WifiStateMachine(  895): fetchFrequency(), freq = 5220
E/WifiStateMachine(  895): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 5220, Net ID: 3, Metered hint: false
,E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 5220, Net ID: 3, Metered hint: false
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  458): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  458): [NET] android_getaddrinfofornet-, err=7
D/libc    (  895): [NET] android_getaddrinfo_proxy-, NODATA
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 6
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 7
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  895): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  895): handleMessage: new destination call exit/enter
,E/WifiStateMachine(  895): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  895): invokeExitMethods: DisconnectedState
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 5909): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  895): setScanAlarm false period 0 initial delay 0
D/WirelessDisplayService(  895): getMirrorDisplayStatus:falsecurState:1
E/WifiStateMachine(  895): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  895): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  895): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  895): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  895): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 5220, Net ID: 3, Metered hint: false
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 8
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  895): L2ConnectedState c0:ff:d4:d3:aa:4a config "NG7005g"WPA_PSK config.bssid null
E/WifiStateMachine(  895): L2ConnectedState "NG7005g" nid=3
E/WifiConfigStore(  895): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
W/WifiHW  (  895): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5909): CTRL_IFACE: SET_NETWORK id=3 name='bssid'
D/wpa_supplicant( 5909): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,D/TetherSettings( 5072): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5072): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5072): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5072): Cust_ConnectToPC   : spcsc>false
D/        ( 5072): Cust_ConnectToPC   : IPT>true
D/        ( 5072): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5072): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
E/SmartNS_Utility( 5072): hasRemovableStorageSlot: true
D/wpa_supplicant( 5909): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 5909): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/SmartNS_Utility( 5072): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5072): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,D/wpa_supplicant( 5909): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5909): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  895): invokeEnterMethods: ObtainingIpState
,E/WifiStateMachine(  895): enter ObtainingIpState netId=3 "NG7005g"WPA_PSK  roam=0 static=false watchdog= 0
,E/WifiStateMachine(  895): ObtainingIpAddress c0:ff:d4:d3:aa:4a config "NG7005g"WPA_PSK config.bssid any
E/WifiStateMachine(  895): ObtainingIpAddress "NG7005g" nid=3
E/WifiConfigStore(  895): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,W/WifiHW  (  895): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 5909): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5909): CTRL_IFACE: SET_NETWORK id=3 name='bssid'
D/wpa_supplicant( 5909): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 5909): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5909): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5909): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/SmartNS_Utility( 5072): setISNotification
D/SmartNS_Utility( 5072): usb_cable_connect = 1
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
D/SmartNS_Utility( 5072): usb_denied = 0
I/SmartNS_PSService( 5072): usb notificaiton:true
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  895): Start Dhcp Watchdog 1
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=147462
E/WifiStateMachine(  895): processMsg: ObtainingIpState
E/WifiStateMachine(  895):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=137235  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: COMPLETED
,E/WifiStateMachine(  895): processMsg: L2ConnectedState
E/WifiStateMachine(  895):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=137235  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: COMPLETED
E/WifiStateMachine(  895): processMsg: ConnectModeState
D/SmartNS_Utility( 5072): usb_cable_connect = 1
E/WifiStateMachine(  895):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=137235  SSID: NG7005g BSSID: c0:ff:d4:d3:aa:4a nid: 3 state: COMPLETED
E/WifiStateMachine(  895): handleMessage: X
D/SmartNS_Utility( 5072): usb_denied = 0
I/SmartNS_PSService( 5072): usb notificaiton:true
E/WifiStateMachine(  895): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  895): handleMessage: E msg.what=131101
E/WifiStateMachine(  895): processMsg: ObtainingIpState
E/WifiStateMachine(  895):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  895): processMsg: L2ConnectedState
,E/WifiStateMachine(  895):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  895): processMsg: DriverStartedState
E/WifiStateMachine(  895):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  895):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/RemoteViews( 1130): reapply : com.android.settings 1 36
D/WISPrService( 5072): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  895): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  895): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131212
E/WifiStateMachine(  895): processMsg: ObtainingIpState
D/WISPrService( 5072): wifi connected:falsemWifiInfo:SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 5220, Net ID: 3, Metered hint: false
E/WifiStateMachine(  895):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: L2ConnectedState
E/WifiStateMachine(  895):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: DriverStartedState
,E/WifiStateMachine(  895):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
E/WifiStateMachine(  895):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/SmartNS_NSReceiver( 5072): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  895): Link configuration changed for netId: 3 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  895): updateLinkProperties nid: 3 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=196612
E/WifiStateMachine(  895): processMsg: ObtainingIpState
E/WifiStateMachine(  895):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,E/WifiStateMachine(  895): processMsg: L2ConnectedState
E/WifiStateMachine(  895):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WISPrService( 5072): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  895): setDhcpActive: true
D/WISPrService( 5072): wifi connected:falsemWifiInfo:SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 5220, Net ID: 3, Metered hint: false
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/WISPrService( 5072): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 4096
D/WISPrService( 5072): wifi connected:falsemWifiInfo:SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 5220, Net ID: 3, Metered hint: false
E/WifiStateMachine(  895): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  895): do suspend false
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
,D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/WISPrService( 5072): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5072): wifi connected:falsemWifiInfo:SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 5220, Net ID: 3, Metered hint: false
D/WISPrService( 5072): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5072): wifi connected:falsemWifiInfo:SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 5220, Net ID: 3, Metered hint: false
I/RemoteViews( 1130): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1130): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1130): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1130): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1130): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1130): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 4096
D/wpa_supplicant( 5909): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 5909): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 5909): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 02
,D/wpa_supplicant( 5909): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 5909): Power_Mode_Type mode = 1
I/wpa_supplicant( 5909): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  895): Unexpected BatchedScanResults :null
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  895): noteBatchedScanstop()
E/WifiStateMachine(  895): handleMessage: X
,E/dhcpcd  ( 6088): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6088): version 5.5.6 starting
,E/dhcpcd  ( 6088): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6088): wlan0: using ClientID 01:00:**:bd:dd:33:d2
,I/dhcpcd  ( 6088): autoip env[11]:autoip=DISABLE
,I/dhcpcd  ( 6088): wlan0: rebinding lease of 192.168.1.127,
,I/dhcpcd  ( 6088): wlan0: sending REQUEST (xid 0xf3f5f0c2), next in 0.98 seconds
,D/wpa_supplicant( 5909): EAPOL: startWhen --> 0,
,D/wpa_supplicant( 5909): EAPOL: disable timer tick,
,I/dhcpcd  ( 6088): wlan0: sending REQUEST (xid 0xf3f5f0c2), next in 2.56 seconds
,I/dhcpcd  ( 6088): wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,I/dhcpcd  ( 6088): wlan0: leased 192.168.1.127 for 86400 seconds,
I/dhcpcd  ( 6088): autoip env[11]:autoip=DISABLE
D/ConnectivityService(  895): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  895): handleMessage: E msg.what=131212
E/WifiStateMachine(  895): processMsg: ObtainingIpState
E/WifiStateMachine(  895):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: L2ConnectedState,
E/WifiStateMachine(  895):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: DriverStartedState
E/WifiStateMachine(  895):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
E/WifiStateMachine(  895):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  895): Link configuration changed for netId: 3 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  895): updateLinkProperties nid: 3 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  895): handleMessage: X
,I/dhcpcd  ( 6088): bind_interface: daemonise,
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  895): handleMessage: E msg.what=196613
E/WifiStateMachine(  895): processMsg: ObtainingIpState
E/WifiStateMachine(  895):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  895): processMsg: L2ConnectedState,
E/WifiStateMachine(  895):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  895): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  895): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  895): do suspend true
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1",
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 4096
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 5909): Power_Mode_Type mode = 0
I/wpa_supplicant( 5909): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2",
D/PMS     (  895): releaseWL(b25ea72): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/ConnectivityService(  895): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/wpa_supplicant( 5909): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 4096
D/WifiDataStallTracker(  895): setDhcpActive: false
E/WifiStateMachine(  895): handlePostDhcpSetup release wake lock during DHCP
,E/WifiStateMachine(  895): WifiStateMachine DHCP successful
E/WifiStateMachine(  895): wifistatemachine handleIPv4Success <IP address 192.168.1.127/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  895): link address 192.168.1.127/24
D/WirelessDisplayService(  895): getMirrorDisplayStatus:falsecurState:1
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 MIRROR-STATUS 0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'MIRROR-STATUS 0'
I/wpa_supplicant( 5909): MIRROR-STATUS+
I/wpa_supplicant( 5909): MIRROR-STATUS : Off
,E/WifiStateMachine(  895): Link configuration changed for netId: 3 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  895): updateLinkProperties nid: 3 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  895): gateway: /192.168.1.1
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 5909): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 5909): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 5909): htc_wext_set_keepalive +
I/wpa_supplicant( 5909): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 5909): getPrivFuncNum +	
I/wpa_supplicant( 5909): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 5909): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 5909): get_ip_address source addr = c0a8017f
I/wpa_supplicant( 5909): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 5909): htc_wext_set_keepalive - ret = 0
D/WirelessDisplayService(  895): getMirrorDisplayStatus:falsecurState:1
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 MIRROR-STATUS 0"
D/wpa_supplicant( 5909): wlan0: Control interface command 'MIRROR-STATUS 0'
I/wpa_supplicant( 5909): MIRROR-STATUS+
I/wpa_supplicant( 5909): MIRROR-STATUS : Off
D/WifiStateMachine(  895): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  895): handleMessage: X
E/WifiStateMachine(  895): handleMessage: E msg.what=131210
E/WifiStateMachine(  895): processMsg: ObtainingIpState
E/WifiStateMachine(  895):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  895): processMsg: L2ConnectedState
E/WifiStateMachine(  895):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 5909): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5909): environment dirty rate=0 [9][0][0]
D/WIFI_ICON( 1130): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  895): fetchRssiLinkSpeedAndFrequencyNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  895): fetchRssiLinkSpeedAndFrequencyNative rssi=-52 linkspeed=150
E/WifiConfigStore(  895): updateConfiguration freq=5220 BSSID=c0:ff:d4:d3:aa:4a RSSI=-52 "NG7005g"WPA_PSK
W/WifiHW  (  895): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 5909): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 5909): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  895): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  895): WifiMonitor:wlan0 cnt=22 dispatchEvent: BLACKLIST CLEAR 
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiWatchdogStateMachine(  895): RSSI current: 0 new: -52, 3
E/WifiStateMachine(  895): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: COMPLETED, RSSI: -52, Link speed: 150, Frequency: 5220, Net ID: 3, Metered hint: false
D/ConnectivityService(  895): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  895): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, Supplicant state: COMPLETED, RSSI: -52, Link speed: 150, Frequency: 5220, Net ID: 3, Metered hint: false
D/ConnectivityService(  895): Adding iface wlan0 to network 100
E/WifiStateMachine(  895): transitionTo: destState=ConnectedState
E/WifiStateMachine(  895): handleMessage: new destination call exit/enter
V/NetworkPolicy(  895): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  895): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
V/NetworkPolicy(  895): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  895): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  895): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  895): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  895): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  895): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  895): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/HtcWifiWanDetect(  895): WAN detection,
E/WifiStateMachine(  895): handleMessage: X
D/HtcWifiWanDetect(  895): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
,I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false),
I/IntentController( 1130): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  895): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 9
D/WIFI_ICON( 1130): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiDataStallTracker(  895): ENABLE_DATA_MONITOR_POLL true Token 1
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiDataStallTracker(  895): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
E/ConnectivityService(  895): Unexpected mtu value: 0, wlan0
E/WifiTrafficPoller(  895): ENABLE_TRAFFIC_STATS_POLL false Token 10
D/ConnectivityService(  895): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/WISPrService( 5072): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  895): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
E/WifiStateMachine(  895): handleMessage: E msg.what=131131
D/ConnectivityService(  895): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
E/WifiStateMachine(  895): processMsg: ConnectedState
D/ConnectivityService(  895): Setting Dns servers for network 100 to [/192.168.1.1]
E/WifiStateMachine(  895):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
D/Nat464Xlat(  895): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
E/WifiStateMachine(  895): processMsg: L2ConnectedState
D/ConnectivityService(  895): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  895):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
D/ConnectivityService(  895): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  895): processMsg: ConnectModeState
D/ConnectivityService(  895): rematching NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  895):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
D/ConnectivityService(  895):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  895): handleMessage: X
D/ConnectivityService(  895):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/ConnectivityService(  895):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  895): currentScore = 0, newScore = 20
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  895):    accepting network in place of null
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  895): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  895): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/CSLegacyTypeTracker(  895): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  895): sendGeneralBroadcast, restrictEnable=false
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIA,TE
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/PMS     (  895): acquireWL(3595d340): PARTIAL_WAKE_LOCK  NetworkStats 0x1 895 1000 null
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
V/NetworkPolicy(  895): ensureActiveMobilePolicyLocked()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/DATA_ICON( 1130): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Connected:true/Type:1/Status:0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Connected
V/NetworkPolicy(  895): updateNetworkEnabledLocked()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
V/NetworkPolicy(  895): updateIfacesLocked()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Validated
V/NetworkPolicy(  895): updateNotificationsLocked()
D/usbnet  (  895): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/PMS     (  895): releaseWL(3595d340): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/usbnet  (  895):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1130): dataConnected: false/false
D/WIFI    (  895): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/usbnet  (  895): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
V/NetworkPolicy(  895): updateNetworkEnabledLocked()
D/WIFI    (  895):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  895): updateNotificationsLocked()
D/WIFI    (  895): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  895): sendGeneralBroadcastDelayed, restrictEnable=false
D/WirelessDisplayService(  895): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/ConnectivityService(  895): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  895):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  895): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  895): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
D/ConnectivityService(  895):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/ConnectivityService(  895):  sending notification for, NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  895): [NET] android_getaddrinfofornet-, pass to proxy
D/ConnectivityService(  895): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  895): [NET] android_getaddrinfo_proxy+
D/ConnectivityService(  895): Validated NetworkAgentInfo [WIFI () - 100]
D/libc    (  895): [NET] android_getaddrinfo_proxy get netid:0
D/ConnectivityService(  895): rematching NetworkAgentInfo [WIFI () - 100]
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/ConnectivityService(  895):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/ConnectivityService(  895):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  458): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/ConnectivityService(  895): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/libc    (  458): [NET] android_getaddrinfofornet-, err=7
D/ConnectivityService(  895): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/libc    (  895): [NET] android_getaddrinfo_proxy-, NODATA
D/ConnectivityService(  895):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QuickSettingWifi( 1130): receive.wifiConnect:true wifiAPname:NG7005g elapse:1
D/ConnectivityService(  895):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QuickSettingWifi( 1130): receive.wifiConnect:true wifiAPname:NG7005g elapse:0
D/ConnectivityService(  895): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  895): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
D/ConnectivityService(  895): sendGeneralBroadcast, restrictEnable=false
D/WISPrService( 5072): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/WifiStateMachine(  895): handleMessage: E msg.what=131131
D/DATA_ICON( 1130): updateConnectivity android.net.conn.INET_CONDITION_ACTION Connected:true/Type:1/Status:100
E/WifiStateMachine(  895): processMsg: ConnectedState
D/DATA_ICON( 1130): dataConnected: false/false
E/WifiStateMachine(  895):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
D/StatusBar.NetworkController( 1130): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  895): processMsg: L2ConnectedState
E/WifiStateMachine(  895):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
E/WifiStateMachine(  895): processMsg: ConnectModeState
E/WifiStateMachine(  895):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
E/WifiStateMachine(  895): handleMessage: X
D/ConnectivityManager.CallbackHandler( 1130): CM callback handler got msg 524290
I/SecurityController( 1130): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1130): CM callback handler got msg 524290
I/SecurityController( 1130): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  895): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  895):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  895): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/usbnet  (  895): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  895):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  895): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 24(0x666538303a3a32),sn(),hints(known),family 0,flags 4,
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS,
D/ConnectivityService(  895): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
E/WifiStateMachine(  895): handleMessage: E msg.what=131212
D/ConnectivityService(  895): identical MTU - not setting
E/WifiStateMachine(  895): processMsg: ConnectedState
D/Nat464Xlat(  895): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true,
,E/WifiStateMachine(  895):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  895): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  895): processMsg: L2ConnectedState
D/ConnectivityService(  895):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  895):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  895):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  895): processMsg: ConnectModeState
D/ConnectivityService(  895): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,E/WifiStateMachine(  895):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  895): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  895): processMsg: DriverStartedState
D/ConnectivityService(  895):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  895):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  895):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
D/ConnectivityService(  895): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  895):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine(  895): Link configuration changed for netId: 3 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::2ee:bdff:fedd:33d2/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  895): updateLinkProperties nid: 3 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
E/WifiStateMachine(  895): handleMessage: X
D/ConnectivityManager.CallbackHandler( 1130): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1130): CM callback handler got msg 524295
,D/PMS     (  895): acquireWL(1aa8a279): PARTIAL_WAKE_LOCK  *alarm* 0x1 895 1000 WorkSource{1000}
,V/AlarmManager(  895): sending alarm PendingIntent{1de43bbe: PendingIntentRecord{3755841f com.google.android.gms broadcastIntent}}, i=ALARM_WAKEUP_LOCATOR, t=2, cnt=1, w=139955, Int=0
,D/PMS     (  895): acquireWL(2ca4e36c): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1658 10025 null
D/PMS     (  895): releaseWL(1aa8a279): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/WifiService(  895): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3988f3aa}
D/PMS     (  895): releaseWL(906d695): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{1000 android}
D/PMS     (  895): acquireWL(1107ed35): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1658 10025 null
D/PMS     (  895): acquireWL(16a455ca): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1658 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(1107ed35): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  895): acquireWL(1a58433b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1658 10025 null
D/PMS     (  895): releaseWL(16a455ca): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(1a58433b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  895): acquireWL(16b2ca58): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1658 10025 WorkSource{1000 android}
,D/PMS     (  895): releaseWL(16b2ca58): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{1000 android}
D/PMS     (  895): acquireWL(3bd727b1): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1658 10025 null
D/PMS     (  895): releaseWL(3bd727b1): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  895): releaseWL(2ca4e36c): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/PMS     (  895): acquireWL(2c9a0496): PARTIAL_WAKE_LOCK  *alarm* 0x1 895 1000 WorkSource{10025},
,V/AlarmManager(  895): sending alarm PendingIntent{cfdd817: PendingIntentRecord{154525c8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=140237, Int=0
D/PMS     (  895): acquireWL(18b63404): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1753 10025 WorkSource{10025 com.google.android.gms},
D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/PMS     (  895): releaseWL(2c9a0496): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10025}
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1753): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 1753): [NET] android_getaddrinfo_proxy+
D/libc    ( 1753): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1753): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
,D/wpa_supplicant( 5909): random: Got 4/4 bytes from /dev/random,
D/wpa_supplicant( 5909): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,D/PMS     (  895): acquireWL(8858ded): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1753 10025 WorkSource{10025 com.google.android.gms},
,D/GCM     ( 1753): Connected,
,D/PMS     (  895): releaseWL(18b63404): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10025 com.google.android.gms},
,D/GCM     ( 1753): Message class com.google.f.a.a.p,
I/ActivityManager(  895): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6151 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/PMS     (  895): releaseWL(8858ded): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): acquireWL(469d422): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(469d422): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
,W/ResourcesManager( 6151): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/Babel_SMS( 6151): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 6151): MmsConfig.loadMmsSettings,
,I/ActivityManager(  895): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6186 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6151, uid=10120, userID:0,
,W/HtcWrapAdjustableCursorFactory( 6186): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 6186): onCreate,
,D/MmsCustomizationProvider( 6186): query uri: content://htc-mms-customization/mms-ua/ua_string,
,D/PMS     (  895): releaseWL(258c434d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,W/Settings( 6151): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/GetPrviateResource( 6186): GetPrviateResource
,V/GetPrviateResource( 6186): GetPrviateResource
,D/MmsCustomizationProvider( 6186): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 6151): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
,I/Babel_SMS( 6151): MmsConfig.loadFromDatabase
D/MessageCustFlag( 6186): sense_version=6.0
I/Babel_Crash( 6151): startup - clean,
D/BTAccessoryUtil( 6186): createReceiver
E/Babel_SMS( 6151): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6151): MmsConfig.loadFromResources
D/BTAccessoryUtil( 6186): registerReceiver return intent = null,
,D/MessageCustFlag( 6186): sku_id=99
,D/HtcBuildUtils( 6186): getRATByHtcTelephonyCapability:1,
W/SystemReader( 6186): Cannot find qct_8960_interface, use default value instead,
,E/Babel_SMS( 6151): canonicalizeMccMnc: invalid mccmnc nullnull,
I/Babel_SMS( 6151): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
,I/Babel   ( 6151): deleted: false for 0,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6151, uid=10120, userID:0
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6151, uid=10120, userID:0
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6151, uid=10120, userID:0,
I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6151, uid=10120, userID:0,
I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6151, uid=10120, userID:0,
,W/VideoCapabilities( 6151): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6151): Unsupported mime video/x-ms-wmv,
,W/AudioCapabilities( 6151): Unsupported mime audio/qcelp,
,W/AudioCapabilities( 6151): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6151): Unsupported mime audio/qcelp,
,W/VideoCapabilities( 6151): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 6151): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6151): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6151): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6151): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6151): Unrecognized profile 2130706433 for video/avc,
,D/Process (  895): killProcessQuiet, pid=3799,
I/ActivityManager(  895): Killing 3799:com.google.android.gms/u0a25 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 3799
,D/Process (  895): killProcessQuiet, pid=5491,
I/ActivityManager(  895): Killing 5491:com.google.android.apps.docs/u0a107 (adj 15): empty #18
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 5491
,D/Process (  895): killProcessQuiet, pid=5491,
W/libprocessgroup(  895): failed to open /acct/uid_10107/pid_5491/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  895): failed to open /acct/uid_10025/pid_3799/cgroup.procs: No such file or directory
D/Process (  895): killProcessQuiet, pid=3799
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/vclib   ( 6151): onServiceConnected
,W/Babel   ( 6151): Attempted to change video mute state without an active call.
,E/SQLiteLog( 1753): (283) recovered 63 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal,
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  895): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  895): [NET] android_getaddrinfo_proxy+
D/libc    (  895): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/HtcWifiWanDetect(  895): Find DNS Address www.htc.com/104.81.130.175
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  895): [NET] android_getaddrinfo_proxy-, success
,D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/Tethering(  895): Tethering got CONNECTIVITY_ACTION
I/AlarmManager(  895): [AlarmQueuing] connectivity wifi: true
D/Tethering(  895): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/htcCheckinService(  895): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  895): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  895): [NET] android_getaddrinfo_proxy+
D/libc    (  895): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/htcCheckinService(  895): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/GpsLocationProvider(  895): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  895): acquireWL(eabf1a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 895 1000 null
,D/PMS     (  895): acquireWL(2494d159): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 895 1000 null
,I/ConnectivityHelper( 1493): [onReceive] WIFI(1): CONNECTED,
I/ActivityManager(  895): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6222 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  895): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  895): acquireWL(2efc711e): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 895 1000 WorkSource{10025},
,D/AlarmManager(  895): Ignore time set to 1447848448746 in setTime(); too close to current time 1447848449677,
,I/MusicStore( 6222): Database version: 120
,I/ActivityManager(  895): Start proc com.google.android.gms for service com.google.android.gms/.auth.api.credentials.sync.CredentialSyncService: pid=6254 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
D/PMS     (  895): acquireWL(3bfa812a): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 895 1000 WorkSource{10025},
,D/PMS     (  895): releaseWL(3bfa812a): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10025}
,D/PMS     (  895): acquireWL(362e0b82): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 895 1000 WorkSource{10025}
,D/PMS     (  895): releaseWL(2494d159): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
I/IntentController( 1130): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
W/ResourcesManager( 6254): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6254): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  895): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  895): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6222): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/MultiDex( 6254): VM with version 2.1.0 has multidex support,
I/MultiDex( 6254): install
I/MultiDex( 6254): VM has multidex support, MultiDex support library is disabled.
,E/GpsLocationProvider(  895): No APN found to select.
,D/PMS     (  895): acquireWL(27f05be8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 895 1000 null
,D/PMS     (  895): releaseWL(27f05be8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  895): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  895): NTP server returned: 1447848448746 (Wed Nov 18 13:07:28 CET 2015) reference: 142057 certainty: 14 system time offset: -1037
,D/GpsLocationProvider(  895): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  895): releaseWL(eabf1a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/GpsLocationProvider(  895): handleReportAgpsStatus with type = 12090status = 30767ipaddr = [B@30b1bd3d,
D/PMS     (  895): acquireWL(3d845932): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 895 1000 null
D/GpsLocationProvider(  895): Received Unknown AGPS status: 30767
D/GpsLocationProvider(  895): xtraDownloadRequest
D/GpsLocationProvider(  895): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  895): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  895): acquireWL(33336683): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 895 1000 null
,D/PMS     (  895): releaseWL(3d845932): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 20(0x78747261332e67),sn(),hints(known),family 0,flags 4
,D/libc    (  895): [NET] android_getaddrinfofornet-, err=8
D/libc    (  895): [NET] android_getaddrinfofornet+,hn 20(0x78747261332e67),sn(),hints(known),family 0,flags 1024
D/libc    (  895): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  895): [NET] android_getaddrinfo_proxy+
D/libc    (  895): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  458): [NET] android_getaddrinfofornet+,hn 20(0x78747261332e67),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/PhoneStatusBar( 1130): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020652 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 6222): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6222): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6222): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6222): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6254): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/JNIHelp ( 6222): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  895): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  895): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233392e),sn(),hints(known),family 0,flags 4
D/libc    (  895): [NET] android_getaddrinfofornet-, SUCCESS
,W/ActivityThread( 6254): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6254): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f883701: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6254): Installed default security provider GmsCore_OpenSSL
,D/GpsLocationProvider(  895): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  895): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
W/GpsLocationProvider(  895): [handleDownloadXtraData] XTRA Downloading, return
,D/PMS     (  895): acquireWL(3309dc8a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 895 1000 null
,D/PMS     (  895): releaseWL(3309dc8a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/ActivityThread( 6222): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6222): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1029f383: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6222): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6222): GMSCore installation verified
,I/ConfigStore( 6222): Config Database version: 1
,W/art     ( 6254): Suspending all threads took: 6.738ms
,D/GpsLocationProvider(  895): [handleDownloadXtraData] calling native_inject_xtra_data,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6222, uid=10167, userID:0,
,D/WifiDisplayAdapter(  895): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  895):     Client/Owner: Client
D/WifiDisplayAdapter(  895):     GroupId: 
D/WifiDisplayAdapter(  895):     Passphrase: 
D/WifiDisplayAdapter(  895):     SessionId: 0
D/WifiDisplayAdapter(  895):     IP Address: }
,D/MediaRouterService(  895): Client com.google.android.music (pid 6222): Registered
,D/WifiDisplayAdapter(  895): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  895):     Client/Owner: Client
D/WifiDisplayAdapter(  895):     GroupId: 
D/WifiDisplayAdapter(  895):     Passphrase: 
D/WifiDisplayAdapter(  895):     SessionId: 0,
D/WifiDisplayAdapter(  895):     IP Address: }
,I/MediaRouter( 6222): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6222): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6222): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6222): type=WIFI subType= reason=null isConnected=true,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6222, uid=10167, userID:0,
,I/ActivityManager(  895): Start proc com.fitbit.FitbitMobile for broadcast com.fitbit.FitbitMobile/.NetworkStateReceiver: pid=6293 uid=10023 gids={50023, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a,
,I/GHttpClientFactory( 6222): Using our fixed implementation of GMSCore's GoogleHttpClient,
,I/GoogleURLConnFactory( 6222): Using platform SSLCertificateSocketFactory,
,D/Process (  895): killProcessQuiet, pid=5168,
I/ActivityManager(  895): Killing 5168:com.google.android.apps.plus/u0a176 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 5168,
,D/Process (  895): killProcessQuiet, pid=5168,
W/libprocessgroup(  895): failed to open /acct/uid_10176/pid_5168/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  895): acquireWL(20a4488d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 895 1000 null
W/DriveInitializer( 6254): Background init thread started
,D/PMS     (  895): releaseWL(20a4488d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/GLSActivity( 1753): [ac] getting account id
,W/DriveInitializer( 6254): Awaiting to be initialized
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/,
W/ContextImpl( 6254): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,D/GpsLocationProvider(  895): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  895): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  895):  [handleDownloadXtraData]inject done.
D/PMS     (  895): acquireWL(236fc45): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 895 1000 null
,D/GpsLocationProvider(  895): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  895): releaseWL(33336683): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,I/art     ( 1753): Explicit concurrent mark sweep GC freed 8187(411KB) AllocSpace objects, 2(32KB) LOS objects, 49% free, 4MB/8MB, paused 734us total 26.299ms,
D/PMS     (  895): releaseWL(236fc45): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/GLSUser ( 1753): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,W/System.err(  895): java.lang.Throwable: stack dump
D/BluetoothManagerService(  895): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  895): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a666cc0:true
W/System.err(  895): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  895): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  895): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  895): 	at android.os.Binder.execTransact(Binder.java:454)
,I/art     (  895): Explicit concurrent mark sweep GC freed 45757(2MB) AllocSpace objects, 6(137KB) LOS objects, 33% free, 17MB/25MB, paused 1.066ms total 72.813ms
,D/Messaging( 6186): supportCMAS(SIE)/init? false/true
D/MmsConfig( 6186): networkCode: 
D/MessageCustFlag( 6186): sku_id=99
D/MmsConfig( 6186): SIE smsPri: null
D/MmsConfig( 6186): networkCode: 
,D/MmsConfig( 6186): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 6186): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6186): 
D/MmsAsyncWorkHandler( 6186): HM tk = 20001
,D/SettingsManager( 6186): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@39d2675e
D/ReportIndicatorCache( 6186): MSG_QUERY_REPORTS >>
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 108
D/AccFlag ( 1445): sku_id=99
,D/DraftCache( 6186): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 6186): [DraftCache/1] refresh
,D/Messaging( 6186): mNeedToUpdateDate2 start
,W/DriveInitializer( 6254): Background init thread ended
,D/DraftCache( 6186): [DraftCache/806] rebuildCache
I/Messaging( 6186): mccmnc> 
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 108
D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/MmsConfig( 6186): networkCode: 
,D/Messaging( 6186): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/Messaging( 6186): mNeedToUpdateDate2: false
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65,
D/Jerry   ( 1445): URI_DRAFT
D/DraftCache( 6186): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 6186): [DraftCache/806] rebuildCache time: 6
D/MmsAsyncWorkHandler( 6186): 
D/MmsAsyncWorkHandler( 6186): HM tk = 20002
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
D/AccFlag ( 1445): sku_id=99
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/AccFlag ( 1445): sku_id=99
,D/Messaging( 6186): ViewCache CreatePreloadOnlyConversationList
,D/MessageCustFlag( 6186): sense_version=6.0
,D/Jerry   ( 6186): start to preload cursor >>>>>>>
,D/PhoneStorageUtil( 6186): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 6186): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6186): createReceiver
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
D/MmsSmsV2Provider( 1445):  slotId = -1000
,D/HockeyApp( 6293): Current handler class = com.android.internal.os.RuntimeInit$UncaughtHandler
,D/Messaging( 6186): ViewCache CreatePreload
D/Messaging( 6186): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Process (  895): killProcessQuiet, pid=5388,
I/ActivityManager(  895): Killing 5388:com.android.defcontainer/u0a15 (adj 15): empty #17,
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/Cust_MMSMS( 6186): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6186): def_index: 0
,I/ActivityManager(  895): Recipient 5388,
,D/PMS     (  895): acquireWL(a5f94c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 895 1000 null,
,D/AutoSetting( 1413): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
D/TelephUtils( 1445): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
V/MmsProvider( 1445): Update uri=content://mms, match=0
V/MmsProvider( 1445): selection=st=129 AND m_type!=134
,I/ActivityManager(  895): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.OneTimeOnConnectedReceiver: pid=6353 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/PMS     (  895): releaseWL(2efc711e): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10025}
D/Process (  895): killProcessQuiet, pid=5388
W/libprocessgroup(  895): failed to open /acct/uid_10015/pid_5388/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Messaging( 6186): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6186): TransactionService is going to be woken up.
D/AutoSetting( 1413): service - onCreate()
,V/TransactionService( 6186): 1-Creating TransactionService
D/PMS     (  895): releaseWL(a5f94c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MsgPreferenceUtils( 6186): globalIndex = 1,
,D/MsgPreferenceUtils( 6186): phone state: true
D/MsgPreferenceUtils( 6186): sd state: false
D/MsgPreferenceUtils( 6186): vIndex = 0
,V/TransactionService( 6186): onStartCommand: 1
D/MmsSystemEventReceiver( 6186): unRegisterForConnectionStateChanges
V/TransactionService( 6186): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6186): Loading previous transactions.
,D/AutoSetting( 1413): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1413): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1413): Util - check NLP state, Allowned:true, Enabled:true
D/LocationManagerService(  895): request 3482e7b passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10054)
D/LocationManagerService(  895): provider request: passive ProviderRequest[ON interval=0]
,D/PMS     (  895): acquireWL(199bca4d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 895 1000 null
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1445): device_type: 1
,D/PMS     (  895): releaseWL(362e0b82): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10025}
D/TransactionService( 6186): Force set service start id to 1
,V/TransactionService( 6186): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6186): unRegisterForConnectionStateChanges
D/TransactionService( 6186): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6186): Destroying TransactionService
,I/ActivityManager(  895): Killing 5553:com.htc.mms.backupagent/u0a79 (adj 15): empty #17,
D/Process (  895): killProcessQuiet, pid=5553
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 5553,
,V/TransactionService( 6186): 4-Handling incoming message: { when=-100ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Process (  895): killProcessQuiet, pid=5553
W/libprocessgroup(  895): failed to open /acct/uid_10079/pid_5553/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  895): acquireWL(2386c902): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 895 1000 WorkSource{10025}
,D/PMS     (  895): releaseWL(199bca4d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  895): acquireWL(2d930c6f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 895 1000 null
,D/PMS     (  895): releaseWL(2d930c6f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  895): acquireWL(2404d7c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 895 1000 null,
,D/PMS     (  895): releaseWL(2386c902): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10025}
,D/PMS     (  895): releaseWL(2404d7c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/IntentController( 1130): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,E/cutils-trace( 6388): Error opening trace file: No such file or directory (2)
,I/dex2oat ( 6388): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=21 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6388): dex2oat took 801.810ms (threads: 4)
,I/PushClient( 6353): ApplicationMonitor {dfda85b}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6353): ApplicationMonitor {dfda85b}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6353): ApplicationMonitor {dfda85b}: logBasicAppInfo(): VersionName:             1.2.848061
I/PushClient( 6353): ApplicationMonitor {dfda85b}: logBasicAppInfo(): VersionCode:             148001212
,I/PushClient( 6353): ApplicationMonitor {dfda85b}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6353): ApplicationMonitor {dfda85b}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6353): ApplicationMonitor {dfda85b}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6353): ApplicationMonitor {dfda85b}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6353): ApplicationMonitor {dfda85b}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=2, flag=1, pid=6353, uid=10074, userID:0
,I/ActivityManager(  895): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6395 uid=10080 gids={50080, 9997, 3003} abi=armeabi-v7a,
I/PushClient( 6353): OnConnectedHandler {26e46f37}: handle(): Try update on network connected.
I/PushClient( 6353): PnsModel {1ed99b6a}: update(): Update registration caused by: android.net.conn.CONNECTIVITY_CHANGE
I/PushClient( 6353): PnsConfigModel {14f42dc5}: <init>(): Use dm-client for provisioning.
,I/art     (  470): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 455us total 11.515ms
,I/art     (  470): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 188us total 8.884ms
,I/art     (  470): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 135us total 8.809ms
,W/System.err( 6353): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6353): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6353): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,D/PhoneMonitor( 6395): Register our PhoneStateListener
,W/ContextImpl( 6353): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,D/MobileConnectivityChangeReceiver( 6395): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6395): onReceive CONNECTIVITY_CHANGE networkType=1
,D/PhoneMonitor( 6395): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6395): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  895): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6415 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
D/Process (  895): killProcessQuiet, pid=5632
I/ActivityManager(  895): Killing 5632:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  895): Recipient 5632
D/WifiService(  895): Client connection lost with reason: 4
,D/Process (  895): killProcessQuiet, pid=5632
W/libprocessgroup(  895): failed to open /acct/uid_1000/pid_5632/cgroup.procs: No such file or directory,
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  895): acquireWL(3705ef5f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 6254 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): acquireWL(2f686a75): PARTIAL_WAKE_LOCK  Checkin Service 0x1 6254 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(3705ef5f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
,I/CheckinService( 6254): Disabling old GoogleServicesFramework version
I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=6254, uid=10025, userID:0
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=6254, uid=10025, userID:0
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=6254, uid=10025, userID:0,
,I/DeviceManagement( 6415): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=6415 dbg=false s=true,
,I/CheckinService( 6254): Checking schedule, now: 1447848452014 next: 1447844379677,
I/CheckinService( 6254): active receiver: enabled
I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=6254, uid=10025, userID:0
,I/DeviceManagement( 6415): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]],
I/DeviceManagement( 6415): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/CheckinService( 6254): Preparing to send checkin request,
I/DeviceManagement( 6415): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10074) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6415): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
I/DeviceManagement( 6415): WorkflowService: Starting workflow service,
,I/EventLogService( 6254): Accumulating logs since 1447848351596
,I/DeviceManagement( 6415): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@5964555] args=[Bundle[mParcelledData.dataSize=728]],
,I/DeviceManagement( 6415): NetworkChangeWorkflow: ==================================================,
I/DeviceManagement( 6415): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
I/DeviceManagement( 6415): NetworkChangeWorkflow: ==================================================
,I/ActivityManager(  895): Start proc com.twitter.android for broadcast com.twitter.android/.client.AppBroadcastReceiver: pid=6441 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DeviceManagement( 6415): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6415): SessionStateController: Checking invariants...
,I/CheckinRequestBuilder( 6254): Checkin reason type: 8 attempt count: 1,
,E/WifiTrafficPoller(  895): ADD_CLIENT: 8
,D/WifiService(  895): New client listening to asynchronous messages
I/ActivityManager(  895): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 6254): Failed to find provider info for com.google.android.wearable.settings
,I/DeviceManagement( 6415): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 6415): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6415): ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm,
,I/DeviceManagement( 6415): ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
I/DeviceManagement( 6415): DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,I/DeviceManagement( 6415): Perf: *** Cache update - start...
I/DeviceManagement( 6415): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 6415): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 6415): Perf: *** Enabled app cache update - complete: 1 ms,
,I/DeviceManagement( 6415): Perf: *** Config cache update - start...
,I/DeviceManagement( 6415): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 6415): ConfigCacheController: *** Device manifest update is pending...
,I/DeviceManagement( 6415): ConfigCacheController: *** Sending device manifest...
,I/Crashlytics( 6441): Initializing Crashlytics 1.1.13.10,
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 6441): [NET] android_getaddrinfofornet+,hn 24(0x73657474696e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 6441): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6441): [NET] android_getaddrinfofornet+,hn 24(0x73657474696e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 6441): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6441): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6441): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 24(0x73657474696e67),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.twitter.android/cache/,
I/ActionCombine( 1753): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6441): Failed to ensure directory: /storage/ext_sd/Android/data/com.twitter.android/cache
,W/ResourcesManager( 1130): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/ResourcesManager( 1130): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1193): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/ResourcesManager( 1193): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1193): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1193): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1193): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/CheckinRequestBuilder( 6254): awaiting user notification for token,
D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6441): [NET] android_getaddrinfo_proxy-, success
,I/RemoteViews( 1130): apply : com.google.android.gms 0 6 3 40,
,I/art     ( 6415): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,I/art     ( 6415): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.twitter.android/cache/
,W/Vold    (  362): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6441): Failed to ensure directory: /storage/ext_sd/Android/data/com.twitter.android/cache
,I/ActivityManager(  895): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6476 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.twitter.android, clsName=com.twitter.android.samsung.single.TwitterWidgetProvider, state=2, flag=1, pid=6441, uid=10181, userID:0
,W/ResourcesManager( 6476): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6476): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/System.err( 6415): Starting the internal HTTP client
,I/MultiDex( 6476): VM with version 2.1.0 has multidex support
,I/MultiDex( 6476): install
I/MultiDex( 6476): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6476): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/DeviceManagement( 6415): DeviceClientResource: Active network...
I/DeviceManagement( 6415):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BuildInfo( 6415): Created new instance: com.htc.cs.lib.hms.BuildInfo@cf3b5af
,I/DeviceManagement( 6415): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
,I/System.out( 6415): isCompatible false
,I/System.out( 6415): createObjectMapper
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
,W/ActivityThread( 6476): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6476): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24e7de2b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6476): Installed default security provider GmsCore_OpenSSL
,I/art     (  895): Explicit concurrent mark sweep GC freed 15841(817KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 17MB/25MB, paused 1.690ms total 64.414ms
D/PMS     (  895): acquireWL(2f17a15e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,D/ConnectivityService(  895): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10025
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): ValidatedState{ when=0 what=532488 arg1=10025 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  895): Validated NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): DefaultState{ when=0 what=532488 arg1=10025 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  895): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Forcing reevaluation
D/ConnectivityService(  895):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  895):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Validated
D/ConnectivityService(  895): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityManager.CallbackHandler( 1130): CM callback handler got msg 524290
D/ConnectivityService(  895): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
I/SecurityController( 1130): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  895):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  895):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  895): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/PMS     (  895): releaseWL(2f17a15e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm,
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GcmGroups( 6254): Failed to subscribe to group.,
I/GcmGroups( 6254): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 6254): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 6254): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 6254): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 6254): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 6254): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 6254): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 6254): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 6254): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 6254): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 6254): 	at android.os.Looper.loop(Looper.java:155)
I/GcmGroups( 6254): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/InstanceID/Rpc( 6254): Found 10025
,I/GcmGroups( 6254): Groups upload failed, retrying in 24000:00:00
,D/libc    ( 6415): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 6415): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6415): [NET] android_getaddrinfo_proxy+
D/libc    ( 6415): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6415): [NET] android_getaddrinfo_proxy-, success
,I/WVCdm   (  463): CdmEngine::OpenSession
I/WVCdm   (  463): Level3 Library Sep 25 2014 17:10:03
,D/libc    ( 6415): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4
,D/libc    ( 6415): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6415): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    ( 6415): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6415): [NET] android_getaddrinfo_proxy+
D/libc    ( 6415): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  458): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
,D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/WVCdm   (  463): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=6254, uid=10025, userID:0,
,D/DrmWidevineDash(  463): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  463): Service_Initialize: starts!
D/QSEECOMAPI: (  463): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  463): App is not loaded in QSEE
,D/QSEECOMAPI: (  463): Loaded image: APP id = 3
D/DrmWidevineDash(  463): Service_Initialize: ends! returns 0,
D/DrmWidevineDash(  463): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb447f000
E/DrmWidevineDash(  463): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb447f000
,D/DrmWidevineDash(  463): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  463): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  463): hlos api version =  9
D/DrmWidevineDash(  463): tz api version =  8
D/DrmWidevineDash(  463): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  463): OEMCrypto_IsKeyboxValid: starts!
I/iu.SyncManager( 6254): SYNC; picasa accounts
,D/DrmWidevineDash(  463): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  463): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  463): OEMCrypto_OpenSession: starts! SID=0xbed52308
D/DrmWidevineDash(  463): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  463): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  463): OEMCrypto_GetRandom: starts! randomData=0xb9056770, dataLength=8
D/DrmWidevineDash(  463): OEMCrypto_GetRandom: ends! returns 0
,D/NetworkLogImpl( 6254): Loaded NetworkSpeedPredictor
,D/DrmWidevineDash(  463): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8fd2080, wrapped_rsa_key_length=1280
I/iu.Environment( 6254): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/DrmWidevineDash(  463): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  463): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  463): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  463): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  463): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  463): OEMCrypto_GetDeviceID: starts! deviceID=0xb8fd0950, idLength=0xb47a7718
,D/DrmWidevineDash(  463): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  463): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  463): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  463): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  463): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  463): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  463): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  463): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  463): hlos api version =  9
D/DrmWidevineDash(  463): tz api version =  8
D/DrmWidevineDash(  463): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  463): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  463): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  463): PrepareKeyRequest: nonce=822321555
D/DrmWidevineDash(  463): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8fd72e8
D/DrmWidevineDash(  463): message_length=1591, signature=0xb8fd0f28, signature_length=3027924732
,D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6415): [NET] android_getaddrinfo_proxy-, success
,D/ChimeraCfgMgr( 6254): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 6254): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 6254): num queued entries: 0
,I/iu.UploadsManager( 6254): num updated entries: 0,
I/iu.SyncManager( 6254): NEXT; no task
,I/ActivityManager(  895): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6518 uid=10169 gids={50169, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc    ( 6151): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6151): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6151): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6151): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6151): [NET] android_getaddrinfo_proxy+
D/libc    ( 6151): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/DrmWidevineDash(  463): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  463): CdmEngine::CloseSession
D/DrmWidevineDash(  463): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  463): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  463): L3 Terminate.
D/DrmWidevineDash(  463): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  463): Service_Uninitialize: starts!
D/QSEECOMAPI: (  463): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  463): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  463): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  463): OEMCrypto_Terminate: ends! returns 0
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6151): [NET] android_getaddrinfo_proxy-, success
,D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1193): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1130): reapply : com.google.android.gms 2 40
,W/Kids    ( 6254): [AccountUtils] Account not ready,
W/Kids    ( 6254): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 6254): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 6254): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 6254): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 6254): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 6254): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 6254): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 6254): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 6254): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 6254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 6254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 6254): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 6151): connection state changed from UNKNOWN to CONNECTED
,I/jxcore-log( 5794): Attempting to connect to the test coordinator server,
I/jxcore-log( 5794): 
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6518): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/,
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6518): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6518): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6518):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6518):   adb logcat -s GAv4
,W/GAv4    ( 6518): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6518): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  362): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/,
W/ContextImpl( 6518): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  362): Returning OperationFailed - no handler for errno 0
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/GAv4    ( 6518): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 5794): Attempting to connect to the test coordinator server
I/jxcore-log( 5794): 
,W/GAv4    ( 6518): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/cutils-trace( 6545): Error opening trace file: No such file or directory (2)
,I/dex2oat ( 6545): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/jxcore-log( 5794): Attempting to connect to the test coordinator server
I/jxcore-log( 5794): 
,I/dex2oat ( 6545): dex2oat took 54.055ms (threads: 4),
,I/Adreno-EGL( 6476): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU (),
I/Adreno-EGL( 6476): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6476): Build Date: 12/11/14 Thu
I/Adreno-EGL( 6476): Local Branch: 
I/Adreno-EGL( 6476): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 6476): Local Patches: NONE
I/Adreno-EGL( 6476): Reconstruct Branch: NOTHING
,I/DeviceManagement( 6415): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6415): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6415): DeviceClientResourceController: handleDirectives: []
I/System.out( 6415): isCompatible false
I/System.out( 6415): createObjectMapper
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
I/System.out( 6415): isCompatible false
,I/WebViewFactory( 6518): Loading com.google.android.webview version 44.0.2403.90 (code 240309000),
,I/LibraryLoader( 6518): Time to load native libraries: 1 ms (timestamps 5713-5714),
I/LibraryLoader( 6518): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6518): Binding Chromium to main looper Looper (main, tid 1) {20237aa0},
I/LibraryLoader( 6518): Expected native library version number "",actual native library version number ""
I/chromium( 6518): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6518): Initializing chromium process, singleProcess=true
,W/art     ( 6518): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6518): ApplicationContext is null in ApplicationStatus
,W/chromium( 6518): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6518): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6518): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6518): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 6518): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6518): Build Date: 12/11/14 Thu
I/Adreno-EGL( 6518): Local Branch: 
I/Adreno-EGL( 6518): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 6518): Local Patches: NONE
I/Adreno-EGL( 6518): Reconstruct Branch: NOTHING
,I/Adreno-EGL( 6476): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 6476): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6476): Build Date: 12/11/14 Thu
I/Adreno-EGL( 6476): Local Branch: 
I/Adreno-EGL( 6476): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 6476): Local Patches: NONE
I/Adreno-EGL( 6476): Reconstruct Branch: NOTHING
,I/Adreno-EGL( 6476): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 6476): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6476): Build Date: 12/11/14 Thu
I/Adreno-EGL( 6476): Local Branch: 
I/Adreno-EGL( 6476): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 6476): Local Patches: NONE
I/Adreno-EGL( 6476): Reconstruct Branch: NOTHING
,I/jxcore-log( 5794): Attempting to connect to the test coordinator server
I/jxcore-log( 5794): 
W/AudioManagerAndroid( 6518): Requires BLUETOOTH permission
I/NSApplication( 6518): Starting up...
,I/jxcore-log( 5794): Attempting to connect to the test coordinator server
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Attempting to connect to the test coordinator server
I/jxcore-log( 5794): 
I/ActivityManager(  895): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6586 uid=10102 gids={50102, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
D/Process (  895): killProcessQuiet, pid=5660
I/ActivityManager(  895): Killing 5660:com.htc.mobiledata/u0a48 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  895): Recipient 5660
,I/WVCdm   (  463): CdmEngine::OpenSession,
I/WVCdm   (  463): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  463): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  463): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13,
D/DrmWidevineDash(  463): Service_Initialize: starts!
D/QSEECOMAPI: (  463): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  463): App is not loaded in QSEE
,D/QSEECOMAPI: (  463): Loaded image: APP id = 3,
,D/DrmWidevineDash(  463): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  463): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb447f000
E/DrmWidevineDash(  463): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb447f000
,D/DrmWidevineDash(  463): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  463): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  463): hlos api version =  9
D/DrmWidevineDash(  463): tz api version =  8
D/DrmWidevineDash(  463): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  463): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  463): OEMCrypto_IsKeyboxValid: ends! returns 0,
D/WVCdm   (  463): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  463): OEMCrypto_OpenSession: starts! SID=0xb47a7948
D/DrmWidevineDash(  463): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  463): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  463): OEMCrypto_GetRandom: starts! randomData=0xb8fd7680, dataLength=8
D/DrmWidevineDash(  463): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  463): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8fd2570, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  463): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  463): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  463): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  463): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  463): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  463): OEMCrypto_GetDeviceID: starts! deviceID=0xb8fd0990, idLength=0xb48a7718
D/DrmWidevineDash(  463): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  463): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  463): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  463): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  463): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  463): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  463): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  463): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  463): hlos api version =  9
D/DrmWidevineDash(  463): tz api version =  8
D/DrmWidevineDash(  463): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  463): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  463): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  463): PrepareKeyRequest: nonce=211365178
D/DrmWidevineDash(  463): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8ff3548
D/DrmWidevineDash(  463): message_length=1625, signature=0xb8ffd808, signature_length=3028973308
E/jxcore  ( 5794): Error!: Cannot find module '../../lib/thali-tape'
E/jxcore  ( 5794): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1604","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1604:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"10","_columnNumber":"12","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js:10:12"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"9","_columnNumber":"9","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:9:9"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"6","_columnNumber":"1","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:6:1"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"63","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:63:3"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.pr
,I/jxcore-log( 5794): {"type":"test","name":"setup","id":0}
I/jxcore-log( 5794): 
I/jxcore-log( 5794): LogCallback not set !!!!
I/jxcore-log( 5794): 
I/chromium( 5794): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../../lib/thali-tape'\nError: Cannot find module '../../lib/thali-tape'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1604:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js:10:12\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:9:9\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:6:1\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:63:3\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:253:5\n    at JXMobile.executeJSON@main.js:272:7\n    at @JX_Evaluate:1:1\n    "", source: file:///android_asset/www/js/thali_main.js (37)
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":,null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
W/libprocessgroup(  895): failed to open /acct/uid_10048/pid_5660/cgroup.procs: No such file or directory
I/DeviceManagement( 6415): ConfigCacheController: *** Update config cache: updating 9 entries...
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/DeviceManagement( 6415): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, statusCode=0, authCode=0>
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
D/Process (  895): killProcessQuiet, pid=5660
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
D/Process (  895): killProcessQuiet, pid=5689
I/ActivityManager(  895): Killing 5689:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityStack.destroyActivityLocked:3417 
,I/ActivityManager(  895): Recipient 5689
D/DrmWidevineDash(  463): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  463): CdmEngine::CloseSession
D/DrmWidevineDash(  463): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  463): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  463): L3 Terminate.
D/DrmWidevineDash(  463): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  463): Service_Uninitialize: starts!
D/QSEECOMAPI: (  463): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  463): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  463): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  463): OEMCrypto_Terminate: ends! returns 0
,W/PluginManager( 5794): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 86ms. Plugin should use CordovaInterface.getThreadPool().
,D/Process (  895): killProcessQuiet, pid=5689
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/libprocessgroup(  895): failed to open /acct/uid_10010/pid_5689/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6254): Classify the device as Phone.
,I/DeviceManagement( 6415): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/art     ( 1753): Explicit concurrent mark sweep GC freed 11309(620KB) AllocSpace objects, 5(405KB) LOS objects, 49% free, 4MB/8MB, paused 473us total 23.099ms
,I/DeviceManagement( 6415): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,D/libc    ( 6254): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 6254): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6254): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 6254): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6254): [NET] android_getaddrinfo_proxy+
D/libc    ( 6254): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/DeviceManagement( 6415): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, statusCode=0, authCode=0>,
,I/DeviceManagement( 6415): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, statusCode=0, authCode=0>
,D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6254): [NET] android_getaddrinfo_proxy-, success
,I/ActivityManager(  895): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6613 uid=10176 gids={50176, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 5723:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  895): killProcessQuiet, pid=5723
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  895): Recipient 5723
I/DeviceManagement( 6415): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.videohub.ui, versionKey=747235e1-123a-48e6-af18-c5967cf0b131, statusCode=0, authCode=0>
,D/libc    ( 6254): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 6254): [NET] android_getaddrinfofornet-, err=8
,D/Process (  895): killProcessQuiet, pid=5723
W/libprocessgroup(  895): failed to open /acct/uid_1000/pid_5723/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/DeviceManagement( 6415): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, statusCode=0, authCode=0>
,D/libc    ( 6254): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 6254): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6254): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 6254): [NET] android_getaddrinfofornet-, err=8
,W/ResourcesManager( 6613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinTask( 6254): Sending checkin request (9492 bytes)
,I/DeviceManagement( 6415): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, statusCode=0, authCode=0>,
,I/DeviceManagement( 6415): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, statusCode=0, authCode=0>
,D/StatusBarManagerService(  895): setSystemUiVisibility(0x700),
D/StatusBarManagerService(  895): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  895): hiding MENU key
,D/StatusBarManagerService(  895): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  895): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  895): hiding MENU key
,I/InputMethodManagerService(  895): Disable input method client, pid=5794,
D/StatusBarManagerService(  895): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 5794): reportFullscreenMode on inactive InputConnection
,I/DeviceManagement( 6415): ChangeEventReceiver: vvv Receive change event: <ConfigChangeEvent appID=com.htc.cs.dm, action=ADD, configID=0:0:2013-09-30T10:30:50.606Z, configJson={"bootstrapNameSet":"com.htc.cs","preloadNameSet":"com.htc.cs"}>,
I/DeviceManagement( 6415): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow] args=[Bundle[{changeEvent=<ConfigChangeEvent appID=com.htc.cs.dm, action=ADD, configID=0:0:2013-09-30T10:30:50.606Z, configJson={"bootstrapNameSet":"com.htc.cs","preloadNameSet":"com.htc.cs"}>}]]
,I/DeviceManagement( 6415): ChangeEventReceiver: vvv Receive change event: <AuthorizationChangeEvent appID=com.htc.cs.dm, action=ADD, configID=0:0:2013-09-30T10:30:50.606Z, authorizationCode=0, authorizationDataJson=null>
,I/DeviceManagement( 6415): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow] args=[Bundle[{changeEvent=<AuthorizationChangeEvent appID=com.htc.cs.dm, action=ADD, configID=0:0:2013-09-30T10:30:50.606Z, authorizationCode=0, authorizationDataJson=null>}]]
,I/DeviceManagement( 6415): AlarmController: Scheduling TTL alarm for: 2015.11.19 at 13:07:33.837 CET (due to: com.htc.launcher)
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=6415, uid=10105, userID:0
,I/DeviceManagement( 6415): Perf: *** Config cache update - complete: 1789 ms
I/DeviceManagement( 6415): Perf: *** Cache update - complete: 1792 ms
,I/DeviceManagement( 6415): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@5964555]
,I/DeviceManagement( 6415): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3526f3fa] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6415): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
I/DeviceManagement( 6415): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6415): SessionStateController: Checking invariants...
,I/DeviceManagement( 6415): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,D/Process (  895): killProcessQuiet, pid=5103,
,I/ActivityManager(  895): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=6639 uid=10037 gids={50037, 9997} abi=armeabi-v7a,
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  895): Killing 5103:com.android.vending/u0a75 (adj 15): empty #17
,I/ActivityManager(  895): Recipient 5103,
,I/DeviceManagement( 6415): SessionStateController: Checking invariants...
,D/Process (  895): killProcessQuiet, pid=5103
W/libprocessgroup(  895): failed to open /acct/uid_10075/pid_5103/cgroup.procs: No such file or directory
,D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/ActivityManager(  895): Killing 5960:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/Process (  895): killProcessQuiet, pid=5960
,D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  895): Recipient 5960,
,I/DeviceManagement( 6415): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6415): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3526f3fa]
,D/Process (  895): killProcessQuiet, pid=5960
,D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  895): failed to open /acct/uid_10042/pid_5960/cgroup.procs: No such file or directory
D/GCM     ( 1753): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/DeviceManagement( 6415): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow@3f244faa] args=[Bundle[mParcelledData.dataSize=416]]
,D/AuthorizationBluetoothService( 1753): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 6254): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PushClient( 6353): PnsModel {1ed99b6a}: update(): Start updating since the registration has expired.
,I/ActivityManager(  895): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6658 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
I/DeviceManagement( 6415): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow@3f244faa]
I/DeviceManagement( 6415): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow@3f244faa] args=[Bundle[mParcelledData.dataSize=316]]
I/DeviceManagement( 6415): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow@3f244faa]
I/DeviceManagement( 6415): WorkflowService: Stopping workflow service
D/Process (  895): killProcessQuiet, pid=5890
I/ActivityManager(  895): Killing 5890:com.htc.widget.hmsproc3/u0a36 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 5890
,W/PushClient( 6353): GCMRegistrator {34b7c6c}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.
W/PushClient( 6353):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6353):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 6353):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6353):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:237)
W/PushClient( 6353):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:375)
W/PushClient( 6353):   	at com.htc.cs.pns.receiver.OnConnectedHandler.handle(OnConnectedHandler.java:31)
W/PushClient( 6353):   	at com.htc.lib1.cs.AbstractIntentServiceBroadcastReceiver$HandleBroadcastService.handleBroadcast(AbstractIntentServiceBroadcastReceiver.java:123)
W/PushClient( 6353):   	at com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver$HandleBroadcastServiceImpl.handleBroadcast(OneTimeOnConnectedReceiver.java:33)
W/PushClient( 6353):   	at com.htc.lib1.cs.AbstractIntentServiceBroadcastReceiver$HandleBroadcastService.onHandleIntent(AbstractIntentServiceBroadcastReceiver.java:94)
W/PushClient( 6353):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65),
W/PushClient( 6353):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 6353):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6353):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6353):   
,D/Process (  895): killProcessQuiet, pid=5890
,W/libprocessgroup(  895): failed to open /acct/uid_10036/pid_5890/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6254, uid=10025, userID:0
,W/ResourcesManager( 6658): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6658): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6658): VM with version 2.1.0 has multidex support
,I/MultiDex( 6658): install
I/MultiDex( 6658): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6658): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/CheckinRequestBuilder( 6254): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  895): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 6254): Failed to find provider info for com.google.android.wearable.settings
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 108
D/AccFlag ( 1445): sku_id=99
,D/GCM     ( 6254): COMPAT: Multi user not supported
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
D/AccFlag ( 1445): sku_id=99
,D/GCM     ( 1753): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 108
D/AccFlag ( 1445): sku_id=99
,W/ActivityThread( 6658): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6658): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24e7de2b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6658): Installed default security provider GmsCore_OpenSSL
,D/LocationInitializer( 6254): Restart initialization of location
,D/AuthorizationBluetoothService( 1753): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
D/AccFlag ( 1445): sku_id=99
,D/WearableService( 6658): callingUid 10025, callindPid: 6658,
,V/GmsCoreStatsServiceLauncher( 6254): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 1753): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1753): [NET] android_getaddrinfo_proxy+
D/libc    ( 1753): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1753): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
,I/art     (  895): Explicit concurrent mark sweep GC freed 15919(753KB) AllocSpace objects, 2(97KB) LOS objects, 33% free, 17MB/25MB, paused 871us total 81.312ms,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6254, uid=10025, userID:0
,D/LocationInitializer( 6254): Restart initialization of location,
,E/MDM     ( 1658): [161] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/MDM     ( 1658): [161] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/PMS     (  895): acquireWL(39969c2a): PARTIAL_WAKE_LOCK  GCMSEND 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,I/ActivityManager(  895): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.dm2.ConfigChangeReceiver: pid=6690 uid=10032 gids={50032, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  895): Killing 5925:com.htc.videocenter/u0a91 (adj 15): empty #17,
D/Process (  895): killProcessQuiet, pid=5925
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  895): Recipient 5925,
,D/Process (  895): killProcessQuiet, pid=5925
W/libprocessgroup(  895): failed to open /acct/uid_10091/pid_5925/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/AuthorizationBluetoothService( 1753): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 6254): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6254, uid=10025, userID:0
,E/MDM     ( 1658): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 6254): Restart initialization of location
,D/GCM     ( 1753): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/GCM     ( 1753): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1193): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1130): reapply : com.google.android.gms 2 40
,W/CheckinRequestBuilder( 6254): awaiting user notification for token
,D/libc    ( 6353): [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 4,
D/libc    ( 6353): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6353): [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024
D/libc    ( 6353): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 6353): [NET] android_getaddrinfo_proxy+
D/libc    ( 6353): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/PMS     (  895): releaseWL(39969c2a): PARTIAL_WAKE_LOCK  GCMSEND 0x1 WorkSource{10025 com.google.android.gms},
D/GCM     ( 1753): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/CheckinRequestBuilder( 6254): Classify the device as Phone.,
,I/CheckinTask( 6254): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6254): Checking schedule, now: 1447848454835 next: 1448417444831
,I/CheckinService( 6254): active receiver: disabled
I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=6254, uid=10025, userID:0
,D/PMS     (  895): releaseWL(2f686a75): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms}
,D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6353): [NET] android_getaddrinfo_proxy-, success
,V/SetupWizard( 6395): Connected to Gservices successfully
,D/PMS     (  895): acquireWL(262b1193): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1753 10025 WorkSource{10025 com.google.android.gms},
D/GCM     ( 1753): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1753): [NET] android_getaddrinfofornet-, pass to proxy,
,D/libc    ( 1753): [NET] android_getaddrinfo_proxy+
D/libc    ( 1753): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1753): [NET] android_getaddrinfo_proxy-, success
,D/ChimeraCfgMgr( 6254): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
D/ChimeraCfgMgr( 6254): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector conne,ct_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1193): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1130): reapply : com.google.android.gms 1 40
W/Kids    ( 6254): [AccountUtils] Account not ready
W/Kids    ( 6254): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 6254): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 6254): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 6254): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 6254): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 6254): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 6254): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 6254): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 6254): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 6254): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 6254): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 6254): 	at java.lang.Thread.run(Thread.java:818)
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/PMS     (  895): acquireWL(2c202ee8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6222 10167 null
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6222, uid=10167, userID:0
,D/PMS     (  895): releaseWL(2c202ee8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6222): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6222): Stop autocaching.
,E/GmsUtils( 6222): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6222): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  895): acquireWL(acf778a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
D/GCM     ( 1753): Connected
,D/PMS     (  895): releaseWL(262b1193): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): releaseWL(acf778a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms},
D/PMS     (  895): acquireWL(f7e21fb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,D/GCM     ( 1753): Message class com.google.f.a.a.p,
,D/PMS     (  895): releaseWL(f7e21fb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
,I/PushClient( 6353): PnsModel {1ed99b6a}: update(): Update registration succeeded.,
,D/Process (  895): killProcessQuiet, pid=6032,
I/ActivityManager(  895): Killing 6032:com.htc.android.mail:sync/u0a65 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 6032
,D/Process (  895): killProcessQuiet, pid=6032,
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  895): failed to open /acct/uid_10065/pid_6032/cgroup.procs: No such file or directory
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): ,
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,D/Process (  895): killProcessQuiet, pid=5072,
I/ActivityManager(  895): Killing 5072:com.android.settings/1000 (adj 15): empty #17,
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 5072,
D/WifiService(  895): Client connection lost with reason: 4
,D/Process (  895): killProcessQuiet, pid=5072,
W/libprocessgroup(  895): failed to open /acct/uid_1000/pid_5072/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
V/BluetoothSapService( 5854): onUnbind
,D/Process (  895): killProcessQuiet, pid=6293,
,I/ActivityManager(  895): Killing 6293:com.fitbit.FitbitMobile/u0a23 (adj 15): empty #17
,D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,I/ActivityManager(  895): Recipient 6293,
,D/Process (  895): killProcessQuiet, pid=5607
I/ActivityManager(  895): Killing 5607:com.htc.bgp/u0a11 (adj 15): empty #17,
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,I/ActivityManager(  895): Recipient 5607,
,D/Process (  895): killProcessQuiet, pid=6293,
W/libprocessgroup(  895): failed to open /acct/uid_10023/pid_6293/cgroup.procs: No such file or directory,
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
W/libprocessgroup(  895): failed to open /acct/uid_10011/pid_5607/cgroup.procs: No such file or directory
D/Process (  895): killProcessQuiet, pid=5607
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): ,
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): ,
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): ,
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,W/ContextImpl(  895): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:817 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1598): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/[PluginManager]RegisterService( 1413): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
D/PhoneApp( 1445): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
I/[PluginManager]RegisterService( 1413): handle notify Blinkfeed plugin client changed
,D/AccTypeManager( 1598): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  895): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,W/PackageManager(  895): Unable to load service info ResolveInfo{3d88f160 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  895): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  895): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950),
W/PackageManager(  895): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  895): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  895): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  895): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  895): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  895): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  895): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
W/PackageManager(  895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
D/PhoneApp( 1445): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1598): Unsupported attribute readOnly
,W/ResourcesManager(  895): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneApp( 1445): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AccTypeManager( 1598): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1598): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=6254, uid=10025, userID:0
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=6254, uid=10025, userID:0
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=6254, uid=10025, userID:0
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=6254, uid=10025, userID:0
,D/HtcFingerPrintQuickLaunchProvider( 6768): -onCreate()
,E/ExternalAccountType( 1598): Unsupported attribute readOnly
,D/AccTypeManager( 1598): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
V/Settings:HtcSettingsApplication( 6768): [6768/6768] onCreate()
,W/PackageManager(  895): Unable to load service info ResolveInfo{232a5b6f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  895): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  895): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  895): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  895): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  895): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  895): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  895): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  895): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  895): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
W/PackageManager(  895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,D/AccTypeManager( 1598): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1598): Unsupported attribute readOnly,
,I/ActivityManager(  895): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6795 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/Process (  895): killProcessQuiet, pid=6186
I/ActivityManager(  895): Killing 6186:com.htc.sense.mms/u0a67 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 ,
,I/art     (  470): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 157us total 10.843ms
I/ActivityManager(  895): Recipient 6186
,I/art     (  470): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 149us total 9.970ms
,I/art     (  470): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 149us total 9.833ms
,E/Settings:HtcWrapHeaderInfo( 6768): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6768): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 6768): updateDevelopment, bPrefShow = true
,D/Process (  895): killProcessQuiet, pid=6186
W/libprocessgroup(  895): failed to open /acct/uid_10067/pid_6186/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/PackageManager(  895): Unable to load service info ResolveInfo{100d906a com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  895): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  895): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  895): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  895): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  895): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  895): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  895): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  895): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  895): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  895): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
W/PackageManager(  895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
E/Settings:HtcUmcWidgetEnabler( 6768): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]support         :false
,I/BackupManagerService(  895): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/Settings:HtcVoWifiWidgetEnabler( 6768): isSupportVoWifi: null
,I/ActivityManager(  895): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6768): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6768): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 6768): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 6768): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6768): [supportHomeButton]support         :false
,E/Settings:HtcVoWifiWidgetEnabler( 6768): isSupportVoWifi: null
,I/ActivityManager(  895): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6768): Failed to find provider info for com.htc.vowifi
,V/GmsNetworkLocationProvi( 1658): DISABLE,
,D/LocationProviderProxy(  895): applying state to connected service,
D/PMS     (  895): acquireWL(157eb72a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1658 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(157eb72a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,V/GmsNetworkLocationProvi( 1658): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,D/LocationProviderProxy(  895): applying state to connected service
,D/PMS     (  895): acquireWL(173ef91b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1658 10025 WorkSource{10025 com.google.android.gms}
,V/GmsNetworkLocationProvi( 1658): ENABLE
,V/GmsNetworkLocationProvi( 1658): SET-REQUEST
V/GmsNetworkLocationProvi( 1658): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
D/PMS     (  895): acquireWL(fca0bf7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1658 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(173ef91b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): releaseWL(fca0bf7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): acquireWL(b68a64): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1658 10025 WorkSource{1000 android}
,D/PMS     (  895): releaseWL(b68a64): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{1000 android}
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6795, uid=10075, userID:0
,D/Finsky  ( 6795): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6795): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  895): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6833 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 6795): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
W/Settings( 6795): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6795, uid=10075, userID:0,
,W/ResourcesManager( 6833): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6833): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6833): VM with version 2.1.0 has multidex support,
D/Finsky  ( 6795): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6795): [1] 2.run: Finished loading 1 libraries.
I/MultiDex( 6833): install
,I/MultiDex( 6833): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6795): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6795): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 6254): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm,
V/JNIHelp ( 6833): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  895): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6857 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/PeopleContactsSync( 6254): CP2 sync disabled
,D/PMS     (  895): acquireWL(17035494): PARTIAL_WAKE_LOCK  Icing 0x1 6254 10025 WorkSource{10025 com.google.android.gms},
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=6254, uid=10025, userID:0
,W/ActivityThread( 6833): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6833): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24e7de2b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6833): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 6254): Storage manager: low false usage 1.67MB avail 7.28GB capacity 9.08GB
,W/Icing   ( 6254): Received bad json for section weights override -- ignoring.
,W/Icing   ( 6254): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 6254): Received bad json for section weights override -- ignoring.
,I/UpdateIcingCorporaServi( 6857): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,W/Icing   ( 6254): Received bad json for corpus context scoring override -- ignoring.
,I/art     (  895): Explicit concurrent mark sweep GC freed 31528(1770KB) AllocSpace objects, 4(194KB) LOS objects, 33% free, 17MB/25MB, paused 1.084ms total 78.681ms
D/PMS     (  895): acquireWL(2aa7b518): PARTIAL_WAKE_LOCK  AsyncService 0x1 6613 10176 null
,D/PMS     (  895): releaseWL(2aa7b518): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  895): acquireWL(3ec5cd56): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6613 10176 null
,I/[PluginManager]RegisterService( 1413): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.pns,
I/[PluginManager]RegisterService( 1413): handle notify Blinkfeed plugin client changed
,D/PMS     (  895): releaseWL(3ec5cd56): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,D/LocationManagerService(  895): getProviders()=[passive, network]
,V/Finsky  ( 6795): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,D/Process (  895): killProcessQuiet, pid=6353
,I/ActivityManager(  895): Killing 6353:com.htc.cs.pns/u0a74 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  895): Recipient 6353,
,D/Process (  895): killProcessQuiet, pid=6353,
W/libprocessgroup(  895): failed to open /acct/uid_10074/pid_6353/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PackageBroadcastService( 6254): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.pns,
,I/Icing   ( 6254): updateResources: need to parse f{com.google.android.gms},
,I/ActivityManager(  895): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6903 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a,
,I/PeopleContactsSync( 6254): CP2 sync disabled,
I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=6254, uid=10025, userID:0
,D/PMS     (  895): acquireWL(66a24cf): PARTIAL_WAKE_LOCK  AsyncService 0x1 6613 10176 null
,D/PMS     (  895): acquireWL(3887b565): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6613 10176 null
D/PMS     (  895): releaseWL(66a24cf): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  895): acquireWL(1c2b323a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6151 10120 null,
,D/PMS     (  895): releaseWL(3887b565): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,D/PackageBroadcastService( 6254): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
I/[PluginManager]RegisterService( 1413): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1413): handle notify Blinkfeed plugin client changed
,I/PackageBroadcastService( 6254): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 6151): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6151): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  895): acquireWL(1821a063): PARTIAL_WAKE_LOCK  AsyncService 0x1 6613 10176 null,
,D/PMS     (  895): acquireWL(38c86d19): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6613 10176 null
,D/PMS     (  895): releaseWL(1821a063): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/AuthorizationBluetoothService( 1753): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/PMS     (  895): releaseWL(1c2b323a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/GCM     ( 1753): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GmsCoreStatsServiceLauncher( 6254): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     ( 1753): Explicit concurrent mark sweep GC freed 14736(855KB) AllocSpace objects, 11(501KB) LOS objects, 49% free, 4MB/8MB, paused 754us total 28.641ms,
,I/UpdateIcingCorporaServi( 6857): UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] ,
,I/UpdateIcingCorporaServi( 6857): Updating corpora: APPS=com.htc.cs.pns, CONTACTS=MAYBE
,D/WearableService( 6658): callingUid 10025, callindPid: 6658
D/PMS     (  895): releaseWL(38c86d19): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6254, uid=10025, userID:0
,D/LocationInitializer( 6254): Restart initialization of location
E/MDM     ( 1658): [156] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/JNIHelp ( 6151): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Icing   ( 6254): Internal init done: storage state 0
,I/Icing   ( 6254): Post-init done
,I/Icing   ( 6254): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 6857): UpdateCorporaTask done [took 47 ms] updated apps [took 47 ms] 
,I/UpdateIcingCorporaServi( 6857): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  895): releaseWL(17035494): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,W/System  ( 6151): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6151): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 6857): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 6151): UserRecoverableAuthException.
,E/Babel   ( 6151): eei: BadAuthentication
E/Babel   ( 6151): 	at eeg.a(Unknown Source)
E/Babel   ( 6151): 	at eeg.a(Unknown Source)
E/Babel   ( 6151): 	at eeg.a(Unknown Source)
E/Babel   ( 6151): 	at g.a(Unknown Source)
E/Babel   ( 6151): 	at cae.a(SourceFile:3089)
E/Babel   ( 6151): 	at cae.a(SourceFile:1131)
E/Babel   ( 6151): 	at cws.a(SourceFile:4333)
E/Babel   ( 6151): 	at cws.a(SourceFile:1419)
E/Babel   ( 6151): 	at crl.a(SourceFile:492)
E/Babel   ( 6151): 	at crl.a(SourceFile:1468)
E/Babel   ( 6151): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6151): 	at cas.b(SourceFile:106)
E/Babel   ( 6151): 	at cap.d(SourceFile:335)
E/Babel   ( 6151): 	at caq.run(SourceFile:81)
,E/Babel   ( 6151): Error getting auth token
E/Babel   ( 6151): dvm
E/Babel   ( 6151): 	at g.a(Unknown Source)
E/Babel   ( 6151): 	at cae.a(SourceFile:3089)
E/Babel   ( 6151): 	at cae.a(SourceFile:1131)
E/Babel   ( 6151): 	at cws.a(SourceFile:4333)
E/Babel   ( 6151): 	at cws.a(SourceFile:1419)
E/Babel   ( 6151): 	at crl.a(SourceFile:492)
E/Babel   ( 6151): 	at crl.a(SourceFile:1468)
E/Babel   ( 6151): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6151): 	at cas.b(SourceFile:106)
E/Babel   ( 6151): 	at cap.d(SourceFile:335)
E/Babel   ( 6151): 	at caq.run(SourceFile:81)
,E/Babel   ( 6151): Account registration failed 1-Redacted-21
,E/Babel   ( 6151): cyp: null -- null
E/Babel   ( 6151): 	at cae.a(SourceFile:3121)
E/Babel   ( 6151): 	at cae.a(SourceFile:1131)
E/Babel   ( 6151): 	at cws.a(SourceFile:4333)
E/Babel   ( 6151): 	at cws.a(SourceFile:1419)
E/Babel   ( 6151): 	at crl.a(SourceFile:492)
E/Babel   ( 6151): 	at crl.a(SourceFile:1468)
E/Babel   ( 6151): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6151): 	at cas.b(SourceFile:106)
E/Babel   ( 6151): 	at cap.d(SourceFile:335)
,E/Babel   ( 6151): 	at caq.run(SourceFile:81)
,I/art     ( 6151): Note: end time exceeds epoch: ,
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ResourcesManager( 1753): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/Babel   ( 6151): Unexpected exception while authenticating.,
E/Babel   ( 6151): eej: User intervention required. Notification has been pushed.
E/Babel   ( 6151): 	at eeg.b(Unknown Source)
E/Babel   ( 6151): 	at eeg.b(Unknown Source)
E/Babel   ( 6151): 	at g.a(Unknown Source)
E/Babel   ( 6151): 	at cae.b(SourceFile:1146)
E/Babel   ( 6151): 	at dcg.run(SourceFile:5617)
E/Babel   ( 6151): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6151): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6151): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1193): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1130): reapply : com.google.android.gms 1 40,
,I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
,I/Prism.ItemManager( 1493): loadItems() com.htc.launcher.pageview.WidgetManager@13cb09ac +,
D/PMS     (  895): acquireWL(3d6d2c0): PARTIAL_WAKE_LOCK  *alarm* 0x1 895 1000 WorkSource{10075},
I/Prism.WidgetManager( 1493): onLoadItems() +,
V/AlarmManager(  895): sending alarm PendingIntent{172e6bf9: PendingIntentRecord{30a07927 com.android.vending startService}}, i=null, t=0, cnt=1, w=1447848463311, Int=0
D/Finsky  ( 6795): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  895): releaseWL(3d6d2c0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
W/ResourcesManager( 1493): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6795): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1493): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6795): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,E/Prism.WidgetManager( 1493): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1493): onLoadItems() -
I/Prism.ItemManager( 1493): loadItems() com.htc.launcher.pageview.WidgetManager@13cb09ac -
,I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1493): AllAppsMgr addApps, already exist: ApplicationInfo(id=43, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1493): Deferring update until onResume
,D/Launcher( 1493): waitUntilResume // bindAppsUpdated
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6795): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6795): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 6795): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 6795): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/DeviceConnectionService( 1658): client connected with version: 7571000,
,D/PhoneApp( 1445): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1445): -- N1 =0
,D/PhoneApp( 1445): -- N2 =0
,D/PhoneApp( 1445): -- N3 =0
,I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
,I/Prism.ItemManager( 1493): loadItems() com.htc.launcher.pageview.WidgetManager@13cb09ac +,
I/Prism.WidgetManager( 1493): onLoadItems() +,
,E/Prism.WidgetManager( 1493): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1493): onLoadItems() -
I/Prism.ItemManager( 1493): loadItems() com.htc.launcher.pageview.WidgetManager@13cb09ac -
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/Prism.ItemManager( 1493): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
,I/Prism.ItemManager( 1493): loadItems() com.htc.launcher.pageview.WidgetManager@13cb09ac +,
,I/Prism.WidgetManager( 1493): onLoadItems() +,
,E/Prism.WidgetManager( 1493): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1493): onLoadItems() -
,I/Prism.ItemManager( 1493): loadItems() com.htc.launcher.pageview.WidgetManager@13cb09ac -
,D/Process (  895): killProcessQuiet, pid=6441,
I/ActivityManager(  895): Killing 6441:com.twitter.android/u0a181 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 6441,
,D/Process (  895): killProcessQuiet, pid=6441,
W/libprocessgroup(  895): failed to open /acct/uid_10181/pid_6441/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
D/Process (  895): killProcessQuiet, pid=6518
I/ActivityManager(  895): Killing 6518:com.google.android.apps.magazines/u0a169 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 6518,
,D/Process (  895): killProcessQuiet, pid=6518,
W/libprocessgroup(  895): failed to open /acct/uid_10169/pid_6518/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/Process (  895): killProcessQuiet, pid=6586,
I/ActivityManager(  895): Killing 6586:com.android.chrome/u0a102 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 6586,
,D/Process (  895): killProcessQuiet, pid=6586,
W/libprocessgroup(  895): failed to open /acct/uid_10102/pid_6586/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): ,
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=6254, uid=10025, userID:0,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=6254, uid=10025, userID:0,
,I/PackageManager(  895):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=6254, uid=10025, userID:0,
,I/CheckinService( 6254): Done disabling old GoogleServicesFramework version,
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): ,
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,D/TelephonyReceiver( 1445): switchBindHtcMsgCursor: null,
,D/PMS     (  895): acquireWL(2beb2013): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 895 1000 WorkSource{1000},
V/AlarmManager(  895): sending alarm PendingIntent{ef0be99: PendingIntentRecord{39e9f55e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=172382, Int=0
V/AlarmManager(  895): sending alarm PendingIntent{3a9dac49: PendingIntentRecord{916c94e com.android.vending startService}}, i=null, t=0, cnt=1, w=1447848478588, Int=0
D/PMS     (  895): acquireWL(105daa6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
V/AlarmManager(  895): sending alarm PendingIntent{2a9937c: PendingIntentRecord{1b0bc405 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=172795, Int=0
,D/PMS     (  895): releaseWL(2beb2013): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/PMS     (  895): acquireWL(3a9a2c5a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(105daa6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,D/WeatherUtility( 1130): Weather sync is On,
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  895): acquireWL(327ed614): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(3a9a2c5a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): releaseWL(327ed614): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): acquireWL(cb36ebd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): releaseWL(cb36ebd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): acquireWL(3751ecb2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,D/WeatherUtility( 1130): Weather sync is On,
,D/PMS     (  895): acquireWL(7ac3403): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms},
,D/PMS     (  895): acquireWL(2f6e21fe): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1413 10054 null,
,D/PMS     (  895): acquireWL(8b40d5f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): releaseWL(3751ecb2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,I/VacuumService( 1753): Vacuum at: now=1447848480693 tag=VacuumService
,D/PMS     (  895): releaseWL(7ac3403): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): acquireWL(29deb875): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): releaseWL(8b40d5f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,D/PMS     (  895): releaseWL(29deb875): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): acquireWL(f86600a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,D/ContactMessageStore( 1445): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1445): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  895): releaseWL(f86600a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): acquireWL(1f36207b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): releaseWL(1f36207b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,D/Finsky  ( 6795): [905] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 6795): [1] 5.onFinished: Installation state replication succeeded.
,D/AutoSetting( 1413): service - handleMessage() stop self
,D/AutoSetting( 1413): service - onDestroy() END,
D/AutoSetting( 1413): service - handleMessage() quit looper
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,D/PMS     (  895): acquireWL(22137e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  895): n_update end
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895): BroadcastReceiver::onReceive+,
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/WifiController(  895): battery changed pluggedType: 2
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/HtcPowerSaver(  895): updateBatteryInfo
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/PMS     (  895): runPSCheck
,D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
D/PMS     (  895): releaseWL(22137e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,E/WifiStateMachine(  895): handleMessage: E msg.what=131165,
,E/WifiStateMachine(  895): processMsg: ConnectedState,
,E/WifiStateMachine(  895):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
,E/WifiStateMachine(  895): processMsg: L2ConnectedState,
,E/WifiStateMachine(  895):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
,E/WifiStateMachine(  895): processMsg: ConnectModeState,
,E/WifiStateMachine(  895):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
,E/WifiStateMachine(  895): processMsg: DriverStartedState,
E/WifiStateMachine(  895):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  895): processMsg: SupplicantStartedState
E/WifiStateMachine(  895):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine(  895): processMsg: DefaultState
E/WifiStateMachine(  895):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
E/WifiStateMachine(  895): handleMessage: X
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): ,
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): ,
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,D/PMS     (  895): releaseWL(2f6e21fe): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): ,
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): ,
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,E/WifiStateMachine(  895): handleMessage: E msg.what=131326,
E/WifiStateMachine(  895): processMsg: ConnectedState
E/WifiStateMachine(  895):  ConnectedState what:131326 1 0,
E/WifiStateMachine(  895): processMsg: L2ConnectedState
E/WifiStateMachine(  895):  L2ConnectedState what:131326 1 0,
E/WifiStateMachine(  895): handleMessage: X
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
I/jxcore-log( 5794): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 5794): 
,D/HtcUPManager( 1130): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1413): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@35cf9ebf,
,I/ActivityManager(  895): Killing 5794:com.test.thalitest/u0a373 (adj 15): empty #17,
D/Process (  895): killProcessQuiet, pid=5794
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
I/ActivityManager(  895): Recipient 5794,
E/InputEventReceiver( 1269): Looper::removeFd(67) is failed, result(0), input channel 'ClientState{1b61e1bc uid 10373 pid 5794} (c)'
D/WifiService(  895): Client connection lost with reason: 4
D/HtcUPManager( 1130): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  895): killProcessQuiet, pid=5794
W/libprocessgroup(  895): failed to open /acct/uid_10373/pid_5794/cgroup.procs: No such file or directory,
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  895): acquireWL(346f66f1): PARTIAL_WAKE_LOCK  *alarm* 0x1 895 1000 WorkSource{1000},
V/AlarmManager(  895): sending alarm PendingIntent{15068ad: PendingIntentRecord{31ef77e2 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1447848522174, Int=0
D/PMS     (  895): acquireWL(143272d6): PARTIAL_WAKE_LOCK  *backup* 0x1 895 1000 null
V/AlarmManager(  895): sending alarm PendingIntent{1ffc4957: PendingIntentRecord{d0dec44 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=215020, Int=0
D/PMS     (  895): releaseWL(346f66f1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/BackupManagerService(  895): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  895): Requested init for com.google.android.gms.backup.BackupTransportService but not found,
D/PMS     (  895): releaseWL(143272d6): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  895): acquireWL(d82812d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  895): plugged=true pluggin=true,
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/WifiController(  895): battery changed pluggedType: 2
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): closing low battery warning: level=100
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): updateBatteryInfo
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  895): runPSCheck
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus,
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
D/PMS     (  895): releaseWL(d82812d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): << updateStatus,
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  895): acquireWL(19bae662): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895): BroadcastReceiver::onReceive-,
D/WifiController(  895): battery changed pluggedType: 2
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  895): updateBatteryInfo
,I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  895): runPSCheck
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
D/PMS     (  895): releaseWL(19bae662): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(389223f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895): BroadcastReceiver::onReceive+,
D/WifiController(  895): battery changed pluggedType: 2
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  895): updateBatteryInfo
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): runPSCheck
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
,I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
D/PMS     (  895): releaseWL(389223f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  895): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=7060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/art     (  895): Explicit concurrent mark sweep GC freed 32394(1572KB) AllocSpace objects, 1(81KB) LOS objects, 33% free, 17MB/25MB, paused 895us total 64.561ms
,W/ContextImpl( 7060): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 6768): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6768): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6768): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6768): Cust_ConnectToPC   : spcsc>false
D/        ( 6768): Cust_ConnectToPC   : IPT>true
D/        ( 6768): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 6768): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false,
D/SmartNS_NSReceiver( 6768): Index of the first 1 = 3
,W/ContextImpl( 6768): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6768): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 6768): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 6768): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 6768): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6768): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 6768): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 6768): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/Process (  895): killProcessQuiet, pid=6415
I/ActivityManager(  895): Killing 6415:com.htc.cs.dm/u0a105 (adj 15): empty #17
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  895): Recipient 6415
,D/Process (  895): killProcessQuiet, pid=6415
,D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  895): failed to open /acct/uid_10105/pid_6415/cgroup.procs: No such file or directory
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  895): acquireWL(17330329): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 895 1000 WorkSource{1000},
V/AlarmManager(  895): sending alarm PendingIntent{ef0be99: PendingIntentRecord{39e9f55e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=232382, Int=0
,I/ActivityManager(  895): Start proc com.htc.backup for service com.htc.backup/.AutoBackupNotificationScheduler: pid=7110 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WeatherUtility( 1130): Weather sync is On
V/AlarmManager(  895): sending alarm PendingIntent{66506ae: PendingIntentRecord{19a10c4f com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1447848641389, Int=0
D/PMS     (  895): releaseWL(17330329): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/htcbackup-core( 7110): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  895): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7150 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,D/WeatherUtility( 1130): Weather sync is On
,D/PMS     (  895): acquireWL(172b3d86): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1413 10054 null
,I/DeviceManagement( 7150): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=7150 dbg=false s=true
,I/DeviceManagement( 7150): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
,I/DeviceManagement( 7150): ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
,I/DeviceManagement( 7150): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/DeviceManagement( 7150): WorkflowService: Starting workflow service
,I/DeviceManagement( 7150): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1ed99b6a] args=[Bundle[mParcelledData.dataSize=132]]
,I/DeviceManagement( 7150): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
,I/DeviceManagement( 7150): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7150): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 7150): SessionStateController: Checking invariants...
,I/DeviceManagement( 7150): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 7150): SessionStateController: Checking invariants...
,I/DeviceManagement( 7150): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true,
,I/DeviceManagement( 7150): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1ed99b6a],
,I/DeviceManagement( 7150): WorkflowService: Stopping workflow service
,I/ActivityManager(  895): Killing 6639:com.htc.widget.hmsproc1/u0a37 (adj 15): empty #17,
D/Process (  895): killProcessQuiet, pid=6639,
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  895): Recipient 6639
,D/Process (  895): killProcessQuiet, pid=6639
,D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  895): failed to open /acct/uid_10037/pid_6639/cgroup.procs: No such file or directory
,D/Process (  895): killProcessQuiet, pid=6690,
I/ActivityManager(  895): Killing 6690:com.htc.csrecommend/u0a32 (adj 15): empty #17,
D/Process (  895): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,D/PMS     (  895): releaseWL(172b3d86): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/ActivityManager(  895): Recipient 6690,
,D/Process (  895): killProcessQuiet, pid=6690,
W/libprocessgroup(  895): failed to open /acct/uid_10032/pid_6690/cgroup.procs: No such file or directory
D/Process (  895): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  895): acquireWL(2af6775e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/WifiController(  895): battery changed pluggedType: 2
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): closing low battery warning: level=100,
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): updateBatteryInfo
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  895): runPSCheck
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
,D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
D/PMS     (  895): releaseWL(2af6775e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  895): acquireWL(1403a73f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/WifiController(  895): battery changed pluggedType: 2
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  895): updateBatteryInfo
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  895): runPSCheck
,D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
D/PMS     (  895): releaseWL(1403a73f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  895): acquireWL(3c3d980c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 895 1000 WorkSource{1000},
V/AlarmManager(  895): sending alarm PendingIntent{ef0be99: PendingIntentRecord{39e9f55e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=352381, Int=0
V/AlarmManager(  895): sending alarm PendingIntent{fd59555: PendingIntentRecord{262eab6a android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=442048, Int=0
,D/PMS     (  895): acquireWL(3815785b): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 895 1000 null
D/PMS     (  895): releaseWL(3c3d980c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1130): Weather sync is On,
,D/WeatherUtility( 1130): Weather sync is On,
,D/PMS     (  895): acquireWL(1ea731d1): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1413 10054 null
,D/PMS     (  895): acquireWL(17041436): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 895 1000 null
,D/PMS     (  895): releaseWL(3815785b): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  895): releaseWL(17041436): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/PMS     (  895): releaseWL(1ea731d1): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1193): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
I/RemoteViews( 1130): reapply : com.google.android.gms 1 40
W/GLSActivity( 1753): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1753): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1753): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1753): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1753): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1753): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1753): 	at android.os.Binder.execTransact(Binder.java:454)
,I/art     ( 1193): Background sticky concurrent mark sweep GC freed 36224(2MB) AllocSpace objects, 15(909KB) LOS objects, 72% free, 1167KB/4MB, paused 5.299ms total 42.277ms
,E/PlayEventLogger( 6795): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 6795): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6795): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6795): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6795): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6795): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6795): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6795): Ignoring header User-Agent because its value was null.
,D/libc    ( 6795): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6795): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6795): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6795): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6795): [NET] android_getaddrinfo_proxy+
D/libc    ( 6795): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6795): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  895): acquireWL(1ffdc028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/WifiController(  895): battery changed pluggedType: 2
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): updateBatteryInfo
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  895): runPSCheck
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0,
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
D/PMS     (  895): releaseWL(1ffdc028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  478): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/PMS     (  895): acquireWL(36873141): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null
D/UsbnetService(  895): onReceive BATTERY_CHANGED
,I/BatteryService(  895): n_update end
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): releaseWL(36873141): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  895): BroadcastReceiver::onReceive-,
D/NotificationService(  895): plugged=true pluggin=true
D/WifiController(  895): battery changed pluggedType: 2,
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1130): closing low battery warning: level=100,
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): updateBatteryInfo
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  895): runPSCheck
D/HtcPowerSaver(  895): Checking...
I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true
I/HtcPowerSaver(  895): >> updateStatus
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  895): << updateStatus
,E/PNP_UPDATERD(  365): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1445): MSG_CHECK_DELETION >>,
D/ContactMessageStore( 1445): mDeleteTask = null, bDeleting = false,
,D/AccFlag ( 1445): sku_id=99,
D/ContactMessageStore( 1445): MSG_CHECK_DELETION <<,
,D/ContactMessageStore( 1445): start background delete task...,
,D/ContactMessageStore( 1445): size: 0 , 0,
D/ContactMessageStore( 1445): Background delete complete,
,D/PMS     (  895): acquireWL(1d7f6e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  895): n_update end
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  895): plugged=true pluggin=true
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  895): battery changed pluggedType: 2,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  895): updateBatteryInfo
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): runPSCheck
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  895): Checking...
,I/HtcPowerSaver(  895): >> updateStatus
D/PMS     (  895): releaseWL(1d7f6e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(32126427): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): updateBatteryInfo
,D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  895): releaseWL(32126427): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1130): closing low battery warning: level=100
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): runPSCheck
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/WifiController(  895): battery changed pluggedType: 2
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(982b6d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/PMS     (  895): releaseWL(982b6d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/NotificationService(  895): plugged=true pluggin=true
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiController(  895): battery changed pluggedType: 2
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): updateBatteryInfo
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  895): runPSCheck
D/HtcPowerSaver(  895): Checking...
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  895): >> updateStatus
,D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/PowerUI ( 1130): closing low battery warning: level=100
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(1c54a07d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  895): releaseWL(1c54a07d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  895): updateBatteryInfo
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
,D/PowerUI ( 1130): closing low battery warning: level=100
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): onReceive BATTERY_CHANGED
,D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): runPSCheck
D/UsbnetService(  895): BroadcastReceiver::onReceive-
,D/WifiController(  895): battery changed pluggedType: 2
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(369c9b72): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
I/BatteryService(  895): n_update end
D/PMS     (  895): releaseWL(369c9b72): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  895): acquireWL(24371bc3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): updateBatteryInfo
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  895): releaseWL(24371bc3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/PowerUI ( 1130): closing low battery warning: level=100
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/UsbnetService(  895): onReceive BATTERY_CHANGED
,D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): runPSCheck
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/WifiController(  895): battery changed pluggedType: 2
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
,I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(31be6c40): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 895 1000 WorkSource{1000},
,V/AlarmManager(  895): sending alarm PendingIntent{ef0be99: PendingIntentRecord{39e9f55e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=472381, Int=0,
V/AlarmManager(  895): sending alarm PendingIntent{2c8fc779: PendingIntentRecord{894fcbe com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1447849311248, Int=0
,D/SmartSyncUtils( 7060): isEpsOn(), nState = 0,
,D/PMS     (  895): releaseWL(31be6c40): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1130): Weather sync is On,
,D/PMS     (  895): acquireWL(565b11f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7060 1000 null,
,D/PMS     (  895): releaseWL(565b11f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  895): acquireWL(253e0c6c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7060 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 7060): [updateNmRange] bManual = false,
D/SmartSyncScreenOnOffTimeReceiver( 7060): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 7060): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 7060): SettingOnTime = 1447912800000, randomSettingOnTime = 1447909296000
D/SmartSyncScreenOnOffTimeReceiver( 7060): SettingOffTime = 1447891200000, randomSettingOffTime = 1447893361000
,D/SmartSyncScreenOnOffTimeReceiver( 7060): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 7060): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 7060): bNightModeTurnOffOnce = false
,D/PMS     (  895): releaseWL(253e0c6c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/WeatherUtility( 1130): Weather sync is On
,D/PMS     (  895): acquireWL(222026ca): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1413 10054 null
,D/PMS     (  895): releaseWL(222026ca): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,D/PMS     (  895): acquireWL(1dbe403b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/WifiController(  895): battery changed pluggedType: 2
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/PowerUI ( 1130): closing low battery warning: level=100
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  895): updateBatteryInfo
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  895): runPSCheck
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus,
D/PMS     (  895): releaseWL(1dbe403b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(a358358): PARTIAL_WAKE_LOCK  *alarm* 0x1 895 1000 WorkSource{1000},
D/GCM     ( 1753): Message class com.google.f.a.a.i
V/AlarmManager(  895): sending alarm PendingIntent{6c1e6e1: PendingIntentRecord{27ee0c06 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=802300, Int=0
I/GCM     ( 6254): Message from null null
V/AlarmManager(  895): sending alarm PendingIntent{ef0be99: PendingIntentRecord{39e9f55e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1012382, Int=0
I/GoogleURLConnFactory( 1753): Using platform SSLCertificateSocketFactory
V/AlarmManager(  895): sending alarm PendingIntent{14ddecb1: PendingIntentRecord{281e596 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1047543, Int=0
,E/GCM     ( 6254): Dropping message from null
D/PMS     (  895): acquireWL(d46a517): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
D/PowerUsageList:PowerUsageHelper( 7060): MY_DEBUG = false
D/PMS     (  895): releaseWL(d46a517): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10025 com.google.android.gms}
D/WeatherUtility( 1130): Weather sync is On
V/AlarmManager(  895): sending alarm PendingIntent{342b7d04: PendingIntentRecord{136f45ad com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1447849258375, Int=0
D/PMS     (  895): acquireWL(2bb3a2ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): acquireWL(76ec522): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): acquireWL(4867bb3): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(76ec522): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
W/ContextImpl( 7060): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  895): releaseWL(a358358): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/PMS     (  895): acquireWL(2b480e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(2bb3a2ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  895): releaseWL(4867bb3): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10025 com.google.android.gms}
,W/Uploader( 1753): No account for auth token provided,
,D/PowerUsageService( 7060): repeat time = 1447850255340
,W/BatSI   (  895): Couldn't get kernel wake lock stats
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1753): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1753): [NET] android_getaddrinfo_proxy+
D/libc    ( 1753): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  458): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  458): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  458): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  458): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1753): [NET] android_getaddrinfo_proxy-, success
,W/BatSI   (  895): Couldn't get kernel wake lock stats
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1753): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1753): [NET] android_getaddrinfofornet-, err=8
,D/WeatherUtility( 1130): Weather sync is On
,D/PMS     (  895): acquireWL(2c77d67a): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1413 10054 null
,I/PowerUsageList:PowerUsageHelper( 7060): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 7060): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 7060): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 7060): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 7060): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 7060): calcPower(), no data
,W/Uploader( 1753):  no longer exists, so no auth token.
,W/Uploader( 1753): No account for auth token provided,
,W/Uploader( 1753): No account for auth token provided
,I/GLSUser ( 1753): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1753): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1753): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1753): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DotMatrix( 1193): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1193): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1130): reapply : com.google.android.gms 2 40
,E/Uploader( 1753): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1753): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1753): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1753): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1753): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1753): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1753): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1753): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1753): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1753): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1753): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1753): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1753): 	at com.google.android.gms.gcm.am.run(SourceFile:135),
,W/Uploader( 1753): No account for auth token provided,
,W/Uploader( 1753): No account for auth token provided,
,W/Uploader( 1753): No account for auth token provided,
,D/PMS     (  895): releaseWL(2b480e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,D/PMS     (  895): acquireWL(9150aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms},
,D/PMS     (  895): releaseWL(9150aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,D/PMS     (  895): acquireWL(1ef27659): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1753 10025 WorkSource{10025 com.google.android.gms},
D/PMS     (  895): releaseWL(1ef27659): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,D/PMS     (  895): releaseWL(2c77d67a): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,D/PMS     (  895): acquireWL(2f21b21e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  895): releaseWL(2f21b21e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  895): plugged=true pluggin=true
,D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/WifiController(  895): battery changed pluggedType: 2
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  895): updateBatteryInfo
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/PMS     (  895): runPSCheck
D/HtcPowerSaver(  895): Checking...,
I/HtcPowerSaver(  895): >> updateStatus
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(36d22aff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/WifiController(  895): battery changed pluggedType: 2
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  895): updateBatteryInfo
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  895): runPSCheck
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
,D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
D/PMS     (  895): releaseWL(36d22aff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  365): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  895): User[0] Flushing usage stats to disk,
,D/PMS     (  895): acquireWL(20d030cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/WifiController(  895): battery changed pluggedType: 2
D/UsbnetService(  895): onReceive BATTERY_CHANGED,
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  895): updateBatteryInfo
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/PMS     (  895): runPSCheck
D/HtcPowerSaver(  895): Checking...
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  895): >> updateStatus,
D/PMS     (  895): releaseWL(20d030cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(314b1f15): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
I/BatteryService(  895): n_update end
,D/PMS     (  895): releaseWL(314b1f15): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  895): acquireWL(3fb2d22a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  895): n_update end
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/PMS     (  895): releaseWL(3fb2d22a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): closing low battery warning: level=100
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  895): plugged=true pluggin=true
,D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/WifiController(  895): battery changed pluggedType: 2
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  895): updateBatteryInfo
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/PMS     (  895): runPSCheck
D/HtcPowerSaver(  895): Checking...
,I/HtcPowerSaver(  895): >> updateStatus
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(11a8781b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/PMS     (  895): releaseWL(11a8781b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  895): updateBatteryInfo
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/PMS     (  895): runPSCheck
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  895): Checking...
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  895): >> updateStatus
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  895): << updateStatus
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/NotificationService(  895): plugged=true pluggin=true
,D/WifiController(  895): battery changed pluggedType: 2
D/PowerUI ( 1130): closing low battery warning: level=100
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(19358db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): releaseWL(19358db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/NotificationService(  895): plugged=true pluggin=true
D/HtcPowerSaver(  895): updateBatteryInfo,
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  895): runPSCheck
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): Checking...
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  895): >> updateStatus
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  895): << updateStatus
D/WifiController(  895): battery changed pluggedType: 2
D/PowerUI ( 1130): closing low battery warning: level=100
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(214b9791): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): updateBatteryInfo
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  895): releaseWL(214b9791): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/PowerUI ( 1130): closing low battery warning: level=100
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/NotificationService(  895): plugged=true pluggin=true
,D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): runPSCheck
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/WifiController(  895): battery changed pluggedType: 2
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(83e6f6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NotificationService(  895): plugged=true pluggin=true
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/WifiController(  895): battery changed pluggedType: 2
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/PowerUI ( 1130): closing low battery warning: level=100
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  895): updateBatteryInfo
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  895): runPSCheck
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  895): << updateStatus
D/PMS     (  895): releaseWL(83e6f6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(cc7af7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/UsbnetService(  895): onReceive BATTERY_CHANGED
I/BatteryService(  895): n_update end,
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): releaseWL(cc7af7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  895): updateBatteryInfo
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/PMS     (  895): runPSCheck
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  895): Checking...
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  895): >> updateStatus
,D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  895): << updateStatus
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/NotificationService(  895): plugged=true pluggin=true
D/WifiController(  895): battery changed pluggedType: 2
D/PowerUI ( 1130): closing low battery warning: level=100
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  895): acquireWL(3691cd64): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
D/UsbnetService(  895): BroadcastReceiver::onReceive+
I/BatteryService(  895): n_update end
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/PMS     (  895): releaseWL(3691cd64): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  895): updateBatteryInfo
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/PMS     (  895): runPSCheck
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  895): Checking...
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  895): >> updateStatus
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  895): << updateStatus
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
,D/NotificationService(  895): plugged=true pluggin=true
D/WifiController(  895): battery changed pluggedType: 2
D/PowerUI ( 1130): closing low battery warning: level=100
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,W/BatSI   (  895): Couldn't get kernel wake lock stats,
,E/PNP_UPDATERD(  365): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  895): acquireWL(2c7f7c82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 895 1000 null,
I/IntentController( 1130): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  895): n_update end
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1130): closing low battery warning: level=100
D/HeadsetStateMachine( 5854): Disconnected process message: 10, size: 0
D/DotMatrix( 1193): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  895): plugged=true pluggin=true
D/DotMatrix( 1193): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1130): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  895): BroadcastReceiver::onReceive+
D/WifiController(  895): battery changed pluggedType: 2
D/UsbnetService(  895): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  895): updateBatteryInfo,
D/UsbnetService(  895):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  895): runPSCheck
D/UsbnetService(  895): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  895): Checking...
I/HtcPowerSaver(  895): >> updateStatus
D/PMS     (  895): releaseWL(2c7f7c82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  895): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  895): << updateStatus
,I/BatteryController( 1130): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1800000ms)
```
