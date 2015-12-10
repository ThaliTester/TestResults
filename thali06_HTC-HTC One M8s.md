#### Test 5065027881383b1_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
,I/ActivityManager(  953): Killing 5586:com.htc.musicenhancer/u0a49 (adj 15): empty #17
--------- beginning of main
D/Process (  953): killProcessQuiet, pid=5586
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2
I/ActivityManager(  953): Recipient 5586
E/cutils-trace( 6579): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6579): ====startRecUseTime====
D/htc.customization.log.level( 6579):  is 
W/CustomizationLogLevel( 6579): Level value is invalid, use default level 2
D/CustomizationManager( 6579):  Read ACC file spent 0.045 (s)
D/CIDMapFileReader( 6579): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6579): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6579): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6579): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6579): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6579): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6579): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6579): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6579): Parsing tag category name = system
I/CustomizationCIDLoader( 6579): Parsing tag category name = application
I/CustomizationCIDLoader( 6579): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6579): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6579): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6579): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6579): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6579): add string-array item, value = 42507
I/CustomizationCIDLoader( 6579): add string-array item, value = 21902
I/CustomizationCIDLoader( 6579): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6579): add string-array item, value = 23420
I/CustomizationCIDLoader( 6579): add string-array item, value = 22299
I/CustomizationCIDLoader( 6579): add string-array item, value = 24002
I/CustomizationCIDLoader( 6579): add string-array item, value = 23210
I/CustomizationCIDLoader( 6579): add string-array item, value = 23205
I/CustomizationCIDLoader( 6579): add string-array item, value = 23806
I/CustomizationCIDLoader( 6579): add string-array item, value = 23430
I/CustomizationCIDLoader( 6579): add string-array item, value = 23408
I/CustomizationCIDLoader( 6579): add string-array item, value = 27205
I/CustomizationCIDLoader( 6579): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6579): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6579):  Read CID file spent 0.096 (s)
D/CustomizationManager( 6579):  All configurations done spent 0.096 (s)
I/ActivityManager(  953): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6579 on display 0
D/PMS     (  953): acquireHCC(17c1fc5e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 953 1000 null
D/PMS     (  953): acquireHCC(731483f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 953 1000 null
I/ActivityManager(  953): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6597 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  953): Display changed displayId=0
D/DotMatrix( 1307): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1307): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1502): [trimMemory] 20
I/WebViewFactory( 6597): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6597): Time to load native libraries: 9 ms (timestamps 517-526),
,I/LibraryLoader( 6597): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6597): Binding Chromium to main looper Looper (main, tid 1) {262f0ee5},
I/LibraryLoader( 6597): Expected native library version number "",actual native library version number ""
,I/chromium( 6597): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6597): Initializing chromium process, singleProcess=true,
,W/art     ( 6597): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6597): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6597): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6597): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6597): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6597): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6597): OpenGL ES Shader Compiler Version: E031.25.03.01
,I/Adreno-EGL( 6597): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6597): Local Branch: 
I/Adreno-EGL( 6597): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6597): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6597):                  d74aa161a12b9c6fc6332151
,W/System.err(  953): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@243468d3:true
W/System.err(  953): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  953): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  953): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  953): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6597): 927380577: getState(). Returning 12
,W/art     ( 6597): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6597): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6597): CordovaWebView is running on device made by: HTC
,W/art     ( 6597): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6597): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6597): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/HtcSystemUPManager(  953): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  953): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
,D/StatusBarManagerService(  953): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
,D/FindExtension( 6597): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6597): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2516f537, mServedView=org.apache.cordova.engine.SystemWebView{29075aa4 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3497c00d,
I/InputMethodManagerService(  953): Disable input method client, pid=1502
,I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
,D/StatusBarManagerService(  953): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6597): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  953): Displayed com.test.thalitest/.MainActivity: +649ms (total +693ms),
,W/BindingManager( 6597): Cannot call determinedVisibility() - never saw a connection for the pid: 6597,
,D/JsMessageQueue( 6597): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6597): JniHelper::setJavaVM(0xab1ee8f8), pthread_self() = -1403988376,
D/JX-Cordova( 6597): jxcore cordova android initializing
,W/jxcore-log( 6597): Initializing JXcore engine,
W/jxcore-log( 6597): JXcore engine is ready
,W/jxcore-log( 6597): Starting JXcore engine
,W/jxcore-log( 6597): Platform android,
W/jxcore-log( 6597): 
W/jxcore-log( 6597): Process ARCH arm
W/jxcore-log( 6597): 
,D/PMS     (  953): releaseHCC(17c1fc5e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  953): releaseHCC(731483f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6597): JXcore Cordova bridge is ready!
I/jxcore-log( 6597): 
W/jxcore-log( 6597): JXcore engine is started
,I/Choreographer( 6597): Skipped 99 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 6597): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6597): Toggling radios to true,
I/jxcore-log( 6597): 
,D/BluetoothAdapter( 6597): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  953): ADD_CLIENT: 8,
D/WifiService(  953): New client listening to asynchronous messages
D/WifiManager( 6597): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/WifiService(  953): setWifiEnabled: true pid=6597, uid=10366,
E/WifiService(  953): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  953): MONITOR_LOG
I/WifiService(  953): isSprintWifiRestricted(): false
W/Settings:Agent(  953): name: wifi_on
I/WifiService(  953): isMdmWifiRestricted(): false
W/Settings:Agent(  953): value: 2
W/Settings:Agent(  953): >> traceCallingStack()
W/Settings:Agent(  953): Process.myPid(): 953
W/Settings:Agent(  953): Process.myTid(): 1159
W/Settings:Agent(  953): Process.myUid(): 1000
W/Settings:Agent(  953): 
W/Settings:Agent(  953): 
W/System.err(  953): java.lang.Throwable: stack dump
,W/System.err(  953): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  953): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  953): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,W/System.err(  953): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  953): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  953): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  953): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  953): ,	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  953): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  953): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
,W/System.err(  953): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  953): 
W/Settings:Agent(  953): << traceCallingStack(): 14(ms)
D/WifiController(  953): handleMessage: E msg.what=155656
D/WifiController(  953): processMsg: DeviceActiveState
,D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): handleMessage: X
D/WifiManager( 6597): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  953): handleMessage: E msg.what=131145
E/WifiStateMachine(  953): processMsg: ConnectedState
D/WifiManager( 6597): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  953):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
,E/WifiStateMachine(  953):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1338): wlan0: Cancelling scan request
D/wpa_supplicant( 1338): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1338): TDLS: Tear down peers
D/wpa_supplicant( 1338): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6597): Radios toggled
I/jxcore-log( 6597): 
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6597): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6597): 
,I/jxcore-log( 6597): Perf Test app loaded loaded,
I/jxcore-log( 6597): 
,I/jxcore-log( 6597): check test folder,
I/jxcore-log( 6597): 
I/jxcore-log( 6597): found test : ./testFindPeers.js
I/jxcore-log( 6597): 
,D/wpa_supplicant( 1338): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1338): wlan0: Deauthentication notification
D/wpa_supplicant( 1338): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1338): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1338): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1338): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1338): enter disconnect check
I/wpa_supplicant( 1338): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1338): wlan0: Auto connect disabled: do not try to re-connect
,D/wpa_supplicant( 1338): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  953): interfaceLinkStateChanged wlan0, false
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/Tethering(  953): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  953): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  953): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  953): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/Tethering(  953): interfaceLinkStateChanged wlan0, false,
D/Tethering(  953): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  953): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  953): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  953): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1338): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1338): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a005cf88 key_idx=0 set_tx=0 seq_len=0 key_len=0
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
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1338): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1338): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1338): nl80211: Ignore disconnect event triggered during reassociation
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  953): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  953): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  953): handleMessage: new destination call exit/enter
E/WifiStateMachine(  953): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  953): invokeExitMethods: ConnectedState
E/WifiStateMachine(  953): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  953): release()
D/Tethering(  953): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  953): PerfLock released for exiting ConnectedState
D/UsbnetService(  953): BroadcastReceiver::onReceive+
,D/UsbnetService(  953): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbDeviceManager(  953): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
E/WifiStateMachine(  953): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
D/PMS     (  953): acquireWL(1784196c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 953 1000 null
E/WifiStateMachine(  953): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  953): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  953): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  953): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  953): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  953): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/WifiP2pService(  953): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/WifiP2pService(  953): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  953): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1338): Power_Mode_Type mode = 0
I/wpa_supplicant( 1338): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  953): setDhcpActive: false
V/NativeCrypto( 1878): Read error: ssl=0x55ace008c0: I/O error during system call, Connection timed out
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
,D/PMS     (  953): acquireWL(1885eb35): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
D/TetherSettings( 5870): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5870): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5870): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5870): Cust_ConnectToPC   : spcsc>false
D/        ( 5870): Cust_ConnectToPC   : IPT>true
D/        ( 5870): Cust_ConnectToPC   : Singel_USB>false
,E/WifiStateMachine(  953): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  953): setDetailed state send new extra info<unknown ssid>
,E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  953): NetworkAgent != null
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  953): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 13
,V/NetworkPolicy(  953): mWifiStateReceiver: meteredHint=false,EPS mode=false
W/Settings( 5870): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NativeCrypto( 1878): SSL shutdown failed: ssl=0x55ace008c0: I/O error during system call, Broken pipe
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
,E/SmartNS_Utility( 5870): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 5870): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  953): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/SmartNS_NSReceiver( 5870): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/ConnectivityService(  953): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  953): autoRoamSetBSSID any key="NG700"WPA_PSK
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiConfigStore(  953): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  953): QCOM Debug skip set_network part for security concern!
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WifiDataStallTracker(  953): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  953): stopDataStallAlarm 
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  953): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): ValidatedState{ when=-2ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): DefaultState{ when=-4ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): Validated
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  953): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  953): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  953): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  953):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  953): Start Disconnecting Watchdog 1
E/WifiStateMachine(  953): handleMessage: X
,E/WifiStateMachine(  953): handleMessage: E msg.what=131146
E/WifiStateMachine(  953): processMsg: DisconnectingState
E/WifiStateMachine(  953):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/PMS     (  953): releaseWL(1885eb35): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  953):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1338): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1338): Fast associate: Old scan results
D/wpa_supplicant( 1338): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1338): wpa_supplicant_scan enter
D/wpa_supplicant( 1338): wlan0: State: DISCONNECTED -> SCANNING
,D/wpa_supplicant( 1338): wlan0: Starting AP scan for wildcard SSID
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
D/wpa_supplicant( 1338): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1338): wlan0: Add radio work 'scan'@0x55a003f860
D/wpa_supplicant( 1338): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1338): wlan0: Starting radio work 'scan'@0x55a003f860 after 0.000062 second wait
D/wpa_supplicant( 1338): wlan0: nl80211: scan request
D/wpa_supplicant( 1338): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1338): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1338): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1338): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1338): wlan0: Own scan request started a scan in 0.000164 seconds
I/wpa_supplicant( 1338): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147460
E/WifiStateMachine(  953): processMsg: DisconnectingState
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  953): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  953): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/WifiStateMachine(  953):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=134184
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  953): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  953): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  953):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=134185
E/WifiStateMachine(  953): ConnectModeState: Network connection lost 
E/WifiStateMachine(  953): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  953): handleMessage: new destination call exit/enter
E/WifiStateMachine(  953): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  953): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  953): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  953): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  953): invokeEnterMethods: DisconnectedState,
E/WifiStateMachine(  953): DisconnectedState call setCountryCode()
E/WifiStateMachine(  953):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1338): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1338): wlan0: Cancelling scan request
,D/PMS     (  953): releaseWL(1784196c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  953): updateNetworkEnabledLocked()
V/NetworkPolicy(  953): updateNotificationsLocked()
,I/jxcore-log( 6597): found test : ./testSendData.js
I/jxcore-log( 6597): 
,W/ContextImpl( 5870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5870): setISNotification
,D/SmartNS_Utility( 5870): usb_cable_connect = 1
,D/SmartNS_Utility( 5870): usb_denied = 0
,I/SmartNS_PSService( 5870): usb notificaiton:true
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 5870): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/wpa_supplicant( 1338): wlan0: nl80211: sched_scan request
,D/SmartNS_Utility( 5870): usb_cable_connect = 1
D/SmartNS_Utility( 5870): usb_denied = 0
I/SmartNS_PSService( 5870): usb notificaiton:true
,E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1219): reapply : com.android.settings 0 36
,I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1,
,D/SmartNS_NSReceiver( 5870): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/wpa_supplicant( 1338): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec,
D/wpa_supplicant( 1338): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1338): wlan0: nl80211: Sched scan started
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147462
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=134238  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  953): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  953): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  953): processMsg: ConnectModeState
I/RemoteViews( 1219): reapply : com.android.settings 1 36
E/WifiStateMachine(  953):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=134238  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131101
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine(  953): processMsg: SupplicantStartedState
D/wpa_supplicant( 1338): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1338): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1338): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1338): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1338): Got an original EVENT_SCAN_RESULTS
E/WifiStateMachine(  953):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1338): wlan0: Scan completed in 0.056439 seconds
E/WifiStateMachine(  953): processMsg: DefaultState
D/wpa_supplicant( 1338): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1338): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
D/wpa_supplicant( 1338): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1338): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1338): wlan0: New scan results available (own=1 ext=0)
E/WifiStateMachine(  953):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  953): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  953): handleMessage: X
D/WifiNetworkAgent(  953): NetworkAgent: NetworkAgent channel lost
D/wpa_supplicant( 1338): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1338): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1338): wlan0: Radio work 'scan'@0x55a003f860 done in 0.058015 seconds
E/WifiStateMachine(  953): handleMessage: E msg.what=131212
E/WifiStateMachine(  953): processMsg: DisconnectedState
D/wpa_supplicant( 1338): wlan0: Selecting BSS from priority group 282
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1338): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58 wps
D/wpa_supplicant( 1338): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
E/WifiMonitor(  953): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1338): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1338): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1338):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1338): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/WifiMonitor(  953): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 1338): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55a005ec00  current_ssid=0x0
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=38 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1338): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wpa_supplicant_set_is_wep_security: 0
W/WifiMonitor(  953): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1338): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1338): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 1338): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1338): wlan0: Add radio work 'connect'@0x55a003f860
E/WifiStateMachine(  953):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1338): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/wpa_supplicant( 1338): wlan0: Starting radio work 'connect'@0x55a003f860 after 0.000060 second wait
I/wpa_supplicant( 1338): check if in concurrent case
I/wpa_supplicant( 1338): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  953):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  953): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131212
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/WifiMonitor(  953): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=39 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  953):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
D/wpa_supplicant( 1338): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1338): wlan0: Cancelling sched scan
E/WifiStateMachine(  953):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
D/wpa_supplicant( 1338): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1338): wlan0: Cancelling scan request
D/wpa_supplicant( 1338): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1338): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1338): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1338): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1338): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1338): RSN: PMKSA cache search - network_ctx=0x55a005ec00 try_opportunistic=0
D/wpa_supplicant( 1338): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1338): wlan0: RSN: using IEEE 802.11i/D9.0
E/WifiStateMachine(  953):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1338): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1338): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1338): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1338): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1338): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1338): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1338): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1338): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1338): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1338): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1338): nl80211: Unsubscribe mgmt frames handle 0x888888dd288d6989 (mode change)
D/wpa_supplicant( 1338): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a005e100
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=0104
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=040a
E/WifiStateMachine(  953): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  953): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=040b
E/WifiStateMachine(  953): handleMessage: X
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=040c
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=040d
E/WifiStateMachine(  953): handleMessage: E msg.what=131212
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=090a
E/WifiStateMachine(  953): processMsg: DisconnectedState
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=090b
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=090c
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=090d
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=0409506f9a09
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=7f506f9a09
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=0801
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=040e
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=06
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=0a07
E/WifiStateMachine(  953):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=0a11
D/wpa_supplicant( 1338): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a005e100 match=0a1a
D/wpa_supplicant( 1338): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1338):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338):   * freq=2412
D/wpa_supplicant( 1338):   * freq_hint=2412
D/wpa_supplicant( 1338):   * SSID - hexdump(len=5): 4e 47 37 30 30
E/WifiStateMachine(  953):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
D/wpa_supplicant( 1338):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1338):   * WPA Versions 0x2
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1338):   * pairwise=0xfac04
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1338):   * group=0xfac04
D/wpa_supplicant( 1338):   * akm=0xfac02
D/wpa_supplicant( 1338):   * Auth Type 0
D/wpa_supplicant( 1338): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55a005ec3a
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  953): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  953): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  953):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  953): processMsg: DefaultState
D/wpa_supplicant( 1338): nl80211: Connect request send successfully
D/wpa_supplicant( 1338): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1338): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1338): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1338): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1338): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1338): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1338): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  953):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  953): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147462
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=134248  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  953): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  953): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  953): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  953): NetworkAgent == null
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=134250  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  953): handleMessage: X
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  953): handleMessage: E msg.what=147461
E/WifiStateMachine(  953): processMsg: DisconnectedState
D/WISPrService( 5870): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  953):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:2126 bcn=0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:2126 bcn=0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:2126 bcn=0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:2126 bcn=0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1338): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  953): [1,449,752,967,577 ms] noteScanEnd no scan source
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1338): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  953): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@32fea51d sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  953): NG7005g c0:ff:d4:d3:aa:4a rssi=-46 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
D/WifiService(  953): New client listening to asynchronous messages
E/WifiAutoJoinController (  953): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  953): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  953): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  953):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  953): Gonzos 38:f8:89:11:e9:11 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  953): UPC503894600 a0:c5:62:7a:49:97 rssi=-87 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiTrafficPoller(  953): ADD_CLIENT: 9
E/WifiAutoJoinController (  953): ageScanResultsOut delay 40000 size 4 now 1449752967581
E/WifiAutoJoinController (  953): newSupplicantResults size=4 known=1 true
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1338): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  953): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  953): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  953): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  953): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  953): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  953):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131213
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState CMD_TARGET_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=134269
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_TARGET_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=134269
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_TARGET_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=134269
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState CMD_TARGET_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=134270
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147462
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=134270  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  953): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  953): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  953): setDetailed state send new extra info0x
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  953): NetworkAgent == null
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  953):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=134275  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  953): handleMessage: X
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  953): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  953): handleMessage: E msg.what=131131
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  953): processMsg: DisconnectedState
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  953): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524292
D/Nat464Xlat(  953): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
E/WifiStateMachine(  953):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  953): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  953): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): Disconnected - quitting
I/SecurityController( 1219): onLost 100
E/WifiStateMachine(  953):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  953): handleMessage: X
D/WIFI    (  953): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  953): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  953):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  953): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI    (  953):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  953): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  953): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/NetworkManagementService(  953): Removing idletimer
D/PMS     (  953): acquireWL(33d1713b): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 953 1000 null
D/CSLegacyTypeTracker(  953): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/WISPrService( 5870): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5870): trigger connection
D/WISPrService( 5870): continue
D/ConnectivityService(  953): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  953): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/ConnectivityService(  953): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  953): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  953): ensureActiveMobilePolicyLocked()
D/PMS     (  953): acquireWL(2f4f6058): PARTIAL_WAKE_LOCK  NetworkStats 0x1 953 1000 null
E/ConnectivityService(  953): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/DATA_ICON( 1219): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/DATA_ICON( 1219): dataConnected: false/false
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkPolicy(  953): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/WISPrService( 5870): start DataConnection
V/NetworkPolicy(  953): updateNetworkEnabledLocked()
D/libc    ( 5870): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
V/NetworkPolicy(  953): updateIfacesLocked()
D/libc    ( 5870): [NET] android_getaddrinfofornet-, err=8
V/NetworkPolicy(  953): updateNotificationsLocked()
D/libc    ( 5870): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/NetworkManagementService(  953): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/libc    ( 5870): [NET] android_getaddrinfofornet-, pass to proxy
D/PMS     (  953): releaseWL(2f4f6058): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/libc    ( 5870): [NET] android_getaddrinfo_proxy+
V/NetworkPolicy(  953): updateNetworkEnabledLocked()
V/NetworkPolicy(  953): updateNotificationsLocked()
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    ( 5870): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5870): [NET] android_getaddrinfo_proxy-, NODATA
D/FlexNetS( 6372): updateSvcAllowedInSettings:false
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/FlexNetS( 6372): updateSvcAllowedInSettings:false,
,I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
I/ActivityManager(  953): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6662 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
,D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/FlexNetS( 6372): updateSvcAllowedInSettings:false
D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/chromium( 6597): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/libc    ( 5870): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 5870): [NET] android_getaddrinfofornet-, err=8
,D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/WISPrService( 5870): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/wpa_supplicant( 1338): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1338): WEXT: Custom wireless event: 'BEACONIEs='
,D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1338): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1338): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1338): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1338): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1338): nl80211: Connect event
D/wpa_supplicant( 1338): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1338): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1338): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1338): wlan0: Association info event
D/wpa_supplicant( 1338): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): wlan0: freq=2412 MHz
D/wpa_supplicant( 1338): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1338): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1338): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1338): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1338): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1338): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1338): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1338): TDLS: Remove peers on association
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1338): EAPOL: External notification - EAP success=0
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1338): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1338): EAPOL: SUPP_PAE entering state CONNECTING
D/HTCRequest(  953): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1338): EAPOL: enable timer tick
D/wpa_supplicant( 1338): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1338): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1338): wlan0: Cancelling scan request
I/wpa_supplicant( 1338): htc_wext_set_keepalive +
I/wpa_supplicant( 1338): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1338): getPrivFuncNum +	
I/wpa_supplicant( 1338): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1338): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1338): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1338): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_su,pplicant( 1338): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1338): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1338): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1338): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/WifiMonitor(  953): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1338): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1338):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1338):   key_nonce - hexdump(len=32): 3c e1 a1 91 b5 26 4d 24 16 b7 a2 09 53 cf 4e e4 b9 b6 90 74 3a e4 f1 40 a6 97 b5 59 3b 0b 0c 66
D/wpa_supplicant( 1338):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/WifiMonitor(  953): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  953): handleMessage: E msg.what=147462
D/wpa_supplicant( 1338): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=42 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/WifiMonitor(  953): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  953): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1338): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/HTCRequest(  953): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1338): RSN: msg 1/4 key data - hexdump(len=0):
D/HTCRequest(  953): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  953):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=134372  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/HTCRequest(  953): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  953): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  953): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  953): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  953): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/Tethering(  953): interfaceStatusChanged wlan0, false
D/WifiMonitor(  953): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  953): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  953): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  953):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=134372  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor(  953): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE,
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147500
E/WifiStateMachine(  953): processMsg: DisconnectedState
D/wpa_supplicant( 1338): WPA: Renewed SNonce - hexdump(len=32): f4 0b c6 a0 b2 51 4c 44 ff 7e 68 28 b8 c7 e7 1b 31 2c 31 b7 18 1d 50 88 e1 3f 83 4f 31 84 05 37
E/WifiStateMachine(  953):  DisconnectedState what:147500 0 0
D/wpa_supplicant( 1338): WPA: Nonce1 - hexdump(len=32): f4 0b c6 a0 b2 51 4c 44 ff 7e 68 28 b8 c7 e7 1b 31 2c 31 b7 18 1d 50 88 e1 3f 83 4f 31 84 05 37
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/wpa_supplicant( 1338): WPA: Nonce2 - hexdump(len=32): 3c e1 a1 91 b5 26 4d 24 16 b7 a2 09 53 cf 4e e4 b9 b6 90 74 3a e4 f1 40 a6 97 b5 59 3b 0b 0c 66
D/wpa_supplicant( 1338): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1338): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1338): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1338): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1338): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): WPA: Derived Key MIC - hexdump(len=16): 5c 44 98 85 1d da 2d 25 7b 7b f1 8c 3c 09 e2 93
,E/WifiStateMachine(  953):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  953): Enter handleAssociatedWithEvent
D/WifiStateMachine(  953): Associated
D/WifiStateMachine(  953): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  953): Exit handleAssociatedWithEvent
E/WifiStateMachine(  953): handleMessage: X
D/Tethering(  953): interfaceLinkStateChanged wlan0, false
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  953): handleMessage: E msg.what=147462
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Tethering(  953): interfaceStatusChanged wlan0, false
D/PMS     (  953): acquireWL(1f3de270): PARTIAL_WAKE_LOCK  NetworkStats 0x1 953 1000 null
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  953):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=134375  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  953): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  953): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/Tethering(  953): interfaceLinkStateChanged wlan0, false
D/Tethering(  953): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  953): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/Tethering(  953): interfaceLinkStateChanged wlan0, true
D/Tethering(  953): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  953): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  953): NetworkAgent == null
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/Tethering(  953): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 20
E/WifiStateMachine(  953): processMsg: ConnectModeState
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  953):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=134380  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  953): handleMessage: X
D/wpa_supplicant( 1338): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1338): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1338): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1338): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1338):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1338):   key_nonce - hexdump(len=32): 3c e1 a1 91 b5 26 4d 24 16 b7 a2 09 53 cf 4e e4 b9 b6 90 74 3a e4 f1 40 a6 97 b5 59 3b 0b 0c 66
D/wpa_supplicant( 1338):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_rsc - hexdump(len=8): af 09 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338):   key_mic - hexdump(len=16): 8a f1 7a 0c d7 38 cf f6 43 6e 32 3d 57 71 c1 20
D/wpa_supplicant( 1338): RSN: encrypted key data - hexdump(len=56): d3 06 fe 2b 8f f1 71 a3 76 3d 31 37 fd 99 70 4d 33 34 98 4c 08 37 03 e7 da c9 61 ab 55 7f 3e d4 ...
D/wpa_supplicant( 1338): WPA: decrypted EAPOL,-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1338): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1338): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1338): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 9f 9f ...
D/wpa_supplicant( 1338): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1338): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1338): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1338): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): WPA: Derived Key MIC - hexdump(len=16): c7 3f 77 7c 41 4b 8a 4f ee 81 f7 e3 3f 53 82 1c
D/wpa_supplicant( 1338): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55a005f390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1338): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1338):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1338): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1338): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1338): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1338): WPA: RSC - hexdump(len=6): af 09 00 00 00 00
D/wpa_supplicant( 1338): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x557073de68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1338): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1338): nl80211: KEY_SEQ - hexdump(len=6): af 09 00 00 00 00
D/wpa_supplicant( 1338):    broadcast key
I/wpa_supplicant( 1338): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1338): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1338): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1338): wlan0: Radio work 'connect'@0x55a003f860 done in 0.143089 seconds
I/wpa_supplicant( 1338): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1338): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1338): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1338): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1338): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  953): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  953): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=45 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  953): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  953): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=46 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1338),: set send_ind_to_ndc = 0
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
I/wpa_supplicant( 1338): htc_wext_set_TX_TRACKING (1)+
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  953): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1338): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1338): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1338): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1338): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1338): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1338): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1338): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1338): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1338): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  953): Event [IFNAME=wlan0 Connect to SSID: NG700]
D/wpa_supplicant( 1338): EAPOL: SUPP_BE entering state IDLE
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=48 dispatchEvent: Connect to SSID: NG700
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1338): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1338): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
W/WifiMonitor(  953): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1338): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/PMS     (  953): releaseWL(1f3de270): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/Tethering(  953): interfaceLinkStateChanged wlan0, true
V/NetworkPolicy(  953): updateNetworkEnabledLocked()
D/Tethering(  953): interfaceStatusChanged wlan0, true
V/NetworkPolicy(  953): updateNotificationsLocked()
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbDeviceManager(  953): [USBNET] bCheckSuppFunc: cdc_network
D/WifiMonitor(  953): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  953): handleMessage: E msg.what=147462
E/WifiStateMachine(  953): processMsg: DisconnectedState
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/UsbnetService(  953): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  953): BroadcastReceiver::onReceive-
E/WifiStateMachine(  953):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=134389  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  953): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  953): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=134391  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147459
E/WifiStateMachine(  953): processMsg: DisconnectedState
D/FlexNetS( 6372): updateSvcAllowedInSettings:false
E/WifiStateMachine(  953):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=134394
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=134394
E/WifiStateMachine(  953): Network connection established
D/WifiStateMachine(  953): fetchFrequency(), freq = 2412
E/WifiStateMachine(  953): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  953): NetworkAgent == null
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 22
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  953): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  953): handleMessage: new destination call exit/enter
E/WifiStateMachine(  953): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  953): invokeExitMethods: DisconnectedState
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 23
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1338): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  953): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
E/WifiStateMachine(  953): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  953): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  953): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  953): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  953): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  953): NetworkAgent == null
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/FlexNetS( 6372): updateSvcAllowedInSettings:false
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 24
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
E/WifiStateMachine(  953): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  953): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  953): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  953): Got NetworkAgent Messenger
E/WifiConfigStore(  953): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  953): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
W/WifiHW  (  953): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  953): NetworkAgent connected
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  953): invokeEnterMethods: ObtainingIpState
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
E/WifiStateMachine(  953): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  953): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  953): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  953): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  953): QCOM Debug skip set_network part for security concern!
D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1338): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1338): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1338): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1338): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1338): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1338): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  953): Start Dhcp Watchdog 2
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147462
E/WifiStateMachine(  953): processMsg: ObtainingIpState
E/WifiStateMachine(  953):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=134416  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=134417  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=134417  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131101
E/WifiStateMachine(  953): processMsg: ObtainingIpState
E/WifiStateMachine(  953):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  953):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  953): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  953): handleMessage: X
D/FlexNetS( 6372): updateSvcAllowedInSettings:false
E/WifiStateMachine(  953): handleMessage: E msg.what=131212
E/WifiStateMachine(  953): processMsg: ObtainingIpState
D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  953):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
D/WISPrService( 5870): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  953):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/WISPrService( 5870): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  953): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=196612
E/WifiStateMachine(  953): processMsg: ObtainingIpState
E/WifiStateMachine(  953):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/ConnectivityService(  953): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  953): processMsg: L2ConnectedState
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
E/WifiStateMachine(  953):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  953): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  953): acquireWL(1b4a1c34): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 953 1000 null
D/WifiDataStallTracker(  953): setDhcpActive: true
D/WifiStateMachine(  953): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  953): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  953): do suspend false
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1338): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1338): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1338): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1338): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1338): wlan0: Event DRIVER_GTK_REKEY (37) received
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  953): Unexpected BatchedScanResults :null
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  953): noteBatchedScanstop()
D/WifiP2pService(  953): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@18160ce3 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  953): handleMessage: X,
D/WifiP2pService(  953): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@18160ce3 target=com.android.internal.util.StateMachine$SmHandler }
D/FlexNetS( 6372): updateSvcAllowedInSettings:false
D/WifiService(  953): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6372): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6372): updateSvcAllowedInSettings:false
D/TetherSettings( 5870): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5870): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5870): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5870): Cust_ConnectToPC   : spcsc>false
D/        ( 5870): Cust_ConnectToPC   : IPT>true
D/        ( 5870): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5870): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 5870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/SmartNS_Utility( 5870): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5870): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 5870): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,I/SmartNS_Utility( 5870): setISNotification,
D/SmartNS_Utility( 5870): usb_cable_connect = 1
,D/SmartNS_Utility( 5870): usb_denied = 0
,D/MdScPhnSt( 6662): [6b0.2.]  listen tmrbb8
,I/SmartNS_PSService( 5870): usb notificaiton:true
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 5870): usb_cable_connect = 1
D/SmartNS_Utility( 5870): usb_denied = 0,
I/SmartNS_PSService( 5870): usb notificaiton:true
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,I/RemoteViews( 1219): reapply : com.android.settings 1 36
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_NSReceiver( 5870): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/FlexNetS( 6372): updateSvcAllowedInSettings:false
,I/RemoteViews( 1219): reapply : com.android.settings 1 36
,D/FlexNetS( 6372): updateSvcAllowedInSettings:false
,D/FlexNetS( 6372): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6456): remove item 101 (p2d24in231) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6662): [6b0.2.] summary 118:p2 ignore
,D/FlexNetS( 6372): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6456): remove item 101 (p2d1in15) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6372): updateSvcAllowedInSettings:false
,D/FlexNetS( 6372): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6456): remove item 101 (p2in22) for 15:android.intent.action.ANY_DATA_STATE
,E/dhcpcd  ( 6694): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6694): version 5.5.6 starting
,E/dhcpcd  ( 6694): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6694): wlan0: using ClientID 01:90:**:c4:e6:4c:f8,
I/dhcpcd  ( 6694): autoip env[11]:autoip=DISABLE
,D/Process (  953): killProcessQuiet, pid=6135
I/ActivityManager(  953): Killing 6135:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6694): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6694): wlan0: sending REQUEST (xid 0x8892c318), next in 1.14 seconds
,I/ActivityManager(  953): Recipient 6135,
,I/dhcpcd  ( 6694): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6694): wlan0: leased 192.168.1.130 for 86400 seconds
,I/dhcpcd  ( 6694): autoip env[11]:autoip=DISABLE
D/ConnectivityService(  953): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  953): handleMessage: E msg.what=131212
E/WifiStateMachine(  953): processMsg: ObtainingIpState
E/WifiStateMachine(  953):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  953): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  953): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  953): handleMessage: X
,I/dhcpcd  ( 6694): bind_interface: daemonise,
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  953): handleMessage: E msg.what=196613
E/WifiStateMachine(  953): processMsg: ObtainingIpState
E/WifiStateMachine(  953):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  953): processMsg: L2ConnectedState
,E/WifiStateMachine(  953):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine(  953): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER POWERMODE 0',
,I/wpa_supplicant( 1338): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1338): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  953): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  953): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1338): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/PMS     (  953): releaseWL(1b4a1c34): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiDataStallTracker(  953): setDhcpActive: false
E/WifiStateMachine(  953): handlePostDhcpSetup release wake lock during DHCP,
E/WifiStateMachine(  953): WifiStateMachine DHCP successful
D/ConnectivityService(  953): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false,
E/WifiStateMachine(  953): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  953): link address 192.168.1.130/24
E/WifiStateMachine(  953): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  953): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  953): gateway: /192.168.1.1
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
,D/wpa_supplicant( 1338): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1338): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1338): htc_wext_set_keepalive +
I/wpa_supplicant( 1338): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1338): getPrivFuncNum +	
,I/wpa_supplicant( 1338): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1338): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1338): get_ip_address source addr = c0a80182
,I/wpa_supplicant( 1338): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1338): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  953): handleMessage: X
,E/WifiStateMachine(  953): handleMessage: E msg.what=131210
E/WifiStateMachine(  953): processMsg: ObtainingIpState
E/WifiStateMachine(  953):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1338): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1338): environment dirty rate=50 [6][3][0]
,E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
,E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1338): wlan0: Control interface command 'BLACKLIST clear'
,E/wpa_supplicant( 1338): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  953): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=50 dispatchEvent: BLACKLIST CLEAR 
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  953): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
,E/WifiStateMachine(  953): NetworkAgent != null,
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/ConnectivityService(  953): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  953): Adding iface wlan0 to network 101
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 25
,D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiDataStallTracker(  953): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  953): WAN detection
E/WifiDataStallTracker(  953): ENABLE_DATA_MONITOR_POLL true Token 4
,D/HtcWifiWanDetect(  953): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiDataStallTracker(  953): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NetworkPolicy(  953): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  953): transitionTo: destState=ConnectedState
E/WifiStateMachine(  953): handleMessage: new destination call exit/enter
E/WifiStateMachine(  953): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  953): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  953): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  953): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  953): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  953): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,E/WifiStateMachine(  953): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/NetworkPolicy(  953): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 26
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5870): >>>>>WISPrService start isConnected = true<<<<<
,E/WifiStateMachine(  953): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/ConnectivityService(  953): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  953): handleMessage: X
D/ConnectivityService(  953): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
,D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  953): handleMessage: E msg.what=131131
,E/WifiStateMachine(  953): processMsg: ConnectedState
,D/ConnectivityService(  953): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  953):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  953): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
E/WifiStateMachine(  953): processMsg: L2ConnectedState
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  953):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  953): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  953): handleMessage: X
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/Nat464Xlat(  953): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true,
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  953): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): Connected
D/ConnectivityService(  953): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  953): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): Validated
D/ConnectivityService(  953):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  953): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  953):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  953):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  953): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  953): currentScore = 0, newScore = 20
D/usbnet  (  953): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):    accepting network in place of null
D/usbnet  (  953):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  953): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  953): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  953): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  953): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WISPrService( 5870): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  953): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  953): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  953): ensureActiveMobilePolicyLocked()
,D/Tethering(  953): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  953): acquireWL(1ef5ef59): PARTIAL_WAKE_LOCK  NetworkStats 0x1 953 1000 null
D/Tethering(  953): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  953): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): ValidatedState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  953): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  953): Validated
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkPolicy(  953): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
V/NetworkPolicy(  953): updateNetworkEnabledLocked()
D/WIFI    (  953): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  953): updateIfacesLocked()
D/WIFI    (  953):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  953): Validated NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  953): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/ConnectivityService(  953): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  953): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  953):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  953):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  953): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  953):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:NG700 elapse:3
D/ConnectivityService(  953): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1219): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
V/NetworkPolicy(  953): updateNotificationsLocked()
D/ConnectivityService(  953): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  953): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/DATA_ICON( 1219): dataConnected: false/false
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/NetworkManagementService(  953): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/PMS     (  953): releaseWL(1ef5ef59): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  953): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  953):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  953): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  953): updateNetworkEnabledLocked()
V/NetworkPolicy(  953): updateNotificationsLocked()
D/DATA_ICON( 1219): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,D/DATA_ICON( 1219): dataConnected: false/false
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/wpa_supplicant( 1338): EAPOL: startWhen --> 0
D/wpa_supplicant( 1338): EAPOL: disable timer tick
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  953): handleMessage: E msg.what=131212
E/WifiStateMachine(  953): processMsg: ConnectedState
,E/WifiStateMachine(  953):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  953): processMsg: ConnectModeState
,E/WifiStateMachine(  953):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
,E/WifiStateMachine(  953):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine(  953): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  953): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  953): identical MTU - not setting
D/Nat464Xlat(  953): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  953): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524295
E/WifiStateMachine(  953): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  953): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  953): handleMessage: X
,D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524295
,D/PMS     (  953): releaseWL(33d1713b): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  953): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  953): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  953): [AlarmQueuing] connectivity wifi: false
,D/htcCheckinService(  953): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  953): acquireWL(157a371e): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 953 1000 null
D/PMS     (  953): acquireWL(2108cbff): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 953 1000 null
D/GpsLocationProvider(  953): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  953): releaseWL(2108cbff): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  953): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ConnectivityHelper( 1502): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  953): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6726 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  953): No APN found to select.,
,D/PMS     (  953): releaseWL(157a371e): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6662): [322.1.]  listen tmrbb8
,D/MdScDataSum( 6662): [322.1.] summary 118:p1 ignore
,I/MusicStore( 6726): Database version: 120,
,D/VoldConnector(  953): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6726): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  953): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6726): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  953): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6726): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,W/ResourcesManager( 6726): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6726): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 6726): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6726): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6726): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1332b9d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6726): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6726): GMSCore installation verified
,I/ConfigStore( 6726): Config Database version: 1,
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6726, uid=10159, userID:0,
,D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
,D/MediaRouterService(  953): Client com.google.android.music (pid 6726): Registered
,D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
,I/MediaRouter( 6726): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6726): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6726): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6726): type=WIFI subType= reason=null isConnected=true
,D/AutoSetting( 1574): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6322): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6322): onReceive CONNECTIVITY_CHANGE networkType=1
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6726, uid=10159, userID:0
,D/AutoSetting( 1574): service - onCreate(),
,D/AutoSetting( 1574): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1574): service - onStartCommand() screen is off, don't request location
D/LocationManagerService(  953): request a26355b passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052),
D/LocationManagerService(  953): provider request: passive ProviderRequest[ON interval=0]
,D/ChimeraCfgMgr( 4455): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4455): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  953): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6769 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 6435): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6435): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6435): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6435): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6435): [NET] android_getaddrinfo_proxy+
D/libc    ( 6435): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6435): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4455): [AccountUtils] Account not ready
W/Kids    ( 4455): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4455): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4455): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4455): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4455): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4455): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4455): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4455): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1219): reapply : com.google.android.gms 2 40,
,I/Babel   ( 6435): connection state changed from UNKNOWN to CONNECTED,
,I/art     (  953): Explicit concurrent mark sweep GC freed 56169(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 1.536ms total 192.046ms
,I/GHttpClientFactory( 6726): Using our fixed implementation of GMSCore's GoogleHttpClient,
,D/VoldConnector(  953): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6769): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/GoogleURLConnFactory( 6726): Using platform SSLCertificateSocketFactory
I/GAv4    ( 6769): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6769):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6769):   adb logcat -s GAv4
,D/VoldConnector(  953): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6769): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6769): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/VoldConnector(  953): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6769): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  953): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/GAv4    ( 6769): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 6769): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6769): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/global  ( 6769): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6769): [apache-http] Connection GC has been deprecated!
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  953): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  953): [NET] android_getaddrinfo_proxy+
D/libc    (  953): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/WebViewFactory( 6769): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/AlarmManager(  953): [AlarmQueuing] connectivity wifi: true
,I/NetworkMonitor( 6726): type=WIFI subType= reason=null isConnected=true
D/htcCheckinService(  953): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/HtcWifiWanDetect(  953): Find DNS Address www.htc.com/23.59.123.86,
,D/libc    (  953): [NET] android_getaddrinfo_proxy-, success
I/ConnectivityHelper( 1502): [onReceive] WIFI(1): CONNECTED
,I/LibraryLoader( 6769): Time to load native libraries: 2 ms (timestamps 8361-8363),
I/LibraryLoader( 6769): Expected native library version number "",actual native library version number ""
,D/GpsLocationProvider(  953): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
D/PMS     (  953): acquireWL(e2a42c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 953 1000 null
,D/MdScPhnSt( 6662): [8a0.1.]  listen tmrbb8
D/PMS     (  953): acquireWL(ed0caec): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 953 1000 null
,D/PMS     (  953): releaseWL(ed0caec): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
D/GpsLocationProvider(  953): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  953): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
V/WebViewChromiumFactoryProvider( 6769): Binding Chromium to main looper Looper (main, tid 1) {2cbf86e9},
I/LibraryLoader( 6769): Expected native library version number "",actual native library version number ""
,I/chromium( 6769): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/GpsLocationProvider(  953): No APN found to select.
,D/PMS     (  953): releaseWL(e2a42c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,I/BrowserStartupController( 6769): Initializing chromium process, singleProcess=true
,W/art     ( 6769): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6769): ApplicationContext is null in ApplicationStatus
,D/MdScDataSum( 6662): [8a0.1.] summary 118:p1 ignore,
,W/chromium( 6769): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6769): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6769): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6769): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6769): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6769): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6769): Local Branch: 
I/Adreno-EGL( 6769): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6769): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6769):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6769): Requires BLUETOOTH permission,
,I/NSApplication( 6769): Starting up...,
,I/ActivityManager(  953): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6835 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  953): killProcessQuiet, pid=6348
I/ActivityManager(  953): Killing 6348:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  408): Explicit concurrent mark sweep GC freed 8645(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 239us total 37.457ms,
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 177us total 25.898ms
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 161us total 24.592ms
,I/ActivityManager(  953): Recipient 6348,
,D/PMS     (  953): acquireWL(3ee9b7a2): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{10024}
D/Process (  953): killProcessQuiet, pid=6277
,V/AlarmManager(  953): sending alarm PendingIntent{28c2bc33: PendingIntentRecord{32b3dbf0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449752952650, Int=1800000
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Killing 6277:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,I/ActivityManager(  953): Recipient 6277
,V/AlarmManager(  953): sending alarm PendingIntent{2f37f569: PendingIntentRecord{1fcfabee com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=138731, Int=0
,D/BluetoothAdapter( 6597): 927380577: getState(). Returning 12,
I/jxcore-log( 6597): BLE supported!!
I/jxcore-log( 6597): 
,I/ActivityManager(  953): Killing 6402:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=6402
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/WifiStateMachine(  953): handleMessage: E msg.what=131168,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  953): processMsg: L2ConnectedState
,E/WifiStateMachine(  953):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  953): processMsg: DriverStartedState
,E/WifiStateMachine(  953):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
,E/WifiStateMachine(  953):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  953): handleMessage: X
,I/ActivityManager(  953): Recipient 6402,
D/WifiService(  953): Client connection lost with reason: 4
,V/MusicLeanback( 6726): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/AutoSetting( 1574): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,D/MobileConnectivityChangeReceiver( 6322): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6322): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1574): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1574): service - onStartCommand() screen is off, don't request location
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4455, uid=10024, userID:0
,D/ChimeraCfgMgr( 4455): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4455): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PMS     (  953): acquireWL(1d516ddd): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4455 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(16331823): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(3ee9b7a2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  953): acquireWL(132e2120): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4455 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): releaseWL(1d516ddd): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 1878): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1878): [NET] android_getaddrinfo_proxy+
D/libc    ( 1878): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/EventLogService( 4455): Aggregate from 1449752936765 (log), 1449751152584 (data)
,W/Kids    ( 4455): [AccountUtils] Account not ready
W/Kids    ( 4455): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4455): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4455): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4455): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4455): 	at com.google.android.gms.kids.account.t.a(SourceFile:62),
W/Kids    ( 4455): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4455): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
W/Kids    ( 4455): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4455): 	at java.lang.Thread.run(Thread.java:818)
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1878): [NET] android_getaddrinfo_proxy-, success
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,D/PMS     (  953): releaseWL(132e2120): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  953): acquireWL(ef1689b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1878): Connected,
,D/PMS     (  953): releaseWL(16331823): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(ef1689b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(2d8af438): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1878 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1878): Message class com.google.f.a.a.p
,D/PMS     (  953): releaseWL(2d8af438): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(1433f176): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6726 10159 null,
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6726, uid=10159, userID:0,
,D/WearableService( 4818): callingUid 10024, callindPid: 4818,
,D/PMS     (  953): releaseWL(1433f176): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6726): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6726): Stop autocaching.
,E/GmsUtils( 6726): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6726): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  953): acquireWL(1efa4b81): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{10024},
,V/AlarmManager(  953): sending alarm PendingIntent{1a59a426: PendingIntentRecord{2392a867 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143616, Int=0
,D/PMS     (  953): releaseWL(1efa4b81): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  953): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  953): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  953): acquireWL(3b6b4614): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 953 1000 null
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  953): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  953): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  953): [NET] android_getaddrinfo_proxy+
D/libc    (  953): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  953): [NET] android_getaddrinfo_proxy-, success
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  953): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  953): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  953): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  953):  [handleDownloadXtraData]inject done.
D/PMS     (  953): acquireWL(3cc0af80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 953 1000 null
D/GpsLocationProvider(  953): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  953): releaseWL(3b6b4614): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  953): releaseWL(3cc0af80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1439): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1439): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1574): service - handleMessage() stop self,
,D/AutoSetting( 1574): service - handleMessage() quit looper
,D/AutoSetting( 1574): service - onDestroy() END
,D/PMS     (  953): acquireWL(1083e9b9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
,I/BatteryService(  953): n_update end,
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  953): releaseWL(1083e9b9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  953): >> updateStatus
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiController(  953): battery changed pluggedType: 2
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): processMsg: DeviceActiveState
,I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,E/WifiStateMachine(  953): handleMessage: E msg.what=131165,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  953): handleMessage: X
,D/TelephonyReceiver( 1439): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  953): acquireWL(377711fe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000},
V/AlarmManager(  953): sending alarm PendingIntent{272d0ea: PendingIntentRecord{5866fdb android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=166686, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{da23d5f: PendingIntentRecord{134143ac android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1449753007226, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{18706875: PendingIntentRecord{272e500a com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190497, Int=0
D/PMS     (  953): acquireWL(3cd7507b): PARTIAL_WAKE_LOCK  *backup* 0x1 953 1000 null
,D/PMS     (  953): acquireWL(3c54ee98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  953): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
D/PMS     (  953): releaseWL(377711fe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,E/BackupManagerService(  953): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  953): releaseWL(3cd7507b): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data,
,D/PMS     (  953): acquireWL(326c16f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): releaseWL(3c54ee98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  953): releaseWL(326c16f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(232953f3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(232953f3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(311ef8b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(2215b329): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(e7b3c4f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): releaseWL(311ef8b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  953): acquireWL(2ead58e5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(2ead58e5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1878): Vacuum at: now=1449753024103 tag=VacuumService,
,I/GoogleURLConnFactory( 1878): Using platform SSLCertificateSocketFactory,
D/PMS     (  953): releaseWL(2215b329): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): acquireWL(1702cfba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1878): No account for auth token provided
,D/PMS     (  953): releaseWL(1702cfba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(b594e6b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(b594e6b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1878): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1878): [NET] android_getaddrinfo_proxy+
D/libc    ( 1878): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1878): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1878): No account for auth token provided,
,W/Uploader( 1878): No account for auth token provided,
,W/Uploader( 1878):  no longer exists, so no auth token.,
,W/Uploader( 1878): No account for auth token provided,
,D/PMS     (  953): releaseWL(e7b3c4f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(cfe2d86): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(cfe2d86): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(35bc6647): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(35bc6647): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiStateMachine(  953): handleMessage: E msg.what=131326
,E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState what:131326 2 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  953): handleMessage: X
,D/PMS     (  953): acquireWL(2a4b5e74): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1000}
V/AlarmManager(  953): sending alarm PendingIntent{3a96bf9d: PendingIntentRecord{30ff9c12 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=210695, Int=0
,D/PMS     (  953): releaseWL(2a4b5e74): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1574): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2f5f3807
I/ActivityManager(  953): Killing 5898:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  953): killProcessQuiet, pid=5898
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5898
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  953): acquireWL(64f1fe3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(64f1fe3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): updateBatteryInfo
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/NotificationService(  953): plugged=true pluggin=true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): runPSCheck
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  953): >> updateStatus
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): processMsg: DeviceActiveState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): processMsg: StaEnabledState
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1338): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 1338): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1338): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,D/PMS     (  953): acquireWL(17f9ede0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(17f9ede0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PMS     (  953): runPSCheck
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5

```
