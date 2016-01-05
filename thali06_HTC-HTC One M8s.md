#### Test 54970261aa56788_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
D/Process (  968): killProcessQuiet, pid=5540
--------- beginning of system
I/ActivityManager(  968): Killing 5540:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  968): Recipient 5540
E/cutils-trace( 6395): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6395): ====startRecUseTime====
D/htc.customization.log.level( 6395):  is 
W/CustomizationLogLevel( 6395): Level value is invalid, use default level 2
D/CustomizationManager( 6395):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 6395): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6395): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6395): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6395): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6395): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6395): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6395): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6395): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6395): Parsing tag category name = system
I/CustomizationCIDLoader( 6395): Parsing tag category name = application
I/CustomizationCIDLoader( 6395): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6395): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6395): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6395): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6395): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6395): add string-array item, value = 42507
I/CustomizationCIDLoader( 6395): add string-array item, value = 21902
I/CustomizationCIDLoader( 6395): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6395): add string-array item, value = 23420
I/CustomizationCIDLoader( 6395): add string-array item, value = 22299
I/CustomizationCIDLoader( 6395): add string-array item, value = 24002
I/CustomizationCIDLoader( 6395): add string-array item, value = 23210
I/CustomizationCIDLoader( 6395): add string-array item, value = 23205
I/CustomizationCIDLoader( 6395): add string-array item, value = 23806
I/CustomizationCIDLoader( 6395): add string-array item, value = 23430
I/CustomizationCIDLoader( 6395): add string-array item, value = 23408
I/CustomizationCIDLoader( 6395): add string-array item, value = 27205
I/CustomizationCIDLoader( 6395): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6395): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6395):  Read CID file spent 0.096 (s)
D/CustomizationManager( 6395):  All configurations done spent 0.097 (s)
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6395 on display 0
D/PMS     (  968): acquireHCC(228183c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 968 1000 null
D/PMS     (  968): acquireHCC(1cdcc9c5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 968 1000 null
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6413 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1312): [EventService]  onDisplayChanged: 0
V/ActivityManager(  968): Display changed displayId=0
D/DotMatrix( 1312): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1582): [trimMemory] 20
I/WebViewFactory( 6413): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6413): Time to load native libraries: 9 ms (timestamps 9704-9713),
,I/LibraryLoader( 6413): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6413): Binding Chromium to main looper Looper (main, tid 1) {b63789c},
I/LibraryLoader( 6413): Expected native library version number "",actual native library version number ""
,I/chromium( 6413): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6413): Initializing chromium process, singleProcess=true,
,W/art     ( 6413): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6413): ApplicationContext is null in ApplicationStatus
,W/chromium( 6413): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6413): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6413): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6413): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6413): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6413): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6413): Local Branch: 
I/Adreno-EGL( 6413): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6413): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6413):                  d74aa161a12b9c6fc6332151
,W/System.err(  968): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30035379:true
,D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
,W/art     ( 6413): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6413): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6413): CordovaWebView is running on device made by: HTC
,W/art     ( 6413): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6413): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  968): Activity pause timeout for ActivityRecord{22da1f1a u0 com.test.thalitest/.MainActivity t8}
,W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/art     (  968): Explicit concurrent mark sweep GC freed 44528(2MB) AllocSpace objects, 3(768KB) LOS objects, 33% free, 16MB/25MB, paused 1.664ms total 140.218ms,
,W/chromium( 6413): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/StatusBarManagerService(  968): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
,D/StatusBarManagerService(  968): setSystemUiVisibility(0x0)
,D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
,D/FindExtension( 6413): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6413): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@28d776f6, mServedView=org.apache.cordova.engine.SystemWebView{240caf7 VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2577dd64,
I/InputMethodManagerService(  968): Disable input method client, pid=1582
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6413): reportFullscreenMode on inactive InputConnection,
W/BindingManager( 6413): Cannot call determinedVisibility() - never saw a connection for the pid: 6413
,I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +771ms (total +817ms)
,D/JsMessageQueue( 6413): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6413): JniHelper::setJavaVM(0xaae278f8), pthread_self() = -1409257256,
D/JX-Cordova( 6413): jxcore cordova android initializing
,W/jxcore-log( 6413): Initializing JXcore engine,
W/jxcore-log( 6413): JXcore engine is ready
,W/jxcore-log( 6413): Starting JXcore engine
,D/PMS     (  968): releaseHCC(228183c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  968): releaseHCC(1cdcc9c5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6413): Platform android,
W/jxcore-log( 6413): 
W/jxcore-log( 6413): Process ARCH arm
W/jxcore-log( 6413): 
,I/jxcore-log( 6413): JXcore Cordova bridge is ready!,
I/jxcore-log( 6413): 
,W/jxcore-log( 6413): JXcore engine is started
I/Choreographer( 6413): Skipped 98 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6413): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6413): Toggling radios to true,
I/jxcore-log( 6413): 
,D/BluetoothAdapter( 6413): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  968): ADD_CLIENT: 8,
D/WifiService(  968): New client listening to asynchronous messages
D/WifiManager( 6413): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  968): setWifiEnabled: true pid=6413, uid=10366
,E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  968): MONITOR_LOG
W/Settings:Agent(  968): name: wifi_on
I/WifiService(  968): isSprintWifiRestricted(): false
W/Settings:Agent(  968): value: 2
I/WifiService(  968): isMdmWifiRestricted(): false
W/Settings:Agent(  968): >> traceCallingStack()
,W/Settings:Agent(  968): Process.myPid(): 968
W/Settings:Agent(  968): Process.myTid(): 1627
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
W/System.err(  968): java.lang.Throwable: stack dump
,W/System.err(  968): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  968): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  968): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 19(ms)
D/WifiController(  968): handleMessage: E msg.what=155656
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): handleMessage: X
D/WifiManager( 6413): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  968): handleMessage: E msg.what=131145
D/WifiManager( 6413): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
I/jxcore-log( 6413): Radios toggled
I/jxcore-log( 6413): 
E/WifiStateMachine(  968):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1353): wlan0: Cancelling scan request
D/wpa_supplicant( 1353): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1353): TDLS: Tear down peers
D/wpa_supplicant( 1353): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 1353): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1353): wlan0: Deauthentication notification
D/wpa_supplicant( 1353): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1353): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1353): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1353): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1353): enter disconnect check
I/wpa_supplicant( 1353): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1353): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1353): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  968): interfaceLinkStateChanged wlan0, false,
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  968): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  968): TetherInterfaceSM: wlan0: exit InitialState
,D/PMS     (  968): acquireWL(332f327a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
V/Tethering(  968): TetherInterfaceSM: wlan0: enter UnavailableState
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  968): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  968): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  968): interfaceStatusChanged wlan0, false
D/Tethering(  968): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbnetService(  968): BroadcastReceiver::onReceive+
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1353): TDLS: Remove peers on disassociation
E/WifiMonitor(  968): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1353): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a92e4f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1353):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1353): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1353): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1353): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1353): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1353): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1353): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1353): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1353): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1353): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1353): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1353): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  968): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: ConnectedState
E/WifiStateMachine(  968): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  968): release()
E/WifiStateMachine(  968): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
,E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
V/NetworkPolicy(  968): updateNotificationsLocked()
E/WifiStateMachine(  968): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/PMS     (  968): releaseWL(332f327a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  968): handleNetworkDisconnect "NG700" nid=0
D/WifiP2pService(  968): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1353): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1353): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1353): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1353): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1353): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1353): Power_Mode_Type mode = 0
I/wpa_supplicant( 1353): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  968): setDhcpActive: false
D/TetherSettings( 5816): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5816): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5816): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5816): Cust_ConnectToPC   : spcsc>false
D/        ( 5816): Cust_ConnectToPC   : IPT>true
D/        ( 5816): Cust_ConnectToPC   : Singel_USB>false
,V/NativeCrypto( 1955): Read error: ssl=0x55c4f3bee0: I/O error during system call, Connection timed out
D/PMS     (  968): acquireWL(30d5da2b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): NetworkAgent != null
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 13
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/Settings( 5816): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5816): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5816): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5816): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  968): stopDataStallAlarm 
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 3
,I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  968): autoRoamSetBSSID any key="NG700"WPA_PSK
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1353): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1353): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1353): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 1353): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
,D/wpa_supplicant( 1353): CTRL_IFACE: SAVE_CONFIG - Configuration updated
V/NativeCrypto( 1955): SSL shutdown failed: ssl=0x55c4f3bee0: I/O error during system call, Broken pipe
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  968):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  968): Start Disconnecting Watchdog 1
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131146
E/WifiStateMachine(  968): processMsg: DisconnectingState
E/WifiStateMachine(  968):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1353): wlan0: Control interface command 'RECONNECT'
D/ConnectivityService(  968): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1353): Fast associate: Old scan results
D/wpa_supplicant( 1353): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1353): wpa_supplicant_scan enter
,D/wpa_supplicant( 1353): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1353): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1353): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1353): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1353): WPS:  * Request Type
D/wpa_supplicant( 1353): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1353): WPS:  * UUID-E
D/wpa_supplicant( 1353): WPS:  * Primary Device Type
D/wpa_supplicant( 1353): WPS:  * RF Bands (3)
D/wpa_supplicant( 1353): WPS:  * Association State
D/wpa_supplicant( 1353): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1353): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1353): WPS:  * Manufacturer
D/wpa_supplicant( 1353): WPS:  * Model Name
D/wpa_supplicant( 1353): WPS:  * Model Number
D/wpa_supplicant( 1353): WPS:  * Device Name
D/wpa_supplicant( 1353): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1353): P2P: * P2P IE header
D/wpa_supplicant( 1353): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1353): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1353): wlan0: Add radio work 'scan'@0x55a92e7680
D/wpa_supplicant( 1353): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1353): wlan0: Starting radio work 'scan'@0x55a92e7680 after 0.000140 second wait
D/wpa_supplicant( 1353): wlan0: nl80211: scan request
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: DisconnectingState
D/wpa_supplicant( 1353): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1353): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1353): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1353): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1353): wlan0: Own scan request started a scan in 0.000336 seconds
I/wpa_supplicant( 1353): wlan0: CTRL-EVENT-SCAN-STARTED 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-2ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=-1ms what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/WifiStateMachine(  968):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  968):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-S,TARTED 
E/WifiStateMachine(  968):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147460
E/WifiStateMachine(  968): processMsg: DisconnectingState
E/WifiStateMachine(  968):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132274
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132274
E/WifiStateMachine(  968): ConnectModeState: Network connection lost 
E/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
D/PMS     (  968): releaseWL(30d5da2b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  968): DisconnectedState call setCountryCode()
E/WifiStateMachine(  968):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1353): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1353): wlan0: Cancelling scan request
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
W/ContextImpl( 5816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1353): wlan0: nl80211: sched_scan request
I/SmartNS_Utility( 5816): setISNotification
D/SmartNS_Utility( 5816): usb_cable_connect = 1
D/SmartNS_Utility( 5816): usb_denied = 0
I/SmartNS_PSService( 5816): usb notificaiton:true
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/ActionCombine( 5816): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/SmartNS_Utility( 5816): usb_cable_connect = 1
D/SmartNS_Utility( 5816): usb_denied = 0
I/SmartNS_PSService( 5816): usb notificaiton:true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
I/RemoteViews( 1223): reapply : com.android.settings 2 36
D/SmartNS_NSReceiver( 5816): Tethered state change:false isNSOpening:false
D/WISPrService( 5816): >>>>>WISPrService start isConnected = true<<<<<
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:2
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/wpa_supplicant( 1353): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1353): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1353): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1353): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1353): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1353): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1353): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1353): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1353): wlan0: Scan completed in 0.047171 seconds
D/wpa_supplicant( 1353): nl80211: Received scan results (1 BSSes)
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
I/wpa_supplicant( 1353): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/wpa_supplicant( 1353): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1353): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1353): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1353): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1353): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1353): wlan0: Radio work 'scan'@0x55a92e7680 done in 0.049192 seconds
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1353): wlan0: Selecting BSS from priority group 423
E/WifiMonitor(  968): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1353): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58 wps
D/wpa_supplicant( 1353): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1353): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1353): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1353):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 1353): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=44 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1353): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55a92e6c00  current_ssid=0x0
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1353): wlan0: Request association with c0:ff:d4:d3:aa:48
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=132314  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/wpa_supplicant( 1353): wpa_supplicant_set_is_wep_security: 0
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1353): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1353): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1353): wlan0: Add radio work 'connect'@0x55a92e7680
D/wpa_supplicant( 1353): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1353): wlan0: Starting radio work 'connect'@0x55a92e7680 after 0.000066 second wait
I/wpa_supplicant( 1353): check if in concurrent case
I/wpa_supplicant( 1353): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=132315  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiMonitor(  968): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=45 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/wpa_supplicant( 1353): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1353): wlan0: Cancelling sched scan
E/WifiStateMachine(  968):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/wpa_supplicant( 1353): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1353): wlan0: Cancelling scan request
D/wpa_supplicant( 1353): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1353): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1353): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1353): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1353): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1353): RSN: PMKSA cache search - network_ctx=0x55a92e6c00 try_opportunistic=0
D/wpa_supplicant( 1353): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1353): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1353): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1353): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1353): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1353): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1353): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1353): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1353): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1353): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): wlan0: State: SCANNING -> ASSOCIATING
D/WifiService(  968): New client listening to asynchronous messages
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  968):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
D/wpa_supplicant( 1353): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1353): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1353): nl80211: Unsubscribe mgmt frames handle 0x888888dd21a6e989 (mode change)
E/WifiStateMachine(  968):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/wpa_supplicant( 1353): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a92e6100
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=0104
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=040a
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=040b
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=040c
E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=040d
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=090a
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=090b
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=090c
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=090d
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=0409506f9a09
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=7f506f9a09
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=0801
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=040e
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=06
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=0a07
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=0a11
D/wpa_supplicant( 1353): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a92e6100 match=0a1a
D/wpa_supplicant( 1353): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1353):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353):   * freq=2412
D/wpa_supplicant( 1353):   * freq_hint=2412
D/wpa_supplicant( 1353):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1353):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1353):   * WPA Versions 0x2
D/wpa_supplicant( 1353):   * pairwise=0xfac04
D/wpa_supplicant( 1353):   * group=0xfac04
D/wpa_supplicant( 1353):   * akm=0xfac02
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1353):   * Auth Type 0
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1353): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55a92e6c3a
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1353): nl80211: Connect request send successfully
D/wpa_supplicant( 1353): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1353): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1353): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1353): EAPOL: External notification - portControl=Auto
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/wpa_supplicant( 1353): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/wpa_supplicant( 1353): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1353): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  968): handleMessage: X
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNetworkAgent(  968): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=132320  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/RemoteViews( 1223): reapply : com.android.settings 1 36
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  968): ADD_CLIENT: 9
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=132327  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147461
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:84 bcn=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:84 bcn=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:84 bcn=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:84 bcn=0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1353): wlan0: Control interface command 'LIST_DONGLES'
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): [1,452,019,312,891 ms] noteScanEnd no scan source
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1353): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  968): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2b45e0dd sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  968): NG7005g c0:ff:d4:d3:aa:4a rssi=-49 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-85 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  968): UPC5999698 64:7c:34:12:7f:81 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): 01ABC c2:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  968): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  968): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  968): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  968):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  968): UPC503894600 a0:c5:62:7a:49:97 rssi=-78 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): Gonzos 38:f8:89:11:e9:11 rssi=-92 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  968): ageScanResultsOut delay 40000 size 7 now 1452019312894
E/WifiAutoJoinController (  968): newSupplicantResults size=7 known=1 true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1353): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  968): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  968): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  968): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  968): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  968): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  968):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  968): handleMessage: X
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6474 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/WifiStateMachine(  968): handleMessage: E msg.what=131213
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState CMD_TARGET_BSSID 45 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132351
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_TARGET_BSSID 45 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132352
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_TARGET_BSSID 45 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132352
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_TARGET_BSSID 45 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132352
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=132352  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info0x
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=132354  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  968): handleMessage: X
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 18
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): handleMessage: X
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Disconnected - quitting
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524292
D/ConnectivityService(  968): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  968): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
I/SecurityController( 1223): onLost 100
I/art     (  448): Explicit concurrent mark sweep GC freed 8668(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 259us total 19.109ms
W/WISPrService( 5816): can not find out wificonfig: SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5816): trigger connection
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  968): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  968): Removing idletimer
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/usbnet  (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/PMS     (  968): acquireWL(26067021): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 968 1000 null
D/CSLegacyTypeTracker(  968): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  968): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
D/PMS     (  968): acquireWL(16dfc46): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/ConnectivityService(  968): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/WISPrService( 5816): continue
I/art     (  448): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 233us total 14.375ms
D/PMS     (  968): releaseWL(16dfc46): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateIfacesLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DATA_ICON( 1223): dataConnected: false/false
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5816): start DataConnection
D/libc    ( 5816): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5816): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/art     (  448): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 246us total 14.692ms
D/libc    ( 5816): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5816): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5816): [NET] android_getaddrinfo_proxy+
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/libc    ( 5816): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
W/ResourcesManager( 6474): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5816): [NET] android_getaddrinfo_proxy-, NODATA
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0,
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    ( 5816): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5816): [NET] android_getaddrinfofornet-, err=8
,I/ActivityManager(  968): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6499 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WISPrService( 5816): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/wpa_supplicant( 1353): Wireless event: cmd=0x8c02 len=271,
I/wpa_supplicant( 1353): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1353): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1353): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1353): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1353): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
,D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/Tethering(  968): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1353): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1353): nl80211: Connect event
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1353): nl80211: Associated on 2412 MHz
D/PMS     (  968): acquireWL(b1c0259): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/wpa_supplicant( 1353): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1353): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1353): wlan0: Association info event
D/wpa_supplicant( 1353): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): wlan0: freq=2412 MHz
D/wpa_supplicant( 1353): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1353): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1353): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1353): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1353): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1353): wlan0: WPA: Association event - clear replay counter
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1353): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1353): TDLS: Remove peers on association
D/wpa_supplicant( 1353): EAPOL: External notification - portEnabled=0
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1353): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1353): EAPOL: External notification - portEnabled=1
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1353): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1353): EAPOL: enable timer tick
D/wpa_supplicant( 1353): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1353): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1353): wlan0: Cancelling scan request
D/wpa_supplicant( 1353): wlan0: Process pending EAPOL frame that was received just before association notification
D/wpa_supplicant( 1353): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wla,n0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1353): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1353): wlan0:   EAPOL-Key type=2
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1353): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1353): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1353):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1353):   key_nonce - hexdump(len=32): 30 be 6e 3b 28 31 f8 2f 97 d0 fc 1e 51 de 31 1c 64 af d2 62 b2 d6 c8 bd 55 76 3f b3 f7 f2 95 b1
D/wpa_supplicant( 1353):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1353): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1353): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=48 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=132444  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/HTCRequest(  968): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  968): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  968): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=132445  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147500
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/wpa_supplicant(, 1353): WPA: Renewed SNonce - hexdump(len=32): 15 cb 60 c9 89 b1 d3 1e 75 5f f9 65 3f 62 03 11 98 3b cd 1a 01 13 10 0b 17 78 1c 40 d9 8b 61 6e
E/WifiStateMachine(  968):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/wpa_supplicant( 1353): WPA: Nonce1 - hexdump(len=32): 15 cb 60 c9 89 b1 d3 1e 75 5f f9 65 3f 62 03 11 98 3b cd 1a 01 13 10 0b 17 78 1c 40 d9 8b 61 6e
D/wpa_supplicant( 1353): WPA: Nonce2 - hexdump(len=32): 30 be 6e 3b 28 31 f8 2f 97 d0 fc 1e 51 de 31 1c 64 af d2 62 b2 d6 c8 bd 55 76 3f b3 f7 f2 95 b1
D/wpa_supplicant( 1353): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1353): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1353): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1353): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1353): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1353): WPA: Derived Key MIC - hexdump(len=16): db f4 43 cc c5 c0 51 fd fa 55 0b 21 72 61 40 82
E/WifiStateMachine(  968):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  968): Enter handleAssociatedWithEvent
D/WifiStateMachine(  968): Associated
I/wpa_supplicant( 1353): htc_wext_set_keepalive +
I/wpa_supplicant( 1353): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1353): getPrivFuncNum +	
I/wpa_supplicant( 1353): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1353): htc_wext_set_keepalive fnum = 0x8bf6
D/PMS     (  968): releaseWL(b1c0259): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/wpa_supplicant( 1353): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  968): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  968): Exit handleAssociatedWithEvent
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
V/Tethering(  968): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=132448  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
V/NetworkPolicy(  968): updateNotificationsLocked()
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/Tethering(  968): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
D/UsbnetService(  968): BroadcastReceiver::onReceive+
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/wpa_supplicant( 1353): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1353): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1353): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1353): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1353): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1353):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1353):   key_nonce - hexdump(len=32): 30 be 6e 3b 28 31 f8 2f 97 d0 fc 1e 51 de 31 1c 64 af d2 62 b2 d6 c8 bd 55 76 3f b3 f7 f2 95 b1
D/wpa_supplicant( 1353):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_rsc - hexdump(len=8): a9 44 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353):   key_mic - hexdump(len=16): 14 4e fd 35 01 de b0 2c 18 77 36 e0 b1 a6 e8 26
D/wpa_supplicant( 1353): RSN: encrypted key data - hexdump(len=56): fc 3a 5b 21 7c 0e a1 ac e8 ed 7e b3 36 40 82 18 99 9c 50 c6 88 6b 79 bc 7d 7d f6 3a 30 b0 d8 14 ...
D/wpa_supplicant( 1353): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1353): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1353): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1353): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 28 ef ...
D/wpa_supplicant( 1353): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1353): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1353): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1353): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1353): WPA: Derived Key MIC - hexdump(len=16): f6 91 fd 1e 43 d5 d3 e6 c0 c7 89 d0 58 f9 1a 03
D/wpa_supplicant( 1353): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55a92e7390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1353): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1353): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1353):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1353): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1353): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1353): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1353): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1353): WPA: RSC - hexdump(len=6): a9 44 00 00 00 00
D/wpa_supplicant( 1353): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5574affe68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1353): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1353): nl80211: KEY_SEQ - hexdump(len=6): a9 44 00 00 00 00
D/wpa_supplicant( 1353):    broadcast key
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1353): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1353): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1353): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1353): wlan0: Radio work 'connect'@0x55a92e7680 done in 0.139225 seconds
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1353): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1353): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=51 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=52 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  968): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1353): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1353): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1353): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  968): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=54 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  968): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1353): set send_ind_to_ndc = 0
I/wpa_supplicant( 1353): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1353): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1353): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1353): EAPOL: External notification - EAP success=1
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1353): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1353): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1353): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1353): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1353): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1353): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1353): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1353): EAPOL authentication completed - result=SUCCESS
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1353): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1353): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/Tethering(  968): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=132461  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
E/WifiStateMachine(  968):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=132463  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=132464  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147459
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=132465
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=132465
E/WifiStateMachine(  968): Network connection established
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/WifiStateMachine(  968): fetchFrequency(), freq = 2412
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 22
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 23
E/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1353): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  968): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  968): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  968): Got NetworkAgent Messenger
E/WifiStateMachine(  968): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  968): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  968): NetworkAgent connected
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1353): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1353): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1353): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1353): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1353): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
E/WifiStateMachine(  968): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  968): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 24
E/WifiStateMachine(  968): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1353): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1353): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1353): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1353): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1353): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1353): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): Start Dhcp Watchdog 2
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=132486  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=132487  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=132488  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): handleMessage: X
,E/WifiStateMachine(  968): handleMessage: E msg.what=131212
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
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=196612
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  968): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/PMS     (  968): acquireWL(20ba7b93): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 968 1000 null
E/WifiStateMachine(  968):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiDataStallTracker(  968): setDhcpActive: true
D/WifiStateMachine(  968): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WISPrService( 5816): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  968): do suspend false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1353): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1353): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1353): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1353): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1353): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): noteBatchedScanstop()
E/WifiStateMachine(  968): handleMessage: X
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@383a463c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@383a463c target=com.android.internal.util.StateMachine$SmHandler }
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WISPrService( 5816): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,I/Babel_SMS( 6474): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6474): MmsConfig.loadMmsSettings
,I/ActivityManager(  968): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6535 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/MdScPhnSt( 6499): [570.2.]  listen tmrbb8,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6474, uid=10112, userID:0
,W/HtcWrapAdjustableCursorFactory( 6535): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
W/Settings( 6474): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 6535): onCreate
D/MdProvGlob( 6344): add item 101 (2:g3d26) for 15:android.intent.action.PRECISE_DATA_CONNECTION_STATE_CHANGED
,I/Babel_Crash( 6474): startup - clean
,V/GetPrviateResource( 6535): GetPrviateResource
V/GetPrviateResource( 6535): GetPrviateResource
D/MmsCustomizationProvider( 6535): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MessageCustFlag( 6535): sense_version=6.0
,D/BTAccessoryUtil( 6535): createReceiver
,D/BTAccessoryUtil( 6535): registerReceiver return intent = null
,D/MessageCustFlag( 6535): sku_id=118,
D/MdProvGlob( 6344): remove item 101 (p3d1in26) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 6499): [570.2.] summary 118:p3 ignore
E/dhcpcd  ( 6563): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6563): version 5.5.6 starting
D/HtcBuildUtils( 6535): getRATByHtcTelephonyCapability:1
E/dhcpcd  ( 6563): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6563): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
,I/dhcpcd  ( 6563): autoip env[11]:autoip=DISABLE
W/SystemReader( 6535): Cannot find qct_8960_interface, use default value instead
,D/MmsCustomizationProvider( 6535): query uri: content://htc-mms-customization/mms-ua/ua_profile,
I/Babel   ( 6474): deleted: false for 0
,I/Babel_SMS( 6474): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
I/Babel_SMS( 6474): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6474): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6474): MmsConfig.loadFromResources
E/Babel_SMS( 6474): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6474): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6474, uid=10112, userID:0
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6474, uid=10112, userID:0
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6474, uid=10112, userID:0
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6474, uid=10112, userID:0
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6474, uid=10112, userID:0
,I/dhcpcd  ( 6563): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6563): wlan0: sending REQUEST (xid 0xbce38570), next in 1.02 seconds
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false
,W/VideoCapabilities( 6474): Unsupported mime video/x-ms-wmv,
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false
W/Utils   ( 6474): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 6474): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6474): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6474): Unsupported mime audio/qcelp,
W/VideoCapabilities( 6474): Unsupported mime video/x-ms-wmv
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false
,D/TetherSettings( 5816): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 5816): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5816): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5816): Cust_ConnectToPC   : spcsc>false
D/        ( 5816): Cust_ConnectToPC   : IPT>true
D/        ( 5816): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5816): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
E/SmartNS_Utility( 5816): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5816): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5816): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5816): setISNotification,
,D/SmartNS_Utility( 5816): usb_cable_connect = 1
D/SmartNS_Utility( 5816): usb_denied = 0,
I/SmartNS_PSService( 5816): usb notificaiton:true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 5816): usb_cable_connect = 1
,D/SmartNS_Utility( 5816): usb_denied = 0
I/SmartNS_PSService( 5816): usb notificaiton:true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1223): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 5816): Tethered state change:false isNSOpening:false,
D/Process (  968): killProcessQuiet, pid=6129
I/ActivityManager(  968): Killing 6129:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/VideoCapabilities( 6474): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc,
,I/ActivityManager(  968): Recipient 6129,
,D/PMS     (  968): acquireWL(b2980df): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
V/AlarmManager(  968): sending alarm PendingIntent{316a012c: PendingIntentRecord{707f4c4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=133082, Int=0
D/Process (  968): killProcessQuiet, pid=6154
I/ActivityManager(  968): Killing 6154:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
I/RemoteViews( 1223): reapply : com.android.settings 2 36
,I/ActivityManager(  968): Recipient 6154
,I/vclib   ( 6474): onServiceConnected,
,W/Babel   ( 6474): Attempted to change video mute state without an active call.,
,D/Process (  968): killProcessQuiet, pid=6179
I/ActivityManager(  968): Killing 6179:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6179,
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false
,D/FlexNetS( 6282): updateSvcAllowedInSettings:false
,D/wpa_supplicant( 1353): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1353): EAPOL: disable timer tick
D/FlexNetS( 6282): updateSvcAllowedInSettings:false
,D/PMS     (  968): acquireWL(32e3098a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(b2980df): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1955): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1955): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1955): [NET] android_getaddrinfo_proxy+
D/libc    ( 1955): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1955): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  968): acquireWL(32e3098a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1955): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  968): releaseWL(32e3098a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/dhcpcd  ( 6563): wlan0: sending REQUEST (xid 0xbce38570), next in 1.56 seconds,
,I/dhcpcd  ( 6563): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6563): wlan0: leased 192.168.1.130 for 86400 seconds
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
I/dhcpcd  ( 6563): autoip env[11]:autoip=DISABLE
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
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
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  968): handleMessage: X
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
,E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  968): handleMessage: X
,I/dhcpcd  ( 6563): bind_interface: daemonise,
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  968): releaseWL(20ba7b93): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=196613
E/WifiStateMachine(  968): processMsg: ObtainingIpState
,E/WifiStateMachine(  968):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  968):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1353): Power_Mode_Type mode = 0
I/wpa_supplicant( 1353): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1353): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  968): setDhcpActive: false
E/WifiStateMachine(  968): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  968): WifiStateMachine DHCP successful
E/WifiStateMachine(  968): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  968): link address 192.168.1.130/24
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  968): gateway: /192.168.1.1
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1353): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1353): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1353): htc_wext_set_keepalive +
I/wpa_supplicant( 1353): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1353): getPrivFuncNum +	
I/wpa_supplicant( 1353): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1353): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1353): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1353): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1353): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131210
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1353): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1353): environment dirty rate=14 [7][1][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1353): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1353): wlan0: BLACKLIST CLEAR 
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiStateMachine(  968): NetworkAgent != null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  968): Adding, iface wlan0 to network 101
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=56 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): transitionTo: destState=ConnectedState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  968): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  968): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/HtcWifiWanDetect(  968): WAN detection
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HtcWifiWanDetect(  968): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true,
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 25
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 26
,D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WISPrService( 5816): >>>>>WISPrService start isConnected = true<<<<<,
,E/WifiStateMachine(  968): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/ConnectivityService(  968): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  968): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
E/WifiStateMachine(  968): processMsg: ConnectedState
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  968): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  968): handleMessage: X
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  968): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5816): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  968): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/WIFI    (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  968): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Connected
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): currentScore = 0, newScore = 20
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/CSLegacyTypeTracker(  968): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  968): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  968): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/PMS     (  968): acquireWL(240c0418): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
,D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  968): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1223): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/usbnet  (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateIfacesLocked()
D/PMS     (  968): releaseWL(240c0418): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/SecurityController( 1223): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
,V/NetworkPolicy(  968): updateNotificationsLocked()
I/SecurityController( 1223): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
D/DATA_ICON( 1223): dataConnected: false/false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/DATA_ICON( 1223): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,D/DATA_ICON( 1223): dataConnected: false/false
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/Messaging( 6535): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6535): networkCode: 
D/MessageCustFlag( 6535): sku_id=118
D/MmsConfig( 6535): SIE smsPri: null
D/MmsConfig( 6535): networkCode: 
,D/MmsConfig( 6535): packageName: com.htc.vvm.att does not exist,
,D/Messaging( 6535): mNeedToUpdateDate2 start,
,D/ReportIndicatorCache( 6535): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6535): 
,D/MmsAsyncWorkHandler( 6535): HM tk = 20001
D/ReportIndicatorCache( 6535): MSG_QUERY_REPORTS >>
,D/SettingsManager( 6535): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@cc212a5
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1543): sku_id=118
,D/DraftCache( 6535): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 6535): [DraftCache/1] refresh
,D/DraftCache( 6535): [DraftCache/156] DraftCache.constructor
,D/DraftCache( 6535): [DraftCache/156] refresh
D/DraftCache( 6535): [DraftCache/156] rebuildCache
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95,
D/MmsSmsV2Provider( 1543):  slotId = -1000
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 6535): mccmnc> 
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/MmsSmsV2Provider( 1543):  slotId = -1000
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,W/ContentService(  968): Observer android.database.IContentObserver$Stub$Proxy@4ed3e71 is already registered.
,W/ContentService(  968): Observer android.database.IContentObserver$Stub$Proxy@1e703456 is already registered.
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1543):  slotId = -1000
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 6535): networkCode: 
,D/Messaging( 6535): mNeedToUpdateDate2: false
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1543):  slotId = -1000
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 6535): ViewCache CreatePreloadOnlyConversationList,
,D/Messaging( 6535): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/Jerry   ( 1543): URI_DRAFT
,D/DraftCache( 6535): hasDraft() = false mNeedNotifyChange = true,
D/DraftCache( 6535): [DraftCache/156] rebuildCache time: 13
D/DraftCache( 6535): [DraftCache/156] rebuildCache
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/Jerry   ( 1543): URI_DRAFT
,D/MessageCustFlag( 6535): sense_version=6.0,
D/PhoneStorageUtil( 6535): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6535): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6535): createReceiver
D/Jerry   ( 6535): start to preload cursor >>>>>>>
,D/DraftCache( 6535): hasDraft() = false mNeedNotifyChange = false,
D/DraftCache( 6535): [DraftCache/156] rebuildCache time: 1
D/MmsAsyncWorkHandler( 6535): 
D/MmsAsyncWorkHandler( 6535): HM tk = 20002
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1543):  slotId = -1000
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
D/AccFlag ( 1543): sku_id=118
,D/Messaging( 6535): ViewCache CreatePreload
D/Messaging( 6535): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1543): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
,V/MmsProvider( 1543): Update uri=content://mms, match=0
V/MmsProvider( 1543): selection=st=129 AND m_type!=134
,D/Messaging( 6535): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6535): TransactionService is going to be woken up.
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95,
D/AccFlag ( 1543): sku_id=118
,D/Cust_MMSMS( 6535): _has_set_default_values_2=true
,V/TransactionService( 6535): 1-Creating TransactionService
,D/MsgPreferenceUtils( 6535): def_index: 0
,D/MsgPreferenceUtils( 6535): globalIndex = 1
,D/MsgPreferenceUtils( 6535): phone state: true
,D/MsgPreferenceUtils( 6535): sd state: false
D/MsgPreferenceUtils( 6535): vIndex = 0
,V/TransactionService( 6535): onStartCommand: 1
,D/MmsSystemEventReceiver( 6535): unRegisterForConnectionStateChanges
V/TransactionService( 6535): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
V/TransactionService( 6535): Loading previous transactions.
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1543): device_type: 1
,D/TransactionService( 6535): Force clearing mTransactionList,
D/TransactionService( 6535): Force set service start id to 1
V/TransactionService( 6535): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6535): unRegisterForConnectionStateChanges
D/TransactionService( 6535): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6535): Destroying TransactionService
,V/TransactionService( 6535): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/PMS     (  968): acquireWL(2a1e14ea): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
V/AlarmManager(  968): sending alarm PendingIntent{302a63db: PendingIntentRecord{707f4c4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=135090, Int=0
D/PMS     (  968): acquireWL(2db6e78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(2a1e14ea): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1955): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1955): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1955): [NET] android_getaddrinfo_proxy+
D/libc    ( 1955): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1955): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1955): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1955): [NET] android_getaddrinfofornet-, err=8
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  968): acquireWL(3be6c951): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/GpsLocationProvider(  968): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: false
D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  968): acquireWL(184095b6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
I/ConnectivityHelper( 1582): [onReceive] WIFI(1): CONNECTED
D/PMS     (  968): releaseWL(26067021): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/GCM     ( 1955): Connected
D/ConnectivityService(  968): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/PMS     (  968): releaseWL(2db6e78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  968): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6632 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  968): releaseWL(184095b6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(994fa24): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1955): Message class com.google.f.a.a.p
,E/GpsLocationProvider(  968): No APN found to select.
,D/PMS     (  968): releaseWL(3be6c951): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  968): acquireWL(147da98d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 968 1000 null
,D/PMS     (  968): releaseWL(994fa24): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(147da98d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MdScPhnSt( 6499): [818.1.]  listen tmrbb8
,D/MdScDataSum( 6499): [818.1.] summary 118:p1 ignore
,I/MusicStore( 6632): Database version: 120,
,D/VoldConnector(  968): SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  968): SND -> {29 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  968): SND -> {30 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6632): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6632): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6632): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6632): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6632): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36f56890: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6632): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6632): GMSCore installation verified
,I/ConfigStore( 6632): Config Database version: 1,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6632, uid=10159, userID:0,
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client,
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,D/MediaRouterService(  968): Client com.google.android.music (pid 6632): Registered
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,I/MediaRouter( 6632): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6632): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6632): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6632): type=WIFI subType= reason=null isConnected=true
,D/AutoSetting( 1640): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6632, uid=10159, userID:0
,I/art     (  968): Explicit concurrent mark sweep GC freed 51840(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 1.778ms total 170.994ms
,I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6669 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/AutoSetting( 1640): service - onCreate()
,D/AutoSetting( 1640): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate,
D/AutoSetting( 1640): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  968): request 234b0041 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,I/GHttpClientFactory( 6632): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/LocationManagerService(  968): provider request: passive ProviderRequest[ON interval=0],
,I/GoogleURLConnFactory( 6632): Using platform SSLCertificateSocketFactory
,D/PhoneMonitor( 6669): Register our PhoneStateListener
,D/Process (  968): killProcessQuiet, pid=4909
I/ActivityManager(  968): Killing 4909:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 4909
,D/MobileConnectivityChangeReceiver( 6669): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6669): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/Process (  968): killProcessQuiet, pid=6208
I/ActivityManager(  968): Killing 6208:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 6669): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6669): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  968): Recipient 6208,
,D/PMS     (  968): acquireWL(26941e77): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4505 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(363e2b4d): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4505 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(26941e77): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4505): Checking schedule, now: 1452019317210 next: 1452019280111,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4505, uid=10024, userID:0
I/CheckinService( 4505): active receiver: enabled
,I/CheckinService( 4505): Preparing to send checkin request,
I/EventLogService( 4505): Accumulating logs since 1452019246018
,D/ChimeraCfgMgr( 4505): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4505): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6700 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/CheckinRequestBuilder( 4505): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  968): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4505): Failed to find provider info for com.google.android.wearable.settings
,D/libc    ( 6474): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6474): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6474): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6474): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6474): [NET] android_getaddrinfo_proxy+
D/libc    ( 6474): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6474): [NET] android_getaddrinfo_proxy-, success
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
I/RemoteViews( 1223): reapply : com.google.android.gms 2 40
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
W/Kids    ( 4505): [AccountUtils] Account not ready
W/Kids    ( 4505): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.c(SourceFile:550)
,W/Kids    ( 4505): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4505): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4505): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4505): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4505): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4505): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 6474): connection state changed from UNKNOWN to CONNECTED
,D/VoldConnector(  968): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6700): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6700): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6700):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6700):   adb logcat -s GAv4
D/VoldConnector(  968): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6700): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  968): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6700): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  968): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6700): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6700): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6700): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6700): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/CheckinRequestBuilder( 4505): awaiting user notification for token
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/ActivityManager(  968): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6731 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/global  ( 6700): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6700): [apache-http] Connection GC has been deprecated!,
,I/art     (  441): Explicit concurrent mark sweep GC freed 8651(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 265us total 35.073ms,
,W/ResourcesManager( 6731): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6731): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  441): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 196us total 26.295ms,
,I/MultiDex( 6731): VM with version 2.1.0 has multidex support
I/MultiDex( 6731): install
I/MultiDex( 6731): VM has multidex support, MultiDex support library is disabled.
,I/art     (  441): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 145us total 16.391ms,
,V/JNIHelp ( 6731): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6731): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6731): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3da856: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6731): Installed default security provider GmsCore_OpenSSL
,I/WebViewFactory( 6700): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6700): Time to load native libraries: 2 ms (timestamps 7174-7176),
I/LibraryLoader( 6700): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6700): Binding Chromium to main looper Looper (main, tid 1) {29438ea9},
,I/LibraryLoader( 6700): Expected native library version number "",actual native library version number ""
,I/chromium( 6700): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6700): Initializing chromium process, singleProcess=true
,W/art     ( 6700): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6700): ApplicationContext is null in ApplicationStatus
,W/chromium( 6700): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6700): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6700): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6700): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6700): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6700): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6700): Local Branch: 
I/Adreno-EGL( 6700): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6700): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6700):                  d74aa161a12b9c6fc6332151
,E/WifiStateMachine(  968): handleMessage: E msg.what=131168,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): handleMessage: X
,I/WVCdm   (  401): CdmEngine::OpenSession,
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
,W/AudioManagerAndroid( 6700): Requires BLUETOOTH permission
,D/QSEECOMAPI: (  401): Loaded image: APP id = 8
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0,
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b50000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b50000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  540): got the req here! ret=0
D/DrmLibTime(  540): command id, time_cmd_id = 770
D/DrmLibTime(  540): time_getutcsec starts!
D/DrmLibTime(  540): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  540): QSEE Time Listener: get_utc_seconds
,D/DrmLibTime(  540): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  540): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  540): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  540): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  540): QSEE Time Listener: Retrieved Android system time: 1452019317
D/DrmLibTime(  540): time_getutcsec returns 0, sec = 1452019317; nsec = 0
D/DrmLibTime(  540): time_getutcsec finished! 
D/DrmLibTime(  540): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  540): before calling ioctl to read the next time_cmd
E/QC-time-services(  474): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/NSApplication( 6700): Starting up...
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
,D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf4c7a928
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1,
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab19d2f0, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab1cdc98, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0,
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab231968, idLength=0xf4d7a6f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6786 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  968): acquireWL(3716226a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE,
I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: true
D/GpsLocationProvider(  968): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
,D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4d7a70e, maximum = 0xf4d7a70f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4d7a77c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=395004036
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab21f238
,D/DrmWidevineDash(  401): message_length=1611, signature=0xab21f888, signature_length=0xf4d7a6dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/ConnectivityHelper( 1582): [onReceive] WIFI(1): CONNECTED
I/NetworkMonitor( 6632): type=WIFI subType= reason=null isConnected=true
,D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,E/GpsLocationProvider(  968): No APN found to select.
,D/PMS     (  968): releaseWL(3716226a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  968): acquireWL(17b7f7f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 968 1000 null
,D/PMS     (  968): releaseWL(17b7f7f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  968): Find DNS Address www.htc.com/104.85.244.81
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
D/MdScPhnSt( 6499): [dc7.1.]  listen tmrbb8
,D/MdScDataSum( 6499): [dc7.1.] summary 118:p1 ignore
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 8
,D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
,D/Process (  968): killProcessQuiet, pid=5762
I/ActivityManager(  968): Killing 5762:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/cutils-trace( 6815): Error opening trace file: Permission denied (13),
I/dex2oat ( 6815): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6815): dex2oat: override thread count:4
,I/ActivityManager(  968): Recipient 5762,
,I/dex2oat ( 6815): dex2oat took 79.714ms (threads: 4)
,I/Adreno-EGL( 6731): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
,I/Adreno-EGL( 6731): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6731): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6731): Local Branch: 
I/Adreno-EGL( 6731): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6731): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6731):                  d74aa161a12b9c6fc6332151
,D/GCM     ( 1955): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1955): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4505): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/Adreno-EGL( 6731): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6731): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6731): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6731): Local Branch: 
I/Adreno-EGL( 6731): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6731): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6731):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  968): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6825 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4505, uid=10024, userID:0,
,V/MusicLeanback( 6632): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/LocationInitializer( 4505): Restart initialization of location
,I/WVCdm   (  401): CdmEngine::OpenSession,
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/AutoSetting( 1640): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 6669): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6669): onReceive CONNECTIVITY_CHANGE networkType=1
D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
,E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  401): App is not loaded in QSEE
,D/AutoSetting( 1640): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1640): service - onStartCommand() screen is off, don't request location
W/ResourcesManager( 6825): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6825): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  968): acquireWL(3f71994b): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4505 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(3f71994b): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/QSEECOMAPI: (  401): Loaded image: APP id = 9
,D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
,D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b50000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b50000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  540): got the req here! ret=0
D/DrmLibTime(  540): command id, time_cmd_id = 770
D/DrmLibTime(  540): time_getutcsec starts!
D/DrmLibTime(  540): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  540): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  540): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  540): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  540): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  540): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  540): QSEE Time Listener: Retrieved Android system time: 1452019318
D/DrmLibTime(  540): time_getutcsec returns 0, sec = 1452019318; nsec = 0
D/DrmLibTime(  540): time_getutcsec finished! 
D/DrmLibTime(  540): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  540): before calling ioctl to read the next time_cmd
E/QC-time-services(  474): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/MultiDex( 6825): VM with version 2.1.0 has multidex support
I/MultiDex( 6825): install
I/MultiDex( 6825): VM has multidex support, MultiDex support library is disabled.
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,V/JNIHelp ( 6825): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf4c7a928
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab2ebd58, dataLength=8,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab1cdc98, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab231988, idLength=0xffbd8db8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xffbd8dce, maximum = 0xffbd8dcf
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/ActivityThread( 6825): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffbd8e3c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=3944109552
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab1e2458
D/DrmWidevineDash(  401): message_length=1646, signature=0xab1e2ad0, signature_length=0xffbd8d9c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/System  ( 6825): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3da856: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6825): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 6825): callingUid 10024, callindPid: 6825,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4505, uid=10024, userID:0,
,E/MDM     ( 1822): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ChimeraCfgMgr( 4505): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4505): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1,
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0,
,I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
D/GCM     ( 1955): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1955): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GmsCoreStatsServiceLauncher( 4505): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1822): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4505, uid=10024, userID:0,
,W/Kids    ( 4505): [AccountUtils] Account not ready
W/Kids    ( 4505): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4505): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4505): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4505): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4505): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4505): 	at java.lang.Thread.run(Thread.java:818)
,D/LocationInitializer( 4505): Restart initialization of location
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 2 40,
,I/CheckinRequestBuilder( 4505): Classify the device as Phone.,
,D/libc    ( 4505): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4505): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4505): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4505): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4505): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4505): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 4505): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4505): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4505): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4505): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4505): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4505): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4505): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4505): Sending checkin request (8401 bytes),
,I/CheckinRequestBuilder( 4505): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  968): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4505): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 1955): Explicit concurrent mark sweep GC freed 14443(780KB) AllocSpace objects, 7(588KB) LOS objects, 49% free, 4MB/8MB, paused 698us total 38.003ms,
,I/art     (  968): Explicit concurrent mark sweep GC freed 19018(901KB) AllocSpace objects, 4(272KB) LOS objects, 33% free, 16MB/25MB, paused 1.864ms total 134.355ms
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
,I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/CheckinRequestBuilder( 4505): awaiting user notification for token,
I/RemoteViews( 1223): reapply : com.google.android.gms 2 40
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/CheckinRequestBuilder( 4505): Classify the device as Phone.,
,I/CheckinTask( 4505): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4505): Checking schedule, now: 1452019319777 next: 1452556151757,
I/CheckinService( 4505): active receiver: disabled
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4505, uid=10024, userID:0,
,I/CheckinService( 4505): Checking schedule, now: 1452019319804 next: 1452556151757,
I/CheckinService( 4505): active receiver: disabled
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4505, uid=10024, userID:0
,D/PMS     (  968): releaseWL(363e2b4d): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,V/SetupWizard( 6669): Connected to Gservices successfully,
,D/ChimeraCfgMgr( 4505): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4505): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/GCM     ( 1955): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40,
,W/Kids    ( 4505): [AccountUtils] Account not ready,
W/Kids    ( 4505): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4505): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4505): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4505): 	at com.google.android.gms.kids.account.p.a(SourceFile:70),
W/Kids    ( 4505): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4505): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4505): 	at java.lang.Thread.run(Thread.java:818)
,D/PMS     (  968): acquireWL(145275a5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000},
V/AlarmManager(  968): sending alarm PendingIntent{1676c2dd: PendingIntentRecord{13de7e52 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=139440, Int=0,
,V/AlarmManager(  968): sending alarm PendingIntent{29928d7a: PendingIntentRecord{dd992b android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452019320459, Int=0,
D/PMS     (  968): acquireWL(5478188): PARTIAL_WAKE_LOCK  *backup* 0x1 968 1000 null
,W/BackupManagerService(  968): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
,E/BackupManagerService(  968): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  968): releaseWL(5478188): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/PMS     (  968): releaseWL(145275a5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/jxcore-log( 6413): Test app app.js loaded,
I/jxcore-log( 6413): 
,I/Choreographer( 6413): Skipped 519 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6413): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/PMS     (  968): acquireWL(a2c0746): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6632 10159 null,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6632, uid=10159, userID:0,
,D/PMS     (  968): releaseWL(a2c0746): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6632): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6632): Stop autocaching.
,E/GmsUtils( 6632): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6632): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Process (  968): killProcessQuiet, pid=6084
I/ActivityManager(  968): Killing 6084:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6084,
,I/ActivityManager(  968): Killing 5843:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  968): killProcessQuiet, pid=5843
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5843
,I/ActivityManager(  968): Killing 6258:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
D/Process (  968): killProcessQuiet, pid=6258
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6258,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/PMS     (  968): acquireWL(35a25cb8): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
,V/AlarmManager(  968): sending alarm PendingIntent{3cb1ba91: PendingIntentRecord{1baacdf6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144203, Int=0
,D/PMS     (  968): releaseWL(35a25cb8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  968): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  968): acquireWL(14bed5f7): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 968 1000 null
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  968): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  968): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  968): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  968):  [handleDownloadXtraData]inject done.
,D/PMS     (  968): acquireWL(900da93): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/PMS     (  968): releaseWL(14bed5f7): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  968): releaseWL(900da93): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/AccTypeManager( 1746): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead
,D/PMS     (  968): acquireWL(25548cef): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6474 10112 null
,D/AccTypeManager( 1746): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1582): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
,W/Prism.AllAppsManager( 1582): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1582): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1582): Deferring update until onResume
D/Launcher( 1582): waitUntilResume // bindAppsUpdated
,W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/AccTypeManager( 1746): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1543): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/ActivityManager(  968): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6884 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/PMS     (  968): releaseWL(25548cef): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
E/ExternalAccountType( 1746): Unsupported attribute readOnly
,W/ResourcesManager( 6474): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6474): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6474): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/PackageManager(  968): Unable to load service info ResolveInfo{26bb2ecf com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
,W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
,W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  968): 	,at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
,W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
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
,W/System  ( 6474): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6474): Installed default security provider GmsCore_OpenSSL
,I/BackupManagerService(  968): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,I/GCoreNlp( 1822): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,D/LocationProviderProxy(  968): applying state to connected service
,D/PMS     (  968): acquireWL(14f3288b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(14f3288b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  968): applying state to connected service
V/GmsNetworkLocationProvi( 1822): DISABLE
,D/PMS     (  968): acquireWL(8e9c267): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(76d5814): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(8e9c267): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(2ddcc8bd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(76d5814): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2ddcc8bd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/LocationManagerService(  968): getProviders()=[passive]
,I/ActivityManager(  968): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6914 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,I/[PluginManager]RegisterService( 1640): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1640): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  968): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6936 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6936, uid=10072, userID:0
,W/global  ( 6936): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 6936): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 6936): [apache-http] Connection GC has been deprecated!
,W/global  ( 6936): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6936): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  968): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6976 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 6936): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6936): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6936, uid=10072, userID:0
,W/ResourcesManager( 6976): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6976): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6976): VM with version 2.1.0 has multidex support
I/MultiDex( 6976): install,
I/MultiDex( 6976): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6936): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6936): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6936): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,V/JNIHelp ( 6976): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/PackageBroadcastService( 4505): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/PMS     (  968): acquireWL(17e0aab0): PARTIAL_WAKE_LOCK  AsyncService 0x1 5913 10167 null,
,I/PackageBroadcastService( 4505): Null package name or gms related package.  Ignoreing.
D/PMS     (  968): releaseWL(17e0aab0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Finsky  ( 6936): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PMS     (  968): acquireWL(1e26164f): PARTIAL_WAKE_LOCK  Icing 0x1 4505 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): acquireWL(11dc1dc): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5913 10167 null
,I/Icing   ( 4505): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  968): releaseWL(11dc1dc): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 6884): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,D/PMS     (  968): releaseWL(1e26164f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,W/ActivityThread( 6976): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6976): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3da856: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6976): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1955): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1955): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4505): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4505, uid=10024, userID:0
,D/WearableService( 6825): callingUid 10024, callindPid: 6825
,E/MDM     ( 1822): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4505): Restart initialization of location
,I/UpdateIcingCorporaServi( 6884): UpdateCorporaTask done [took 143 ms] updated apps [took 142 ms] ,
,I/art     (  968): Explicit concurrent mark sweep GC freed 23117(1330KB) AllocSpace objects, 4(220KB) LOS objects, 33% free, 16MB/25MB, paused 1.723ms total 156.220ms,
,I/ActivityManager(  968): Killing 6313:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
D/Process (  968): killProcessQuiet, pid=6313
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6313
,D/WifiService(  968): Client connection lost with reason: 4
,I/Prism.ItemManager( 1582): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1582): loadItems() com.htc.launcher.pageview.WidgetManager@2a16e26c +
I/Prism.WidgetManager( 1582): onLoadItems() +
,V/Finsky  ( 6936): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
W/ResourcesManager( 1582): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Finsky  ( 6936): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
D/PMS     (  968): acquireWL(5c35a0c): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10072}
V/AlarmManager(  968): sending alarm PendingIntent{2ae52f55: PendingIntentRecord{2638e501 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452019329007, Int=0
D/PMS     (  968): releaseWL(5c35a0c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6936): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
W/ResourcesManager( 1582): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6936): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,W/asset   ( 1582): Copying FileAsset 0x55c5455f30 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/AndroidHttpClient( 6936): Leak found,
E/AndroidHttpClient( 6936): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 6936): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 6936): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 6936): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 6936): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 6936): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 6936): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 6936): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 6936): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 6936): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 6936): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 6936): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 6936): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 6936): ,	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 6936): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 6936): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 6936): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/Prism.WidgetManager( 1582): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1582): onLoadItems() -
I/Prism.ItemManager( 1582): loadItems() com.htc.launcher.pageview.WidgetManager@2a16e26c -
,D/PhoneApp( 1543): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1543): -- N1 =0
,D/PhoneApp( 1543): -- N2 =0
,D/PhoneApp( 1543): -- N3 =0
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6936): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6936): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6936): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6936): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1822): client connected with version: 7571000
,D/Process (  968): killProcessQuiet, pid=6368,
I/ActivityManager(  968): Killing 6368:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6368,
,I/ActivityManager(  968): Killing 6535:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=6535
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  968): Recipient 6535
,D/Process (  968): killProcessQuiet, pid=6344
I/ActivityManager(  968): Killing 6344:com.htc.mobiledata/u0a46 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6344
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/PMS     (  968): acquireWL(120a5ca5): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10072}
,V/AlarmManager(  968): sending alarm PendingIntent{2341e87a: PendingIntentRecord{2041582b com.android.vending startService}}, i=null, t=0, cnt=1, w=1452019344261, Int=0
D/PMS     (  968): releaseWL(120a5ca5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/Finsky  ( 6936): [707] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 6936): [1] 5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1640): service - handleMessage() stop self,
,D/AutoSetting( 1640): service - handleMessage() quit looper
,D/AutoSetting( 1640): service - onDestroy() END
,E/WifiStateMachine(  968): handleMessage: E msg.what=131165,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
,E/WifiStateMachine(  968):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState,
E/WifiStateMachine(  968):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): handleMessage: X
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): acquireWL(f1d488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
D/UsbnetService(  968): onReceive BATTERY_CHANGED
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(f1d488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: DeviceActiveState
D/PMS     (  968): runPSCheck
D/WifiController(  968): processMsg: StaEnabledState
D/HtcPowerSaver(  968): Checking...
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  968): >> updateStatus
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1543): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131326,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState what:131326 2 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  968): handleMessage: X
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1640): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@25dfddc7,
D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  968): Killing 6499:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=6499
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6499
,D/PMS     (  968): acquireWL(3ee91e21): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000},
V/AlarmManager(  968): sending alarm PendingIntent{1676c2dd: PendingIntentRecord{13de7e52 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199441, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{29928d7a: PendingIntentRecord{dd992b android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452019387566, Int=0,
V/AlarmManager(  968): sending alarm PendingIntent{3ef61246: PendingIntentRecord{307b4c07 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=211177, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{a13b134: PendingIntentRecord{c987b5d com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189711, Int=0
D/PMS     (  968): acquireWL(19710cd2): PARTIAL_WAKE_LOCK  *backup* 0x1 968 1000 null
W/BackupManagerService(  968): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  968): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  968): releaseWL(19710cd2): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  968): acquireWL(376a1a3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
D/PMS     (  968): releaseWL(3ee91e21): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  968): acquireWL(5d4aca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(376a1a3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  968): releaseWL(5d4aca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): acquireWL(2e25642a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2e25642a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(2ceca21b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2ceca21b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(36076fb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(2584d191): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(1d2944f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(36076fb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1955): Vacuum at: now=1452019392027 tag=VacuumService
,I/GoogleURLConnFactory( 1955): Using platform SSLCertificateSocketFactory,
,D/PMS     (  968): releaseWL(2584d191): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(2f93f5cd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2f93f5cd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1955): No account for auth token provided
,D/PMS     (  968): acquireWL(724e82): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(724e82): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/art     ( 1955): Explicit concurrent mark sweep GC freed 25517(1454KB) AllocSpace objects, 5(420KB) LOS objects, 48% free, 4MB/8MB, paused 1.219ms total 65.548ms,
,D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1955): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1955): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1955): [NET] android_getaddrinfo_proxy+
D/libc    ( 1955): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1955): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1955): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1955): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1955): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1955): No account for auth token provided
,W/Uploader( 1955): No account for auth token provided,
,W/Uploader( 1955): No account for auth token provided,
,W/Uploader( 1955):  no longer exists, so no auth token.,
,W/Uploader( 1955): No account for auth token provided,
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
,E/Uploader( 1955): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1955): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1955): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1955): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1955): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1955): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1955): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1955): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1955): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1955): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1955): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1955): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1955): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/RemoteViews( 1223): reapply : com.google.android.gms 4 40
,W/Uploader( 1955): No account for auth token provided,
,D/PMS     (  968): releaseWL(1d2944f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(222c2ba6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(222c2ba6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(2a7f59e7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2a7f59e7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  968): acquireWL(1547d994): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
I/BatteryService(  968): n_update end
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): releaseWL(1547d994): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  968): updateBatteryInfo
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/PMS     (  968): runPSCheck
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  968): processMsg: StaEnabledState
,D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): processMsg: DefaultState
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: X
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1353): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 1353): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1353): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1353): wlan0: BSS: Remove id 1 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1353): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1353): wlan0: BSS: Remove id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 06:7c:34:12:7f:81]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 06:7c:34:12:7f:81
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11
,D/PMS     (  968): acquireWL(105aec3d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
D/UsbnetService(  968): BroadcastReceiver::onReceive+
I/BatteryService(  968): n_update end
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): releaseWL(105aec3d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/NotificationService(  968): plugged=true pluggin=true
D/WifiController(  968): handleMessage: E msg.what=155652
D/PMS     (  968): runPSCheck
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): processMsg: DeviceActiveState
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: X
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  968): << updateStatus
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6413): TAP version 13,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # multiplex can send data
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 1 String should be length:200,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # basic,
I/jxcore-log( 6413): 
,D/PMS     (  968): acquireWL(1edf5c32): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000},
,V/AlarmManager(  968): sending alarm PendingIntent{1676c2dd: PendingIntentRecord{13de7e52 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259441, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{1692fb00: PendingIntentRecord{70f0f39 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1452019522023, Int=0
,D/WeatherUtility( 1223): Weather sync is On
D/PMS     (  968): releaseWL(1edf5c32): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6413): ok 2 sane,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # another,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 3 sane,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # successfully create a new pkcs12 file and return hash value,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  968): acquireWL(1723097e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(1723097e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968): BroadcastReceiver::onReceive+,
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PMS     (  968): runPSCheck
D/WifiController(  968): handleMessage: E msg.what=155652
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): processMsg: DeviceActiveState
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  968): processMsg: DefaultState
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): handleMessage: X
I/HtcPowerSaver(  968): << updateStatus
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6413): ok 4 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 5 null,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 6 (unnamed assert),
I/jxcore-log( 6413): 
I/jxcore-log( 6413): ok 7 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 8 should not throw
I/jxcore-log( 6413): 
I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # successfully read a previous pkcs12 file and return hash value,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 9 (unnamed assert),
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 10 (unnamed assert),
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 11 should not throw
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 12 should be equal,
I/jxcore-log( 6413): 
I/jxcore-log( 6413): ok 13 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # failed to extract public key because of corrupt pkcs12 file,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 14 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup,
I/jxcore-log( 6413): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6413): # failed to get mobile documents path
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 15 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 16 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 17 should be equal
I/jxcore-log( 6413): 
I/jxcore-log( 6413): ok 18 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #init should register the networkChanged event
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 19 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup,
I/jxcore-log( 6413): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6413): # #startBroadcasting should throw on null device name
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 20 should throw
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 21 should throw
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 22 should throw
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6413): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 23 should throw
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #startBroadcasting should throw on negative port
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 24 should throw
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #startBroadcasting should throw on too large port
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 25 should throw
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 26 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 27 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 28 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6413): 
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1955): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1955): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1955): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1955): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1955): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1955): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1955): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 6936): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6936): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6936): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6936): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6936): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6936): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6936): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1312): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 6 40,
,W/System  ( 6936): Ignoring header User-Agent because its value was null.
,D/libc    ( 6936): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6936): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6936): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6936): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6936): [NET] android_getaddrinfo_proxy+
D/libc    ( 6936): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6936): [NET] android_getaddrinfo_proxy-, success
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 29 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 30 should be equal,
I/jxcore-log( 6413): 
I/jxcore-log( 6413): ok 31 should be equal
I/jxcore-log( 6413): 
I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 32 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 33 should be equal,
I/jxcore-log( 6413): 
I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error,
I/jxcore-log( 6413): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 34 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 35 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #connect should call Mobile("Connect") with a port and without an error,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6413): ok 36 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 37 should be equal,
,I/jxcore-log( 6413): 
I/jxcore-log( 6413): ok 38 should be equal
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # #connect should call Mobile("Connect") and handle an error,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 39 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 40 should be equal,
,I/jxcore-log( 6413): 
I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6413): # should call Mobile("Disconnect") without an error,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 41 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 42 should be equal,
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): ,
,I/jxcore-log( 6413): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
,I/jxcore-log( 6413): 
,I/jxcore-log( 6413): ok 43 should be equal
I/jxcore-log( 6413): ,
,I/jxcore-log( 6413): ok 44 should be equal
,I/jxcore-log( 6413): 
I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6413): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # teardown
I/jxcore-log( 6413): 
,D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699135.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699135.6413","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3091): BTA_JvCreateRecordByUser
D/bt-btm  ( 3091): BTM_AllocateSCN
D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
,I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699135.6413
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699135.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699135.6413","ra":"90:E7:C4:F6:69:77"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699135.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): start: OK
,I/jxcore-log( 6413): ok 45 Should be able to call startBroadcasting without error,
I/jxcore-log( 6413): 
I/io.jxcore.node.ConnectionHelper( 6413): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
I/bt-btif ( 3091): BTA_JvDeleteRecord
I/bt-btif ( 3091): BTA_JvRfcommStopServer
D/bt-btm  ( 3091): BTM_FreeSCN 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b048c608 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b048c608 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
D/WifiP2pService(  968): add a new client
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393133352e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393133352e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393133352e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393133351f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393133351f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393133351f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/WifiP2pService(  968): discovery change broadcast true
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 13,53): WPS: Building WPS IE for Probe Request
D/WifiP2pService(  968): InactiveState{ when=-4ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): WPS:  * Version (hardcoded 0x10)
D/WifiP2pService(  968): P2pEnabledState{ when=-4ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): WPS:  * Request Type
D/WifiP2pService(  968): P2pEnabledState clear service
D/wpa_supplicant( 1353): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1353): WPS:  * UUID-E
D/wpa_supplicant( 1353): WPS:  * Primary Device Type
D/wpa_supplicant( 1353): WPS:  * RF Bands (3)
D/wpa_supplicant( 1353): WPS:  * Association State
D/wpa_supplicant( 1353): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1353): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1353): WPS:  * Manufacturer
D/wpa_supplicant( 1353): WPS:  * Model Name
D/wpa_supplicant( 1353): WPS:  * Model Number
D/wpa_supplicant( 1353): WPS:  * Device Name
D/wpa_supplicant( 1353): WPS:  * Version2 (0x20)
D/WifiP2pService(  968): remove client information from framework
D/wpa_supplicant( 1353): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1353): P2P: * P2P IE header
D/WifiP2pService(  968): InactiveState{ when=-7ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1353): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1353): p2p0: Add radio work 'p2p-scan'@0x55a92c7aa0
D/wpa_supplicant( 1353): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1353): p2p0: Starting radio work 'p2p-scan'@0x55a92c7aa0 after 0.000068 second wait
D/wpa_supplicant( 1353): p2p0: nl80211: scan request
D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1353): nl80211: P2P probe - mask SuppRates
D/WifiP2pService(  968): mFlushDisabled: false
D/wpa_supplicant( 1353): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 1353): P2P: Running p2p_scan
D/wpa_supplicant( 1353): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1353): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1353): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1353): p2p0: Own scan request started a scan in 0.000092 seconds
I/wpa_supplicant( 1353): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  968): InactiveState{ when=-9ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/WifiP2pService(  968): P2pEnabledState{ when=-9ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=63 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  968): P2pEnabledState clear service request
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  968): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6413): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
D/WifiP2pService(  968): discovery change broadcast false
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393133351f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplica,nt( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393133351f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393133351f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Do not consider the scan results after stop_find
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-FIND-STOPPED 
D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699231.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699231.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3091): BTA_JvCreateRecordByUser
D/bt-btm  ( 3091): BTM_AllocateSCN
D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699231.6413
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699231.6413","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699231.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699231.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e8611b4e target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393233312e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e8611b4e target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393233312e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState add service
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393233312e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService(  968): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
D/WifiP2pService(  968): P2pEnabledState clear service
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393233311f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
I/io.jxcore.node.ConnectionHelper( 6413): start: OK
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393233311f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiP2pService(  968): remove client information from framework
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393233311f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
I/jxcore-log( 6413): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 6413): 
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/WifiP2pService(  968): mFlushDisabled: false
D/wpa_supplicant( 1353): P2P: p2p_scan is already running
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1353): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  968): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiP2pService(  968): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WifiP2pService(  968): P2pEnabledState clear service request
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6413): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
I/bt-btif ( 3091): BTA_JvDeleteRecord
I/bt-btif ( 3091): BTA_JvRfcommStopServer
D/bt-btm  ( 3091): BTM_FreeSCN 
D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
D/WifiP2pService(  968): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiP2pService(  968): discovery change broadcast false
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393233311f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393233311f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393233311f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6413): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P-FIND-STOPPED 
D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699292.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699292.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3091): BTA_JvCreateRecordByUser
D/bt-btm  ( 3091): BTM_AllocateSCN
D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699292.6413
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699292.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699292.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699292.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c9870f00 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393239322e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c9870f00 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393239322e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState add service
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393239322e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): add a new client
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393239321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...
D/WifiP2pService(  968): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): start: OK
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393239321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393239321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/wpa_supplicant( 1353): P2P: p2p_scan is already running
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiP2pService(  968): P2pEnabledState clear service
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=67 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6413): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 6413): 
I/io.jxcore.node.ConnectionHelper( 6413): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
I/bt-btif ( 3091): BTA_JvDeleteRecord
D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
D/WifiP2pService(  968): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
I/bt-btif ( 3091): BTA_JvRfcommStopServer
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
D/WifiP2pService(  968): Stop discovery in Inactive state
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
D/WifiP2pService(  968): mFlushDisabled: false
D/bt-btm  ( 3091): BTM_FreeSCN 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393239321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393239321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393239321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  968): discovery change broadcast false
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Stopping find
D/WifiP2pService(  968): P2pEnabledState clear service request
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
I/jxcore-log( 6413): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
,D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699356.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699356.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3091): BTA_JvCreateRecordByUser
D/bt-btm  ( 3091): BTM_AllocateSCN
D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
,I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699356.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699356.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699356.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699356.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393335362e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c05e73e target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393335362e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c05e73e target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393335362e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): P2pEnabledState add service
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393335361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  968): add a new client
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393335361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393335361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  968): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): start: OK
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/wpa_supplicant( 1353): P2P: p2p_scan is already running
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
,I/wpa_supplicant( 1353): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Failed to start p2p_scan - another p2p_scan was already running
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6413): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 6413): 
D/WifiP2pService(  968): P2pEnabledState clear service
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WifiP2pService(  968): remove client information from framework
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=69 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6413): stop
D/WifiP2pService(  968): Stop discovery in Inactive state
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
D/WifiP2pService(  968): mFlushDisabled: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
D/WifiP2pService(  968): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
,D/WifiP2pService(  968): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3091): BTA_JvDeleteRecord
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,I/bt-btif ( 3091): BTA_JvRfcommStopServer
D/WifiP2pService(  968): P2pEnabledState clear service request
D/bt-btm  ( 3091): BTM_FreeSCN 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393335361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
,D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393335361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393335361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=70 dispatchEvent: P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
,D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6413): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI,
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699409.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699409.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3091): BTA_JvCreateRecordByUser
,D/bt-btm  ( 3091): BTM_AllocateSCN
D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
,I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699409.6413
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699409.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699409.6413","ra":"90:E7:C4:F6:69:77"}
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b7198480 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699409.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b7198480 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393430392e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState add service
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393430392e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): add a new client
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393430392e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393430391f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393430391f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393430391f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): start: OK
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
I/jxcore-log( 6413): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 6413): 
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
,D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/wpa_supplicant( 1353): P2P: p2p_scan is already running
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1353): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1353): P2P: Failed to start p2p_scan - another p2p_scan was already running
I/io.jxcore.node.ConnectionHelper( 6413): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
D/WifiP2pService(  968): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
I/bt-btif ( 3091): BTA_JvDeleteRecord
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3091): BTA_JvRfcommStopServer
D/WifiP2pService(  968): P2pEnabledState clear service
D/bt-btm  ( 3091): BTM_FreeSCN 
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
D/WifiP2pService(  968): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
D/WifiP2pService(  968): Stop discovery in Inactive state
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393430391f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/WifiP2pService(  968): mFlushDisabled: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393430391f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393430391f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
D/WifiP2pService(  968): P2pEnabledState clear service request
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
D/WifiP2pService(  968): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
D/WifiP2pService(  968): discovery change broadcast false
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
I/jxcore-log( 6413): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=72 dispatchEvent: P2P-FIND-STOPPED 
D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699464.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699464.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3091): BTA_JvCreateRecordByUser
,D/bt-btm  ( 3091): BTM_AllocateSCN
D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699464.6413
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699464.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699464.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699464.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393436342e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6435c0be target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393436342e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027',
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6435c0be target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393436342e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): P2pEnabledState add service
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393436341f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  968): add a new client
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393436341f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393436341f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
D/WifiP2pService(  968): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): start: OK
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
,D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/wpa_supplicant( 1353): P2P: p2p_scan is already running
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
D/WifiP2pService(  968): P2pEnabledState clear service
I/wpa_supplicant( 1353): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1353): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6413): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 6413): 
I/io.jxcore.node.ConnectionHelper( 6413): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
I/bt-btif ( 3091): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 3091): BTA_JvRfcommStopServer
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
D/WifiP2pService(  968): remove client information from framework
D/bt-btm  ( 3091): BTM_FreeSCN 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
,D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/WifiP2pService(  968): Stop discovery in Inactive state
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393436341f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/WifiP2pService(  968): mFlushDisabled: false
I/jxcore-log( 6413): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393436341f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393436341f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
D/WifiP2pService(  968): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Stopping find
D/WifiP2pService(  968): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
,D/WifiP2pService(  968): P2pEnabledState clear service request
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): discovery change broadcast false
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
,E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=74 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
,D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699518.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699518.6413","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3091): BTA_JvCreateRecordByUser
D/bt-btm  ( 3091): BTM_AllocateSCN
D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
,I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699518.6413
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699518.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699518.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699518.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393531382e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@97f5a73e target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393531382e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@97f5a73e target=com.android.internal.util.StateMachine$SmHandler },
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393531382e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): P2pEnabledState add service
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393531381f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
,D/WifiP2pService(  968): add a new client
,D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393531381f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
,I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393531381f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): start: OK,
I/jxcore-log( 6413): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 6413): 
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/io.jxcore.node.ConnectionHelper( 6413): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  968): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
I/bt-btif ( 3091): BTA_JvDeleteRecord
I/bt-btif ( 3091): BTA_JvRfcommStopServer
D/bt-btm  ( 3091): BTM_FreeSCN 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
,D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/wpa_supplicant( 1353): P2P: p2p_scan is already running
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1353): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiP2pService(  968): P2pEnabledState clear service
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
,D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/WifiP2pService(  968): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393531381f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393531381f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
,I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393531381f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
,I/jxcore-log( 6413): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
,D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
D/WifiP2pService(  968): Stop discovery in Inactive state
D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
D/WifiP2pService(  968): mFlushDisabled: false
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
,E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Stopping find
D/WifiP2pService(  968): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): P2pEnabledState clear service request
,D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/WifiP2pService(  968): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE
D/WifiP2pService(  968): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699576.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699576.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3091): BTA_JvCreateRecordByUser,
D/bt-btm  ( 3091): BTM_AllocateSCN
D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699576.6413
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699576.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699576.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699576.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@df16bf36 target=com.android.internal.util.StateMachine$SmHandler },
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393537362e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@df16bf36 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393537362e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState add service
,I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393537362e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): add a new client
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393537361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393537361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393537361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
D/WifiP2pService(  968): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): start: OK
D/wpa_supplicant( 1353): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1353): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1353): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1353): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
,D/wpa_supplicant( 1353): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1353): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1353): p2p0: Scan completed in 0.389151 seconds
D/wpa_supplicant( 1353): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1353): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1353): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
,D/wpa_supplicant( 1353): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1353): p2p0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 1353): p2p0: BSS: Add new id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 1353): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1353): P2P: Ignore scan results
D/wpa_supplicant( 1353): p2p0: Radio work 'p2p-scan'@0x55a92c7aa0 done in 0.390270 seconds
,D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1353): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1353): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1353): WPS:  * Request Type
D/wpa_supplicant( 1353): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1353): WPS:  * UUID-E
D/wpa_supplicant( 1353): WPS:  * Primary Device Type
D/wpa_supplicant( 1353): WPS:  * RF Bands (3)
D/wpa_supplicant( 1353): WPS:  * Association State
D/wpa_supplicant( 1353): WPS:  * Configuration Error (0)
,D/wpa_supplicant( 1353): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1353): WPS:  * Manufacturer
D/wpa_supplicant( 1353): WPS:  * Model Name
D/wpa_supplicant( 1353): WPS:  * Model Number
D/wpa_supplicant( 1353): WPS:  * Device Name
D/wpa_supplicant( 1353): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1353): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1353): P2P: * P2P IE header
D/wpa_supplicant( 1353): P2P: * Capability dev=25 group=00
,D/wpa_supplicant( 1353): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1353): p2p0: Add radio work 'p2p-scan'@0x55a92c7aa0
D/wpa_supplicant( 1353): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1353): p2p0: Starting radio work 'p2p-scan'@0x55a92c7aa0 after 0.000093 second wait
D/wpa_supplicant( 1353): p2p0: nl80211: scan request
D/wpa_supplicant( 1353): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1353): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1353): P2P: Running p2p_scan
D/wpa_supplicant( 1353): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
,D/wpa_supplicant( 1353): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1353): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1353): p2p0: Own scan request started a scan in 0.000086 seconds
I/wpa_supplicant( 1353): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=79 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6413): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 6413): 
,I/io.jxcore.node.ConnectionHelper( 6413): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
I/bt-btif ( 3091): BTA_JvDeleteRecord
I/bt-btif ( 3091): BTA_JvRfcommStopServer
D/bt-btm  ( 3091): BTM_FreeSCN 
D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
D/WifiP2pService(  968): P2pEnabledState clear service
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393537361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
,D/WifiP2pService(  968): remove client information from framework
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393537361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393537361f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/WifiP2pService(  968): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Do not consider the scan results after stop_find
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=80 dispatchEvent: P2P-FIND-STOPPED 
D/WifiP2pService(  968): Stop discovery in Inactive state
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/WifiP2pService(  968): mFlushDisabled: false
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
I/jxcore-log( 6413): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Stopping find
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/WifiP2pService(  968): P2pEnabledState clear service request
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): discovery change broadcast false
,D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699647.6413
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699647.6413","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3091): BTA_JvCreateRecordByUser
D/bt-btm  ( 3091): BTM_AllocateSCN
,D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699647.6413
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699647.6413","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699647.6413","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699647.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393634372e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
,D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@964fad78 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393634372e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@964fad78 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393634372e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
D/WifiP2pService(  968): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6413): start: OK
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393634371f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393634371f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393634371f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
I/jxcore-log( 6413): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 6413): 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
,D/WifiP2pService(  968): discovery change broadcast true
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/wpa_supplicant( 1353): P2P: p2p_scan is already running
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1353): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1353): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=81 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6413): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/WifiP2pService(  968): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
I/bt-btif ( 3091): BTA_JvDeleteRecord
I/bt-btif ( 3091): BTA_JvRfcommStopServer
D/bt-btm  ( 3091): BTM_FreeSCN 
D/WifiP2pService(  968): remove client information from framework
D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
D/WifiP2pService(  968): Stop discovery in Inactive state
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/WifiP2pService(  968): mFlushDisabled: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393634371f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393634371f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393634371f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  968): P2pEnabledState clear service request
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): P2P: Stopping find
D/WifiP2pService(  968): discovery change broadcast false
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=82 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
,D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6413): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
,D/BluetoothAdapter( 6413): 209552008: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699692.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): bind: Binding a new listener
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699692.6413","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6413): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3091): BTA_JvCreateRecordByUser
,D/bt-btm  ( 3091): BTM_AllocateSCN
D/bt-sdp  ( 3091): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3091): BTA_JvRfcommStartServer
I/bt-btm  ( 3091): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3091):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): start: OK
I/io.jxcore.node.ConnectionHelper( 6413): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452019699692.6413
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Waiting for incoming connections...
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6413): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699692.6413","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452019699692.6413","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452019699692.6413","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393639322e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  968): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@34acf7f8 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393639322e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@34acf7f8 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323031393639393639322e36343133222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  968): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: INITIALIZED
D/WifiP2pService(  968): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): start: Starting P2P device discovery...
D/WifiP2pService(  968): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: true
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  968): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): start: OK
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393639321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): start: OK
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393639321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393639321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  968): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1353): [p2p command] (P2P_FIND 120)
,D/WifiP2pService(  968): P2pEnabledState clear service
D/wpa_supplicant( 1353): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1353): P2P: Starting find (type=0)
D/wpa_supplicant( 1353): P2P: p2p_scan is already running
,D/WifiP2pService(  968): remove client information from framework
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  968): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1353): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1353): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  968): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 6413): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6413): 
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=83 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  968): Stop discovery in Inactive state
I/io.jxcore.node.ConnectionHelper( 6413): stop
D/WifiP2pService(  968): mFlushDisabled: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6413): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6413): onServerStopped
D/WifiP2pService(  968): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3091): BTA_JvDeleteRecord
D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3091): BTA_JvRfcommStopServer
D/WifiP2pService(  968): P2pEnabledState clear service request
D/bt-btm  ( 3091): BTM_FreeSCN 
D/WifiP2pService(  968): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-sdp  ( 3091): SDP_DeleteRecord ok, num_records:15
,D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3091): BTM_SEC_CLR[19]: id 61
D/WifiP2pService(  968): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6413): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6413): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): stop: Stopping P2P device discovery...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
,I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6413): release: No more listeners, de-initializing...
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393639321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393639321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1353): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323031393639393639321f36343133222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1353): [p2p command] (P2P_STOP_FIND)
,D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1353): P2P-FIND-STOPPED 
D/wpa_supplicant( 1353): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6413): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6413): setState: NOT_STARTED
D/WifiMonitor(  968): Event [P2P-FIND-STOPPED ]
,E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=84 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  968): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1353): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1353): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1353): P2P: Stopping find
D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1353): P2P: Stopping find
,D/wpa_supplicant( 1353): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1353): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1353): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6413): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6413): 
,I/jxcore-log( 6413): # setup
I/jxcore-log( 6413): 
,I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6413): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6413): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6413): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6413): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6413): Service requests cleared successfully
,D/wpa_supplicant( 1353): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
,D/wpa_supplicant( 1353): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1353): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1353): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1353): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1353): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1353): p2p0: Scan completed in 0.409262 seconds
D/wpa_supplicant( 1353): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1353): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1353): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
D/wpa_supplicant( 1353): p2p0: BSS: Start scan result update 2
,D/wpa_supplicant( 1353): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1353): P2P: Ignore scan results
D/wpa_supplicant( 1353): p2p0: Radio work 'p2p-scan'@0x55a92c7aa0 done in 0.411464 seconds
,W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  968): acquireWL(26c14505): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(26c14505): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  968): plugged=true pluggin=true
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
,D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(a30195a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(a30195a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): handleMessage: E msg.what=155652
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,D/PowerUI ( 1223): closing low battery warning: level=100
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1543): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1543): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1543): sku_id=118
D/ContactMessageStore( 1543): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1543): start background delete task...,
,D/ContactMessageStore( 1543): size: 0 , 0,
D/ContactMessageStore( 1543): Background delete complete
,D/PMS     (  968): acquireWL(33d0678b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
,D/UsbnetService(  968): BroadcastReceiver::onReceive+,
I/BatteryService(  968): n_update end
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): releaseWL(33d0678b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  968): updateBatteryInfo
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/PMS     (  968): runPSCheck
D/WifiController(  968): processMsg: StaEnabledState
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): processMsg: DefaultState
,I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: X
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  968): << updateStatus
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1353): p2p0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1353): p2p0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=85 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,E/WifiMonitor(  968): WifiMonitor:p2p0 cnt=86 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  968): acquireWL(2fcaa068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  968): n_update end
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): releaseWL(2fcaa068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PMS     (  968): runPSCheck
D/HtcPowerSaver(  968): Checking...
I/HtcPowerSaver(  968): >> updateStatus
,D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
,D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(e962c81): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): releaseWL(e962c81): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/HtcPowerSaver(  968): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
,D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  968): acquireWL(24467126): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(24467126): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  968): updateBatteryInfo
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): onReceive BATTERY_CHANGED,
D/HtcPowerSaver(  968): Checking...
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  968): >> updateStatus
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiController(  968): battery changed pluggedType: 2
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
,D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(11dbf167): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(11dbf167): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  968): runPSCheck,
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  968): Checking...
I/HtcPowerSaver(  968): >> updateStatus
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  968): acquireWL(3add5b14): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
,V/AlarmManager(  968): sending alarm PendingIntent{1676c2dd: PendingIntentRecord{13de7e52 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379440, Int=0
I/bt-btm  ( 3091): Received oneshot timer event complete
V/AlarmManager(  968): sending alarm PendingIntent{7780fbd: PendingIntentRecord{2c1879b2 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941378, Int=0
I/bt-btm  ( 3091): btm_ble_timeout
D/PMS     (  968): acquireWL(d2c3d03): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3091 1002 null
,I/bt-btm  ( 3091): btm_gen_resolvable_private_addr
,D/WeatherUtility( 1223): Weather sync is On
,D/PMS     (  968): releaseWL(3add5b14): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/bt-btm  ( 3091): btm_ble_rand_enc_complete
I/bt-btm  ( 3091): btm_gen_resolve_paddr_low
,D/bt-smp  ( 3091): smp_encrypt_data
W/bt-smp  ( 3091): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3091): Plain text(LSB ~ MSB) = 31 39 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3091): Encrypted text(LSB ~ MSB) = 4f ac 1a 08 02 f4 fb 81 e2 8d 80 2e 4e c9 f4 34 
I/bt-btm  ( 3091): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3091): Stopping oneshot timer
D/bt-btm  ( 3091): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  968): releaseWL(d2c3d03): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  968): acquireWL(9bf1480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(9bf1480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
,D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
,D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(399aeab9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000},
V/AlarmManager(  968): sending alarm PendingIntent{1676c2dd: PendingIntentRecord{13de7e52 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=979441, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{3e907efe: PendingIntentRecord{20aba65f com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452020195051, Int=0
,I/ActivityManager(  968): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=7055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/WeatherUtility( 1223): Weather sync is On,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/SmartSyncUtils( 7055): isEpsOn(), nState = 0,
,D/PMS     (  968): acquireWL(240f8ac): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7055 1000 null,
,D/Process (  968): killProcessQuiet, pid=6282
I/ActivityManager(  968): Killing 6282:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/PMS     (  968): releaseWL(399aeab9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  968): releaseWL(240f8ac): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  968): acquireWL(2767975): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7055 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 7055): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 7055): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 7055): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 7055): SettingOnTime = 1452060000000, randomSettingOnTime = 1452056805000
,D/SmartSyncScreenOnOffTimeReceiver( 7055): SettingOffTime = 1452038400000, randomSettingOffTime = 1452043594000
,D/SmartSyncScreenOnOffTimeReceiver( 7055): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 7055): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 7055): bNightModeTurnOffOnce = false
,I/ActivityManager(  968): Recipient 6282
,D/PMS     (  968): releaseWL(2767975): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  968): acquireWL(af18d0a): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
V/AlarmManager(  968): sending alarm PendingIntent{218e497b: PendingIntentRecord{341af398 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1035454, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{3d895083: PendingIntentRecord{12516200 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804607, Int=0
,D/PMS     (  968): acquireWL(254237f1): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(254237f1): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  968): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7080 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  968): sending alarm PendingIntent{3fa36fd6: PendingIntentRecord{3a2e0257 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1452020002555, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{3097b144: PendingIntentRecord{2d567fcb com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452020148252, Int=0
,W/ContextImpl( 7055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  968): releaseWL(af18d0a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 7055): MY_DEBUG = false
,D/PowerUsageService( 7055): repeat time = 1452021116088
,I/art     (  968): Explicit concurrent mark sweep GC freed 40513(2MB) AllocSpace objects, 4(444KB) LOS objects, 33% free, 16MB/25MB, paused 1.780ms total 182.819ms
,D/PMS     (  968): acquireWL(36a66cf3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1955): Message class com.google.f.a.a.i
,D/PMS     (  968): releaseWL(36a66cf3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 7055): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 7055): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 7102): Error opening trace file: Permission denied (13)
I/dex2oat ( 7102): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7102): dex2oat: override thread count:4
,I/dex2oat ( 7102): dex2oat took 663.631ms (threads: 4),
,I/PushClient( 7080): ApplicationMonitor {1dec7046}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 7080): ApplicationMonitor {1dec7046}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 7080): ApplicationMonitor {1dec7046}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7080): ApplicationMonitor {1dec7046}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7080): ApplicationMonitor {1dec7046}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7080): ApplicationMonitor {1dec7046}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7080): ApplicationMonitor {1dec7046}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7080): ApplicationMonitor {1dec7046}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7080): ApplicationMonitor {1dec7046}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7080): PnsModel {c663421}: update(): Update registration caused by: alarm,
,I/PushClient( 7080): PnsConfigModel {174440cc}: <init>(): Use dm-client for provisioning.
,W/System.err( 7080): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 7080): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7080): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.,
,W/ContextImpl( 7080): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  968): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7109 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7109): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7109 dbg=false s=true
,I/DeviceManagement( 7109): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 7109): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7109): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 7109): WorkflowService: Starting workflow service
,I/DeviceManagement( 7109): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@c663421] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7109): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7109): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7109): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7109): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7109): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7109): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7109): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7109): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@c663421],
,I/DeviceManagement( 7109): WorkflowService: Stopping workflow service,
,I/ActivityManager(  968): Killing 6700:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=6700
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  968): Recipient 6700
,I/PushClient( 7080): PnsModel {c663421}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  968): Killing 6786:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=6786
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6786,
,D/PMS     (  968): acquireWL(205e2f47): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
D/UsbnetService(  968): BroadcastReceiver::onReceive+
I/BatteryService(  968): n_update end
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): releaseWL(205e2f47): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive-
,D/NotificationService(  968): plugged=true pluggin=true
D/WifiController(  968): handleMessage: E msg.what=155652
D/PMS     (  968): runPSCheck
D/WifiController(  968): processMsg: DeviceActiveState
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): processMsg: StaEnabledState
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: X
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  968): << updateStatus
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  968): acquireWL(126bf374): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(126bf374): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  968): handleMessage: E msg.what=155652
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
D/PMS     (  968): runPSCheck
D/WifiController(  968): processMsg: DeviceActiveState
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): processMsg: StaEnabledState
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  968): User[0] Flushing usage stats to disk
,D/PMS     (  968): acquireWL(3bdc309d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
I/BatteryService(  968): n_update end
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  968): releaseWL(3bdc309d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1312): [EventService] reorderNotification, total:1
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  968): updateBatteryInfo
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): closing low battery warning: level=98
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetPhoneState( 3091): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
I/HtcPowerSaver(  968): >> updateStatus
D/HeadsetStateMachine( 3091): Disconnected process message: 11, size: 0
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
W/ContextImpl( 7055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
D/WifiController(  968): processMsg: DeviceActiveState
I/HtcPowerSaver(  968): updateStatus (8000,98,-1,false,false,false,-1)
D/WifiController(  968): processMsg: StaEnabledState
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,D/TetherSettings( 5816): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5816): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5816): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5816): Cust_ConnectToPC   : spcsc>false
D/        ( 5816): Cust_ConnectToPC   : IPT>true
D/        ( 5816): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 5816): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false,
D/SmartNS_NSReceiver( 5816): Index of the first 1 = -1
,W/ContextImpl( 5816): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5816): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5816): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5816): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5816): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1223): status:2 level:98 unsupport:false plugged:true
D/SmartNS_Utility( 5816): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 5816): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/PMS     (  968): acquireWL(13c478e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
,I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(13c478e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  968): updateBatteryInfo
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=98
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
,D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
,D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:2 level:98 unsupport:false plugged:true,
,D/PMS     (  968): acquireWL(2a0ed2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
,I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(2a0ed2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  968): updateBatteryInfo
,D/PowerUI ( 1223): closing low battery warning: level=98
,D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  968): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(25d03999): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): releaseWL(25d03999): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): closing low battery warning: level=99
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/HtcPowerSaver(  968): updateBatteryInfo
D/WifiController(  968): handleMessage: X
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  968): runPSCheck
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/HtcPowerSaver(  968): Checking...
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  968): >> updateStatus
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  968): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:2 level:99 unsupport:false plugged:true,
,D/PMS     (  968): acquireWL(308b545e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(308b545e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  968): updateBatteryInfo
,D/DotMatrix( 1312): [EventService] reorderNotification, total:0
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3091): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3091): Disconnected process message: 11, size: 0
D/NotificationService(  968): plugged=true pluggin=true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  968): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
W/ContextImpl( 7055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5816): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5816): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5816): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5816): Cust_ConnectToPC   : spcsc>false
D/        ( 5816): Cust_ConnectToPC   : IPT>true
D/        ( 5816): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5816): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5816): Index of the first 1 = -1
W/ContextImpl( 5816): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 ,
,W/Settings( 5816): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5816): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5816): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5816): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(2d3e3d0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): releaseWL(2d3e3d0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  968): processMsg: DeviceActiveState
D/HtcPowerSaver(  968): updateBatteryInfo
D/WifiController(  968): processMsg: StaEnabledState
D/PMS     (  968): runPSCheck,
D/WifiController(  968): processMsg: DefaultState
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): handleMessage: X
I/HtcPowerSaver(  968): >> updateStatus
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1312): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1312): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3091): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/bt-btm  ( 3091): Received oneshot timer event complete
D/PMS     (  968): acquireWL(cb4586a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
I/bt-btm  ( 3091): btm_ble_timeout
V/AlarmManager(  968): sending alarm PendingIntent{1676c2dd: PendingIntentRecord{13de7e52 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1039440, Int=0
I/bt-btm  ( 3091): btm_gen_resolvable_private_addr
V/AlarmManager(  968): sending alarm PendingIntent{27b6215b: PendingIntentRecord{e181df8 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1841391, Int=0
D/PMS     (  968): acquireWL(3f3682d1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3091 1002 null
,D/bt-btm  ( 3091): btm_ble_rand_enc_complete,
I/bt-btm  ( 3091): btm_gen_resolve_paddr_low
D/bt-smp  ( 3091): smp_encrypt_data
W/bt-smp  ( 3091): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3091): Plain text(LSB ~ MSB) = 82 0a 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3091): Encrypted text(LSB ~ MSB) = cb c4 32 03 22 a3 3d f7 9a 39 8a 0f b7 96 86 97 
I/bt-btm  ( 3091): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3091): Stopping oneshot timer
D/bt-btm  ( 3091): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  968): Prepared write state in 14ms,
,I/ProcessStatsService(  968): Prepared write state in 13ms
,I/ProcessStatsService(  968): Prepared write state in 13ms
,D/PMS     (  968): releaseWL(cb4586a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/ProcessStatsService(  968): Pruning old procstats: /data/system/procstats/state-2016-01-05-08-53-48.bin,
,D/PMS     (  968): releaseWL(3f3682d1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  968): acquireWL(4b79136): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{1000}
V/AlarmManager(  968): sending alarm PendingIntent{3d895083: PendingIntentRecord{12516200 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1755512, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{1d478429: PendingIntentRecord{226df3ae android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1824536, Int=1800000,
D/PMS     (  968): acquireWL(362b7837): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
V/AlarmManager(  968): sending alarm PendingIntent{1676c2dd: PendingIntentRecord{13de7e52 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1879441, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{ad21a4: PendingIntentRecord{32cf7b0d com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452020707083, Int=1800000
V/AlarmManager(  968): sending alarm PendingIntent{12e38ac2: PendingIntentRecord{333560d3 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1855490, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{1c85bb09: PendingIntentRecord{2638e501 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452021079343, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{15e3910e: PendingIntentRecord{341af398 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1935705, Int=0
D/PMS     (  968): releaseWL(362b7837): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  968): updateNetworkEnabledLocked(),
D/Finsky  ( 6936): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/NetworkPolicy(  968): updateNotificationsLocked()
,V/AlarmManager(  968): sending alarm PendingIntent{26eb372f: PendingIntentRecord{2d567fcb com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452021116088, Int=0
,D/PMS     (  968): acquireWL(14caf528): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4505 10024 WorkSource{10024 com.google.android.gms},
V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  968): acquireWL(25e4b3e6): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4505 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(14caf528): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(2d6824c3): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2d6824c3): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): acquireWL(25d4140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 7055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  968): releaseWL(4b79136): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/LocationManagerService(  968): getAllProviders()=[passive, gps, network]
,D/PowerUsageList:PowerUsageHelper( 7055): MY_DEBUG = false
,D/PowerUsageService( 7055): repeat time = 1452022016374
,I/EventLogService( 4505): Aggregate from 1452019317282 (log), 1452018907031 (data)
,D/GCM     ( 1955): Message class com.google.f.a.a.i,
D/PMS     (  968): acquireWL(5b7e296): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(5b7e296): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(1fab83ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(25d4140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(25e4b3e6): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6936): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 7055): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 7055): gen(), null == sipper.uidObj, userId = 0,
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  968): releaseWL(1fab83ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(2ca5a759): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(2ca5a759): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  968): acquireWL(3a2d7f2a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(3a2d7f2a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6936): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1955): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1955): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1955): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1955): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1955): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6936): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6936): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6936): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 6936): [1] DailyHygiene.reschedule: Scheduling new run in 91 minutes (failures=3),
,D/DeviceConnectionService( 1822): client connected with version: 7571000,
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  968): Killing 6669:com.google.android.setupwizard/u0a77 (adj 13): empty for 1801s
D/Process (  968): killProcessQuiet, pid=6669
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  968): Recipient 6669
E/cutils-trace( 7154): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7154): ====startRecUseTime====
D/htc.customization.log.level( 7154):  is 
W/CustomizationLogLevel( 7154): Level value is invalid, use default level 2
D/CustomizationManager( 7154):  Read ACC file spent 0.035 (s)
D/CIDMapFileReader( 7154): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7154): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7154): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7154): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7154): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7154): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7154): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7154): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7154): Parsing tag category name = system
I/CustomizationCIDLoader( 7154): Parsing tag category name = application
I/CustomizationCIDLoader( 7154): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7154): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7154): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7154): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7154): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7154): add string-array item, value = 42507
I/CustomizationCIDLoader( 7154): add string-array item, value = 21902
I/CustomizationCIDLoader( 7154): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7154): add string-array item, value = 23420
I/CustomizationCIDLoader( 7154): add string-array item, value = 22299
I/CustomizationCIDLoader( 7154): add string-array item, value = 24002
I/CustomizationCIDLoader( 7154): add string-array item, value = 23210
I/CustomizationCIDLoader( 7154): add string-array item, value = 23205
I/CustomizationCIDLoader( 7154): add string-array item, value = 23806
I/CustomizationCIDLoader( 7154): add string-array item, value = 23430
I/CustomizationCIDLoader( 7154): add string-array item, value = 23408
I/CustomizationCIDLoader( 7154): add string-array item, value = 27205
I/CustomizationCIDLoader( 7154): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7154): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7154):  Read CID file spent 0.070 (s)
D/CustomizationManager( 7154):  All configurations done spent 0.070 (s)
D/PackageManager(  968): deletePackageAsUser: pkg=com.test.thalitest, pid=7154, uid=2000 userid=0
I/ActivityManager(  968): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  968): Killing 6413:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  968): killProcessQuiet, pid=6413
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  968): Skipping PackageSetting{18a5d664 com.example.hello/10374} due to missing metadata
I/ActivityManager(  968): Recipient 6413
I/WindowState(  968): WIN DEATH: Window{230ce9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  968): Client connection lost with reason: 4
D/Process (  968): killProcessQuiet, pid=6632
I/ActivityManager(  968): Killing 6632:com.google.android.music:main/u0a159 (adj 15): empty for 1800s
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  968): Recipient 6632
D/MediaRouterService(  968): Client com.google.android.music (pid 6632): Died!
I/ActivityManager(  968):   Force finishing activity ActivityRecord{22da1f1a u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  968): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  968):   Force finishing activity ActivityRecord{22da1f1a u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  968): Duplicate finish request for ActivityRecord{22da1f1a u0 com.test.thalitest/.MainActivity t8 f}
W/BroadcastQueue(  968): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  968): android.os.RemoteException: app.thread must not be null
W/BroadcastQueue(  968): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:467)
W/BroadcastQueue(  968): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:568)
W/BroadcastQueue(  968): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:645)
W/BroadcastQueue(  968): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:152)
W/BroadcastQueue(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  968): 	at android.os.Looper.loop(Looper.java:155)
W/BroadcastQueue(  968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  968): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/DotMatrix( 1312): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1312): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1312): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/ActivityManager(  968): Spurious death for ProcessRecord{ef1801 6413:com.test.thalitest/u0a366}, curProc for 6413: null
W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead
D/PMS     (  968): acquireWL(3cff88e7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1822): Ignoring removeGeofence because network location is disabled.
I/InputMethodManagerService(  968): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1746): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  968): releaseWL(3cff88e7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1746): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/art     ( 1582): Explicit concurrent mark sweep GC freed 24765(1481KB) AllocSpace objects, 11(848KB) LOS objects, 34% free, 29MB/45MB, paused 963us total 82.231ms
I/Prism.ItemManager( 1582): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1582): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1692): Cleaning up data for package: com.test.thalitest
I/Launcher( 1582): Deferring update until onResume
D/Launcher( 1582): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1582): action: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/[PluginManager]RegisterService( 1640): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/PhoneApp( 1543): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/AccTypeManager( 1746): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1640): handle notify Blinkfeed plugin client changed
I/ActivityManager(  968): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7174 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/ExternalAccountType( 1746): Unsupported attribute readOnly
I/art     (  968): Explicit concurrent mark sweep GC freed 37828(2MB) AllocSpace objects, 13(1152KB) LOS objects, 33% free, 16MB/25MB, paused 1.737ms total 216.449ms
I/art     (  968): WaitForGcToComplete blocked for 199.885ms for cause Explicit
W/PackageManager(  968): Unable to load service info ResolveInfo{eb1f6b6 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
W/ContextImpl( 7174): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  968): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
D/StatusBarManagerService(  968): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
D/FindExtension( 1582): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1582): Defer allocateBuffers to drawing time
D/JobSchedulerService(  968): Receieved: android.intent.action.PACKAGE_REMOVED
W/InputMethodManagerService(  968): Got RemoteException sending setActive(false) notification to pid 6413 uid 10366
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
D/TaskPersister(  968): removeObsoleteFile: deleting file=8_task.xml
I/art     (  968): Explicit concurrent mark sweep GC freed 7278(425KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 3.167ms total 176.776ms
E/NetworkScheduler.SchedulerReceiver( 1955): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1955): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  968): acquireWL(2bd3609b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1955 10024 WorkSource{10024 com.google.android.gms}
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/PMS     (  968): releaseWL(2bd3609b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/ChimeraCfgMgr( 4505): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4505): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 4505): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4505): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4505): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4505): Module APK com.google.android.play.games already loaded
I/ActivityManager(  968): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7212 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
I/LocationSettingsChecker( 4505): Removing dialog suppression flag for package com.test.thalitest
D/GOOGLEHELP_CompatibleDatabase( 4505): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4505): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4505): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4505): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4505): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4505): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4505): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4505): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4505): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4505): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4505): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4505): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4505): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/PMS     (  968): acquireWL(389af45a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4505 10024 null
I/ConfigService( 1955): onCreate
I/ConfigFetchService( 4505): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
W/BaseAppContext( 4505): Using Auth Proxy for data requests.
D/PMS     (  968): releaseWL(389af45a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
W/BaseAppContext( 4505): Using Auth Proxy for data requests.
D/PMS     (  968): acquireWL(96e5c03): PARTIAL_WAKE_LOCK  Icing 0x1 4505 10024 WorkSource{10024 com.google.android.gms}
I/PeopleContactsSync( 4505): CP2 sync disabled
I/Icing   ( 4505): doRemovePackageData com.test.thalitest
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4505, uid=10024, userID:0
D/PMS     (  968): releaseWL(96e5c03): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
W/DriveInitializer( 4505): Awaiting to be initialized
W/DriveInitializer( 4505): Background init thread started
D/VoldConnector(  968): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.gms/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
W/ContextImpl( 4505): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/art     ( 4505): Suspending all threads took: 19.230ms
W/DriveInitializer( 4505): Background init thread ended
I/GAv4    ( 7212): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7212):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7212):   adb logcat -s GAv4
I/art     ( 1955): Explicit concurrent mark sweep GC freed 34028(1902KB) AllocSpace objects, 10(604KB) LOS objects, 47% free, 4MB/8MB, paused 1.065ms total 56.537ms
W/GAv4    ( 7212): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7212): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7212): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 7212): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
E/SQLiteDatabase( 7212): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7212): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7212): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7212): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7212): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7212): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7212): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7212): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7212): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7212): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7212): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7212): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7212): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 7212): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7212): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7212): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7212): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7212): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7212): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7212): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7212): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7212): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7212): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7212): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7212): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7212): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7212): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 7212): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7212): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7212): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7212): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7212): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7212): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7212): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7212): 	at aen.run(PG:536)
E/SQLiteDatabase( 1955): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 1955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1955): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1955): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1955): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1955): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1955): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1955): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 1955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1955): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1955): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1955): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1955): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1955): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1955): Opened phenotype.db in read-only mode
E/SQLiteLog( 1955): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1955): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1955): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1955): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1955): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1955): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1955): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1955): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1955): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1955): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1955): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1955): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1955): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1955): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1955): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1955): 	at java.lang.Thread.run(Thread.java:818)
D/VoldConnector(  968): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
E/GAv4    ( 7212): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7212): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ContextImpl( 7212): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7212): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7212): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 7212): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 7212): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 7212): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 7212): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 7212): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7212): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7212): 	at aen.run(PG:536)
E/SQLiteDatabase( 7212): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7212): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7212): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7212): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7212): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7212): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7212): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7212): 	at aej.c(PG:139)
E/SQLiteDatabase( 7212): 	at aej.b(PG:398)
E/SQLiteDatabase( 7212): 	at agf.f(PG:417)
E/SQLiteDatabase( 7212): 	at oe.run(PG:1112)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7212): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 7212): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 7212): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7212): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7212): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7212): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7212): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7212): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7212): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7212): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 7212): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 7212): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 7212): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 7212): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7212): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7212): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7212): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 7212): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7212): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  968): acquireWL(1c2d4eae): PARTIAL_WAKE_LOCK  AsyncService 0x1 5913 10167 null
D/PMS     (  968): acquireWL(9e207dc): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5913 10167 null
D/PMS     (  968): releaseWL(1c2d4eae): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  968): releaseWL(9e207dc): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
I/ActivityManager(  968): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 7212 on display 0
V/JNIHelp ( 7212): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Process (  968): killProcessQuiet, pid=6731
I/ActivityManager(  968): Killing 6731:com.google.android.gms.unstable/u0a24 (adj 15): empty for 1800s
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityStackSupervisor.realStartActivityLocked:1143 
I/art     ( 7212): Background sticky concurrent mark sweep GC freed 5643(439KB) AllocSpace objects, 4(80KB) LOS objects, 4% free, 4MB/5MB, paused 6.082ms total 30.702ms
W/OpenGLRenderer( 1582): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/System  ( 7212): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7212): Installed default security provider GmsCore_OpenSSL
E/SQLiteDatabase( 7212): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7212): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7212): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7212): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7212): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7212): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7212): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7212): 	at aej.c(PG:139)
E/SQLiteDatabase( 7212): 	at aej.a(PG:358)
E/SQLiteDatabase( 7212): 	at aej.a(PG:345)
E/SQLiteDatabase( 7212): 	at agf.c(PG:884)
E/SQLiteDatabase( 7212): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 7212): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7212): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7212): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7212): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 7212): Failed to query Account133 object
E/AbstractDatabaseInstance( 7212): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7212): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7212): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7212): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7212): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7212): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7212): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7212): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 7212): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 7212): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 7212): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 7212): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 7212): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7212): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 7212): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7212): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7212): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7212): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7212): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7212): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7212): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7212): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7212): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7212): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7212): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 7212): java.lang.RuntimeException: An error occured while executing doInBackground()
E/CAKEMIX_CRASHED( 7212): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/CAKEMIX_CRASHED( 7212): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/CAKEMIX_CRASHED( 7212): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/CAKEMIX_CRASHED( 7212): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/CAKEMIX_CRASHED( 7212): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/CAKEMIX_CRASHED( 7212): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/CAKEMIX_CRASHED( 7212): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/CAKEMIX_CRASHED( 7212): 	at java.lang.Thread.run(Thread.java:818)
E/CAKEMIX_CRASHED( 7212): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 7212): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 7212): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 7212): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 7212): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 7212): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7212): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7212): 	at aej.c(PG:139)
E/CAKEMIX_CRASHED( 7212): 	at aej.a(PG:358)
E/CAKEMIX_CRASHED( 7212): 	at aej.a(PG:345)
E/CAKEMIX_CRASHED( 7212): 	at agf.c(PG:884)
E/CAKEMIX_CRASHED( 7212): 	at aii.doInBackground(PG:1063)
E/CAKEMIX_CRASHED( 7212): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/CAKEMIX_CRASHED( 7212): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/CAKEMIX_CRASHED( 7212): 	... 4 more

```
