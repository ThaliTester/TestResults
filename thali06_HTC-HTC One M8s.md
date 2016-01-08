#### Test 54970261e0c50c1_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
I/ActivityManager(  946): Killing 5588:com.htc.musicenhancer/u0a49 (adj 15): empty #17
--------- beginning of main
D/Process (  946): killProcessQuiet, pid=5588
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
I/ActivityManager(  946): Recipient 5588
E/cutils-trace( 6694): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6694): ====startRecUseTime====
D/htc.customization.log.level( 6694):  is 
W/CustomizationLogLevel( 6694): Level value is invalid, use default level 2
D/CustomizationManager( 6694):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 6694): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6694): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6694): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6694): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6694): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6694): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6694): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6694): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6694): Parsing tag category name = system
I/CustomizationCIDLoader( 6694): Parsing tag category name = application
I/CustomizationCIDLoader( 6694): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6694): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6694): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6694): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6694): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6694): add string-array item, value = 42507
I/CustomizationCIDLoader( 6694): add string-array item, value = 21902
I/CustomizationCIDLoader( 6694): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6694): add string-array item, value = 23420
I/CustomizationCIDLoader( 6694): add string-array item, value = 22299
I/CustomizationCIDLoader( 6694): add string-array item, value = 24002
I/CustomizationCIDLoader( 6694): add string-array item, value = 23210
I/CustomizationCIDLoader( 6694): add string-array item, value = 23205
I/CustomizationCIDLoader( 6694): add string-array item, value = 23806
I/CustomizationCIDLoader( 6694): add string-array item, value = 23430
I/CustomizationCIDLoader( 6694): add string-array item, value = 23408
I/CustomizationCIDLoader( 6694): add string-array item, value = 27205
I/CustomizationCIDLoader( 6694): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6694): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6694):  Read CID file spent 0.108 (s)
D/CustomizationManager( 6694):  All configurations done spent 0.108 (s)
I/ActivityManager(  946): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6694 on display 0
D/PMS     (  946): acquireHCC(960ca29): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 946 1000 null
D/PMS     (  946): acquireHCC(84c1ae): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 946 1000 null
I/ActivityManager(  946): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6712 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1363): [EventService]  onDisplayChanged: 0
V/ActivityManager(  946): Display changed displayId=0
D/DotMatrix( 1363): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1602): [trimMemory] 20
I/WebViewFactory( 6712): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6712): Time to load native libraries: 10 ms (timestamps 9858-9868)
I/LibraryLoader( 6712): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6712): Binding Chromium to main looper Looper (main, tid 1) {808009e},
I/LibraryLoader( 6712): Expected native library version number "",actual native library version number ""
,I/chromium( 6712): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6712): Initializing chromium process, singleProcess=true
W/art     ( 6712): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6712): ApplicationContext is null in ApplicationStatus
,W/chromium( 6712): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
E/libEGL  ( 6712): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6712): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6712): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6712): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6712): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6712): Local Branch: 
I/Adreno-EGL( 6712): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6712): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6712):                  d74aa161a12b9c6fc6332151
,W/System.err(  946): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  946): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  946): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d107712:true
W/System.err(  946): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  946): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  946): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  946): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6712): 1055885482: getState(). Returning 12,
,W/art     ( 6712): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6712): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6712): CordovaWebView is running on device made by: HTC
,W/art     ( 6712): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6712): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6712): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/HtcSystemUPManager(  946): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  946): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  946): hiding MENU key,
D/StatusBarManagerService(  946): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  946): hiding MENU key
,D/FindExtension( 6712): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6712): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2a9f4f68, mServedView=org.apache.cordova.engine.SystemWebView{276af81 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@34c83826
,I/InputMethodManagerService(  946): Disable input method client, pid=1602
,I/PhoneStatusBar( 1239): setImeWindowStatus(false,false),
D/StatusBarManagerService(  946): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6712): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  946): Displayed com.test.thalitest/.MainActivity: +634ms (total +680ms)
,W/BindingManager( 6712): Cannot call determinedVisibility() - never saw a connection for the pid: 6712,
,D/JsMessageQueue( 6712): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6712): JniHelper::setJavaVM(0xab3fb8f8), pthread_self() = -1401803416,
D/JX-Cordova( 6712): jxcore cordova android initializing
,E/libc    ( 6712): mmap fail (pid 6712, tid 6712, size 0, flags 0x1, errno 22(Invalid argument))
,W/jxcore-log( 6712): Initializing JXcore engine,
W/jxcore-log( 6712): JXcore engine is ready
,W/jxcore-log( 6712): Starting JXcore engine
,W/jxcore-log( 6712): Platform android,
W/jxcore-log( 6712): 
W/jxcore-log( 6712): Process ARCH arm
W/jxcore-log( 6712): 
,D/PMS     (  946): releaseHCC(960ca29): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  946): releaseHCC(84c1ae): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6712): JXcore Cordova bridge is ready!
I/jxcore-log( 6712): 
W/jxcore-log( 6712): JXcore engine is started
I/Choreographer( 6712): Skipped 96 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6712): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6712): Toggling radios to true
I/jxcore-log( 6712): 
,D/BluetoothAdapter( 6712): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  946): ADD_CLIENT: 8,
D/WifiService(  946): New client listening to asynchronous messages
D/WifiManager( 6712): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  946): MONITOR_LOG
D/WifiService(  946): setWifiEnabled: true pid=6712, uid=10366
W/Settings:Agent(  946): name: wifi_on
E/WifiService(  946): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  946): value: 2
I/WifiService(  946): isSprintWifiRestricted(): false
W/Settings:Agent(  946): >> traceCallingStack()
I/WifiService(  946): isMdmWifiRestricted(): false
W/Settings:Agent(  946): Process.myPid(): 946
W/Settings:Agent(  946): Process.myTid(): 1805
W/Settings:Agent(  946): Process.myUid(): 1000
W/Settings:Agent(  946): 
W/Settings:Agent(  946): 
W/System.err(  946): java.lang.Throwable: stack dump
,W/System.err(  946): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  946): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  946): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  946): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  946): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  946): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  946): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  946): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  946): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  946): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  946): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  946): 
W/Settings:Agent(  946): << traceCallingStack(): 10(ms)
D/WifiController(  946): handleMessage: E msg.what=155656
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): handleMessage: X
,D/WifiManager( 6712): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  946): handleMessage: E msg.what=131145
D/WifiManager( 6712): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  946): processMsg: ConnectedState
,E/WifiStateMachine(  946):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  946): processMsg: L2ConnectedState
E/WifiStateMachine(  946):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
I/jxcore-log( 6712): Radios toggled
I/jxcore-log( 6712): 
D/wpa_supplicant( 1348): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1348): TDLS: Tear down peers
D/wpa_supplicant( 1348): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 1348): wlan0: Event DEAUTH (12) received
D/PMS     (  946): acquireWL(17b2fd2f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 946 1000 null
D/wpa_supplicant( 1348): wlan0: Deauthentication notification
D/UsbDeviceManager(  946): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1348): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1348): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1348): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1348): enter disconnect check
I/wpa_supplicant( 1348): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1348): wlan0: Auto connect disabled: do not try to re-connect
D/Tethering(  946): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1348): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  946): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  946): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  946): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  946): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  946): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  946): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  946): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor(  946): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  946): interfaceLinkStateChanged wlan0, false
D/Tethering(  946): interfaceStatusChanged wlan0, false
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/UsbnetService(  946): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1348): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1348): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x556c59bf88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348):    addr=c0:ff:d4:d3:aa:48
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
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
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  946): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1348): RTM_N,EWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1348): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1348): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1348): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  946): transitionTo: destState=DisconnectingState
D/WifiMonitor(  946): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  946): handleMessage: new destination call exit/enter
E/WifiStateMachine(  946): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  946): invokeExitMethods: ConnectedState
E/WifiStateMachine(  946): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  946): release()
E/WifiStateMachine(  946): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  946): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  946): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  946): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  946): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  946): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  946): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  946): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1348): Power_Mode_Type mode = 0
I/wpa_supplicant( 1348): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  946): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  946): setDhcpActive: false
D/WifiP2pService(  946): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/Netd    (  393): ifc_reset_connections failed on iface wlan0 for address 192.168.1.130/24 (Unknown error -1)
,D/libc    (  946): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  946): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  946): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/PMS     (  946): releaseWL(17b2fd2f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  946): setDetailed state send new extra info<unknown ssid>
V/NetworkPolicy(  946): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  946): NetworkAgent != null
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 13
,D/WIFI_ICON( 1239): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1239): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NetworkPolicy(  946): updateNetworkEnabledLocked()
V/NetworkPolicy(  946): updateNotificationsLocked()
D/WifiDataStallTracker(  946): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  946): stopDataStallAlarm 
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/ConnectivityService(  946): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiDataStallTracker(  946): ENABLE_DATA_MONITOR_POLL false Token 3
I/IntentController( 1239): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
,D/TetherSettings( 5926): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5926): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5926): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5926): Cust_ConnectToPC   : spcsc>false
D/        ( 5926): Cust_ConnectToPC   : IPT>true
D/        ( 5926): Cust_ConnectToPC   : Singel_USB>false
D/libc    (  946): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  946): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  946): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  946): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WIFI_ICON( 1239): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/StatusBar.NetworkController( 1239): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1239): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 15
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/IntentController( 1239): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  946): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  946): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  946):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  946): Start Disconnecting Watchdog 1
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131146
E/WifiStateMachine(  946): processMsg: DisconnectingState
E/WifiStateMachine(  946):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
,D/wpa_supplicant( 1348): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1348): Fast associate: Old scan results
D/wpa_supplicant( 1348): wlan0: Setting scan request: 0.000000 sec
,I/wpa_supplicant( 1348): wpa_supplicant_scan enter
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
D/wpa_supplicant( 1348): P2P: * P2P IE header
E/WifiStateMachine(  946): handleMessage: X
D/wpa_supplicant( 1348): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1348): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1348): wlan0: Add radio work 'scan'@0x556c57e860
D/wpa_supplicant( 1348): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  946): handleMessage: E msg.what=147460
E/WifiStateMachine(  946): processMsg: DisconnectingState
D/wpa_supplicant( 1348): wlan0: Starting radio work 'scan'@0x556c57e860 after 0.000053 second wait
,D/wpa_supplicant( 1348): wlan0: nl80211: scan request
E/WifiStateMachine(  946):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132284
D/wpa_supplicant( 1348): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  946): processMsg: ConnectModeState
D/wpa_supplicant( 1348): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1348): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1348): wlan0: Own scan request started a scan in 0.000118 seconds
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  946):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132285
E/WifiStateMachine(  946): ConnectModeState: Network connection lost 
E/WifiStateMachine(  946): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  946): handleMessage: new destination call exit/enter
E/WifiStateMachine(  946): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  946): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  946): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  946): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  946): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  946): DisconnectedState call setCountryCode()
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  946):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  946): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/HTCRequest(  946): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1348): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
D/WifiMonitor(  946): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  946): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  946): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1348): wlan0: nl80211: sched_scan request
,W/Settings( 5926): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WIFI_ICON( 1239): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1239): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/SmartNS_Utility( 5926): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5926): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5926): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
,W/ContextImpl( 5926): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5926): setISNotification
,D/SmartNS_Utility( 5926): usb_cable_connect = 1,
,D/SmartNS_Utility( 5926): usb_denied = 0
,I/SmartNS_PSService( 5926): usb notificaiton:true,
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 5926): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,I/QuickSettingWifi( 1239): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0,
D/SmartNS_Utility( 5926): usb_cable_connect = 1
D/SmartNS_Utility( 5926): usb_denied = 0
I/SmartNS_PSService( 5926): usb notificaiton:true
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1363): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/wpa_supplicant( 1348): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
,D/wpa_supplicant( 1348): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Sched scan started
I/RemoteViews( 1239): reapply : com.android.settings 1 36
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131101
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
D/wpa_supplicant( 1348): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1348): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1348): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1348): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1348): wlan0: Scan completed in 0.039798 seconds
D/wpa_supplicant( 1348): nl80211: Received scan results (0 BSSes)
E/WifiStateMachine(  946):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  946): processMsg: DefaultState
D/wpa_supplicant( 1348): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 3 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to no match in scan
D/wpa_supplicant( 1348): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1348): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1348): wlan0: Radio work 'scan'@0x556c57e860 done in 0.040736 seconds
D/wpa_supplicant( 1348): wlan0: No suitable network found
D/wpa_supplicant( 1348): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1348): wlan0: Cancelling sched scan
E/WifiStateMachine(  946):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  946): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  946): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  946): handleMessage: X
D/wpa_supplicant( 1348): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
D/wpa_supplicant( 1348): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1348): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1348): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1348): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1348): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1348): p2p0: No suitable network found
D/wpa_supplicant( 1348): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1348): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/SmartNS_NSReceiver( 5926): Tethered state change:false isNSOpening:false
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 9e:93:4e:3e:ba:c5]
I/QuickSettingWifi( 1239): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 9e:93:4e:3e:ba:c5
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  946): handleMessage: E msg.what=147462
E/WifiMonitor(  946): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=132328  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiMonitor(  946): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiStateMachine(  946): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debo,uncing=false
E/WifiStateMachine(  946): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=44 dispatchEvent: WPS-AP-AVAILABLE 
E/WifiStateMachine(  946): processMsg: ConnectModeState
W/WifiMonitor(  946): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor(  946): WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  946): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  946):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=132328  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  946): handleMessage: X
D/WifiNetworkAgent(  946): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  946): handleMessage: E msg.what=147462
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=132329  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  946): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/WifiP2pService(  946): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  946): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiP2pService(  946): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  946): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  946): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  946): NetworkAgent == null
E/WifiStateMachine(  946): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DotMatrix( 1363): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1239): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiTrafficPoller(  946): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  946):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=132335  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=147461
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 dur:89 bcn=0
E/WifiStateMachine(  946): processMsg: ConnectModeState
I/IntentController( 1239): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  946):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 dur:89 bcn=0
E/WifiStateMachine(  946): processMsg: DriverStartedState
E/WifiStateMachine(  946):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 dur:89 bcn=0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 dur:89 bcn=0
D/WifiStateMachine(  946): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1348): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  946): [1,452,274,506,418 ms] noteScanEnd no scan source
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1348): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  946): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@30ad5af7 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  946): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  946): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  946): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  946): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  946):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  946): UPC503894600 a0:c5:62:7a:49:97 rssi=-80 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
I/QuickSettingWifi( 1239): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiAutoJoinController (  946): UPC5999698 64:7c:34:12:7f:81 rssi=-87 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
D/WIFI_ICON( 1239): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiAutoJoinController (  946): andilabs 34:36:3b:bd:89:28 rssi=-92 cap [WPA2-PSK-CCMP][ESS] is not scored
D/StatusBar.NetworkController( 1239): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiAutoJoinController (  946): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  946): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-87 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  946): ageScanResultsOut delay 40000 size 8 now 1452274506421
E/WifiAutoJoinController (  946): newSupplicantResults size=8 known=1 true
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1348): wlan0: Control interface command 'STATUS-NO_EVENTS'
I/RemoteViews( 1239): reapply : com.android.settings 1 36
E/WifiAutoJoinController (  946): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  946): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  946): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  946): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  946): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  946): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  946): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  946): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  946): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  946): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  946): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412
D/HtcWifiControlRoamOffload: (  946): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  946): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  946): Done attemptAutoJoin status=3
E/WifiConfigStore(  946):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  946): handleMessage: X
E/WifiStateMachine(  946): handleMessage: E msg.what=131215
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-60 ;0 ,-127] any roam=0 rt=132346
E/WifiStateMachine(  946): processMsg: ConnectModeState
D/WIFI_ICON( 1239): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  946):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-60 ;0 ,-127] any roam=0 rt=132347
D/StatusBar.NetworkController( 1239): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  946): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  946): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  946): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
,D/WISPrService( 5926): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  946): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  946):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  946): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  946): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  946): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  946): Disconnected - quitting
D/ConnectivityService(  946): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  946): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  946): Removing idletimer
D/usbnet  (  946):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  946): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiConfigStore(  946): Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WifiService(  946): New client listening to asynchronous messages
D/ConnectivityManager.CallbackHandler( 1239): CM callback handler got msg 524292
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
I/SecurityController( 1239): onLost 100
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/PMS     (  946): acquireWL(e5234c5): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 946 1000 null
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
E/WifiTrafficPoller(  946): ADD_CLIENT: 9
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/CSLegacyTypeTracker(  946): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/ConnectivityService(  946): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/ConnectivityService(  946): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
E/ConnectivityService(  946): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  946): ensureActiveMobilePolicyLocked()
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/DATA_ICON( 1239): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/PMS     (  946): acquireWL(3a72ae1a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 946 1000 null
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
D/NetworkPolicy(  946): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  946): updateNetworkEnabledLocked()
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
V/NetworkPolicy(  946): updateIfacesLocked()
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='group'
V/NetworkPolicy(  946): updateNotificationsLocked()
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
D/NetworkManagementService(  946): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/DATA_ICON( 1239): dataConnected: false/false
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/StatusBar.NetworkController( 1239): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/Tethering(  946): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  946): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1348): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  946): will read network variables netId=0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1348): Do not allow key_data field to be exposed
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/PMS     (  946): releaseWL(3a72ae1a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='group'
I/QuickSettingWifi( 1239): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 key_id'
V/NetworkPolicy(  946): updateNetworkEnabledLocked()
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
V/NetworkPolicy(  946): updateNotificationsLocked()
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
I/QuickSettingWifi( 1239): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiConfigStore(  946): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  946):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  946): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  946): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1348): ENABLE_NETWORK (0)
D/wpa_supplicant( 1348): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1348): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1348): wpa_supplicant_scan enter
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
D/wpa_supplicant( 1348): P2P: * P2P IE header
D/wpa_supplicant( 1348): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1348): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1348): wlan0: Add radio work 'scan'@0x556c5a1f40
D/wpa_supplicant( 1348): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1348): wlan0: Starting radio work 'scan'@0x556c5a1f40 after 0.000036 second wait
D/wpa_supplicant( 1348): wlan0: nl80211: scan request
D/wpa_supplicant( 1348): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1348): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1348): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1348): wlan0: Own scan request started a scan in 0.000081 seconds
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  946): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  946): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  946): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1348): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  946): will read network variables netId=0
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1348): Do not allow key_data field to be exposed
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
,D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1348): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1348): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  946): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  946):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1348): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1348): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1348): wpa_supplicant_scan enter
D/wpa_supplicant( 1348): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1348): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1348): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  946): setLastSelectedConfiguration -1
E/WifiStateMachine(  946): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  946): handleMessage: new destination call exit/enter
E/WifiStateMachine(  946): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  946): invokeExitMethods: DisconnectedState
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1348): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  946): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  946): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  946): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  946): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  946): DisconnectedState call setCountryCode()
E/WifiStateMachine(  946):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1348): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
D/wpa_supplicant( 1348): wlan0: nl80211: sched_scan request
D/FlexNetS( 6553): updateSvcAllowedInSettings:false
I/ActivityManager(  946): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6773 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/wpa_supplicant( 1348): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1348): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1348): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1348): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1348): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1348): Got an original EVENT_SCAN_RESULTS
D/WifiP2pService(  946): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1348): wlan0: Scan completed in 0.043894 seconds,
D/WifiP2pService(  946): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1348): nl80211: Received scan results (0 BSSes)
D/WifiP2pService(  946): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1348): wlan0: BSS: Start scan result update 8
W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
E/WifiStateMachine(  946): handleMessage: X
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to no match in scan
D/WIFI    (  946): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/WIFI    (  946):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to no match in scan
D/WIFI    (  946): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to no match in scan
E/WifiStateMachine(  946): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to no match in scan
E/WifiStateMachine(  946): handleMessage: E msg.what=131131
E/WifiStateMachine(  946): processMsg: DisconnectedState
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 5 BSSID 34:36:3b:bd:89:28 SSID 'andilabs' due to no match in scan
D/wpa_supplicant( 1348): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1348): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1348): wlan0: Radio work 'scan'@0x556c5a1f40 done in 0.044996 seconds
D/wpa_supplicant( 1348): wlan0: No suitable network found
D/wpa_supplicant( 1348): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1348): wlan0: Cancelling sched scan
E/WifiStateMachine(  946):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  946): processMsg: ConnectModeState
D/wpa_supplicant( 1348): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
D/wpa_supplicant( 1348): p2p0: Updating scan results from sibling
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1348): nl80211: Received scan results (0 BSSes)
D/FlexNetS( 6553): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1348): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1348): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1348): p2p0: New scan results available (own=0 ext=0)
E/WifiStateMachine(  946):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/wpa_supplicant( 1348): p2p0: No suitable network found
,D/wpa_supplicant( 1348): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 1348): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1348): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
E/WifiStateMachine(  946): handleMessage: X
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 c2:ff:d4:d3:aa:48
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:12:7f:81]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 06:7c:34:12:7f:81
D/WifiMonitor(  946): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 34:36:3b:bd:89:28]
E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 34:36:3b:bd:89:28
,E/WifiMonitor(  946): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  946): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  946): WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  946): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  946): handleMessage: E msg.what=147461
E/WifiStateMachine(  946): processMsg: DisconnectedState
E/WifiStateMachine(  946):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:89 bcn=0
E/WifiStateMachine(  946): processMsg: ConnectModeState
E/WifiStateMachine(  946):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:89 bcn=0,
E/WifiStateMachine(  946): processMsg: DriverStartedState
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
E/WifiStateMachine(  946):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:89 bcn=0
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:89 bcn=0
D/WifiStateMachine(  946): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1348): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  946): [1,452,274,506,520 ms] noteScanEnd no scan source
W/WifiHW  (  946): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1348): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  946): handleMessage: X
D/FlexNetS( 6553): updateSvcAllowedInSettings:false
W/WISPrService( 5926): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5926): trigger connection
D/WISPrService( 5926): continue
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5926): start DataConnection
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5926): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5926): [NET] android_getaddrinfofornet-, err=8
,D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<,
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5926): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5926): [NET] android_getaddrinfofornet-, pass to proxy
D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/libc    ( 5926): [NET] android_getaddrinfo_proxy+
D/libc    ( 5926): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5926): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false
,D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false
,D/WifiService(  946): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false,
D/libc    ( 5926): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5926): [NET] android_getaddrinfofornet-, err=8
,D/WISPrService( 5926): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6553): updateSvcAllowedInSettings:false,
,D/MdScPhnSt( 6773): [152.2.]  listen tmrbb8
,D/MdProvGlob( 6616): remove item 101 (p2d27in195) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 6773): [152.2.] summary 118:p2 ignore
,D/Process (  946): killProcessQuiet, pid=6214
I/ActivityManager(  946): Killing 6214:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6214,
,D/GpsLocationProvider(  946): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  946): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  946): [handleMessage] UPDATE_NETWORK_STATE
,D/PMS     (  946): acquireWL(184f6327): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 946 1000 null
D/GpsLocationProvider(  946): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  946): [AlarmQueuing] connectivity wifi: false
D/htcCheckinService(  946): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  946): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1602): [onReceive] WIFI(1): DISCONNECTED
,I/ActivityManager(  946): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6804 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/art     (  414): Explicit concurrent mark sweep GC freed 8647(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 145us total 22.733ms
,E/GpsLocationProvider(  946): No APN found to select.
,D/PMS     (  946): releaseWL(184f6327): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/art     (  414): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 134us total 15.648ms,
D/MdScPhnSt( 6773): [cb0.1.]  listen tmrbb8
,I/art     (  414): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 145us total 15.930ms,
,D/MdScDataSum( 6773): [cb0.1.] summary 118:p1 ignore
,I/MusicStore( 6804): Database version: 120,
,D/VoldConnector(  946): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6804): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  946): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6804): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  946): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6804): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
,W/ResourcesManager( 6804): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6804): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6804): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6804): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6804): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@51e5f72: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6804): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6804): GMSCore installation verified
,I/ConfigStore( 6804): Config Database version: 1,
,I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6804, uid=10159, userID:0,
,D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client,
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0
D/WifiDisplayAdapter(  946):     IP Address: }
,D/MediaRouterService(  946): Client com.google.android.music (pid 6804): Registered
,D/WifiDisplayAdapter(  946): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  946):     Client/Owner: Client
D/WifiDisplayAdapter(  946):     GroupId: 
D/WifiDisplayAdapter(  946):     Passphrase: 
D/WifiDisplayAdapter(  946):     SessionId: 0,
D/WifiDisplayAdapter(  946):     IP Address: }
,I/MediaRouter( 6804): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6804): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6804, uid=10159, userID:0,
,D/MobileConnectivityChangeReceiver( 6436): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6436): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1672): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1672): Util - no network available!
,I/GHttpClientFactory( 6804): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6804): Using platform SSLCertificateSocketFactory,
,D/AutoSetting( 1672): service - onCreate(),
,I/iu.Environment( 4462): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/PMS     (  946): acquireWL(21c55ed0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1884 10024 WorkSource{10024 com.google.android.gms},
,I/iu.UploadsManager( 4462): num queued entries: 0
D/PMS     (  946): releaseWL(21c55ed0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/iu.UploadsManager( 4462): num updated entries: 0
I/iu.SyncManager( 4462): NEXT; no task
,D/AutoSetting( 1672): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  946): request 204a9bbb passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  946): provider request: passive ProviderRequest[ON interval=0]
D/ChimeraCfgMgr( 4462): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/AutoSetting( 1672): service - mHandler: cancel location update
D/AutoSetting( 1672): service -           changes count: 0
,I/ActivityManager(  946): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6847 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/Babel   ( 6484): connection state changed from UNKNOWN to DISCONNECTED
,D/Process (  946): killProcessQuiet, pid=6391,
I/ActivityManager(  946): Killing 6391:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6391,
,D/VoldConnector(  946): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/ContextImpl( 6847): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  946): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6847): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6847): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6847):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6847):   adb logcat -s GAv4
,D/VoldConnector(  946): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6847): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6847): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
D/VoldConnector(  946): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
W/ContextImpl( 6847): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/GAv4    ( 6847): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6847): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6847): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6847): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6847): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6847): Time to load native libraries: 2 ms (timestamps 6396-6398)
,I/LibraryLoader( 6847): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6847): Binding Chromium to main looper Looper (main, tid 1) {2f97639d},
I/LibraryLoader( 6847): Expected native library version number "",actual native library version number "",
I/chromium( 6847): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6847): Initializing chromium process, singleProcess=true,
,W/art     ( 6847): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6847): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6847): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6847): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6847): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6847): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6847): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6847): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6847): Local Branch: 
I/Adreno-EGL( 6847): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6847): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6847):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6847): Requires BLUETOOTH permission,
,I/art     (  946): Explicit concurrent mark sweep GC freed 35325(1861KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.640ms total 181.384ms
,I/NSApplication( 6847): Starting up...
,I/ActivityManager(  946): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6906 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  946): Killing 6461:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  946): killProcessQuiet, pid=6461
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  946): Recipient 6461,
,D/Process (  946): killProcessQuiet, pid=5962
I/ActivityManager(  946): Killing 5962:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  946): Recipient 5962
,E/WifiStateMachine(  946): handleMessage: E msg.what=131168,
,E/WifiStateMachine(  946): processMsg: DisconnectedState
,E/WifiStateMachine(  946):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  946): processMsg: ConnectModeState
,E/WifiStateMachine(  946):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  946): processMsg: DriverStartedState,
E/WifiStateMachine(  946):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  946): processMsg: SupplicantStartedState
E/WifiStateMachine(  946):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  946): processMsg: DefaultState
E/WifiStateMachine(  946):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  946): handleMessage: X
,I/jxcore-log( 6712): Test app app.js loaded,
I/jxcore-log( 6712): 
,I/chromium( 6712): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/PMS     (  946): acquireWL(ff15e06): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6804 10159 null,
,I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6804, uid=10159, userID:0
,D/WearableService( 5671): callingUid 10024, callindPid: 5671,
D/PMS     (  946): releaseWL(ff15e06): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6804): Conditions not met for autocaching. okToAttempt=false,
I/MusicLeanback( 6804): Stop autocaching.
,E/GmsUtils( 6804): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6804): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  946): acquireWL(d212451): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000}
V/AlarmManager(  946): sending alarm PendingIntent{2e00d50d: PendingIntentRecord{2c52dcc2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=125922, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{17d354b6: PendingIntentRecord{38eb5b7 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143302, Int=0
,D/PMS     (  946): releaseWL(d212451): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1239): Weather sync is On
W/WeatherTimeKeeper( 1239): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  946): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  946): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/ContactMessageStore( 1559): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1559): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1672): service - handleMessage() stop self
,D/AutoSetting( 1672): service - handleMessage() quit looper
,D/AutoSetting( 1672): service - onDestroy() END
,D/PMS     (  946): acquireWL(1ab5124): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
,I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(1ab5124): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1239): closing low battery warning: level=100
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  946): updateBatteryInfo
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  946): >> updateStatus
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): handleMessage: E msg.what=155652
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1559): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  946): acquireWL(e82b48d): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{1000},
V/AlarmManager(  946): sending alarm PendingIntent{32b80642: PendingIntentRecord{34ef653 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452274545714, Int=0
D/PMS     (  946): acquireWL(ede5b90): PARTIAL_WAKE_LOCK  *backup* 0x1 946 1000 null
V/AlarmManager(  946): sending alarm PendingIntent{35f30c89: PendingIntentRecord{144448e android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=174089, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{2e00d50d: PendingIntentRecord{2c52dcc2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=185921, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{2ac8a4af: PendingIntentRecord{27f5a0bc com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189707, Int=0
,D/HtcSystemUPManager(  946): UPAlarmListener onAlarmArrival
D/HtcSystemUPManager(  946): UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1452274563805, last = 1452252948166, freq = 21600000
,D/HtcSystemUPManager(  946): AlarmScheduler_INEXACT [onReceive] end
D/HtcSystemUPManager(  946): com.htc.upm.AlarmScheduler$SchedulerBase$1@15e2e6c6
,W/BackupManagerService(  946): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  946): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  946): releaseWL(ede5b90): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  946): acquireWL(27f6e845): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/HtcSystemUPManager(  946): HtcSystemUPHandler sendService() has been called
D/PMS     (  946): releaseWL(27f6e845): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcSystemUPManager(  946): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
D/HtcSystemUPManager(  946): HtcSystemUPHandler send to UPService takes: 1 ms
,D/PMS     (  946): releaseWL(e82b48d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1239): Weather sync is On
,W/WeatherTimeKeeper( 1239): [refreshWeatherData] no weather data,
,D/PMS     (  946): releaseWL(e5234c5): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  946): Failed to find a new network - expiring NetTransition Wakelock
,D/PMS     (  946): acquireWL(12a2c3c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{1000},
V/AlarmManager(  946): sending alarm PendingIntent{2f385766: PendingIntentRecord{4827aa7 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=208532, Int=0
,D/PMS     (  946): releaseWL(12a2c3c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/HtcUPManager( 1239): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcUPManager( 1239): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1672): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@289b45d1
,D/Process (  946): killProcessQuiet, pid=5873
I/ActivityManager(  946): Killing 5873:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 5873,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  946): acquireWL(31174b54): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(31174b54): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  946): updateBatteryInfo
D/NotificationService(  946): plugged=true pluggin=true
D/PowerUI ( 1239): closing low battery warning: level=100
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
,D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/PMS     (  946): runPSCheck
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  946): acquireWL(16d6dafd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(16d6dafd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  946): updateBatteryInfo,
D/PMS     (  946): runPSCheck
D/HtcPowerSaver(  946): Checking...
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): >> updateStatus
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  946): << updateStatus
D/PowerUI ( 1239): closing low battery warning: level=100
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/NotificationService(  946): plugged=true pluggin=true
,D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/WifiController(  946): battery changed pluggedType: 2
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  946): acquireWL(ce283f2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000}
V/AlarmManager(  946): sending alarm PendingIntent{2e00d50d: PendingIntentRecord{2c52dcc2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=245922, Int=0
,V/AlarmManager(  946): sending alarm PendingIntent{347c8c0: PendingIntentRecord{93b29f9 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1452274715391, Int=0
,D/WeatherUtility( 1239): Weather sync is On,
D/PMS     (  946): releaseWL(ce283f2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1239): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  946): acquireWL(2490ed3e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(2490ed3e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  946): updateBatteryInfo
D/NotificationService(  946): plugged=true pluggin=true
D/PMS     (  946): runPSCheck
D/HtcPowerSaver(  946): Checking...
I/HtcPowerSaver(  946): >> updateStatus
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1239): closing low battery warning: level=100
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  946): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  946): << updateStatus
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/WifiController(  946): battery changed pluggedType: 2
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  946): handleMessage: X
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  946): acquireWL(35f2179f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
,I/BatteryService(  946): n_update end
,D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/PMS     (  946): releaseWL(35f2179f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/PowerUI ( 1239): closing low battery warning: level=100
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): handleMessage: E msg.what=155652
D/PMS     (  946): runPSCheck
,D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  946): Checking...
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): >> updateStatus
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  946): acquireWL(1f40b0ec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
,I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(1f40b0ec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
,D/NotificationService(  946): plugged=true pluggin=true
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1239): closing low battery warning: level=100
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  946): updateBatteryInfo
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/WifiController(  946): battery changed pluggedType: 2
,D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  946): >> updateStatus
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  946): acquireWL(6fb6cb5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(6fb6cb5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  946): updateBatteryInfo
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  946): plugged=true pluggin=true
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/PMS     (  946): runPSCheck
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  946): >> updateStatus
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/PowerUI ( 1239): closing low battery warning: level=100
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  946): battery changed pluggedType: 2
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
,D/WifiController(  946): handleMessage: X
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1559): MSG_CHECK_DELETION >>,
,D/ContactMessageStore( 1559): mDeleteTask = null, bDeleting = false,
D/AccFlag ( 1559): sku_id=118,
D/ContactMessageStore( 1559): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1559): start background delete task...
,D/ContactMessageStore( 1559): size: 0 , 0
,D/ContactMessageStore( 1559): Background delete complete
,D/PMS     (  946): acquireWL(1d2a9f4a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(1d2a9f4a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): onReceive BATTERY_CHANGED
,D/PowerUI ( 1239): closing low battery warning: level=100
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): battery changed pluggedType: 2
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  946): handleMessage: E msg.what=155652
,D/PMS     (  946): runPSCheck
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): processMsg: DeviceActiveState
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  946): processMsg: DefaultState
I/HtcPowerSaver(  946): << updateStatus
D/WifiController(  946): handleMessage: X
,D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  946): acquireWL(24ea8ebb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(24ea8ebb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1239): closing low battery warning: level=100
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/NotificationService(  946): plugged=true pluggin=true
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  946): runPSCheck
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
I/HtcPowerSaver(  946): >> updateStatus
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): battery changed pluggedType: 2
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(efdefd8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000}
V/AlarmManager(  946): sending alarm PendingIntent{2e00d50d: PendingIntentRecord{2c52dcc2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=365922, Int=0
,V/AlarmManager(  946): sending alarm PendingIntent{2571dbf7: PendingIntentRecord{3a8a1a64 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805048, Int=0
,I/ActivityManager(  946): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=6944 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,V/AlarmManager(  946): sending alarm PendingIntent{1a431f31: PendingIntentRecord{3c0fe4ed com.android.vending startService}}, i=null, t=0, cnt=1, w=1452275080906, Int=0
,I/ActivityManager(  946): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6959 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  946): sending alarm PendingIntent{32fb6616: PendingIntentRecord{19295b97 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1452274977998, Int=0,
,D/PMS     (  946): releaseWL(efdefd8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1239): Weather sync is On
,W/WeatherTimeKeeper( 1239): [refreshWeatherData] no weather data
,I/PackageManager(  946):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6944, uid=10072, userID:0,
,W/global  ( 6944): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6944): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 6944): [apache-http] Connection GC has been deprecated!,
,E/cutils-trace( 6993): Error opening trace file: Permission denied (13),
I/dex2oat ( 6993): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6993): dex2oat: override thread count:4
,W/global  ( 6944): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6944): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  946): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7008 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 6944): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6944): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7008): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7008): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PackageManager(  946):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6944, uid=10072, userID:0
,I/MultiDex( 7008): VM with version 2.1.0 has multidex support,
,I/MultiDex( 7008): install
I/MultiDex( 7008): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6944): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Finsky  ( 6944): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6944): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6944): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/JNIHelp ( 7008): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 6944): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 7008): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 7008): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d56a1c8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7008): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1884): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1884): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4462): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,W/Finsky  ( 6944): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/WearableService( 5671): callingUid 10024, callindPid: 5671
,I/PackageManager(  946):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4462, uid=10024, userID:0
,E/MDM     ( 1843): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4462): Restart initialization of location
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6944): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/Finsky  ( 6944): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,I/dex2oat ( 6993): dex2oat took 721.357ms (threads: 4)
,I/PushClient( 6959): ApplicationMonitor {be56838}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6959): ApplicationMonitor {be56838}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6959): ApplicationMonitor {be56838}: logBasicAppInfo(): VersionName:             1.2.853019,
I/PushClient( 6959): ApplicationMonitor {be56838}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6959): ApplicationMonitor {be56838}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6959): ApplicationMonitor {be56838}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6959): ApplicationMonitor {be56838}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6959): ApplicationMonitor {be56838}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6959): ApplicationMonitor {be56838}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6959): PnsModel {251d2c9b}: update(): Update registration caused by: alarm,
,I/PushClient( 6959): PnsConfigModel {2903cd4e}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6959): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6959): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6959): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6959): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,E/AndroidHttpClient( 6944): Leak found
E/AndroidHttpClient( 6944): java.lang.IllegalStateException: AndroidHttpClient created and never closed,
E/AndroidHttpClient( 6944): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 6944): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 6944): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 6944): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 6944): ,	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 6944): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 6944): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 6944): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 6944): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 6944): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 6944): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 6944): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 6944): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 6944): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 6944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 6944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  946): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7049 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7049): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7049 dbg=false s=true,
,I/DeviceManagement( 7049): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 7049): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7049): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 7049): WorkflowService: Starting workflow service
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DeviceManagement( 7049): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@251d2c9b] args=[Bundle[mParcelledData.dataSize=88]]
I/DeviceManagement( 7049): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7049): ModelRegistry: Loading model meta data from resources...
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DeviceManagement( 7049): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,W/Finsky  ( 6944): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/DeviceManagement( 7049): SessionStateController: Checking invariants...
,D/Finsky  ( 6944): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6944): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 6944): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1843): client connected with version: 7571000
,I/DeviceManagement( 7049): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7049): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7049): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7049): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@251d2c9b],
,I/DeviceManagement( 7049): WorkflowService: Stopping workflow service
,D/Process (  946): killProcessQuiet, pid=6584
I/ActivityManager(  946): Killing 6584:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6959): PnsModel {251d2c9b}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  946): Recipient 6584,
D/WifiService(  946): Client connection lost with reason: 4
,D/Process (  946): killProcessQuiet, pid=6648
I/ActivityManager(  946): Killing 6648:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6648
,I/ActivityManager(  946): Killing 6514:com.htc.sense.mms/u0a64 (adj 15): empty #17,
,D/Process (  946): killProcessQuiet, pid=6514
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6514
,I/ActivityManager(  946): Killing 5926:com.android.settings/1000 (adj 15): empty #17,
D/Process (  946): killProcessQuiet, pid=5926,
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 5926
,D/WifiService(  946): Client connection lost with reason: 4
,D/PMS     (  946): acquireWL(3a67c699): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{10072},
,V/AlarmManager(  946): sending alarm PendingIntent{30085d5e: PendingIntentRecord{b5dcf80 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452275195075, Int=0
D/PMS     (  946): releaseWL(3a67c699): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 6944): [697] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 6944): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  946): acquireWL(14b6953f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(14b6953f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  946): runPSCheck
,D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): handleMessage: E msg.what=155652
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  946): processMsg: DefaultState
I/HtcPowerSaver(  946): << updateStatus
D/WifiController(  946): handleMessage: X
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1239): closing low battery warning: level=100
,D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  946): acquireWL(20f0ee0c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000}
,V/AlarmManager(  946): sending alarm PendingIntent{2e00d50d: PendingIntentRecord{2c52dcc2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=845922, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{18653355: PendingIntentRecord{178f16a com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941252, Int=0
,I/bt-btm  ( 3122): Received oneshot timer event complete
I/bt-btm  ( 3122): btm_ble_timeout
I/bt-btm  ( 3122): btm_gen_resolvable_private_addr
,D/WeatherUtility( 1239): Weather sync is On,
W/WeatherTimeKeeper( 1239): [refreshWeatherData] no weather data
,I/art     (  946): Explicit concurrent mark sweep GC freed 24745(1183KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.965ms total 173.516ms
,D/PMS     (  946): acquireWL(1c09465b): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3122 1002 null,
,D/PMS     (  946): releaseWL(20f0ee0c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/bt-btm  ( 3122): btm_ble_rand_enc_complete
,I/bt-btm  ( 3122): btm_gen_resolve_paddr_low
D/bt-smp  ( 3122): smp_encrypt_data
W/bt-smp  ( 3122): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3122): Plain text(LSB ~ MSB) = b8 c8 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3122): Encrypted text(LSB ~ MSB) = 09 8e 6f 67 db 90 b5 70 72 4f 7e 18 eb d4 44 35 
I/bt-btm  ( 3122): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3122): Stopping oneshot timer,
D/bt-btm  ( 3122): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  946): releaseWL(1c09465b): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  946): acquireWL(8c4def8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(8c4def8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  946): updateBatteryInfo
D/PMS     (  946): runPSCheck
D/HtcPowerSaver(  946): Checking...
I/HtcPowerSaver(  946): >> updateStatus
,D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1239): closing low battery warning: level=100
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  946): << updateStatus
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/NotificationService(  946): plugged=true pluggin=true
,D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(2392afd1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000},
V/AlarmManager(  946): sending alarm PendingIntent{2e00d50d: PendingIntentRecord{2c52dcc2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=965922, Int=0
,V/AlarmManager(  946): sending alarm PendingIntent{23acba36: PendingIntentRecord{585aa21 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452275340873, Int=0,
,I/ActivityManager(  946): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=7079 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/WeatherUtility( 1239): Weather sync is On
,W/WeatherTimeKeeper( 1239): [refreshWeatherData] no weather data
,W/ContextImpl( 7079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  946): releaseWL(2392afd1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 7079): MY_DEBUG = false
,D/PowerUsageService( 7079): repeat time = 1452276241072,
,I/PowerUsageList:PowerUsageHelper( 7079): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 7079): gen(), null == sipper.uidObj, userId = 0,
,D/Process (  946): killProcessQuiet, pid=6616
I/ActivityManager(  946): Killing 6616:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  946): Recipient 6616
,D/PMS     (  946): acquireWL(1fe4f2a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{1000}
V/AlarmManager(  946): sending alarm PendingIntent{2541780d: PendingIntentRecord{368243c2 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452275387737, Int=0
,D/SmartSyncUtils( 7079): isEpsOn(), nState = 0
,D/PMS     (  946): acquireWL(102825d3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7079 1000 null,
D/PMS     (  946): releaseWL(1fe4f2a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  946): releaseWL(102825d3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  946): acquireWL(30d09510): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7079 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 7079): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 7079): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 7079): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 7079): SettingOnTime = 1452319200000, randomSettingOnTime = 1452316889000
D/SmartSyncScreenOnOffTimeReceiver( 7079): SettingOffTime = 1452297600000, randomSettingOffTime = 1452297960000
D/SmartSyncScreenOnOffTimeReceiver( 7079): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 7079): bNightMode = true,
D/SmartSyncScreenOnOffTimeReceiver( 7079): bNightModeTurnOffOnce = false
,D/PMS     (  946): releaseWL(30d09510): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1884): Explicit concurrent mark sweep GC freed 16467(922KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.053ms total 67.402ms,
,D/DotMatrix( 1363): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1363): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1239): reapply : com.google.android.gms 4 40
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268),
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	,at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6944): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6944): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6944): Ignoring header User-Agent because its value was null.
,D/libc    ( 6944): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6944): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6944): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6944): [NET] android_getaddrinfo_proxy+
D/libc    ( 6944): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6944): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  946): acquireWL(14772172): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(14772172): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): handleMessage: E msg.what=155652
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): processMsg: DeviceActiveState
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
,D/WifiController(  946): handleMessage: X
D/PowerUI ( 1239): closing low battery warning: level=100
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(131629c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(131629c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  946): updateBatteryInfo
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1239): closing low battery warning: level=100
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  946): >> updateStatus
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  946): User[0] Flushing usage stats to disk,
,D/PMS     (  946): acquireWL(30fb6240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/PMS     (  946): releaseWL(30fb6240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/NotificationService(  946): plugged=true pluggin=true
,D/WifiController(  946): handleMessage: E msg.what=155652
D/PMS     (  946): runPSCheck
D/WifiController(  946): processMsg: DeviceActiveState
D/HtcPowerSaver(  946): Checking...
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): handleMessage: X
D/PowerUI ( 1239): closing low battery warning: level=100
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): << updateStatus
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  946): acquireWL(30788579): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(30788579): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1239): closing low battery warning: level=100
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  946): updateBatteryInfo
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/PMS     (  946): runPSCheck
D/WifiController(  946): handleMessage: E msg.what=155652
D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: StaEnabledState
,I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(1091e2be): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null
I/BatteryService(  946): n_update end
D/UsbnetService(  946): BroadcastReceiver::onReceive+
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  946): releaseWL(1091e2be): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  946): updateBatteryInfo
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  946): plugged=true pluggin=true
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1239): closing low battery warning: level=100
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/PMS     (  946): runPSCheck
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  946): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  946): Checking...
D/WifiController(  946): handleMessage: E msg.what=155652
I/HtcPowerSaver(  946): >> updateStatus
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): battery changed pluggedType: 2
D/WifiController(  946): processMsg: StaEnabledState
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  946): processMsg: DefaultState
I/HtcPowerSaver(  946): << updateStatus
D/WifiController(  946): handleMessage: X
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6944): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6944): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1239): reapply : com.google.android.gms 2 40
,W/System  ( 6944): Ignoring header User-Agent because its value was null.
D/DotMatrix( 1363): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1363): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/libc    ( 6944): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6944): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6944): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6944): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6944): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6944): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  946): acquireWL(1cbdb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(1cbdb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  946): plugged=true pluggin=true,
D/PowerUI ( 1239): closing low battery warning: level=100
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  946): updateBatteryInfo
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  946): runPSCheck
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  946): Checking...
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  946): >> updateStatus
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/WifiController(  946): battery changed pluggedType: 2
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
,D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(948bee9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(948bee9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  946): updateBatteryInfo,
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1239): closing low battery warning: level=100
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  946): plugged=true pluggin=true
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  946): >> updateStatus
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  946): battery changed pluggedType: 2
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6944): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6944): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1363): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1363): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 6944): Ignoring header User-Agent because its value was null.
D/libc    ( 6944): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6944): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6944): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6944): [NET] android_getaddrinfo_proxy+
D/libc    ( 6944): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
I/RemoteViews( 1239): reapply : com.google.android.gms 4 40
D/libc    ( 6944): [NET] android_getaddrinfo_proxy-, NODATA
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  946): acquireWL(1e0500a0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 946 1000 WorkSource{1000},
,V/AlarmManager(  946): sending alarm PendingIntent{2e00d50d: PendingIntentRecord{2c52dcc2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1025922, Int=0
I/bt-btm  ( 3122): Received oneshot timer event complete
D/PMS     (  946): acquireWL(2a123459): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3122 1002 null
I/bt-btm  ( 3122): btm_ble_timeout
I/bt-btm  ( 3122): btm_gen_resolvable_private_addr
,V/AlarmManager(  946): sending alarm PendingIntent{b89981e: PendingIntentRecord{1b2318ff com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1841441, Int=0,
,D/bt-btm  ( 3122): btm_ble_rand_enc_complete,
I/bt-btm  ( 3122): btm_gen_resolve_paddr_low
D/bt-smp  ( 3122): smp_encrypt_data
,W/bt-smp  ( 3122): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3122): Plain text(LSB ~ MSB) = e9 28 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3122): Encrypted text(LSB ~ MSB) = 15 23 8d 27 d1 6c 98 e2 cd 97 ff c7 18 ab 5e 85 
I/bt-btm  ( 3122): btm_gen_resolve_paddr_cmpl
,W/bt-btm  ( 3122): Stopping oneshot timer
D/bt-btm  ( 3122): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  946): Prepared write state in 14ms,
,I/ProcessStatsService(  946): Prepared write state in 13ms
,D/PMS     (  946): releaseWL(1e0500a0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1239): Weather sync is On
W/WeatherTimeKeeper( 1239): [refreshWeatherData] no weather data
,I/ProcessStatsService(  946): Pruning old procstats: /data/system/procstats/state-2016-01-08-05-16-01.bin,
,D/PMS     (  946): releaseWL(2a123459): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  946): acquireWL(13c986cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  946): releaseWL(13c986cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  946): updateBatteryInfo
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
D/NotificationService(  946): plugged=true pluggin=true
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  946): runPSCheck
D/UsbnetService(  946): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  946): Checking...
D/UsbnetService(  946): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  946): >> updateStatus
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  946): battery changed pluggedType: 2
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
,D/PowerUI ( 1239): closing low battery warning: level=100
I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  946): << updateStatus
D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  946): acquireWL(21a8bd15): PARTIAL_WAKE_LOCK  *alarm* 0x1 946 1000 WorkSource{1000},
V/AlarmManager(  946): sending alarm PendingIntent{2571dbf7: PendingIntentRecord{3a8a1a64 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1525150, Int=0
,V/AlarmManager(  946): sending alarm PendingIntent{35cf5d63: PendingIntentRecord{35511d60 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1824975, Int=1800000
D/PMS     (  946): acquireWL(11b3182a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 946 1000 null
,V/AlarmManager(  946): sending alarm PendingIntent{2e00d50d: PendingIntentRecord{2c52dcc2 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1865922, Int=0
,V/AlarmManager(  946): sending alarm PendingIntent{351a461b: PendingIntentRecord{316e43b8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452275729952, Int=1800000
V/AlarmManager(  946): sending alarm PendingIntent{3ce51591: PendingIntentRecord{39428cf6 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1854153, Int=0
V/AlarmManager(  946): sending alarm PendingIntent{248d28f7: PendingIntentRecord{585aa21 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452276241072, Int=0
D/PMS     (  946): releaseWL(11b3182a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  946): updateNetworkEnabledLocked()
V/NetworkPolicy(  946): updateNotificationsLocked()
,D/WeatherUtility( 1239): Weather sync is On,
W/WeatherTimeKeeper( 1239): [refreshWeatherData] no weather data
,D/PMS     (  946): acquireWL(389fe364): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4462 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): acquireWL(29828282): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4462 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  946): releaseWL(389fe364): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 7079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  946): releaseWL(21a8bd15): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
D/PowerUsageList:PowerUsageHelper( 7079): MY_DEBUG = false
,D/PowerUsageService( 7079): repeat time = 1452277141160
,I/EventLogService( 4462): Aggregate from 1452274475396 (log), 1452273929901 (data)
,D/LocationManagerService(  946): getAllProviders()=[passive, gps, network],
,D/PMS     (  946): releaseWL(29828282): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 7079): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 7079): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  946): acquireWL(257d4f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 946 1000 null,
I/BatteryService(  946): n_update end
D/PMS     (  946): releaseWL(257d4f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  946): updateBatteryInfo,
D/UsbnetService(  946): BroadcastReceiver::onReceive+
D/NotificationService(  946): plugged=true pluggin=true
D/UsbnetService(  946): onReceive BATTERY_CHANGED
D/WifiController(  946): battery changed pluggedType: 2
D/UsbnetService(  946):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1239): closing low battery warning: level=100
D/UsbnetService(  946): BroadcastReceiver::onReceive-
D/PMS     (  946): runPSCheck
I/IntentController( 1239): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  946): Checking...
,D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  946): >> updateStatus
D/DotMatrix( 1363): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1363): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  946): handleMessage: E msg.what=155652
D/WifiController(  946): processMsg: DeviceActiveState
D/WifiController(  946): processMsg: StaEnabledState
D/WifiController(  946): processMsg: DefaultState
D/WifiController(  946): handleMessage: X
D/HeadsetStateMachine( 3122): Disconnected process message: 10, size: 0
,D/PowerUI ( 1239): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  946): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  946): << updateStatus
,I/BatteryController( 1239): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 7123): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7123): ====startRecUseTime====
D/htc.customization.log.level( 7123):  is 
W/CustomizationLogLevel( 7123): Level value is invalid, use default level 2
D/CustomizationManager( 7123):  Read ACC file spent 0.048 (s)
D/CIDMapFileReader( 7123): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7123): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7123): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7123): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7123): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7123): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7123): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7123): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7123): Parsing tag category name = system
I/CustomizationCIDLoader( 7123): Parsing tag category name = application
I/CustomizationCIDLoader( 7123): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7123): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7123): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7123): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7123): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7123): add string-array item, value = 42507
I/CustomizationCIDLoader( 7123): add string-array item, value = 21902
I/CustomizationCIDLoader( 7123): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7123): add string-array item, value = 23420
I/CustomizationCIDLoader( 7123): add string-array item, value = 22299
I/CustomizationCIDLoader( 7123): add string-array item, value = 24002
I/CustomizationCIDLoader( 7123): add string-array item, value = 23210
I/CustomizationCIDLoader( 7123): add string-array item, value = 23205
I/CustomizationCIDLoader( 7123): add string-array item, value = 23806
I/CustomizationCIDLoader( 7123): add string-array item, value = 23430
I/CustomizationCIDLoader( 7123): add string-array item, value = 23408
I/CustomizationCIDLoader( 7123): add string-array item, value = 27205
I/CustomizationCIDLoader( 7123): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7123): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7123):  Read CID file spent 0.103 (s)
D/CustomizationManager( 7123):  All configurations done spent 0.104 (s)
D/PackageManager(  946): deletePackageAsUser: pkg=com.test.thalitest, pid=7123, uid=2000 userid=0
I/ActivityManager(  946): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  946): killProcessQuiet, pid=6712
I/ActivityManager(  946): Killing 6712:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  946): Skipping PackageSetting{9118926 com.example.hello/10374} due to missing metadata
I/ActivityManager(  946): Recipient 6712
D/WifiService(  946): Client connection lost with reason: 4
E/InputEventReceiver( 1430): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{d76af0e uid 10366 pid 6712} (c)'
I/WindowState(  946): WIN DEATH: Window{14e0c8c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  946): Killing 6484:com.google.android.talk/u0a112 (adj 11): empty for 1803s
D/Process (  946): killProcessQuiet, pid=6484
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  946): Recipient 6484
D/Process (  946): killProcessQuiet, pid=6036
I/ActivityManager(  946): Killing 6036:com.google.android.apps.plus/u0a167 (adj 13): empty for 1803s
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  946): Recipient 6036
D/Process (  946): killProcessQuiet, pid=6906
I/ActivityManager(  946): Killing 6906:com.android.chrome/u0a96 (adj 13): empty for 1803s
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  946): Recipient 6906
D/Process (  946): killProcessQuiet, pid=6847
I/ActivityManager(  946): Killing 6847:com.google.android.apps.magazines/u0a161 (adj 13): empty for 1804s
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  946): Recipient 6847
D/Process (  946): killProcessQuiet, pid=6436
I/ActivityManager(  946): Killing 6436:com.google.android.setupwizard/u0a77 (adj 13): empty for 1805s
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  946): Recipient 6436
D/Process (  946): killProcessQuiet, pid=6553
I/ActivityManager(  946): Killing 6553:com.htc.bgp/u0a11 (adj 15): empty for 1805s
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  946): Recipient 6553
I/ActivityManager(  946): Killing 6773:com.htc.mobiledata:remote/u0a46 (adj 15): empty for 1805s
D/Process (  946): killProcessQuiet, pid=6773
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  946): Recipient 6773
I/ActivityManager(  946):   Force finishing activity ActivityRecord{261dab4f u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  946): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  946):   Force finishing activity ActivityRecord{261dab4f u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  946): Duplicate finish request for ActivityRecord{261dab4f u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  946): Spurious death for ProcessRecord{3e6cd339 6712:com.test.thalitest/u0a366}, curProc for 6712: null
D/DotMatrix( 1363): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1363): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1363): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  946): acquireWL(1a102df): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1843 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1843): Ignoring removeGeofence because network location is disabled.
W/SystemReader(  946): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1779): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  946): releaseWL(1a102df): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1779): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/art     ( 1602): Explicit concurrent mark sweep GC freed 2745(149KB) AllocSpace objects, 6(492KB) LOS objects, 34% free, 29MB/45MB, paused 1.360ms total 92.339ms
I/Prism.ItemManager( 1602): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1602): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1740): Cleaning up data for package: com.test.thalitest
D/PhoneApp( 1559): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/Launcher( 1602): Deferring update until onResume
D/Launcher( 1602): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1602): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1672): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1672): handle notify Blinkfeed plugin client changed
D/AccTypeManager( 1779): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  946): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7143 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/ExternalAccountType( 1779): Unsupported attribute readOnly
I/art     (  946): Explicit concurrent mark sweep GC freed 34321(2MB) AllocSpace objects, 17(1716KB) LOS objects, 33% free, 16MB/24MB, paused 1.685ms total 228.014ms
I/art     (  946): WaitForGcToComplete blocked for 224.884ms for cause Explicit
I/InputMethodManagerService(  946): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/StatusBarManagerService(  946): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  946): hiding MENU key
D/StatusBarManagerService(  946): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  946): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  946): hiding MENU key
W/ContextImpl( 7143): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/FindExtension( 1602): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1602): Defer allocateBuffers to drawing time
W/InputMethodManagerService(  946): Got RemoteException sending setActive(false) notification to pid 6712 uid 10366
D/StatusBarManagerService(  946): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  946): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7167 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  946): killProcessQuiet, pid=6804
I/ActivityManager(  946): Killing 6804:com.google.android.music:main/u0a159 (adj 15): empty for 1801s
D/Process (  946): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager(  946): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/PackageManager(  946): Unable to load service info ResolveInfo{1d48df8c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  946): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  946): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  946): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  946): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  946): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  946): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  946): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  946): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  946): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  946): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  946): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  946): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/art     (  946): Explicit concurrent mark sweep GC freed 7840(417KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 2.169ms total 187.179ms
D/JobSchedulerService(  946): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  946): Recipient 6804
D/MediaRouterService(  946): Client com.google.android.music (pid 6804): Died!
I/PhoneStatusBar( 1239): setImeWindowStatus(false,false)
D/TaskPersister(  946): removeObsoleteFile: deleting file=8_task.xml
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7167): -onCreate()
V/Settings:HtcSettingsApplication( 7167): [7167/7167] onCreate()
E/SQLiteLog( 1884): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1884): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x557e698ad0
E/AndroidRuntime( 1884): FATAL EXCEPTION: main
E/AndroidRuntime( 1884): Process: com.google.process.gapps, PID: 1884
E/AndroidRuntime( 1884): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1884): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1884): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1884): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1884): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1884): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1884): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1884): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1884): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1884): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1884): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1884): 	... 9 more
E/ActivityManager(  946): App crashed! Process: com.google.process.gapps
D/Process ( 1884): killProcess, pid=1884
D/Process ( 1884): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  946): Can't write: system_app_crash
E/DropBoxManagerService(  946): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  946): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  946): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  946): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  946): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  946): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  946): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  946): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  946): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  946): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  946): 	... 5 more
D/Settings:HtcWirelessFeatureFlags( 7167): id/is att sku: 118/false
E/Settings:HtcWrapHeaderInfo( 7167): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7167): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7167): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7167): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]support         :false
I/ActivityManager(  946): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7167): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7167): isSupportVoWifi: null
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7167): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7167): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7167): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7167): [supportHomeButton]support         :false
I/ActivityManager(  946): Recipient 1884
I/ActivityManager(  946): Process com.google.process.gapps (pid 1884) has died
W/ActivityManager(  946): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
W/ActivityManager(  946): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
I/ActivityManager(  946): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7167): isSupportVoWifi: null
E/ActivityThread( 7167): Failed to find provider info for com.htc.vowifi
I/Prism.ItemManager( 1602): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1602): loadItems() com.htc.launcher.pageview.WidgetManager@3a8097b4 +
I/Prism.WidgetManager( 1602): onLoadItems() +
W/ResourcesManager( 1602): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 1602): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/asset   ( 1602): Copying FileAsset 0x557ec4a0e0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.

```
