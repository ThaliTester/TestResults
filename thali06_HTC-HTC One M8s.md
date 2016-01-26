#### Test 5667282762e056f_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6645): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6645): ====startRecUseTime====
D/htc.customization.log.level( 6645):  is 
W/CustomizationLogLevel( 6645): Level value is invalid, use default level 2
D/CustomizationManager( 6645):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 6645): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6645): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6645): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6645): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6645): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6645): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6645): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6645): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6645): Parsing tag category name = system
I/CustomizationCIDLoader( 6645): Parsing tag category name = application
I/CustomizationCIDLoader( 6645): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6645): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6645): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6645): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6645): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6645): add string-array item, value = 42507
I/CustomizationCIDLoader( 6645): add string-array item, value = 21902
I/CustomizationCIDLoader( 6645): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6645): add string-array item, value = 23420
I/CustomizationCIDLoader( 6645): add string-array item, value = 22299
I/CustomizationCIDLoader( 6645): add string-array item, value = 24002
I/CustomizationCIDLoader( 6645): add string-array item, value = 23210
I/CustomizationCIDLoader( 6645): add string-array item, value = 23205
I/CustomizationCIDLoader( 6645): add string-array item, value = 23806
I/CustomizationCIDLoader( 6645): add string-array item, value = 23430
I/CustomizationCIDLoader( 6645): add string-array item, value = 23408
I/CustomizationCIDLoader( 6645): add string-array item, value = 27205
I/CustomizationCIDLoader( 6645): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6645): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6645):  Read CID file spent 0.105 (s)
D/CustomizationManager( 6645):  All configurations done spent 0.105 (s)
--------- beginning of system
I/ActivityManager(  955): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6645 on display 0
D/PMS     (  955): acquireHCC(69d6861): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 955 1000 null
D/PMS     (  955): acquireHCC(22d92f86): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 955 1000 null
I/ActivityManager(  955): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6663 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1324): [EventService]  onDisplayChanged: 0
V/ActivityManager(  955): Display changed displayId=0
D/DotMatrix( 1324): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1582): [trimMemory] 20
I/WebViewFactory( 6663): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6663): Time to load native libraries: 10 ms (timestamps 223-233),
,I/LibraryLoader( 6663): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6663): Binding Chromium to main looper Looper (main, tid 1) {19d569f9}
,I/LibraryLoader( 6663): Expected native library version number "",actual native library version number ""
,I/chromium( 6663): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6663): Initializing chromium process, singleProcess=true
,W/art     ( 6663): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6663): ApplicationContext is null in ApplicationStatus
,W/chromium( 6663): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6663): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6663): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6663): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6663): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6663): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6663): Local Branch: 
I/Adreno-EGL( 6663): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6663): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6663):                  d74aa161a12b9c6fc6332151
,W/System.err(  955): java.lang.Throwable: stack dump
D/BluetoothManagerService(  955): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  955): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35d9fd6a:true
W/System.err(  955): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  955): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  955): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  955): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6663): 653896885: getState(). Returning 12
,W/art     ( 6663): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6663): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6663): CordovaWebView is running on device made by: HTC
,W/art     ( 6663): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6663): Attempt to remove local handle scope entry from IRT, ignoring
,D/PMS     (  955): acquireWL(fe4a82f): PARTIAL_WAKE_LOCK  *alarm* 0x1 955 1000 WorkSource{1000}
V/AlarmManager(  955): sending alarm PendingIntent{32f41e3c: PendingIntentRecord{318f57c5 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453831017468, Int=0
D/PMS     (  955): acquireWL(2e24951a): PARTIAL_WAKE_LOCK  *backup* 0x1 955 1000 null
D/PMS     (  955): releaseWL(fe4a82f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  955): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  955): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  955): releaseWL(2e24951a): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,W/chromium( 6663): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/HtcSystemUPManager(  955): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  955): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  955): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  955): hiding MENU key
D/StatusBarManagerService(  955): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  955): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  955): hiding MENU key
,D/FindExtension( 6663): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6663): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2730dcab, mServedView=org.apache.cordova.engine.SystemWebView{2a4c3f08 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@5db76a1
,I/InputMethodManagerService(  955): Disable input method client, pid=1582
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/StatusBarManagerService(  955): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6663): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  955): Displayed com.test.thalitest/.MainActivity: +633ms (total +678ms),
,W/BindingManager( 6663): Cannot call determinedVisibility() - never saw a connection for the pid: 6663
,D/JsMessageQueue( 6663): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6663): JniHelper::setJavaVM(0xab4ad8f8), pthread_self() = -1416457192
,I/chromium( 6663): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Process (  955): killProcessQuiet, pid=5893
I/ActivityManager(  955): Killing 5893:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 5893
,W/jxcore-log( 6663): Initializing JXcore engine
W/jxcore-log( 6663): JXcore engine is ready
,W/jxcore-log( 6663): Starting JXcore engine
,D/PMS     (  955): releaseHCC(69d6861): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  955): releaseHCC(22d92f86): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6663): Platform android,
W/jxcore-log( 6663): 
W/jxcore-log( 6663): Process ARCH arm
W/jxcore-log( 6663): 
,I/jxcore-log( 6663): JXcore Cordova bridge is ready!,
I/jxcore-log( 6663): 
W/jxcore-log( 6663): JXcore engine is started
,I/jxcore-log( 6663): Toggling radios to true
I/jxcore-log( 6663): 
,D/BluetoothAdapter( 6663): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  955): ADD_CLIENT: 7
D/WifiService(  955): New client listening to asynchronous messages
,D/WifiManager( 6663): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
W/Settings:Agent(  955): MONITOR_LOG
D/WifiService(  955): setWifiEnabled: true pid=6663, uid=10366
W/Settings:Agent(  955): name: wifi_on
E/WifiService(  955): Invoking mWifiStateMachine.setWifiEnabled,
W/Settings:Agent(  955): value: 2
I/WifiService(  955): isSprintWifiRestricted(): false
W/Settings:Agent(  955): >> traceCallingStack()
I/WifiService(  955): isMdmWifiRestricted(): false
W/Settings:Agent(  955): Process.myPid(): 955
W/Settings:Agent(  955): Process.myTid(): 1745
W/Settings:Agent(  955): Process.myUid(): 1000
W/Settings:Agent(  955): 
W/Settings:Agent(  955): 
W/System.err(  955): java.lang.Throwable: stack dump
,W/System.err(  955): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  955): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  955): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  955): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  955): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  955): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  955): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  955): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  955): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  955): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  955): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  955): 
W/Settings:Agent(  955): << traceCallingStack(): 7(ms)
D/WifiController(  955): handleMessage: E msg.what=155656
D/WifiController(  955): processMsg: DeviceActiveState
D/WifiManager( 6663): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  955): processMsg: StaEnabledState
D/WifiController(  955): handleMessage: X
D/WifiManager( 6663): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  955): handleMessage: E msg.what=131145
I/jxcore-log( 6663): Radios toggled
I/jxcore-log( 6663): 
E/WifiStateMachine(  955): processMsg: ConnectedState
E/WifiStateMachine(  955):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  955): processMsg: L2ConnectedState
I/jxcore-log( 6663): My device name is: HTC-HTC One M8s
I/jxcore-log( 6663): 
E/WifiStateMachine(  955):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1322): wlan0: Cancelling scan request
D/wpa_supplicant( 1322): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1322): TDLS: Tear down peers
D/wpa_supplicant( 1322): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 1322): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 1322): wlan0: Deauthentication notification
D/wpa_supplicant( 1322): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1322): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1322): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1322): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1322): enter disconnect check
I/wpa_supplicant( 1322): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/wpa_supplicant( 1322): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1322): wlan0: Ignore connection failure indication since interface has been put into disconnected state
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  955): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  955): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  955): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  955): interfaceLinkStateChanged wlan0, false
D/Tethering(  955): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  955): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  955): interfaceLinkStateChanged wlan0, false
D/Tethering(  955): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  955): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  955): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  955): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  955): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  955): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  955): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  955): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  955): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  955): acquireWL(d56c5c3): PARTIAL_WAKE_LOCK  NetworkStats 0x1 955 1000 null
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1322): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1322): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1322): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1322): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1322): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55ad767f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1322):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1322): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1322): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1322): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1322): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1322): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1322): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1322): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1322): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1322): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1322): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1322): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1322): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1322): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 1322): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1322): EAPOL: External notification - portValid=0
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1322): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/HTCRequest(  955): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiDisplayAdapter(  955): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  955):     Client/Owner: Client
D/WifiDisplayAdapter(  955):     GroupId: 
D/WifiDisplayAdapter(  955):     Passphrase: 
D/WifiDisplayAdapter(  955):     SessionId: 0
D/WifiDisplayAdapter(  955):     IP Address: }
D/HTCRequest(  955): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1322): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1322): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1322): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1322): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  955): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  955): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  955): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  955): handleMessage: new destination call exit/enter
E/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  955): invokeExitMethods: ConnectedState
E/WifiStateMachine(  955): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  955): release()
E/WifiStateMachine(  955): PerfLock released for exiting ConnectedState
,E/WifiStateMachine(  955): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  955): invokeExitMethods: L2ConnectedState
D/TetherSettings( 4725): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4725): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4725): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4725): Cust_ConnectToPC   : spcsc>false
D/        ( 4725): Cust_ConnectToPC   : IPT>true
D/        ( 4725): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4725): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  955): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/SmartNS_Utility( 4725): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4725): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
E/WifiStateMachine(  955): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  955): handleNetworkDisconnect "NG700" nid=0
D/SmartNS_NSReceiver( 4725): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiConfigStore(  955): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/WifiStateMachine(  955): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  955): releaseWL(d56c5c3): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SAVE_CONFIG'
V/NetworkPolicy(  955): updateNetworkEnabledLocked()
D/wpa_supplicant( 1322): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
V/NetworkPolicy(  955): updateNotificationsLocked()
D/wpa_supplicant( 1322): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1322): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  955): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1322): Power_Mode_Type mode = 0
I/wpa_supplicant( 1322): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1322): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1322): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  955): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  955): setDhcpActive: false
V/NativeCrypto( 1954): Read error: ssl=0x55a98e59f0: I/O error during system call, Connection timed out
D/PMS     (  955): acquireWL(1605ce40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/libc    (  955): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  955): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1954): SSL shutdown failed: ssl=0x55a98e59f0: I/O error during system call, Broken pipe
W/ContextImpl( 4725): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  955): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  955): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  955): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  955): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  955): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  955): NetworkAgent != null
E/WifiStateMachine(  955): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  955): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  955): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  955): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  955): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/ConnectivityService(  955): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1322): wlan0: Control interface command 'SAVE_CONFIG'
D/ConnectivityService(  955): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1322): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1322): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1322): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  955): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  955): DefaultState{ when=-2ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  955): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  955):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  955): Forcing reevaluation
E/WifiStateMachine(  955): Start Disconnecting Watchdog 1
E/WifiStateMachine(  955): handleMessage: X
V/NetworkPolicy(  955): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  955): handleMessage: E msg.what=131146
E/WifiStateMachine(  955): processMsg: DisconnectingState
E/WifiStateMachine(  955):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  955): processM,sg: ConnectModeState
E/WifiStateMachine(  955):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1322): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1322): Fast associate: Old scan results
D/wpa_supplicant( 1322): wlan0: Setting scan request: 0.000000 sec
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  955): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1322): wpa_supplicant_scan enter
D/WifiDataStallTracker(  955): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  955): stopDataStallAlarm 
D/wpa_supplicant( 1322): wlan0: State: DISCONNECTED -> SCANNING
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  955): Validated
D/wpa_supplicant( 1322): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1322): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1322): WPS:  * Version (hardcoded 0x10)
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/wpa_supplicant( 1322): WPS:  * Request Type
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/wpa_supplicant( 1322): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1322): WPS:  * UUID-E
D/wpa_supplicant( 1322): WPS:  * Primary Device Type
D/wpa_supplicant( 1322): WPS:  * RF Bands (3)
D/wpa_supplicant( 1322): WPS:  * Association State
E/WifiTrafficPoller(  955): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/wpa_supplicant( 1322): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1322): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1322): WPS:  * Manufacturer
D/wpa_supplicant( 1322): WPS:  * Model Name
D/wpa_supplicant( 1322): WPS:  * Model Number
E/WifiTrafficPoller(  955): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/wpa_supplicant( 1322): WPS:  * Device Name
D/wpa_supplicant( 1322): WPS:  * Version2 (0x20)
E/WifiDataStallTracker(  955): ENABLE_DATA_MONITOR_POLL false Token 3
D/wpa_supplicant( 1322): P2P: * P2P IE header
D/wpa_supplicant( 1322): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1322): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1322): wlan0: Add radio work 'scan'@0x55ad74a860
D/wpa_supplicant( 1322): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1322): wlan0: Starting radio work 'scan'@0x55ad74a860 after 0.000040 second wait
D/wpa_supplicant( 1322): wlan0: nl80211: scan request
D/wpa_supplicant( 1322): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1322): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/PMS     (  955): releaseWL(1605ce40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1322): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1322): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1322): wlan0: Own scan request started a scan in 0.000079 seconds
I/wpa_supplicant( 1322): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  955): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  955): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  955): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  955): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor(  955): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  955): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=147460
E/WifiStateMachine(  955): processMsg: DisconnectingState
E/WifiStateMachine(  955):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=140184
E/WifiStateMachine(  955): processMsg: ConnectModeState
E/WifiTrafficPoller(  955): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/libc    (  955): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  955):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=140185
D/libc    (  955): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  955): ConnectModeState: Network connection lost 
E/WifiStateMachine(  955): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  955): handleMessage: new destination call exit/enter
E/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  955): invokeExitMethods: DisconnectingState
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  955): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  955): DisconnectedState call setCountryCode()
E/WifiStateMachine(  955):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1322): CTRL_IFACE SET 'pno'='1'
,D/wpa_supplicant( 1322): wlan0: Cancelling scan request
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/SmartNS_Utility( 4725): setISNotification
D/SmartNS_Utility( 4725): usb_cable_connect = 1
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_Utility( 4725): usb_denied = 0
I/SmartNS_PSService( 4725): usb notificaiton:true
D/wpa_supplicant( 1322): wlan0: nl80211: sched_scan request
E/WifiStateMachine(  955): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 4725): usb_cable_connect = 1
,D/SmartNS_Utility( 4725): usb_denied = 0
I/SmartNS_PSService( 4725): usb notificaiton:true
E/WifiStateMachine(  955): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1324): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 4725): Tethered state change:false isNSOpening:false
,D/wpa_supplicant( 1322): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1322): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: Sched scan started
,D/wpa_supplicant( 1322): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,D/wpa_supplicant( 1322): wlan0: nl80211: New scan results available,
D/wpa_supplicant( 1322): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/WifiP2pService(  955): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1322): wlan0: Event SCAN_RESULTS (3) received
D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1322): Got an original EVENT_SCAN_RESULTS
D/WifiP2pService(  955): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1322): wlan0: Scan completed in 0.039181 seconds
D/wpa_supplicant( 1322): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1322): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1322): wlan0: BSS: Remove id 2 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to no match in scan
D/wpa_supplicant( 1322): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1322): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1322): wlan0: Radio work 'scan'@0x55ad74a860 done in 0.039950 seconds,
D/wpa_supplicant( 1322): wlan0: No suitable network found
D/wpa_supplicant( 1322): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1322): wlan0: Cancelling sched scan
D/wpa_supplicant( 1322): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1322): wlan0: Cancelling scan request
D/wpa_supplicant( 1322): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1322): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1322): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1322): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1322): p2p0: New scan results available (own=0 ext=0)
,D/wpa_supplicant( 1322): p2p0: No suitable network found
D/wpa_supplicant( 1322): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1322): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=131101
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  955): processMsg: ConnectModeState
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 9e:93:4e:3e:ba:c5]
,E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 9e:93:4e:3e:ba:c5
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  955): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  955):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  955): processMsg: DriverStartedState
D/WifiMonitor(  955): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=42 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  955): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor(  955): WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  955): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  955):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  955): processMsg: SupplicantStartedState
E/WifiStateMachine(  955):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  955): processMsg: DefaultState
E/WifiStateMachine(  955):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  955): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  955): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=147462
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=140225  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  955): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  955): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  955): processMsg: ConnectModeState
E/WifiStateMachine(  955):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=140225  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=131212
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): processMsg: ConnectModeState
D/DotMatrix( 1324): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  955):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): processMsg: DriverStartedState
E/WifiStateMachine(  955):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): processMsg: SupplicantStartedState
E/WifiStateMachine(  955):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): processMsg: DefaultState
E/WifiStateMachine(  955):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  955): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=131212
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): processMsg: ConnectModeState
E/WifiStateMachine(  955):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): processMsg: DriverStartedState
E/WifiStateMachine(  955):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): processMsg: SupplicantStartedState
E/WifiStateMachine(  955):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): processMsg: DefaultState
E/WifiStateMachine(  955):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  955): Link configuration cha,nged for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  955): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  955): handleMessage: X
D/WifiNetworkAgent(  955): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  955): handleMessage: E msg.what=147462
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=140230  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  955): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  955): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  955): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  955): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  955): NetworkAgent == null
E/WifiStateMachine(  955): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  955): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
I/RemoteViews( 1221): reapply : com.android.settings 1 36
E/WifiStateMachine(  955): processMsg: ConnectModeState
E/WifiStateMachine(  955):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=140234  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=147461
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:53 bcn=0
E/WifiStateMachine(  955): processMsg: ConnectModeState
E/WifiStateMachine(  955):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:53 bcn=0
E/WifiStateMachine(  955): processMsg: DriverStartedState
E/WifiStateMachine(  955):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:53 bcn=0
E/WifiStateMachine(  955): processMsg: SupplicantStartedState
E/WifiStateMachine(  955):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:53 bcn=0
D/WifiStateMachine(  955): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1322): wlan0: Control interface command 'LIST_DONGLES'
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  955): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  955): [1,453,831,027,212 ms] noteScanEnd no scan source
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1322): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  955): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2e73f17 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  955): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  955): NG700 c0:ff:d4:d3:aa:48 rssi=-66 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  955): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  955): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  955):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-66 freq=2412
E/WifiAutoJoinController (  955): Gonzos 38:f8:89:11:e9:11 rssi=-83 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  955): 01ABC c2:ff:d4:d3:aa:48 rssi=-65 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  955): ageScanResultsOut delay 40000 size 5 now 1453831027214
E/WifiAutoJoinController (  955): newSupplicantResults size=5 known=1 true
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1322): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  955): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  955): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  955): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  955): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  955): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  955): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-66,-127) num=(1,0)
E/WifiAutoJoinController (  955): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  955): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  955): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  955): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  955): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-66 freq=2412
D/HtcWifiControlRoamOffload: (  955): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  955): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  955): Done attemptAutoJoin status=3
E/WifiConfigStore(  955):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=131215
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-66 ;0 ,-127] any roam=0 rt=140244
E/WifiStateMachine(  955): processMsg: ConnectModeState
E/WifiStateMachine(  955):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-66 ;0 ,-127] any roam=0 rt=140245
E/WifiStateMachine(  955): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  955): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  955): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiConfigStore(  955): Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
,D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1322): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  955): will read network variables netId=0
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
I/ActivityManager(  955): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6720 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1322): Do not allow key_data field to be exposed
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  955): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  955):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  955): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1322): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1322): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1322): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  955): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/WISPrService( 4725): >>>>>WISPrService start isConnected = true<<<<<
D/wpa_supplicant( 1322): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1322): ENABLE_NETWORK (0)
D/wpa_supplicant( 1322): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1322): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1322): wpa_supplicant_scan enter
D/wpa_supplicant( 1322): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1322): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1322): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1322): WPS:  * Request Type
D/wpa_supplicant( 1322): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1322): WPS:  * UUID-E
D/wpa_supplicant( 1322): WPS:  * Primary Device Type
D/wpa_supplicant( 1322): WPS:  * RF Bands (3)
D/wpa_supplicant( 1322): WPS:  * Association State
D/wpa_supplicant( 1322): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1322): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1322): WPS:  * Manufacturer
D/wpa_supplicant( 1322): WPS:  * Model Name
D/wpa_supplicant( 1322): WPS:  * Model Number
D/wpa_supplicant( 1322): WPS:  * Device Name
D/wpa_supplicant( 1322): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1322): P2P: * P2P IE header
D/wpa_supplicant( 1322): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1322): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1322): wlan0: Add radio work 'scan'@0x55ad74a860
D/wpa_supplicant( 1322): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1322): wlan0: Starting radio work 'scan'@0x55ad74a860 after 0.000027 second wait
D/wpa_supplicant( 1322): wlan0: nl80211: scan request
D/wpa_supplicant( 1322): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1322): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1322): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1322): wlan0: Own scan request started a scan in 0.000060 seconds
I/wpa_supplicant( 1322): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  955): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  955): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  955): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1322): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1322): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1322): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiConfigStore(  955): will read network variables netId=0
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/WifiService(  955): New client listening to asynchronous messages
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiDisplayAdapter(  955): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  955):     Client/Owner: Client
D/WifiDisplayAdapter(  955):     GroupId: 
D/WifiDisplayAdapter(  955):     Passphrase: 
D/WifiDisplayAdapter(  955):     SessionId: 0
D/WifiDisplayAdapter(  955):     IP Address: }
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1322): Do not allow key_data field to be exposed
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/ConnectivityService(  955): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/ConnectivityService(  955):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='engine'
E/WifiTrafficPoller(  955): ADD_CLIENT: 8
D/ConnectivityService(  955): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/Nat464Xlat(  955): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/ConnectivityService(  955): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/ConnectivityService(  955): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1322): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1322): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  955): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
D/NetworkManagementService(  955): Removing idletimer
E/WifiConfigStore(  955):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1322): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1322): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1322): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1322): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1322): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1322): wpa_supplicant_scan enter
D/wpa_supplicant( 1322): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1322): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1322): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  955): setLastSelectedConfiguration -1
E/WifiStateMachine(  955): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  955): handleMessage: new destination call exit/enter
E/WifiStateMachine(  955): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  955): invokeExitMethods: DisconnectedState
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1322): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  955): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  955): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  955): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  955): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  955): DisconnectedState call setCountryCode()
E/WifiStateMachine(  955):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1322): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1322): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1322): wlan0: Cancelling scan request
D/wpa_supplicant( 1322): wlan0: nl80211: sched_scan request
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  955): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  955): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  955): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
I/SecurityController( 1221): onLost 100
D/usbnet  (  955): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  955):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  955): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/PMS     (  955): acquireWL(1ed02ebe): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 955 1000 null
D/CSLegacyTypeTracker(  955): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  955): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/wpa_supplicant( 1322): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1322): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1322): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1322): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1322): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1322): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1322): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1322): wlan0: Scan completed in 0.041252 seconds
D/wpa_supplicant( 1322): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1322): wlan0: BSS: Start scan result update 8
D/wpa_supplicant( 1322): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
D/wpa_supplicant( 1322): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to no match in scan
E/WifiStateMachine(  955): handleMessage: X
D/wpa_supplicant( 1322): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/wpa_supplicant( 1322): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to no match in scan
D/wpa_supplicant( 1322): BSS: last_scan_res_used=0/32
D/WIFI    (  955): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1322): wlan0: New scan results available (own=1 ext=0)
D/WIFI    (  955):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  955): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/wpa_supplicant( 1322): wlan0: Radio work 'scan'@0x55ad74a860 done in 0.042143 seconds
E/ConnectivityService(  955): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/wpa_supplicant( 1322): wlan0: No suitable network found
E/ConnectivityService(  955): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WIFI    (  955): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/WifiP2pService(  955): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1322): wlan0: Setting scan request: 15.000000 sec
D/WifiP2pService(  955): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1322): wlan0: Cancelling sched scan
D/WifiP2pService(  955): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  955): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/PMS     (  955): acquireWL(31d5fb1f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 955 1000 null
D/wpa_supplicant( 1322): nl80211: Sched scan stop sent (ret=0)
D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/wpa_supplicant( 1322): wlan0: Cancelling scan request
V/NetworkPolicy(  955): ensureActiveMobilePolicyLocked()
D/wpa_supplicant( 1322): p2p0: Updating scan results from sibling
W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1322): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1322): p2p0: BSS: Start scan result update 2
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/wpa_supplicant( 1322): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1322): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1322): p2p0: No suitable network found
D/wpa_supplicant( 1322): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/NetworkPolicy(  955): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/wpa_supplicant( 1322): wlan0: nl80211: Sched scan stopped
V/NetworkPolicy(  955): updateNetworkEnabledLocked()
D/wpa_supplicant( 1322): wlan0: Event SCHED_SCAN_STOPPED (38) received
V/NetworkPolicy(  955): updateIfacesLocked()
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
V/NetworkPolicy(  955): updateNotificationsLocked()
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/NetworkManagementService(  955): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  955): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
D/DATA_ICON( 1221): dataConnected: false/false
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiMonitor(  955): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  955): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/PMS     (  955): releaseWL(31d5fb1f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiMonitor(  955): WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
E/WifiMonitor(  955): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  955): handleMessage: E msg.what=147461
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:53 bcn=0
E/WifiStateMachine(  955): processMsg: ConnectModeState
E/WifiStateMachine(  955):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:53 bcn=0
E/WifiStateMachine(  955): processMsg: DriverStartedState
E/WifiStateMachine(  955):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:53 bcn=0
E/WifiStateMachine(  955): processMsg: SupplicantStartedState
E/WifiStateMachine(  955):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:53 bcn=0
D/WifiStateMachine(  955): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/Tethering(  955): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  955): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/wpa_supplicant( 1322): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  955): [1,453,831,027,307 ms] noteScanEnd no scan source
W/WifiHW  (  955): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1322): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  955): handleMessage: X
V/NetworkPolicy(  955): updateNetworkEnabledLocked()
V/NetworkPolicy(  955): updateNotificationsLocked()
E/WifiStateMachine(  955): handleMessage: E msg.what=131131
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  955): processMsg: ConnectModeState
E/WifiStateMachine(  955):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  955): handleMessage: X
W/ResourcesManager( 6720): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/WISPrService( 4725): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4725): trigger connection
D/WISPrService( 4725): continue
D/WISPrService( 4725): start DataConnection
,D/libc    ( 4725): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4725): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4725): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    ( 4725): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4725): [NET] android_getaddrinfo_proxy+
D/libc    ( 4725): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4725): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  955): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6745 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 4725): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4725): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl,
,D/WISPrService( 4725): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4725): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4725): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4725): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/WISPrService( 4725): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4725): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/libc    ( 4725): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4725): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 4725): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri,
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default,
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun,
,D/WifiService(  955): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/MdScPhnSt( 6745): [3f2.2.]  listen tmrbb8
,I/Babel_SMS( 6720): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6720): MmsConfig.loadMmsSettings
,I/ActivityManager(  955): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6781 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6720, uid=10112, userID:0
,D/MdProvGlob( 6594): remove item 101 (p2d27in237) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdScDataSum( 6745): [3f2.2.] summary 118:p2 ignore
,W/Settings( 6720): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6720): startup - clean
,D/Process (  955): killProcessQuiet, pid=6367,
I/ActivityManager(  955): Killing 6367:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/Babel   ( 6720): deleted: false for 0
,W/HtcWrapAdjustableCursorFactory( 6781): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 6781): onCreate,
,I/ActivityManager(  955): Recipient 6367,
,V/GetPrviateResource( 6781): GetPrviateResource,
V/GetPrviateResource( 6781): GetPrviateResource
,D/MmsCustomizationProvider( 6781): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 6781): query uri: content://htc-mms-customization/mms-ua/ua_profile,
I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6720, uid=10112, userID:0
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6720, uid=10112, userID:0
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6720, uid=10112, userID:0
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6720, uid=10112, userID:0
I/Babel_SMS( 6720): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,D/MessageCustFlag( 6781): sense_version=6.0
I/Babel_SMS( 6720): MmsConfig.loadFromDatabase
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6720, uid=10112, userID:0
D/BTAccessoryUtil( 6781): createReceiver
,D/BTAccessoryUtil( 6781): registerReceiver return intent = null,
,D/MessageCustFlag( 6781): sku_id=118
,D/HtcBuildUtils( 6781): getRATByHtcTelephonyCapability:1,
W/SystemReader( 6781): Cannot find qct_8960_interface, use default value instead
E/Babel_SMS( 6720): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6720): MmsConfig.loadFromResources
,E/Babel_SMS( 6720): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6720): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc,
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false,
,W/VideoCapabilities( 6720): Unsupported mime video/x-ms-wmv
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,W/Utils   ( 6720): could not parse size range '64x64-1920X1080'
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,W/AudioCapabilities( 6720): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6720): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6720): Unsupported mime audio/qcelp
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,W/VideoCapabilities( 6720): Unsupported mime video/x-ms-wmv
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false
,D/FlexNetS( 6530): updateSvcAllowedInSettings:false,
,I/VideoCapabilities( 6720): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  955): Killing 5319:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=5319
,D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 5319
,D/Process (  955): killProcessQuiet, pid=6390
I/ActivityManager(  955): Killing 6390:com.htc.providers.settings:remote/u0a13 (adj 15): empty #18
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 6390
,I/vclib   ( 6720): onServiceConnected,
,W/Babel   ( 6720): Attempted to change video mute state without an active call.,
,D/Messaging( 6781): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6781): networkCode: 
,D/MessageCustFlag( 6781): sku_id=118
,D/MmsConfig( 6781): SIE smsPri: null
D/MmsConfig( 6781): networkCode: 
,D/MmsConfig( 6781): packageName: com.htc.vvm.att does not exist
,D/Messaging( 6781): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 6781): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 6781): 
D/MmsAsyncWorkHandler( 6781): HM tk = 20001
,D/ReportIndicatorCache( 6781): MSG_QUERY_REPORTS >>
,D/SettingsManager( 6781): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@35be2d3e
,D/DraftCache( 6781): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6781): [DraftCache/1] refresh
D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/AccFlag ( 1541): sku_id=118
,D/DraftCache( 6781): [DraftCache/171] rebuildCache
,D/MmsConfig( 6781): networkCode: 
,D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1541):  slotId = -1000
D/MmsSmsV2Provider( 1541): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/MmsSmsV2Provider( 1541):  slotId = -1000
D/MmsSmsV2Provider( 1541): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 6781): mccmnc> ,
,D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93,
,D/MmsSmsV2Provider( 1541):  slotId = -1000
D/MmsSmsV2Provider( 1541): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73,
D/MmsSmsV2Provider( 1541):  slotId = -1000
D/MmsSmsV2Provider( 1541): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 6781): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Messaging( 6781): ViewCache CreatePreloadOnlyConversationList
,D/Messaging( 6781): mNeedToUpdateDate2: false
,D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/Jerry   ( 1541): URI_DRAFT
,D/MessageCustFlag( 6781): sense_version=6.0
D/Jerry   ( 6781): start to preload cursor >>>>>>>
,D/PhoneStorageUtil( 6781): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 6781): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6781): createReceiver
,D/TelephUtils( 1541): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 93,
V/MmsProvider( 1541): Update uri=content://mms, match=0
V/MmsProvider( 1541): selection=st=129 AND m_type!=134
,D/Messaging( 6781): Reset downloading state: 0
V/MmsSystemEventReceiver( 6781): TransactionService is going to be woken up.
V/TransactionService( 6781): 1-Creating TransactionService
,V/TransactionService( 6781): onStartCommand: 1
,D/MmsSystemEventReceiver( 6781): unRegisterForConnectionStateChanges
V/TransactionService( 6781): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6781): Loading previous transactions.
,I/art     (  955): Explicit concurrent mark sweep GC freed 40033(2MB) AllocSpace objects, 4(944KB) LOS objects, 33% free, 16MB/25MB, paused 1.926ms total 164.028ms,
D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1541): device_type: 1
,D/DraftCache( 6781): hasDraft() = false mNeedNotifyChange = true,
D/DraftCache( 6781): [DraftCache/171] rebuildCache time: 18
D/MmsAsyncWorkHandler( 6781): 
D/MmsAsyncWorkHandler( 6781): HM tk = 20002
D/TransactionService( 6781): Force clearing mTransactionList
,D/TransactionService( 6781): Force set service start id to 1,
V/TransactionService( 6781): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6781): unRegisterForConnectionStateChanges
D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1541):  slotId = -1000
D/TransactionService( 6781): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6781): Destroying TransactionService
,V/TransactionService( 6781): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/AccFlag ( 1541): sku_id=118
D/Messaging( 6781): ViewCache CreatePreload
D/Messaging( 6781): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1541): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/AccFlag ( 1541): sku_id=118
,D/Cust_MMSMS( 6781): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6781): def_index: 0
,D/MsgPreferenceUtils( 6781): globalIndex = 1
,D/MsgPreferenceUtils( 6781): phone state: true
,D/MsgPreferenceUtils( 6781): sd state: false
,D/MsgPreferenceUtils( 6781): vIndex = 0
,D/GpsLocationProvider(  955): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  955): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  955): [handleMessage] UPDATE_NETWORK_STATE
I/AlarmManager(  955): [AlarmQueuing] connectivity wifi: false
,D/GpsLocationProvider(  955): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  955): acquireWL(149066fc): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 955 1000 null
I/ConnectivityHelper( 1582): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  955): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  955): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ActivityManager(  955): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6836 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  955): No APN found to select.,
,D/PMS     (  955): releaseWL(149066fc): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6745): [850.1.]  listen tmrbb8,
,D/MdScDataSum( 6745): [850.1.] summary 118:p1 ignore
,I/MusicStore( 6836): Database version: 120,
,D/VoldConnector(  955): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  955): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  955): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6836): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6836): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6836): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6836): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6836): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a467212: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6836): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6836): GMSCore installation verified
,I/ConfigStore( 6836): Config Database version: 1
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6836, uid=10159, userID:0,
,D/WifiDisplayAdapter(  955): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  955):     Client/Owner: Client
D/WifiDisplayAdapter(  955):     GroupId: 
D/WifiDisplayAdapter(  955):     Passphrase: 
D/WifiDisplayAdapter(  955):     SessionId: 0
D/WifiDisplayAdapter(  955):     IP Address: }
,D/MediaRouterService(  955): Client com.google.android.music (pid 6836): Registered
,D/WifiDisplayAdapter(  955): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  955):     Client/Owner: Client
D/WifiDisplayAdapter(  955):     GroupId: 
D/WifiDisplayAdapter(  955):     Passphrase: 
,D/WifiDisplayAdapter(  955):     SessionId: 0
D/WifiDisplayAdapter(  955):     IP Address: }
,I/MediaRouter( 6836): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6836): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6836, uid=10159, userID:0
,D/AutoSetting( 1653): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1653): Util - no network available!,
,I/ActivityManager(  955): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6873 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/AutoSetting( 1653): service - onCreate(),
,I/GHttpClientFactory( 6836): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6836): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1653): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  955): request 3d363105 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052),
D/LocationManagerService(  955): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1653): service - mHandler: cancel location update,
,D/AutoSetting( 1653): service -           changes count: 0
,D/PhoneMonitor( 6873): Register our PhoneStateListener
,D/Process (  955): killProcessQuiet, pid=6422,
I/ActivityManager(  955): Killing 6422:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 6422
,D/MobileConnectivityChangeReceiver( 6873): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6873): onReceive CONNECTIVITY_CHANGE networkType=1
,D/Process (  955): killProcessQuiet, pid=6217
I/ActivityManager(  955): Killing 6217:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 6873): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6873): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  955): Recipient 6217
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 3
,I/iu.SyncManager( 4307): SYNC; picasa accounts,
,D/NetworkLogImpl( 4307): Loaded NetworkSpeedPredictor,
,D/ChimeraCfgMgr( 4307): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  955): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6903 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/Babel   ( 6720): connection state changed from UNKNOWN to DISCONNECTED
,D/VoldConnector(  955): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6903): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  955): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/,
,W/ContextImpl( 6903): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6903): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6903):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6903):   adb logcat -s GAv4
,D/VoldConnector(  955): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6903): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 6903): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/VoldConnector(  955): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/GAv4    ( 6903): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6903): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6903): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/global  ( 6903): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6903): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6903): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6903): Time to load native libraries: 2 ms (timestamps 5116-5118),
I/LibraryLoader( 6903): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6903): Binding Chromium to main looper Looper (main, tid 1) {1d948cbd}
,I/LibraryLoader( 6903): Expected native library version number "",actual native library version number ""
I/chromium( 6903): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6903): Initializing chromium process, singleProcess=true
,W/art     ( 6903): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6903): ApplicationContext is null in ApplicationStatus,
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
,E/WifiStateMachine(  955): handleMessage: E msg.what=131168
E/WifiStateMachine(  955): processMsg: DisconnectedState
E/WifiStateMachine(  955):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  955): processMsg: ConnectModeState
E/WifiStateMachine(  955):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  955): processMsg: DriverStartedState
E/WifiStateMachine(  955):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  955): processMsg: SupplicantStartedState
E/WifiStateMachine(  955):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  955): processMsg: DefaultState
E/WifiStateMachine(  955):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  955): handleMessage: X
,W/AudioManagerAndroid( 6903): Requires BLUETOOTH permission,
,I/NSApplication( 6903): Starting up...
,I/ActivityManager(  955): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6961 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  955): Killing 6160:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  955): killProcessQuiet, pid=6160
,D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  955): Recipient 6160
,D/GpsLocationProvider(  955): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  955): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/Process (  955): killProcessQuiet, pid=6467
I/ActivityManager(  955): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6984 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  955): Killing 6467:com.htc.mediamanager/u0a28 (adj 15): empty #17
,I/ActivityManager(  955): Recipient 6467
,W/ResourcesManager( 6984): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Process (  955): killProcessQuiet, pid=6332,
I/ActivityManager(  955): Killing 6332:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  955): Recipient 6332
,D/PMS     (  955): acquireWL(c6977ab): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 955 1000 WorkSource{1000},
V/AlarmManager(  955): sending alarm PendingIntent{2cf568c1: PendingIntentRecord{30ae9866 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=133026, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{24a03e08: PendingIntentRecord{2d5109a1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=148771, Int=0
,D/PMS     (  955): acquireWL(3c5e387): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6836 10159 null
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6836, uid=10159, userID:0,
,I/ActivityManager(  955): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7015 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/PMS     (  955): acquireWL(91ba19b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  955): releaseWL(3c5e387): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6836): Conditions not met for autocaching. okToAttempt=false
D/PMS     (  955): releaseWL(c6977ab): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
I/MusicLeanback( 6836): Stop autocaching.
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1954): [NET] android_getaddrinfo_proxy+
D/libc    ( 1954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1954): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  955): releaseWL(91ba19b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ResourcesManager( 7015): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7015): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7015): VM with version 2.1.0 has multidex support,
I/MultiDex( 7015): install
I/MultiDex( 7015): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7015): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7015): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 7015): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14f3e168: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7015): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1954): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1954): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,D/WearableService( 7015): callingUid 10024, callindPid: 7015
,V/GmsCoreStatsServiceLauncher( 4307): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4307, uid=10024, userID:0
,E/MDM     ( 1838): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
D/LocationInitializer( 4307): Restart initialization of location
,E/GmsUtils( 6836): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6836): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  955): acquireWL(1796a64e): PARTIAL_WAKE_LOCK  *alarm* 0x1 955 1000 WorkSource{10024}
V/AlarmManager(  955): sending alarm PendingIntent{2024c36f: PendingIntentRecord{3a0d387c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=149366, Int=0
,D/PMS     (  955): releaseWL(1796a64e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/Process (  955): killProcessQuiet, pid=5662
I/ActivityManager(  955): Killing 5662:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 5662
,I/jxcore-log( 6663): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6663): 
,I/jxcore-log( 6663): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6663): 
,I/jxcore-log( 6663): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6663): 
,I/jxcore-log( 6663): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6663): 
,I/jxcore-log( 6663): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 6663): 
,I/jxcore-log( 6663): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 6663): 
I/jxcore-log( 6663): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6663): 
,I/jxcore-log( 6663): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6663): 
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/jxcore-log( 6663): Test app app.js loaded
I/jxcore-log( 6663): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6663): setDiscoveryMode: Mode set to BLE,
I/jxcore-log( 6663): BLE advertisement is supported
I/jxcore-log( 6663): 
I/chromium( 6663): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ContactMessageStore( 1541): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1541): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1653): service - handleMessage() stop self,
,D/AutoSetting( 1653): service - handleMessage() quit looper,
D/AutoSetting( 1653): service - onDestroy() END
,D/PMS     (  955): acquireWL(2abf0505): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null,
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(2abf0505): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  955): updateBatteryInfo
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  955): runPSCheck
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  955): Checking...
D/WifiController(  955): handleMessage: E msg.what=155652
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): processMsg: DeviceActiveState
,D/WifiController(  955): battery changed pluggedType: 2
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  955): processMsg: StaEnabledState
D/WifiController(  955): processMsg: DefaultState
,D/WifiController(  955): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3488): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/TelephonyReceiver( 1541): switchBindHtcMsgCursor: null
,D/PMS     (  955): releaseWL(1ed02ebe): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  955): Failed to find a new network - expiring NetTransition Wakelock
,D/PMS     (  955): acquireWL(dbad95a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 955 1000 WorkSource{1000},
V/AlarmManager(  955): sending alarm PendingIntent{2cf568c1: PendingIntentRecord{30ae9866 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=193026, Int=0
,V/AlarmManager(  955): sending alarm PendingIntent{3c64278b: PendingIntentRecord{1b336068 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=208282, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{34afec81: PendingIntentRecord{35bd3126 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192037, Int=0,
,D/PMS     (  955): acquireWL(2febb167): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
D/PMS     (  955): releaseWL(dbad95a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  955): releaseWL(2febb167): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1653): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@f3c3757
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  955): killProcessQuiet, pid=6507
I/ActivityManager(  955): Killing 6507:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 6507
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  955): acquireWL(1c77fd03): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 955 1000 WorkSource{1000}
,V/AlarmManager(  955): sending alarm PendingIntent{2cf568c1: PendingIntentRecord{30ae9866 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=253026, Int=0
,V/AlarmManager(  955): sending alarm PendingIntent{112caab9: PendingIntentRecord{301f3efe com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453831233577, Int=0,
,D/PMS     (  955): releaseWL(1c77fd03): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1221): Weather sync is On,
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 3
,D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/PMS     (  955): acquireWL(38f3665f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  955): n_update end
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  955): releaseWL(38f3665f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  955): plugged=true pluggin=true
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3488): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  955): updateBatteryInfo
,D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/PMS     (  955): runPSCheck
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  955): Checking...
D/UsbnetService(  955): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): handleMessage: E msg.what=155652
D/WifiController(  955): battery changed pluggedType: 2
D/WifiController(  955): processMsg: DeviceActiveState
D/WifiController(  955): processMsg: StaEnabledState
D/WifiController(  955): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  955): handleMessage: X
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  955): acquireWL(354db8ac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(354db8ac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  955): updateBatteryInfo
D/HeadsetStateMachine( 3488): Disconnected process message: 10, size: 0
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/PMS     (  955): runPSCheck
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  955): Checking...
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/HtcPowerSaver(  955): >> updateStatus
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/WifiController(  955): battery changed pluggedType: 2
D/WifiController(  955): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  955): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  955): processMsg: StaEnabledState
I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  955): processMsg: DefaultState
,I/HtcPowerSaver(  955): << updateStatus
D/WifiController(  955): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  441): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1541): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1541): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1541): sku_id=118
,D/ContactMessageStore( 1541): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1541): start background delete task...
,D/ContactMessageStore( 1541): size: 0 , 0
,D/ContactMessageStore( 1541): Background delete complete
,D/PMS     (  955): acquireWL(21643975): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 955 1000 WorkSource{1000},
V/AlarmManager(  955): sending alarm PendingIntent{2cf568c1: PendingIntentRecord{30ae9866 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=373026, Int=0,
V/AlarmManager(  955): sending alarm PendingIntent{26ac4d0a: PendingIntentRecord{1692097b com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=946386, Int=0
,I/bt-btm  ( 3488): Received oneshot timer event complete
I/bt-btm  ( 3488): btm_ble_timeout
I/bt-btm  ( 3488): btm_gen_resolvable_private_addr
,D/PMS     (  955): acquireWL(2b33b398): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3488 1002 null
,D/bt-btm  ( 3488): btm_ble_rand_enc_complete
I/bt-btm  ( 3488): btm_gen_resolve_paddr_low
D/bt-smp  ( 3488): smp_encrypt_data
W/bt-smp  ( 3488): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3488): Plain text(LSB ~ MSB) = 3d 0c 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3488): Encrypted text(LSB ~ MSB) = 38 10 fa 7f 7a b8 26 e4 34 85 7a 1a 9a a3 64 d9 
I/bt-btm  ( 3488): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3488): Stopping oneshot timer
D/bt-btm  ( 3488): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  955): releaseWL(21643975): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  955): releaseWL(2b33b398): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  955): acquireWL(254bf7f1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(254bf7f1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  955): updateBatteryInfo
,D/PMS     (  955): runPSCheck
D/HtcPowerSaver(  955): Checking...
I/HtcPowerSaver(  955): >> updateStatus
,D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3488): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  955): BroadcastReceiver::onReceive+
,I/HtcPowerSaver(  955): << updateStatus
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  955): battery changed pluggedType: 2
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  955): handleMessage: E msg.what=155652
D/WifiController(  955): processMsg: DeviceActiveState
D/WifiController(  955): processMsg: StaEnabledState
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  955): acquireWL(3c4a2fd6): PARTIAL_WAKE_LOCK  *alarm* 0x1 955 1000 WorkSource{1000}
V/AlarmManager(  955): sending alarm PendingIntent{adb25f9: PendingIntentRecord{3c77393e android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=807453, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{2cf568c1: PendingIntentRecord{30ae9866 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=973025, Int=0
,I/ActivityManager(  955): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7054 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,V/AlarmManager(  955): sending alarm PendingIntent{1badc257: PendingIntentRecord{207c7144 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453831703073, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{1e17222d: PendingIntentRecord{3f44ffa1 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453831855593, Int=0
W/ContextImpl( 6560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6560): MY_DEBUG = false
,D/PMS     (  955): releaseWL(3c4a2fd6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageService( 6560): repeat time = 1453832760066
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/PowerUsageList:PowerUsageHelper( 6560): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6560): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 7076): Error opening trace file: Permission denied (13),
I/dex2oat ( 7076): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7076): dex2oat: override thread count:4
,I/art     (  955): Explicit concurrent mark sweep GC freed 20423(1077KB) AllocSpace objects, 3(636KB) LOS objects, 33% free, 16MB/25MB, paused 2.030ms total 189.005ms
,I/dex2oat ( 7076): dex2oat took 631.472ms (threads: 4),
,I/PushClient( 7054): ApplicationMonitor {36b2cebb}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
I/PushClient( 7054): ApplicationMonitor {36b2cebb}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 7054): ApplicationMonitor {36b2cebb}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7054): ApplicationMonitor {36b2cebb}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7054): ApplicationMonitor {36b2cebb}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7054): ApplicationMonitor {36b2cebb}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7054): ApplicationMonitor {36b2cebb}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7054): ApplicationMonitor {36b2cebb}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7054): ApplicationMonitor {36b2cebb}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7054): PnsModel {33ebdf4a}: update(): Update registration caused by: alarm
,I/PushClient( 7054): PnsConfigModel {3fe7c369}: <init>(): Use dm-client for provisioning.
,W/System.err( 7054): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 7054): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7054): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7054): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  955): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7083 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 7083): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7083 dbg=false s=true
,I/DeviceManagement( 7083): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 7083): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7083): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 7083): WorkflowService: Starting workflow service,
,I/DeviceManagement( 7083): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@36b2cebb] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 7083): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7083): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 7083): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7083): SessionStateController: Checking invariants...
,I/DeviceManagement( 7083): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7083): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7083): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7083): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@36b2cebb],
,I/DeviceManagement( 7083): WorkflowService: Stopping workflow service,
,D/Process (  955): killProcessQuiet, pid=6618
I/ActivityManager(  955): Killing 6618:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 6618
,I/PushClient( 7054): PnsModel {33ebdf4a}: update(): The registration record has not expired yet. No need to update.
,D/Process (  955): killProcessQuiet, pid=4725,
,I/ActivityManager(  955): Killing 4725:com.android.settings/1000 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 4725
,D/WifiService(  955): Client connection lost with reason: 4
,D/PMS     (  955): acquireWL(14def47): PARTIAL_WAKE_LOCK  *alarm* 0x1 955 1000 WorkSource{1000},
V/AlarmManager(  955): sending alarm PendingIntent{2500b374: PendingIntentRecord{37b1f09d com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453831906442, Int=0
,D/SmartSyncUtils( 6560): isEpsOn(), nState = 0
,D/PMS     (  955): releaseWL(14def47): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  955): acquireWL(24817912): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6560 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6560): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6560): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6560): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6560): SettingOnTime = 1453874400000, randomSettingOnTime = 1453871500000
D/SmartSyncScreenOnOffTimeReceiver( 6560): SettingOffTime = 1453852800000, randomSettingOffTime = 1453855196000
,D/SmartSyncScreenOnOffTimeReceiver( 6560): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6560): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6560): bNightModeTurnOffOnce = false
,D/PMS     (  955): releaseWL(24817912): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  955): acquireWL(33f038e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(33f038e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  955): updateBatteryInfo
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  955): plugged=true pluggin=true
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  955): runPSCheck
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  955): Checking...
D/UsbnetService(  955): onReceive BATTERY_CHANGED
,I/HtcPowerSaver(  955): >> updateStatus
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  955): battery changed pluggedType: 2
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetStateMachine( 3488): Disconnected process message: 10, size: 0
D/WifiController(  955): handleMessage: E msg.what=155652
D/WifiController(  955): processMsg: DeviceActiveState
D/WifiController(  955): processMsg: StaEnabledState
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): handleMessage: X
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/UsageStatsService(  955): User[0] Flushing usage stats to disk
,D/PMS     (  955): acquireWL(312f92e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null,
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  955): n_update end
D/HeadsetStateMachine( 3488): Disconnected process message: 10, size: 0
D/PMS     (  955): releaseWL(312f92e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  955): updateBatteryInfo
,D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  955): runPSCheck
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  955): battery changed pluggedType: 2
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  955): Checking...
D/WifiController(  955): handleMessage: E msg.what=155652
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): processMsg: DeviceActiveState
D/WifiController(  955): processMsg: StaEnabledState
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): handleMessage: X
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
