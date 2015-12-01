#### Test 519863408c638e9_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 7061): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7061): ====startRecUseTime====
D/htc.customization.log.level( 7061):  is 
W/CustomizationLogLevel( 7061): Level value is invalid, use default level 2
D/CustomizationManager( 7061):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 7061): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7061): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7061): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7061): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7061): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7061): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7061): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7061): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7061): Parsing tag category name = system
I/CustomizationCIDLoader( 7061): Parsing tag category name = application
I/CustomizationCIDLoader( 7061): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7061): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7061): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7061): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7061): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7061): add string-array item, value = 42507
I/CustomizationCIDLoader( 7061): add string-array item, value = 21902
I/CustomizationCIDLoader( 7061): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7061): add string-array item, value = 23420
I/CustomizationCIDLoader( 7061): add string-array item, value = 22299
I/CustomizationCIDLoader( 7061): add string-array item, value = 24002
I/CustomizationCIDLoader( 7061): add string-array item, value = 23210
I/CustomizationCIDLoader( 7061): add string-array item, value = 23205
I/CustomizationCIDLoader( 7061): add string-array item, value = 23806
I/CustomizationCIDLoader( 7061): add string-array item, value = 23430
I/CustomizationCIDLoader( 7061): add string-array item, value = 23408
I/CustomizationCIDLoader( 7061): add string-array item, value = 27205
I/CustomizationCIDLoader( 7061): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7061): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7061):  Read CID file spent 0.099 (s)
D/CustomizationManager( 7061):  All configurations done spent 0.099 (s)
--------- beginning of system
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7061 on display 0
D/PMS     (  966): acquireHCC(967a532): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 966 1000 null
D/PMS     (  966): acquireHCC(c22c283): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 966 1000 null
W/asset   (  966): Copying FileAsset 0x55879a71d0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7079 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  966): Display changed displayId=0
D/DotMatrix( 1327): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1327): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 7079): Copying FileAsset 0xabf73290 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1518): [trimMemory] 20
I/WebViewFactory( 7079): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 7079): Time to load native libraries: 9 ms (timestamps 9981-9990),
,I/LibraryLoader( 7079): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 7079): Binding Chromium to main looper Looper (main, tid 1) {299c6918},
I/LibraryLoader( 7079): Expected native library version number "",actual native library version number ""
,I/chromium( 7079): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 7079): Initializing chromium process, singleProcess=true,
,W/art     ( 7079): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 7079): ApplicationContext is null in ApplicationStatus,
,W/chromium( 7079): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 7079): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7079): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7079): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7079): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7079): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7079): Local Branch: 
,I/Adreno-EGL( 7079): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7079): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7079):                  d74aa161a12b9c6fc6332151
,W/System.err(  966): java.lang.Throwable: stack dump,
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  966): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18e58fd7:true
,D/BluetoothAdapter( 7079): 947584708: getState(). Returning 12
,W/art     ( 7079): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 7079): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 7079): CordovaWebView is running on device made by: HTC
,W/art     ( 7079): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 7079): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  966): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 7079): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  966): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key,
D/StatusBarManagerService(  966): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
,D/FindExtension( 7079): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 7079): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2a9de292, mServedView=org.apache.cordova.engine.SystemWebView{f2e2463 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@d4dd860,
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
I/InputMethodManagerService(  966): Disable input method client, pid=1518
D/StatusBarManagerService(  966): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 7079): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +629ms (total +676ms)
,W/BindingManager( 7079): Cannot call determinedVisibility() - never saw a connection for the pid: 7079,
,D/JsMessageQueue( 7079): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 7079): JniHelper::setJavaVM(0xaae078f8), pthread_self() = -1407899408
,D/JX-Cordova( 7079): jxcore cordova android initializing
,I/ActivityManager(  966): Killing 5975:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=5975
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 5975,
,W/jxcore-log( 7079): Initializing JXcore engine,
W/jxcore-log( 7079): JXcore engine is ready
,W/jxcore-log( 7079): Starting JXcore engine,
,W/jxcore-log( 7079): Platform android,
W/jxcore-log( 7079): 
W/jxcore-log( 7079): Process ARCH arm
W/jxcore-log( 7079): 
,D/PMS     (  966): releaseHCC(967a532): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  966): releaseHCC(c22c283): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 7079): JXcore Cordova bridge is ready!,
I/jxcore-log( 7079): 
W/jxcore-log( 7079): JXcore engine is started,
I/Choreographer( 7079): Skipped 93 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7079): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 7079): Toggling radios to true,
I/jxcore-log( 7079): 
,D/BluetoothAdapter( 7079): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  966): ADD_CLIENT: 8,
,D/WifiService(  966): New client listening to asynchronous messages,
D/WifiManager( 7079): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  966): setWifiEnabled: true pid=7079, uid=10366
W/Settings:Agent(  966): MONITOR_LOG
E/WifiService(  966): Invoking mWifiStateMachine.setWifiEnabled,
W/Settings:Agent(  966): name: wifi_on
I/WifiService(  966): isSprintWifiRestricted(): false
W/Settings:Agent(  966): value: 2
I/WifiService(  966): isMdmWifiRestricted(): false
W/Settings:Agent(  966): >> traceCallingStack()
W/Settings:Agent(  966): Process.myPid(): 966
,W/Settings:Agent(  966): Process.myTid(): 1745
W/Settings:Agent(  966): Process.myUid(): 1000
W/Settings:Agent(  966): 
W/Settings:Agent(  966): 
W/System.err(  966): java.lang.Throwable: stack dump
,W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  966): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  966): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  966): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  966): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  966): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  966): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  966): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  966): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  966): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  966): 
W/Settings:Agent(  966): << traceCallingStack(): 11(ms)
,D/WifiController(  966): handleMessage: E msg.what=155656
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): handleMessage: X
D/WifiManager( 7079): disconnect: Base Package Name=com.test.thalitest, uid=10366
,E/WifiStateMachine(  966): handleMessage: E msg.what=131145
D/WifiManager( 7079): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState CMD_DISCONNECT 0 0
,E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/jxcore-log( 7079): Radios toggled
I/jxcore-log( 7079): 
D/wpa_supplicant( 1366): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1366): wlan0: Cancelling scan request
D/wpa_supplicant( 1366): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1366): TDLS: Tear down peers
D/wpa_supplicant( 1366): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 1366): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1366): wlan0: Deauthentication notification
D/wpa_supplicant( 1366): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1366): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1366): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1366): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1366): enter disconnect check
I/wpa_supplicant( 1366): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1366): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1366): wlan0: Ignore connection failure indication since interface has been put into disconnected state
,D/Tethering(  966): interfaceLinkStateChanged wlan0, false
D/Tethering(  966): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  966): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  966): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  966): TetherInterfaceSM: wlan0: enter UnavailableState
D/PMS     (  966): acquireWL(2e746a60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
D/UsbDeviceManager(  966): [USBNET] bCheckSuppFunc: cdc_network
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  966): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
,D/HTCRequest(  966): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  966): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  966): interfaceLinkStateChanged wlan0, false
D/Tethering(  966): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  966): interfaceStatusChanged wlan0, false
D/UsbnetService(  966): BroadcastReceiver::onReceive+
,D/UsbnetService(  966): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1366): TDLS: Remove peers on disassociation
D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
D/wpa_supplicant( 1366): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5581e75f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1366):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1366): wlan0: State: COMPLETED -> DISCONNECTED
,D/wpa_supplicant( 1366): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1366): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1366): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1366): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1366): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1366): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1366): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1366): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1366): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1366): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 1366): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1366): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1366): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1366): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1366): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1366): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1366): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1366): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 1366): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  966): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  966): handleMessage: new destination call exit/enter
E/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  966): invokeExitMethods: ConnectedState
E/WifiStateMachine(  966): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  966): release()
E/WifiStateMachine(  966): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  966): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  966): invokeExitMethods: L2ConnectedState
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  966): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  966): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  966): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  966): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
,D/WifiMonitor(  966): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  966): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  966): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  966): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1366): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1366): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1366): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1366): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1366): Power_Mode_Type mode = 0
I/wpa_supplicant( 1366): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1366): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1366): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  966): setDhcpActive: false
,D/PMS     (  966): releaseWL(2e746a60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  966): updateNetworkEnabledLocked()
V/NetworkPolicy(  966): updateNotificationsLocked()
D/WifiP2pService(  966): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 1941): Read error: ssl=0x55871cdfe0: I/O error during system call, Connection timed out
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  966): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  966): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  966): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  966): NetworkAgent != null
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  966): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/TetherSettings( 6313): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
V/NetworkPolicy(  966): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/        ( 6313): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6313): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6313): Cust_ConnectToPC   : spcsc>false
D/        ( 6313): Cust_ConnectToPC   : IPT>true
D/        ( 6313): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  966): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/Settings( 6313): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiDataStallTracker(  966): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  966): stopDataStallAlarm 
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
,D/libc    (  966): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/PMS     (  966): acquireWL(263abb19): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
E/WifiDataStallTracker(  966): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  966): autoRoamSetBSSID any key="NG700"WPA_PSK
D/ConnectivityService(  966): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiConfigStore(  966): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
V/NativeCrypto( 1941): SSL shutdown failed: ssl=0x55871cdfe0: I/O error during system call, Broken pipe
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1366): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/SmartNS_Utility( 6313): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6313): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/wpa_supplicant( 1366): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1366): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/SmartNS_NSReceiver( 6313): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=4
D/ConnectivityService(  966): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  966): invokeEnterMethods: DisconnectingState
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  966):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  966): Start Disconnecting Watchdog 1
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131146
E/WifiStateMachine(  966): processMsg: DisconnectingState
E/WifiStateMachine(  966):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  966):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ContextImpl( 6313): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1366): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1366): Fast associate: Old scan results
D/wpa_supplicant( 1366): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1366): wpa_supplicant_scan enter
D/wpa_supplicant( 1366): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1366): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1366): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1366): WPS:  * Version (hardcoded 0x10)
D/,wpa_supplicant( 1366): WPS:  * Request Type
D/wpa_supplicant( 1366): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1366): WPS:  * UUID-E
D/wpa_supplicant( 1366): WPS:  * Primary Device Type
D/wpa_supplicant( 1366): WPS:  * RF Bands (3)
D/wpa_supplicant( 1366): WPS:  * Association State
D/wpa_supplicant( 1366): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1366): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1366): WPS:  * Manufacturer
D/wpa_supplicant( 1366): WPS:  * Model Name
D/wpa_supplicant( 1366): WPS:  * Model Number
D/wpa_supplicant( 1366): WPS:  * Device Name
D/wpa_supplicant( 1366): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1366): P2P: * P2P IE header
D/wpa_supplicant( 1366): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1366): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1366): wlan0: Add radio work 'scan'@0x5581e78680
D/wpa_supplicant( 1366): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1366): wlan0: Starting radio work 'scan'@0x5581e78680 after 0.000105 second wait
D/wpa_supplicant( 1366): wlan0: nl80211: scan request
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1366): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1366): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1366): wlan0: nl80211: Scan trigger
D/PMS     (  966): releaseWL(263abb19): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1366): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1366): wlan0: Own scan request started a scan in 0.000291 seconds
I/wpa_supplicant( 1366): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  966): handleMessage: X
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  966): handleMessage: E msg.what=147460
E/WifiStateMachine(  966): processMsg: DisconnectingState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  966): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  966): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  966): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  966): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/WifiStateMachine(  966):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132369
E/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  966): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  966): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  966):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132369
,E/WifiStateMachine(  966): ConnectModeState: Network connection lost 
E/WifiStateMachine(  966): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  966): handleMessage: new destination call exit/enter
E/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  966): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  966): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  966): DisconnectedState call setCountryCode()
E/WifiStateMachine(  966):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1366): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1366): wlan0: Cancelling scan request
I/SmartNS_Utility( 6313): setISNotification
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): Validated
D/SmartNS_Utility( 6313): usb_cable_connect = 1
,D/SmartNS_Utility( 6313): usb_denied = 0
D/wpa_supplicant( 1366): wlan0: nl80211: sched_scan request
,I/SmartNS_PSService( 6313): usb notificaiton:true
,E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 6313): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 6313): usb_cable_connect = 1
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_Utility( 6313): usb_denied = 0
I/SmartNS_PSService( 6313): usb notificaiton:true
,E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1223): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 6313): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/wpa_supplicant( 1366): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1366): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1366): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1366): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1366): wlan0: nl80211: New scan results available
D/WifiP2pService(  966): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1366): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/WifiP2pService(  966): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1366): wlan0: Event SCAN_RESULTS (3) received
D/WifiP2pService(  966): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1366): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1366): wlan0: Scan completed in 0.050778 seconds
D/wpa_supplicant( 1366): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1366): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1366): BSS: last_scan_res_used=0/32
,D/wpa_supplicant( 1366): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1366): wlan0: Radio work 'scan'@0x5581e78680 done in 0.052423 seconds
D/wpa_supplicant( 1366): wlan0: No suitable network found
D/wpa_supplicant( 1366): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1366): wlan0: Cancelling sched scan
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor(  966): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1366): nl80211: Sched scan stop sent (ret=0)
D/WifiMonitor(  966): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ],
,D/wpa_supplicant( 1366): wlan0: Cancelling scan request
D/wpa_supplicant( 1366): p2p0: Updating scan results from sibling
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=38 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1366): nl80211: Received scan results (1 BSSes)
W/WifiMonitor(  966): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 1366): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1366): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1366): p2p0: BSS: Add new id 0 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 1366): BSS: last_scan_res_used=1/32
,D/wpa_supplicant( 1366): p2p0: New scan results available (own=0 ext=0)
I/wpa_supplicant( 1366): clear disabled list - type=1
D/wpa_supplicant( 1366): p2p0: No suitable network found
D/wpa_supplicant( 1366): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1366): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1366): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WifiMonitor(  966): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 0 38:f8:89:11:e9:11]
E/WifiMonitor(  966): WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  966): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131101
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  966):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  966): processMsg: DefaultState
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  966):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  966): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  966): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=147462
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=132421  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  966): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  966): processMsg: ConnectModeState
I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
E/WifiStateMachine(  966):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=132421  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  966): handleMessage: X
D/WifiNetworkAgent(  966): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  966): handleMessage: E msg.what=147462
E/WifiStateMachine(  966): processMsg: DisconnectedState
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  966):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=132422  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  966): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  966): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/RemoteViews( 1223): reapply : com.android.settings 1 36
E/WifiStateMachine(  966): NetworkAgent == null
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  966):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=132427  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=147461
E/WifiStateMachine(  966): processMsg: DisconnectedState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  966):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:182 bcn=0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:182 bcn=0
E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:182 bcn=0
E/WifiStateMachine(  966): processMsg: SupplicantStartedState
E/WifiStateMachine(  966):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:182 bcn=0
D/WifiStateMachine(  966): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1366): wlan0: Control interface command 'LIST_DONGLES'
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  966): [1,448,966,972,707 ms] noteScanEnd no scan source
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1366): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  966): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@35357329 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  966): NG7005g c0:ff:d4:d3:aa:4a rssi=-45 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  966): NG700 c0:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  966): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  966): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  966):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-56 freq=2462
E/WifiAutoJoinController (  966): ageScanResultsOut delay 40000 size 3 now 1448966972711
E/WifiAutoJoinController (  966): newSupplicantResults size=3 known=1 true
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1366): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  966): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  966): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  966): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  966): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  966): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  966): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-56,-127) num=(1,0)
E/WifiAutoJoinController (  966): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  966): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  966): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  966): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  966): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-56 freq=2462
D/HtcWifiControlRoamOffload: (  966): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  966): Done attemptAutoJoin status=3
E/WifiConfigStore(  966):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  966): handleMessage: X
D/WISPrService( 6313): >>>>>WISPrService start isConnected = true<<<<<
,E/WifiStateMachine(  966): handleMessage: E msg.what=131215
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-56 ;0 ,-127] any roam=0 rt=132440
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-56 ;0 ,-127] any roam=0 rt=132441
E/WifiStateMachine(  966): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  966): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  966): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
,D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
D/WifiService(  966): New client listening to asynchronous messages
E/WifiTrafficPoller(  966): ADD_CLIENT: 9
,D/ConnectivityService(  966): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  966):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  966):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  966): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  966): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  966): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  966): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): Disconnected - quitting
D/NetworkManagementService(  966): Removing idletimer
D/usbnet  (  966): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  966):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/usbnet  (  966): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524292
I/SecurityController( 1223): onLost 100
,D/PMS     (  966): acquireWL(2e51ddbf): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 966 1000 null
,D/CSLegacyTypeTracker(  966): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  966): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  966): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  966): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  966): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/ConnectivityService(  966): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  966): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  966): acquireWL(2b25cc8c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
,D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
V/NetworkPolicy(  966): ensureActiveMobilePolicyLocked()
,D/NetworkPolicy(  966): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
,V/NetworkPolicy(  966): updateNetworkEnabledLocked()
V/NetworkPolicy(  966): updateIfacesLocked()
D/PMS     (  966): releaseWL(2b25cc8c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1223): dataConnected: false/false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  966): updateNotificationsLocked()
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
E/WifiConfigStore(  966): Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
D/NetworkManagementService(  966): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
,D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1366): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
V/NetworkPolicy(  966): updateNetworkEnabledLocked()
E/WifiConfigStore(  966): will read network variables netId=0
V/NetworkPolicy(  966): updateNotificationsLocked()
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='priority'
,W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
,D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1366): Do not allow key_data field to be exposed
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
,D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  966): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  966):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  966): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1366): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1366): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1366): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  966): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1366): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1366): ENABLE_NETWORK (0)
D/wpa_supplicant( 1366): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1366): wlan0: Setting scan request: 0.000000 sec
,I/wpa_supplicant( 1366): wpa_supplicant_scan enter
D/wpa_supplicant( 1366): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1366): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1366): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1366): WPS:  * Request Type
D/wpa_supplicant( 1366): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1366): WPS:  * UUID-E
D/wpa_supplicant( 1366): WPS:  * Primary Device Type
D/wpa_supplicant( 1366): WPS:  * RF Bands (3)
D/wpa_supplicant( 1366): WPS:  * Association State
D/wpa_supplicant( 1366): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1366): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1366): WPS:  * Manufacturer
,D/wpa_supplicant( 1366): WPS:  * Model Name
D/wpa_supplicant( 1366): WPS:  * Model Number
D/wpa_supplicant( 1366): WPS:  * Device Name
D/wpa_supplicant( 1366): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1366): P2P: * P2P IE header
D/wpa_supplicant( 1366): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1366): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1366): wlan0: Add radio work 'scan'@0x5581e58aa0
D/wpa_supplicant( 1366): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1366): wlan0: Starting radio work 'scan'@0x5581e58aa0 after 0.000029 second wait
D/wpa_supplicant( 1366): wlan0: nl80211: scan request
D/wpa_supplicant( 1366): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1366): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1366): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1366): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1366): wlan0: Own scan request started a scan in 0.000070 seconds
I/wpa_supplicant( 1366): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  966): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  966): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1366): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  966): will read network variables netId=0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 na,me='wep_key2'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1366): Do not allow key_data field to be exposed
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1366): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1366): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  966): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  966):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1366): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1366): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1366): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1366): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1366): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1366): wpa_supplicant_scan enter
D/wpa_supplicant( 1366): wlan0: Already scanning - Reschedule the incoming scan req
D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
D/wpa_supplicant( 1366): wlan0: Setting scan request: 1.000000 sec
D/FlexNetS( 6922): updateSvcAllowedInSettings:false
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1366): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  966): setLastSelectedConfiguration -1
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
E/WifiStateMachine(  966): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  966): handleMessage: new destination call exit/enter
E/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  966): invokeExitMethods: DisconnectedState
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1366): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  966): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  966): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  966): DisconnectedState call setCountryCode()
E/WifiStateMachine(  966):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1366): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1366): wlan0: Cancelling scan request
D/wpa_supplicant( 1366): wlan0: nl80211: sched_scan request
I/ActivityManager(  966): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=7140 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/FlexNetS( 6922): updateSvcAllowedInSettings:false
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1366): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
,D/wpa_supplicant( 1366): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1366): wlan0: nl80211: Sched scan started
D/WifiP2pService(  966): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1366): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/WifiP2pService(  966): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1366): wlan0: nl80211: New scan results available
D/WifiP2pService(  966): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1366): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/wpa_supplicant( 1366): wlan0: Event SCAN_RESULTS (3) received
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/wpa_supplicant( 1366): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1366): wlan0: Scan completed in 0.039365 seconds
D/wpa_supplicant( 1366): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1366): wlan0: BSS: Start scan result update 7
E/WifiStateMachine(  966): handleMessage: X
D/wpa_supplicant( 1366): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
D/WIFI    (  966): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1366): wlan0: BSS: Remove id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/wpa_supplicant( 1366): BSS: last_scan_res_used=0/32
D/WIFI    (  966):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/wpa_supplicant( 1366): wlan0: New scan results available (own=1 ext=0)
D/WIFI    (  966): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/wpa_supplicant( 1366): wlan0: Radio work 'scan'@0x5581e58aa0 done in 0.040268 seconds
D/wpa_supplicant( 1366): wlan0: No suitable network found
D/wpa_supplicant( 1366): wlan0: Setting scan request: 15.000000 sec
E/WifiStateMachine(  966): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/wpa_supplicant( 1366): wlan0: Cancelling sched scan
E/WifiStateMachine(  966): handleMessage: E msg.what=131131
E/WifiStateMachine(  966): processMsg: DisconnectedState
D/wpa_supplicant( 1366): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1366): wlan0: Cancelling scan request
D/wpa_supplicant( 1366): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1366): nl80211: Received scan results (1 BSSes)
E/WifiStateMachine(  966):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  966): processMsg: ConnectModeState
I/wpa_supplicant( 1366): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1366): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1366): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1366): p2p0: New scan results available (own=0 ext=0)
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
I/wpa_supplicant( 1366): clear disabled list - type=1
D/wpa_supplicant( 1366): p2p0: No suitable network found
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 1366): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1366): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1366): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48
E/WifiStateMachine(  966):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  966): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  966): WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  966): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=147461
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:182 bcn=0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:182 bcn=0
E/WifiStateMachine(  966): processMsg: DriverStartedState
D/FlexNetS( 6922): updateSvcAllowedInSettings:false
E/WifiStateMachine(  966):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:182 bcn=0
E/WifiStateMachine(  966): processMsg: SupplicantStartedState
E/WifiStateMachine(  966):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:182 bcn=0
D/WifiStateMachine(  966): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1366): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  966): [1,448,966,972,806 ms] noteScanEnd no scan source
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1366): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  966): handleMessage: X
W/WISPrService( 6313): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6313): trigger connection
D/WISPrService( 6313): continue
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/FlexNetS( 6922): updateSvcAllowedInSettings:false
D/WISPrService( 6313): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6313): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6313): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6313): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6313): start DataConnection
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/libc    ( 6313): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6313): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 6313): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6313): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6313): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6313): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/FlexNetS( 6922): updateSvcAllowedInSettings:false
D/libc    ( 6313): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6313): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6313): [NET] android_getaddrinfo_proxy+
D/libc    ( 6313): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  401): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  401): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6313): [NET] android_getaddrinfo_proxy-, NODATA
,D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/FlexNetS( 6922): updateSvcAllowedInSettings:false
,D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6922): updateSvcAllowedInSettings:false
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/libc    ( 6313): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6313): [NET] android_getaddrinfofornet-, err=8
D/FlexNetS( 6922): updateSvcAllowedInSettings:false
,D/WISPrService( 6313): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/FlexNetS( 6922): updateSvcAllowedInSettings:false
,D/FlexNetS( 6922): updateSvcAllowedInSettings:false
,D/FlexNetS( 6922): updateSvcAllowedInSettings:false
,D/FlexNetS( 6922): updateSvcAllowedInSettings:false
,D/FlexNetS( 6922): updateSvcAllowedInSettings:false
,D/FlexNetS( 6922): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 7140): [62c.2.]  listen tmrbb8,
,D/FlexNetS( 6922): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6995): remove item 101 (p2d27in218) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 7140): [62c.2.] summary 118:p2 ignore
,D/Process (  966): killProcessQuiet, pid=6564
I/ActivityManager(  966): Killing 6564:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 6564,
,D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/jxcore-log( 7079): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 7079): 
I/jxcore-log( 7079): my name is : HTC-HTC One M8s_PT4774
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): attempting to connect to test coordinator,
I/jxcore-log( 7079): 
I/jxcore-log( 7079): check test folder
I/jxcore-log( 7079): 
I/jxcore-log( 7079): found test : ./testFindPeers.js
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): found test : ./testReConnect.js
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): found test : ./testSendData.js,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): Test app app.js loaded,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/Choreographer( 7079): Skipped 144 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7079): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/GpsLocationProvider(  966): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  966): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  966): acquireWL(1f3fb451): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 966 1000 null
D/GpsLocationProvider(  966): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  966): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  966): [AlarmQueuing] connectivity wifi: false
,D/htcCheckinService(  966): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  966): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1518): [onReceive] WIFI(1): DISCONNECTED
,I/ActivityManager(  966): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7171 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  966): No APN found to select.
,D/PMS     (  966): releaseWL(1f3fb451): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 7140): [99a.1.]  listen tmrbb8,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,D/MdScDataSum( 7140): [99a.1.] summary 118:p1 ignore
,I/MusicStore( 7171): Database version: 120,
,D/VoldConnector(  966): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 7171): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  966): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 7171): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  966): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 7171): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 7171): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7171): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7171): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 7171): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 7171): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d41334c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7171): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7171): GMSCore installation verified
,I/ConfigStore( 7171): Config Database version: 1,
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=7171, uid=10159, userID:0,
,D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
,D/MediaRouterService(  966): Client com.google.android.music (pid 7171): Registered,
,D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
,I/MediaRouter( 7171): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 7171): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AutoSetting( 1590): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=7171, uid=10159, userID:0,
,D/AutoSetting( 1590): Util - no network available!
D/MobileConnectivityChangeReceiver( 6805): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6805): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1590): service - onCreate()
,I/GHttpClientFactory( 7171): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1590): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  966): request 288c5301 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  966): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1590): service - mHandler: cancel location update,
D/AutoSetting( 1590): service -           changes count: 0,
,I/GoogleURLConnFactory( 7171): Using platform SSLCertificateSocketFactory
,I/iu.Environment( 4696): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 4696): num queued entries: 0
,I/iu.UploadsManager( 4696): num updated entries: 0
,I/iu.SyncManager( 4696): NEXT; no task
,D/ChimeraCfgMgr( 4696): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  966): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7213 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/Babel   ( 6853): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  966): Killing 6760:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  966): killProcessQuiet, pid=6760
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 6760
,D/VoldConnector(  966): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 7213): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  966): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 7213): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7213): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 7213):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7213):   adb logcat -s GAv4
,D/VoldConnector(  966): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 7213): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  966): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 7213): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7213): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 7213): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 7213): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 7213): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7213): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 7213): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 7213): Time to load native libraries: 1 ms (timestamps 6989-6990),
,I/LibraryLoader( 7213): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7213): Binding Chromium to main looper Looper (main, tid 1) {2d6eed9f}
,I/LibraryLoader( 7213): Expected native library version number "",actual native library version number ""
,I/chromium( 7213): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 7213): Initializing chromium process, singleProcess=true
,W/art     ( 7213): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7213): ApplicationContext is null in ApplicationStatus
,W/chromium( 7213): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7213): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7213): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7213): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7213): Local Branch: 
I/Adreno-EGL( 7213): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7213): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7213):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 7213): Requires BLUETOOTH permission
,I/NSApplication( 7213): Starting up...
,I/ActivityManager(  966): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7271 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  966): killProcessQuiet, pid=6831
I/ActivityManager(  966): Killing 6831:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiStateMachine(  966): handleMessage: E msg.what=131168
E/WifiStateMachine(  966): processMsg: DisconnectedState,
E/WifiStateMachine(  966):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  966): processMsg: SupplicantStartedState
E/WifiStateMachine(  966):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  966): handleMessage: X
,I/ActivityManager(  966): Recipient 6831
,I/art     (  966): Explicit concurrent mark sweep GC freed 38278(2037KB) AllocSpace objects, 2(328KB) LOS objects, 33% free, 16MB/25MB, paused 2.047ms total 173.117ms,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/Process (  966): killProcessQuiet, pid=6337
I/ActivityManager(  966): Killing 6337:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  966): Recipient 6337,
,D/BluetoothAdapter( 7079): 947584708: getState(). Returning 12,
,I/jxcore-log( 7079): BLE supported!!
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(2e3afe7b): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7171 10159 null,
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7171, uid=10159, userID:0
,D/PMS     (  966): releaseWL(2e3afe7b): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 7171): Conditions not met for autocaching. okToAttempt=false,
I/MusicLeanback( 7171): Stop autocaching.
,D/WearableService( 5496): callingUid 10024, callindPid: 5496
,E/GmsUtils( 7171): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7171): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  966): acquireWL(3bc5f5ba): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{10024},
,V/AlarmManager(  966): sending alarm PendingIntent{c047c6b: PendingIntentRecord{2193c3c8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=141991, Int=0,
D/PMS     (  966): acquireWL(6417c61): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/PMS     (  966): releaseWL(3bc5f5ba): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
D/libc    ( 1941): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1941): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1941): [NET] android_getaddrinfo_proxy+
D/libc    ( 1941): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  401): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  401): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1941): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  966): releaseWL(6417c61): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  966): acquireWL(31cdb386): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{10024},
V/AlarmManager(  966): sending alarm PendingIntent{ec7447: PendingIntentRecord{26055474 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144910, Int=0
,D/PMS     (  966): releaseWL(31cdb386): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/GpsLocationProvider(  966): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  966): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,D/ContactMessageStore( 1468): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1468): MSG_NOTIFY_CS_TO_SYNC <<
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1590): service - handleMessage() stop self
,D/AutoSetting( 1590): service - handleMessage() quit looper
D/AutoSetting( 1590): service - onDestroy() END
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(15b87d9d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(15b87d9d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PMS     (  966): runPSCheck
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1468): switchBindHtcMsgCursor: null
,D/PMS     (  966): acquireWL(3a418212): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000},
V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=159725, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{2f720de3: PendingIntentRecord{145d43e0 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1448967013024, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{3cb1ad5e: PendingIntentRecord{2f2da53f com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192082, Int=0,
D/PMS     (  966): acquireWL(c82be0c): PARTIAL_WAKE_LOCK  *backup* 0x1 966 1000 null
,D/PMS     (  966): acquireWL(32dac355): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms},
,W/BackupManagerService(  966): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  966): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  966): releaseWL(c82be0c): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/PMS     (  966): releaseWL(32dac355): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/WeatherUtility( 1223): Weather sync is On
,D/PMS     (  966): releaseWL(3a418212): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  966): releaseWL(2e51ddbf): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  966): Failed to find a new network - expiring NetTransition Wakelock
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(17d13fd1): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{12300a36: PendingIntentRecord{3d54fd37 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=209173, Int=0
,D/PMS     (  966): releaseWL(17d13fd1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1590): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3a8dd8aa
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
I/ActivityManager(  966): Killing 6255:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=6255
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 6255
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(11e0c2a4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null,
I/BatteryService(  966): n_update end
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): releaseWL(11e0c2a4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  966): handleMessage: E msg.what=155652
D/HtcPowerSaver(  966): updateBatteryInfo
,D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/PMS     (  966): runPSCheck
D/WifiController(  966): processMsg: DefaultState
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): handleMessage: X
I/HtcPowerSaver(  966): >> updateStatus
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(6d9080d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  966): n_update end
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
D/PMS     (  966): releaseWL(6d9080d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): updateBatteryInfo
D/WifiController(  966): handleMessage: E msg.what=155652
D/PMS     (  966): runPSCheck
D/WifiController(  966): processMsg: DeviceActiveState
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): processMsg: StaEnabledState
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: X
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/wpa_supplicant( 1366): p2p0: BSS: Remove id 0 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  966): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 0 38:f8:89:11:e9:11]
E/WifiMonitor(  966): WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 38:f8:89:11:e9:11
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(11ea93c2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
,V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=219725, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{eb96510: PendingIntentRecord{3c1b1809 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1448967182073, Int=0
,D/PMS     (  966): releaseWL(11ea93c2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  966): acquireWL(38d22a0e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
,I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(38d22a0e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  966): updateBatteryInfo
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/PMS     (  966): runPSCheck
D/HtcPowerSaver(  966): Checking...
I/HtcPowerSaver(  966): >> updateStatus
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
,D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  966): acquireWL(f205c2f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=399724, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{837c23c: PendingIntentRecord{2f2da53f com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=512890, Int=0
,D/PMS     (  966): acquireWL(33542bc5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(33542bc5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(f205c2f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  966): acquireWL(1f8ad91a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(1f8ad91a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  966): processMsg: DefaultState
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: X
I/HtcPowerSaver(  966): << updateStatus
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,E/PNP_UPDATERD(  389): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/ContactMessageStore( 1468): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1468): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1468): sku_id=118
D/ContactMessageStore( 1468): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1468): start background delete task...
,D/ContactMessageStore( 1468): size: 0 , 0,
D/ContactMessageStore( 1468): Background delete complete
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(608c4b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(608c4b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): processMsg: DeviceActiveState
I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(20dcc628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null,
I/BatteryService(  966): n_update end
,D/PMS     (  966): releaseWL(20dcc628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): runPSCheck
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  966): Checking...
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  966): >> updateStatus
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  966): << updateStatus
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/NotificationService(  966): plugged=true pluggin=true
,D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(2d50bf41): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(2d50bf41): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
,D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  966): battery changed pluggedType: 2
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  966): acquireWL(12ed6ce6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=519725, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{3629cbf0: PendingIntentRecord{378f2569 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804892, Int=0
,I/ActivityManager(  966): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7313 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  966): sending alarm PendingIntent{629a227: PendingIntentRecord{204c1cd4 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1448967440492, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{11290e7d: PendingIntentRecord{2937172 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448967600000, Int=86400000
,I/ActivityManager(  966): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=7326 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  966): sending alarm PendingIntent{358439c3: PendingIntentRecord{2b83240 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,D/PMS     (  966): releaseWL(12ed6ce6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/art     (  445): Explicit concurrent mark sweep GC freed 8646(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 438us total 38.289ms
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/art     (  445): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 163us total 23.139ms,
,I/art     (  445): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 274us total 22.342ms
,I/ImageRamCache( 7326): create image Cache, size: 31457280.
I/ImageRamCache( 7326): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 7326): create image Cache, size: 31457280.
,I/FeedSettings( 7326): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 7326): GroupBudget 0.500000 0.380000
,I/FeedSettings( 7326): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 7326): changeLocale(): en_GB
,E/cutils-trace( 7359): Error opening trace file: Permission denied (13)
I/dex2oat ( 7359): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7359): dex2oat: override thread count:4
I/Prism.AllAppsOptionsMa_( 7326): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 7326): loadGridSize() with Alternative
,D/Process (  966): killProcessQuiet, pid=6884
I/ActivityManager(  966): Killing 6884:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/ActivityManager(  966): Recipient 6884
,I/dex2oat ( 7359): dex2oat took 655.506ms (threads: 4),
,I/PushClient( 7313): ApplicationMonitor {3b987ce2}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 7313): ApplicationMonitor {3b987ce2}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 7313): ApplicationMonitor {3b987ce2}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7313): ApplicationMonitor {3b987ce2}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7313): ApplicationMonitor {3b987ce2}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7313): ApplicationMonitor {3b987ce2}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7313): ApplicationMonitor {3b987ce2}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7313): ApplicationMonitor {3b987ce2}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7313): ApplicationMonitor {3b987ce2}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7313): PnsModel {159661ad}: update(): Update registration caused by: alarm
,I/PushClient( 7313): PnsConfigModel {2a084848}: <init>(): Use dm-client for provisioning.
,W/System.err( 7313): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 7313): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7313): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7313): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  966): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7369 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7369): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7369 dbg=false s=true
,I/DeviceManagement( 7369): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 7369): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7369): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 7369): WorkflowService: Starting workflow service
,I/DeviceManagement( 7369): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@159661ad] args=[Bundle[mParcelledData.dataSize=88]]
I/DeviceManagement( 7369): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7369): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7369): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7369): SessionStateController: Checking invariants...
,I/DeviceManagement( 7369): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7369): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7369): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7369): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@159661ad],
,I/DeviceManagement( 7369): WorkflowService: Stopping workflow service
,I/ActivityManager(  966): Killing 6953:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
,D/Process (  966): killProcessQuiet, pid=6953
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 6953,
D/WifiService(  966): Client connection lost with reason: 4
,I/PushClient( 7313): PnsModel {159661ad}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  966): killProcessQuiet, pid=7034
I/ActivityManager(  966): Killing 7034:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 7034
,W/SQLiteConnectionPool( 7326): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(e420c2b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=939725, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{6167888: PendingIntentRecord{317af221 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=942012, Int=0
,I/bt-btm  ( 3332): Received oneshot timer event complete
I/bt-btm  ( 3332): btm_ble_timeout
I/bt-btm  ( 3332): btm_gen_resolvable_private_addr
,D/PMS     (  966): acquireWL(2da55646): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3332 1002 null
,D/bt-btm  ( 3332): btm_ble_rand_enc_complete,
I/bt-btm  ( 3332): btm_gen_resolve_paddr_low
D/bt-smp  ( 3332): smp_encrypt_data
W/bt-smp  ( 3332): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 ,
W/bt-smp  ( 3332): Plain text(LSB ~ MSB) = 4c 04 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3332): Encrypted text(LSB ~ MSB) = 2a 53 ea 6f 5a 48 24 fc f6 af 29 21 e7 4f 6f 82 
I/bt-btm  ( 3332): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3332): Stopping oneshot timer
D/bt-btm  ( 3332): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  966): releaseWL(e420c2b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  966): releaseWL(2da55646): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(fd34007): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null,
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(fd34007): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
,D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: DefaultState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  966): handleMessage: X
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(26de9534): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000},
V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=999725, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{38738f5d: PendingIntentRecord{3dd090d2 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448967855381, Int=0
,I/ActivityManager(  966): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=7396 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/SmartSyncUtils( 7396): isEpsOn(), nState = 0,
,D/PMS     (  966): releaseWL(26de9534): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
I/ActivityManager(  966): Killing 6313:com.android.settings/1000 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=6313
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/PMS     (  966): acquireWL(3259d5a3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7396 1000 null
,D/PMS     (  966): releaseWL(3259d5a3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  966): acquireWL(2e69d0a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7396 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 7396): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 7396): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 7396): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 7396): SettingOnTime = 1449036000000, randomSettingOnTime = 1449035066000
D/SmartSyncScreenOnOffTimeReceiver( 7396): SettingOffTime = 1449014400000, randomSettingOffTime = 1449014658000,
,D/SmartSyncScreenOnOffTimeReceiver( 7396): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 7396): bNightMode = true,
D/SmartSyncScreenOnOffTimeReceiver( 7396): bNightModeTurnOffOnce = false
,I/ActivityManager(  966): Recipient 6313
D/WifiService(  966): Client connection lost with reason: 4
,D/PMS     (  966): releaseWL(2e69d0a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(3c5ec459): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null,
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(3c5ec459): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  966): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): runPSCheck,
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
,D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive+
,I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): << updateStatus
,D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): acquireWL(a02e81e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
D/UsbnetService(  966): onReceive BATTERY_CHANGED
I/BatteryService(  966): n_update end
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  966): releaseWL(a02e81e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/NotificationService(  966): plugged=true pluggin=true
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: DeviceActiveState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  966): processMsg: StaEnabledState
D/HtcPowerSaver(  966): updateBatteryInfo
D/WifiController(  966): processMsg: DefaultState
D/PMS     (  966): runPSCheck
D/WifiController(  966): handleMessage: X
D/HtcPowerSaver(  966): Checking...
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  966): >> updateStatus
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,E/PNP_UPDATERD(  389): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/UsageStatsService(  966): User[0] Flushing usage stats to disk,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): ,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(b2a28ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
,I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(b2a28ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(dab56cc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1059724, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{342e4d15: PendingIntentRecord{671682a com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448968171049, Int=1800000
,V/AlarmManager(  966): sending alarm PendingIntent{682561b: PendingIntentRecord{1b021b3 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448967808736, Int=0
,D/PMS     (  966): acquireWL(2f9d13b8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4696 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/ContextImpl( 7396): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  966): releaseWL(dab56cc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  966): acquireWL(c6638f7): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4696 10024 WorkSource{10024 com.google.android.gms},
,D/PowerUsageList:PowerUsageHelper( 7396): MY_DEBUG = false
D/PMS     (  966): releaseWL(2f9d13b8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms},
,D/PowerUsageService( 7396): repeat time = 1448969071112,
,I/EventLogService( 4696): Aggregate from 1448966942576 (log), 1448966371007 (data),
,D/PMS     (  966): releaseWL(c6638f7): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 7396): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 7396): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 7396): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 7396): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 7396): calcPower(), no data
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  966): acquireWL(173b6d93): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
I/BatteryService(  966): n_update end
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): releaseWL(173b6d93): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/NotificationService(  966): plugged=true pluggin=true
,D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: E msg.what=155652
D/PMS     (  966): runPSCheck
D/WifiController(  966): processMsg: DeviceActiveState
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): processMsg: StaEnabledState
,I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): handleMessage: X
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): acquireWL(1262a1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  966): n_update end
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): releaseWL(1262a1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: E msg.what=155652
D/PMS     (  966): runPSCheck
D/WifiController(  966): processMsg: DeviceActiveState
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): processMsg: StaEnabledState
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): handleMessage: X
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  966): << updateStatus
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(182c75c9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(182c75c9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): acquireWL(394794ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  966): n_update end
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): releaseWL(394794ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  966): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  966): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  966): runPSCheck
D/WifiController(  966): handleMessage: E msg.what=155652
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): processMsg: DeviceActiveState
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,E/PNP_UPDATERD(  389): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(28180afc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000},
V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1359725, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{3629cbf0: PendingIntentRecord{378f2569 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1620101, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{207da585: PendingIntentRecord{27cc2fda android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1719730, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{3f0e2035: PendingIntentRecord{4d20cca android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1824831, Int=1800000
,I/ProcessStatsService(  966): Prepared write state in 26ms
,D/HtcSystemUPManager(  966): AlarmScheduler_INEXACT [onReceive] end,
D/HtcSystemUPManager(  966): com.htc.upm.AlarmScheduler$SchedulerBase$1@34c7f7f6
,D/PMS     (  966): acquireWL(520fc0b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
,D/HtcSystemUPManager(  966): UPAlarmListener onAlarmArrival
D/HtcSystemUPManager(  966): UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1448968665156, last = 1448946960004, freq = 21600000
,D/PMS     (  966): releaseWL(520fc0b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  966): updateNetworkEnabledLocked()
V/NetworkPolicy(  966): updateNotificationsLocked()
D/PMS     (  966): releaseWL(28180afc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/HtcSystemUPManager(  966): HtcSystemUPHandler sendService() has been called
,D/HtcSystemUPManager(  966): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
D/HtcSystemUPManager(  966): HtcSystemUPHandler send to UPService takes: 2 ms,
,I/ProcessStatsService(  966): Pruning old procstats: /data/system/procstats/state-2015-11-30-11-49-18.bin
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(3758dae8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
,V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1839725, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{1af81501: PendingIntentRecord{11cd6fa6 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1842025, Int=0
I/bt-btm  ( 3332): Received oneshot timer event complete
I/bt-btm  ( 3332): btm_ble_timeout
I/bt-btm  ( 3332): btm_gen_resolvable_private_addr
,D/PMS     (  966): acquireWL(2ce14de7): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3332 1002 null
,D/bt-btm  ( 3332): btm_ble_rand_enc_complete,
,I/bt-btm  ( 3332): btm_gen_resolve_paddr_low
,D/PMS     (  966): releaseWL(3758dae8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/bt-smp  ( 3332): smp_encrypt_data
W/bt-smp  ( 3332): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3332): Plain text(LSB ~ MSB) = 35 38 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3332): Encrypted text(LSB ~ MSB) = 70 5b cd 0a 99 b9 09 68 55 c1 5b 51 f1 fa c2 d8 
I/bt-btm  ( 3332): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3332): Stopping oneshot timer
D/bt-btm  ( 3332): Starting oneshot timer type:103 timeout:900s
D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): releaseWL(2ce14de7): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,D/PMS     (  966): acquireWL(2954bd94): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(2954bd94): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive-
,D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: E msg.what=155652
D/PMS     (  966): runPSCheck
D/WifiController(  966): processMsg: DeviceActiveState
D/HtcPowerSaver(  966): Checking...
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  966): >> updateStatus
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  966): processMsg: StaEnabledState
D/HeadsetStateMachine( 3332): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,I/jxcore-log( 7079): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7079): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 7431): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7431): ====startRecUseTime====
D/htc.customization.log.level( 7431):  is 
W/CustomizationLogLevel( 7431): Level value is invalid, use default level 2
D/CustomizationManager( 7431):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 7431): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7431): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7431): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7431): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7431): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7431): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7431): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7431): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7431): Parsing tag category name = system
I/CustomizationCIDLoader( 7431): Parsing tag category name = application
I/CustomizationCIDLoader( 7431): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7431): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7431): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7431): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7431): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7431): add string-array item, value = 42507
I/CustomizationCIDLoader( 7431): add string-array item, value = 21902
I/CustomizationCIDLoader( 7431): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7431): add string-array item, value = 23420
I/CustomizationCIDLoader( 7431): add string-array item, value = 22299
I/CustomizationCIDLoader( 7431): add string-array item, value = 24002
I/CustomizationCIDLoader( 7431): add string-array item, value = 23210
I/CustomizationCIDLoader( 7431): add string-array item, value = 23205
I/CustomizationCIDLoader( 7431): add string-array item, value = 23806
I/CustomizationCIDLoader( 7431): add string-array item, value = 23430
I/CustomizationCIDLoader( 7431): add string-array item, value = 23408
I/CustomizationCIDLoader( 7431): add string-array item, value = 27205
I/CustomizationCIDLoader( 7431): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7431): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7431):  Read CID file spent 0.098 (s)
D/CustomizationManager( 7431):  All configurations done spent 0.098 (s)
D/PackageManager(  966): deletePackageAsUser: pkg=com.test.thalitest, pid=7431, uid=2000 userid=0
I/ActivityManager(  966): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  966): killProcessQuiet, pid=7079
I/ActivityManager(  966): Killing 7079:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  966): Skipping PackageSetting{51b2160 com.example.hello/10373} due to missing metadata
I/WindowState(  966): WIN DEATH: Window{d41cc7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/InputEventReceiver( 1390): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{d6bbe63 uid 10366 pid 7079} (c)'
D/WifiService(  966): Client connection lost with reason: 4
I/ActivityManager(  966): Recipient 7079
D/Process (  966): killProcessQuiet, pid=6406
I/ActivityManager(  966): Killing 6406:com.google.android.apps.plus/u0a167 (adj 13): empty for 1802s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  966): Recipient 6406
D/Process (  966): killProcessQuiet, pid=7271
I/ActivityManager(  966): Killing 7271:com.android.chrome/u0a96 (adj 13): empty for 1803s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  966): Recipient 7271
D/Process (  966): killProcessQuiet, pid=7213
I/ActivityManager(  966): Killing 7213:com.google.android.apps.magazines/u0a161 (adj 13): empty for 1804s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  966): Recipient 7213
D/Process (  966): killProcessQuiet, pid=6805
I/ActivityManager(  966): Killing 6805:com.google.android.setupwizard/u0a77 (adj 13): empty for 1804s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  966): Recipient 6805
D/Process (  966): killProcessQuiet, pid=6922
I/ActivityManager(  966): Killing 6922:com.htc.bgp/u0a11 (adj 13): empty for 1804s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  966): Recipient 6922
D/Process (  966): killProcessQuiet, pid=7140
I/ActivityManager(  966): Killing 7140:com.htc.mobiledata:remote/u0a46 (adj 15): empty for 1805s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  966): Recipient 7140
D/Process (  966): killProcessQuiet, pid=6995
I/ActivityManager(  966): Killing 6995:com.htc.mobiledata/u0a46 (adj 15): empty for 1805s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  966): Recipient 6995
I/ActivityManager(  966):   Force finishing activity ActivityRecord{3662ec00 u0 com.test.thalitest/.MainActivity t10}
I/ActivityManager(  966): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  966):   Force finishing activity ActivityRecord{3662ec00 u0 com.test.thalitest/.MainActivity t10 f}
W/ActivityManager(  966): Duplicate finish request for ActivityRecord{3662ec00 u0 com.test.thalitest/.MainActivity t10 f}
W/ActivityManager(  966): Spurious death for ProcessRecord{1f50003d 7079:com.test.thalitest/u0a366}, curProc for 7079: null
D/DotMatrix( 1327): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1327): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/SystemReader(  966): Cannot find grip_rejection_width, use default value instead
D/PMS     (  966): acquireWL(2c6ae183): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1834): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1754): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 7326): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 7326): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  966): releaseWL(2c6ae183): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1754): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/art     ( 1518): Explicit concurrent mark sweep GC freed 5877(287KB) AllocSpace objects, 8(716KB) LOS objects, 34% free, 29MB/45MB, paused 1.082ms total 94.328ms
I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1518): Deferring update until onResume
D/Launcher( 1518): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1518): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1590): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/VoicemailCleanupService( 1671): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1754): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PhoneApp( 1468): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1590): handle notify Blinkfeed plugin client changed
I/ActivityManager(  966): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7453 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/ExternalAccountType( 1754): Unsupported attribute readOnly
I/art     (  966): Explicit concurrent mark sweep GC freed 35215(2MB) AllocSpace objects, 13(1056KB) LOS objects, 33% free, 16MB/25MB, paused 1.729ms total 224.310ms
I/art     (  966): WaitForGcToComplete blocked for 165.739ms for cause Explicit
D/StatusBarManagerService(  966): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
D/StatusBarManagerService(  966): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ContextImpl( 7453): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  966): hiding MENU key
D/FindExtension( 1518): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1518): Defer allocateBuffers to drawing time
I/ActivityManager(  966): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7477 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/InputMethodManagerService(  966): Got RemoteException sending setActive(false) notification to pid 7079 uid 10366
D/StatusBarManagerService(  966): swetImeWindowStatus vis=0 backDisposition=0
D/Process (  966): killProcessQuiet, pid=7171
I/ActivityManager(  966): Killing 7171:com.google.android.music:main/u0a159 (adj 15): empty for 1801s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/PackageManager(  966): Unable to load service info ResolveInfo{10755beb com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  966): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  966): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  966): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  966): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  966): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  966): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  966): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  966): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/JobSchedulerService(  966): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  966): Explicit concurrent mark sweep GC freed 8771(554KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.582ms total 181.354ms
W/asset   (  966): Copying FileAsset 0x55879a74a0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/MediaRouterService(  966): Client com.google.android.music (pid 7171): Died!
I/ActivityManager(  966): Recipient 7171
D/TaskPersister(  966): removeObsoleteFile: deleting file=10_task.xml
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7477): -onCreate()
V/Settings:HtcSettingsApplication( 7477): [7477/7477] onCreate()
D/Process (  966): killProcessQuiet, pid=5496
I/ActivityManager(  966): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7506 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  966): Killing 5496:com.google.android.gms.wearable/u0a24 (adj 15): empty for 1801s
D/Settings:HtcWirelessFeatureFlags( 7477): id/is att sku: 118/false
E/Settings:HtcWrapHeaderInfo( 7477): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7477): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7477): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7477): isSupportMusicChannel(): false
I/ActivityManager(  966): Recipient 5496
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]support         :false
I/InputMethodManagerService(  966): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  966): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7477): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7477): isSupportVoWifi: null
W/ResourcesManager(  966): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7477): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7477): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7477): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7477): [supportHomeButton]support         :false
E/Settings:HtcVoWifiWidgetEnabler( 7477): isSupportVoWifi: null
I/ActivityManager(  966): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7477): Failed to find provider info for com.htc.vowifi
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7506, uid=10072, userID:0
W/global  ( 7506): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 7506): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 7506): [apache-http] Connection GC has been deprecated!
W/global  ( 7506): [apache-http] Connection GC has been deprecated!
E/RollingFileStream( 7506): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 7506): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  966): acquireWL(2d519002): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{2a74752a: PendingIntentRecord{17c4df1b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1899725, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{9271d13: PendingIntentRecord{20355b50 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1855189, Int=0
D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
I/ActivityManager(  966): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7545 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 7506): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7506): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 7506): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 7506): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7506): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7506): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7506): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 7506): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 7506): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 7506): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7506): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7506): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7506): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 7506): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 7506): Process: com.android.vending, PID: 7506
E/AndroidRuntime( 7506): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7506): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7506): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7506): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7506): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 7506): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 7506): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 7506): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 7506): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7506): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7506): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  966): App crashed! Process: com.android.vending
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7506, uid=10072, userID:0
E/SQLiteDatabase( 7506): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7506): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7506): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7506): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7506): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7506): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7506): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7506): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7506): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7506): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 7506): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 7506): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7506): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7506): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7506): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7506): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7506): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 7506): killProcess, pid=7506
E/DropBoxManagerService(  966): Can't write: system_app_crash
E/DropBoxManagerService(  966): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  966): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  966): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  966): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  966): 	... 5 more
E/AndroidRuntime_2_crash( 7506): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 7506): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 7506): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 7506): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 7506): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 7506): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 7506): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 7506): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 7506): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 7506): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 7506): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 7506): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 7506): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 7506): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 7506): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 7506): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 7506): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 7506): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 7506): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 7506): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 7506): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 7506): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 7506): 	... 4 more
W/ResourcesManager( 7545): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7545): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Process ( 7506): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
I/MultiDex( 7545): VM with version 2.1.0 has multidex support
I/MultiDex( 7545): install
I/MultiDex( 7545): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7545): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/Prism.ItemManager( 7326): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 7326): loadItems() com.htc.launcher.pageview.WidgetManager@ec63873 +
I/Prism.WidgetManager( 7326): onLoadItems() +
I/ActivityManager(  966): Recipient 7506
I/ActivityManager(  966): Process com.android.vending (pid 7506) has died
W/ActivityThread( 7545): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1518): loadItems() com.htc.launcher.pageview.WidgetManager@181a85c +
I/Prism.WidgetManager( 1518): onLoadItems() +
W/System  ( 7545): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2faa11f2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7545): Installed default security provider GmsCore_OpenSSL
E/SQLiteLog( 1941): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1941): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x5587118eb0
E/AndroidRuntime( 1941): FATAL EXCEPTION: main
E/AndroidRuntime( 1941): Process: com.google.process.gapps, PID: 1941
E/AndroidRuntime( 1941): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1941): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1941): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1941): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1941): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1941): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1941): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1941): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1941): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1941): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1941): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1941): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1941): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1941): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1941): 	... 9 more
E/ActivityManager(  966): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  966): Can't write: system_app_crash
E/DropBoxManagerService(  966): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  966): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  966): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  966): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  966): 	... 5 more
D/Process ( 1941): killProcess, pid=1941
D/Process ( 1941): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/ResourcesManager( 7326): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 1518): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/BulkCursor( 7545): Remote process exception when closing
I/ActivityManager(  966): Recipient 1941
I/ActivityManager(  966): Process com.google.process.gapps (pid 1941) has died
W/ActivityManager(  966): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
W/ActivityManager(  966): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
W/ActivityManager(  966): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
W/NativeLibraryUtils( 7545): Failed to open lock file
W/NativeLibraryUtils( 7545): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7545): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7545): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7545): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7545): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7545): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7545): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7545): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7545): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7545): 	... 3 more
W/ResourcesManager( 1518): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityThread( 7545): Removing dead content provider:android.content.ContentProviderProxy@2e8d06c0
W/ResourcesManager( 7326): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  966): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7577 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a

```
