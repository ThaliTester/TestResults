#### Test 522773652a05488_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  978): acquireWL(27b0de9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 978 1000 null
I/BatteryService(  978): n_update end
D/PMS     (  978): releaseWL(27b0de9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
--------- beginning of main
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1236): closing low battery warning: level=100
D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  978): updateBatteryInfo
D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  978): plugged=true pluggin=true
D/DotMatrix( 1360): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  978): runPSCheck
D/UsbnetService(  978): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  978): Checking...
D/UsbnetService(  978): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  978): >> updateStatus
D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
D/UsbnetService(  978):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  978): BroadcastReceiver::onReceive-
D/WifiController(  978): handleMessage: E msg.what=155652
D/WifiController(  978): battery changed pluggedType: 2
D/WifiController(  978): processMsg: DeviceActiveState
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  978): processMsg: StaEnabledState
D/WifiController(  978): processMsg: DefaultState
D/WifiController(  978): handleMessage: X
I/HtcPowerSaver(  978): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  978): << updateStatus
I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 6697): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6697): ====startRecUseTime====
D/htc.customization.log.level( 6697):  is 
W/CustomizationLogLevel( 6697): Level value is invalid, use default level 2
D/CustomizationManager( 6697):  Read ACC file spent 0.045 (s)
D/CIDMapFileReader( 6697): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6697): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6697): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6697): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6697): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6697): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6697): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6697): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6697): Parsing tag category name = system
I/CustomizationCIDLoader( 6697): Parsing tag category name = application
I/CustomizationCIDLoader( 6697): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6697): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6697): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6697): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6697): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6697): add string-array item, value = 42507
I/CustomizationCIDLoader( 6697): add string-array item, value = 21902
I/CustomizationCIDLoader( 6697): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6697): add string-array item, value = 23420
I/CustomizationCIDLoader( 6697): add string-array item, value = 22299
I/CustomizationCIDLoader( 6697): add string-array item, value = 24002
I/CustomizationCIDLoader( 6697): add string-array item, value = 23210
I/CustomizationCIDLoader( 6697): add string-array item, value = 23205
I/CustomizationCIDLoader( 6697): add string-array item, value = 23806
I/CustomizationCIDLoader( 6697): add string-array item, value = 23430
I/CustomizationCIDLoader( 6697): add string-array item, value = 23408
I/CustomizationCIDLoader( 6697): add string-array item, value = 27205
I/CustomizationCIDLoader( 6697): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6697): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6697):  Read CID file spent 0.097 (s)
D/CustomizationManager( 6697):  All configurations done spent 0.097 (s)
I/ActivityManager(  978): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6697 on display 0
D/PMS     (  978): acquireHCC(37d81a6e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 978 1000 null
D/PMS     (  978): acquireHCC(3e24f50f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 978 1000 null
I/ActivityManager(  978): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6715 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  978): Display changed displayId=0
D/DotMatrix( 1360): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1360): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1601): [trimMemory] 20
I/WebViewFactory( 6715): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6715): Time to load native libraries: 9 ms (timestamps 9763-9772),
,I/LibraryLoader( 6715): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6715): Binding Chromium to main looper Looper (main, tid 1) {565ba0c},
I/LibraryLoader( 6715): Expected native library version number "",actual native library version number ""
,I/chromium( 6715): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6715): Initializing chromium process, singleProcess=true,
,W/art     ( 6715): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6715): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6715): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
E/libEGL  ( 6715): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6715): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6715): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6715): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6715): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6715): Local Branch: 
I/Adreno-EGL( 6715): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6715): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6715):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  978): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  978): java.lang.Throwable: stack dump
,W/System.err(  978): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  978): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  978): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  978): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  978): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@333d0034:true
,D/BluetoothAdapter( 6715): 767191800: getState(). Returning 12
,W/art     ( 6715): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6715): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6715): CordovaWebView is running on device made by: HTC
,W/art     ( 6715): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6715): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  978): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6715): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  978): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  978): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  978): hiding MENU key
,D/StatusBarManagerService(  978): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  978): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  978): hiding MENU key
,D/FindExtension( 6715): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6715): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@a5788e6, mServedView=org.apache.cordova.engine.SystemWebView{1adf8e27 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@27a998d4
I/InputMethodManagerService(  978): Disable input method client, pid=1601
D/StatusBarManagerService(  978): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1236): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6715): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  978): Displayed com.test.thalitest/.MainActivity: +636ms (total +680ms)
,W/BindingManager( 6715): Cannot call determinedVisibility() - never saw a connection for the pid: 6715
,D/JsMessageQueue( 6715): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6715): JniHelper::setJavaVM(0xab6148f8), pthread_self() = -1399485504
D/JX-Cordova( 6715): jxcore cordova android initializing
,W/jxcore-log( 6715): Initializing JXcore engine
W/jxcore-log( 6715): JXcore engine is ready
,W/jxcore-log( 6715): Starting JXcore engine,
,W/jxcore-log( 6715): Platform android
W/jxcore-log( 6715): 
W/jxcore-log( 6715): Process ARCH arm
W/jxcore-log( 6715): 
,D/PMS     (  978): releaseHCC(37d81a6e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  978): releaseHCC(3e24f50f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6715): JXcore Cordova bridge is ready!
I/jxcore-log( 6715): 
,W/jxcore-log( 6715): JXcore engine is started
I/Choreographer( 6715): Skipped 96 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6715): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6715): Toggling radios to true
I/jxcore-log( 6715): 
,D/BluetoothAdapter( 6715): enable(): BT is already enabled..!
,D/WifiManager( 6715): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  978): New client listening to asynchronous messages
E/WifiTrafficPoller(  978): ADD_CLIENT: 8
,W/Settings:Agent(  978): MONITOR_LOG
D/WifiService(  978): setWifiEnabled: true pid=6715, uid=10366
W/Settings:Agent(  978): name: wifi_on
E/WifiService(  978): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  978): value: 2
,I/WifiService(  978): isSprintWifiRestricted(): false
W/Settings:Agent(  978): >> traceCallingStack()
,I/WifiService(  978): isMdmWifiRestricted(): false
W/Settings:Agent(  978): Process.myPid(): 978
,W/Settings:Agent(  978): Process.myTid(): 2155
W/Settings:Agent(  978): Process.myUid(): 1000
W/Settings:Agent(  978): ,
W/Settings:Agent(  978): 
W/System.err(  978): java.lang.Throwable: stack dump
,W/System.err(  978): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  978): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  978): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  978): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  978): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  978): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  978): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  978): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  978): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  978): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  978): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  978): 
W/Settings:Agent(  978): << traceCallingStack(): 11(ms)
D/WifiController(  978): handleMessage: E msg.what=155656
D/WifiController(  978): processMsg: DeviceActiveState
D/WifiController(  978): processMsg: StaEnabledState
D/WifiController(  978): handleMessage: X
D/WifiManager( 6715): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  978): handleMessage: E msg.what=131145
D/WifiManager( 6715): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  978): processMsg: ConnectedState
E/WifiStateMachine(  978):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  978): processMsg: L2ConnectedState
E/WifiStateMachine(  978):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/jxcore-log( 6715): Radios toggled
I/jxcore-log( 6715): 
D/wpa_supplicant( 1349): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1349): wlan0: Cancelling scan request
D/wpa_supplicant( 1349): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1349): TDLS: Tear down peers
D/wpa_supplicant( 1349): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 1349): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1349): wlan0: Deauthentication notification
D/wpa_supplicant( 1349): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1349): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1349): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1349): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1349): enter disconnect check
I/wpa_supplicant( 1349): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1,
D/wpa_supplicant( 1349): wlan0: Auto connect disabled: do not try to re-connect
D/UsbDeviceManager(  978): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1349): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/PMS     (  978): acquireWL(19c195fc): PARTIAL_WAKE_LOCK  NetworkStats 0x1 978 1000 null
D/Tethering(  978): interfaceLinkStateChanged wlan0, false
D/Tethering(  978): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  978): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  978): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  978): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  978): TetherInterfaceSM: wlan0: enter UnavailableState
D/WifiMonitor(  978): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  978): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiStateMachine(  978): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  978): interfaceLinkStateChanged wlan0, false
,D/Tethering(  978): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  978): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  978): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  978): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  978): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  978): BroadcastReceiver::onReceive+
D/UsbnetService(  978): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  978): BroadcastReceiver::onReceive-
,D/TetherSettings( 5944): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 5944): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5944): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5944): Cust_ConnectToPC   : spcsc>false
D/        ( 5944): Cust_ConnectToPC   : IPT>true
D/        ( 5944): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5944): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5944): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5944): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5944): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/wpa_supplicant( 1349): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1349): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1349): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1349): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1349): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55b5422f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1349):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1349): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1349): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1349): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1349): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1349): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1349): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1349): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1349): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1349): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1349): EAPOL: External notification - EAP success=0
D/WifiMonitor(  978): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1349): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1349): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1349): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1349): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1349): EAPOL: External notification - portValid=0
D/WifiDisplayAdapter(  978): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  978):     Client/Owner: Client
D/WifiDisplayAdapter(  978):     GroupId: 
D/WifiDisplayAdapter(  978):     Passphrase: 
D/WifiDisplayAdapter(  978):     SessionId: 0
D/WifiDisplayAdapter(  978):     IP Address: }
D/HTCRequest(  978): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  978): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  978): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1349): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/HTCRequest(  978): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1349): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1349): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/WifiMonitor(  978): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/wpa_supplicant( 1349): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1349): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  978): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  978): handleMessage: new destination call exit/enter
E/WifiStateMachine(  978): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  978): invokeExitMethods: ConnectedState
E/WifiStateMachine(  978): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  978): release()
E/WifiStateMachine(  978): PerfLock released for exiting ConnectedState,
E/WifiStateMachine(  978): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  978): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  978): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  978): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  978): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  978): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
,D/wpa_supplicant( 1349): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1349): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1349): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1349): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  978): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1349): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1349): Power_Mode_Type mode = 0
I/wpa_supplicant( 1349): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
W/ContextImpl( 5944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1349): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  978): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1349): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  978): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  978): setDhcpActive: false
I/SmartNS_Utility( 5944): setISNotification
D/PMS     (  978): releaseWL(19c195fc): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NativeCrypto( 1937): Read error: ssl=0x55a6cc2910: I/O error during system call, Connection timed out
V/NetworkPolicy(  978): updateNetworkEnabledLocked()
V/NetworkPolicy(  978): updateNotificationsLocked()
D/PMS     (  978): acquireWL(3007d485): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1937 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  978): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  978): [NET] android_getaddrinfofornet-, SUCCESS
D/SmartNS_Utility( 5944): usb_cable_connect = 1
D/SmartNS_Utility( 5944): usb_denied = 0
,E/WifiStateMachine(  978): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  978): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  978): setDetailed state send new extra info<unknown ssid>
V/NetworkPolicy(  978): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  978): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED connected
V/NativeCrypto( 1937): SSL shutdown failed: ssl=0x55a6cc2910: I/O error during system call, Broken pipe
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  978): NetworkAgent != null
D/ConnectivityService(  978): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
,E/WifiStateMachine(  978): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  978): ENABLE_TRAFFIC_STATS_POLL false Token 13
I/SmartNS_PSService( 5944): usb notificaiton:true
E/WifiStateMachine(  978): WiFiDisplay: getWifidisplayApEnabled=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  978): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  978): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  978): Forcing reevaluation
D/libc    (  978): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  978): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  978): [NET] android_getaddrinfofornet-, SUCCESS
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  978): Validated
D/libc    (  978): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  978): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  978): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  978): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  978): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
I/ActionCombine( 5944): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/PMS     (  978): releaseWL(3007d485): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1349): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1349): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1349): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1349): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/ConnectivityService(  978): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  978): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  978): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  978): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  978):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  978): Start Disconnecting Watchdog 1
E/WifiStateMachine(  978): handleMessage: X
E/WifiStateMachine(  978): handleMessage: E msg.what=131146
E/WifiStateMachine(  978): processMsg: DisconnectingState
E/WifiStateMachine(  978):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  978): processMsg: ConnectModeState
E/WifiStateMachine(  978):  ConnectModeState ,CMD_RECONNECT 0 0
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1349): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1349): Fast associate: Old scan results
D/wpa_supplicant( 1349): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1349): wpa_supplicant_scan enter
D/wpa_supplicant( 1349): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1349): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1349): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1349): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1349): WPS:  * Request Type
D/wpa_supplicant( 1349): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1349): WPS:  * UUID-E
D/wpa_supplicant( 1349): WPS:  * Primary Device Type
D/wpa_supplicant( 1349): WPS:  * RF Bands (3)
D/wpa_supplicant( 1349): WPS:  * Association State
D/wpa_supplicant( 1349): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1349): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1349): WPS:  * Manufacturer
D/wpa_supplicant( 1349): WPS:  * Model Name
D/wpa_supplicant( 1349): WPS:  * Model Number
D/WifiMonitor(  978): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1349): WPS:  * Device Name
D/wpa_supplicant( 1349): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1349): P2P: * P2P IE header
D/wpa_supplicant( 1349): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1349): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1349): wlan0: Add radio work 'scan'@0x55b5405860
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1349): wlan0: First radio work item in the queue - schedule start immediately
D/HTCRequest(  978): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  978): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1349): wlan0: Starting radio work 'scan'@0x55b5405860 after 0.000056 second wait
D/wpa_supplicant( 1349): wlan0: nl80211: scan request
D/HTCRequest(  978): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  978): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/wpa_supplicant( 1349): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1349): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1349): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1349): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1349): wlan0: Own scan request started a scan in 0.000111 seconds
I/wpa_supplicant( 1349): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  978): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  978): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  978): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  978): handleMessage: X
E/WifiStateMachine(  978): handleMessage: E msg.what=147460
E/WifiStateMachine(  978): processMsg: DisconnectingState
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/SmartNS_Utility( 5944): usb_cable_connect = 1
E/WifiStateMachine(  978):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=142226
E/WifiStateMachine(  978): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  978):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=142226
E/WifiStateMachine(  978): ConnectModeState: Network connection lost 
D/SmartNS_Utility( 5944): usb_denied = 0
E/WifiStateMachine(  978): transitionTo: destState=DisconnectedState
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  978): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  978): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  978): invokeExitMethods: DisconnectingState
I/SmartNS_PSService( 5944): usb notificaiton:true
E/WifiStateMachine(  978): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  978): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  978): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  978): DisconnectedState call setCountryCode()
E/WifiStateMachine(  978):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1349): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1349): wlan0: Cancelling scan request
E/WifiStateMachine(  978): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  978): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  978): stopDataStallAlarm 
E/WifiTrafficPoller(  978): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  978): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiTrafficPoller(  978): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/SmartNS_NSReceiver( 5944): Tethered state change:false isNSOpening:false
D/wpa_supplicant( 1349): wlan0: nl80211: sched_scan request
D/DotMatrix( 1360): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/DotMatrix( 1360): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1236): reapply : com.android.settings 0 36
I/RemoteViews( 1236): reapply : com.android.settings 1 36
,D/wpa_supplicant( 1349): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1349): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiP2pService(  978): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1349): wlan0: nl80211: Sched scan started
D/WifiP2pService(  978): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1349): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/WifiP2pService(  978): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1349): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1349): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1349): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1349): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1349): wlan0: Scan completed in 0.041401 seconds
D/wpa_supplicant( 1349): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1349): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1349): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1349): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1349): wlan0: Radio work 'scan'@0x55b5405860 done in 0.042109 seconds
D/wpa_supplicant( 1349): wlan0: No suitable network found
D/wpa_supplicant( 1349): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1349): wlan0: Cancelling sched scan
D/wpa_supplicant( 1349): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1349): wlan0: Cancelling scan request
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1349): p2p0: Updating scan results from sibling
E/WifiStateMachine(  978): handleMessage: X
D/wpa_supplicant( 1349): nl80211: Received scan results (0 BSSes)
E/WifiMonitor(  978): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1349): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1349): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1349): p2p0: New scan results available (own=0 ext=0)
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  978): handleMessage: E msg.what=131101
D/wpa_supplicant( 1349): p2p0: No suitable network found
E/WifiStateMachine(  978): processMsg: DisconnectedState
D/WifiMonitor(  978): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1349): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1349): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1349): wlan0: Event SCHED_SCAN_STOPPED (38) received
W/WifiMonitor(  978): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor(  978): WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  978): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  978):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  978): processMsg: ConnectModeState
I/QuickSettingWifi( 1236): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
E/WifiStateMachine(  978):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  978): processMsg: DriverStartedState
E/WifiStateMachine(  978):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  978): processMsg: SupplicantStartedState
E/WifiStateMachine(  978):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  978): processMsg: DefaultState
E/WifiStateMachine(  978):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  978): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  978): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  978): handleMessage: X
E/WifiStateMachine(  978): handleMessage: E msg.what=147462
E/WifiStateMachine(  978): processMsg: DisconnectedState
E/WifiStateMachine(  978):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=142267  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  978): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  978): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  978): processMsg: ConnectModeState
E/WifiStateMachine(  978):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=142268  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  978): handleMessage: X
D/WifiNetworkAgent(  978): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  978): handleMessage: E msg.what=131212
E/WifiStateMachine(  978): processMsg: DisconnectedState
E/WifiStateMachine(  978):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: ConnectModeState
E/WifiStateMachine(  978):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: DriverStartedState
E/WifiStateMachine(  978):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: SupplicantStartedState
E/WifiStateMachine(  978):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: DefaultState
E/WifiStateMachine(  978):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  978): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  978): handleMessage: X
E/WifiStateMachine(  978): handleMessage: E msg.what=131212
E/WifiStateMachine(  978): processMsg: DisconnectedState
E/WifiStateMachine(  978):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: ConnectModeState
E/WifiStateMachine(  978):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: DriverStartedState
E/WifiStateMachine(  978):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: SupplicantStartedState
E/WifiStateMachine(  978):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: DefaultState
E/WifiStateMachine(  978):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  978): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  978): handleMessage: X
E/WifiStateMachine(  978): handleMessage: E msg.what=131212
E/WifiStateMachine(  978): processMsg: DisconnectedState
E/WifiStateMachine(  978):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: ConnectModeState
E/WifiStateMachine(  978):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: DriverStartedState
E/WifiStateMachine(  978):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: SupplicantStartedState
E/WifiStateMachine(  978):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): processMsg: DefaultState
E/WifiStateMachine(  978):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  978): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  978): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  978): handleMessage: X
E/WifiStateMachine(  978): handleMessage: E msg.what=147462
E/WifiStateMachine(  978): processMsg: DisconnectedState
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  978):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=142276  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  978): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  978): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  978): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  978): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  978): NetworkAgent == null
E/WifiTrafficPoller(  978): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  978): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:0
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  978): processMsg: ConnectModeState
E/WifiStateMachine(  978):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=142283  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  978): handleMessage: X
E/WifiStateMachine(  978): handleMessage: E msg.what=147461
E/WifiStateMachine(  978): processMsg: DisconnectedState
E/WifiStateMachine(  978):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:97 bcn=0
E/WifiStateMachine(  978): processMsg: ConnectModeState
E/WifiTrafficPoller(  978): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  978):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:97 bcn=0
E/WifiStateMachine(  978): processMsg: DriverStartedState
E/WifiStateMachine(  978):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:97 bcn=0
E/WifiStateMachine(  978): processMsg: SupplicantStartedState
E/WifiStateMachine(  978):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:97 bcn=0
D/WifiStateMachine(  978): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1349): wlan0: Control interface command 'LIST_DONGLES'
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/ContextImpl(  978): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  978): [1,448,986,943,688 ms] noteScanEnd no scan source
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1349): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  978): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2ec238d sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  978): NG7005g c0:ff:d4:d3:aa:4a rssi=-45 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  978): NG700 c0:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  978): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  978): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  978):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-56 freq=2462
E/WifiAutoJoinController (  978): Gonzos 38:f8:89:11:e9:11 rss,i=-84 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  978): 01ABC c2:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][ESS] is not scored
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiAutoJoinController (  978): ageScanResultsOut delay 40000 size 4 now 1448986943690
E/WifiAutoJoinController (  978): newSupplicantResults size=4 known=1 true
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1349): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  978): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  978): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  978): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  978): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  978): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  978): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-56,-127) num=(1,0)
E/WifiAutoJoinController (  978): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  978): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  978): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  978): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  978): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-56 freq=2462
D/HtcWifiControlRoamOffload: (  978): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  978): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  978): Done attemptAutoJoin status=3
E/WifiConfigStore(  978):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  978): handleMessage: X
D/WISPrService( 5944): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  978): handleMessage: E msg.what=131215
E/WifiStateMachine(  978): processMsg: DisconnectedState
E/WifiStateMachine(  978):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-56 ;0 ,-127] any roam=0 rt=142292
E/WifiStateMachine(  978): processMsg: ConnectModeState
E/WifiStateMachine(  978):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-56 ;0 ,-127] any roam=0 rt=142292
E/WifiStateMachine(  978): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  978): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  978): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
D/WifiService(  978): New client listening to asynchronous messages
E/WifiTrafficPoller(  978): ADD_CLIENT: 9
D/ConnectivityService(  978): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  978): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  978): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  978): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1236): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  978): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  978): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  978): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  978): Disconnected - quitting
D/usbnet  (  978): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  978):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  978): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/SecurityController( 1236): onLost 100
D/NetworkManagementService(  978): Removing idletimer
D/PMS     (  978): acquireWL(314430b): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 978 1000 null
D/CSLegacyTypeTracker(  978): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  978): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  978): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  978): ensureActiveMobilePolicyLocked()
D/PMS     (  978): acquireWL(219015e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 978 1000 null
E/ConnectivityService(  978): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  978): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  978): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  978): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/DATA_ICON( 1236): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/NetworkPolicy(  978): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  978): updateNetworkEnabledLocked()
V/NetworkPolicy(  978): updateIfacesLocked()
V/NetworkPolicy(  978): updateNotificationsLocked()
E/WifiConfigStore(  978): Setting BSSID for "NG700"WPA_PSK to any
D/NetworkManagementService(  978): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/DATA_ICON( 1236): dataConnected: false/false
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/PMS     (  978): releaseWL(219015e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
V/NetworkPolicy(  978): updateNetworkEnabledLocked()
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  978): updateNotificationsLocked()
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1349): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  978): will read network variables netId=0
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1349): Do not allow key_data field to be exposed
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  978): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  978):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  978): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/wpa_supplicant( 1349): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1349): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1349): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1349): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  978): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1349): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1349): ENABLE_NETWORK (0)
D/wpa_supplicant( 1349): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1349): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1349): wpa_supplicant_scan enter
,D/wpa_supplicant( 1349): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1349): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1349): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1349): WPS:  * Request Type
D/wpa_supplicant( 1349): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1349): WPS:  * UUID-E
D/wpa_supplicant( 1349): WPS:  * Primary Device Type
D/wpa_supplicant( 1349): WPS:  * RF Bands (3)
D/wpa_supplicant( 1349): WPS:  * Association State
D/wpa_supplicant( 1349): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1349): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1349): WPS:  * Manufacturer
D/wpa_supplicant( 1349): WPS:  * Model Name
D/WifiDisplayAdapter(  978): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  978):     Client/Owner: Client
D/WifiDisplayAdapter(  978):     GroupId: 
D/WifiDisplayAdapter(  978):     Passphrase: 
D/WifiDisplayAdapter(  978):     SessionId: 0
D/WifiDisplayAdapter(  978):     IP Address: }
D/wpa_supplicant( 1349): WPS:  * Model Number
D/wpa_supplicant( 1349): WPS:  * Device Name
D/wpa_supplicant( 1349): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1349): P2P: * P2P IE header
D/wpa_supplicant( 1349): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1349): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1349): wlan0: Add radio work 'scan'@0x55b5405860
D/wpa_supplicant( 1349): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1349): wlan0: Starting radio work 'scan'@0x55b5405860 after 0.000026 second wait
D/wpa_supplicant( 1349): wlan0: nl80211: scan request
D/wpa_supplicant( 1349): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1349): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1349): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1349): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1349): wlan0: Own scan request started a scan in 0.000057 seconds
I/wpa_supplicant( 1349): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  978): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  978): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  978): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  978): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1349): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1349): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1349): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  978): will read network variables netId=0
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/FlexNetS( 6555): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1349): Do not allow key_data field to be exposed
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:0
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1349): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1349): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  978): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  978):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1349): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1349): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1349): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1349): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1349): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1349): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1349): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1349): wpa_supplicant_scan enter
D/wpa_supplicant( 1349): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1349): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1349): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  978): setLastSelectedConfiguration -1
E/WifiStateMachine(  978): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  978): handleMessage: new destination call exit/enter
E/WifiStateMachine(  978): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  978): invokeExitMethods: DisconnectedState
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1349): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  978): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  978): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  978): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  978): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  978): DisconnectedState call setCountryCode()
E/WifiStateMachine(  978):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1349): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1349): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1349): wlan0: Cancelling scan request
D/wpa_supplicant( 1349): wlan0: nl80211: sched_scan request
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6555): updateSvcAllowedInSettings:false
I/ActivityManager(  978): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6775 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/FlexNetS( 6555): updateSvcAllowedInSettings:false
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/wpa_supplicant( 1349): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1349): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1349): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1349): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1349): wlan0: nl80211: New scan results available
D/WifiP2pService(  978): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1349): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/WifiP2pService(  978): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1349): wlan0: Event SCAN_RESULTS (3) received
D/WifiP2pService(  978): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1349): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1349): wlan0: Scan completed in 0.038841 seconds
D/wpa_supplicant( 1349): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1349): wlan0: BSS: Start scan result update 8
W/ContextImpl(  978): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1349): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
E/WifiStateMachine(  978): handleMessage: X
E/WifiStateMachine(  978): handleMessage: E msg.what=131131
E/WifiStateMachine(  978): processMsg: DisconnectedState
D/wpa_supplicant( 1349): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/wpa_supplicant( 1349): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to no match in scan
D/wpa_supplicant( 1349): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to no match in scan
D/wpa_supplicant( 1349): BSS: last_scan_res_used=0/32,
D/wpa_supplicant( 1349): wlan0: New scan results available (own=1 ext=0),
D/wpa_supplicant( 1349): wlan0: Radio work 'scan'@0x55b5405860 done in 0.039733 seconds
D/wpa_supplicant( 1349): wlan0: No suitable network found
E/WifiStateMachine(  978):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/wpa_supplicant( 1349): wlan0: Setting scan request: 15.000000 sec
E/WifiStateMachine(  978): processMsg: ConnectModeState
D/wpa_supplicant( 1349): wlan0: Cancelling sched scan
D/wpa_supplicant( 1349): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1349): wlan0: Cancelling scan request
D/wpa_supplicant( 1349): p2p0: Updating scan results from sibling
E/WifiStateMachine(  978):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/wpa_supplicant( 1349): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1349): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1349): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1349): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1349): p2p0: No suitable network found
D/wpa_supplicant( 1349): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1349): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1349): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WifiMonitor(  978): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  978): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  978): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  978): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
E/WifiMonitor(  978): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  978): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  978): WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  978): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  978): handleMessage: X
D/WIFI    (  978): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  978):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  978): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  978): enter WifiNetworkFactory startNetwork. mIPTStart:false
E/WifiStateMachine(  978): handleMessage: E msg.what=147461
E/WifiStateMachine(  978): processMsg: DisconnectedState
E/WifiStateMachine(  978):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:97 bcn=0
E/WifiStateMachine(  978): processMsg: ConnectModeState
E/WifiStateMachine(  978):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:97 bcn=0
E/WifiStateMachine(  978): processMsg: DriverStartedState
E/WifiStateMachine(  978):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:97 bcn=0
E/WifiStateMachine(  978): processMsg: SupplicantStartedState
E/WifiStateMachine(  978):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:97 bcn=0
D/WifiStateMachine(  978): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1349): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  978): [1,448,986,943,773 ms] noteScanEnd no scan source
W/WifiHW  (  978): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1349): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987',
E/WifiStateMachine(  978): handleMessage: X
W/WISPrService( 5944): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5944): trigger connection
D/WISPrService( 5944): continue
D/WISPrService( 5944): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5944): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5944): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5944): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/FlexNetS( 6555): updateSvcAllowedInSettings:false
D/WISPrService( 5944): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5944): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/WISPrService( 5944): >>>>>WISPrService start isConnected = false<<<<<,
D/WISPrService( 5944): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5944): start DataConnection,
,D/libc    ( 5944): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5944): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5944): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5944): [NET] android_getaddrinfo_proxy+
D/libc    ( 5944): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  397): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/FlexNetS( 6555): updateSvcAllowedInSettings:false
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5944): [NET] android_getaddrinfo_proxy-, NODATA
,D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false
,D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false
,D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false
,D/libc    ( 5944): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5944): [NET] android_getaddrinfofornet-, err=8
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WISPrService( 5944): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false
,D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false
,D/WifiService(  978): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6555): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6775): [fe0.2.]  listen tmrbb8,
,D/MdProvGlob( 6621): remove item 101 (p2d27in201) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 6775): [fe0.2.] summary 118:p2 ignore
,D/PMS     (  978): acquireWL(12110f3d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 978 1000 WorkSource{1000},
,V/AlarmManager(  978): sending alarm PendingIntent{29ea5b3: PendingIntentRecord{f7b4770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=118599, Int=0
V/AlarmManager(  978): sending alarm PendingIntent{2a164332: PendingIntentRecord{1ea00883 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142571, Int=0
,D/PMS     (  978): releaseWL(12110f3d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1236): Weather sync is On
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,D/Process (  978): killProcessQuiet, pid=6233,
I/ActivityManager(  978): Killing 6233:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  978): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  978): Recipient 6233,
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/jxcore-log( 6715): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6715): 
I/jxcore-log( 6715): my name is : HTC-HTC One M8s_PT9668,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): attempting to connect to test coordinator,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): check test folder
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): found test : ./testFindPeers.js,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): found test : ./testReConnect.js,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): found test : ./testSendData.js,
,I/jxcore-log( 6715): 
,I/jxcore-log( 6715): Test app app.js loaded
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/chromium( 6715): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/GpsLocationProvider(  978): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  978): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  978): acquireWL(250dba00): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 978 1000 null,
,D/libc    (  978): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  978): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  978): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  978): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  978): [NET] android_getaddrinfo_proxy+
,D/libc    (  978): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  397): [NET] android_getaddrinfofornet-, err=7,
D/libc    (  978): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    (  978): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  978): [NET] android_getaddrinfofornet-, err=8
D/libc    (  978): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  978): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  978): [NET] android_getaddrinfo_proxy+
D/libc    (  978): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    (  978): [NET] android_getaddrinfo_proxy-, NODATA
,D/libc    (  978): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  978): [NET] android_getaddrinfofornet-, err=8
D/libc    (  978): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  978): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  978): [NET] android_getaddrinfo_proxy+
,D/libc    (  978): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  397): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/ConnectivityService(  978): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    (  978): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  978): acquireWL(383fe8f5): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 978 1000 null
,D/GpsLocationProvider(  978): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/GpsLocationProvider(  978):  [handleDownloadXtraData]download failure, retry count: 1
D/PMS     (  978): releaseWL(383fe8f5): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/AlarmManager(  978): [AlarmQueuing] connectivity wifi: false
,D/htcCheckinService(  978): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  978): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/GpsLocationProvider(  978): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  978): acquireWL(eaf068a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 978 1000 null
D/GpsLocationProvider(  978): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  978): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  978): releaseWL(250dba00): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
I/ConnectivityHelper( 1601): [onReceive] WIFI(1): DISCONNECTED
,I/ActivityManager(  978): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6810 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  978): No APN found to select.
,D/PMS     (  978): releaseWL(eaf068a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6775): [36e.1.]  listen tmrbb8
,D/MdScDataSum( 6775): [36e.1.] summary 118:p1 ignore
,I/MusicStore( 6810): Database version: 120
,D/VoldConnector(  978): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6810): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  978): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6810): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  978): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6810): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6810): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6810): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6810): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6810): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@27df5b00: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
W/ActivityThread( 6810): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 6810): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6810): GMSCore installation verified
,I/ConfigStore( 6810): Config Database version: 1,
,I/PackageManager(  978):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6810, uid=10159, userID:0
,D/WifiDisplayAdapter(  978): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  978):     Client/Owner: Client
D/WifiDisplayAdapter(  978):     GroupId: 
D/WifiDisplayAdapter(  978):     Passphrase: 
D/WifiDisplayAdapter(  978):     SessionId: 0
D/WifiDisplayAdapter(  978):     IP Address: }
,D/MediaRouterService(  978): Client com.google.android.music (pid 6810): Registered,
,D/WifiDisplayAdapter(  978): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  978):     Client/Owner: Client
D/WifiDisplayAdapter(  978):     GroupId: 
D/WifiDisplayAdapter(  978):     Passphrase: 
D/WifiDisplayAdapter(  978):     SessionId: 0
D/WifiDisplayAdapter(  978):     IP Address: }
,I/MediaRouter( 6810): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6810): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,D/AutoSetting( 1683): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/PackageManager(  978):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6810, uid=10159, userID:0
D/MobileConnectivityChangeReceiver( 6437): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1683): Util - no network available!
,D/MobileConnectivityChangeReceiver( 6437): onReceive CONNECTIVITY_CHANGE networkType=1
,I/GHttpClientFactory( 6810): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1683): service - onCreate()
,I/GoogleURLConnFactory( 6810): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1683): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate,
,D/LocationManagerService(  978): request 24eda112 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  978): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1683): service - mHandler: cancel location update
,D/AutoSetting( 1683): service -           changes count: 0
,I/iu.Environment( 4461): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4461): num queued entries: 0
,I/iu.UploadsManager( 4461): num updated entries: 0
,I/iu.SyncManager( 4461): NEXT; no task
,D/ChimeraCfgMgr( 4461): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/ActivityManager(  978): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6851 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/Babel   ( 6487): connection state changed from UNKNOWN to DISCONNECTED
,D/Process (  978): killProcessQuiet, pid=6394
I/ActivityManager(  978): Killing 6394:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  978): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  426): Explicit concurrent mark sweep GC freed 8645(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 243us total 29.961ms
,I/art     (  426): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 171us total 23.396ms
,I/art     (  426): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 193us total 21.824ms
,I/ActivityManager(  978): Recipient 6394
,D/VoldConnector(  978): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6851): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  978): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6851): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6851): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6851):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6851):   adb logcat -s GAv4
,D/VoldConnector(  978): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6851): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  978): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6851): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6851): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6851): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6851): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6851): [apache-http] Connection GC has been deprecated!
,W/global  ( 6851): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6851): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6851): Time to load native libraries: 3 ms (timestamps 6537-6540),
,I/LibraryLoader( 6851): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6851): Binding Chromium to main looper Looper (main, tid 1) {44881a3}
,I/LibraryLoader( 6851): Expected native library version number "",actual native library version number ""
,I/chromium( 6851): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6851): Initializing chromium process, singleProcess=true
,W/art     ( 6851): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6851): ApplicationContext is null in ApplicationStatus
,W/chromium( 6851): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6851): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6851): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6851): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6851): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6851): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6851): Local Branch: 
I/Adreno-EGL( 6851): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6851): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6851):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6851): Requires BLUETOOTH permission,
,I/NSApplication( 6851): Starting up...
,I/ActivityManager(  978): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6909 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  978): killProcessQuiet, pid=6463,
I/ActivityManager(  978): Killing 6463:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  978): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  978): Recipient 6463,
,I/ActivityManager(  978): Killing 5969:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  978): killProcessQuiet, pid=5969,
D/Process (  978): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  978): Recipient 5969
,E/WifiStateMachine(  978): handleMessage: E msg.what=131168,
E/WifiStateMachine(  978): processMsg: DisconnectedState
,E/WifiStateMachine(  978):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  978): processMsg: ConnectModeState,
E/WifiStateMachine(  978):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  978): processMsg: DriverStartedState,
E/WifiStateMachine(  978):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  978): processMsg: SupplicantStartedState
E/WifiStateMachine(  978):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  978): processMsg: DefaultState
E/WifiStateMachine(  978):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  978): handleMessage: X
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC >>,
,D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC <<
,D/BluetoothAdapter( 6715): 767191800: getState(). Returning 12,
I/jxcore-log( 6715): BLE supported!!
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(3667877f): PARTIAL_WAKE_LOCK  *alarm* 0x1 978 1000 WorkSource{10024},
V/AlarmManager(  978): sending alarm PendingIntent{97934c: PendingIntentRecord{28330f95 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=149775, Int=0
D/PMS     (  978): acquireWL(ebb38aa): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1937 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  978): releaseWL(3667877f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1937): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1937): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1937): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1937): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1937): [NET] android_getaddrinfo_proxy+
D/libc    ( 1937): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1937): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  978): releaseWL(ebb38aa): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  978): acquireWL(2e509838): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6810 10159 null
,I/art     (  978): Explicit concurrent mark sweep GC freed 40130(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 2.069ms total 210.290ms
,I/PackageManager(  978):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6810, uid=10159, userID:0,
,D/PMS     (  978): releaseWL(2e509838): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6810): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6810): Stop autocaching.
,D/WearableService( 4828): callingUid 10024, callindPid: 4828
,E/GmsUtils( 6810): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6810): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,W/ContextImpl(  978): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/AutoSetting( 1683): service - handleMessage() stop self
,D/AutoSetting( 1683): service - handleMessage() quit looper
D/AutoSetting( 1683): service - onDestroy() END,
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(914628b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 978 1000 null
,I/BatteryService(  978): n_update end
D/UsbnetService(  978): BroadcastReceiver::onReceive+
D/PMS     (  978): releaseWL(914628b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  978): onReceive BATTERY_CHANGED
D/NotificationService(  978): plugged=true pluggin=true
D/UsbnetService(  978):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  978): BroadcastReceiver::onReceive-
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
D/WifiController(  978): battery changed pluggedType: 2
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  978): updateBatteryInfo
D/WifiController(  978): handleMessage: E msg.what=155652
D/PMS     (  978): runPSCheck
D/WifiController(  978): processMsg: DeviceActiveState
D/HtcPowerSaver(  978): Checking...
D/WifiController(  978): processMsg: StaEnabledState
I/HtcPowerSaver(  978): >> updateStatus
D/WifiController(  978): processMsg: DefaultState
D/WifiController(  978): handleMessage: X
D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1360): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  978): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  978): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,D/TelephonyReceiver( 1560): switchBindHtcMsgCursor: null,
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(16367f68): PARTIAL_WAKE_LOCK  *alarm* 0x1 978 1000 WorkSource{1000}
,V/AlarmManager(  978): sending alarm PendingIntent{2761f81: PendingIntentRecord{28aae826 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1448986973573, Int=0,
D/PMS     (  978): acquireWL(16e49c67): PARTIAL_WAKE_LOCK  *backup* 0x1 978 1000 null
V/AlarmManager(  978): sending alarm PendingIntent{29ea5b3: PendingIntentRecord{f7b4770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=178599, Int=0
V/AlarmManager(  978): sending alarm PendingIntent{5a82a14: PendingIntentRecord{4e432bd com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=188451, Int=0
,D/PMS     (  978): acquireWL(17cd60b2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1937 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  978): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  978): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  978): releaseWL(16e49c67): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  978): releaseWL(17cd60b2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  978): releaseWL(16367f68): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/WeatherUtility( 1236): Weather sync is On,
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,D/PMS     (  978): releaseWL(314430b): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  978): Failed to find a new network - expiring NetTransition Wakelock
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(e2cd5fe): PARTIAL_WAKE_LOCK  *alarm* 0x1 978 1000 WorkSource{1000}
,V/AlarmManager(  978): sending alarm PendingIntent{32beb15f: PendingIntentRecord{3b6a7ac android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=208802, Int=0
,D/PMS     (  978): releaseWL(e2cd5fe): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/HtcUPManager( 1236): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1683): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3f5524f7
D/HtcUPManager( 1236): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  978): Killing 5883:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  978): killProcessQuiet, pid=5883
,D/Process (  978): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  978): Recipient 5883
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(16e3fc75): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 978 1000 null
I/BatteryService(  978): n_update end
D/PMS     (  978): releaseWL(16e3fc75): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1236): closing low battery warning: level=100
D/DotMatrix( 1360): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  978): updateBatteryInfo
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  978): plugged=true pluggin=true
D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
D/PMS     (  978): runPSCheck
D/UsbnetService(  978): BroadcastReceiver::onReceive+
D/WifiController(  978): battery changed pluggedType: 2
D/UsbnetService(  978): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  978): Checking...
D/UsbnetService(  978):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  978): >> updateStatus
D/UsbnetService(  978): BroadcastReceiver::onReceive-
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  978): handleMessage: E msg.what=155652
D/WifiController(  978): processMsg: DeviceActiveState
D/WifiController(  978): processMsg: StaEnabledState
D/WifiController(  978): processMsg: DefaultState
D/WifiController(  978): handleMessage: X
I/HtcPowerSaver(  978): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  978): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(2d7c540a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 978 1000 WorkSource{1000},
V/AlarmManager(  978): sending alarm PendingIntent{29ea5b3: PendingIntentRecord{f7b4770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=238599, Int=0
V/AlarmManager(  978): sending alarm PendingIntent{947047b: PendingIntentRecord{8bc9298 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=445315, Int=0
D/GpsLocationProvider(  978): receive broadcast intent, action: com.htc.location.XTRA_ALARM_TIMEOUT
D/GpsLocationProvider(  978): ALARM_XTRA_TIMEOUT
D/PMS     (  978): acquireWL(d93a6d6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 978 1000 null
V/AlarmManager(  978): sending alarm PendingIntent{24376d57: PendingIntentRecord{37344044 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1448987141625, Int=0
,D/PMS     (  978): releaseWL(2d7c540a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1236): Weather sync is On
,W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,D/GpsLocationProvider(  978): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  978): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  978): releaseWL(d93a6d6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): ,
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/ContactMessageStore( 1560): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1560): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1560): sku_id=118
,D/ContactMessageStore( 1560): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1560): start background delete task...
,D/ContactMessageStore( 1560): size: 0 , 0
,D/ContactMessageStore( 1560): Background delete complete
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): ,
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(256c452d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 978 1000 null
I/BatteryService(  978): n_update end
,D/PMS     (  978): releaseWL(256c452d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  978): plugged=true pluggin=true
D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1360): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiController(  978): battery changed pluggedType: 2
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1236): closing low battery warning: level=100
,D/UsbnetService(  978): BroadcastReceiver::onReceive+
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  978): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  978): updateBatteryInfo
D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
D/PMS     (  978): runPSCheck
D/UsbnetService(  978):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  978): Checking...
D/UsbnetService(  978): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  978): >> updateStatus
D/WifiController(  978): handleMessage: E msg.what=155652
D/WifiController(  978): processMsg: DeviceActiveState
D/WifiController(  978): processMsg: StaEnabledState
D/WifiController(  978): processMsg: DefaultState
D/WifiController(  978): handleMessage: X
,I/HtcPowerSaver(  978): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  978): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(19fb5a62): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 978 1000 WorkSource{1000}
V/AlarmManager(  978): sending alarm PendingIntent{29ea5b3: PendingIntentRecord{f7b4770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=478599, Int=0
I/bt-btm  ( 3167): Received oneshot timer event complete
V/AlarmManager(  978): sending alarm PendingIntent{2f5b87f3: PendingIntentRecord{26571cb0 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=939965, Int=0
,I/bt-btm  ( 3167): btm_ble_timeout
I/bt-btm  ( 3167): btm_gen_resolvable_private_addr
,D/PMS     (  978): acquireWL(3df50729): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3167 1002 null
,D/bt-btm  ( 3167): btm_ble_rand_enc_complete
I/bt-btm  ( 3167): btm_gen_resolve_paddr_low
D/bt-smp  ( 3167): smp_encrypt_data
W/bt-smp  ( 3167): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3167): Plain text(LSB ~ MSB) = d4 6c 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3167): Encrypted text(LSB ~ MSB) = ea 28 b7 a7 6e 65 be 3c f4 65 3f d1 5a 23 4c f1 
I/bt-btm  ( 3167): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3167): Stopping oneshot timer
D/bt-btm  ( 3167): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  978): releaseWL(19fb5a62): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1236): Weather sync is On
,W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,D/PMS     (  978): releaseWL(3df50729): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(3c38baae): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 978 1000 WorkSource{1000}
,V/AlarmManager(  978): sending alarm PendingIntent{29ea5b3: PendingIntentRecord{f7b4770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=958599, Int=0
V/AlarmManager(  978): sending alarm PendingIntent{3d9cb04f: PendingIntentRecord{258953dc com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448987814406, Int=0,
,D/SmartSyncUtils( 6584): isEpsOn(), nState = 0,
,D/WeatherUtility( 1236): Weather sync is On
,W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data,
D/PMS     (  978): acquireWL(b2dece5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6584 1000 null
D/PMS     (  978): releaseWL(3c38baae): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6584): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6584): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6584): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6584): SettingOnTime = 1449036000000, randomSettingOnTime = 1449035645000
D/SmartSyncScreenOnOffTimeReceiver( 6584): SettingOffTime = 1449014400000, randomSettingOffTime = 1449015045000,
D/SmartSyncScreenOnOffTimeReceiver( 6584): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6584): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6584): bNightModeTurnOffOnce = false
,D/PMS     (  978): releaseWL(b2dece5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/PMS     (  978): acquireWL(1ed9d3ba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 978 1000 null
,I/BatteryService(  978): n_update end
D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  978): releaseWL(1ed9d3ba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1360): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
D/NotificationService(  978): plugged=true pluggin=true
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  978): BroadcastReceiver::onReceive+
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  978): onReceive BATTERY_CHANGED
D/WifiController(  978): battery changed pluggedType: 2
D/UsbnetService(  978):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  978): updateBatteryInfo
D/UsbnetService(  978): BroadcastReceiver::onReceive-
,D/PMS     (  978): runPSCheck
D/WifiController(  978): handleMessage: E msg.what=155652
D/HtcPowerSaver(  978): Checking...
D/WifiController(  978): processMsg: DeviceActiveState
I/HtcPowerSaver(  978): >> updateStatus
D/WifiController(  978): processMsg: StaEnabledState
I/HtcPowerSaver(  978): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  978): processMsg: DefaultState
I/HtcPowerSaver(  978): << updateStatus
D/WifiController(  978): handleMessage: X
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(3d1e026b): PARTIAL_WAKE_LOCK  *alarm* 0x1 978 1000 WorkSource{1000},
V/AlarmManager(  978): sending alarm PendingIntent{250fc51: PendingIntentRecord{21024cb6 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804662, Int=0
,V/AlarmManager(  978): sending alarm PendingIntent{29ea5b3: PendingIntentRecord{f7b4770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1018598, Int=0
V/AlarmManager(  978): sending alarm PendingIntent{3445d1c8: PendingIntentRecord{10557261 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448987975454, Int=1800000
,D/PMS     (  978): acquireWL(15417186): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4461 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  978): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6953 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  978): sending alarm PendingIntent{11185a47: PendingIntentRecord{cca4274 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1448987642381, Int=0,
,V/AlarmManager(  978): sending alarm PendingIntent{34332012: PendingIntentRecord{3ec8c12c com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448987767063, Int=0
,W/ContextImpl( 6584): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  978): acquireWL(2d8311e0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4461 10024 WorkSource{10024 com.google.android.gms},
D/WeatherUtility( 1236): Weather sync is On,
D/PMS     (  978): releaseWL(15417186): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  978): releaseWL(3d1e026b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6584): MY_DEBUG = false
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,D/PowerUsageService( 6584): repeat time = 1448988875547,
,I/EventLogService( 4461): Aggregate from 1448986903190 (log), 1448986175410 (data),
,D/PMS     (  978): releaseWL(2d8311e0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6584): PowerProfile::POWER_SCREEN_FULL = 154.8
,E/cutils-trace( 6976): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6976): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6976): dex2oat: override thread count:4
,D/PowerUsageList:BatterySipperExt( 6584): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 6584): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 6584): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 6584): calcPower(), no data,
,I/dex2oat ( 6976): dex2oat took 808.336ms (threads: 4),
,I/PushClient( 6953): ApplicationMonitor {1a9b2636}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6953): ApplicationMonitor {1a9b2636}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
,I/PushClient( 6953): ApplicationMonitor {1a9b2636}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6953): ApplicationMonitor {1a9b2636}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6953): ApplicationMonitor {1a9b2636}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6953): ApplicationMonitor {1a9b2636}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6953): ApplicationMonitor {1a9b2636}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6953): ApplicationMonitor {1a9b2636}: logBasicAppInfo(): Htc_DEBUG_flag:          false,
I/PushClient( 6953): ApplicationMonitor {1a9b2636}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6953): PnsModel {38c74bd1}: update(): Update registration caused by: alarm
,I/PushClient( 6953): PnsConfigModel {2dd1be3c}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6953): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6953): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6953): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.,
,W/ContextImpl( 6953): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  978): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6984 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6984): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6984 dbg=false s=true
,I/DeviceManagement( 6984): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6984): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6984): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6984): WorkflowService: Starting workflow service
,I/DeviceManagement( 6984): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@38c74bd1] args=[Bundle[mParcelledData.dataSize=88]]
I/DeviceManagement( 6984): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6984): ModelRegistry: Loading model meta data from resources...
I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/DeviceManagement( 6984): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6984): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6984): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6984): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6984): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6984): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@38c74bd1]
,I/DeviceManagement( 6984): WorkflowService: Stopping workflow service,
,I/ActivityManager(  978): Killing 6645:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  978): killProcessQuiet, pid=6645
,D/Process (  978): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  978): Recipient 6645
,I/PushClient( 6953): PnsModel {38c74bd1}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  978): killProcessQuiet, pid=6517,
I/ActivityManager(  978): Killing 6517:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  978): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  978): Recipient 6517,
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(3beeb310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 978 1000 null
I/BatteryService(  978): n_update end
D/PMS     (  978): releaseWL(3beeb310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  978): updateBatteryInfo
D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  978): plugged=true pluggin=true
D/DotMatrix( 1360): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  978): runPSCheck
D/UsbnetService(  978): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  978): Checking...
D/UsbnetService(  978): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  978): >> updateStatus
D/UsbnetService(  978):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  978): BroadcastReceiver::onReceive-
D/WifiController(  978): battery changed pluggedType: 2
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  978): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  978): handleMessage: E msg.what=155652
I/HtcPowerSaver(  978): << updateStatus
,D/WifiController(  978): processMsg: DeviceActiveState
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  978): processMsg: StaEnabledState
D/WifiController(  978): processMsg: DefaultState
D/WifiController(  978): handleMessage: X
D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory),
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/UsageStatsService(  978): User[0] Flushing usage stats to disk
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(d914e09): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 978 1000 null
I/BatteryService(  978): n_update end
D/PMS     (  978): releaseWL(d914e09): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  978): updateBatteryInfo
,D/DotMatrix( 1360): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  978): plugged=true pluggin=true
D/DotMatrix( 1360): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1236): closing low battery warning: level=100,
D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
D/PMS     (  978): runPSCheck
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  978): Checking...
,D/UsbnetService(  978): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  978): >> updateStatus
D/UsbnetService(  978): onReceive BATTERY_CHANGED
D/WifiController(  978): battery changed pluggedType: 2
D/UsbnetService(  978):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  978): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  978): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  978): handleMessage: E msg.what=155652
I/HtcPowerSaver(  978): << updateStatus
D/WifiController(  978): processMsg: DeviceActiveState
D/WifiController(  978): processMsg: StaEnabledState
D/WifiController(  978): processMsg: DefaultState
D/WifiController(  978): handleMessage: X
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,D/PMS     (  978): acquireWL(118822f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 978 1000 WorkSource{1000},
V/AlarmManager(  978): sending alarm PendingIntent{29ea5b3: PendingIntentRecord{f7b4770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1198599, Int=0
I/bt-btm  ( 3167): Received oneshot timer event complete
V/AlarmManager(  978): sending alarm PendingIntent{e73f03c: PendingIntentRecord{4f7c1c5 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1839979, Int=0
I/bt-btm  ( 3167): btm_ble_timeout
D/PMS     (  978): acquireWL(3de5b71a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3167 1002 null
I/bt-btm  ( 3167): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3167): btm_ble_rand_enc_complete
,I/bt-btm  ( 3167): btm_gen_resolve_paddr_low
D/bt-smp  ( 3167): smp_encrypt_data
W/bt-smp  ( 3167): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3167): Plain text(LSB ~ MSB) = 35 4a 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3167): Encrypted text(LSB ~ MSB) = ae 84 e2 e8 95 59 a1 63 56 b1 a8 39 ef ac fd c1 
I/bt-btm  ( 3167): btm_gen_resolve_paddr_cmpl,
W/bt-btm  ( 3167): Stopping oneshot timer
D/bt-btm  ( 3167): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  978): Prepared write state in 17ms
,I/ProcessStatsService(  978): Prepared write state in 12ms
,I/ProcessStatsService(  978): Prepared write state in 12ms,
,I/ProcessStatsService(  978): Prepared write state in 8ms,
,D/PMS     (  978): releaseWL(118822f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1236): Weather sync is On,
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,I/ProcessStatsService(  978): Pruning old procstats: /data/system/procstats/state-2015-11-30-18-22-26.bin,
,D/PMS     (  978): releaseWL(3de5b71a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,I/jxcore-log( 6715): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6715): 
,TIME-OUT KILL (timeout was 1800000ms)
```
