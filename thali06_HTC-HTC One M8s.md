#### Test 5497026186051be_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
,D/PMS     (  967): acquireWL(1f0eb87f): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{26b5704c: PendingIntentRecord{2a402895 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452511791911, Int=0
D/PMS     (  967): acquireWL(1ecddaa): PARTIAL_WAKE_LOCK  *backup* 0x1 967 1000 null
D/PMS     (  967): releaseWL(1f0eb87f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/BackupManagerService(  967): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  967): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  967): releaseWL(1ecddaa): PARTIAL_WAKE_LOCK  *backup* 0x1 null
--------- beginning of main
E/cutils-trace( 6302): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6302): ====startRecUseTime====
D/htc.customization.log.level( 6302):  is 
W/CustomizationLogLevel( 6302): Level value is invalid, use default level 2
D/CustomizationManager( 6302):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 6302): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6302): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6302): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6302): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6302): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6302): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6302): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6302): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6302): Parsing tag category name = system
I/CustomizationCIDLoader( 6302): Parsing tag category name = application
I/CustomizationCIDLoader( 6302): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6302): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6302): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6302): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6302): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6302): add string-array item, value = 42507
I/CustomizationCIDLoader( 6302): add string-array item, value = 21902
I/CustomizationCIDLoader( 6302): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6302): add string-array item, value = 23420
I/CustomizationCIDLoader( 6302): add string-array item, value = 22299
I/CustomizationCIDLoader( 6302): add string-array item, value = 24002
I/CustomizationCIDLoader( 6302): add string-array item, value = 23210
I/CustomizationCIDLoader( 6302): add string-array item, value = 23205
I/CustomizationCIDLoader( 6302): add string-array item, value = 23806
I/CustomizationCIDLoader( 6302): add string-array item, value = 23430
I/CustomizationCIDLoader( 6302): add string-array item, value = 23408
I/CustomizationCIDLoader( 6302): add string-array item, value = 27205
I/CustomizationCIDLoader( 6302): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6302): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6302):  Read CID file spent 0.096 (s)
D/CustomizationManager( 6302):  All configurations done spent 0.096 (s)
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6302 on display 0
D/PMS     (  967): acquireHCC(18e05d9b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 967 1000 null
D/PMS     (  967): acquireHCC(34ef4538): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 967 1000 null
W/asset   (  967): Copying FileAsset 0x5597298ca0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6320 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  967): killProcessQuiet, pid=5631
I/ActivityManager(  967): Killing 5631:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  967): Recipient 5631
D/DotMatrix( 1306): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1306): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  967): Display changed displayId=0
W/asset   ( 6320): Copying FileAsset 0xac4c3ad8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1611): [trimMemory] 20
,I/WebViewFactory( 6320): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6320): Time to load native libraries: 10 ms (timestamps 9782-9792),
,I/LibraryLoader( 6320): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6320): Binding Chromium to main looper Looper (main, tid 1) {6faa0f0},
I/LibraryLoader( 6320): Expected native library version number "",actual native library version number ""
,I/chromium( 6320): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6320): Initializing chromium process, singleProcess=true,
,W/art     ( 6320): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6320): ApplicationContext is null in ApplicationStatus
,W/chromium( 6320): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6320): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6320): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6320): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6320): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6320): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6320): Local Branch: 
I/Adreno-EGL( 6320): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6320): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6320):                  d74aa161a12b9c6fc6332151
,W/System.err(  967): java.lang.Throwable: stack dump
W/System.err(  967): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  967): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  967): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  967): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@329b847c:true
D/BluetoothAdapter( 6320): 142662684: getState(). Returning 12
,W/ActivityManager(  967): Activity pause timeout for ActivityRecord{3247b911 u0 com.test.thalitest/.MainActivity t8}
I/art     (  967): Explicit concurrent mark sweep GC freed 49346(2MB) AllocSpace objects, 4(836KB) LOS objects, 33% free, 16MB/25MB, paused 1.636ms total 139.202ms
W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 2
,W/art     ( 6320): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6320): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6320): CordovaWebView is running on device made by: HTC
,W/art     ( 6320): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6320): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6320): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  967): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
,D/StatusBarManagerService(  967): setSystemUiVisibility(0x0)
,D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
,D/FindExtension( 6320): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6320): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@366911aa, mServedView=org.apache.cordova.engine.SystemWebView{19a819b VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1b289938
I/InputMethodManagerService(  967): Disable input method client, pid=1611
,I/PhoneStatusBar( 1212): setImeWindowStatus(false,false)
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6320): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +785ms (total +929ms)
,W/BindingManager( 6320): Cannot call determinedVisibility() - never saw a connection for the pid: 6320
,D/JsMessageQueue( 6320): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6320): JniHelper::setJavaVM(0xab3578f8), pthread_self() = -1402511104
D/JX-Cordova( 6320): jxcore cordova android initializing,
,D/PMS     (  967): releaseHCC(18e05d9b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  967): releaseHCC(34ef4538): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6320): Initializing JXcore engine
W/jxcore-log( 6320): JXcore engine is ready
,W/jxcore-log( 6320): Starting JXcore engine
,W/jxcore-log( 6320): Platform android
W/jxcore-log( 6320): ,
W/jxcore-log( 6320): Process ARCH arm
W/jxcore-log( 6320): 
,I/jxcore-log( 6320): JXcore Cordova bridge is ready!,
I/jxcore-log( 6320): 
W/jxcore-log( 6320): JXcore engine is started
I/Choreographer( 6320): Skipped 95 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6320): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6320): Toggling radios to true,
I/jxcore-log( 6320): 
,D/BluetoothAdapter( 6320): enable(): BT is already enabled..!,
,D/WifiService(  967): New client listening to asynchronous messages,
E/WifiTrafficPoller(  967): ADD_CLIENT: 9
D/WifiManager( 6320): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  967): setWifiEnabled: true pid=6320, uid=10366
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings:Agent(  967): MONITOR_LOG
I/WifiService(  967): isSprintWifiRestricted(): false
,W/Settings:Agent(  967): name: wifi_on
I/WifiService(  967): isMdmWifiRestricted(): false
W/Settings:Agent(  967): value: 2
W/Settings:Agent(  967): >> traceCallingStack()
,W/Settings:Agent(  967): Process.myPid(): 967
W/Settings:Agent(  967): Process.myTid(): 1606
W/Settings:Agent(  967): Process.myUid(): 1000
W/Settings:Agent(  967): 
W/Settings:Agent(  967): 
W/System.err(  967): java.lang.Throwable: stack dump
,W/System.err(  967): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  967): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  967): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  967): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  967): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  967): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  967): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  967): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  967): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  967): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  967): 
W/Settings:Agent(  967): << traceCallingStack(): 13(ms)
D/WifiController(  967): handleMessage: E msg.what=155656
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): handleMessage: X
D/WifiManager( 6320): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  967): handleMessage: E msg.what=131145
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
D/wpa_supplicant( 1348): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1348): TDLS: Tear down peers
D/wpa_supplicant( 1348): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiManager( 6320): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 6320): Radios toggled
I/jxcore-log( 6320): 
I/jxcore-log( 6320): My device name is: HTC-HTC One M8s
I/jxcore-log( 6320): 
,D/wpa_supplicant( 1348): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1348): wlan0: Deauthentication notification
D/wpa_supplicant( 1348): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1348): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1348): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1348): enter disconnect check
I/wpa_supplicant( 1348): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1348): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1348): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  967): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  967): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  967): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  967): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
,V/Tethering(  967): TetherInterfaceSM: wlan0: exit InitialState,
V/Tethering(  967): TetherInterfaceSM: wlan0: enter UnavailableState
D/PMS     (  967): acquireWL(10d313f1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbDeviceManager(  967): [USBNET] bCheckSuppFunc: cdc_network
D/Tethering(  967): sendTetherStateChangedBroadcast 0, 0, 0
D/wpa_supplicant( 1348): TDLS: Remove peers on disassociation
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
D/wpa_supplicant( 1348): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a3dd0f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1348): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1348): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1348): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1348): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1348): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1348): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1348): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1348): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1348): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbnetService(  967): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
E/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: ConnectedState
E/WifiStateMachine(  967): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  967): release()
E/WifiStateMachine(  967): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  967): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
D/TetherSettings( 4576): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4576): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4576): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4576): Cust_ConnectToPC   : spcsc>false
D/        ( 4576): Cust_ConnectToPC   : IPT>true
D/        ( 4576): Cust_ConnectToPC   : Singel_USB>false
W/ContextImpl( 4576): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
W/Settings( 4576): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4576): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4576): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/SmartNS_NSReceiver( 4576): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
,D/PMS     (  967): releaseWL(10d313f1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  967): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
E/WifiStateMachine(  967): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
V/NetworkPolicy(  967): updateNotificationsLocked()
E/WifiStateMachine(  967): handleNetworkDisconnect "NG700" nid=0
D/PMS     (  967): acquireWL(17591bd6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1348): Power_Mode_Type mode = 0
I/wpa_supplicant( 1348): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
I/SmartNS_Utility( 4576): setISNotification
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  967): setDhcpActive: false
D/SmartNS_Utility( 4576): usb_cable_connect = 1
D/SmartNS_Utility( 4576): usb_denied = 0
I/SmartNS_PSService( 4576): usb notificaiton:true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
V/NativeCrypto( 1797): Read error: ssl=0x55970118c0: I/O error during system call, Connection timed out
E/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/SmartNS_Utility( 4576): usb_cable_connect = 1
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/SmartNS_Utility( 4576): usb_denied = 0
I/SmartNS_PSService( 4576): usb notificaiton:true
,E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  967): NetworkAgent != null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED connected
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 1797): SSL shutdown failed: ssl=0x55970118c0: I/O error during system call, Broken pipe
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  967): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  967): stopDataStallAlarm 
D/ConnectivityService(  967): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL false Token 3
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
,I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,E/WifiStateMachine(  967): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/PMS     (  967): releaseWL(17591bd6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 15
,W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_NSReceiver( 4576): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  967): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  967):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  967): Start Disconnecting Watchdog 1
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131146
E/WifiStateMachine(  967): processMsg: DisconnectingState
E/WifiStateMachine(  967):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1348): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1348): Fast associate: Old scan results
D/wpa_supplicant( 1348): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1348): wpa_supplicant_scan enter
D/wpa_supplicant( 1348): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1348): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1348): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1348): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1348): WPS:  * Request Type
D/wpa_supplicant( 1348): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1348): WPS:  * UUID-E
D/wpa_supplicant( 1348): WPS:  * Primary Device Type
D/wpa_supplicant( 1348): WPS:  * RF Bands (3)
D/wpa_supplicant( 1348): WPS:  * Association State
D/wpa_supplicant( 1348): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1348): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1348): WPS:  * Manufacturer
D/wpa_supplicant( 1348): WPS:  * Model Name
D/wpa_supplicant( 1348): WPS:  * Model Number
D/wpa_supplicant( 1348): WPS:  * Device Name
D/wpa_supplicant( 1348): WPS:  * Version2 (0x20)
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1348): P2P: * P2P IE header
D/wpa_supplicant( 1348): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1348): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1348): wlan0: Add radio work 'scan'@0x55a3dd3680
D/wpa_supplicant( 1348): wlan0: First radio work item in the queue - schedule start immediately
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1348): wlan0: Starting radio work 'scan'@0x55a3dd3680 after 0.000056 second wait
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1348): wlan0: nl80211: scan request
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/wpa_supplicant( 1348): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1348): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1348): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1348): wlan0: Own scan request started a scan in 0.000138 seconds
I/wpa_supplicant( 1348),: wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147460
E/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  967): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  967): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  967):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132359
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132359
E/WifiStateMachine(  967): ConnectModeState: Network connection lost 
E/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  967): DisconnectedState call setCountryCode()
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  967):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1348): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
I/RemoteViews( 1212): reapply : com.android.settings 1 36
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1348): wlan0: nl80211: sched_scan request
I/RemoteViews( 1212): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1212): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
,I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:1,
,D/wpa_supplicant( 1348): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1348): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1348): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1348): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1348): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1348): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1348): wlan0: Scan completed in 0.044942 seconds
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/wpa_supplicant( 1348): nl80211: Received scan results (1 BSSes)
E/WifiStateMachine(  967): processMsg: DisconnectedState
I/wpa_supplicant( 1348): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
D/wpa_supplicant( 1348): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1348): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1348): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1348): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1348): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1348): wlan0: Radio work 'scan'@0x55a3dd3680 done in 0.045937 seconds
D/wpa_supplicant( 1348): wlan0: Selecting BSS from priority group 468
D/wpa_supplicant( 1348): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-60 wps
D/wpa_supplicant( 1348): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1348): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1348): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1348):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1348): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1348): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55a3dd2c00  current_ssid=0x0
D/wpa_supplicant( 1348): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1348): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1348): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1348): wlan0: Add radio work 'connect'@0x55a3dd3680
D/wpa_supplicant( 1348): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1348): wlan0: Starting radio work 'connect'@0x55a3dd3680 after 0.000044 second wait
I/wpa_supplicant( 1348): check if in concurrent case
I/wpa_supplicant( 1348): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132403  S,SID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  967): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=42 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  967): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=43 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132404  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131101
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/wpa_supplicant( 1348): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1348): wlan0: Cancelling sched scan
D/wpa_supplicant( 1348): nl80211: Sched scan stop sent (ret=0)
E/WifiStateMachine(  967):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
D/wpa_supplicant( 1348): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1348): wpas_start_assoc_cb, 1895
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/wpa_supplicant( 1348): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1348): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1348): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1348): RSN: PMKSA cache search - network_ctx=0x55a3dd2c00 try_opportunistic=0
D/wpa_supplicant( 1348): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1348): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1348): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1348): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1348): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1348): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1348): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1348): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1348): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1348): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1348): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1348): nl80211: Set mode ifindex 29 iftype 2 (STATION)
E/WifiStateMachine(  967):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
D/wpa_supplicant( 1348): nl80211: Unsubscribe mgmt frames handle 0x888888dd2b55a989 (mode change)
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1348): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a3dd2100
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=0104
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=040a
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=040b
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=040c
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=040d
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=090a
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=090b
E/WifiStateMachine(  967):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=090c
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=090d
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=0409506f9a09
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=7f506f9a09
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=0801
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=040e
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=06
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=0a07
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=0a11
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a3dd2100 match=0a1a
D/wpa_supplicant( 1348): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1348):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348):   * freq=2412
D/wpa_supplicant( 1348):   * freq_hint=2412
D/wpa_supplicant( 1348):   * SSID - hexdump(len=5): 4e 47 37 30 30
E/WifiStateMachine(  967):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1348):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1348):   * WPA Versions 0x2
D/wpa_supplicant( 1348):   * pairwise=0xfac04
E/WifiStateMachine(  967): processMsg: DefaultState
D/wpa_supplicant( 1348):   * group=0xfac04
D/wpa_supplicant( 1348):   * akm=0xfac02
D/wpa_supplicant( 1348):   * Auth Type 0
D/wpa_supplicant( 1348): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55a3dd2c3a
D/wpa_supplicant( 1348): nl80211: Connect request send successfully
E/WifiStateMachine(  967):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1348): wlan0: Setting authentication timeout: 10 sec 0 usec
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent DefaultState
D/wpa_supplicant( 1348): EAPOL: External notification - EAP success=0
D/WifiStateMachine(  967): Default got CMD_TETHER_STATE_CHANGE
D/wpa_supplicant( 1348): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1348): EAPOL: External notification - portControl=Auto
E/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 1348): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1348): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6377 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
D/WifiNetworkAgent(  967): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=132416  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4576): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=132421  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  967): handleMessage: X
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  967): handleMessage: E msg.what=147461
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 dur:84 bcn=0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 dur:84 bcn=0
E/WifiStateMachine(  967): processMsg: DriverStartedState
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  967):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 dur:84 bcn=0
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 dur:84 bcn=0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1348): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  967): [1,452,511,795,500 ms] noteScanEnd no scan source
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1348): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  967): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3414c388 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  967): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  967): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  967): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  967): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  967):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  967): Gonzos 38:f8:89:11:e9:11 rssi=-87 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  967): UPC503894600 a0:c5:62:7a:49:97 rssi=-82 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  967): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  967): UPC5999698 64:7c:34:12:7f:81 rssi=-91 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  967): ageScanResultsOut delay 40000 size 6 now 1452511795503
E/WifiAutoJoinController (  967): newSupplicantResults size=6 known=1 true
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1348): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  967): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  967): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  967): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  967): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
D/WifiService(  967): New client listening to asynchronous messages
E/WifiAutoJoinController (  967): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  967):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  967): handleMessage: X
E/WifiTrafficPoller(  967): ADD_CLIENT: 10
E/WifiStateMachine(  967): handleMessage: E msg.what=131213
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132432
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132432
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132432
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132433
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=132434  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info0x
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 18
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=132437  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  967): handleMessage: X
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 19
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
I/art     (  431): Explicit concurrent mark sweep GC freed 8679(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 273us total 23.849ms
D/ConnectivityService(  967): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  967): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  967): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Disconnected - quitting
D/WIFI    (  967): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  967): Removing idletimer
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  967): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/usbnet  (  967): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/PMS     (  967): acquireWL(b933d44): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 967 1000 null
D/ConnectivityManager.CallbackHandler( 1212): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  967): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
I/SecurityController( 1212): onLost 100
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  967): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  967): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  967): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy(  967): ensureActiveMobilePolicyLocked()
D/PMS     (  967): acquireWL(30f3fe2d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
E/ConnectivityService(  967): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/DATA_ICON( 1212): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkPolicy(  967): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateIfacesLocked()
D/DATA_ICON( 1212): dataConnected: false/false
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  967): releaseWL(30f3fe2d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
V/NetworkPolicy(  967): updateNotificationsLocked()
I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 232us total 14.175ms
E/WifiStateMachine(  967): handleMessage: E msg.what=131131
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
E/WifiStateMachine(  967): handleMessage: X
V/NetworkPolicy(  967): updateNotificationsLocked()
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
W/WISPrService( 4576): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4576): trigger connection
D/WISPrService( 4576): continue
I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 274us total 14.576ms
D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:1
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:0
D/WISPrService( 4576): start DataConnection
D/libc    ( 4576): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4576): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4576): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4576): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4576): [NET] android_getaddrinfo_proxy+
D/libc    ( 4576): [NET] android_getaddrinfo_proxy get netid:0
W/ResourcesManager( 6377): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4576): [NET] android_getaddrinfo_proxy-, NODATA
I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:2
I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:0
,I/ActivityManager(  967): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6402 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/libc    ( 4576): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4576): [NET] android_getaddrinfofornet-, err=8
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/WISPrService( 4576): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/Tethering(  967): interfaceLinkStateChanged wlan0, false
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  967): interfaceLinkStateChanged wlan0, true
D/Tethering(  967): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  967): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  967): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  967): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  967): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  967): acquireWL(36d3c5e5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
E/WifiStateMachine(  967): handleMessage: E msg.what=131101
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
D/PMS     (  967): releaseWL(36d3c5e5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  967):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent DefaultState
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
D/WifiStateMachine(  967): Default got CMD_TETHER_STATE_CHANGE
V/NetworkPolicy(  967): updateNotificationsLocked()
E/WifiStateMachine(  967): handleMessage: X
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/wpa_supplicant( 1348): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1348): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1348): Wireless event: cmd=0x8c02 len=152
,I/wpa_supplicant( 1348): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1348): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1348): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1348): nl80211: Connect event
D/wpa_supplicant( 1348): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1348): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1348): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1348): wlan0: Association info event
D/wpa_supplicant( 1348): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): wlan0: freq=2412 MHz
D/wpa_supplicant( 1348): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1348): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1348): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1348): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1348): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1348): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1348): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1348): TDLS: Remove peers on association
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1348): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1348): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1348): EAPOL: enable timer tick
D/wpa_supplicant( 1348): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1348): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
I/wpa_supplicant( 1348): htc_wext_set_keepalive +
I/wpa_supplicant( 1348): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1348): getPrivFuncNum +	
I/wpa_supplicant( 1348): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1348): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1348): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1348): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1348): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1348): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1348): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1348): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1348):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1348):   key_nonce - hexdump(len=32): 55 67 e8 1a 5c b2 25 26 0c 44 a0 d8 95 11 c0 37 5f 8a 33 65 3f db cd 48 a5 b8 62 d7 7c 33 0e ef
D/wpa_supplicant( 1348):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D,/wpa_supplicant( 1348):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1348): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1348): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 1348): WPA: Renewed SNonce - hexdump(len=32): 13 26 46 84 69 b5 29 78 19 bb 43 39 79 ec 5e 9a 03 3f 80 a6 c8 d1 db 25 93 bb 72 b1 15 5d 0d f3
D/wpa_supplicant( 1348): WPA: Nonce1 - hexdump(len=32): 13 26 46 84 69 b5 29 78 19 bb 43 39 79 ec 5e 9a 03 3f 80 a6 c8 d1 db 25 93 bb 72 b1 15 5d 0d f3
D/wpa_supplicant( 1348): WPA: Nonce2 - hexdump(len=32): 55 67 e8 1a 5c b2 25 26 0c 44 a0 d8 95 11 c0 37 5f 8a 33 65 3f db cd 48 a5 b8 62 d7 7c 33 0e ef
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1348): WPA: PMK - hexdump(len=32): [REMOVED]
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1348): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1348): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1348): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1348): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1348): WPA: Derived Key MIC - hexdump(len=16): 59 33 cc b3 76 14 8f b0 0d 16 80 7b d8 ca 79 fc
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=46 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  967): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  967): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  967): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  967): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=132545  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/HTCRequest(  967): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  967): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiMonitor(  967): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  967): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  967): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d,4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=132546  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147500
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  967): Enter handleAssociatedWithEvent
D/WifiStateMachine(  967): Associated
D/WifiStateMachine(  967): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): Exit handleAssociatedWithEvent
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=132548  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info"NG700"
D/wpa_supplicant( 1348): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1348): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1348): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1348): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1348):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1348):   key_nonce - hexdump(len=32): 55 67 e8 1a 5c b2 25 26 0c 44 a0 d8 95 11 c0 37 5f 8a 33 65 3f db cd 48 a5 b8 62 d7 7c 33 0e ef
D/wpa_supplicant( 1348):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_rsc - hexdump(len=8): 8c cd 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_mic - hexdump(len=16): ea 55 7a 6d 80 ec 98 99 6a d3 7d 9e c2 0a 68 b0
D/wpa_supplicant( 1348): RSN: encrypted key data - hexdump(len=56): dc f4 69 12 61 cd 13 26 05 22 72 4a e2 2a d7 c2 20 09 55 a1 f8 66 20 cc a4 38 9e 35 f1 d6 ed 1d ...
D/wpa_supplicant( 1348): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1348): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1348): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1348): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 19 b2 ...
D/wpa_supplicant( 1348): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1348): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1348): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1348): WPA: Derived Key MIC - hexdump(len=16): 37 0b a0 5e c8 5e eb 17 30 ad 6e fb d0 9f 67 c9
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1348): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55a3dd3390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1348): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1348): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1348):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1348): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1348): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1348): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1348): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1348): WPA: RSC - hexdump(len=6): 8c cd 00 00 00 00
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x557d1abe68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1348): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1348): nl80211: KEY_SEQ - hexdump(len=6): 8c cd 00 00 00 00
D/wpa_supplicant( 1348):    broadcast key
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 1348): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1348): wlan0: Cancelling authentication timeout
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1348): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1348): wlan0: Radio work 'connect'@0x55a3dd3680 done in 0.147546 seconds
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1348): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=49 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=50 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  967): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1348): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  967): Event [IFNAME=wlan0 Connect to SSID: NG700]
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=52 dispatchEvent: Connect to SSID: NG700
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiMonitor(  967): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1348): set send_ind_to_ndc = 0
I/wpa_supplicant( 1348): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1348): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=1
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/wpa_supplicant( 1348): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1348): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1348): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1348): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1348): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1348): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1348): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1348): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1348): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/Tethering(  967): interfaceLinkStateChanged wlan0, true
D/Tethering(  967): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=132560  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  967): handleMessage: X
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 21
D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: FOUR_WAY_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=132566  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=132567  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147459
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=132569
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=132569
E/WifiStateMachine(  967): Network connection established
D/WifiStateMachine(  967): fetchFrequency(), freq = 2412
E/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 22
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1348): CTRL_IFACE SET 'pno'='0'
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 23
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  967): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
E/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=4
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/ConnectivityService(  967): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/ConnectivityService(  967): Got NetworkAgent Messenger
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  967): NetworkAgent == null
D/ConnectivityService(  967): NetworkAgent connected
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 24
D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  967): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  967): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  967): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  967): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  967): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967): Start Dhcp Watchdog 2
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=132594  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=132595  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=132595  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  967): handleMessage: X
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: ObtainingIpState
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WISPrService( 4576): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  967): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  967):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/PMS     (  967): acquireWL(31ef9599): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 967 1000 null
E/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  967):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
D/WISPrService( 4576): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=196612
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  967):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiDataStallTracker(  967): setDhcpActive: true
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  967): do suspend false
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1348): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1348): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1348): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@328896f1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  967): noteBatchedScanstop()
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@328896f1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  967): handleMessage: X
I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1212): receive.wifiConnect:false wifiAPname:null elapse:1
,D/MdScPhnSt( 6402): [697.2.]  listen tmrbb8,
I/Babel_SMS( 6377): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6377): MmsConfig.loadMmsSettings
,I/ActivityManager(  967): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6438 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6377, uid=10112, userID:0,
,W/Settings( 6377): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6377): startup - clean,
,D/MdProvGlob( 6272): remove item 101 (p2d23in233) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 6402): [697.2.] summary 118:p2 ignore
,W/HtcWrapAdjustableCursorFactory( 6438): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MdProvGlob( 6272): remove item 101 (p2in20) for 15:android.intent.action.ANY_DATA_STATE
,D/MessageFrequencyProvider( 6438): onCreate
,V/GetPrviateResource( 6438): GetPrviateResource,
V/GetPrviateResource( 6438): GetPrviateResource
,D/MessageCustFlag( 6438): sense_version=6.0,
,D/BTAccessoryUtil( 6438): createReceiver
D/MdProvGlob( 6272): remove item 101 (p2d1in19) for 15:android.intent.action.ANY_DATA_STATE
,D/BTAccessoryUtil( 6438): registerReceiver return intent = null
I/Babel   ( 6377): deleted: false for 0
D/MessageCustFlag( 6438): sku_id=118
D/MmsCustomizationProvider( 6438): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/HtcBuildUtils( 6438): getRATByHtcTelephonyCapability:1
W/SystemReader( 6438): Cannot find qct_8960_interface, use default value instead
,D/MmsCustomizationProvider( 6438): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 6377): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6377): MmsConfig.loadFromDatabase,
,E/Babel_SMS( 6377): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6377): MmsConfig.loadFromResources
,E/Babel_SMS( 6377): canonicalizeMccMnc: invalid mccmnc nullnull
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6377, uid=10112, userID:0
I/Babel_SMS( 6377): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6377, uid=10112, userID:0
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6377, uid=10112, userID:0
,E/dhcpcd  ( 6467): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6377, uid=10112, userID:0
I/dhcpcd  ( 6467): version 5.5.6 starting
,E/dhcpcd  ( 6467): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6377, uid=10112, userID:0
I/dhcpcd  ( 6467): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6467): autoip env[11]:autoip=DISABLE
,D/MdProvGlob( 6272): remove item 101 (p2in50) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6402): [697.14.] summary 118:p1 ignore
,W/VideoCapabilities( 6377): Unrecognized profile 2130706433 for video/avc
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,I/dhcpcd  ( 6467): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6467): wlan0: sending REQUEST (xid 0x2b3fc65e), next in 1.51 seconds
W/VideoCapabilities( 6377): Unsupported mime video/x-ms-wmv
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,W/Utils   ( 6377): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 6377): Unsupported mime audio/qcelp
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false
W/AudioCapabilities( 6377): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6377): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6377): Unsupported mime video/x-ms-wmv
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,D/TetherSettings( 4576): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 4576): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4576): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4576): Cust_ConnectToPC   : spcsc>false,
D/        ( 4576): Cust_ConnectToPC   : IPT>true
D/        ( 4576): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4576): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4576): hasRemovableStorageSlot: true,
,D/SmartNS_Utility( 4576): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
W/ContextImpl( 4576): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartNS_NSReceiver( 4576): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
I/SmartNS_Utility( 4576): setISNotification
D/SmartNS_Utility( 4576): usb_cable_connect = 1
,D/SmartNS_Utility( 4576): usb_denied = 0
I/VideoCapabilities( 6377): Unsupported profile 4 for video/mp4v-es
I/SmartNS_PSService( 4576): usb notificaiton:true
,E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
,W/VideoCapabilities( 6377): Unrecognized profile 2130706433 for video/avc,
W/VideoCapabilities( 6377): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6377): Unrecognized profile 2130706433 for video/avc
D/SmartNS_Utility( 4576): usb_cable_connect = 1
,D/SmartNS_Utility( 4576): usb_denied = 0
I/SmartNS_PSService( 4576): usb notificaiton:true,
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
W/VideoCapabilities( 6377): Unrecognized profile 2130706433 for video/avc
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1212): reapply : com.android.settings 1 36
I/ActivityManager(  967): Killing 6078:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=6078
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/SmartNS_NSReceiver( 4576): Tethered state change:false isNSOpening:false
,I/ActivityManager(  967): Recipient 6078
,D/Process (  967): killProcessQuiet, pid=6053
I/ActivityManager(  967): Killing 6053:com.google.android.partnersetup/u0a27 (adj 15): empty #18
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6053,
,I/vclib   ( 6377): onServiceConnected,
W/Babel   ( 6377): Attempted to change video mute state without an active call.,
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1212): reapply : com.android.settings 1 36
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false
,D/Process (  967): killProcessQuiet, pid=6103
I/ActivityManager(  967): Killing 6103:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  967): Recipient 6103
,D/wpa_supplicant( 1348): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1348): EAPOL: disable timer tick
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false
,D/FlexNetS( 6208): updateSvcAllowedInSettings:false,
,I/dhcpcd  ( 6467): wlan0: sending REQUEST (xid 0x2b3fc65e), next in 2.17 seconds,
,I/dhcpcd  ( 6467): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
,D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  967): handleMessage: E msg.what=131212
,E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  967):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
,I/dhcpcd  ( 6467): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6467): autoip env[11]:autoip=DISABLE
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
,E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState,
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  967): handleMessage: X
,I/dhcpcd  ( 6467): bind_interface: daemonise
,D/Messaging( 6438): supportCMAS(SIE)/init? false/true
,D/MmsConfig( 6438): networkCode: 
D/MessageCustFlag( 6438): sku_id=118
D/MmsConfig( 6438): SIE smsPri: null
D/MmsConfig( 6438): networkCode: 
,D/MmsConfig( 6438): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 6438): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 6438): ,
D/MmsAsyncWorkHandler( 6438): HM tk = 20001
D/ReportIndicatorCache( 6438): MSG_QUERY_REPORTS >>,
D/SettingsManager( 6438): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3f5fd669
D/Messaging( 6438): mNeedToUpdateDate2 start
,D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 98
D/AccFlag ( 1547): sku_id=118
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967): handleMessage: E msg.what=196613
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1348): Power_Mode_Type mode = 0
I/wpa_supplicant( 1348): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/PMS     (  967): releaseWL(31ef9599): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiDataStallTracker(  967): setDhcpActive: false
E/WifiStateMachine(  967): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  967): WifiStateMachine DHCP successful
E/WifiStateMachine(  967): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  967): link address 192.168.1.130/24
D/WifiP2pService(  967): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  967): gateway: /192.168.1.1
,W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1348): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1348): htc_wext_set_keepalive +
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/wpa_supplicant( 1348): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1348): getPrivFuncNum +	
I/wpa_supplicant( 1348): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1348): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1348): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1348): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1348): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131210
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 85
E/WifiStateMachine(  967):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SIGNAL_POLL'
D/MmsSmsV2Provider( 1547):  slotId = -1000
D/MmsAsyncWorkHandler( 6438): 
D/MmsAsyncWorkHandler( 6438): HM tk = 20002
D/MmsSmsV2Provider( 1547): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
I/wpa_supplicant( 1348): environment dirty rate=0 [7][0][0]
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
,E/WifiConfigStore(  967): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1348): wlan0: Control interface command 'BLACKLIST clear'
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/wpa_supplicant( 1348): wlan0: BLACKLIST CLEAR 
D/WIFI_ICON( 1212): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiMonitor(  967): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/ConnectivityService(  967): Adding iface wlan0 to network 101
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=54 dispatchEvent: BLACKLIST CLEAR 
V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -60, 3
D/HtcWifiWanDetect(  967): WAN detection
E/WifiStateMachine(  967): NetworkAgent != null
D/HtcWifiWanDetect(  967): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  967): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/DraftCache( 6438): [DraftCache/1] DraftCache.constructor
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
D/DraftCache( 6438): [DraftCache/1] refresh
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
E/WifiStateMachine(  967): transitionTo: destState=ConnectedState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
I/IntentController( 1212): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  967): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 26
,D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54,
D/MmsSmsV2Provider( 1547):  slotId = -1000
D/MmsSmsV2Provider( 1547): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/WISPrService( 4576): >>>>>WISPrService start isConnected = true<<<<<,
D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1212): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  967): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/ConnectivityService(  967): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine(  967): handleMessage: X
D/ConnectivityService(  967): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  967): handleMessage: E msg.what=131131
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  967): processMsg: ConnectModeState
I/Messaging( 6438): mccmnc> 
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine(  967): handleMessage: X
D/ConnectivityService(  967): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  967): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/ConnectivityService(  967): Setting Dns servers for network 101 to [/192.168.1.1]
D/AccFlag ( 1547): sku_id=118
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 4576): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/Nat464Xlat(  967): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  967): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967): currentScore = 0, newScore = 20
,D/ConnectivityService(  967):    accepting network in place of null
D/ConnectivityService(  967): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  967): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Connected
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
D/WIFI    (  967): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/MmsConfig( 6438): networkCode: 
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  967): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  967): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 85
D/MmsSmsV2Provider( 1547):  slotId = -1000
D/MmsSmsV2Provider( 1547): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/ConnectivityService(  967): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  967): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
V/NetworkPolicy(  967): ensureActiveMobilePolicyLocked()
D/PMS     (  967): acquireWL(459934b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
D/Tethering(  967): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  967): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/DATA_ICON( 1212): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
,D/NetworkPolicy(  967): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
V/NetworkPolicy(  967): updateIfacesLocked()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
V/NetworkPolicy(  967): updateNotificationsLocked()
,D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/Messaging( 6438): ViewCache CreatePreloadOnlyConversationList
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1212): CM callback handler got msg 524290
D/DATA_ICON( 1212): dataConnected: false/false
D/ConnectivityService(  967): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 98
D/ConnectivityService(  967): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/MmsSmsV2Provider( 1547):  slotId = -1000
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/MmsSmsV2Provider( 1547): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  967): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/PMS     (  967): releaseWL(459934b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/Messaging( 6438): mNeedToUpdateDate2: false
I/SecurityController( 1212): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityManager.CallbackHandler( 1212): CM callback handler got msg 524290
D/WIFI    (  967): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/SecurityController( 1212): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateNotificationsLocked()
D/ConnectivityManager.CallbackHandler(, 1212): CM callback handler got msg 524290
D/PhoneStorageUtil( 6438): HtcWrapEnvironment.getSupportedStorages() >1,
D/PhoneStorageUtil( 6438): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/DATA_ICON( 1212): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/PhoneStorageUtil( 6438): createReceiver
I/SecurityController( 1212): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/AccFlag ( 1547): sku_id=118
,D/Messaging( 6438): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/DATA_ICON( 1212): dataConnected: false/false
D/StatusBar.NetworkController( 1212): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/QuickSettingWifi( 1212): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1212): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,D/MessageCustFlag( 6438): sense_version=6.0
,D/TelephUtils( 1547): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 85
,V/MmsProvider( 1547): Update uri=content://mms, match=0
V/MmsProvider( 1547): selection=st=129 AND m_type!=134
,D/Jerry   ( 6438): start to preload cursor >>>>>>>
,D/Messaging( 6438): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6438): TransactionService is going to be woken up.
,D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/MmsSmsV2Provider( 1547):  slotId = -1000
,V/TransactionService( 6438): 1-Creating TransactionService
,D/DraftCache( 6438): [DraftCache/156] rebuildCache
,D/Messaging( 6438): ViewCache CreatePreload
D/Messaging( 6438): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/Jerry   ( 1547): URI_DRAFT
,V/TransactionService( 6438): onStartCommand: 1
D/MmsSystemEventReceiver( 6438): unRegisterForConnectionStateChanges
V/TransactionService( 6438): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6438): Loading previous transactions.
,D/DraftCache( 6438): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 6438): [DraftCache/156] rebuildCache time: 2
,D/Cust_MMSMS( 6438): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6438): def_index: 0
,D/MsgPreferenceUtils( 6438): globalIndex = 1
,D/MsgPreferenceUtils( 6438): phone state: true
D/MsgPreferenceUtils( 6438): sd state: false
,D/MsgPreferenceUtils( 6438): vIndex = 0
D/TelephUtils( 1547): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/AccFlag ( 1547): device_type: 1
,D/TransactionService( 6438): Force clearing mTransactionList,
,D/TransactionService( 6438): Force set service start id to 1
,V/TransactionService( 6438): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6438): unRegisterForConnectionStateChanges
D/TransactionService( 6438): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 6438): Destroying TransactionService
V/TransactionService( 6438): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/AlarmManager(  967): [AlarmQueuing] connectivity wifi: false
,D/htcCheckinService(  967): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/PMS     (  967): acquireWL(3ddb50f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  967): acquireWL(b2ad99c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 967 1000 null
,D/PMS     (  967): releaseWL(b2ad99c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  967): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  967): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true,
,I/ConnectivityHelper( 1611): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  967): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6527 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  967): No APN found to select.
,D/PMS     (  967): releaseWL(3ddb50f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6402): [cf3.1.]  listen tmrbb8,
,D/MdScDataSum( 6402): [cf3.1.] summary 118:p1 ignore
,I/MusicStore( 6527): Database version: 120,
,D/VoldConnector(  967): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6527): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  967): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6527): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  967): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6527): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6527): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6527): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6527): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6527): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bf81837: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,W/ActivityThread( 6527): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 6527): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6527): GMSCore installation verified
,I/ConfigStore( 6527): Config Database version: 1
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6527, uid=10159, userID:0,
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
,D/WifiDisplayAdapter(  967):     IP Address: }
,D/MediaRouterService(  967): Client com.google.android.music (pid 6527): Registered
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
,I/MediaRouter( 6527): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,D/PMS     (  967): releaseWL(b933d44): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  967): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/MusicLeanback( 6527): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6527): type=WIFI subType= reason=null isConnected=true,
,I/art     (  967): Explicit concurrent mark sweep GC freed 53078(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.882ms total 139.012ms,
,I/NetworkMonitor( 6527): type=WIFI subType= reason=null isConnected=true
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6527, uid=10159, userID:0
,D/AutoSetting( 1532): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6566 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/AutoSetting( 1532): service - onCreate()
,I/GHttpClientFactory( 6527): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6527): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1532): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1532): service - onStartCommand() screen is off, don't request location
D/LocationManagerService(  967): request 34d3084d passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/Process (  967): killProcessQuiet, pid=5125
I/ActivityManager(  967): Killing 5125:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PhoneMonitor( 6566): Register our PhoneStateListener
,I/ActivityManager(  967): Recipient 5125
,D/MobileConnectivityChangeReceiver( 6566): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
,D/MobileConnectivityChangeReceiver( 6566): onReceive CONNECTIVITY_CHANGE networkType=1
,D/Process (  967): killProcessQuiet, pid=6132
,I/ActivityManager(  967): Killing 6132:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 6566): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6566): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  967): Recipient 6132
,D/PMS     (  967): acquireWL(365688cf): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2198 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(1ca4b965): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2198 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(365688cf): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 2198): Checking schedule, now: 1452511799824 next: 1452511739054
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2198, uid=10024, userID:0
I/CheckinService( 2198): active receiver: enabled
,I/CheckinService( 2198): Preparing to send checkin request
,D/ChimeraCfgMgr( 2198): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/EventLogService( 2198): Accumulating logs since 1452511704424
,D/ChimeraCfgMgr( 2198): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6597 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/CheckinRequestBuilder( 2198): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  967): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2198): Failed to find provider info for com.google.android.wearable.settings
,D/libc    ( 6377): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6377): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6377): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6377): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6377): [NET] android_getaddrinfo_proxy+
D/libc    ( 6377): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6377): [NET] android_getaddrinfo_proxy-, success
,I/Babel   ( 6377): connection state changed from UNKNOWN to CONNECTED
,I/art     ( 1797): Explicit concurrent mark sweep GC freed 11924(715KB) AllocSpace objects, 3(252KB) LOS objects, 48% free, 4MB/8MB, paused 831us total 44.739ms
,W/Kids    ( 2198): [AccountUtils] Account not ready
W/Kids    ( 2198): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2198): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2198): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2198): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2198): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2198): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2198): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2198): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1212): reapply : com.google.android.gms 3 40
,D/PMS     (  967): acquireWL(dcfc5d5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{4ec7a44: PendingIntentRecord{3a88f72d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=136925, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{77c51ea: PendingIntentRecord{15e05cdb com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=137027, Int=0
,D/WeatherUtility( 1212): Weather sync is On
,W/WeatherTimeKeeper( 1212): [refreshWeatherData] no weather data
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 2198): awaiting user notification for token
,I/RemoteViews( 1212): reapply : com.google.android.gms 2 40
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6622 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/VoldConnector(  967): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/ContextImpl( 6597): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/ResourcesManager( 6622): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6622): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/VoldConnector(  967): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6597): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  967): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,I/GAv4    ( 6597): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6597):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6597):   adb logcat -s GAv4
W/ContextImpl( 6597): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  967): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6597): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/MultiDex( 6622): VM with version 2.1.0 has multidex support,
I/MultiDex( 6622): install
I/MultiDex( 6622): VM has multidex support, MultiDex support library is disabled.
,W/GAv4    ( 6597): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/JNIHelp ( 6622): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/GAv4    ( 6597): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6597): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityThread( 6622): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6622): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c01975: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6622): Installed default security provider GmsCore_OpenSSL
,E/WifiStateMachine(  967): handleMessage: E msg.what=131168
,E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): handleMessage: X
,W/global  ( 6597): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6597): [apache-http] Connection GC has been deprecated!,
,I/WVCdm   (  399): CdmEngine::OpenSession
I/WVCdm   (  399): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  399): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,D/DrmWidevineDash(  399): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  399): Service_Initialize: starts!
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
E/QSEECOMAPI: (  399): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  399): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
,D/QSEECOMAPI: (  399): Loaded image: APP id = 8,
D/DrmWidevineDash(  399): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  399): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  399): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48ff000
E/DrmWidevineDash(  399): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48ff000
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  541): got the req here! ret=0,
,D/DrmLibTime(  541): command id, time_cmd_id = 770
D/DrmLibTime(  541): time_getutcsec starts!
D/DrmLibTime(  541): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  541): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  541): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  541): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  541): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  541): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  541): QSEE Time Listener: Retrieved Android system time: 1452511800
D/DrmLibTime(  541): time_getutcsec returns 0, sec = 1452511800; nsec = 0
D/DrmLibTime(  541): time_getutcsec finished! 
D/DrmLibTime(  541): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  541): before calling ioctl to read the next time_cmd
E/QC-time-services(  475): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  399): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xf3807928
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xab703508, dataLength=8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab725a30, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xab7232a0, idLength=0xff9324b8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xff9324ce, maximum = 0xff9324cf
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
,D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xff93253c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  399): PrepareKeyRequest: nonce=93851899
,D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab68fa40
D/DrmWidevineDash(  399): message_length=1610, signature=0xab81f508, signature_length=0xff93249c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/WebViewFactory( 6597): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6597): Time to load native libraries: 22 ms (timestamps 7733-7755),
,I/LibraryLoader( 6597): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6597): Binding Chromium to main looper Looper (main, tid 1) {26e7d144},
I/LibraryLoader( 6597): Expected native library version number "",actual native library version number ""
,I/chromium( 6597): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6597): Initializing chromium process, singleProcess=true
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
W/art     ( 6597): Attempt to remove local handle scope entry from IRT, ignoring
I/WVCdm   (  399): CdmEngine::CloseSession
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  399): L3 Terminate.
D/DrmWidevineDash(  399): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): Service_Uninitialize: starts!
D/QSEECOMAPI: (  399): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  399): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  399): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  399): OEMCrypto_Terminate: ends! returns 0
,E/SysUtils( 6597): ApplicationContext is null in ApplicationStatus
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
,D/libc    (  967): [NET] android_getaddrinfofornet-, err=8
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  967): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  967): [NET] android_getaddrinfo_proxy+
D/libc    (  967): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  967): [AlarmQueuing] connectivity wifi: true
D/PMS     (  967): acquireWL(182f0dd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
D/PMS     (  967): acquireWL(2f50e531): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 967 1000 null
,I/NetworkMonitor( 6527): type=WIFI subType= reason=null isConnected=true
I/ConnectivityHelper( 1611): [onReceive] WIFI(1): CONNECTED
,D/GpsLocationProvider(  967): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  967): releaseWL(2f50e531): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/GpsLocationProvider(  967): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/htcCheckinService(  967): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,W/chromium( 6597): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/GpsLocationProvider(  967): No APN found to select.,
E/libEGL  ( 6597): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6597): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6597): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6597): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6597): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6597): Local Branch: 
I/Adreno-EGL( 6597): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6597): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6597):                  d74aa161a12b9c6fc6332151
,D/PMS     (  967): releaseWL(182f0dd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6402): [999.1.]  listen tmrbb8
,I/WVCdm   (  399): CdmEngine::OpenSession
I/WVCdm   (  399): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  399): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  967): [NET] android_getaddrinfo_proxy-, success
D/HtcWifiWanDetect(  967): Find DNS Address www.htc.com/104.81.130.175
D/DrmWidevineDash(  399): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  399): Service_Initialize: starts!
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
E/QSEECOMAPI: (  399): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  399): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
,D/MdScDataSum( 6402): [999.1.] summary 118:p1 ignore
,D/QSEECOMAPI: (  399): Loaded image: APP id = 9,
,D/DrmWidevineDash(  399): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  399): qsapps_get_capabilities: Capability from secure side: 0x0
,D/QSAPPSVER(  399): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48ff000
E/DrmWidevineDash(  399): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48ff000
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  541): got the req here! ret=0
,D/DrmLibTime(  541): command id, time_cmd_id = 770
D/DrmLibTime(  541): time_getutcsec starts!
D/DrmLibTime(  541): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  541): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  541): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  541): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  541): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  541): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,D/DrmLibTime(  541): QSEE Time Listener: Retrieved Android system time: 1452511801
D/DrmLibTime(  541): time_getutcsec returns 0, sec = 1452511801; nsec = 0
D/DrmLibTime(  541): time_getutcsec finished! 
D/DrmLibTime(  541): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  541): before calling ioctl to read the next time_cmd
E/QC-time-services(  475): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  399): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xf3807928
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xab726968, dataLength=8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab725a30, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xab7232c0, idLength=0xff9324b8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/AudioManagerAndroid( 6597): Requires BLUETOOTH permission,
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
,D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xff9324ce, maximum = 0xff9324cf
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xff93253c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  399): PrepareKeyRequest: nonce=4052055562
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab6de188
D/DrmWidevineDash(  399): message_length=1646, signature=0xab702cb8, signature_length=0xff93249c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/NSApplication( 6597): Starting up...
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6692 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  399): CdmEngine::CloseSession
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  399): L3 Terminate.
D/DrmWidevineDash(  399): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): Service_Uninitialize: starts!
D/QSEECOMAPI: (  399): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  399): QSEECom_shutdown_app, app_id = 9
,D/DrmWidevineDash(  399): Service_Uninitialize: ends! returns 0x0,
D/DrmWidevineDash(  399): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6715): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6715): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6715): dex2oat: override thread count:4
,I/dex2oat ( 6715): dex2oat took 85.574ms (threads: 4)
,I/Adreno-EGL( 6622): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6622): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6622): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6622): Local Branch: 
I/Adreno-EGL( 6622): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6622): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6622):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6622): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6622): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6622): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6622): Local Branch: 
I/Adreno-EGL( 6622): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6622): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6622):                  d74aa161a12b9c6fc6332151
,D/Process (  967): killProcessQuiet, pid=5023
I/ActivityManager(  967): Killing 5023:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  967): Recipient 5023
D/WifiService(  967): Client connection lost with reason: 4
,D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/PMS     (  967): acquireWL(27d84ec6): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): releaseWL(dcfc5d5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
D/libc    ( 1797): [NET] android_getaddrinfofornet-, err=8
D/GCM     ( 1797): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1797): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1797): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1797): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1797): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,V/GmsCoreStatsServiceLauncher( 2198): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/CheckinRequestBuilder( 2198): Classify the device as Phone.
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1797): [NET] android_getaddrinfo_proxy-, success
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2198, uid=10024, userID:0,
,I/ActivityManager(  967): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6732 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,V/MusicLeanback( 6527): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1797): [NET] android_getaddrinfofornet-, err=8
,D/LocationInitializer( 2198): Restart initialization of location
,D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1797): [NET] android_getaddrinfofornet-, err=8
,D/AutoSetting( 1532): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 6566): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6566): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1532): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/PMS     (  967): acquireWL(d29cf95): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2198 10024 WorkSource{10024 com.google.android.gms}
D/AutoSetting( 1532): service - onStartCommand() screen is off, don't request location
,D/PMS     (  967): releaseWL(d29cf95): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,W/ResourcesManager( 6732): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6732): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6732): VM with version 2.1.0 has multidex support
,I/MultiDex( 6732): install
I/MultiDex( 6732): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6732): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6732): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6732): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c01975: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6732): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1797): Connected,
D/PMS     (  967): acquireWL(3a4af8aa): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): releaseWL(27d84ec6): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WearableService( 6732): callingUid 10024, callindPid: 6732
,D/PMS     (  967): releaseWL(3a4af8aa): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(272bdc9b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1797): Message class com.google.f.a.a.p
,D/libc    ( 2198): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 2198): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 2198): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2198, uid=10024, userID:0
D/libc    ( 2198): [NET] android_getaddrinfofornet-, pass to proxy
D/PMS     (  967): releaseWL(272bdc9b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 2198): [NET] android_getaddrinfo_proxy+
,D/libc    ( 2198): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ChimeraCfgMgr( 2198): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/MDM     ( 1866): [161] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 2198): [NET] android_getaddrinfo_proxy-, success,
D/ChimeraCfgMgr( 2198): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc    ( 2198): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 2198): [NET] android_getaddrinfofornet-, err=8
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/GCM     ( 1797): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AuthorizationBluetoothService( 1797): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2198): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2198, uid=10024, userID:0
,E/MDM     ( 1866): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Kids    ( 2198): [AccountUtils] Account not ready
W/Kids    ( 2198): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2198): 	,at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2198): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2198): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2198): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2198): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2198): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2198): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2198): 	at java.lang.Thread.run(Thread.java:818)
,D/libc    ( 2198): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 2198): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 2198): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 2198): [NET] android_getaddrinfofornet-, err=8
D/LocationInitializer( 2198): Restart initialization of location
,I/CheckinTask( 2198): Sending checkin request (8418 bytes)
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
,I/art     (  967): Explicit concurrent mark sweep GC freed 19625(925KB) AllocSpace objects, 4(272KB) LOS objects, 33% free, 16MB/24MB, paused 1.508ms total 152.182ms,
,I/RemoteViews( 1212): reapply : com.google.android.gms 3 40,
,I/CheckinRequestBuilder( 2198): Checkin reason type: 8 attempt count: 1,
,I/ActivityManager(  967): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2198): Failed to find provider info for com.google.android.wearable.settings,
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 2198): awaiting user notification for token,
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
I/CheckinRequestBuilder( 2198): Classify the device as Phone.
I/RemoteViews( 1212): reapply : com.google.android.gms 3 40,
,I/CheckinTask( 2198): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2198): Checking schedule, now: 1452511802989 next: 1453048634985,
I/CheckinService( 2198): active receiver: disabled
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2198, uid=10024, userID:0
,I/CheckinService( 2198): Checking schedule, now: 1452511803016 next: 1453048634985
,I/CheckinService( 2198): active receiver: disabled
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2198, uid=10024, userID:0
,D/PMS     (  967): releaseWL(1ca4b965): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,V/SetupWizard( 6566): Connected to Gservices successfully
,D/ChimeraCfgMgr( 2198): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 2198): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1797): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
,I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 2198): [AccountUtils] Account not ready,
W/Kids    ( 2198): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2198): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2198): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2198): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2198): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2198): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2198): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2198): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2198): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1212): reapply : com.google.android.gms 2 40
,D/PMS     (  967): acquireWL(90fdb9): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6527 10159 null
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6527, uid=10159, userID:0
,D/PMS     (  967): releaseWL(90fdb9): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6527): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6527): Stop autocaching.
,E/GmsUtils( 6527): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6527): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/jxcore-log( 6320): Test app app.js loaded,
I/jxcore-log( 6320): 
,I/chromium( 6320): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  967): Killing 6020:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=6020
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  967): Recipient 6020
,D/Process (  967): killProcessQuiet, pid=5463
,I/ActivityManager(  967): Killing 5463:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5463
,D/Process (  967): killProcessQuiet, pid=6185,
I/ActivityManager(  967): Killing 6185:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.appDiedLocked:5130 
,I/ActivityManager(  967): Recipient 6185,
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  967): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  967): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  967): acquireWL(174847f3): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 967 1000 null
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  967): [NET] android_getaddrinfofornet-, err=8
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  967): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  967): [NET] android_getaddrinfo_proxy+
D/libc    (  967): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfo_proxy-, success
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
,D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  967): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/AccTypeManager( 1757): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,W/SystemReader(  967): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1757): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  967): acquireWL(28b993ba): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6377 10112 null,
,I/Prism.ItemManager( 1611): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1611): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1611): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/ResourcesManager(  967): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/Launcher( 1611): Deferring update until onResume,
,D/Launcher( 1611): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1757): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1547): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  967): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6786 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,E/ExternalAccountType( 1757): Unsupported attribute readOnly
,D/PMS     (  967): releaseWL(28b993ba): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6377): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6377): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6377): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/PackageManager(  967): Unable to load service info ResolveInfo{212a7541 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  967): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  967): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  967): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  967): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  967): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  967): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  967): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  967): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  967): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  967): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  967): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,W/System  ( 6377): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6377): Installed default security provider GmsCore_OpenSSL
,D/GpsLocationProvider(  967): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  967): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  967):  [handleDownloadXtraData]inject done.
,D/PMS     (  967): acquireWL(865e607): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
,D/PMS     (  967): releaseWL(174847f3): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,I/BackupManagerService(  967): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,V/GmsNetworkLocationProvi( 1866): DISABLE
,I/GCoreNlp( 1866): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  967): acquireWL(1dbc6363): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1866 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): releaseWL(1dbc6363): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(1110ab60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1866 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): releaseWL(1110ab60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationManagerService(  967): getProviders()=[passive]
,D/GpsLocationProvider(  967): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  967): releaseWL(865e607): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/LocationProviderProxy(  967): applying state to connected service
D/LocationProviderProxy(  967): applying state to connected service
,D/PMS     (  967): acquireWL(1c51d8c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1866 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(36366cd5): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): releaseWL(1c51d8c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(36366cd5): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  967): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6815 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/art     (  429): Explicit concurrent mark sweep GC freed 8674(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 137us total 18.306ms
,I/[PluginManager]RegisterService( 1532): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1532): handle notify Blinkfeed plugin client changed
,I/art     (  429): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 122us total 16.242ms
,I/art     (  429): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 116us total 15.705ms
,I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6838 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6838, uid=10072, userID:0,
,W/global  ( 6838): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 6838): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 6838): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6838): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6838): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  967): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6877 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 6838): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 6838): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6838, uid=10072, userID:0
,W/ResourcesManager( 6877): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6877): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6838): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6838): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6838): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 6877): VM with version 2.1.0 has multidex support
,I/MultiDex( 6877): install
I/MultiDex( 6877): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6838): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 2198): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/PMS     (  967): acquireWL(27ad3545): PARTIAL_WAKE_LOCK  AsyncService 0x1 5537 10167 null,
,I/PackageBroadcastService( 2198): Null package name or gms related package.  Ignoreing.,
D/PMS     (  967): releaseWL(27ad3545): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  967): acquireWL(b9c71cb): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5537 10167 null
,V/JNIHelp ( 6877): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/UpdateIcingCorporaServi( 6786): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,W/ActivityThread( 6877): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6877): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c01975: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6877): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1797): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,I/UpdateIcingCorporaServi( 6786): UpdateCorporaTask done [took 118 ms] updated apps [took 118 ms] ,
,I/art     (  967): Explicit concurrent mark sweep GC freed 22078(1242KB) AllocSpace objects, 4(220KB) LOS objects, 33% free, 16MB/25MB, paused 1.665ms total 161.471ms
D/PMS     (  967): acquireWL(1050b066): PARTIAL_WAKE_LOCK  Icing 0x1 2198 10024 WorkSource{10024 com.google.android.gms}
D/Process (  967): killProcessQuiet, pid=6239
D/PMS     (  967): releaseWL(b9c71cb): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  967): Killing 6239:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/Icing   ( 2198): updateResources: need to parse f{com.google.android.gms},
,I/art     ( 1797): Explicit concurrent mark sweep GC freed 16780(943KB) AllocSpace objects, 14(1048KB) LOS objects, 49% free, 4MB/8MB, paused 1.172ms total 70.254ms
,D/PMS     (  967): releaseWL(1050b066): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  967): Recipient 6239
,D/WifiService(  967): Client connection lost with reason: 4
,D/PMS     (  967): acquireWL(1cfe5fa7): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024},
V/AlarmManager(  967): sending alarm PendingIntent{3b9dcc54: PendingIntentRecord{1369c7fd com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=148011, Int=0
,D/AuthorizationBluetoothService( 1797): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2198): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,D/WearableService( 6732): callingUid 10024, callindPid: 6732
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2198, uid=10024, userID:0
,E/MDM     ( 1866): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/LocationInitializer( 2198): Restart initialization of location
,D/PMS     (  967): releaseWL(1cfe5fa7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,I/Prism.ItemManager( 1611): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1611): loadItems() com.htc.launcher.pageview.WidgetManager@8414031 +
I/Prism.WidgetManager( 1611): onLoadItems() +
,V/Finsky  ( 6838): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/ResourcesManager( 1611): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/PMS     (  967): acquireWL(2bf6f284): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10072},
D/Finsky  ( 6838): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  967): sending alarm PendingIntent{c21aa6d: PendingIntentRecord{1ab0ecad com.android.vending startService}}, i=null, t=0, cnt=1, w=1452511811554, Int=0
,D/PMS     (  967): releaseWL(2bf6f284): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1611): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Finsky  ( 6838): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6838): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/asset   ( 1611): Copying FileAsset 0x55973bedc0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,D/PhoneApp( 1547): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1547): -- N1 =0,
,D/PhoneApp( 1547): -- N2 =0
D/PhoneApp( 1547): -- N3 =0
,E/Prism.WidgetManager( 1611): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1611): onLoadItems() -
,I/Prism.ItemManager( 1611): loadItems() com.htc.launcher.pageview.WidgetManager@8414031 -
,E/AndroidHttpClient( 6838): Leak found,
E/AndroidHttpClient( 6838): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 6838): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 6838): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 6838): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 6838): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 6838): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 6838): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 6838): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 6838): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 6838): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
,E/AndroidHttpClient( 6838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 6838): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 6838): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 6838): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 6838): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 6838): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 6838): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6838): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6838): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6838): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6838): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1866): client connected with version: 7571000,
,D/Process (  967): killProcessQuiet, pid=5889,
I/ActivityManager(  967): Killing 5889:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5889
,I/ActivityManager(  967): Killing 6438:com.htc.sense.mms/u0a64 (adj 15): empty #17,
,D/Process (  967): killProcessQuiet, pid=6438
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6438
,D/Process (  967): killProcessQuiet, pid=6272,
I/ActivityManager(  967): Killing 6272:com.htc.mobiledata/u0a46 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6272
,D/PMS     (  967): acquireWL(2da639bd): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10072}
V/AlarmManager(  967): sending alarm PendingIntent{3a8c5bb2: PendingIntentRecord{f5f7703 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452511826807, Int=0
D/PMS     (  967): releaseWL(2da639bd): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 6838): [687] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 6838): [1] 5.onFinished: Installation state replication succeeded.,
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/ContactMessageStore( 1547): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1547): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1532): service - handleMessage() stop self
,D/AutoSetting( 1532): service - handleMessage() quit looper,
D/AutoSetting( 1532): service - onDestroy() END
,E/WifiStateMachine(  967): handleMessage: E msg.what=131165
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0,
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): handleMessage: X
,D/PMS     (  967): acquireWL(313ac680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(313ac680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED,
,D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): handleMessage: E msg.what=155652
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DeviceActiveState
,D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1212): closing low battery warning: level=100
D/WifiController(  967): processMsg: DefaultState
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): << updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3392): Disconnected process message: 10, size: 0
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1547): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 5
,E/WifiStateMachine(  967): handleMessage: E msg.what=131326
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState what:131326 2 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  967): handleMessage: X
,D/PMS     (  967): acquireWL(2581b4b9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{4ec7a44: PendingIntentRecord{3a88f72d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=196925, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{26b5704c: PendingIntentRecord{2a402895 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452511870162, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{3d6080fe: PendingIntentRecord{bd8805f android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=208052, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{2ac5caac: PendingIntentRecord{26ffe375 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190730, Int=0
,D/PMS     (  967): acquireWL(33bfaf0a): PARTIAL_WAKE_LOCK  *backup* 0x1 967 1000 null
,W/BackupManagerService(  967): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  967): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  967): releaseWL(33bfaf0a): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  967): acquireWL(1baec37b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(2581b4b9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1212): Weather sync is On
,W/WeatherTimeKeeper( 1212): [refreshWeatherData] no weather data
,D/PMS     (  967): acquireWL(351ae598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(1baec37b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  967): releaseWL(351ae598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): acquireWL(23ef1562): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(23ef1562): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(111c26f3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(2fcccfb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(312d25ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(111c26f3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(1c2736dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(1c2736dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1797): Vacuum at: now=1452511871456 tag=VacuumService
,I/GoogleURLConnFactory( 1797): Using platform SSLCertificateSocketFactory
,D/PMS     (  967): releaseWL(2fcccfb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(399193e5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1797): No account for auth token provided
,D/PMS     (  967): releaseWL(399193e5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): acquireWL(2629eeba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(2629eeba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1797): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1797): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 1797): [NET] android_getaddrinfo_proxy+
D/libc    ( 1797): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1797): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1797): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1797): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1797): No account for auth token provided,
,W/Uploader( 1797): No account for auth token provided,
,W/Uploader( 1797): No account for auth token provided,
,W/Uploader( 1797):  no longer exists, so no auth token.,
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1797): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1797): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1797): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1797): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1797): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1797): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1797): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1797): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1797): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1797): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1797): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1797): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1797): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1212): reapply : com.google.android.gms 3 40,
,D/PMS     (  967): releaseWL(312d25ae): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(3384565e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(3384565e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(2c5d9a3f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(2c5d9a3f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1212): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcUPManager( 1212): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1532): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@23d492c8
,I/ActivityManager(  967): Killing 6402:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=6402
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6402
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  967): acquireWL(34940f0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
D/UsbnetService(  967): BroadcastReceiver::onReceive+
I/BatteryService(  967): n_update end
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): releaseWL(34940f0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: E msg.what=155652
D/HtcPowerSaver(  967): updateBatteryInfo
D/WifiController(  967): processMsg: DeviceActiveState
D/PMS     (  967): runPSCheck
D/WifiController(  967): processMsg: StaEnabledState
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): >> updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  967): handleMessage: X
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1212): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3392): Disconnected process message: 10, size: 0
D/PowerUI ( 1212): closing low battery warning: level=100
D/PowerUI ( 1212): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1212): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  462): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6320): --= Surplus to requirements =--
I/jxcore-log( 6320): 
,I/jxcore-log( 6320): ****TEST TOOK:  ms ****
I/jxcore-log( 6320): 
I/jxcore-log( 6320): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6320): 
,E/cutils-trace( 6936): Error opening trace file: Permission denied (13),
,D/CustomizationManager( 6936): ====startRecUseTime====,
D/htc.customization.log.level( 6936):  is 
W/CustomizationLogLevel( 6936): Level value is invalid, use default level 2
,D/CustomizationManager( 6936):  Read ACC file spent 0.067 (s)
D/CIDMapFileReader( 6936): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6936): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6936): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6936): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6936): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6936): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6936): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 6936): full path : /system/customize/CID/HTC__102.xml,
I/CustomizationCIDLoader( 6936): Parsing tag category name = system
,I/CustomizationCIDLoader( 6936): Parsing tag category name = application
,I/CustomizationCIDLoader( 6936): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 6936): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6936): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6936): Parsing tag category name = Settings,
I/CustomizationCIDLoader( 6936): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 6936): add string-array item, value = 42507,
I/CustomizationCIDLoader( 6936): add string-array item, value = 21902
I/CustomizationCIDLoader( 6936): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6936): add string-array item, value = 23420
I/CustomizationCIDLoader( 6936): add string-array item, value = 22299
I/CustomizationCIDLoader( 6936): add string-array item, value = 24002,
I/CustomizationCIDLoader( 6936): add string-array item, value = 23210
I/CustomizationCIDLoader( 6936): add string-array item, value = 23205
I/CustomizationCIDLoader( 6936): add string-array item, value = 23806
I/CustomizationCIDLoader( 6936): add string-array item, value = 23430
,I/CustomizationCIDLoader( 6936): add string-array item, value = 23408
I/CustomizationCIDLoader( 6936): add string-array item, value = 27205
I/CustomizationCIDLoader( 6936): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6936): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6936): add string-array item, value = 26006:D:1:0
,I/CustomizationCIDLoader( 6936): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6936): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6936): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6936): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6936): add string-array item, value = 23205:D:0:0
,I/CustomizationCIDLoader( 6936): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6936): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6936): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6936): add string-array item, value = 27205:C:1:0
,D/CustomizationManager( 6936):  Read CID file spent 0.126 (s)
D/CustomizationManager( 6936):  All configurations done spent 0.126 (s)
,D/PackageManager(  967): deletePackageAsUser: pkg=com.test.thalitest, pid=6936, uid=2000 userid=0,
,I/ActivityManager(  967): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
,I/ActivityManager(  967): Killing 6320:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  967): killProcessQuiet, pid=6320
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  967): Skipping PackageSetting{32d8ee9b com.example.hello/10374} due to missing metadata
,E/InputEventReceiver( 1387): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1a35bf98 uid 10366 pid 6320} (c)'
I/ActivityManager(  967): Recipient 6320
I/WindowState(  967): WIN DEATH: Window{40704ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  967): Client connection lost with reason: 4
,I/ActivityManager(  967):   Force finishing activity ActivityRecord{3247b911 u0 com.test.thalitest/.MainActivity t8},
,W/ActivityManager(  967): Spurious death for ProcessRecord{2ee84055 6320:com.test.thalitest/u0a366}, curProc for 6320: null,
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
,D/DotMatrix( 1306): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1306): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  967): acquireWL(133b7a6a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1866): Ignoring removeGeofence because network location is disabled.,
D/AccTypeManager( 1757): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  967): releaseWL(133b7a6a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/SystemReader(  967): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1757): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/VoicemailCleanupService( 1702): Cleaning up data for package: com.test.thalitest
,I/[PluginManager]RegisterService( 1532): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,D/PhoneApp( 1547): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
D/AccTypeManager( 1757): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/[PluginManager]RegisterService( 1532): handle notify Blinkfeed plugin client changed
I/art     ( 1611): Explicit concurrent mark sweep GC freed 23619(1411KB) AllocSpace objects, 7(492KB) LOS objects, 34% free, 29MB/45MB, paused 896us total 98.749ms
,D/Prism.PackageStateRece_( 1611): action: android.intent.action.PACKAGE_REMOVED
,I/Prism.ItemManager( 1611): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1611): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/InputMethodManagerService(  967): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/Launcher( 1611): Deferring update until onResume,
D/Launcher( 1611): waitUntilResume // bindAppsRemoved
,E/ExternalAccountType( 1757): Unsupported attribute readOnly
,I/ActivityManager(  967): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6956 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,W/ResourcesManager(  967): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  967): Explicit concurrent mark sweep GC freed 33930(2036KB) AllocSpace objects, 3(124KB) LOS objects, 33% free, 16MB/25MB, paused 1.424ms total 200.889ms
I/art     (  967): WaitForGcToComplete blocked for 166.580ms for cause Explicit
,D/StatusBarManagerService(  967): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  967): hiding MENU key
,D/StatusBarManagerService(  967): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
W/ContextImpl( 6956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,D/FindExtension( 1611): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/PackageManager(  967): Unable to load service info ResolveInfo{2f6a9988 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  967): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  967): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  967): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  967): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  967): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  967): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  967): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  967): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  967): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  967): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  967): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ThreadedRenderer( 1611): Defer allocateBuffers to drawing time
,W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 6320 uid 10366
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
,I/ActivityManager(  967): Killing 6208:com.htc.bgp/u0a11 (adj 15): empty #17
,D/Process (  967): killProcessQuiet, pid=6208
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/art     (  967): Explicit concurrent mark sweep GC freed 6931(417KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 9.799ms total 157.919ms
,W/asset   (  967): Copying FileAsset 0x55976dedd0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,D/JobSchedulerService(  967): Receieved: android.intent.action.PACKAGE_REMOVED,
,I/ActivityManager(  967): Recipient 6208
,I/PhoneStatusBar( 1212): setImeWindowStatus(false,false)
,D/TaskPersister(  967): removeObsoleteFile: deleting file=8_task.xml
,E/NetworkScheduler.SchedulerReceiver( 1797): Invalid parameter app
D/PMS     (  967): acquireWL(129e9c3a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,E/NetworkScheduler.SchedulerReceiver( 1797): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/PMS     (  967): releaseWL(129e9c3a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PackageBroadcastService( 2198): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2198): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2198): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 2198): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2198): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2198): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  967): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6991 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/LocationSettingsChecker( 2198): Removing dialog suppression flag for package com.test.thalitest,
,D/GOOGLEHELP_CompatibleDatabase( 2198): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 2198): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 2198): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 2198): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 2198): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 2198): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 2198): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 2198): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
D/GOOGLEHELP_CompatibleDatabase( 2198): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 2198): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 2198): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0,
,D/GOOGLEHELP_CompatibleDatabase( 2198): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/PMS     (  967): acquireWL(32fe008c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 2198 10024 null
D/GOOGLEHELP_CompatibleDatabase( 2198): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/PMS     (  967): releaseWL(32fe008c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ConfigFetchService( 2198): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigService( 1797): onCreate
,W/BaseAppContext( 2198): Using Auth Proxy for data requests.
,W/BaseAppContext( 2198): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 2198): CP2 sync disabled
,D/PMS     (  967): acquireWL(9ad38b6): PARTIAL_WAKE_LOCK  Icing 0x1 2198 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2198, uid=10024, userID:0
,I/Icing   ( 2198): doRemovePackageData com.test.thalitest
,D/PMS     (  967): releaseWL(9ad38b6): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/GAv4    ( 6991): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6991):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6991):   adb logcat -s GAv4
,W/GAv4    ( 6991): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6991): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 6991): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 6991): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,E/SQLiteDatabase( 6991): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6991): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6991): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6991): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6991): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6991): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6991): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6991): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6991): 	at fdw.e(Unknown Source),
E/SQLiteDatabase( 6991): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6991): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6991): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6991): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6991): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
E/SQLiteDatabase( 6991): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6991): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6991): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6991): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6991): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6991): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6991): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6991): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6991): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6991): 	,at fdy.b(Unknown Source)
E/SQLiteDatabase( 6991): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6991): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6991): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6991): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
W/GAv4    ( 6991): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6991): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 6991): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 6991): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
,E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6991): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6991): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6991): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6991): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6991): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6991): 	at aen.run(PG:536)
,W/GAv4    ( 6991): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 6991): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 6991): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 6991): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6991): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 6991): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6991): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 6991): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,D/VoldConnector(  967): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,E/GAv4    ( 6991): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/CAKEMIX_CRASHED( 6991): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 6991): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 6991): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 6991): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 6991): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 6991): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 6991): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 6991): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ContextImpl( 6991): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,D/PMS     (  967): acquireWL(3ab8bf9a): PARTIAL_WAKE_LOCK  AsyncService 0x1 5537 10167 null
,D/PMS     (  967): releaseWL(3ab8bf9a): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  967): acquireWL(5950a8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5537 10167 null
,W/ResourcesManager( 6991): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6991): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  967): releaseWL(5950a8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,E/SQLiteDatabase( 6991): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6991): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6991): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6991): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6991): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6991): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6991): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6991): 	at aej.c(PG:139)
,E/SQLiteDatabase( 6991): 	at aej.b(PG:398)
E/SQLiteDatabase( 6991): 	at agf.f(PG:417)
E/SQLiteDatabase( 6991): 	at oe.run(PG:1112)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6991): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6991): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 6991): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 6991): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6991): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6991): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6991): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6991): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6991): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6991): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6991): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6991): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 6991): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 6991): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 6991): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 6991): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6991): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6991): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6991): 	at java.lang.Thread.run(Thread.java:818)
,I/UpdateIcingCorporaServi( 6786): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  967): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=7038 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  967): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 6991 on display 0,
,V/JNIHelp ( 6991): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,E/SQLiteLog( 6786): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
E/SQLiteDBG( 6786): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x5596ef15c0
,I/art     ( 6991): Background sticky concurrent mark sweep GC freed 6624(549KB) AllocSpace objects, 4(80KB) LOS objects, 0% free, 5MB/5MB, paused 5.143ms total 41.844ms
,D/Process ( 6991): killProcess, pid=6991
D/Process ( 6991): vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
,W/OpenGLRenderer( 1611): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ActivityManager(  967): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=7059 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,E/SharedPreferencesImpl( 6786): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
,E/AndroidRuntime( 6786): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6786): Process: com.google.android.googlequicksearchbox:search, PID: 6786
E/AndroidRuntime( 6786): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 6786): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 6786): 	,at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 6786): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 6786): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 6786): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 6786): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 6786): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 6786): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 6786): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 6786): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 6786): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6786): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6786): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  967): App crashed! Process: com.google.android.googlequicksearchbox:search
,D/Process ( 6786): killProcess, pid=6786
,D/Process ( 6786): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 ,
,E/DropBoxManagerService(  967): Can't write: system_app_crash
E/DropBoxManagerService(  967): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  967): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  967): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  967): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  967): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  967): 	... 5 more
,I/DeviceManagement( 7038): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7038 dbg=false s=true,
,I/DeviceManagement( 7038): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 7038): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]],
,I/DeviceManagement( 7038): WorkflowService: Starting workflow service
,I/DeviceManagement( 7038): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@2d5878ee] args=[Bundle[mParcelledData.dataSize=112]],
I/DeviceManagement( 7038): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 7038): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 7038): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 7038): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  967): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7084 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager(  967): Recipient 6786
,I/ActivityManager(  967): Process com.google.android.googlequicksearchbox:search (pid 6786) has died
I/ActivityManager(  967): Recipient 6991
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  967): Process com.google.android.apps.docs (pid 6991) has died
,I/DeviceManagement( 7038): BackgroundController: *** Processing package remove for appID=com.test.thalitest,
,I/DeviceManagement( 7038): SessionStateController: Checking invariants...
,I/ActivityManager(  967): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=7106 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,E/SQLiteDatabase( 7084): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7084): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7084): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7084): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7084): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7084): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 7084): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 7084): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 7084): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 7084): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 7084): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 7084): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
,E/SQLiteDatabase( 7084): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 7084): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7084): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7084): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7084): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7084): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7084): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7084): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7084): FATAL EXCEPTION: main
E/AndroidRuntime( 7084): Process: com.android.documentsui, PID: 7084
E/AndroidRuntime( 7084): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7084): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 7084): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 7084): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 7084): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7084): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7084): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7084): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7084): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7084): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7084): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/AndroidRuntime( 7084): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7084): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7084): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7084): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7084): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 7084): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 7084): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 7084): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 7084): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 7084): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 7084): 	... 9 more
,I/ActivityManager(  967): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=7129 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
E/ActivityManager(  967): App crashed! Process: com.android.documentsui
,I/ActivityManager(  967): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=7149 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a
,D/ErrorReport(  967): HtcErrorReportManager Begin---add error logs to dropbox
,W/System.err(  967): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  967): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  967): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  967): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  967): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  967): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  967): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  967): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
,W/System.err(  967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  967): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  967): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  967): 	at libcore.io.Posix.open(Native Method)
W/System.err(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  967): 	... 12 more
,W/ResourcesManager( 7129): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  967): Killing 6597:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=6597
D/GFEEDBACK_SendErrorReportOperation( 2198): Error doing instant send: java.io.IOException: failed to create reports directory
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
E/GFEEDBACK_SendErrorReportOperation( 2198): Error saving report: java.io.IOException: failed to create reports directory
W/System.err(  967): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  967): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  967): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  967): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  967): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  967): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  967): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  967): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  967): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  967): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  967): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  967): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  967): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  967): 	at libcore.io.Posix.open(Native Method)
W/System.err(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  967): 	... 14 more
,W/System.err(  967): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  967): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,W/System.err(  967): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  967): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  967): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  967): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  967): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  967): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  967): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  967): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  967): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
,W/System.err(  967): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  967): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  967): 	at libcore.io.Posix.open(Native Method)
W/System.err(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  967): 	... 14 more
,E/SQLiteDatabase( 7038): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 7038): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 7038): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 7038): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 7038): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 7038): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7038): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 7038): 	,at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7038): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 7038): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 7038): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 7038): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7038): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7038): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7038): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  967): Recipient 6597
,I/Prism.ItemManager( 1611): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1611): loadItems() com.htc.launcher.pageview.WidgetManager@8414031 +
I/Prism.WidgetManager( 1611): onLoadItems() +
,I/DeviceManagement( 7038): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/ResourcesManager( 1611): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Process ( 7084): killProcess, pid=7084
D/Process ( 7084): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  967): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  967): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452511959338.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  967): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  967): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  967): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  967): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  967): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  967): 	... 4 more
,I/DeviceManagement( 7038): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 7038): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,E/SQLiteDatabase( 7038): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185),
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7038): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 7038): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 7038): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 7038): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 7038): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 7038): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 7038): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7038): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7038): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7038): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 7038): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@2d5878ee]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/DeviceManagemen,t( 7038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/DeviceManagement( 7038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
W/DeviceManagement( 7038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/DeviceManagement( 7038): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 7038): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 7038): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 7038): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 7038): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 7038): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 7038): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 7038): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 7038): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 7038): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 7038): WorkflowService: Stopping workflow service
,D/Process (  967): killProcessQuiet, pid=6692
I/ActivityManager(  967): Killing 6692:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/ExternalStorage( 7149): After updating volumes, found 1 active roots
,E/JavaBinder(  967): !!! FAILED BINDER TRANSACTION !!!
,W/ContentService(  967): Found dead observer, removing
,I/ActivityManager(  967): Recipient 7084,
I/ActivityManager(  967): Recipient 6692
,I/ActivityManager(  967): Process com.android.documentsui (pid 7084) has died,
,E/SQLiteDatabase( 7129): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.,
E/SQLiteDatabase( 7129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7129): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
,E/SQLiteDatabase( 7129): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 7129): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 7129): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 7129): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 7129): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7129): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7129): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 7129): Couldn't open MyDB.db for writing (will try read-only):
,E/SQLiteOpenHelper( 7129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 7129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 7129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7129): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7129): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 7129): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 7129): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 7129): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 7129): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 7129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7129): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 7129): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 7129): Opened MyDB.db in read-only mode
,I/GAv4    ( 7106): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7106):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7106):   adb logcat -s GAv4
,W/ResourcesManager( 1611): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/GAv4    ( 7106): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,E/SharedPreferencesImpl( 7106): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7106): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 7106): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7106): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 7106): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7106): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7106): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7106): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7106): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7106): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7106): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7106): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7106): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7106): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7106): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7106): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7106): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7106): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7106): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7106): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7106): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7106): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 7106): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 7106): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,E/SQLiteDatabase( 7106): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7106): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235),
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7106): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7106): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7106): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7106): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7106): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7106): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7106): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7106): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7106): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7106): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7106): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7106): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7106): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7106): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7106): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 7106): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GAv4    ( 7106): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7106): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7106): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7106): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7106): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7106): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7106): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7106): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7106): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7106): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7106): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7106): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7106): 	at aen.run(PG:536)
,W/ActivityManager(  967): Activity pause timeout for ActivityRecord{d533b66 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t9}
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch

```
