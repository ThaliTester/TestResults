#### Test 506502782e2cb10_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
,D/PMS     (  922): acquireWL(31dbd1f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 922 1000 null
--------- beginning of main
D/UsbnetService(  922): BroadcastReceiver::onReceive+
I/BatteryService(  922): n_update end
D/UsbnetService(  922): onReceive BATTERY_CHANGED
D/PMS     (  922): releaseWL(31dbd1f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  922):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  922): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  922): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  922): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  922): runPSCheck
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  922): Checking...
D/WifiController(  922): handleMessage: E msg.what=155652
I/HtcPowerSaver(  922): >> updateStatus
D/WifiController(  922): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  922): processMsg: StaEnabledState
D/WifiController(  922): battery changed pluggedType: 2
D/WifiController(  922): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  922): handleMessage: X
I/HtcPowerSaver(  922): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  922): << updateStatus
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 6746): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6746): ====startRecUseTime====
D/htc.customization.log.level( 6746):  is 
W/CustomizationLogLevel( 6746): Level value is invalid, use default level 2
D/CustomizationManager( 6746):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 6746): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6746): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6746): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6746): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6746): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6746): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6746): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6746): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6746): Parsing tag category name = system
I/CustomizationCIDLoader( 6746): Parsing tag category name = application
I/CustomizationCIDLoader( 6746): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6746): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6746): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6746): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6746): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6746): add string-array item, value = 42507
I/CustomizationCIDLoader( 6746): add string-array item, value = 21902
I/CustomizationCIDLoader( 6746): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6746): add string-array item, value = 23420
I/CustomizationCIDLoader( 6746): add string-array item, value = 22299
I/CustomizationCIDLoader( 6746): add string-array item, value = 24002
I/CustomizationCIDLoader( 6746): add string-array item, value = 23210
I/CustomizationCIDLoader( 6746): add string-array item, value = 23205
I/CustomizationCIDLoader( 6746): add string-array item, value = 23806
I/CustomizationCIDLoader( 6746): add string-array item, value = 23430
I/CustomizationCIDLoader( 6746): add string-array item, value = 23408
I/CustomizationCIDLoader( 6746): add string-array item, value = 27205
I/CustomizationCIDLoader( 6746): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6746): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6746):  Read CID file spent 0.117 (s)
D/CustomizationManager( 6746):  All configurations done spent 0.118 (s)
D/PMS     (  922): acquireHCC(b48ed1d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 922 1000 null
I/ActivityManager(  922): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6746 on display 0
D/PMS     (  922): acquireHCC(7b9fb92): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 922 1000 null
W/asset   (  922): Copying FileAsset 0x555b356ec0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  922): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6764 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
V/ActivityManager(  922): Display changed displayId=0
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6764): Copying FileAsset 0xac202e18 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1587): [trimMemory] 20
I/WebViewFactory( 6764): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6764): Time to load native libraries: 10 ms (timestamps 9210-9220),
,I/LibraryLoader( 6764): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6764): Binding Chromium to main looper Looper (main, tid 1) {26054c5},
I/LibraryLoader( 6764): Expected native library version number "",actual native library version number ""
,I/chromium( 6764): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6764): Initializing chromium process, singleProcess=true,
,W/art     ( 6764): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6764): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6764): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6764): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6764): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6764): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6764): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6764): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6764): Local Branch: 
I/Adreno-EGL( 6764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6764): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6764):                  d74aa161a12b9c6fc6332151
,W/System.err(  922): java.lang.Throwable: stack dump
W/System.err(  922): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  922): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  922): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  922): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  922): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  922): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31874bb6:true
,D/BluetoothAdapter( 6764): 729184321: getState(). Returning 12
,W/art     ( 6764): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6764): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6764): CordovaWebView is running on device made by: HTC
,W/art     ( 6764): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6764): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6764): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
W/HtcSystemUPManager(  922): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  922): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  922): hiding MENU key
,D/StatusBarManagerService(  922): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  922): hiding MENU key
,D/FindExtension( 6764): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6764): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@28668417, mServedView=org.apache.cordova.engine.SystemWebView{30af7004 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@15ec19ed
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/InputMethodManagerService(  922): Disable input method client, pid=1587
D/StatusBarManagerService(  922): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6764): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  922): Displayed com.test.thalitest/.MainActivity: +658ms (total +702ms)
,W/BindingManager( 6764): Cannot call determinedVisibility() - never saw a connection for the pid: 6764,
,D/JsMessageQueue( 6764): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6764): JniHelper::setJavaVM(0xab0968f8), pthread_self() = -1406543760
,D/JX-Cordova( 6764): jxcore cordova android initializing
,W/jxcore-log( 6764): Initializing JXcore engine
,W/jxcore-log( 6764): JXcore engine is ready
,W/jxcore-log( 6764): Starting JXcore engine
,W/jxcore-log( 6764): Platform android
W/jxcore-log( 6764): ,
W/jxcore-log( 6764): Process ARCH arm
W/jxcore-log( 6764): 
,D/PMS     (  922): releaseHCC(b48ed1d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  922): releaseHCC(7b9fb92): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6764): JXcore Cordova bridge is ready!,
I/jxcore-log( 6764): 
W/jxcore-log( 6764): JXcore engine is started
,I/chromium( 6764): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6764): Toggling radios to true,
I/jxcore-log( 6764): 
,D/BluetoothAdapter( 6764): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  922): ADD_CLIENT: 8
D/WifiService(  922): New client listening to asynchronous messages
,D/WifiManager( 6764): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/WifiService(  922): setWifiEnabled: true pid=6764, uid=10366
W/Settings:Agent(  922): MONITOR_LOG
E/WifiService(  922): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  922): name: wifi_on
I/WifiService(  922): isSprintWifiRestricted(): false
W/Settings:Agent(  922): value: 2
I/WifiService(  922): isMdmWifiRestricted(): false
W/Settings:Agent(  922): >> traceCallingStack()
W/Settings:Agent(  922): Process.myPid(): 922
W/Settings:Agent(  922): Process.myTid(): 1764
W/Settings:Agent(  922): Process.myUid(): 1000
,W/Settings:Agent(  922): 
W/Settings:Agent(  922): 
W/System.err(  922): java.lang.Throwable: stack dump
,W/System.err(  922): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  922): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  922): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  922): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  922): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  922): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  922): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  922): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  922): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
,W/System.err(  922): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  922): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  922): 
W/Settings:Agent(  922): << traceCallingStack(): 17(ms)
D/WifiController(  922): handleMessage: E msg.what=155656
D/WifiController(  922): processMsg: DeviceActiveState
D/WifiController(  922): processMsg: StaEnabledState
,D/WifiController(  922): handleMessage: X
D/WifiManager( 6764): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  922): handleMessage: E msg.what=131145
D/WifiManager( 6764): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  922): processMsg: ConnectedState
E/WifiStateMachine(  922):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
,D/wpa_supplicant( 1351): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1351): wlan0: Cancelling scan request
D/wpa_supplicant( 1351): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1351): TDLS: Tear down peers
D/wpa_supplicant( 1351): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6764): Radios toggled
I/jxcore-log( 6764): 
D/BluetoothManagerService(  922): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6764): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6764): 
I/jxcore-log( 6764): Perf Test app loaded loaded
I/jxcore-log( 6764): 
,I/jxcore-log( 6764): check test folder,
I/jxcore-log( 6764): 
,I/jxcore-log( 6764): found test : ./testFindPeers.js,
I/jxcore-log( 6764): 
,D/wpa_supplicant( 1351): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1351): wlan0: Deauthentication notification
,D/PMS     (  922): acquireWL(7d8b543): PARTIAL_WAKE_LOCK  NetworkStats 0x1 922 1000 null
D/wpa_supplicant( 1351): wlan0:  * reason 3 (locally generated)
D/UsbDeviceManager(  922): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1351): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1351): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1351): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1351): enter disconnect check
I/wpa_supplicant( 1351): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1351): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1351): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  922): interfaceLinkStateChanged wlan0, false
D/Tethering(  922): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  922): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  922): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  922): TetherInterfaceSM: wlan0: enter UnavailableState
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  922): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  922): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  922): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  922): interfaceLinkStateChanged wlan0, false
D/Tethering(  922): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  922): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbnetService(  922): BroadcastReceiver::onReceive+
D/UsbnetService(  922): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  922): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1351): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1351): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x558f8a9f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1351):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1351): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1351): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1351): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1351): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1351): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1351): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1351): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1351): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1351): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1351): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1351): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1351): netlink: Operstate: if,index=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1351): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1351): EAPOL: External notification - portValid=0
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1351): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/HTCRequest(  922): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1351): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1351): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1351): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1351): nl80211: Ignore disconnect event triggered during reassociation
D/WifiDisplayAdapter(  922): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  922):     Client/Owner: Client
D/WifiDisplayAdapter(  922):     GroupId: 
D/WifiDisplayAdapter(  922):     Passphrase: 
D/WifiDisplayAdapter(  922):     SessionId: 0
D/WifiDisplayAdapter(  922):     IP Address: }
D/WifiMonitor(  922): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  922): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  922): handleMessage: new destination call exit/enter
E/WifiStateMachine(  922): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  922): invokeExitMethods: ConnectedState
E/WifiStateMachine(  922): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  922): release()
E/WifiStateMachine(  922): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  922): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  922): invokeExitMethods: L2ConnectedState
D/TetherSettings( 5993): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5993): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5993): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5993): Cust_ConnectToPC   : spcsc>false
D/        ( 5993): Cust_ConnectToPC   : IPT>true
D/        ( 5993): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5993): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5993): hasRemovableStorageSlot: true
E/WifiStateMachine(  922): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
D/SmartNS_Utility( 5993): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5993): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  922): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  922): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  922): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER POWERMODE 0'
,I/wpa_supplicant( 1351): Power_Mode_Type mode = 0
I/wpa_supplicant( 1351): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  922): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  922): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  922): setDhcpActive: false
,V/NativeCrypto( 1839): Read error: ssl=0x555ae169f0: I/O error during system call, Connection timed out
,D/PMS     (  922): acquireWL(1351c7c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 5993): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  922): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  922): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  922): NetworkAgent != null
I/SmartNS_Utility( 5993): setISNotification
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
V/NetworkPolicy(  922): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/SmartNS_Utility( 5993): usb_cable_connect = 1
,D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/SmartNS_Utility( 5993): usb_denied = 0
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922): autoRoamSetBSSID any key="NG700"WPA_PSK
,E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
,D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
I/jxcore-log( 6764): found test : ./testSendData.js
I/jxcore-log( 6764): 
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
I/SmartNS_PSService( 5993): usb notificaiton:true
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  922): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  922): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  922):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  922): Start Disconnecting Watchdog 1
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=131146
E/WifiStateMachine(  922): processMsg: DisconnectingState
E/WifiStateMachine(  922):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1351): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1351): Fast associate: Old scan results
D/wpa_supplicant( 1351): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1351): wpa_supplicant_scan enter
D/wpa_supplicant( 1351): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1351): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1351): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1351): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1351): WPS:  * Request Type
D/wpa_supplicant( 1351): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1351): WPS:  * UUID-E
D/wpa_supplicant( 1351): WPS:  * Primary Device Type,
D/wpa_supplicant( 1351): WPS:  * RF Bands (3)
D/wpa_supplicant( 1351): WPS:  * Association State
D/wpa_supplicant( 1351): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1351): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1351): WPS:  * Manufacturer
D/wpa_supplicant( 1351): WPS:  * Model Name
D/wpa_supplicant( 1351): WPS:  * Model Number
D/wpa_supplicant( 1351): WPS:  * Device Name
D/wpa_supplicant( 1351): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1351): P2P: * P2P IE header
D/wpa_supplicant( 1351): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1351): P2P: * Listen Channel: Regulatory Class 81 Channel 6
E/WifiStateMachine(  922): handleMessage: X
D/wpa_supplicant( 1351): wlan0: Add radio work 'scan'@0x558f8ac680
D/wpa_supplicant( 1351): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  922): handleMessage: E msg.what=147460
E/WifiStateMachine(  922): processMsg: DisconnectingState
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1351): wlan0: Starting radio work 'scan'@0x558f8ac680 after 0.000053 second wait
D/WifiDataStallTracker(  922): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/wpa_supplicant( 1351): wlan0: nl80211: scan request
D/WifiDataStallTracker(  922): stopDataStallAlarm 
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1351): Scan requested (ret=0) - scan timeout 30 seconds
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  922):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=142824
E/WifiStateMachine(  922): processMsg: ConnectModeState
D/wpa_supplicant( 1351): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1351): wlan0: nl80211: Scan trigger
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1351): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1351): wlan0: Own scan request started a scan in 0.000116 seconds
I/wpa_supplicant( 1351): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  922):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=142825
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  922): ConnectModeState: Network connection lost 
E/WifiStateMachine(  922): transitionTo: destState=DisconnectedState
D/HTCRequest(  922): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiDataStallTracker(  922): ENABLE_DATA_MONITOR_POLL false Token 3
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  922): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED ,
E/WifiMonitor(  922): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/PMS     (  922): releaseWL(7d8b543): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiMonitor(  922): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/NetworkPolicy(  922): updateNetworkEnabledLocked()
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 15
V/NetworkPolicy(  922): updateNotificationsLocked()
E/WifiStateMachine(  922): handleMessage: new destination call exit/enter
E/WifiStateMachine(  922): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  922): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  922): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  922): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  922): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  922): DisconnectedState call setCountryCode()
E/WifiStateMachine(  922):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1351): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1351): wlan0: Cancelling scan request
V/NativeCrypto( 1839): SSL shutdown failed: ssl=0x555ae169f0: I/O error during system call, Broken pipe
D/ConnectivityService(  922): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
I/ActionCombine( 5993): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Validated
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  922): releaseWL(1351c7c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/wpa_supplicant( 1351): wlan0: nl80211: sched_scan request
,D/SmartNS_Utility( 5993): usb_cable_connect = 1
D/SmartNS_Utility( 5993): usb_denied = 0
I/SmartNS_PSService( 5993): usb notificaiton:true
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/RemoteViews( 1221): reapply : com.android.settings 0 36
,D/SmartNS_NSReceiver( 5993): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
,I/jxcore-log( 6764): found test : ./testSendData2.js
I/jxcore-log( 6764): 
I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/wpa_supplicant( 1351): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1351): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1351): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1351): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1351): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1351): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1351): wlan0: Scan completed in 0.050369 seconds
D/wpa_supplicant( 1351): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1351): wlan0: BSS: Start scan result update 7
D/WifiP2pService(  922): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1351): BSS: last_scan_res_used=0/32
D/WifiP2pService(  922): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1351): wlan0: New scan results available (own=1 ext=0)
D/WifiP2pService(  922): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1351): wlan0: Radio work 'scan'@0x558f8ac680 done in 0.051207 seconds
D/wpa_supplicant( 1351): wlan0: No suitable network found
D/wpa_supplicant( 1351): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1351): wlan0: Cancelling sched scan
D/wpa_supplicant( 1351): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1351): wlan0: Cancelling scan request
D/wpa_supplicant( 1351): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1351): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1351): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1351): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1351): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1351): p2p0: No suitable network found
D/wpa_supplicant( 1351): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1351): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  922): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  922): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  922): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor(  922): WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  922): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/jxcore  ( 6764): Error!: missing ) after argument list
E/jxcore  ( 6764): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNum,ber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=131101
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: DriverStartedState
I/chromium( 6764): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/WifiStateMachine(  922):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: DefaultState
E/WifiStateMachine(  922):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  922): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  922): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=147462
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=142880  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  922): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=142881  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  922): handleMessage: X
D/WifiNetworkAgent(  922): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  922): handleMessage: E msg.what=147462
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=142881  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  922): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  922): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  922): NetworkAgent == null
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  922): processMsg: ConnectModeState
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=142886  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  922): handleMessage: X
D/WISPrService( 5993): >>>>>WISPrService start isConnected = true<<<<<
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922): handleMessage: E msg.what=147461
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2243 bcn=0
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2243 bcn=0
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2243 bcn=0
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2243 bcn=0
D/WifiStateMachine(  922): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1351): wlan0: Control interface command 'LIST_DONGLES'
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 16
W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  922): [1,450,736,111,252 ms] noteScanEnd no scan source
D/WifiService(  922): New client listening to asynchronous messages
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1351): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiTrafficPoller(  922): ADD_CLIENT: 9
E/WifiStateMachine(  922): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@156bff2 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  922): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  922): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  922): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  922): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  922):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  922): UPC503894600 a0:c5:62:7a:49:97 rssi=-85 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  922): ageScanResultsOut delay 40000 size 3 now 1450736111254
E/WifiAutoJoinController (  922): newSupplicantResults size=3 known=1 true
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1351): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  922): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  922): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  922): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  922): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  922): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  922): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-58,-127) num=(1,0)
E/WifiAutoJoinController (  922): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  922): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  922): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  922): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  922): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-58 freq=2412
D/HtcWifiControlRoamOffload: (  922): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  922): Done attemptAutoJoin status=3
E/WifiConfigStore(  922):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  922): handleMessage: X
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  922): handleMessage: E msg.what=131215
E/WifiStateMachine(  922): processMsg: DisconnectedState
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  922):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-58 ;0 ,-127] any roam=0 rt=142902
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-58 ;0 ,-127] any roam=0 rt=142902
E/WifiStateMachine(  922): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  922): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  922): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
,E/WifiConfigStore(  922): Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
D/ConnectivityService(  922): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/ConnectivityService(  922): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
D/Nat464Xlat(  922): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1351): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  922): will read network variables netId=0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1351): Do not allow key_data field to be exposed
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Disconnected - quitting
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 group'
I/SecurityController( 1221): onLost 100
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/ConnectivityService(  922): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/ConnectivityService(  922): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/NetworkManagementService(  922): Removing idletimer
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  922): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  922):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  922): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/WifiDisplayAdapter(  922): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  922):     Client/Owner: Client
D/WifiDisplayAdapter(  922):     GroupId: 
D/WifiDisplayAdapter(  922):     Passphrase: 
D/WifiDisplayAdapter(  922):     SessionId: 0
D/WifiDisplayAdapter(  922):     IP Address: }
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  922): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1351): ENABLE_NETWORK (0)
D/wpa_supplicant( 1351): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1351): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1351): wpa_supplicant_scan enter
D/wpa_supplicant( 1351): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1351): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1351): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1351): WPS:  * Request Type
D/wpa_supplicant( 1351): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1351): WPS:  * UUID-E
D/wpa_supplicant( 1351): WPS:  * Primary Device Type
D/wpa_supplicant( 1351): WPS:  * RF Bands (3)
D/wpa_supplicant( 1351): WPS:  * Association State
D/wpa_supplicant( 1351): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1351): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1351): WPS:  * Manufacturer
D/wpa_supplicant( 1351): WPS:  * Model Name
D/wpa_supplicant( 1351): WPS:  * Model Number
D/wpa_supplicant( 1351): WPS:  * Device Name
D/wpa_supplicant( 1351): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1351): P2P: * P2P IE header
D/wpa_supplicant( 1351): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1351): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1351): wlan0: Add radio work 'scan'@0x558f8ac680
D/wpa_supplicant( 1351): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1351): wlan0: Starting radio work 'scan'@0x558f8ac680 after 0.000022 second wait
D/wpa_supplicant( 1351): wlan0: nl80211: scan request
D/wpa_supplicant( 1351): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1351): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1351): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1351): wlan0: Own scan request started a scan in 0.000052 seconds
I/wpa_supplicant( 1351): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  922): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  922): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1351): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  922): will read network variables netId=0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/wpa_supplicant( 1351): Do not allow key_data field to be exposed
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  ,922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1351): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1351): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  922): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  922):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/PMS     (  922): acquireWL(1a10843e): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 922 1000 null
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/usbnet  (  922): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  922):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  922): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/CSLegacyTypeTracker(  922): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1351): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1351): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1351): wpa_supplicant_scan enter
D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/wpa_supplicant( 1351): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1351): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1351): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  922): setLastSelectedConfiguration -1
E/WifiStateMachine(  922): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  922): handleMessage: new destination call exit/enter
E/WifiStateMachine(  922): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  922): invokeExitMethods: DisconnectedState
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1351): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  922): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  922): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  922): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  922): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  922): DisconnectedState call setCountryCode()
E/WifiStateMachine(  922):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1351): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1351): wlan0: Cancelling scan request
D/wpa_supplicant( 1351): wlan0: nl80211: sched_scan request
D/ConnectivityService(  922): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  922): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  922): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  922): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  922): ensureActiveMobilePolicyLocked()
D/PMS     (  922): acquireWL(2747629f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 922 1000 null
E/ConnectivityService(  922): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/DATA_ICON( 1221): dataConnected: false/false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkPolicy(  922): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  922): updateNetworkEnabledLocked()
V/NetworkPolicy(  922): updateIfacesLocked()
V/NetworkPolicy(  922): updateNotificationsLocked()
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/NetworkManagementService(  922): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/FlexNetS( 6627): updateSvcAllowedInSettings:false
D/PMS     (  922): releaseWL(2747629f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  922): updateNetworkEnabledLocked()
V/NetworkPolicy(  922): updateNotificationsLocked()
D/wpa_supplicant( 1351): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1351): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1351): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1351): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1351): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1351): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1351): wlan0: Scan completed in 0.038113 seconds
D/wpa_supplicant( 1351): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1351): wlan0: BSS: Start scan result update 8
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=131131
E/WifiStateMachine(  922): processMsg: DisconnectedState
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to no match in scan
D/wpa_supplicant( 1351): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1351): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1351): wlan0: Radio work 'scan'@0x558f8ac680 done in 0.038898 seconds
D/wpa_supplicant( 1351): wlan0: No suitable network found
D/wpa_supplicant( 1351): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1351): wlan0: Cancelling sched scan
E/WifiStateMachine(  922):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/wpa_supplicant( 1351): nl80211: Sched scan stop sent (ret=0)
D/WifiP2pService(  922): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  922): processMsg: ConnectModeState
D/WifiP2pService(  922): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1351): wlan0: Cancelling scan request
D/WifiP2pService(  922): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1351): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1351): nl80211: Received scan results (0 BSSes)
D/wpa_suppli,cant( 1351): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1351): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1351): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1351): p2p0: No suitable network found
D/wpa_supplicant( 1351): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1351): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  922): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  922): WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  922): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  922):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  922): handleMessage: X
D/WIFI    (  922): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  922):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  922): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  922): enter WifiNetworkFactory startNetwork. mIPTStart:false
E/WifiStateMachine(  922): handleMessage: E msg.what=147461
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2243 bcn=0
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2243 bcn=0
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2243 bcn=0
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2243 bcn=0
D/WifiStateMachine(  922): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1351): wlan0: Control interface command 'LIST_DONGLES'
D/FlexNetS( 6627): updateSvcAllowedInSettings:false
W/WISPrService( 5993): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5993): trigger connection
D/WISPrService( 5993): continue
D/WISPrService( 5993): start DataConnection
D/libc    ( 5993): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
I/ActivityManager(  922): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6824 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/libc    ( 5993): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  922): [1,450,736,111,347 ms] noteScanEnd no scan source
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987",
D/wpa_supplicant( 1351): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  922): handleMessage: X
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 5993): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5993): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5993): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5993): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5993): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5993): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5993): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5993): [NET] android_getaddrinfo_proxy+,
D/libc    ( 5993): [NET] android_getaddrinfo_proxy get netid:0
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5993): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5993): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5993): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency,
D/WISPrService( 5993): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/FlexNetS( 6627): updateSvcAllowedInSettings:false
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800,
D/FlexNetS( 6627): updateSvcAllowedInSettings:false
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/FlexNetS( 6627): updateSvcAllowedInSettings:false
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/libc    ( 5993): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5993): [NET] android_getaddrinfofornet-, err=8
,D/FlexNetS( 6627): updateSvcAllowedInSettings:false,
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WISPrService( 5993): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/FlexNetS( 6627): updateSvcAllowedInSettings:false
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6627): updateSvcAllowedInSettings:false
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6627): updateSvcAllowedInSettings:false
,D/FlexNetS( 6627): updateSvcAllowedInSettings:false
,D/FlexNetS( 6627): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6627): updateSvcAllowedInSettings:false
,D/PMS     (  922): acquireWL(8152fb5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 922 1000 WorkSource{1000}
V/AlarmManager(  922): sending alarm PendingIntent{26b8fb88: PendingIntentRecord{2c96b921 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=131644, Int=0
V/AlarmManager(  922): sending alarm PendingIntent{8ca64a: PendingIntentRecord{3dc989bb com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143116, Int=0
D/FlexNetS( 6627): updateSvcAllowedInSettings:false
D/MdScPhnSt( 6824): [109.2.]  listen tmrbb8
,D/FlexNetS( 6627): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6627): updateSvcAllowedInSettings:false
,D/PMS     (  922): releaseWL(8152fb5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/MdProvGlob( 6695): remove item 101 (p2d27in206) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 6824): [109.2.] summary 118:p2 ignore
,D/Process (  922): killProcessQuiet, pid=6278
I/ActivityManager(  922): Killing 6278:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  922): Recipient 6278,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  922): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  922): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  922): acquireWL(7d0697): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 922 1000 null
,D/libc    (  922): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  922): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  922): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  922): [NET] android_getaddrinfo_proxy+
D/libc    (  922): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  396): [NET] android_getaddrinfofornet-, err=7,
D/libc    (  922): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, err=8
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  922): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  922): [NET] android_getaddrinfo_proxy+
D/libc    (  922): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    (  922): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, err=8
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  922): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  922): [NET] android_getaddrinfo_proxy+
D/libc    (  922): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  922): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  922): acquireWL(1746a0f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 922 1000 null,
D/GpsLocationProvider(  922): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/GpsLocationProvider(  922):  [handleDownloadXtraData]download failure, retry count: 1
D/PMS     (  922): releaseWL(7d0697): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  922): releaseWL(1746a0f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/htcCheckinService(  922): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/AlarmManager(  922): [AlarmQueuing] connectivity wifi: false
D/htcCheckinService(  922): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/GpsLocationProvider(  922): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  922): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  922): acquireWL(17bbd669): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 922 1000 null
D/GpsLocationProvider(  922): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ConnectivityHelper( 1587): [onReceive] WIFI(1): DISCONNECTED
,I/ActivityManager(  922): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6860 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/art     (  412): Explicit concurrent mark sweep GC freed 8640(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 243us total 34.357ms
,E/GpsLocationProvider(  922): No APN found to select.
,D/PMS     (  922): releaseWL(17bbd669): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6824): [9ff.1.]  listen tmrbb8,
,I/art     (  412): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 160us total 25.650ms,
D/MdScDataSum( 6824): [9ff.1.] summary 118:p1 ignore
,I/art     (  412): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 164us total 22.478ms,
,I/MusicStore( 6860): Database version: 120,
,D/VoldConnector(  922): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6860): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  922): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6860): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  922): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6860): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 6860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6860): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6860): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6860): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28f3372e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6860): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6860): GMSCore installation verified
,I/ConfigStore( 6860): Config Database version: 1
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6860, uid=10159, userID:0
,D/WifiDisplayAdapter(  922): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  922):     Client/Owner: Client
D/WifiDisplayAdapter(  922):     GroupId: 
D/WifiDisplayAdapter(  922):     Passphrase: 
D/WifiDisplayAdapter(  922):     SessionId: 0
D/WifiDisplayAdapter(  922):     IP Address: }
,D/MediaRouterService(  922): Client com.google.android.music (pid 6860): Registered,
,D/WifiDisplayAdapter(  922): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  922):     Client/Owner: Client
D/WifiDisplayAdapter(  922):     GroupId: 
D/WifiDisplayAdapter(  922):     Passphrase: 
D/WifiDisplayAdapter(  922):     SessionId: 0
D/WifiDisplayAdapter(  922):     IP Address: }
,I/MediaRouter( 6860): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6860): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6860, uid=10159, userID:0
,D/AutoSetting( 1646): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6485): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6485): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1646): Util - no network available!,
,D/AutoSetting( 1646): service - onCreate()
,I/GHttpClientFactory( 6860): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1646): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,I/iu.Environment( 4447): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/GoogleURLConnFactory( 6860): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  922): request 1bf37c59 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
I/iu.UploadsManager( 4447): num queued entries: 0
I/iu.UploadsManager( 4447): num updated entries: 0
D/LocationManagerService(  922): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1646): service - mHandler: cancel location update,
I/iu.SyncManager( 4447): NEXT; no task
D/AutoSetting( 1646): service -           changes count: 0
,D/ChimeraCfgMgr( 4447): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  922): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6903 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/Babel   ( 6511): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  922): Killing 6440:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  922): killProcessQuiet, pid=6440
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  922): Recipient 6440
,D/VoldConnector(  922): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6903): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  922): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/,
W/ContextImpl( 6903): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6903): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6903):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6903):   adb logcat -s GAv4
,D/VoldConnector(  922): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
,E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6903): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  922): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6903): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files,
,W/GAv4    ( 6903): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6903): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6903): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6903): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6903): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6903): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6903): Time to load native libraries: 1 ms (timestamps 7261-7262),
I/LibraryLoader( 6903): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6903): Binding Chromium to main looper Looper (main, tid 1) {346dfed0},
,I/LibraryLoader( 6903): Expected native library version number "",actual native library version number "",
,I/chromium( 6903): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6903): Initializing chromium process, singleProcess=true
,W/art     ( 6903): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6903): ApplicationContext is null in ApplicationStatus
,W/chromium( 6903): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6903): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6903): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6903): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6903): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6903): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6903): Local Branch: 
I/Adreno-EGL( 6903): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6903): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6903):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6903): Requires BLUETOOTH permission
,I/art     (  922): Explicit concurrent mark sweep GC freed 39791(2MB) AllocSpace objects, 3(508KB) LOS objects, 33% free, 16MB/25MB, paused 1.805ms total 180.915ms
,I/NSApplication( 6903): Starting up...,
,D/Process (  922): killProcessQuiet, pid=6018,
I/ActivityManager(  922): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6961 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  922): Killing 6018:com.android.vending/u0a72 (adj 15): empty #17
,D/BluetoothAdapter( 6764): 729184321: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6764): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6764): BLE supported!!
I/jxcore-log( 6764): 
,E/WifiStateMachine(  922): handleMessage: E msg.what=131168,
E/WifiStateMachine(  922): processMsg: DisconnectedState
,E/WifiStateMachine(  922):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  922): processMsg: ConnectModeState
,E/WifiStateMachine(  922):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  922): processMsg: DefaultState
E/WifiStateMachine(  922):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  922): handleMessage: X
,I/ActivityManager(  922): Recipient 6018
,D/Process (  922): killProcessQuiet, pid=5724
I/ActivityManager(  922): Killing 5724:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  922): Recipient 5724
,D/PMS     (  922): acquireWL(207caac2): PARTIAL_WAKE_LOCK  *alarm* 0x1 922 1000 WorkSource{10024},
V/AlarmManager(  922): sending alarm PendingIntent{252800d3: PendingIntentRecord{387ad410 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=148617, Int=0
,D/PMS     (  922): acquireWL(d495b09): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1839 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  922): releaseWL(207caac2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1839): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1839): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1839): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1839): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1839): [NET] android_getaddrinfo_proxy+
D/libc    ( 1839): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1839): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  922): releaseWL(d495b09): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  922): acquireWL(1567d72f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6860 10159 null,
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6860, uid=10159, userID:0
,D/PMS     (  922): releaseWL(1567d72f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6860): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6860): Stop autocaching.
,I/ActivityManager(  922): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6992 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 6992): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6992): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6992): VM with version 2.1.0 has multidex support
,I/MultiDex( 6992): install
I/MultiDex( 6992): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6992): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6992): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6992): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b47d9f7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6992): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1839): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1839): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4447): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 6992): callingUid 10024, callindPid: 6992
,E/MDM     ( 1893): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
I/PackageManager(  922):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4447, uid=10024, userID:0
,D/LocationInitializer( 4447): Restart initialization of location
,E/GmsUtils( 6860): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6860): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Process (  922): killProcessQuiet, pid=5932,
I/ActivityManager(  922): Killing 5932:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  922): Recipient 5932
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  922): acquireWL(34295db1): PARTIAL_WAKE_LOCK  *alarm* 0x1 922 1000 WorkSource{1000},
V/AlarmManager(  922): sending alarm PendingIntent{380f0296: PendingIntentRecord{731fe17 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1450736135113, Int=0
D/PMS     (  922): acquireWL(287e6204): PARTIAL_WAKE_LOCK  *backup* 0x1 922 1000 null
,D/PMS     (  922): releaseWL(34295db1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  922): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  922): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  922): releaseWL(287e6204): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/AutoSetting( 1646): service - handleMessage() stop self,
,D/AutoSetting( 1646): service - onDestroy() END
D/AutoSetting( 1646): service - handleMessage() quit looper
,D/TelephonyReceiver( 1542): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  922): acquireWL(12c523ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 922 1000 null,
I/BatteryService(  922): n_update end
D/PMS     (  922): releaseWL(12c523ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  922): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  922): updateBatteryInfo
D/UsbnetService(  922): onReceive BATTERY_CHANGED
D/NotificationService(  922): plugged=true pluggin=true
D/UsbnetService(  922):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  922): BroadcastReceiver::onReceive-
D/PMS     (  922): runPSCheck
D/HtcPowerSaver(  922): Checking...
I/HtcPowerSaver(  922): >> updateStatus
,D/WifiController(  922): handleMessage: E msg.what=155652,
D/WifiController(  922): processMsg: DeviceActiveState
D/WifiController(  922): processMsg: StaEnabledState
D/WifiController(  922): processMsg: DefaultState
D/WifiController(  922): battery changed pluggedType: 2
D/WifiController(  922): handleMessage: X
,I/HtcPowerSaver(  922): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  922): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  922): releaseWL(1a10843e): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  922): Failed to find a new network - expiring NetTransition Wakelock
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1646): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3289493d
,I/ActivityManager(  922): Killing 6579:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  922): killProcessQuiet, pid=6579
,D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  922): Recipient 6579,
,D/PMS     (  922): acquireWL(530b222): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 922 1000 WorkSource{1000},
V/AlarmManager(  922): sending alarm PendingIntent{26b8fb88: PendingIntentRecord{2c96b921 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=191644, Int=0
,V/AlarmManager(  922): sending alarm PendingIntent{344e64b3: PendingIntentRecord{3d819a70 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=212553, Int=0
V/AlarmManager(  922): sending alarm PendingIntent{fdd11e9: PendingIntentRecord{1fcbce6e com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190188, Int=0,
D/PMS     (  922): acquireWL(39c0990f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1839 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): releaseWL(39c0990f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
D/PMS     (  922): releaseWL(530b222): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/PMS     (  922): acquireWL(77b72b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 922 1000 null
I/BatteryService(  922): n_update end
D/PMS     (  922): releaseWL(77b72b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  922): updateBatteryInfo
D/PMS     (  922): runPSCheck
D/HtcPowerSaver(  922): Checking...
I/HtcPowerSaver(  922): >> updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  922): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  922): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  922): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  922): << updateStatus
D/UsbnetService(  922):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  922): plugged=true pluggin=true
D/UsbnetService(  922): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  922): handleMessage: E msg.what=155652
D/WifiController(  922): processMsg: DeviceActiveState
D/WifiController(  922): battery changed pluggedType: 2
D/WifiController(  922): processMsg: StaEnabledState
D/WifiController(  922): processMsg: DefaultState
D/WifiController(  922): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 5
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PMS     (  922): acquireWL(30a4788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 922 1000 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  922): n_update end
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  922): releaseWL(30a4788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  922): plugged=true pluggin=true
D/UsbnetService(  922): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  922): updateBatteryInfo
D/UsbnetService(  922): onReceive BATTERY_CHANGED
D/PMS     (  922): runPSCheck
D/UsbnetService(  922):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  922): Checking...
D/UsbnetService(  922): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  922): >> updateStatus
D/WifiController(  922): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  922): processMsg: DeviceActiveState
D/WifiController(  922): battery changed pluggedType: 2
D/WifiController(  922): processMsg: StaEnabledState
D/WifiController(  922): processMsg: DefaultState
D/WifiController(  922): handleMessage: X
I/HtcPowerSaver(  922): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  922): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  922): acquireWL(85c1521): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 922 1000 WorkSource{1000},
V/AlarmManager(  922): sending alarm PendingIntent{26b8fb88: PendingIntentRecord{2c96b921 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=251643, Int=0
D/GpsLocationProvider(  922): receive broadcast intent, action: com.htc.location.XTRA_ALARM_TIMEOUT
V/AlarmManager(  922): sending alarm PendingIntent{162b3d46: PendingIntentRecord{7389b07 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=445619, Int=0
D/GpsLocationProvider(  922): ALARM_XTRA_TIMEOUT
D/PMS     (  922): acquireWL(c05434): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 922 1000 null
,V/AlarmManager(  922): sending alarm PendingIntent{64de7d2: PendingIntentRecord{a39e0a3 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1450736309385, Int=0
D/GpsLocationProvider(  922): [handleMessage] DOWNLOAD_XTRA_DATA
D/PMS     (  922): releaseWL(c05434): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  922): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  922): releaseWL(85c1521): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  455): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  922): acquireWL(1e287fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 922 1000 null
I/BatteryService(  922): n_update end
D/PMS     (  922): releaseWL(1e287fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  922): updateBatteryInfo
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  922): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  922): runPSCheck
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,D/HtcPowerSaver(  922): Checking...
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  922): >> updateStatus
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  922): BroadcastReceiver::onReceive+
D/UsbnetService(  922): onReceive BATTERY_CHANGED
D/UsbnetService(  922):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  922): BroadcastReceiver::onReceive-
D/WifiController(  922): handleMessage: E msg.what=155652
D/WifiController(  922): processMsg: DeviceActiveState
D/WifiController(  922): battery changed pluggedType: 2
D/WifiController(  922): processMsg: StaEnabledState
,D/WifiController(  922): processMsg: DefaultState
D/WifiController(  922): handleMessage: X
D/PowerUI ( 1221): closing low battery warning: level=100
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  922): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  922): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  389): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1542): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1542): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1542): sku_id=118
,D/ContactMessageStore( 1542): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1542): start background delete task...
,D/ContactMessageStore( 1542): size: 0 , 0
,D/ContactMessageStore( 1542): Background delete complete
,D/PMS     (  922): acquireWL(3e14759): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 922 1000 WorkSource{1000},
V/AlarmManager(  922): sending alarm PendingIntent{26b8fb88: PendingIntentRecord{2c96b921 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=491644, Int=0
I/bt-btm  ( 3102): Received oneshot timer event complete
V/AlarmManager(  922): sending alarm PendingIntent{127eaf1e: PendingIntentRecord{87fe3ff com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940515, Int=0
I/bt-btm  ( 3102): btm_ble_timeout
I/bt-btm  ( 3102): btm_gen_resolvable_private_addr
,D/PMS     (  922): acquireWL(2c25f5cc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3102 1002 null
,D/bt-btm  ( 3102): btm_ble_rand_enc_complete,
I/bt-btm  ( 3102): btm_gen_resolve_paddr_low
D/bt-smp  ( 3102): smp_encrypt_data
W/bt-smp  ( 3102): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3102): Plain text(LSB ~ MSB) = b0 47 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3102): Encrypted text(LSB ~ MSB) = 41 26 44 e6 a7 c1 61 8a e7 09 4f 1b 4e 21 c8 0f 
I/bt-btm  ( 3102): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3102): Stopping oneshot timer
D/bt-btm  ( 3102): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  922): releaseWL(3e14759): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  922): releaseWL(2c25f5cc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/ActivityManager(  922): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7029 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/PMS     (  922): acquireWL(4d60015): PARTIAL_WAKE_LOCK  *alarm* 0x1 922 1000 WorkSource{10072},
V/AlarmManager(  922): sending alarm PendingIntent{28629f2a: PendingIntentRecord{8eae4a1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450736663178, Int=0
V/AlarmManager(  922): sending alarm PendingIntent{b33bdd9: PendingIntentRecord{37b6239e android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804945, Int=0
,I/ActivityManager(  922): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7043 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  922): sending alarm PendingIntent{2f8c11b: PendingIntentRecord{4a2a2b8 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1450736850592, Int=0
V/AlarmManager(  922): sending alarm PendingIntent{19238891: PendingIntentRecord{2975368c com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450736935755, Int=0,
,W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  922): releaseWL(4d60015): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6659): MY_DEBUG = false
,D/PowerUsageService( 6659): repeat time = 1450737835845,
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7029, uid=10072, userID:0
,W/global  ( 7029): [apache-http] Connection GC has been deprecated!
,I/PowerUsageList:PowerUsageHelper( 6659): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/art     ( 1839): Explicit concurrent mark sweep GC freed 13999(744KB) AllocSpace objects, 7(588KB) LOS objects, 48% free, 4MB/8MB, paused 761us total 40.782ms,
,D/PowerUsageList:BatterySipperExt( 6659): gen(), null == sipper.uidObj, userId = 0,
,D/Finsky  ( 7029): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 7029): [apache-http] Connection GC has been deprecated!,
E/cutils-trace( 7075): Error opening trace file: Permission denied (13)
I/dex2oat ( 7075): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7075): dex2oat: override thread count:4
,W/global  ( 7029): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7029): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  922): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7094 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7029): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7029): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7029, uid=10072, userID:0
,W/ResourcesManager( 7094): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7094): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7029): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/MultiDex( 7094): VM with version 2.1.0 has multidex support,
I/MultiDex( 7094): install
I/MultiDex( 7094): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 7029): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 7029): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7029): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 7094): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 7029): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityThread( 7094): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7094): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b47d9f7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7094): Installed default security provider GmsCore_OpenSSL,
V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1839): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1839): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4447): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/Finsky  ( 7029): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 6992): callingUid 10024, callindPid: 6992
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4447, uid=10024, userID:0
,E/MDM     ( 1893): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4447): Restart initialization of location
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 7075): dex2oat took 610.243ms (threads: 4)
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PushClient( 7043): ApplicationMonitor {6ec8327}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 7043): ApplicationMonitor {6ec8327}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 7043): ApplicationMonitor {6ec8327}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7043): ApplicationMonitor {6ec8327}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7043): ApplicationMonitor {6ec8327}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7043): ApplicationMonitor {6ec8327}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7043): ApplicationMonitor {6ec8327}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7043): ApplicationMonitor {6ec8327}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7043): ApplicationMonitor {6ec8327}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7043): PnsModel {1d5b31e6}: update(): Update registration caused by: alarm
,W/Finsky  ( 7029): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/PushClient( 7043): PnsConfigModel {2ed8f935}: <init>(): Use dm-client for provisioning.
,V/Finsky  ( 7029): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/System.err( 7043): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 7043): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7043): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7043): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  922): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7135 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,E/AndroidHttpClient( 7029): Leak found,
E/AndroidHttpClient( 7029): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 7029): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 7029): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 7029): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 7029): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 7029): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 7029): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 7029): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 7029): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 7029): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 7029): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 7029): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 7029): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 7029): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 7029): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 7029): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 7029): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/DeviceManagement( 7135): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7135 dbg=false s=true
,I/DeviceManagement( 7135): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 7135): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7135): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 7135): WorkflowService: Starting workflow service
,I/DeviceManagement( 7135): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1d5b31e6] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7135): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7135): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7135): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7135): SessionStateController: Checking invariants...
,D/Finsky  ( 7029): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  922): acquireWL(2f1e3053): PARTIAL_WAKE_LOCK  *alarm* 0x1 922 1000 WorkSource{10072}
V/AlarmManager(  922): sending alarm PendingIntent{35c60d90: PendingIntentRecord{8eae4a1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450736937102, Int=0
,D/PMS     (  922): releaseWL(2f1e3053): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DeviceManagement( 7135): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7029): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7029): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,I/art     (  922): Explicit concurrent mark sweep GC freed 22115(1066KB) AllocSpace objects, 3(508KB) LOS objects, 33% free, 16MB/25MB, paused 1.563ms total 135.007ms,
,I/DeviceManagement( 7135): SessionStateController: Checking invariants...,
V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7029): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7029): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1893): client connected with version: 7571000
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7029): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DeviceManagement( 7135): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DeviceManagement( 7135): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1d5b31e6]
,I/DeviceManagement( 7135): WorkflowService: Stopping workflow service,
I/ActivityManager(  922): Killing 6541:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  922): killProcessQuiet, pid=6541
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 7043): PnsModel {1d5b31e6}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  922): Recipient 6541
,D/Process (  922): killProcessQuiet, pid=6719,
I/ActivityManager(  922): Killing 6719:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  922): Recipient 6719
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7029): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 7029): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 7029): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7029): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7029): [1] DailyHygiene.reschedule: Scheduling new run in 81 minutes (failures=3)
,D/DeviceConnectionService( 1893): client connected with version: 7571000
,D/Process (  922): killProcessQuiet, pid=5993
,I/ActivityManager(  922): Killing 5993:com.android.settings/1000 (adj 15): empty #17
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  922): Recipient 5993
D/WifiService(  922): Client connection lost with reason: 4
,D/Process (  922): killProcessQuiet, pid=6695
I/ActivityManager(  922): Killing 6695:com.htc.mobiledata/u0a46 (adj 15): empty #17
,D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  922): Recipient 6695
,D/PMS     (  922): acquireWL(2ebf6976): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 922 1000 WorkSource{1000},
V/AlarmManager(  922): sending alarm PendingIntent{26b8fb88: PendingIntentRecord{2c96b921 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=971644, Int=0
,V/AlarmManager(  922): sending alarm PendingIntent{e7b53e4: PendingIntentRecord{be458a8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450736952940, Int=0,
,D/PMS     (  922): releaseWL(2ebf6976): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/Finsky  ( 7029): [702] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 7029): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  922): acquireWL(46a604d): PARTIAL_WAKE_LOCK  *alarm* 0x1 922 1000 WorkSource{1000}
V/AlarmManager(  922): sending alarm PendingIntent{1330a702: PendingIntentRecord{2c25e813 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450736981567, Int=0,
D/SmartSyncUtils( 6659): isEpsOn(), nState = 0
,D/PMS     (  922): releaseWL(46a604d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  922): acquireWL(2a8bca50): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6659 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6659): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6659): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6659): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6659): SettingOnTime = 1450764000000, randomSettingOnTime = 1450760417000
,D/SmartSyncScreenOnOffTimeReceiver( 6659): SettingOffTime = 1450742400000, randomSettingOffTime = 1450744610000
,D/SmartSyncScreenOnOffTimeReceiver( 6659): bDayMode = false,
D/SmartSyncScreenOnOffTimeReceiver( 6659): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6659): bNightModeTurnOffOnce = false,
,D/PMS     (  922): releaseWL(2a8bca50): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,E/PNP_UPDATERD(  389): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  922): User[0] Flushing usage stats to disk
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1839): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1839): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1839): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1839): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1839): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1839): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1839): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 1 40
E/PlayEventLogger( 7029): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7029): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7029): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7029): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7029): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7029): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7029): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 7029): Ignoring header User-Agent because its value was null.,
D/libc    ( 7029): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 7029): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7029): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7029): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7029): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7029): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 7029): [NET] android_getaddrinfo_proxy-, NODATA
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1839): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1839): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1839): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1839): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1839): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1839): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1839): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 7029): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7029): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7029): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7029): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7029): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7029): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7029): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 7029): Ignoring header User-Agent because its value was null.
D/libc    ( 7029): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 7029): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7029): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7029): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7029): [NET] android_getaddrinfo_proxy+
D/libc    ( 7029): [NET] android_getaddrinfo_proxy get netid:0
I/RemoteViews( 1221): reapply : com.google.android.gms 5 40
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 7029): [NET] android_getaddrinfo_proxy-, NODATA
,E/PNP_UPDATERD(  389): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  922): acquireWL(31d69444): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 922 1000 WorkSource{1000}
V/AlarmManager(  922): sending alarm PendingIntent{26b8fb88: PendingIntentRecord{2c96b921 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1031643, Int=0,
V/AlarmManager(  922): sending alarm PendingIntent{a22092d: PendingIntentRecord{3517ce62 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1840527, Int=0
I/bt-btm  ( 3102): Received oneshot timer event complete
I/bt-btm  ( 3102): btm_ble_timeout
I/bt-btm  ( 3102): btm_gen_resolvable_private_addr
D/PMS     (  922): acquireWL(1dd0ebf3): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3102 1002 null
,D/bt-btm  ( 3102): btm_ble_rand_enc_complete
,I/bt-btm  ( 3102): btm_gen_resolve_paddr_low
D/bt-smp  ( 3102): smp_encrypt_data
W/bt-smp  ( 3102): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 3102): Plain text(LSB ~ MSB) = c7 2e 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 3102): Encrypted text(LSB ~ MSB) = 1e da 06 89 99 2a 99 c4 7e 4f 54 08 74 4d a5 b8 
I/bt-btm  ( 3102): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3102): Stopping oneshot timer
D/bt-btm  ( 3102): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  922): Prepared write state in 20ms,
,I/ProcessStatsService(  922): Prepared write state in 7ms,
,I/ProcessStatsService(  922): Prepared write state in 6ms,
,I/ProcessStatsService(  922): Prepared write state in 6ms,
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
D/PMS     (  922): releaseWL(31d69444): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  922): releaseWL(1dd0ebf3): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  922): acquireWL(acab0b0): PARTIAL_WAKE_LOCK  *alarm* 0x1 922 1000 WorkSource{10024}
V/AlarmManager(  922): sending alarm PendingIntent{32430b29: PendingIntentRecord{1ea86eae com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450737629267, Int=1800000,
V/AlarmManager(  922): sending alarm PendingIntent{2804544f: PendingIntentRecord{1fa227dc com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1852934, Int=0
V/AlarmManager(  922): sending alarm PendingIntent{b33bdd9: PendingIntentRecord{37b6239e android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1687482, Int=0
V/AlarmManager(  922): sending alarm PendingIntent{3cca7c38: PendingIntentRecord{1f602411 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1824880, Int=1800000
V/AlarmManager(  922): sending alarm PendingIntent{105830e5: PendingIntentRecord{2975368c com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450737835845, Int=0
,D/PMS     (  922): acquireWL(a90c7ba): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4447 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(1917e5c8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4447 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): releaseWL(a90c7ba): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(1bc4979d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 922 1000 null
,D/PMS     (  922): releaseWL(1bc4979d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  922): updateNetworkEnabledLocked()
V/NetworkPolicy(  922): updateNotificationsLocked()
,W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  922): releaseWL(acab0b0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6659): MY_DEBUG = false
,I/EventLogService( 4447): Aggregate from 1450736064771 (log), 1450735829215 (data)
,D/PowerUsageService( 6659): repeat time = 1450738735941
,D/LocationManagerService(  922): getAllProviders()=[passive, gps, network]
,D/PMS     (  922): releaseWL(1917e5c8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 6659): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6659): gen(), null == sipper.uidObj, userId = 0,
,I/art     ( 1839): Explicit concurrent mark sweep GC freed 27092(1594KB) AllocSpace objects, 5(420KB) LOS objects, 48% free, 4MB/8MB, paused 1.206ms total 74.747ms
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1839): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1839): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1839): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1839): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,W/GLSActivity( 1839): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1839): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1839): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1839): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1839): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1839): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1839): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 7029): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 7029): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7029): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7029): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7029): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7029): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7029): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 7029): Ignoring header User-Agent because its value was null.
D/libc    ( 7029): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 7029): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7029): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7029): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7029): [NET] android_getaddrinfo_proxy+
D/libc    ( 7029): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 7029): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  922): acquireWL(1e745ee6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 922 1000 null,
I/BatteryService(  922): n_update end
,D/UsbnetService(  922): BroadcastReceiver::onReceive+
D/PMS     (  922): releaseWL(1e745ee6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  922): onReceive BATTERY_CHANGED
D/NotificationService(  922): plugged=true pluggin=true
D/UsbnetService(  922):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  922): battery changed pluggedType: 2
D/UsbnetService(  922): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  922): updateBatteryInfo
D/WifiController(  922): handleMessage: E msg.what=155652
D/PMS     (  922): runPSCheck
D/WifiController(  922): processMsg: DeviceActiveState
D/HtcPowerSaver(  922): Checking...
D/WifiController(  922): processMsg: StaEnabledState
I/HtcPowerSaver(  922): >> updateStatus
D/WifiController(  922): processMsg: DefaultState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  922): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  922): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  922): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms)
```
