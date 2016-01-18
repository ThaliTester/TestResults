#### Test 56151093f6e24ff_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  968): acquireWL(7df71b6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
,D/PMS     (  968): releaseWL(7df71b6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
--------- beginning of main
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/HeadsetStateMachine( 3239): Disconnected process message: 10, size: 0
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 6839): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6839): ====startRecUseTime====
D/htc.customization.log.level( 6839):  is 
W/CustomizationLogLevel( 6839): Level value is invalid, use default level 2
D/CustomizationManager( 6839):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6839): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6839): Parsing tag category name = system
I/CustomizationCIDLoader( 6839): Parsing tag category name = application
I/CustomizationCIDLoader( 6839): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6839): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6839): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6839): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6839): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6839): add string-array item, value = 42507
I/CustomizationCIDLoader( 6839): add string-array item, value = 21902
I/CustomizationCIDLoader( 6839): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6839): add string-array item, value = 23420
I/CustomizationCIDLoader( 6839): add string-array item, value = 22299
I/CustomizationCIDLoader( 6839): add string-array item, value = 24002
I/CustomizationCIDLoader( 6839): add string-array item, value = 23210
I/CustomizationCIDLoader( 6839): add string-array item, value = 23205
I/CustomizationCIDLoader( 6839): add string-array item, value = 23806
I/CustomizationCIDLoader( 6839): add string-array item, value = 23430
I/CustomizationCIDLoader( 6839): add string-array item, value = 23408
I/CustomizationCIDLoader( 6839): add string-array item, value = 27205
I/CustomizationCIDLoader( 6839): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6839):  Read CID file spent 0.105 (s)
D/CustomizationManager( 6839):  All configurations done spent 0.106 (s)
D/PMS     (  968): acquireHCC(178d0eb7): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 968 1000 null
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6839 on display 0
D/PMS     (  968): acquireHCC(1a153624): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 968 1000 null
W/asset   (  968): Copying FileAsset 0x558809a590 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6857 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1307): [EventService]  onDisplayChanged: 0
V/ActivityManager(  968): Display changed displayId=0
D/DotMatrix( 1307): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6857): Copying FileAsset 0xac203d50 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1495): [trimMemory] 20
I/WebViewFactory( 6857): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6857): Time to load native libraries: 10 ms (timestamps 2545-2555),
,I/LibraryLoader( 6857): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6857): Binding Chromium to main looper Looper (main, tid 1) {30c3453c},
I/LibraryLoader( 6857): Expected native library version number "",actual native library version number ""
,I/chromium( 6857): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6857): Initializing chromium process, singleProcess=true,
,W/art     ( 6857): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6857): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6857): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6857): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6857): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6857): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6857): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6857): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6857): Local Branch: 
I/Adreno-EGL( 6857): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6857): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6857):                  d74aa161a12b9c6fc6332151,
,D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER,
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b0ee1a8:true
W/System.err(  968): java.lang.Throwable: stack dump
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,W/art     ( 6857): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6857): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6857): CordovaWebView is running on device made by: HTC
,W/art     ( 6857): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6857): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6857): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  968): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
,D/StatusBarManagerService(  968): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
,D/FindExtension( 6857): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6857): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@12490696, mServedView=org.apache.cordova.engine.SystemWebView{371db217 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@18b20604
I/InputMethodManagerService(  968): Disable input method client, pid=1495,
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6857): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +624ms (total +672ms)
,W/BindingManager( 6857): Cannot call determinedVisibility() - never saw a connection for the pid: 6857
,D/JsMessageQueue( 6857): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6857): JniHelper::setJavaVM(0xab0988f8), pthread_self() = -1405427504,
D/JX-Cordova( 6857): jxcore cordova android initializing
,W/jxcore-log( 6857): Initializing JXcore engine
,W/jxcore-log( 6857): JXcore engine is ready
,W/jxcore-log( 6857): Starting JXcore engine,
,D/PMS     (  968): acquireWL(7aa7e6d): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024}
,V/AlarmManager(  968): sending alarm PendingIntent{2b6b3aa2: PendingIntentRecord{23d18333 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144235, Int=0
,D/PMS     (  968): releaseWL(7aa7e6d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/PMS     (  968): releaseHCC(178d0eb7): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  968): releaseHCC(1a153624): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6857): Platform android
W/jxcore-log( 6857): 
W/jxcore-log( 6857): Process ARCH arm,
W/jxcore-log( 6857): 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6857): JXcore Cordova bridge is ready!
I/jxcore-log( 6857): 
W/jxcore-log( 6857): JXcore engine is started,
I/Choreographer( 6857): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6857): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6857): Toggling radios to true
I/jxcore-log( 6857): 
,D/BluetoothAdapter( 6857): enable(): BT is already enabled..!
,E/WifiTrafficPoller(  968): ADD_CLIENT: 8,
,D/WifiService(  968): New client listening to asynchronous messages
,D/WifiManager( 6857): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
W/Settings:Agent(  968): MONITOR_LOG
D/WifiService(  968): setWifiEnabled: true pid=6857, uid=10366
W/Settings:Agent(  968): name: wifi_on
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  968): value: 2
I/WifiService(  968): isSprintWifiRestricted(): false
,W/Settings:Agent(  968): >> traceCallingStack()
I/WifiService(  968): isMdmWifiRestricted(): false
W/Settings:Agent(  968): Process.myPid(): 968
,W/Settings:Agent(  968): Process.myTid(): 1569
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
W/System.err(  968): java.lang.Throwable: stack dump
,W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  968): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  968): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 15(ms)
D/WifiManager( 6857): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  968): handleMessage: E msg.what=155656
D/WifiController(  968): processMsg: DeviceActiveState
E/WifiStateMachine(  968): handleMessage: E msg.what=131145
,D/WifiManager( 6857): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_DISCONNECT 0 0
D/WifiController(  968): processMsg: StaEnabledState,
D/WifiController(  968): handleMessage: X
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT",
D/wpa_supplicant( 1338): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1338): wlan0: Cancelling scan request
D/wpa_supplicant( 1338): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1338): TDLS: Tear down peers,
D/wpa_supplicant( 1338): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6857): Radios toggled
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): My device name is: HTC-HTC One M8s
I/jxcore-log( 6857): 
,D/wpa_supplicant( 1338): wlan0: Event DEAUTH (12) received
,D/PMS     (  968): acquireWL(2a096f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/wpa_supplicant( 1338): wlan0: Deauthentication notification
D/wpa_supplicant( 1338): wlan0:  * reason 3 (locally generated)
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1338): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1338): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1338): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1338): enter disconnect check
I/wpa_supplicant( 1338): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1338): wlan0: Auto connect disabled: do not try to re-connect
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1338): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  968): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  968): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  968): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  968): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/TetherSettings( 5475): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5475): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5475): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5475): Cust_ConnectToPC   : spcsc>false
D/        ( 5475): Cust_ConnectToPC   : IPT>true
D/        ( 5475): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5475): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5475): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5475): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5475): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 1338): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1338): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5588043f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1338):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1338): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1338): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1338): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1338): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1338): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1338): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
W/ContextImpl( 5475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=0
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1338): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1338): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1338): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  968): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: ConnectedState
I/SmartNS_Utility( 5475): setISNotification
E/WifiStateMachine(  968): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  968): release()
E/WifiStateMachine(  968): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  968): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/SmartNS_Utility( 5475): usb_cable_connect = 1
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/SmartNS_Utility( 5475): usb_denied = 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
I/SmartNS_PSService( 5475): usb notificaiton:true
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1338): Power_Mode_Type mode = 0
I/wpa_supplicant( 1338): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  968): setDhcpActive: false
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 1954): Read error: ssl=0x55877c4470: I/O error during system call, Connection timed out
D/PMS     (  968): acquireWL(39fd9469): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info<unknown ssid>
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  968): NetworkAgent != null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/PMS     (  968): releaseWL(2a096f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  968): autoRoamSetBSSID any key="NG700"WPA_PSK
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/NetworkPolicy(  968): updateNotificationsLocked()
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/SmartNS_Utility( 5475): usb_cable_connect = 1
,W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/SmartNS_Utility( 5475): usb_denied = 0
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/SmartNS_PSService( 5475): usb notificaiton:true
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  968):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  968): Start Disconnecting Watchdog 1
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131146
E/WifiStateMachine(  968): processMsg: DisconnectingState
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  968):  ConnectModeState CMD_RECONNECT 0 0
,W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1338): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1338): Fast associate: Old scan results
D/wpa_supplicant( 1338): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1338): wpa_supplicant_scan enter
D/wpa_supplicant( 1338): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1338): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1338): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1338): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1338): WPS:  * Request Type
D/wpa_supplicant( 1338): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1338): WPS:  * UUID-E
D/wpa_supplicant( 1338): WPS:  * Primary Device Type
D/wpa_supplicant( 1338): WPS:  * RF Bands (3)
D/wpa_supplicant( 1338): WPS:  * Association State
D/wpa_supplicant( 1338): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1338): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1338): WPS:  * Manufacturer
D/wpa_supplicant( 1338): WPS:  * Model Name
D/wpa_supplicant( 1338): WPS:  * Model Number
D/wpa_supplicant( 1338): WPS:  * Device Name
D/wpa_supplicant( 1338): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1338): P2P: * P2P IE header
D/wpa_supplicant( 1338): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1338): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1338): wlan0: Add radio work 'scan'@0x5588046680
D/wpa_supplicant( 1338): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1338): wlan0: Starting radio work 'scan'@0x5588046680 after 0.000059 second wait
D/wpa_supplicant( 1338): wlan0: nl80211: scan request
E/WifiStateMachine(  968): handleMessage: X
D/wpa_supplicant( 1338): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: DisconnectingState
D/wpa_supplicant( 1338): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1338): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1338): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1338): wlan0: Own scan request started a scan in 0.000121 seconds
I/wpa_supplicant( 1338): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  968):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/WifiStateMachine(  968):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D,/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): processMsg: DefaultState
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147460
E/WifiStateMachine(  968): processMsg: DisconnectingState
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  968): stopDataStallAlarm 
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  968):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=145220
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=145220
E/WifiStateMachine(  968): ConnectModeState: Network connection lost 
E/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  968): DisconnectedState call setCountryCode()
E/WifiStateMachine(  968):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1338): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1338): wlan0: Cancelling scan request
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NativeCrypto( 1954): SSL shutdown failed: ssl=0x55877c4470: I/O error during system call, Broken pipe
D/wpa_supplicant( 1338): wlan0: nl80211: sched_scan request
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/ConnectivityService(  968): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  968): releaseWL(39fd9469): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/SmartNS_NSReceiver( 5475): Tethered state change:false isNSOpening:false
I/RemoteViews( 1217): reapply : com.android.settings 1 36
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
I/RemoteViews( 1217): reapply : com.android.settings 0 36
D/wpa_supplicant( 1338): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1338): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1338): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1338): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1338): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1338): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1338): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1338): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1338): wlan0: Scan completed in 0.041773 seconds
D/wpa_supplicant( 1338): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1338): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,D/wpa_supplicant( 1338): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1338): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1338): wlan0: New scan results available (own=1 ext=0)
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): handleMessage: X
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1338): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1338): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1338): wlan0: Radio work 'scan'@0x5588046680 done in 0.042680 seconds
D/wpa_supplicant( 1338): wlan0: Selecting BSS from priority group 524
D/wpa_supplicant( 1338): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 1338): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1338): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1338): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1338):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1338): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1338): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x5588045c00  current_ssid=0x0
D/wpa_supplicant( 1338): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1338): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1338): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1338): wlan0: Add radio work 'connect'@0x5588046680
D/wpa_supplicant( 1338): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1338): wlan0: Starting radio work 'connect'@0x5588046680 after 0.000054 second wait
I/wpa_supplicant( 1338): check if in concurrent case
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=145259  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/wpa_supplicant( 1338): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=145259  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
D/wpa_supplicant( 1338): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1338): wlan0: Cancelling sched scan
E/WifiStateMachine(  968):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/wpa_supplicant( 1338): nl80211: Sched scan stop sent (ret=0)
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1338): wlan0: Cancelling scan request
D/wpa_supplicant( 1338): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1338): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1338): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1338): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1338): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1338): RSN: PMKSA cache search - network_ctx=0x5588045c00 try_opportunistic=0
D/wpa_supplicant( 1338): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1338): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1338): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1338): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1338): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1338): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1338): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1338): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1338): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1338): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1338): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 0->0 (DORMANT)
E/WifiStateMachine(  968): processMsg: DefaultState
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1338): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1338): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1338): nl80211: Unsubscribe mgmt frames handle 0x888888dd008cd989 (mode change)
D/wpa_supplicant( 1338): nl80211: Subscribe to mgmt frames with non-AP handle 0x5588045100
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=0104
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=040a
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=040b
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=040c
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=040d
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=090a
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=090b
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=090c
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=090d
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=0409506f9a09
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=7f506f9a09
E/WifiStateMachine(  968): handleMessage: X
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=0801
D/WifiNetworkAgent(  968): NetworkAgent: NetworkAgent channel lost
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=040e
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=06
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=0a07
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=0a11
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5588045100 match=0a1a
D/wpa_supplicant( 1338): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1338):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338):   * freq=2412
D/wpa_supplicant( 1338):   * freq_hint=2412
D/wpa_supplicant( 1338):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1338):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1338):   * WPA Versions 0x2
D/wpa_supplicant( 1338):   * pairwise=0xfac04
D/wpa_supplicant( 1338):   * group=0xfac04
D/wpa_supplicant( 1338):   * akm=0xfac02
D/wpa_supplicant( 1338):   * Auth Type 0
D/wpa_supplicant( 1338): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5588045c3a
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=145262  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
D/wpa_supplicant( 1338): nl80211: Connect request send successfully
D/wpa_supplicant( 1338): wlan0: Setting authentication timeout: 10 sec 0 usec
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1338): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1338): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1338): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1338): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1338): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1338): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  968): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  968): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=42 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  968): NetworkAgent == null
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
I/QuickSettingWifi( 1217): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=145269  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): handleMessage: X
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): handleMessage: E msg.what=147461
E/WifiStateMachine(  968): processMsg: DisconnectedState
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  968):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:71 bcn=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:71 bcn=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:71 bcn=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:71 bcn=0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1338): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  968): [1,453,125,277,677 ms] noteScanEnd no scan source
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1338): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  968): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@29073d54 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  968): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): NG700 c0:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  968): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  968): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  968):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-56 freq=2412
E/WifiAutoJoinController (  968): Gonzos 38:f8:89:11:e9:11 rssi=-83 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  968): UPC503894600 a0:c5:62:7a:49:97 rssi=-81 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): 01ABC c2:ff:d4:d3:aa:48 rssi=-55 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  968): ageScanResultsOut delay 40000 size 5 now 1453125277682
E/WifiAutoJoinController (  968): newSupplicantResults size=5 known=1 true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1338): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  968): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  968): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  968): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  968): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  968): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  968):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131213
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState CMD_TARGET_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=145282
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_TARGET_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=145282
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_TARGET_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=145283
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WISPrService( 5475): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  968):  SupplicantStartedState CMD_TARGET_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=145283
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=145283  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info0x
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 18
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): NetworkAgent == null
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 19
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=145292  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): handleMessage: X
E/WifiTrafficPoller(  968): ADD_CLIENT: 9
D/WifiService(  968): New client listening to asynchronous messages
D/ConnectivityService(  968): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  968): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  968): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524292
D/ConnectivityService(  968): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Disconnected - quitting
D/WIFI    (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  968): enter WifiNetworkFactory startNetwork. mIPTStart:false
I/SecurityController( 1217): onLost 100
D/usbnet  (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/NetworkManagementService(  968): Removing idletimer
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): handleMessage: X
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/PMS     (  968): acquireWL(24971f8f): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 968 1000 null
D/CSLegacyTypeTracker(  968): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  968): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/PMS     (  968): acquireWL(1790321c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
E/ConnectivityService(  968): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
D/DATA_ICON( 1217): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
W/WISPrService( 5475): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
D/WISPrService( 5475): trigger connection
V/NetworkPolicy(  968): updateIfacesLocked()
D/WISPrService( 5475): continue
D/DATA_ICON( 1217): dataConnected: false/false
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  968): updateNotificationsLocked()
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 5475): start DataConnection
D/libc    ( 5475): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5475): [NET] android_getaddrinfofornet-, err=8
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
,D/libc    ( 5475): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5475): [NET] android_getaddrinfofornet-, pass to proxy
I/ActivityManager(  968): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6918 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/libc    ( 5475): [NET] android_getaddrinfo_proxy+
,D/PMS     (  968): releaseWL(1790321c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/libc    ( 5475): [NET] android_getaddrinfo_proxy get netid:0
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
V/NetworkPolicy(  968): updateNotificationsLocked()
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5475): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/libc    ( 5475): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5475): [NET] android_getaddrinfofornet-, err=8
,D/wpa_supplicant( 1338): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1338): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1338): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1338): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1338): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1338): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1338): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1338): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/wpa_supplicant( 1338): nl80211: Connect event
D/wpa_supplicant( 1338): nl80211: Associated on 2412 MHz
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/wpa_supplicant( 1338): nl80211: Associated with c0:ff:d4:d3:aa:48
D/PMS     (  968): acquireWL(1886a8b4): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/wpa_supplicant( 1338): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1338): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1338): wlan0: Association info event
D/wpa_supplicant( 1338): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): wlan0: freq=2412 MHz
D/wpa_supplicant( 1338): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 1338): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/wpa_supplicant( 1338): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/PMS     (  968): releaseWL(1886a8b4): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 1338): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1338): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1338): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1338): wlan0: WPA: Association event - clear replay counter
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
D/wpa_supplicant( 1338): wlan0: WPA: Clear old PTK
V/NetworkPolicy(  968): updateNotificationsLocked()
D/wpa_supplicant( 1338): TDLS: Remove peers on association
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1338): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1338): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1338): EAPOL: enable timer tick
D/wpa_supplicant( 1338): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1338): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1338): wlan0: Cancelling scan request
D/wpa_supplicant( 1338): wlan0: Process pending EAPOL frame that was received just before association notification
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1338): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1338): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1338): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1338): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1338): wlan0:   key_length=16 key_data_length=0
,D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1338):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1338):   key_nonce - hexdump(len=32): b7 32 4f d0 eb 31 fb 7e 3c 69 e0 5b b7 24 13 19 94 57 69 90 ef 4b 9d ec f3 9e 9e 0f 1b 0b f4 0a
D/wpa_supplicant( 1338):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1338): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1338): RSN: msg 1/4 key data - hexdump(len=0):
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/Tethering(  968): interfaceStatusChanged wlan0, true
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=45 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  968): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WISPrService( 5475): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/HTCRequest(  968): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  968): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  968): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
V/Tethering(  968): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1338): WPA: Renewed SNonce - hexdump(len=32): 77 b7 ae 20 98 37 39 8e b3 09 ae 34 81 02 18 f9 4a 4d 30 28 74 27 d7 06 04 94 d2 40 81 cc 29 d3
D/wpa_supplicant( 1338): WPA: Nonce1 - hexdump(len=32): 77 b7 ae 20 98 37 39 8e b3 09 ae 34 81 02 18 f9 4a 4d 30 28 74 27 d7 06 04 94 d2 40 81 cc 29 d3
D/wpa_supplicant( 1338): WPA: Nonce2 - hexdump(len=32): b7 32 4f d0 eb 31 fb 7e 3c 69 e0 5b b7 24 13 19 94 57 69 90 ef 4b 9d ec f3 9e 9e 0f 1b 0b f4 0a
D/wpa_supplicant( 1338): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1338): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1338): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1338): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1338): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1338): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): WPA: Derived Key MIC - hexdump(len=16): 63 3c 29 2e dd ae ab 12 b9 93 14 47 f3 42 df c8
I/wpa_supplicant( 1338): htc_wext_set_keepalive +
I/wpa_supplicant( 1338): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1338): getPrivFuncNum +	
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1338): getPrivFuncNum -, cmd = 0x8bf6
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 1338): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1338): htc_wext_set_keepalive - ret = 0
D/Tethering(  968): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1338): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1338): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1338): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1338): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1338):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1338):   key_nonce - hexdump(len=32): b7 32 4f d0 eb 31 fb 7e 3c 69 e0 5b b7 24 13 19 94 57 69 90 ef 4b 9d ec f3 9e 9e 0f 1b 0b f4 0a
D/wpa_supplicant( 1338):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_rsc - hexdump(len=8): a8 16 00 00 00 00 00 00
D/wpa_supplicant( 13,38):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_mic - hexdump(len=16): 9e 9b 05 ca dd 29 12 0d 55 17 75 00 c2 4d d9 fe
D/wpa_supplicant( 1338): RSN: encrypted key data - hexdump(len=56): 89 ec c5 7d 78 7b f5 b0 78 a2 e9 69 2d 8f 5a fa ca 1f c2 95 e7 6e f0 af 7c 8f 38 17 e2 ed 91 f1 ...
D/wpa_supplicant( 1338): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1338): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1338): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1338): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 2f c5 ...
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1338): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1338): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1338): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): WPA: Derived Key MIC - hexdump(len=16): 8d e8 cc 5c d7 cc b5 c0 31 a7 31 69 63 3c f6 a2
D/wpa_supplicant( 1338): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5588046390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1338): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1338):    addr=c0:ff:d4:d3:aa:48
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1338): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1338): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1338): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1338): WPA: RSC - hexdump(len=6): a8 16 00 00 00 00
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x555f37ee68 key_idx=2 set_tx=0 seq_len=6 key_len=16
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1338): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): nl80211: KEY_SEQ - hexdump(len=6): a8 16 00 00 00 00
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1338):    broadcast key
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1338): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1338): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1338): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1338): wlan0: Radio work 'connect'@0x5588046680 done in 0.137133 seconds
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1338): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1338): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=48 dispatchEvent: WPA: Key negotiation ,completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=49 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  968): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1338): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 1338): set send_ind_to_ndc = 0
I/wpa_supplicant( 1338): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1338): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1338): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1338): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1338): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1338): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1338): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1338): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1338): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1338): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1338): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  968): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=51 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  968): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/Tethering(  968): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=145400  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=145401  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): handleMessage: X
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): handleMessage: E msg.what=147500
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  968): Enter handleAssociatedWithEvent
D/WifiStateMachine(  968): Associated
D/WifiStateMachine(  968): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  968): Exit handleAssociatedWithEvent
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=145403  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 20
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=145408  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  968):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=145410  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=145411  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147459
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=145412
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=145413
E/WifiStateMachine(  968): Network connection established
D/WifiStateMachine(  968): fetchFrequency(), freq = 2412
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 22
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1338): CTRL_IFACE SET 'pno'='0'
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
E/WifiStateMachine(  968): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 23
E/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 24
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  968): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  968): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  968): Got NetworkAgent Messenger
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  968): NetworkAgent connected
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  968): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  968): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  968): Start Dhcp Watchdog 2
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=145439  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
E/WifiStateMachine(  968):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=145439  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=145440  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): handleMessage: X
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=196612
E/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  968):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/PMS     (  968): acquireWL(16f0cf38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 968 1000 null
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  968): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  968): setDhcpActive: true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  968): do suspend false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1338): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1338): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/wpa_supplicant( 1338): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): noteBatchedScanstop()
E/WifiStateMachine(  968): handleMessage: X
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b58a47d target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3b58a47d target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
D/TetherSettings( 5475): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5475): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5475): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5475): Cust_ConnectToPC   : spcsc>false
D/        ( 5475): Cust_ConnectToPC   : IPT>true
D/        ( 5475): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5475): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5475): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5475): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5475): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
I/SmartNS_Utility( 5475): setISNotification
D/SmartNS_Utility( 5475): usb_cable_connect = 1
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
D/SmartNS_Utility( 5475): usb_denied = 0
I/SmartNS_PSService( 5475): usb notificaiton:true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartNS_Utility( 5475): usb_cable_connect = 1
D/SmartNS_Utility( 5475): usb_denied = 0
I/SmartNS_PSService( 5475): usb notificaiton:true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1217): reapply : com.android.settings 1 36
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_NSReceiver( 5475): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/MdScPhnSt( 6918): [4d3.2.]  listen tmrbb8
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,I/RemoteViews( 1217): reapply : com.android.settings 1 36
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false,
,D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA,
D/PMS     (  968): acquireWL(3e7fa6e4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 968 1000 null
D/GpsLocationProvider(  968): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  968): [NET] android_getaddrinfo_proxy-, NODATA
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/PMS     (  968): acquireWL(1a697b49): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
,D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/PMS     (  968): releaseWL(1a697b49): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/PMS     (  968): releaseWL(3e7fa6e4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  968): [NET] android_getaddrinfo_proxy-, NODATA
D/MdProvGlob( 6788): remove item 101 (p2d27in232) for 15:android.intent.action.ANY_DATA_STATE
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/MdScDataSum( 6918): [4d3.2.] summary 118:p2 ignore
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  968): [NET] android_getaddrinfo_proxy-, NODATA
D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/GpsLocationProvider(  968):  [handleDownloadXtraData]download failure, retry count: 1
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/Process (  968): killProcessQuiet, pid=6368
I/ActivityManager(  968): Killing 6368:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/dhcpcd  ( 6956): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6956): version 5.5.6 starting
E/dhcpcd  ( 6956): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6956): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6956): autoip env[11]:autoip=DISABLE
,I/ActivityManager(  968): Recipient 6368
,I/dhcpcd  ( 6956): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6956): wlan0: sending REQUEST (xid 0x78c87f59), next in 1.57 seconds
,I/dhcpcd  ( 6956): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6956): wlan0: leased 192.168.1.130 for 86400 seconds,
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/dhcpcd  ( 6956): autoip env[11]:autoip=DISABLE
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
,E/WifiStateMachine(  968):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0},
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  968): handleMessage: X
,I/dhcpcd  ( 6956): bind_interface: daemonise,
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=196613
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1338): Power_Mode_Type mode = 0
I/wpa_supplicant( 1338): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/PMS     (  968): releaseWL(16f0cf38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  968): setDhcpActive: false
E/WifiStateMachine(  968): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  968): WifiStateMachine DHCP successful
E/WifiStateMachine(  968): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  968): link address 192.168.1.130/24
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  968): gateway: /192.168.1.1
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
,I/wpa_supplicant( 1338): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1338): htc_wext_set_keepalive +
I/wpa_supplicant( 1338): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1338): getPrivFuncNum +	
I/wpa_supplicant( 1338): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1338): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1338): get_ip_address source addr = c0a80182
,I/wpa_supplicant( 1338): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1338): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131210
E/WifiStateMachine(  968): processMsg: ObtainingIpState
,E/WifiStateMachine(  968):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1338): environment dirty rate=40 [5][2][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
,E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
,D/wpa_supplicant( 1338): wlan0: Control interface command 'BLACKLIST clear'
,E/wpa_supplicant( 1338): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=53 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
,D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -56, 3
,E/WifiStateMachine(  968): NetworkAgent != null
,E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WIFI_ICON( 1217): updateWifiState: RSSI_CHANGED -1 -> 3
,D/ConnectivityService(  968): Adding iface wlan0 to network 101
E/WifiStateMachine(  968): transitionTo: destState=ConnectedState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,E/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
,E/WifiStateMachine(  968): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  968): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  968): WAN detection,
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/HtcWifiWanDetect(  968): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
,E/WifiStateMachine(  968): ConnectedState Enter  mScreenOn=false scanperiod=20000
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  968): handleMessage: X
,E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 26
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED connected,
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5475): >>>>>WISPrService start isConnected = true<<<<<,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131131,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): handleMessage: X
,E/ConnectivityService(  968): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  968): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/WISPrService( 5475): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  968): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  968): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  968): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/Nat464Xlat(  968): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Connected
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): currentScore = 0, newScore = 20
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):    accepting network in place of null
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/ConnectivityService(  968): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/CSLegacyTypeTracker(  968): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  968): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  968): acquireWL(337b916f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
,D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  968): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
D/DATA_ICON( 1217): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
,D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.,
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
V/NetworkPolicy(  968): updateIfacesLocked()
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524290
V/NetworkPolicy(  968): updateNotificationsLocked()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/SecurityController( 1217): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524290
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/SecurityController( 1217): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false,
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524290
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
I/SecurityController( 1217): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1217): dataConnected: false/false
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/DATA_ICON( 1217): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/DATA_ICON( 1217): dataConnected: false/false
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  968): releaseWL(337b916f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  968): updateNetworkEnabledLocked()
,V/NetworkPolicy(  968): updateNotificationsLocked()
,I/QuickSettingWifi( 1217): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1217): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/wpa_supplicant( 1338): EAPOL: startWhen --> 0
D/wpa_supplicant( 1338): EAPOL: disable timer tick
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: ConnectModeState
,E/WifiStateMachine(  968):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  968): identical MTU - not setting
D/Nat464Xlat(  968): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524295
,D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  968): handleMessage: X
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524295
,D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/PMS     (  968): releaseWL(24971f8f): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  968): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 6857): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6857): 
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  968): acquireWL(3cc6ee7c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE
I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: false
,D/GpsLocationProvider(  968): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/ConnectivityHelper( 1495): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  968): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6988 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  968): No APN found to select.
D/PMS     (  968): releaseWL(3cc6ee7c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  968): acquireWL(f627f5a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 968 1000 null
D/PMS     (  968): releaseWL(f627f5a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/MdScPhnSt( 6918): [b59.1.]  listen tmrbb8
,D/MdScDataSum( 6918): [b59.1.] summary 118:p1 ignore
,I/MusicStore( 6988): Database version: 120,
,D/VoldConnector(  968): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6988): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  968): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6988): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  968): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6988): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6988): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6988): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6988): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6988): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6988): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31d87073: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6988): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6988): GMSCore installation verified
,I/ConfigStore( 6988): Config Database version: 1
,I/jxcore-log( 6857): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 6857): 
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6988, uid=10159, userID:0
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,D/MediaRouterService(  968): Client com.google.android.music (pid 6988): Registered
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,I/jxcore-log( 6857): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 6857): 
,I/MediaRouter( 6988): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,I/jxcore-log( 6857): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6857): 
,V/MusicLeanback( 6988): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6988): type=WIFI subType= reason=null isConnected=true,
,D/ContactMessageStore( 1440): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1440): MSG_NOTIFY_CS_TO_SYNC <<,
,I/NetworkMonitor( 6988): type=WIFI subType= reason=null isConnected=true,
,D/AutoSetting( 1590): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6578): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6578): onReceive CONNECTIVITY_CHANGE networkType=1
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6988, uid=10159, userID:0
,D/AutoSetting( 1590): service - onCreate()
,I/GHttpClientFactory( 6988): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1590): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1590): service - onStartCommand() screen is off, don't request location
D/LocationManagerService(  968): request 19a15446 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  968): provider request: passive ProviderRequest[ON interval=0]
I/GoogleURLConnFactory( 6988): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4565): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4565): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7032 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6630): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 6630): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6630): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6630): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6630): [NET] android_getaddrinfo_proxy+
D/libc    ( 6630): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
,I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6630): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4565): [AccountUtils] Account not ready
W/Kids    ( 4565): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4565): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4565): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4565): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4565): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4565): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4565): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4565): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4565): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4565): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4565): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4565): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1217): reapply : com.google.android.gms 3 40
,I/Babel   ( 6630): connection state changed from UNKNOWN to CONNECTED,
,I/art     (  968): Explicit concurrent mark sweep GC freed 58968(3MB) AllocSpace objects, 4(420KB) LOS objects, 33% free, 17MB/25MB, paused 1.757ms total 151.540ms
,I/jxcore-log( 6857): Test app app.js loaded,
I/jxcore-log( 6857): 
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
,D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+,
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
I/chromium( 6857): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: true
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  968): acquireWL(c274e72): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  968): Find DNS Address www.htc.com/104.81.130.175
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  968): acquireWL(4cf52c3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 968 1000 null
I/NetworkMonitor( 6988): type=WIFI subType= reason=null isConnected=true
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
D/VoldConnector(  968): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,I/ConnectivityHelper( 1495): [onReceive] WIFI(1): CONNECTED
D/PMS     (  968): releaseWL(4cf52c3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
D/GpsLocationProvider(  968): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
W/ContextImpl( 7032): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7032): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7032):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7032):   adb logcat -s GAv4
,D/VoldConnector(  968): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 7032): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/GpsLocationProvider(  968): No APN found to select.
,D/PMS     (  968): releaseWL(c274e72): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6918): [eef.1.]  listen tmrbb8
,D/VoldConnector(  968): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 7032): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7032): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/VoldConnector(  968): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 7032): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/MdScDataSum( 6918): [eef.1.] summary 118:p1 ignore
,W/GAv4    ( 7032): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 7032): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 7032): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7032): [apache-http] Connection GC has been deprecated!,
,D/Process (  968): killProcessQuiet, pid=6534,
,I/ActivityManager(  968): Killing 6534:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/WebViewFactory( 7032): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/ActivityManager(  968): Recipient 6534,
,I/LibraryLoader( 7032): Time to load native libraries: 3 ms (timestamps 9822-9825),
I/LibraryLoader( 7032): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 7032): Binding Chromium to main looper Looper (main, tid 1) {1f36f4d0},
,I/LibraryLoader( 7032): Expected native library version number "",actual native library version number ""
,I/chromium( 7032): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7032): Initializing chromium process, singleProcess=true
,W/art     ( 7032): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7032): ApplicationContext is null in ApplicationStatus
,W/chromium( 7032): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7032): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7032): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7032): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7032): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7032): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7032): Local Branch: 
I/Adreno-EGL( 7032): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7032): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7032):                  d74aa161a12b9c6fc6332151
,D/PMS     (  968): acquireWL(3ef7852b): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024}
V/AlarmManager(  968): sending alarm PendingIntent{2438fd88: PendingIntentRecord{28b39321 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=149991, Int=0
,W/AudioManagerAndroid( 7032): Requires BLUETOOTH permission,
,I/NSApplication( 7032): Starting up...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6857): BLE advertisement is supported
I/jxcore-log( 6857): 
I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7096 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  968): killProcessQuiet, pid=6607
,I/ActivityManager(  968): Killing 6607:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  968): Recipient 6607
,E/WifiStateMachine(  968): handleMessage: E msg.what=131168,
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DriverStartedState
,E/WifiStateMachine(  968):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): handleMessage: X
,I/ActivityManager(  968): Killing 6098:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  968): killProcessQuiet, pid=6098
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  968): Recipient 6098
,V/MusicLeanback( 6988): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/AutoSetting( 1590): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6578): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6578): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1590): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1590): service - onStartCommand() screen is off, don't request location
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4565, uid=10024, userID:0
,D/ChimeraCfgMgr( 4565): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4565): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1954): Explicit concurrent mark sweep GC freed 16380(901KB) AllocSpace objects, 9(756KB) LOS objects, 49% free, 4MB/8MB, paused 1.306ms total 67.829ms
D/PMS     (  968): acquireWL(234bfacd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(3ef7852b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1954): [NET] android_getaddrinfo_proxy+
D/libc    ( 1954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1954): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4565): [AccountUtils] Account not ready
W/Kids    ( 4565): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4565): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4565): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4565): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4565): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4565): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4565): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4565): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4565): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4565): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4565): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/Kids    ( 4565): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1217): reapply : com.google.android.gms 2 40
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  968): acquireWL(16aa76c9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1954): Connected
,D/PMS     (  968): releaseWL(234bfacd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(16aa76c9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(3f3c01ce): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(286db8ef): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,I/GCM     ( 4565): Message from null null,
,E/GCM     ( 4565): Dropping message from null,
,D/PMS     (  968): releaseWL(286db8ef): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1954): Message class com.google.f.a.a.p,
,D/PMS     (  968): releaseWL(3f3c01ce): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(f5ab685): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6988 10159 null
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6988, uid=10159, userID:0,
,I/MusicLeanback( 6988): Conditions not met for autocaching. okToAttempt=false
,D/PMS     (  968): releaseWL(f5ab685): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6988): Stop autocaching.
,D/WearableService( 5826): callingUid 10024, callindPid: 5826
,E/GmsUtils( 6988): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 6988): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  968): acquireWL(345c202c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000},
V/AlarmManager(  968): sending alarm PendingIntent{7fc686f: PendingIntentRecord{324797c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=167597, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{2b0f4af5: PendingIntentRecord{2cd7c08a android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453125302097, Int=0
,D/PMS     (  968): acquireWL(94336fb): PARTIAL_WAKE_LOCK  *backup* 0x1 968 1000 null
,W/BackupManagerService(  968): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  968): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  968): releaseWL(94336fb): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
D/PMS     (  968): releaseWL(345c202c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1217): Weather sync is On
,W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/AutoSetting( 1590): service - handleMessage() stop self
,D/AutoSetting( 1590): service - handleMessage() quit looper
D/AutoSetting( 1590): service - onDestroy() END
,E/WifiStateMachine(  968): handleMessage: E msg.what=131165,
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
,E/WifiStateMachine(  968):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
,E/WifiStateMachine(  968):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): handleMessage: X,
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1440): switchBindHtcMsgCursor: null,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131326
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState what:131326 2 0
,E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  968): handleMessage: X
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1590): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@39e7daa6
I/ActivityManager(  968): Killing 6038:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=6038
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6038
,D/PMS     (  968): acquireWL(2d811318): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
V/AlarmManager(  968): sending alarm PendingIntent{1056a171: PendingIntentRecord{28795b56 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192083, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{300447d7: PendingIntentRecord{270048c4 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=212268, Int=0
,D/PMS     (  968): acquireWL(3ce2e3ad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2d811318): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  968): acquireWL(12c7d6e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(3ce2e3ad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  968): releaseWL(12c7d6e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(20bdec5c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(20bdec5c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(3a09db65): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(c29603a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(d6b7248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(3a09db65): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(193d4606): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(193d4606): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1954): Vacuum at: now=1453125344931 tag=VacuumService
,I/GoogleURLConnFactory( 1954): Using platform SSLCertificateSocketFactory,
,D/PMS     (  968): releaseWL(c29603a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(1910d4c7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(1910d4c7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): acquireWL(25e96af4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(25e96af4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1954): No account for auth token provided,
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1954): [NET] android_getaddrinfo_proxy+
D/libc    ( 1954): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1954): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1954): No account for auth token provided,
,W/Uploader( 1954): No account for auth token provided,
,W/Uploader( 1954):  no longer exists, so no auth token.,
,W/Uploader( 1954): No account for auth token provided,
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1954): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1954): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1954): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.b(SourceFile:477),
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1954): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/RemoteViews( 1217): reapply : com.google.android.gms 5 40
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/Uploader( 1954): Failed to get auth token: User intervention required. Notification has been pushed.,
,E/Uploader( 1954): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1954): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
,E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1954): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/RemoteViews( 1217): reapply : com.google.android.gms 4 40
,W/Uploader( 1954): No account for auth token provided,
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1954): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1954): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1954): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1954): ,	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235),
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1954): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1217): reapply : com.google.android.gms 3 40
,D/PMS     (  968): releaseWL(d6b7248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(26dec8bc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(26dec8bc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(2b6cf045): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2b6cf045): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1338): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 1338): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6857): TAP version 13
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # multiplex can send data
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 1 String should be length:200
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # basic
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 2 sane
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # another
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 3 sane
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 4 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 5 null
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 6 (unnamed assert)
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 7 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 8 should not throw
I/jxcore-log( 6857): 
I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 9 (unnamed assert)
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 10 (unnamed assert)
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 11 should not throw
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 12 should be equal
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 13 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 14 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # failed to get mobile documents path
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 15 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 16 should be equal
,I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 17 should be equal
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 18 should be equal
I/jxcore-log( 6857): 
I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #init should register the networkChanged event
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 19 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #startBroadcasting should throw on null device name
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
I/jxcore-log( 6857): 
,D/PMS     (  968): acquireWL(8f5839a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(8f5839a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1217): closing low battery warning: level=100
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3239): Disconnected process message: 10, size: 0
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  968): Checking...
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus,
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6857): ok 20 should throw
,I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
,I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #startBroadcasting should throw on empty string device name
,I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown
,I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 21 should throw,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
,I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #startBroadcasting should throw on non-number port
,I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 22 should throw
,I/jxcore-log( 6857): 
I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #startBroadcasting should throw on NaN port,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 23 should throw,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #startBroadcasting should throw on negative port,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 24 should throw,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #startBroadcasting should throw on too large port,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 25 should throw,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #startBroadcasting should call Mobile("StartBroadcasting") without an error,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 26 should be equal,
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 27 should be equal
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 28 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 29 should be equal,
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 30 should be equal
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 31 should be equal
I/jxcore-log( 6857): 
I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 32 should be equal,
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 33 should be equal,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 34 should be equal,
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 35 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #connect should call Mobile("Connect") with a port and without an error,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 36 should be equal,
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 37 should be equal
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 38 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 39 should be equal,
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 40 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # should call Mobile("Disconnect") without an error,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 41 should be equal
,I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 42 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # should call Mobile("Disconnect") and handle an error,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 43 should be equal,
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 44 should be equal
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125474551.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474551.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125474551.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12,
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125474551.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
,D/PMS     (  968): acquireWL(205e2fd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
V/AlarmManager(  968): sending alarm PendingIntent{7fc686f: PendingIntentRecord{324797c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=227598, Int=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
V/AlarmManager(  968): sending alarm PendingIntent{10ec6243: PendingIntentRecord{3d6870c0 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453125474612, Int=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=b75bd473-4b40-47bc-9c18-5f612db47a7e
,D/PMS     (  968): releaseWL(205e2fd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0xb75bd4734b4047bc9c185f612db47a7e]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
,D/WeatherUtility( 1217): Weather sync is On
,D/BtGatt.GattService( 3239): onClientRegistered() - UUID=b75bd473-4b40-47bc-9c18-5f612db47a7e, clientIf=5
,W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3239): message : 0
,D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
,I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
,D/PMS     (  968): acquireWL(2c52b1f9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3239 1002 null,
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
,I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1,
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
,D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12,
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=c703297f-cd0c-4870-bb23-2de31837d907
,I/bt-att  ( 3239): GATT_Register,
,D/bt-att  ( 3239): UUID=[0xc703297fcd0c4870bb232de31837d907]
,I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=c703297f-cd0c-4870-bb23-2de31837d907, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474551.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474551.6857","ra":"90:E7:C4:F6:69:77"}
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125474551.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
,I/jxcore-log( 6857): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
,D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ef3fef80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ef3fef80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState add service
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  968): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343535312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343535312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343535312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343535311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
D/WifiP2pService(  968): InactiveState{ when=-4ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3239): BTA_JvDeleteRecord
D/WifiP2pService(  968): P2pEnabledState{ when=-4ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343535311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343535311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/WifiP2pService(  968): discovery change broadcast true
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1338): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1338): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1338): WPS:  * Request Type
D/wpa_supplicant( 1338): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1338): WPS:  * UUID-E
D/wpa_supplicant( 1338): WPS:  * Primary Device Type
,D/wpa_supplicant( 1338): WPS:  * RF Bands (3)
D/wpa_supplicant( 1338): WPS:  * Association State
D/wpa_supplicant( 1338): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1338): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1338): WPS:  * Manufacturer
D/wpa_supplicant( 1338): WPS:  * Model Name
D/wpa_supplicant( 1338): WPS:  * Model Number
D/wpa_supplicant( 1338): WPS:  * Device Name
D/wpa_supplicant( 1338): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 1338): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1338): P2P: * P2P IE header
D/wpa_supplicant( 1338): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1338): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1338): p2p0: Add radio work 'p2p-scan'@0x5588046680
D/wpa_supplicant( 1338): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1338): p2p0: Starting radio work 'p2p-scan'@0x5588046680 after 0.000051 second wait
D/wpa_supplicant( 1338): p2p0: nl80211: scan request
D/wpa_supplicant( 1338): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1338): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 1338): P2P: Running p2p_scan
D/wpa_supplicant( 1338): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1338): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1338): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1338): p2p0: Own scan request started a scan in 0.000072 seconds
I/wpa_supplicant( 1338): p2p0: CTRL-EVENT-SCAN-STARTED 
D/BtGatt.AdvertiseManager( 3239): message : 1
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): stopScan() - queue size =1
,D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = 3c 0c 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 50 f4 cc d8 7d ac 5e e4 13 a8 ff b3 50 32 4d 15 
D/BtGatt.ScanManager( 3239): stop scan
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,I/bt-btm  ( 3239): btm_ble_stop_scan 
D/WifiP2pService(  968): P2pEnabledState clear service
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343535311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
D/WifiP2pService(  968): remove client information from framework
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343535311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343535311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
,D/WifiP2pService(  968): mFlushDisabled: false
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/WifiP2pService(  968): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Do not consider the scan results after stop_find
D/WifiP2pService(  968): discovery change broadcast false
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
D/WifiP2pService(  968): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P-FIND-STOPPED 
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/WifiP2pService(  968): P2pEnabledState clear service request
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
,D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
,I/jxcore-log( 6857): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125474743.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474743.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125474743.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125474743.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=996dea1b-b608-4871-b9fe-883490811c3c
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x996dea1bb6084871b9fe883490811c3c]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=996dea1b-b608-4871-b9fe-883490811c3c, clientIf=5
,D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3239): message : 0
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1,
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
,D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=1a2e0be0-e665-4d7c-b3b8-6224e8b71019
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x1a2e0be0e6654d7cb3b86224e8b71019]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=1a2e0be0-e665-4d7c-b3b8-6224e8b71019, clientIf=6
,D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474743.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474743.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125474743.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a76c84ba target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343734332e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a76c84ba target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343734332e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState add service
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343734332e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): add a new client
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343734331f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343734331f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343734331f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/WifiP2pService(  968): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
,D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: p2p_scan is already running
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1338): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6857): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): ,
D/wpa_supplicant( 1338): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=60 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
I/bt-btif ( 3239): BTA_JvDeleteRecord
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 3239): BTA_JvRfcommStopServer
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/bt-btm  ( 3239): BTM_FreeSCN 
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
,I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): stopScan() - queue size =1
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = 8d 57 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = b1 60 99 ed 50 07 e5 cf 27 f6 55 61 b9 b2 1d ab 
D/BtGatt.ScanManager( 3239): stop scan
,D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
D/WifiP2pService(  968): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
,D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343734331f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343734331f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343734331f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/WifiP2pService(  968): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): Stop discovery in Inactive state
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/WifiP2pService(  968): mFlushDisabled: false
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
,D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/WifiP2pService(  968): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): P2pEnabledState clear service request
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
I/jxcore-log( 6857): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
,E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P-FIND-STOPPED 
D/WifiP2pService(  968): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125474839.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474839.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125474839.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125474839.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=09255a50-c00b-4a4f-ade0-0272cd546371
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x09255a50c00b4a4fade00272cd546371]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=09255a50-c00b-4a4f-ade0-0272cd546371, clientIf=5
,D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
,I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
,I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): registerClient() - UUID=0883aed8-aa1d-43a1-9ca5-19b46ae0837b
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x0883aed8aa1d43a19ca519b46ae0837b]
,I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=0883aed8-aa1d-43a1-9ca5-19b46ae0837b, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474839.6857","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474839.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125474839.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2780c4ae target=com.android.internal.util.StateMachine$SmHandler }
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2780c4ae target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343833392e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState add service
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343833392e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
,D/WifiP2pService(  968): add a new client
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343833392e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343833391f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343833391f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343833391f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/jxcore-log( 6857): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0,
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): btm_ble_stop_scan ,
D/WifiP2pService(  968): discovery change broadcast true
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/wpa_supplicant( 1338): P2P: p2p_scan is already running
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
I/bt-btif ( 3239): BTA_JvDeleteRecord
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
I/wpa_supplicant( 1338): p2p0: P2P: Reject scan trigger since one is already pending
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
,I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/wpa_supplicant( 1338): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/bt-btm  ( 3239): BTM_FreeSCN 
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=62 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
,D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
,I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): stopScan() - queue size =1
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
,I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-att  ( 3239): GATT_Listen gatt_if=6
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
D/WifiP2pService(  968): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
D/WifiP2pService(  968): remove client information from framework
I/bt-btm  ( 3239): BTM_ReadConnectability
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/WifiP2pService(  968): Stop discovery in Inactive state
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/WifiP2pService(  968): mFlushDisabled: false
D/bt-btm  ( 3239): disc_mode 0000
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = 19 7a 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 23 ee dd 86 34 23 b5 a0 71 0b 92 65 c0 7e 51 90 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  968): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
D/WifiP2pService(  968): P2pEnabledState clear service request
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343833391f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343833391f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343833391f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/WifiP2pService(  968): discovery change broadcast false
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=63 dispatchEvent: P2P-FIND-STOPPED 
D/BtGatt.ScanManager( 3239): stop scan
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
D/wpa_supplicant( 1338): p,2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
I/bt-btm  ( 3239): btm_ble_stop_scan 
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
I/jxcore-log( 6857): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125474945.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474945.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125474945.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125474945.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=918a12bf-d677-4f7f-867c-9eddae8b39b9,
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x918a12bfd6774f7f867c9eddae8b39b9]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=918a12bf-d677-4f7f-867c-9eddae8b39b9, clientIf=5
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3239): message : 0
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
,I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
,D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
,I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=48a35fc3-0df4-4191-ab03-9f78ab13a512
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x48a35fc30df44191ab039f78ab13a512]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): HAL bt_gatt_callbacks->client->register
,I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=48a35fc3-0df4-4191-ab03-9f78ab13a512, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474945.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125474945.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125474945.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343934352e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6e580bb2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343934352e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6e580bb2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437343934352e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): P2pEnabledState add service
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343934351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  968): add a new client
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343934351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343934351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
,I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  968): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: p2p_scan is already running
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1338): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1338): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 6857): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
,I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
,D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
,D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): stopScan() - queue size =1
,D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
D/BtGatt.ScanManager( 3239): stop scan
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = ca e3 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 12 07 e6 f0 82 4c c4 ee 4e d7 a4 df 52 0b 42 37 
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
,D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiP2pService(  968): P2pEnabledState clear service
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343934351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343934351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437343934351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
D/WifiP2pService(  968): remove client information from framework
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  968): InactiveState{ when=-3ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): mFlushDisabled: false
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
,E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): InactiveState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/WifiP2pService(  968): P2pEnabledState{ when=-5ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): P2pEnabledState clear service request
D/wpa_supplicant( 1338): P2P: Stopping find
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/WifiP2pService(  968): discovery change broadcast false
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6857): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475041.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475041.6857","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3239): BTA_JvCreateRecordByUser,
,D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475041.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125475041.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=76ac095d-f9b2-4c6d-9f3a-3d3b24a31915
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x76ac095df9b24c6d9f3a3d3b24a31915]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
,D/BtGatt.GattService( 3239): onClientRegistered() - UUID=76ac095d-f9b2-4c6d-9f3a-3d3b24a31915, clientIf=5
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
,D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
,D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=6cd36bd3-415e-4d79-8c81-fc24316553a7
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x6cd36bd3415e4d798c81fc24316553a7]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): HAL bt_gatt_callbacks->_bda start_idx=0
I/bt-btif ( 3239): gatt_find_the_connected_bda found=0ster_client_cb
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=6cd36bd3-415e-4d79-8c81-fc24316553a7, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3239): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475041.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475041.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125475041.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e8e57d4a target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353034312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e8e57d4a target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353034312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState add service
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353034312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353034311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353034311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353034311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
,D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: p2p_scan is already running
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1338): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1338): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  968): discovery change broadcast true
I/jxcore-log( 6857): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
,I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
,I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): stopScan() - queue size =1
,D/BtGatt.ScanManager( 3239): stop scan
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
,D/bt-smp  ( 3239): smp_encrypt_data
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = 68 69 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = db e4 cc f8 a2 cb c7 98 28 91 35 81 a1 c6 3f 1c 
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/WifiP2pService(  968): P2pEnabledState clear service
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353034311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353034311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353034311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
D/WifiP2pService(  968): remove client information from framework
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): mFlushDisabled: false
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): P2pEnabledState clear service request
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=67 dispatchEvent: P2P-FIND-STOPPED 
D/WifiP2pService(  968): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): discovery change broadcast false
,I/jxcore-log( 6857): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475151.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475151.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
,I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475151.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125475151.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=f0021480-3874-4255-9a75-bb4427fbb9d1
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0xf0021480387442559a75bb4427fbb9d1]
,I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16,
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=f0021480-3874-4255-9a75-bb4427fbb9d1, clientIf=5
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
,D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
,D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
,D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=d3c4fc8b-fa4f-46fe-8561-b616ed9c1d49
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0xd3c4fc8bfa4f46fe8561b616ed9c1d49]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=d3c4fc8b-fa4f-46fe-8561-b616ed9c1d49, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475151.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475151.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125475151.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
,I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@526de946 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353135312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@526de946 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353135312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState add service
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353135312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): add a new client
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353135311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353135311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353135311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
,I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: p2p_scan is already running
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): discovery change broadcast true
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1338): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1338): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6857): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.AdvertiseManager( 3239): message : 1
,D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02,
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
,I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): stopScan() - queue size =1
,D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
D/BtGatt.ScanManager( 3239): stop scan
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
,W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = c4 27 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 96 57 46 1f 7f db c8 be 07 b4 7e b7 fd ad 6e d1 
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/bt-att  ( 3239): GATT_Listen gatt_if=6
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): BTM_ReadConnectability
D/WifiP2pService(  968): P2pEnabledState clear service
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353135311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353135311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353135311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/WifiP2pService(  968): remove client information from framework
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): Stop discovery in Inactive state
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/WifiP2pService(  968): mFlushDisabled: false
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6857): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
,D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
D/WifiP2pService(  968): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState clear service request
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=69 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
D/WifiP2pService(  968): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475252.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475252.6857","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475252.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125475252.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=4b0cf975-97ff-4ef7-84ac-f952c5f41c1a
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x4b0cf97597ff4ef784acf952c5f41c1a]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
,I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=4b0cf975-97ff-4ef7-84ac-f952c5f41c1a, clientIf=5
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
,D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
,D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12,
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): registerClient() - UUID=7628b9c1-2c34-4607-82ea-f0832222f50e
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x7628b9c12c34460782eaf0832222f50e]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6,
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): HAL bt_gatt_callbacks->client->regi found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->regi found_idx=16
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=7628b9c1-2c34-4607-82ea-f0832222f50e, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3239): handling starting scan
D/wpa_supplicant( 1338): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 1338): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1338): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1338): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1338): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1338): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1338): p2p0: Scan completed in 0.592246 seconds
D/wpa_supplicant( 1338): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1338): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1338): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1338): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1338): p2p0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 1338): p2p0: BSS: Add new id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 1338): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1338): P2P: Ignore scan results
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 1338): p2p0: Radio work 'p2p-scan'@0x5588046680 done in 0.593166 seconds
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48]
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475252.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475252.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125475252.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@35e3acc2 target=com.android.internal.util.StateMachine$SmHandler }
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@35e3acc2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353235322e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState add service
,D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353235322e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): add a new client
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353235322e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353235321f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353235321f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353235321f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
,I/jxcore-log( 6857): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  968): discovery change broadcast true
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
,D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1338): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1338): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1338): WPS:  * Request Type
D/wpa_supplicant( 1338): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1338): WPS:  * UUID-E
D/wpa_supplicant( 1338): WPS:  * Primary Device Type
D/wpa_supplicant( 1338): WPS:  * RF Bands (3)
D/wpa_supplicant( 1338): WPS:  * Association State
,D/wpa_supplicant( 1338): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1338): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1338): WPS:  * Manufacturer
D/wpa_supplicant( 1338): WPS:  * Model Name
D/wpa_supplicant( 1338): WPS:  * Model Number
D/wpa_supplicant( 1338): WPS:  * Device Name
D/wpa_supplicant( 1338): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1338): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1338): P2P: * P2P IE header
I/io.jxcore.node.ConnectionHelper( 6857): stop
D/wpa_supplicant( 1338): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1338): P2P: * Listen Channel: Regulatory Class 81 Channel 11
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
D/wpa_supplicant( 1338): p2p0: Add radio work 'p2p-scan'@0x5588046680
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
,D/wpa_supplicant( 1338): p2p0: First radio work item in the queue - schedule start immediately
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/wpa_supplicant( 1338): p2p0: Starting radio work 'p2p-scan'@0x5588046680 after 0.000144 second wait
D/wpa_supplicant( 1338): p2p0: nl80211: scan request
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/wpa_supplicant( 1338): nl80211: P2P probe - mask SuppRates
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
D/wpa_supplicant( 1338): Scan requested (ret=0) - scan timeout 30 seconds
,D/wpa_supplicant( 1338): P2P: Running p2p_scan
D/wpa_supplicant( 1338): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1338): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1338): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1338): p2p0: Own scan request started a scan in 0.000130 seconds
I/wpa_supplicant( 1338): p2p0: CTRL-EVENT-SCAN-STARTED 
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=72 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/BtGatt.AdvertiseManager( 3239): message : 1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
,I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): stopScan() - queue size =1
,D/BtGatt.ScanManager( 3239): stop scan
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
,I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = fa 78 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 96 d7 38 09 56 41 c9 f1 b6 41 db 10 45 6d a4 7a 
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
D/WifiP2pService(  968): P2pEnabledState clear service
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353235321f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353235321f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353235321f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/WifiP2pService(  968): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
,I/jxcore-log( 6857): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
,D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler },
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
,D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): mFlushDisabled: false
D/wpa_supplicant( 1338): P2P: Do not consider the scan results after stop_find
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): InactiveState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Stopping find
D/WifiP2pService(  968): P2pEnabledState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): P2pEnabledState clear service request
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475361.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475361.6857","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475361.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125475361.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=d3aea1ac-a808-4f1c-baf3-ebd857aaa3c8
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0xd3aea1aca8084f1cbaf3ebd857aaa3c8]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=d3aea1ac-a808-4f1c-baf3-ebd857aaa3c8, clientIf=5,
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
,D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
,I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01,
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
,I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): registerClient() - UUID=46d50d29-34b5-4971-9ed0-48ab57eb5bf1
,I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x46d50d2934b549719ed048ab57eb5bf1]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=46d50d29-34b5-4971-9ed0-48ab57eb5bf1, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475361.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475361.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125475361.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@16bfcf80 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353336312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@16bfcf80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState add service
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353336312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): add a new client
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353336312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353336311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353336311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353336311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
,D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
,I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: p2p_scan is already running
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1338): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService(  968): discovery change broadcast true
D/wpa_supplicant( 1338): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=74 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/jxcore-log( 6857): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
I/io.jxcore.node.ConnectionHelper( 6857): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
I/bt-btif ( 3239): BTA_JvDeleteRecord
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 3239): BTA_JvRfcommStopServer
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61,
D/bt-btm  ( 3239): BTM_FreeSCN 
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
,I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
,D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
,I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): stopScan() - queue size =1
,D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
D/BtGatt.ScanManager( 3239): stop scan
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-smp  ( 3239): smp_encrypt_data
D/WifiP2pService(  968): P2pEnabledState clear service
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = 55 48 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/WifiP2pService(  968): remove client information from framework
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 13 ee d4 1f 7c 70 74 5e 32 cc cc 13 8d d1 94 9e 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/WifiP2pService(  968): Stop discovery in Inactive state
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353336311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/WifiP2pService(  968): mFlushDisabled: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353336311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353336311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Stopping find
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
D/WifiP2pService(  968): P2pEnabledState clear service request
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1338): p2p0: Cont,rol interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6857): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
D/WifiP2pService(  968): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P-FIND-STOPPED 
D/WifiP2pService(  968): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475461.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,I/art     (  968): Explicit concurrent mark sweep GC freed 34313(1808KB) AllocSpace objects, 4(336KB) LOS objects, 33% free, 16MB/25MB, paused 2.043ms total 197.656ms
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475461.6857","ra":"90:E7:C4:F6:69:77"}
D/PMS     (  968): releaseWL(2c52b1f9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3239): BTA_JvCreateRecordByUser,
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
,I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475461.6857
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125475461.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=4b3203e8-5df8-4b28-9235-52b97f2ace4a
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x4b3203e85df84b28923552b97f2ace4a]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=4b3203e8-5df8-4b28-9235-52b97f2ace4a, clientIf=5
,D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
,I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
D/PMS     (  968): acquireWL(b5d424f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3239 1002 null
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01,
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
,D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=bef790c0-af38-4616-9b9f-1f7ce56ab002
I/bt-att  ( 3239): GATT_Register
,D/bt-att  ( 3239): UUID=[0xbef790c0af3846169b9f1f7ce56ab002]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=bef790c0-af38-4616-9b9f-1f7ce56ab002, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
D/wpa_supplicant( 1338): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 1338): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1338): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1338): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1338): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1338): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1338): p2p0: Scan completed in 0.417769 seconds
D/wpa_supplicant( 1338): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 1338): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1338): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1338): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1338): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1338): P2P: Ignore scan results
D/wpa_supplicant( 1338): p2p0: Radio work 'p2p-scan'@0x5588046680 done in 0.418735 seconds
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475461.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475461.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125475461.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@718949be target=com.android.internal.util.StateMachine$SmHandler }
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@718949be target=com.android.internal.util.StateMachine$SmHandler }
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/WifiP2pService(  968): P2pEnabledState add service
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353436312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): add a new client
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353436312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353436312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353436311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353436311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353436311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
,I/jxcore-log( 6857): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1338): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1338): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1338): WPS:  * Request Type
D/wpa_supplicant( 1338): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1338): WPS:  * UUID-E
D/wpa_supplicant( 1338): WPS:  * Primary Device Type
D/wpa_supplicant( 1338): WPS:  * RF Bands (3)
D/wpa_supplicant( 1338): WPS:  * Association State
D/wpa_supplicant( 1338): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1338): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1338): WPS:  * Manufacturer
D/wpa_supplicant( 1338): WPS:  * Model Name
D/wpa_supplicant( 1338): WPS:  * Model Number
D/wpa_supplicant( 1338): WPS:  * Device Name
D/wpa_supplicant( 1338): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1338): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1338): P2P: * P2P IE header
D/wpa_supplicant( 1338): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1338): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/WifiP2pService(  968): discovery change broadcast true
D/wpa_supplicant( 1338): p2p0: Add radio work 'p2p-scan'@0x5588046680
D/wpa_supplicant( 1338): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1338): p2p0: Starting radio work 'p2p-scan'@0x5588046680 after 0.000091 second wait
D/wpa_supplicant( 1338): p2p0: nl80211: scan request
D/wpa_supplicant( 1338): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1338): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1338): P2P: Running p2p_scan
D/wpa_supplicant( 1338): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1338): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1338): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1338): p2p0: Own scan request started a scan in 0.000100 seconds
I/wpa_supplicant( 1338): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=76 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
,D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): stopScan() - queue size =1
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
,I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-btm  ( 3239): disc_mode 0000
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/WifiP2pService(  968): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
D/BtGatt.ScanManager( 3239): stop scan
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/WifiP2pService(  968): remove client information from framework
,I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353436311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353436311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353436311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = f3 0e 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 58 f7 c5 ef c8 ab ac 0c bb 09 b8 db 22 9c 9b f9 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
,D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1338): P2P: Do not consider the scan results after stop_find
D/WifiP2pService(  968): mFlushDisabled: false
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=77 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState clear service request
,I/jxcore-log( 6857): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475791.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475791.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125475791.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125475791.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=3fa2f49c-5fe7-4a85-96d5-d2f3587c9de5
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x3fa2f49c5fe74a8596d5d2f3587c9de5]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
,D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=3fa2f49c-5fe7-4a85-96d5-d2f3587c9de5, clientIf=5
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
,D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
,D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
,D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=dbc3f0d1-98e1-4e32-bcf4-4ff8596c5f51
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0xdbc3f0d198e14e32bcf44ff8596c5f51]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
,I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=dbc3f0d1-98e1-4e32-bcf4-4ff8596c5f51, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
D/BtGatt.ScanManager( 3239): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475791.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125475791.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125475791.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ae228db2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353739312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ae228db2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353739312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState add service
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437353739312e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): add a new client
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353739311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353739311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353739311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler },
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: p2p_scan is already running
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1338): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1338): P2P: Failed to start p2p_scan - another p2p_scan was already running
I/jxcore-log( 6857): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
D/WifiP2pService(  968): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=78 dispatchEvent: P2P: Reject scan trigger since one is already pending,
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02,
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): stopScan() - queue size =1
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = d9 d3 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = c9 a3 d8 ec 46 19 ec d9 ce b2 30 21 94 08 34 36 
,D/BtGatt.ScanManager( 3239): stop scan
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
,I/bt-btm  ( 3239): btm_ble_stop_scan 
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  968): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
D/WifiP2pService(  968): remove client information from framework
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353739311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353739311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437353739311f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...,
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
D/WifiP2pService(  968): mFlushDisabled: false
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=79 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/WifiP2pService(  968): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/WifiP2pService(  968): P2pEnabledState clear service request,
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Stopping find
D/WifiP2pService(  968): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): discovery change broadcast false
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
,I/jxcore-log( 6857): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
,I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
,I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
,D/wpa_supplicant( 1338): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1338): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1338): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1338): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1338): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1338): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1338): p2p0: Scan completed in 0.461097 seconds
D/wpa_supplicant( 1338): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1338): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1338): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1338): p2p0: BSS: Start scan result update 3
D/wpa_supplicant( 1338): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1338): P2P: Ignore scan results
D/wpa_supplicant( 1338): p2p0: Radio work 'p2p-scan'@0x5588046680 done in 0.461936 seconds
,I/jxcore-log( 6857): # ThaliEmitter calls startBroadcasting twice with error,
I/jxcore-log( 6857): 
,D/PMS     (  968): releaseWL(b5d424f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125477814.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125477814.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125477814.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125477814.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=8604df5c-bf8a-434c-a1a9-c2f34216a7aa
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x8604df5cbf8a434ca1a9c2f34216a7aa]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=8604df5c-bf8a-434c-a1a9-c2f34216a7aa, clientIf=5
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
,D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
,D/PMS     (  968): acquireWL(372e86f8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3239 1002 null
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
,D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=748c7996-1ca7-4750-9e55-06d0b75d5c38
,I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x748c79961ca747509e5506d0b75d5c38]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=748c7996-1ca7-4750-9e55-06d0b75d5c38, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3239): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125477814.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125477814.6857","ra":"90:E7:C4:F6:69:77"}
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c9a11b36 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125477814.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c9a11b36 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/WifiP2pService(  968): P2pEnabledState add service
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
D/WifiP2pService(  968): add a new client
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437373831342e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437373831342e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437373831342e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437373831341f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437373831341f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437373831341f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
,D/WifiP2pService(  968): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/WifiP2pService(  968): discovery change broadcast true
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1338): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1338): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1338): WPS:  * Request Type
D/wpa_supplicant( 1338): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1338): WPS:  * UUID-E
D/wpa_supplicant( 1338): WPS:  * Primary Device Type
D/wpa_supplicant( 1338): WPS:  * RF Bands (3)
,D/wpa_supplicant( 1338): WPS:  * Association State
D/wpa_supplicant( 1338): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1338): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1338): WPS:  * Manufacturer
D/wpa_supplicant( 1338): WPS:  * Model Name
D/wpa_supplicant( 1338): WPS:  * Model Number
D/wpa_supplicant( 1338): WPS:  * Device Name
D/wpa_supplicant( 1338): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1338): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1338): P2P: * P2P IE header
D/wpa_supplicant( 1338): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1338): P2P: * Listen Channel: Regulatory Class 81 Channel 11
,D/wpa_supplicant( 1338): p2p0: Add radio work 'p2p-scan'@0x5588046680
D/wpa_supplicant( 1338): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1338): p2p0: Starting radio work 'p2p-scan'@0x5588046680 after 0.000091 second wait
D/wpa_supplicant( 1338): p2p0: nl80211: scan request
D/wpa_supplicant( 1338): nl80211: P2P probe - mask SuppRates
I/jxcore-log( 6857): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
D/wpa_supplicant( 1338): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1338): P2P: Running p2p_scan
D/wpa_supplicant( 1338): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1338): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1338): p2p0: Event SCAN_STARTED (49) received
,D/wpa_supplicant( 1338): p2p0: Own scan request started a scan in 0.000118 seconds
I/wpa_supplicant( 1338): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=80 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 6857): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 6857): 
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
I/bt-btif ( 3239): BTA_JvDeleteRecord
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
I/bt-btif ( 3239): BTA_JvRfcommStopServer
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/bt-btm  ( 3239): BTM_FreeSCN 
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
,I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
,D/bt-btm  ( 3239): disc_mode 0000
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): stopScan() - queue size =1
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/BtGatt.ScanManager( 3239): stop scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
D/WifiP2pService(  968): P2pEnabledState clear service
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
I/bt-att  ( 3239): GATT_Listen gatt_if=6
D/WifiP2pService(  968): remove client information from framework
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = fb fd 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 47 25 36 cc 0c 8d c7 f0 a8 f0 4e ab 2f 3a e5 46 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  968): Stop discovery in Inactive state
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
D/WifiP2pService(  968): mFlushDisabled: false
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437373831341f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437373831341f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a,66363a36393a3737222c22706e223a22313435333132353437373831341f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Stopping find
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
D/WifiP2pService(  968): P2pEnabledState clear service request
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): discovery change broadcast false
D/wpa_supplicant( 1338): P2P: Do not consider the scan results after stop_find
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=81 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6857): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
,D/wpa_supplicant( 1338): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 1338): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1338): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1338): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
,D/wpa_supplicant( 1338): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1338): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1338): p2p0: Scan completed in 0.415779 seconds
D/wpa_supplicant( 1338): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1338): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1338): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1338): p2p0: BSS: Start scan result update 4
D/wpa_supplicant( 1338): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1338): P2P: Ignore scan results,
D/wpa_supplicant( 1338): p2p0: Radio work 'p2p-scan'@0x5588046680 done in 0.416681 seconds
,I/jxcore-log( 6857): # ThaliEmitter throws on connection to bad peer,
I/jxcore-log( 6857): 
,D/PMS     (  968): releaseWL(372e86f8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125479786.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125479786.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3239): BTA_JvCreateRecordByUser
,D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
,I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125479786.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125479786.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=1b2c1ed8-a16f-4b3a-85f6-e85c3a55e607
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x1b2c1ed8a16f4b3a85f6e85c3a55e607]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
,D/BtGatt.GattService( 3239): onClientRegistered() - UUID=1b2c1ed8-a16f-4b3a-85f6-e85c3a55e607, clientIf=5,
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
,D/PMS     (  968): acquireWL(368a142f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3239 1002 null
D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
,I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
,D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
,I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=b45233b5-ae73-4b7e-95e3-541b906b7fe1
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0xb45233b5ae734b7e95e3541b906b7fe1]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
,D/BtGatt.GattService( 3239): onClientRegistered() - UUID=b45233b5-ae73-4b7e-95e3-541b906b7fe1, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3239): handling starting scan
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125479786.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125479786.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125479786.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@84109522 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@84109522 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437393738362e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState add service
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437393738362e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
,D/WifiP2pService(  968): add a new client
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353437393738362e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437393738361f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  968): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437393738361f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437393738361f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239):  BTM_BleSetScanParams
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
,I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1338): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1338): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1338): WPS:  * Request Type
D/wpa_supplicant( 1338): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1338): WPS:  * UUID-E
D/wpa_supplicant( 1338): WPS:  * Primary Device Type
D/wpa_supplicant( 1338): WPS:  * RF Bands (3)
,D/wpa_supplicant( 1338): WPS:  * Association State
D/wpa_supplicant( 1338): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1338): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1338): WPS:  * Manufacturer
D/wpa_supplicant( 1338): WPS:  * Model Name
D/wpa_supplicant( 1338): WPS:  * Model Number
D/wpa_supplicant( 1338): WPS:  * Device Name
D/wpa_supplicant( 1338): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1338): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1338): P2P: * P2P IE header
D/wpa_supplicant( 1338): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1338): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1338): p2p0: Add radio work 'p2p-scan'@0x5588046680
D/wpa_supplicant( 1338): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1338): p2p0: Starting radio work 'p2p-scan'@0x5588046680 after 0.000083 second wait
D/wpa_supplicant( 1338): p2p0: nl80211: scan request
D/wpa_supplicant( 1338): nl80211: P2P probe - mask SuppRates
,D/wpa_supplicant( 1338): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1338): P2P: Running p2p_scan
D/wpa_supplicant( 1338): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1338): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1338): p2p0: Event SCAN_STARTED (49) received
I/jxcore-log( 6857): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
D/wpa_supplicant( 1338): p2p0: Own scan request started a scan in 0.000099 seconds
I/wpa_supplicant( 1338): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=82 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/io.jxcore.node.ConnectionHelper( 6857): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 6857): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 6857): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 6857): ok 69 Should not connect to a bad peer
I/jxcore-log( 6857): 
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
,I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): stopScan() - queue size =1
D/BtGatt.ScanManager( 3239): stop scan
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/WifiP2pService(  968): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  968): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiP2pService(  968): Stop discovery in Inactive state
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
,D/WifiP2pService(  968): mFlushDisabled: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437393738361f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437393738361f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353437393738361f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
D/WifiP2pService(  968): P2pEnabledState clear service request
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
D/WifiP2pService(  968): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/bt-smp  ( 3239): smp_encrypt_data
D/WifiP2pService(  968): discovery change broadcast false
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = ad ed 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 8e f7 41 d3 3a 45 0e 78 66 0a 1b 8f 81 f9 79 21 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
,I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Do not consider the scan results after stop_find
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=83 dispatchEvent: P2P-FIND-STOPPED 
I/jxcore-log( 6857): ok 70 Should be able to call stopBroadcasting without error
,I/jxcore-log( 6857): 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
,D/wpa_supplicant( 1338): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1338): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1338): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1338): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1338): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1338): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1338): p2p0: Scan completed in 0.382842 seconds
D/wpa_supplicant( 1338): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1338): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1338): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
,D/wpa_supplicant( 1338): p2p0: BSS: Start scan result update 5
D/wpa_supplicant( 1338): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1338): P2P: Ignore scan results
D/wpa_supplicant( 1338): p2p0: Radio work 'p2p-scan'@0x5588046680 done in 0.383785 seconds
,I/jxcore-log( 6857): # ThaliEmitter throws on disconnect to bad peer,
I/jxcore-log( 6857): 
,D/PMS     (  968): releaseWL(368a142f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125481425.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): initialize: My bluetooth address is 90:E7:C4:F6:69:77
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125481425.6857","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6857): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3239): BTA_JvCreateRecordByUser
D/bt-btm  ( 3239): BTM_AllocateSCN
D/bt-sdp  ( 3239): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3239): BTA_JvRfcommStartServer
I/bt-btm  ( 3239): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3239):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): start: OK
I/io.jxcore.node.ConnectionHelper( 6857): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1453125481425.6857
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Waiting for incoming connections...
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): createAdvertiseData: From: 1453125481425.6857 b6a44ad1-d319-4b3a-815d-8b805a47fb51 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6857): 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -112, -25, -60, -10, 105, 119]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6857): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.GattService( 3239): registerClient() - UUID=919e7b5d-0fb2-4e00-8ef9-8fb435628878
I/bt-att  ( 3239): GATT_Register
D/bt-att  ( 3239): UUID=[0x919e7b5d0fb24e008ef98fb435628878]
I/bt-att  ( 3239): allocated gatt_if=5
I/bt-att  ( 3239): GATT_StartIf gatt_if=5
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=919e7b5d-0fb2-4e00-8ef9-8fb435628878, clientIf=5
D/BluetoothLeAdvertiser( 6857): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3239): message : 0
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
I/bt-btif ( 3239): BTA_BleEnableAdvInstance
I/bt-btm  ( 3239): BTM_BleEnableAdvInstance called
I/bt-btm  ( 3239):  btm_ble_multi_adv_set_params,Min 400, Max 410,adv_type 0
I/bt-btm  ( 3239): set_params:Chnl Map 7,adv_fltr policy 0,ID:1, TX Power1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 24.
,D/PMS     (  968): acquireWL(53d8972): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3239 1002 null
,D/bt-btm  ( 3239): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 3239): btm_ble_enable_multi_adv being called with inst_id:1
,I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 1, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
D/bt-btm  ( 3239): op_code = 01 inst_id = 1 cb_evt = 00
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_SET_PARAM status = 0
,D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 01
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_enable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceEnabled() - clientIf=5, status=0
I/bt-btif ( 3239): BTA_BleCfgAdvInstData
,D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239): BTM_BleCfgAdvInstData called with inst_id:1
I/bt-btm  ( 3239):  btm_ble_build_adv_data
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 34.
D/bt-btm  ( 3239): op_code = 02 inst_id = 1 cb_evt = 04
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_WRITE_ADV_DATA status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_data_cb
D/BtGatt.GattService( 3239): onAdvertiseDataSet() - clientIf=5, status=0
,D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): registerClient() - UUID=1a2b864a-a318-435b-acc9-edb9d1554ad9
,I/bt-att  ( 3239): GATT_Register
,D/bt-att  ( 3239): UUID=[0x1a2b864aa318435bacc9edb9d1554ad9]
I/bt-att  ( 3239): allocated gatt_if=6
I/bt-att  ( 3239): GATT_StartIf gatt_if=6
D/bt-att  ( 3239): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3239): gatt_find_the_connected_bda found=0 found_idx=16
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->register_client_cb
D/BtGatt.GattService( 3239): onClientRegistered() - UUID=1a2b864a-a318-435b-acc9-edb9d1554ad9, clientIf=6
D/BluetoothLeScanner( 6857): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3239): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3239): handling starting scan
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6857): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1453125481425.6857","ra":"90:E7:C4:F6:69:77"}
D/BluetoothAdapter( 3239): 863588103: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): start: {"pi":"90:E7:C4:F6:69:77","pn":"1453125481425.6857","ra":"90:E7:C4:F6:69:77"}
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=1
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1453125481425.6857","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 ,
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a8d54804 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3239):  BTM_BleSetScanParams
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a8d54804 target=com.android.internal.util.StateMachine$SmHandler }
,I/bt-btif ( 3239): BTA_DmBleObserve:start = 1 
D/WifiP2pService(  968): P2pEnabledState add service
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
D/WifiP2pService(  968): add a new client
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353438313432352e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353438313432352e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435333132353438313432352e36383537222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353438313432351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353438313432351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353438313432351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6857): start: OK
I/jxcore-log( 6857): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 6857): 
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1338): [p2p command] (P2P_FIND 120)
D/WifiP2pService(  968): discovery change broadcast true
D/wpa_supplicant( 1338): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1338): P2P: Starting find (type=0)
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1338): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1338): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1338): WPS:  * Request Type
D/wpa_supplicant( 1338): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1338): WPS:  * UUID-E
D/wpa_supplicant( 1338): WPS:  * Primary Device Type
D/wpa_supplicant( 1338): WPS:  * RF Bands (3)
D/wpa_supplicant( 1338): WPS:  * Association State
D/wpa_supplicant( 1338): WPS:  * Configuration Error (0)
,D/wpa_supplicant( 1338): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1338): WPS:  * Manufacturer
D/io.jxcore.node.ConnectionHelper( 6857): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
D/wpa_supplicant( 1338): WPS:  * Model Name
D/wpa_supplicant( 1338): WPS:  * Model Number
D/wpa_supplicant( 1338): WPS:  * Device Name
D/wpa_supplicant( 1338): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1338): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1338): P2P: * P2P IE header
D/wpa_supplicant( 1338): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1338): P2P: * Listen Channel: Regulatory Class 81 Channel 11
,E/io.jxcore.node.ConnectionHelper( 6857): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/wpa_supplicant( 1338): p2p0: Add radio work 'p2p-scan'@0x5588046680
D/wpa_supplicant( 1338): p2p0: First radio work item in the queue - schedule start immediately
D/io.jxcore.node.ConnectionHelper( 6857): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6857): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
D/wpa_supplicant( 1338): p2p0: Starting radio work 'p2p-scan'@0x5588046680 after 0.000129 second wait
,D/wpa_supplicant( 1338): p2p0: nl80211: scan request
D/wpa_supplicant( 1338): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1338): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1338): P2P: Running p2p_scan
D/wpa_supplicant( 1338): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1338): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1338): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1338): p2p0: Own scan request started a scan in 0.000162 seconds
I/wpa_supplicant( 1338): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=84 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6857): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log( 6857): 
I/io.jxcore.node.ConnectionHelper( 6857): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6857): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6857): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6857): onServerStopped
I/bt-btif ( 3239): BTA_JvDeleteRecord
,I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3239): BTM_SEC_CLR[19]: id 61
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
D/BtGatt.AdvertiseManager( 3239): message : 1
D/BtGatt.AdvertiseManager( 3239): stop advertise for client 5
I/bt-btif ( 3239): BTA_BleDisableAdvInstance: 1
I/bt-btm  ( 3239): BTM_BleDisableAdvInstance with inst_id:1
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
I/bt-btm  ( 3239):  btm_ble_enable_multi_adv: enb 0, Inst ID 1
I/bt-btm  ( 3239): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD54, ParamLen: 3.
I/bt-btm  ( 3239): btm_gen_resolvable_private_addr
D/bt-btm  ( 3239): op_code = 05 inst_id = 1 cb_evt = 02
D/bt-btm  ( 3239): BTM_BLE_MULTI_ADV_ENB status = 0
I/bt-btif ( 3239): HAL bt_gatt_callbacks->client->multi_adv_disable_cb
D/BtGatt.GattService( 3239): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3239): Client app is not null!
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: false
,I/bt-att  ( 3239): GATT_Deregister gatt_if=5
I/bt-att  ( 3239): GATT_Listen gatt_if=5
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
D/BluetoothAdapter( 6857): 438139176: getState(). Returning 12
,D/BtGatt.GattService( 3239): stopScan() - queue size =1
,D/BtGatt.ScanManager( 3239): stop scan
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue=0
I/bt-btif ( 3239): BTA_DmBleObserve:start = 0 
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3239): configureRegularScanParams() - queue emtpy, scan stopped
,I/bt-btm  ( 3239): BTM_BleObserve : scan_type:0
I/bt-btm  ( 3239): btm_ble_stop_scan 
I/bt-btm  ( 3239): btm_update_scanner_filter_policy
D/BtGatt.GattService( 3239): unregisterClient() - clientIf=6
D/bt-btm  ( 3239): btm_ble_rand_enc_complete
I/bt-btm  ( 3239): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 3239): smp_encrypt_data
W/bt-smp  ( 3239): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3239): Plain text(LSB ~ MSB) = 91 35 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3239): Encrypted text(LSB ~ MSB) = 00 29 85 46 cb 2d c6 9b 86 ec d5 bf c3 d5 1c 5d 
I/bt-att  ( 3239): GATT_Deregister gatt_if=6
,I/bt-att  ( 3239): GATT_Listen gatt_if=6
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6857): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6857): release: No more listeners, de-initializing...
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6857): release: No more listeners, de-initializing...
D/WifiP2pService(  968): P2pEnabledState clear service
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353438313432351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353438313432351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1338): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435333132353438313432351f36383537222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/WifiP2pService(  968): remove client information from framework
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1338): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1338): P2P: Stopping find
D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1338): P2P: Clear timeout (state=SEARCH)
D/WifiP2pService(  968): mFlushDisabled: false
I/wpa_supplicant( 1338): P2P-FIND-STOPPED 
D/wpa_supplicant( 1338): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Do not consider the scan results after stop_find
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=85 dispatchEvent: P2P-FIND-STOPPED 
D/WifiP2pService(  968): InactiveState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/WifiP2pService(  968): P2pEnabledState{ when=-4,ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): p2p0: Control interface command 'P2P_FLUSH'
D/WifiP2pService(  968): P2pEnabledState clear service request
I/wpa_supplicant( 1338): [p2p command] (P2P_FLUSH)
D/WifiP2pService(  968): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Stopping find
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): discovery change broadcast false
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1338): P2P: Stopping find
D/wpa_supplicant( 1338): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1338): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1338): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6857): setState: NOT_STARTED
I/jxcore-log( 6857): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 6857): 
I/jxcore-log( 6857): # setup
I/jxcore-log( 6857): 
,I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6857): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6857): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6857): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6857): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6857): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6857): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6857): onDiscoveryManagerStateChanged: NOT_STARTED
,D/wpa_supplicant( 1338): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1338): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1338): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1338): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1338): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1338): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1338): p2p0: Scan completed in 0.510729 seconds
D/wpa_supplicant( 1338): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1338): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1338): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1338): p2p0: BSS: Start scan result update 6
D/wpa_supplicant( 1338): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1338): P2P: Ignore scan results
D/wpa_supplicant( 1338): p2p0: Radio work 'p2p-scan'@0x5588046680 done in 0.512074 seconds
,I/jxcore-log( 6857): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available,
I/jxcore-log( 6857): 
,D/PMS     (  968): releaseWL(53d8972): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 74 should be equal,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 75 should not be equal,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # setup,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # verify that Thali-specific messages are filtered correctly,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): # teardown,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 76 irrelevant messages should be ignored
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): ok 77 relevant messages should not be ignored
I/jxcore-log( 6857): 
I/jxcore-log( 6857): ok 78 messages from this device should be ignored
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): Tests Complete,
I/jxcore-log( 6857): 
,I/jxcore-log( 6857): Total: 0,	,Passed: 0	Failed: 0
I/jxcore-log( 6857): 
I/jxcore-log( 6857): Toggling radios to false
I/jxcore-log( 6857): 
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  968): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@19bc9b0a mBinding = false
W/Settings:Agent(  968): MONITOR_LOG
W/Settings:Agent(  968): name: bluetooth_on
W/Settings:Agent(  968): value: 0
,W/Settings:Agent(  968): >> traceCallingStack()
W/Settings:Agent(  968): Process.myPid(): 968
W/Settings:Agent(  968): Process.myTid(): 1832
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
W/System.err(  968): java.lang.Throwable: stack dump
,W/System.err(  968): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 12(ms)
,D/BluetoothManagerService(  968): Message: MESSAGE_DISABLE
,D/WifiManager( 6857): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/BluetoothManagerService(  968): Sending off request.
D/WifiService(  968): setWifiEnabled: false pid=6857, uid=10366
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  968): isSprintWifiRestricted(): false
,W/Settings:Agent(  968): MONITOR_LOG
W/Settings:Agent(  968): name: wifi_on
I/WifiService(  968): isMdmWifiRestricted(): false
W/Settings:Agent(  968): value: 0
W/Settings:Agent(  968): >> traceCallingStack()
W/Settings:Agent(  968): Process.myPid(): 968
W/Settings:Agent(  968): Process.myTid(): 2064
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
W/System.err(  968): java.lang.Throwable: stack dump
,W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
D/PMS     (  968): acquireWL(32ae671f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3239 1002 null
W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
,W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  968): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  968): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 1(ms)
D/BluetoothAdapterState( 3239): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3239): Setting state to 13
I/BluetoothAdapterState( 3239): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  968): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3239): onBluetoothDisable()
I/bt-btm  ( 3239): BTM_SetDiscoverability
I/bt-btm  ( 3239): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3239): disc_mode 0000
,I/bt-btm  ( 3239): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3239): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/BluetoothAdapterState( 3239): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  968): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  968): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  968): Bluetooth State Change Intent: 12 -> 13
I/bt-btm  ( 3239): BTM_SetConnectability
I/bt-btif ( 3239): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3239): disc_mode 0000
I/bt-btm  ( 3239): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/IntentController( 1217): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothAdapterProperties( 3239): Scan Mode:21
D/BluetoothAdapterState( 3239): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/WifiController(  968): handleMessage: E msg.what=155656
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
I/bt-btif ( 3239): BTA_JvDeleteRecord
D/WifiController(  968): transitionTo: destState=ApStaDisabledState
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/WifiController(  968): handleMessage: new destination call exit/enter
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/WifiController(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  968): invokeExitMethods: DeviceActiveState
I/bt-btif ( 3239): BTA_JvDeleteRecord
D/WifiController(  968): invokeExitMethods: StaEnabledState
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
I/bt-btif ( 3239): BTA_JvDeleteRecord
D/WifiController(  968): moveTempStackToStateStack: i=0,j=1
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
D/WifiController(  968): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  968): invokeEnterMethods: ApStaDisabledState
I/jxcore-log( 6857): Radios toggled
I/jxcore-log( 6857): 
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/bt-btif ( 3239): BTA_JvRfcommStopServer
,D/bt-btm  ( 3239): BTM_FreeSCN 
I/bt-btif ( 3239): BTA_JvDeleteRecord
I/bt-btif ( 3239): BTA_JvRfcommStopServer
D/bt-btm  ( 3239): BTM_FreeSCN 
E/bt-btif ( 3239): cmd socket is not created
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:14
I/bt-btm  ( 3239): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3239): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:12
I/jxcore-log( 6857): ****TEST TOOK:  ms ****
I/jxcore-log( 6857): 
I/bt-btm  ( 3239): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3239): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3239): BTM_SEC_CLR[17]: id 59
I/jxcore-log( 6857): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6857): 
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:9
D/WifiController(  968): handleMessage: X
I/bt-btm  ( 3239): BTM_SEC_CLR[18]: id 60
E/WifiStateMachine(  968): handleMessage: E msg.what=131084
E/WifiStateMachine(  968): processMsg: ConnectedState
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:8
I/chromium( 6857): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
E/WifiStateMachine(  968):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
I/chromium( 6857): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
E/WifiStateMachine(  968):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/NGFService( 3843): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
E/WifiStateMachine(  968):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
I/bt-btm  ( 3239): Write Extended Inquiry Response to controller
I/bt-btm  ( 3239): Write Extended Inquiry Response to controller
I/bt-btm  ( 3239): Write Extended Inquiry Response to controller
I/bt-btm  ( 3239): Write Extended Inquiry Response to controller
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3239): BTM_SetDiscoverability
I/bt-btm  ( 3239): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3239): disc_mode 0000
I/bt-btm  ( 3239): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3239): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
,I/bt-btm  ( 3239): BTM_SetConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3239): disc_mode 0000
D/bt-btm  ( 3239): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3239): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3239): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
E/WifiStateMachine(  968):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  968): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
I/bt-btm  ( 3239): BTM_IsInquiryActive
I/bt-btm  ( 3239): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3239): btm_ble_clear_white_list
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  968): invokeExitMethods: ConnectedState
E/WifiStateMachine(  968): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  968): release()
E/WifiStateMachine(  968): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  968): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  968): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/BtOppRfcommListener( 3239): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
W/bt-btif ( 3239): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
V/BluetoothSapService( 3239): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1338): Power_Mode_Type mode = 0
I/wpa_supplicant( 1338): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  968): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDataStallTracker(  968): setDhcpActive: false
V/NativeCrypto( 1954): Read error: ssl=0x55877aae40: I/O error during system call, Connection timed out
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  968): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-btif ( 3239): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3239): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3239): BTM_FreeSCN 
I/bt-btm  ( 3239): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3239): BTM_FreeSCN 
I/bt-btm  ( 3239): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3239): AVRC_Close handle:0
D/bt-btif ( 3239): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3239): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3239): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3239): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3239): GATT_Deregister gatt_if=3
I/bt-att  ( 3239): GATT_Listen gatt_if=3
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3239): disc_mode 0000
I/bt-att  ( 3239): GATT_Deregister gatt_if=4
I/bt-att  ( 3239): GATT_Listen gatt_if=4
I/bt-btm  ( 3239): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3239): BTM_ReadConnectability
,I/bt-btm  ( 3239): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3239): disc_mode 0000
E/bt-btif ( 3239): bta_gattc_deregister Deregister Failedm unknown client cif
,D/bt-btif ( 3239): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
,D/PMS     (  968): acquireWL(18a78a6c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info<unknown ssid>
I/jxcore-log( 6857): Toggling radios to false
I/jxcore-log( 6857): 
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): NetworkAgent != null
,E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/bt-btm  ( 3239): btm_ble_clear_white_list_complete
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 27
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NativeCrypto( 1954): SSL shutdown failed: ssl=0x55877aae40: I/O error during system call, Broken pipe
,D/ConnectivityService(  968): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10024
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  968): setWifiEnabled: false pid=6857, uid=10366
E/WifiStateMachine(  968): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/WifiService(  968): isSprintWifiRestricted(): false
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/WifiService(  968): isMdmWifiRestricted(): false
,W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
I/QuickSettingBluetooth( 1217): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/BluetoothManagerService(  968): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@19bc9b0a mBinding = false
W/Settings:Agent(  968): MONITOR_LOG
W/Settings:Agent(  968): name: bluetooth_on
W/Settings:Agent(  968): value: 0
W/Settings:Agent(  968): >> traceCallingStack()
D/PMS     (  968): releaseWL(18a78a6c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
W/Settings:Agent(  968): Process.myPid(): 968
W/Settings:Agent(  968): Process.myTid(): 1160
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/System.err(  968): java.lang.Throwable: stack dump
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 3(ms)
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/BluetoothManagerService(  968): Message: MESSAGE_DISABLE
D/BluetoothManagerService(  968): Sending off request.
E/WifiStateMachine(  968): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  968): invokeExitMethods: DriverStartedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/WifiManager( 6857): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): noteBatchedScanstop()
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
W/Settings:Agent(  968): MONITOR_LOG
W/Settings:Agent(  968): name: wifi_on
W/Settings:Agent(  968): value: 0
W/Settings:Agent(  968): >> traceCallingStack()
W/Settings:Agent(  968): Process.myPid(): 968
W/Settings:Agent(  968): Process.myTid(): 2063
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
W/System.err(  968): java.lang.Throwable: stack dump
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.,java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  968): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  968): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 1(ms)
D/WifiController(  968): handleMessage: E msg.what=155656
D/WifiController(  968): processMsg: ApStaDisabledState
D/WifiController(  968): handleMessage: X
D/BluetoothAdapterState( 3239): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3239): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
I/jxcore-log( 6857): Radios toggled
I/jxcore-log( 6857): 
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  968): stopDataStallAlarm 
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 28
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 5
V/BluetoothPbapReceiver( 3239): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3239): ***********state = 13
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 29
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): [1,453,125,486,408 ms] noteScanEnd no scan source
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=2
,E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  968): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: WaitForP2pDisableState
I/BtOppRfcommListener( 3239): stopping Accept Thread
I/BtOppRfcommListener( 3239): BluetoothSocket listen thread finished
D/WifiScanningService(  968): SCAN_AVAILABLE : 1
E/WifiStateMachine(  968):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/RttService(  968): SCAN_AVAILABLE : 1
,D/WifiScanningService(  968): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
D/RttService(  968): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  968):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
,E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
D/WifiNetworkAgent(  968): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  968):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  968): handleMessage: X
,D/WifiP2pService(  968): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=-9ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  968): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@10f54a1f
D/WifiP2pService(  968): P2pDisablingState
D/WifiP2pService(  968): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): p2p socket connection lost
D/WifiP2pService(  968): P2pDisabledState
E/WifiStateMachine(  968): handleMessage: E msg.what=131205
E/WifiStateMachine(  968): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  968):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  968): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  968): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  968): invokeExitMethods: SupplicantStartedState
D/WifiP2pService(  968): P2pDisabledState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=1
D/WifiP2pService(  968): DefaultState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiDisplayController(  968): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
E/WifiStateMachine(  968): invokeEnterMethods: SupplicantStoppingState
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WISPrService( 5475): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
,V/AudioService(  968): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  968):     Client/Owner: Client
V/AudioService(  968):     GroupId: 
V/AudioService(  968):     Passphrase: 
V/AudioService(  968):     SessionId: 0
V/AudioService(  968):     IP Address: }
D/HtcEffectManagerBase(  968): onEventChanged id=5 status=false
D/HtcEffectManager(  968): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  968): convertEffect before=902
D/HtcEffectManager(  968): convertEffect after=902
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1338): Power_Mode_Type mode = 0
I/wpa_supplicant( 1338): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WifiP2pService(  968): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  968): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  968): setDhcpActive: false
,V/BluetoothPbapService( 3239): Pbap Service closeService in
,D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
V/BluetoothPbapService( 3239): successfully stopped pbap service
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/BluetoothPbapService( 3239): Pbap Service closeService out
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,V/BluetoothPbapService( 3239): Pbap Service onDestroy
,D/ConnectivityService(  968): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  968): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  968): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  968): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkManagementService(  968): Removing idletimer
E/WifiStateMachine(  968): stopping supplicant
D/PMS     (  968): acquireWL(2a30d4ca): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 968 1000 null
W/WifiHW  (  968): QCOM Debug wifi_send_command "TERMINATE"
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 30
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Disconnected - quitting
D/wpa_supplicant( 1338): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 1338): wlan0: Removing interface wlan0
D/usbnet  (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/wpa_supplicant( 1338): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1338): TDLS: Tear down peers
D/wpa_supplicant( 1338): wpa_driver_nl80211_disconnect(reason_code=3)
D/ConnectivityManager.CallbackHandler( 1217): CM callback handler got msg 524292
I/SecurityController( 1217): onLost 101
E/WifiStateMachine(  968): setWifiState: disabling
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
,E/WifiStateMachine(  968):  SupplicantStoppingState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): handleMessage: X
D/WIFI    (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/IntentController( 1217): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/CSLegacyTypeTracker(  968): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=false
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  968): acquireWL(35dc563b): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5475 1000 null
E/ConnectivityService(  968): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
V/BluetoothPbapService( 3239): Pbap Service closeService in
E/ConnectivityService(  968): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/BluetoothPbapService( 3239): Pbap Service closeService out
D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/PMS     (  968): acquireWL(3db8e158): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
,D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1217): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1217): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
,D/DATA_ICON( 1217): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateIfacesLocked()
,V/NetworkPolicy(  968): updateNotificationsLocked()
W/ContextImpl( 5475): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  968): releaseWL(3db8e158): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DATA_ICON( 1217): dataConnected: false/false
,D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
,V/NetworkPolicy(  968): updateNotificationsLocked()
,D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  968): releaseWL(35dc563b): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  968): acquireWL(25ef7396): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5475 1000 null
,I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1338): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1338): wlan0: Deauthentication notification
D/wpa_supplicant( 1338): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1338): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1338): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1338): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1338): enter disconnect check
I/wpa_supplicant( 1338): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=86 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  968): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1338): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1338): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 1338): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1338): wlan0: Disconnect event - remove keys
E/WifiMonitor(  968): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/WifiStateMachine(  968): handleMessage: E msg.what=147460
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5588043f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1338):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  968): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  968): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  968): TetherInterfaceSM: wlan0: enter UnavailableState
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=0
E/WifiStateMachine(  968):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=354063
D/wpa_supplicant( 1338): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1338): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1338): nl80211: Skip set_supp_port(unauthorized) while not associated
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1338): EAPOL: SUPP_BE entering state INITIALIZE
E/WifiStateMachine(  968): processMsg: DefaultState
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1338): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1338): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=0
E/WifiStateMachine(  968):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=354063
E/WifiStateMachine(  968): handleMessage: X
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=87 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
E/WifiStateMachine(  968):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 87 0 rt=354065  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 87 0 rt=354065  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,W/System.err(  968): java.lang.Throwable: stack dump
,W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
I/ActivityManager(  968): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=7179 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/Tethering(  968): sendTetherStateChangedBroadcast 0, 0, 0
,D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
D/PMS     (  968): acquireWL(27108ed): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f86bb04:true
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
E/WifiStateMachine(  968):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
,E/WifiStateMachine(  968):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
,I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1217): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
,I/ActivityManager(  968): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=7199 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/PMS     (  968): releaseWL(27108ed): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  968): updateNetworkEnabledLocked(),
,D/BluetoothAdapter( 5475): 100937090: getState(). Returning 13
V/NetworkPolicy(  968): updateNotificationsLocked()
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,D/BluetoothInputDevice( 5475): BluetoothInputDevice()
D/BluetoothManagerService(  968): registerStateChangeCallback+
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/BluetoothManagerService(  968): Registered receivers: 9
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota,
,D/BluetoothPan( 5475): BluetoothPan()
D/BluetoothManagerService(  968): registerStateChangeCallback+
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  968): Registered receivers: 10
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/BluetoothMap( 5475): Create BluetoothMap proxy object
D/BluetoothManagerService(  968): registerStateChangeCallback+
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  968): Registered receivers: 11
,E/BluetoothMap( 5475): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  968): registerStateChangeCallback+
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/BluetoothSap( 5475): BluetoothSap() call bindService,
W/ContextImpl( 5475): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  968): Registered receivers: 12
D/bt-btm  ( 3239): BTM_BleGetVendorCapabilities
,W/bt-btif ( 3239): ag scb idx 1 not allocated
W/bt-btif ( 3239): ag scb idx 2 not allocated
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
E/bt-btif ( 3239): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3239): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3239): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3239): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3239): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3239): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3239): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3239): L2CAP - PSM: 0x0017 not found for deregistration
,E/bt-btif ( 3239): bta_gattc_deregister Deregister Failedm unknown client cif
E/WifiStateMachine(  968): handleMessage: E msg.what=196614
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
E/WifiStateMachine(  968):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_ON_QUIT 0 0
E/WifiStateMachine(  968): handleMessage: X
D/BluetoothPbap( 5475): BluetoothPbap()
D/BluetoothManagerService(  968): registerStateChangeCallback+
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  968): Registered receivers: 13
E/bt_userial_mct( 3239): pthread_join() FAILED result:3
D/LocalBluetoothProfileManager( 5475): LocalBluetoothProfileManager construction complete
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/HtcWiFiWidget_WiFiWidgetProvider( 7179): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 7179): updateWidget(context) for widget: 
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/HtcBtWidget_BTWidgetProvider( 7199): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 7199): updateWidget(context) for widget: 
,D/DockEventReceiver( 5475): finishStartingService: stopping service
,D/BluetoothInputDevice( 5475): Proxy object connected
,D/HidProfile( 5475): Bluetooth service connected
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/BluetoothAdapter( 5475): 100937090: getState(). Returning 13
,D/BluetoothPan( 5475): BluetoothPAN Proxy object connected,
D/PanProfile( 5475): Bluetooth service connected
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/SapServerProfile( 5475): Bluetooth service connected
D/TetherSettings( 5475): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/BluetoothFtpService( 3239): ACTION_STATE_CHANGED: state: 13mHasStarted: true
D/        ( 5475): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5475): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 5475): Cust_ConnectToPC   : spcsc>false
D/        ( 5475): Cust_ConnectToPC   : IPT>true
D/        ( 5475): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5475): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/BluetoothFtpService:RfcommSocketAcceptThread( 3239): Shutdown,
E/SmartNS_Utility( 5475): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5475): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5475): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothMasReceiver( 3239): Bluetooth STATE CHANGED to 13
,W/ContextImpl( 5475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
V/BluetoothSapReceiver( 3239): SapReceiver onReceive 
I/SmartNS_Utility( 5475): setISNotification
V/BluetoothSapReceiver( 3239): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3239):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3239): startService = false
,D/SmartNS_Utility( 5475): usb_cable_connect = 1
D/SmartNS_Utility( 5475): usb_denied = 0
I/SmartNS_PSService( 5475): usb notificaiton:true
,E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/AuthorizationBluetoothService( 1954): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/SmartNS_Utility( 5475): usb_cable_connect = 1
,D/SmartNS_Utility( 5475): usb_denied = 0
,I/SmartNS_PSService( 5475): usb notificaiton:true
,E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/MdScPhnSt( 6918): [f5.1.]  listen tmrbb8
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
I/RemoteViews( 1217): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5475): Tethered state change:false isNSOpening:false
E/wpa_supplicant( 1338): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/PMS     (  968): releaseWL(25ef7396): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/wpa_supplicant( 1338): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1338): wlan0: Cancelling scan request
D/wpa_supplicant( 1338): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1338): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=88 dispatchEvent: BLACKLIST CLEAR 
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=89 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=90 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/wpa_supplicant( 1338): Remove interface wlan0 from radio phy0
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,I/RemoteViews( 1217): reapply : com.android.settings 1 36
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,E/cutils-trace( 7177): Error opening trace file: Permission denied (13),
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/PMS     (  968): releaseWL(32ae671f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6788): remove item 101 (p2d20in146) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6918): [f5.1.] summary 118:p2 ignore
D/wpa_supplicant( 1338): nl80211: Remove monitor interface: refcount=0
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6788): remove item 101 (p2in7) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6788): remove item 101 (p2d2in17) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false,
,D/MdProvGlob( 6788): remove item 101 (p2in11) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6788): remove item 101 (p2in11) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false,
D/CustomizationManager( 7177): ====startRecUseTime====,
D/htc.customization.log.level( 7177):  is 
W/CustomizationLogLevel( 7177): Level value is invalid, use default level 2
,D/MdProvGlob( 6788): remove item 101 (p2in10) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6725): updateSvcAllowedInSettings:false,
,D/wpa_supplicant( 1338): nl80211: Set mode ifindex 29 iftype 2 (STATION)
I/ActivityManager(  968): Killing 6660:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/wpa_supplicant( 1338): nl80211: Unsubscribe mgmt frames handle 0x888888dd008cd989 (mode change)
I/wpa_supplicant( 1338): htc_wext_command_deinit +
I/wpa_supplicant( 1338): htc_wext_command_deinit -
I/wpa_supplicant( 1338): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1338): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1338): p2p0: Removing interface p2p0
D/wpa_supplicant( 1338): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1338): TDLS: Tear down peers
D/wpa_supplicant( 1338): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1338): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=0
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Process (  968): killProcessQuiet, pid=6660
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=91 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor(  968): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  968): handleMessage: E msg.what=147458
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
E/WifiStateMachine(  968):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 91 0
E/WifiStateMachine(  968): Supplicant connection lost
,D/CustomizationManager( 7177):  Read ACC file spent 0.035 (s),
,D/CIDMapFileReader( 7177): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7177): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7177): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7177): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7177): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 7177): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7177): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 7177): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 7177): Parsing tag category name = system
I/CustomizationCIDLoader( 7177): Parsing tag category name = application
,I/CustomizationCIDLoader( 7177): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 7177): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7177): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7177): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7177): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7177): add string-array item, value = 42507,
I/CustomizationCIDLoader( 7177): add string-array item, value = 21902
I/CustomizationCIDLoader( 7177): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7177): add string-array item, value = 23420
I/CustomizationCIDLoader( 7177): add string-array item, value = 22299
I/CustomizationCIDLoader( 7177): add string-array item, value = 24002
I/CustomizationCIDLoader( 7177): add string-array item, value = 23210
I/CustomizationCIDLoader( 7177): add string-array item, value = 23205
I/CustomizationCIDLoader( 7177): add string-array item, value = 23806
I/CustomizationCIDLoader( 7177): add string-array item, value = 23430
I/CustomizationCIDLoader( 7177): add string-array item, value = 23408
I/CustomizationCIDLoader( 7177): add string-array item, value = 27205
I/CustomizationCIDLoader( 7177): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7177): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7177):  Read CID file spent 0.069 (s)
D/CustomizationManager( 7177):  All configurations done spent 0.069 (s)
,I/bt-btif ( 3239): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 3239): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3239): mProfilesStarted : true supportedProfileServices.length : 6
,D/PackageManager(  968): deletePackageAsUser: pkg=com.test.thalitest, pid=7177, uid=2000 userid=0
,W/PackageSettings(  968): Skipping PackageSetting{37ad6f17 com.example.hello/10374} due to missing metadata,
,I/ActivityManager(  968): Recipient 6660
,I/ActivityManager(  968): Killing 6755:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
D/Process (  968): killProcessQuiet, pid=6755
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  968): Recipient 6755
D/WifiService(  968): Client connection lost with reason: 4,
,I/ActivityManager(  968): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
D/Process (  968): killProcessQuiet, pid=6857
I/ActivityManager(  968): Killing 6857:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,I/ActivityManager(  968): Recipient 6857
I/WindowState(  968): WIN DEATH: Window{1a9204d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  968): Client connection lost with reason: 4
,E/InputEventReceiver( 1381): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{378e9684 uid 10366 pid 6857} (c)'
,I/wpa_ctrl(  968): [wpa_ctrl_close] ctrl=0x5587724810,
I/wpa_ctrl(  968): [wpa_ctrl_close] ctrl=0x55877249d0
,I/ActivityManager(  968):   Force finishing activity ActivityRecord{155f358d u0 com.test.thalitest/.MainActivity t8},
,D/HeadsetService( 3239): Received stop request...Stopping profile...
I/ActivityManager(  968): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  968):   Force finishing activity ActivityRecord{155f358d u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  968): Duplicate finish request for ActivityRecord{155f358d u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  968): Spurious death for ProcessRecord{2aade0ff 6857:com.test.thalitest/u0a366}, curProc for 6857: null
,D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/AccTypeManager( 1691): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
D/HeadsetStateMachine( 3239): Exit Disconnected: -1
,E/WifiStateMachine(  968): setWifiState: disabled
W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead
D/WifiStateMachine(  968): Enter handleNetworkDisconnect
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
,D/PMS     (  968): acquireWL(de4c515): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1848): Ignoring removeGeofence because network location is disabled.
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/A2dpService( 3239): Received stop request...Stopping profile...
D/WifiStateMachine(  968): Exit handleNetworkDisconnect
D/A2dpStateMachine( 3239): Exit Disconnected: -1
E/WifiStateMachine(  968): [MLHD] Error! unhandled message 6 { when=-657ms what=147458 arg1=91 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): transitionTo: destState=InitialState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  968): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  968): invokeEnterMethods: InitialState
D/BluetoothHeadset( 1217): Proxy object disconnected
D/BluetoothAdapterState( 3239): Stopping profile services that were post enabled
I/InputMethodManagerService(  968): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/QuickSettingMiniLite( 1217): btListener.disconnect:HEADSET
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
W/Settings( 6630): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/IntentController( 1217): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothHeadset( 3843): Proxy object disconnected
D/PMS     (  968): releaseWL(de4c515): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1217): updateWifiState: WIFI_STATE_CHANGED disabled
D/NGFService( 3843): BluetoothHeadset onServiceDisconnected: main
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/Settings( 1848): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/HidService( 3239): Received stop request...Stopping profile...
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothA2dp( 3843): Proxy object disconnected
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
,D/NGFService( 3843): BluetoothA2dp onServiceDisconnected: main
D/PMS     (  968): acquireWL(35bfebb8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 968 1000 null
,D/AccTypeManager( 1691): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/BluetoothInputDevice( 5475): Proxy object disconnected
D/HidProfile( 5475): Bluetooth service disconnected
,D/HealthService( 3239): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
,D/WISPrService( 5475): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5475): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/art     ( 1495): Explicit concurrent mark sweep GC freed 5853(310KB) AllocSpace objects, 3(64KB) LOS objects, 34% free, 29MB/45MB, paused 2.311ms total 90.244ms
,W/BluetoothHeadsetServiceJni( 3239): Cleaning up Bluetooth Handsfree Interface...
,I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/BluetoothHeadsetServiceJni( 3239): Cleaning up Bluetooth Handsfree callback object
I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PanService( 3239): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
,D/BtGatt.DebugUtils( 3239): handleDebugAction() action=null
D/BluetoothPan( 5475): BluetoothPAN Proxy object disconnected
D/PanProfile( 5475): Bluetooth service disconnected
D/BtGatt.GattService( 3239): Received stop request...Stopping profile...
D/BtGatt.GattService( 3239): stop()
D/BtGatt.AdvertiseManager( 3239): advertise clients cleared
D/VoicemailCleanupService( 1706): Cleaning up data for package: com.test.thalitest
I/Launcher( 1495): Deferring update until onResume
D/Launcher( 1495): waitUntilResume // bindAppsRemoved
,D/BluetoothAdapterService( 3239): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa4f2c5
,W/BluetoothHidServiceJni( 3239): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 3239): Cleaning up Bluetooth GID callback object
W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/BluetoothHealthServiceJni( 3239): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3239): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3239): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3239): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterState( 3239): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3239): Setting state to 10
I/BluetoothAdapterState( 3239): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  968): +onBluetoothStateChange prev=13 new=10
I/BluetoothAdapterState( 3239): Entering OffState
,D/BluetoothManagerService(  968): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  968): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  968): Broadcasting onBluetoothStateChange(false) to 13 receivers.
I/QuickSettingWifi( 1217): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
D/BluetoothMap( 5475): onBluetoothStateChange: up=false
,I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:0
D/PhoneApp( 1440): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/BluetoothHeadset( 1440): Proxy object disconnected
D/BluetoothHeadset( 1440): Proxy object disconnected
D/BluetoothPhoneService( 1440): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 1440): Proxy object disconnected
E/BluetoothMap( 5475): 
E/BluetoothMap( 5475): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@3a048de8
E/BluetoothMap( 5475): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5475): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 5475): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5475): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
,E/BluetoothMap( 5475): ,	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5475): 	at android.os.Binder.execTransact(Binder.java:454)
D/Prism.PackageStateRece_( 1495): action: android.intent.action.PACKAGE_REMOVED
D/BluetoothHeadset( 1217): onBluetoothStateChange: up=false
D/BluetoothHeadset(  968): onBluetoothStateChange: up=false
I/[PluginManager]RegisterService( 1590): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/AccTypeManager( 1691): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/[PluginManager]RegisterService( 1590): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  968): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7247 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/BluetoothPan( 5475): onBluetoothStateChange on: false
,D/BluetoothA2dp( 3843): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 5475): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1440): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3843): onBluetoothStateChange: up=false
E/ExternalAccountType( 1691): Unsupported attribute readOnly
,D/BluetoothA2dp(  968): onBluetoothStateChange: up=false
D/BluetoothPbap( 5475): onBluetoothStateChange: up=false
,D/BluetoothSap( 5475): onBluetoothStateChange on: false
V/BluetoothSapService( 3239): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@2f0d1c91
D/BluetoothHeadset( 1440): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1440): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  968): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  968): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter(  968): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@19bc9b0a
D/BluetoothAdapter(  968): onBluetoothServiceDown: done
,D/BluetoothAdapter( 5475): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@9d4c01
D/BluetoothAdapter( 5475): onBluetoothServiceDown: done
D/BluetoothAdapter( 2377): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@bc5b45b
D/BluetoothAdapter( 2377): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1848): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@109864f2
D/BluetoothAdapter( 1848): onBluetoothServiceDown: done
D/BluetoothAdapter( 1217): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@ebc756f
D/BluetoothAdapter( 1217): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1462): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@26032c79
,D/BluetoothAdapter( 1462): onBluetoothServiceDown: done
D/BluetoothAdapter( 3843): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@12490696
D/BluetoothAdapter( 3843): onBluetoothServiceDown: done
D/BluetoothAdapter( 1440): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@cc5349c
D/BluetoothAdapter( 1440): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3239): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@3666f641
,D/BluetoothAdapter( 3239): onBluetoothServiceDown: done
D/BluetoothManagerService(  968): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@19bc9b0a mBinding = false
,D/BluetoothManagerService(  968): Sending unbind request.
,D/BluetoothManagerService(  968): Bluetooth State Change Intent: 13 -> 10
,W/BluetoothHeadset( 1217): Proxy not attached to service
I/QuickSettingMiniLite( 1217): updateLiteState:no connect device!
,I/bt-btif ( 3239): HAL bt_hal_cbacks->thread_evt_cb
,D/NGFService( 3843): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/IntentController( 1217): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3843): Bluetooth Adapter: OFF
I/art     ( 3239): System.exit called, status: 0
D/LocalBluetoothProfileManager( 5475): setBluetoothStateOff
,W/BluetoothEventManager( 5475): unregister mProfileBroadcastReceiver fail
,D/TetherPref( 5475): persistRestoreBluetoothState false
,I/art     (  968): Explicit concurrent mark sweep GC freed 42122(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 10.351ms total 229.572ms
,I/art     (  968): WaitForGcToComplete blocked for 199.163ms for cause Explicit,
,I/ActivityManager(  968): Recipient 3239
,D/BluetoothAdapter( 1217): 669524799: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  968): Process com.android.bluetooth (pid 3239) has died
,I/QuickSettingBluetooth( 1217): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
W/ActivityManager(  968): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
W/ActivityManager(  968): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
I/BroadcastQueue(  968): Schedule to resend BroadcastRecord{14552030 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=968 callingUid=1000} for ResolveInfo{2d2d84a9 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,I/ActivityManager(  968): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7272 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,W/ContextImpl( 7247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,D/StatusBarManagerService(  968): setSystemUiVisibility(0x700),
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key,
D/StatusBarManagerService(  968): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
,D/FindExtension( 1495): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/ThreadedRenderer( 1495): Defer allocateBuffers to drawing time,
,I/ActivityManager(  968): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7293 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/InputMethodManagerService(  968): Got RemoteException sending setActive(false) notification to pid 6857 uid 10366
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
,D/Process (  968): killProcessQuiet, pid=6812
I/ActivityManager(  968): Killing 6812:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  968): Unable to load service info ResolveInfo{197a5106 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  968): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  968): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  968): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  968): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/JobSchedulerService(  968): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  968): Explicit concurrent mark sweep GC freed 8408(477KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.672ms total 209.464ms,
,W/asset   (  968): Copying FileAsset 0x5587cf2670 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.,
,I/ActivityManager(  968): Recipient 6812
,E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 31
I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
,W/ResourcesManager( 7272): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/TaskPersister(  968): removeObsoleteFile: deleting file=8_task.xml
D/NfcHandover( 1462): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,D/AdapterServiceConfig( 7272): Adding HeadsetService,
D/AdapterServiceConfig( 7272): Adding A2dpService
,D/AdapterServiceConfig( 7272): Adding HidService,
D/AdapterServiceConfig( 7272): Adding HealthService
D/AdapterServiceConfig( 7272): Adding PanService
,D/AdapterServiceConfig( 7272): Adding GattService
V/BluetoothPbapReceiver( 7272): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 7272): ***********state = 10
,E/BluetoothMasService( 7272): BluetoothMasObexConnectionManager: mIsEmailEnabled: true,
,D/PMS     (  968): acquireWL(16b0fa08): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5475 1000 null
W/ContextImpl( 5475): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/PMS     (  968): releaseWL(16b0fa08): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7293, uid=10072, userID:0
D/PMS     (  968): acquireWL(21eb73c6): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5475 1000 null
D/HtcBtWidget_BTWidgetProvider( 7199): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 7199): updateWidget(context) for widget: 
,D/BluetoothMasService( 7272): Add permission for SmsProvider.
,D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  968): java.lang.Throwable: stack dump
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@305faeb4:true
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
V/BluetoothMasService( 7272): Starting MAS instances
D/PMS     (  968): releaseWL(21eb73c6): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothAdapter( 7272): 142784528: getState() :  mService = null. Returning STATE_OFF
W/global  ( 7293): [apache-http] Connection GC has been deprecated!
D/DockEventReceiver( 5475): finishStartingService: stopping service
I/MailMessageReceiver( 7272): reg:com.android.bluetooth.btservice.AdapterApp@201d6f09 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@e53350e
,I/MailManager( 7272): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@e53350e
,V/EmailUtils( 7272): Manager Instance is not NULL
,I/ActivityManager(  968): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=7322 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7293): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 7293): [apache-http] Connection GC has been deprecated!
,D/HtcAdjCursorFactory( 7322): Set CursorWindow size to: 4194304 KB, Tid: 7346,
,D/Tethering(  968): interfaceRemoved wlan0,
E/Tethering(  968): attempting to remove unknown iface (wlan0), ignoring
,W/global  ( 7293): [apache-http] Connection GC has been deprecated!,
,D/EmailUtils( 7272): ============NULL aList========
V/EmailUtils( 7272): <-getEmailAccountIdList
V/BluetoothMasService( 7272): onCreate: mIsEmailEnabled: true
,D/Process (  968): killProcessQuiet, pid=6578
I/ActivityManager(  968): Killing 6578:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/Finsky  ( 7293): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/Tethering(  968): interfaceLinkStateChanged p2p0, false
D/Tethering(  968): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  968): Recipient 6578
,D/BluetoothMasReceiver( 7272): Bluetooth STATE CHANGED to 10
V/BluetoothMasService( 7272): onDestroy: mIsEmailEnabled: true
,V/BluetoothSapReceiver( 7272): SapReceiver onReceive 
,V/BluetoothSapReceiver( 7272): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 7272):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 7272): startService = false
I/ActivityManager(  968): Killing 7032:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=7032
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/Tethering(  968): interfaceRemoved p2p0,
E/Tethering(  968): attempting to remove unknown iface (p2p0), ignoring
,I/ActivityManager(  968): Recipient 7032
,D/PMS     (  968): acquireWL(18cdd7d9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
V/AlarmManager(  968): sending alarm PendingIntent{7fc686f: PendingIntentRecord{324797c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=347598, Int=0
,D/AuthorizationBluetoothService( 1954): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/AlarmManager(  968): sending alarm PendingIntent{273b1895: PendingIntentRecord{28b39321 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=356062, Int=0
,D/WeatherUtility( 1217): Weather sync is On,
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,I/ActivityManager(  968): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7362 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7293): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 7293): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SQLiteDatabase( 7293): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 7293): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7293): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7293): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 7293): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7293): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7293): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7293): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 7293): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7293): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7293): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7293): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7293): ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 7293): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7293): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7293): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7293): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7293): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7293): 	at java.lang.Thread.run(Thread.java:818)
,E/AndroidRuntime( 7293): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 7293): Process: com.android.vending, PID: 7293
E/AndroidRuntime( 7293): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7293): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7293): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7293): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 7293): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 7293): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 7293): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 7293): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7293): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7293): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  968): App crashed! Process: com.android.vending
E/AndroidRuntime_2_crash( 7293): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 7293): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 7293): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 7293): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 7293): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 7293): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 7293): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 7293): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 7293): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 7293): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 7293): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 7293): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 7293): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 7293): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 7293): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 7293): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 7293): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 7293): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 7293): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 7293): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 7293): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 7293): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 7293): 	... 4 more
I/art     (  430): Explicit concurrent mark sweep GC freed 8672(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 210us total 36.084ms
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7293, uid=10072, userID:0
I/ActivityManager(  968): Killing 7096:com.android.chrome/u0a96 (adj 15): empty #17
E/DropBoxManagerService(  968): Can't write: system_app_crash
E/DropBoxManagerService(  968): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  968): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  968): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  968): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  968): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  968): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  968): 	... 5 more
D/Process (  968): killProcessQuiet, pid=7096
E/SQLiteDatabase( 7293): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7293): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7293): 	at androi,d.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7293): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7293): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 7293): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 7293): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7293): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7293): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7293): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7293): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7293): 	at java.lang.Thread.run(Thread.java:818)
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
,E/AndroidRuntime_3_crash( 7293): crash in the same process: AsyncTask #3
E/AndroidRuntime_3_crash( 7293): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 7293): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 7293): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 7293): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 7293): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 7293): 	,at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 7293): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 7293): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 7293): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 7293): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 7293): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 7293): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 7293): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 7293): ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 7293): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 7293): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 7293): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 7293): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 7293): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 7293): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 7293): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 7293): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 7293): 	... 4 more
,I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 168us total 23.627ms,
,I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 160us total 21.005ms,
,I/ActivityManager(  968): Recipient 7096,
,D/Process ( 7293): killProcess, pid=7293,
,D/Process ( 7293): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 ,
,W/ResourcesManager( 7362): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7362): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1495): loadItems() com.htc.launcher.pageview.WidgetManager@3a31470c +
I/Prism.WidgetManager( 1495): onLoadItems() +
,I/MultiDex( 7362): VM with version 2.1.0 has multidex support,
I/MultiDex( 7362): install
I/MultiDex( 7362): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  968): Recipient 7293
,I/ActivityManager(  968): Process com.android.vending (pid 7293) has died
,W/ResourcesManager( 1495): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/JNIHelp ( 7362): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7362): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7362): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f0d1c91: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7362): Installed default security provider GmsCore_OpenSSL
,E/SQLiteLog( 1954): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error,
E/SQLiteDBG( 1954): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x55874bc0b0
,W/NativeLibraryUtils( 7362): Failed to open lock file,
W/NativeLibraryUtils( 7362): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7362): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7362): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7362): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7362): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7362): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7362): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7362): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7362): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7362): 	... 3 more
E/AndroidRuntime( 1954): FATAL EXCEPTION: main
E/AndroidRuntime( 1954): Process: com.google.process.gapps, PID: 1954
E/AndroidRuntime( 1954): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1954): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1954): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1954): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1954): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1954): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1954): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1954): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1954): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1954): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1954): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1954): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1954): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1954): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1954): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1954): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1954): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1954): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1954): 	... 9 more
E/ActivityManager(  968): App crashed! Process: com.google.process.gapps
D/Process ( 1954): killProcess, pid=1954
,D/Process ( 1954): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 ,
,E/DropBoxManagerService(  968): Can't write: system_app_crash
E/DropBoxManagerService(  968): java.io.FileNotFoundException: /data/system/dropbox/drop150.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  968): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
,E/DropBoxManagerService(  968): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  968): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  968): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  968): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  968): 	... 5 more
,E/JavaBinder( 7362): !!! FAILED BINDER TRANSACTION !!!,
,E/JavaBinder( 7362): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 7362): !!! FAILED BINDER TRANSACTION !!!,
E/JavaBinder( 7362): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 7362): !!! FAILED BINDER TRANSACTION !!!
,W/ResourcesManager( 1495): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  968): Recipient 1954
I/ActivityManager(  968): Process com.google.process.gapps (pid 1954) has died
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 10999ms
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 30999ms
,I/ActivityThread( 7362): Removing dead content provider:android.content.ContentProviderProxy@3f10d664
,I/ActivityManager(  968): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=7396 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/ActivityManager(  968): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7410 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
V/AlarmManager(  968): sending alarm PendingIntent{df2424e: PendingIntentRecord{37c1a46f com.android.vending startService}}, i=null, t=0, cnt=1, w=1453125489238, Int=0,
,W/asset   ( 1495): Copying FileAsset 0x5587d5f180 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/ResourcesManager( 7396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 7396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
