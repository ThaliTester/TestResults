#### Test 56449660bb41d23_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2
,E/cutils-trace( 7030): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7030): ====startRecUseTime====
D/htc.customization.log.level( 7030):  is 
W/CustomizationLogLevel( 7030): Level value is invalid, use default level 2
D/CustomizationManager( 7030):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 7030): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7030): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7030): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7030): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7030): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7030): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7030): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7030): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7030): Parsing tag category name = system
I/CustomizationCIDLoader( 7030): Parsing tag category name = application
I/CustomizationCIDLoader( 7030): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7030): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7030): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7030): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7030): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7030): add string-array item, value = 42507
I/CustomizationCIDLoader( 7030): add string-array item, value = 21902
I/CustomizationCIDLoader( 7030): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7030): add string-array item, value = 23420
I/CustomizationCIDLoader( 7030): add string-array item, value = 22299
I/CustomizationCIDLoader( 7030): add string-array item, value = 24002
I/CustomizationCIDLoader( 7030): add string-array item, value = 23210
I/CustomizationCIDLoader( 7030): add string-array item, value = 23205
I/CustomizationCIDLoader( 7030): add string-array item, value = 23806
I/CustomizationCIDLoader( 7030): add string-array item, value = 23430
I/CustomizationCIDLoader( 7030): add string-array item, value = 23408
I/CustomizationCIDLoader( 7030): add string-array item, value = 27205
I/CustomizationCIDLoader( 7030): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7030): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7030):  Read CID file spent 0.108 (s)
D/CustomizationManager( 7030):  All configurations done spent 0.108 (s)
--------- beginning of system
D/PMS     (  960): acquireHCC(3a83b2bf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 960 1000 null
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7030 on display 0
D/PMS     (  960): acquireHCC(9437d8c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 960 1000 null
W/asset   (  960): Copying FileAsset 0x5596415e90 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7048 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1327): [EventService]  onDisplayChanged: 0
V/ActivityManager(  960): Display changed displayId=0
D/DotMatrix( 1327): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 7048): Copying FileAsset 0xab54df90 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1590): [trimMemory] 20
I/WebViewFactory( 7048): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 7048): Time to load native libraries: 9 ms (timestamps 1709-1718),
,I/LibraryLoader( 7048): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 7048): Binding Chromium to main looper Looper (main, tid 1) {3a166084},
I/LibraryLoader( 7048): Expected native library version number "",actual native library version number ""
,I/chromium( 7048): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 7048): Initializing chromium process, singleProcess=true,
,W/art     ( 7048): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 7048): ApplicationContext is null in ApplicationStatus,
,W/chromium( 7048): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 7048): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 7048): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7048): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7048): OpenGL ES Shader Compiler Version: E031.25.03.01,
I/Adreno-EGL( 7048): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7048): Local Branch: 
I/Adreno-EGL( 7048): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7048): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7048):                  d74aa161a12b9c6fc6332151
,W/System.err(  960): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a060c90:true
W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  960): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 7048): 254326377: getState(). Returning 12,
,W/art     ( 7048): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 7048): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 7048): CordovaWebView is running on device made by: HTC
,W/art     ( 7048): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7048): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
W/chromium( 7048): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  960): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  960): hiding MENU key
,D/StatusBarManagerService(  960): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  960): hiding MENU key
,D/FindExtension( 7048): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 7048): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@112a599e, mServedView=org.apache.cordova.engine.SystemWebView{248a7c7f VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@a1fe44c,
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/InputMethodManagerService(  960): Disable input method client, pid=1590
D/StatusBarManagerService(  960): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 7048): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +628ms (total +673ms)
,W/BindingManager( 7048): Cannot call determinedVisibility() - never saw a connection for the pid: 7048
,D/JsMessageQueue( 7048): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7048): JniHelper::setJavaVM(0xab4db8f8), pthread_self() = -1400737736,
,I/chromium( 7048): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 7048): Initializing JXcore engine,
W/jxcore-log( 7048): JXcore engine is ready
,W/jxcore-log( 7048): Starting JXcore engine,
,I/ActivityManager(  960): Killing 5947:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=5947
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 5947,
,D/PMS     (  960): releaseHCC(3a83b2bf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
,D/PMS     (  960): releaseHCC(9437d8c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 7048): Platform android,
W/jxcore-log( 7048): 
,W/jxcore-log( 7048): Process ARCH arm,
W/jxcore-log( 7048): 
,I/jxcore-log( 7048): JXcore Cordova bridge is ready!
I/jxcore-log( 7048): 
W/jxcore-log( 7048): JXcore engine is started,
,I/jxcore-log( 7048): Toggling radios to true
I/jxcore-log( 7048): 
,D/BluetoothAdapter( 7048): enable(): BT is already enabled..!
,D/WifiService(  960): New client listening to asynchronous messages
,E/WifiTrafficPoller(  960): ADD_CLIENT: 8
D/WifiManager( 7048): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366,
W/Settings:Agent(  960): MONITOR_LOG
D/WifiService(  960): setWifiEnabled: true pid=7048, uid=10366
W/Settings:Agent(  960): name: wifi_on
,E/WifiService(  960): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  960): value: 2
,I/WifiService(  960): isSprintWifiRestricted(): false
W/Settings:Agent(  960): >> traceCallingStack()
I/WifiService(  960): isMdmWifiRestricted(): false
W/Settings:Agent(  960): Process.myPid(): 960
W/Settings:Agent(  960): Process.myTid(): 3898
W/Settings:Agent(  960): Process.myUid(): 1000
W/Settings:Agent(  960): 
,W/Settings:Agent(  960): 
W/System.err(  960): java.lang.Throwable: stack dump
,W/System.err(  960): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  960): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  960): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  960): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  960): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  960): ,	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  960): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  960): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  960): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  960): 
W/Settings:Agent(  960): << traceCallingStack(): 19(ms)
D/WifiController(  960): handleMessage: E msg.what=155656
D/WifiManager( 7048): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131145
E/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiManager( 7048): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  960):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  960): processMsg: L2ConnectedState
E/WifiStateMachine(  960):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1329): wlan0: Control interface command 'DISCONNECT',
D/wpa_supplicant( 1329): wlan0: Cancelling scan request
D/wpa_supplicant( 1329): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1329): TDLS: Tear down peers
D/wpa_supplicant( 1329): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 7048): Radios toggled
I/jxcore-log( 7048): 
,I/jxcore-log( 7048): My device name is: HTC-HTC One M8s
I/jxcore-log( 7048): 
,D/wpa_supplicant( 1329): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1329): wlan0: Deauthentication notification
D/wpa_supplicant( 1329): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1329): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1329): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1329): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1329): enter disconnect check,
I/wpa_supplicant( 1329): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  960): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  960): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1329): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1329): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  960): interfaceLinkStateChanged wlan0, false
D/Tethering(  960): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  960): interfaceLinkStateChanged wlan0, false
D/Tethering(  960): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  960): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  960): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  960): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiMonitor(  960): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  960): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/PMS     (  960): acquireWL(e5dd9b5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 960 1000 null
D/UsbnetService(  960): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbDeviceManager(  960): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  960): BroadcastReceiver::onReceive-
,D/wpa_supplicant( 1329): TDLS: Remove peers on disassociation,
D/wpa_supplicant( 1329): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1329): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1329): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1329): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55b6de1f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1329):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1329): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1329): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1329): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1329): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1329): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1329): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1329): nl80211: Skip set_supp_port(unauthorized) while not associated
D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
D/wpa_supplicant( 1329): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1329): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1329): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1329): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 1329): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1329): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 1329): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1329): EAPOL: External notification - portValid=0
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1329): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1329): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1329): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/HTCRequest(  960): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  960): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/wpa_supplicant( 1329): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1329): nl80211: Ignore disconnect event triggered during reassociation
,E/WifiStateMachine(  960): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  960): handleMessage: new destination call exit/enter
E/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  960): invokeExitMethods: ConnectedState
E/WifiStateMachine(  960): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  960): release()
E/WifiStateMachine(  960): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  960): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  960): invokeExitMethods: L2ConnectedState
D/HTCRequest(  960): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  960): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
D/WifiMonitor(  960): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  960): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  960): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  960): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1329): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1329): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1329): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/WifiP2pService(  960): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1329): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiP2pService(  960): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1329): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1329): Power_Mode_Type mode = 0
I/wpa_supplicant( 1329): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,D/wpa_supplicant( 1329): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1329): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  960): setDhcpActive: false
V/NativeCrypto( 1840): Read error: ssl=0x5595b3f1f0: I/O error during system call, Connection timed out
D/libc    (  960): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  960): acquireWL(d49084a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/libc    (  960): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  960): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  960): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  960): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  960): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
V/NetworkPolicy(  960): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  960): NetworkAgent != null
D/ConnectivityService(  960): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  960): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  960): ignoring duplicate network state non-change
E/WifiTrafficPoller(  960): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/libc    (  960): [NET] android_getaddrinfofornet-, SUCCESS
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/TetherSettings( 6296): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/ConnectivityService(  960): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/        ( 6296): Cust_ConnectToPC   : Internet_Sharing>true
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/        ( 6296): Cust_ConnectToPC   : Modem_Link>false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/        ( 6296): Cust_ConnectToPC   : spcsc>false
D/PMS     (  960): releaseWL(d49084a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/        ( 6296): Cust_ConnectToPC   : IPT>true
D/        ( 6296): Cust_ConnectToPC   : Singel_USB>false
D/libc    (  960): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  960): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  960): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NativeCrypto( 1840): SSL shutdown failed: ssl=0x5595b3f1f0: I/O error during system call, Broken pipe
W/Settings( 6296): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  960): autoRoamSetBSSID any key="NG700"WPA_PSK
,E/WifiConfigStore(  960): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  960): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1329): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1329): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  960): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  960): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  960): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1329): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  960): Validated
D/wpa_supplicant( 1329): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  960): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  960):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  960): Start Disconnecting Watchdog 1
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131146
E/WifiStateMachine(  960): processMsg: DisconnectingState
E/WifiStateMachine(  960):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1329): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1329): Fast associate: Old scan results
D/wpa_supplicant( 1329): wlan0: Setting scan request: 0.000000 sec
D/ConnectivityService(  960): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/wpa_supplicant( 1329): wpa_supplicant_scan enter
D/wpa_supplicant( 1329): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1329): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1329): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1329): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1329): WPS:  * Request Type
D/wpa_supplicant( 1329): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1329): WPS:  * UUID-E
D/wpa_supplicant( 1329): WPS:  * Primary Device Type
D/wpa_supplicant( 1329): WPS:  * RF Bands (3)
D/wpa_supplicant( 1329): WPS:  * Association State
D/wpa_supplicant( 1329): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1329): WPS:  * Device Password ID (0)
D/PMS     (  960): releaseWL(e5dd9b5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1329): WPS:  * Manufacturer
D/wpa_supplicant( 1329): WPS:  * Model Name
D/wpa_supplicant( 1329): WPS:  * Model Number
D/wpa_supplicant( 1329): WPS:  * Device Name
D/wpa_supplicant( 1329): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1329): P2P: * P2P IE header
D/wpa_supplicant( 1329): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1329): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1329): wlan0: Add radio work 'scan'@0x55b6de4680
D/wpa_supplicant( 1329): wlan0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1329): wlan0: Starting radio work 'scan'@0x55b6de4680 after 0.000077 second wait
D/wpa_supplicant( 1329): wlan0: nl80211: scan request
D/wpa_supplicant( 1329): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1329): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1329): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1329): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1329): wlan0: Own scan request started a scan in 0.000163 seconds
I/wpa_supplicant( 1329): wlan0: CTRL-EVENT-SCAN-STARTED 
V/NetworkPolicy(  960): updateNetworkEnabledLocked()
E/WifiStateMachine(  960): handleMessage: X
V/NetworkPolicy(  960): updateNotificationsLocked()
E/WifiStateMachine(  960): handleMessage: E msg.what=147460
E/WifiStateMachine(  960): processMsg: DisconnectingState
D/WifiDataStallTracker(  960): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/WifiStateMachine(  960):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=141822
D/WifiDataStallTracker(  960): stopDataStallAlarm 
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=141823
E/WifiStateMachine(  960): ConnectModeState: Network connection lost 
E/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  960): handleMessage: new destination call exit/enter
W/ContextImpl( 6296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  960): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  960): DisconnectedState call setCountryCode()
E/WifiStateMachine(  960):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1329): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1329): wlan0: Cancelling scan request
E/WifiTrafficPoller(  960): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  960): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiTrafficPoller(  960): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/HTCRequest(  960): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/HTCRequest(  960): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  960): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  960): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  960): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  960): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/wpa_supplicant( 1329): wlan0: nl80211: sched_scan request
E/SmartNS_Utility( 6296): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6296): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6296): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
I/SmartNS_Utility( 6296): setISNotification
D/SmartNS_Utility( 6296): usb_cable_connect = 1
D/SmartNS_Utility( 6296): usb_denied = 0
I/SmartNS_PSService( 6296): usb notificaiton:true
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
I/ActionCombine( 6296): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/SmartNS_Utility( 6296): usb_cable_connect = 1
D/SmartNS_Utility( 6296): usb_denied = 0
I/SmartNS_PSService( 6296): usb notificaiton:true
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1329): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
D/wpa_supplicant( 1329): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1329): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1329): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1329): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1329): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1329): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1329): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1329): wlan0: Scan completed in 0.039253 seconds
D/wpa_supplicant( 1329): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1329): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1329): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1329): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1329): wlan0: Radio work 'scan'@0x55b6de4680 done in 0.040668 seconds
D/wpa_supplicant( 1329): wlan0: No suitable network found
D/wpa_supplicant( 1329): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1329): wlan0: Cancelling sched scan
D/wpa_supplicant( 1329): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1329): wlan0: Cancelling scan request
D/wpa_supplicant( 1329): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1329): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1329): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1329): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1329): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1329): p2p0: No suitable network found
D/wpa_supplicant( 1329): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1329): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1329): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131101
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  960): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=40 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  960): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine(  960):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor(  960): WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiMonitor(  960): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  960):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
E/WifiStateMachine(  960):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  960): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  960): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=147462
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=141865  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiP2pService(  960): InactiveState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  960): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/WifiP2pService(  960): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiP2pService(  960): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  960): processMsg: ConnectModeState
D/SmartNS_NSReceiver( 6296): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  960):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=141865  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131212
E/WifiStateMachine(  960): processMsg: DisconnectedState
I/RemoteViews( 1221): reapply : com.android.settings 2 36
E/WifiStateMachine(  960):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
E/WifiStateMachine(  960):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  960): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  960): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131212
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
E/WifiStateMachine(  960):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  960): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  960): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  960): handleMessage: X
D/WifiNetworkAgent(  960): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  960): handleMessage: E msg.what=147462
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=141878  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  960): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  960): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  960): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  960): NetworkAgent == null
E/WifiStateMachine(  960): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiTrafficPoller(  960): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  960):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=141883  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=147461
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:88 bcn=0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiTrafficPoller(  960): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  960):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:88 bcn=0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:88 bcn=0
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:88 bcn=0
D/WifiStateMachine(  960): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1329): wlan0: Control interface command 'LIST_DONGLES'
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  960): [1,453,390,913,431 ms] noteScanEnd no scan source
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1329): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  960): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@109f099c sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  960): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  960): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  960): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  960): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  960):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  960): Gonzos 38:f8:89:11:e9:11 rssi=-91 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  960): UPC503894600 a0:c5:62:7a:49:97 rssi=-82 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiAutoJoinController (  960): ageScanResultsOut delay 40000 size 4 now 1453390913434
E/WifiAutoJoinController (  960): newSupplicantResults size=4 known=1 true
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1329): wlan0: Control interface command 'STATUS-NO_EVENTS'
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
I/RemoteViews( 1221): reapply : com.android.settings 1 36
E/WifiAutoJoinController (  960): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  960): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  960): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  960): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  960): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  960): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-59,-127) num=(1,0)
E/WifiAutoJoinController (  960): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  960): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  960): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  960): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  960): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-59 freq=2412
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/HtcWifiControlRoamOffload: (  960): roamCandidate: nullcurrentBSSID: null
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiAutoJoinController (  960): Done attemptAutoJoin status=3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiConfigStore(  960):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WISPrService( 6296): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131215
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-59 ;0 ,-127] any roam=0 rt=141896
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-59 ;0 ,-127] any roam=0 rt=141896
E/WifiStateMachine(  960): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  960): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  960): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
,D/WifiService(  960): New client listening to asynchronous messages
E/WifiTrafficPoller(  960): ADD_CLIENT: 9
E/WifiConfigStore(  960): Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1329): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  960): will read network variables netId=0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1329): Do not allow key_data field to be exposed
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  960): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  960):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  960): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1329): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1329): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1329): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1329): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  960): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1329): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1329): ENABLE_NETWORK (0)
D/wpa_supplicant( 1329): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1329): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1329): wpa_supplicant_scan enter
D/wpa_supplicant( 1329): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1329): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1329): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1329): WPS:  * Request Type
D/wpa_supplicant( 1329): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1329): WPS:  * UUID-E
D/wpa_supplicant( 1329): WPS:  * Primary Device Type
D/wpa_supplicant( 1329): WPS:  * RF Bands (3)
D/wpa_supplicant( 1329): WPS:  * Association State
D/wpa_supplicant( 1329): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1329): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1329): WPS:  * Manufacturer
D/wpa_supplicant( 1329): WPS:  * Model Name
D/wpa_supplicant( 1329): WPS:  * Model Number
D/wpa_supplicant( 1329): WPS:  * Device Name
D/wpa_supplicant( 1329): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1329): P2P: * P2P IE header
D/wpa_supplicant( 1329): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1329): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1329): wlan0: Add radio work 'scan'@0x55b6de4680
D/wpa_supplicant( 1329): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1329): wlan0: Starting radio work 'scan'@0x55b6de4680 after 0.000031 second wait
D/wpa_supplicant( 1329): wlan0: nl80211: scan request
D/wpa_supplicant( 1329): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1329): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1329): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1329): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1329): wlan0: Own scan request started a scan in 0.000068 seconds
I/wpa_supplicant( 1329): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  960): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
E/WifiMonitor(  960): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  960): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1329): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1329): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1329): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  960): will read network variables netId=0
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1329): Do not allow key_data field to be exposed
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/ConnectivityService(  960): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 group'
D/ConnectivityService(  960): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/Nat464Xlat(  960): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/ConnectivityService(  960): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/ConnectivityService(  960): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/NetworkManagementService(  960): Removing idletimer
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1329): wlan0: Control interface command ',GET_NETWORK 0 identity'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1329): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1329): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  960): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  960):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1329): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1329): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1329): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1329): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1329): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1329): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1329): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1329): wpa_supplicant_scan enter
D/wpa_supplicant( 1329): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1329): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1329): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  960): setLastSelectedConfiguration -1
E/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  960): handleMessage: new destination call exit/enter
E/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  960): invokeExitMethods: DisconnectedState
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1329): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  960): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  960): DisconnectedState call setCountryCode()
E/WifiStateMachine(  960):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  960): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  960): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  960): Disconnected - quitting
D/wpa_supplicant( 1329): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1329): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1329): wlan0: Cancelling scan request
D/wpa_supplicant( 1329): wlan0: nl80211: sched_scan request
I/SecurityController( 1221): onLost 100
D/usbnet  (  960): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  960):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  960): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/PMS     (  960): acquireWL(8a100d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 960 1000 null
D/CSLegacyTypeTracker(  960): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  960): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/ConnectivityService(  960): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  960): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/ConnectivityService(  960): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  960): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  960): ensureActiveMobilePolicyLocked()
D/PMS     (  960): acquireWL(39df5c31): PARTIAL_WAKE_LOCK  NetworkStats 0x1 960 1000 null
D/NetworkPolicy(  960): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  960): updateNetworkEnabledLocked()
V/NetworkPolicy(  960): updateIfacesLocked()
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
V/NetworkPolicy(  960): updateNotificationsLocked()
D/NetworkManagementService(  960): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/FlexNetS( 6914): updateSvcAllowedInSettings:false
D/DATA_ICON( 1221): dataConnected: false/false
D/wpa_supplicant( 1329): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1329): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/PMS     (  960): releaseWL(39df5c31): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1329): wlan0: nl80211: Sched scan started
D/WifiP2pService(  960): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1329): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/WifiP2pService(  960): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1329): wlan0: nl80211: New scan results available
D/WifiP2pService(  960): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1329): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
V/NetworkPolicy(  960): updateNetworkEnabledLocked()
D/wpa_supplicant( 1329): wlan0: Event SCAN_RESULTS (3) received
V/NetworkPolicy(  960): updateNotificationsLocked()
I/wpa_supplicant( 1329): Got an original EVENT_SCAN_RESULTS
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1329): wlan0: Scan completed in 0.039718 seconds
D/wpa_supplicant( 1329): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1329): wlan0: BSS: Start scan result update 8
D/wpa_supplicant( 1329): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
D/wpa_supplicant( 1329): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/wpa_supplicant( 1329): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to no match in scan
D/wpa_supplicant( 1329): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to no match in scan
E/WifiStateMachine(  960): handleMessage: X
D/wpa_supplicant( 1329): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1329): wlan0: New scan results available (own=1 ext=0)
E/WifiStateMachine(  960): handleMessage: E msg.what=131131
E/WifiStateMachine(  960): processMsg: DisconnectedState
D/wpa_supplicant( 1329): wlan0: Radio work 'scan'@0x55b6de4680 done in 0.040699 seconds
D/wpa_supplicant( 1329): wlan0: No suitable network found
D/wpa_supplicant( 1329): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1329): wlan0: Cancelling sched scan
D/wpa_supplicant( 1329): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1329): wlan0: Cancelling scan request
D/wpa_supplicant( 1329): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1329): nl80211: Received scan results (0 BSSes)
E/WifiStateMachine(  960):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  960): processMsg: ConnectModeState
D/wpa_supplicant( 1329): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1329): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1329): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1329): p2p0: No suitable network found
D/wpa_supplicant( 1329): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1329): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1329): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  960):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiStateMachine(  960): handleMessage: X
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
D/WIFI    (  960): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WIFI    (  960):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WIFI    (  960): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  960): enter WifiNetworkFactory startNetwork. mIPTStart:false
E/WifiMonitor(  960): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  960): WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  960): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  960): handleMessage: E msg.what=147461
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:88 bcn=0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:88 bcn=0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:88 bcn=0
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:88 bcn=0
D/WifiStateMachine(  960): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1329): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  960): [1,453,390,913,522 ms] noteScanEnd no scan source
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1329): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  960): handleMessage: X
W/WISPrService( 6296): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6296): trigger connection
D/WISPrService( 6296): continue
D/FlexNetS( 6914): updateSvcAllowedInSettings:false
D/WISPrService( 6296): start DataConnection
D/libc    ( 6296): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6296): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6296): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6296): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6296): [NET] android_getaddrinfo_proxy+
D/libc    ( 6296): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6296): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  960): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=7114 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 6296): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6296): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WISPrService( 6296): >>>>>WISPrService start isConnected = false<<<<<,
D/WISPrService( 6296): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 6296): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 6296): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/FlexNetS( 6914): updateSvcAllowedInSettings:false
D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WISPrService( 6296): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6296): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/libc    ( 6296): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6296): [NET] android_getaddrinfofornet-, err=8
D/FlexNetS( 6914): updateSvcAllowedInSettings:false
D/WISPrService( 6296): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/FlexNetS( 6914): updateSvcAllowedInSettings:false
D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/FlexNetS( 6914): updateSvcAllowedInSettings:false
,D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/FlexNetS( 6914): updateSvcAllowedInSettings:false,
D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6914): updateSvcAllowedInSettings:false,
D/WifiService(  960): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6914): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6914): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6914): updateSvcAllowedInSettings:false
,D/FlexNetS( 6914): updateSvcAllowedInSettings:false
,D/FlexNetS( 6914): updateSvcAllowedInSettings:false
,D/FlexNetS( 6914): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 7114): [9bb.2.]  listen tmrbb8,
D/FlexNetS( 6914): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6978): remove item 101 (p2d27in250) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdScDataSum( 7114): [9bb.2.] summary 118:p2 ignore
,D/Process (  960): killProcessQuiet, pid=6563,
I/ActivityManager(  960): Killing 6563:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6563
,D/PMS     (  960): acquireWL(1fa256a2): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{10024}
V/AlarmManager(  960): sending alarm PendingIntent{11d06f33: PendingIntentRecord{c1312f0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144389, Int=0
,D/PMS     (  960): releaseWL(1fa256a2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/ConnectivityService(  960): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  960): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  960): acquireWL(9846069): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 960 1000 null
D/GpsLocationProvider(  960): [handleMessage] UPDATE_NETWORK_STATE
I/AlarmManager(  960): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  960): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  960): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  960): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/ConnectivityHelper( 1590): [onReceive] WIFI(1): DISCONNECTED
,I/ActivityManager(  960): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7143 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/PMS     (  960): acquireWL(1cf33aee): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{10024}
,V/AlarmManager(  960): sending alarm PendingIntent{3198cb8f: PendingIntentRecord{2bae6e1c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=144971, Int=0
,E/GpsLocationProvider(  960): No APN found to select.,
,D/PMS     (  960): releaseWL(9846069): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 7114): [126.1.]  listen tmrbb8
,D/MdScDataSum( 7114): [126.1.] summary 118:p1 ignore
,I/MusicStore( 7143): Database version: 120
,D/VoldConnector(  960): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 7143): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  960): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 7143): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  960): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 7143): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 7143): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7143): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3,
V/JNIHelp ( 7143): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7143): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 7143): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b92a15b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7143): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7143): GMSCore installation verified
,I/ConfigStore( 7143): Config Database version: 1,
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=7143, uid=10159, userID:0,
,D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
,D/MediaRouterService(  960): Client com.google.android.music (pid 7143): Registered
,D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
,I/MediaRouter( 7143): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 7143): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=7143, uid=10159, userID:0
D/AutoSetting( 1632): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6769): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6769): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1632): Util - no network available!
,D/AutoSetting( 1632): service - onCreate()
,I/GHttpClientFactory( 7143): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7143): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1632): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate,
,D/LocationManagerService(  960): request 26d1737f passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052),
,D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1632): service - mHandler: cancel location update
D/AutoSetting( 1632): service -           changes count: 0
,I/iu.Environment( 4571): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4571): num queued entries: 0,
,I/iu.UploadsManager( 4571): num updated entries: 0
,I/iu.SyncManager( 4571): NEXT; no task,
,D/ChimeraCfgMgr( 4571): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7185 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/Babel   ( 6818): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  960): Killing 6724:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=6724
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6724
,D/VoldConnector(  960): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
,I/GAv4    ( 7185): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7185):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7185):   adb logcat -s GAv4
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 7185): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  960): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
W/ContextImpl( 7185): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/GAv4    ( 7185): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
D/VoldConnector(  960): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 7185): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  960): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 7185): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7185): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7185): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 7185): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7185): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 7185): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 7185): Time to load native libraries: 2 ms (timestamps 6150-6152),
I/LibraryLoader( 7185): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7185): Binding Chromium to main looper Looper (main, tid 1) {29300d0a},
,I/LibraryLoader( 7185): Expected native library version number "",actual native library version number "",
,I/chromium( 7185): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 7185): Initializing chromium process, singleProcess=true,
,W/art     ( 7185): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7185): ApplicationContext is null in ApplicationStatus
,W/chromium( 7185): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7185): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7185): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7185): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7185): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7185): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7185): Local Branch: 
I/Adreno-EGL( 7185): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
,I/Adreno-EGL( 7185): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7185):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 7185): Requires BLUETOOTH permission,
,D/GpsLocationProvider(  960): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  960): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,I/art     (  960): Explicit concurrent mark sweep GC freed 39485(2MB) AllocSpace objects, 3(628KB) LOS objects, 33% free, 16MB/25MB, paused 1.695ms total 138.477ms,
,I/NSApplication( 7185): Starting up...
,I/ActivityManager(  960): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7243 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  960): Killing 6795:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=6795
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  407): Explicit concurrent mark sweep GC freed 8638(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 212us total 43.623ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 118us total 18.759ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 123us total 15.101ms
,I/ActivityManager(  960): Recipient 6795,
,E/WifiStateMachine(  960): handleMessage: E msg.what=131168,
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  960): processMsg: SupplicantStartedState,
E/WifiStateMachine(  960):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  960): processMsg: DefaultState
E/WifiStateMachine(  960):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  960): handleMessage: X
,D/Process (  960): killProcessQuiet, pid=6320,
,I/ActivityManager(  960): Killing 6320:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  960): Recipient 6320
,D/PMS     (  960): acquireWL(2fb8e509): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1840 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  960): releaseWL(1cf33aee): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1840): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
,D/libc    ( 1840): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1840): [NET] android_getaddrinfo_proxy+
D/libc    ( 1840): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1840): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  960): releaseWL(2fb8e509): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/ContactMessageStore( 1547): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1547): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  960): acquireWL(222b712f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7143 10159 null,
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7143, uid=10159, userID:0,
D/PMS     (  960): releaseWL(222b712f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 7143): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7143): Stop autocaching.
,D/WearableService( 6029): callingUid 10024, callindPid: 6029
,E/GmsUtils( 7143): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7143): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/jxcore-log( 7048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 7048): 
,I/jxcore-log( 7048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 7048): 
,I/jxcore-log( 7048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 7048): 
,I/jxcore-log( 7048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 7048): 
,I/jxcore-log( 7048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 7048): 
,I/jxcore-log( 7048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 7048): 
,I/jxcore-log( 7048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 7048): 
,W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  960): acquireWL(176dbbbe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{3e6eab3: PendingIntentRecord{3e46a870 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=148457, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{1be1041f: PendingIntentRecord{3d0a636c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453390941077, Int=0
D/PMS     (  960): acquireWL(393f6d35): PARTIAL_WAKE_LOCK  *backup* 0x1 960 1000 null
,W/BackupManagerService(  960): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  960): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  960): releaseWL(393f6d35): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  960): releaseWL(176dbbbe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/jxcore-log( 7048): Test app app.js loaded,
I/jxcore-log( 7048): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7048): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 7048): BLE advertisement is supported
I/jxcore-log( 7048): 
,I/chromium( 7048): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PMS     (  960): acquireWL(1f45d5ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
D/UsbnetService(  960): BroadcastReceiver::onReceive+,
I/BatteryService(  960): n_update end
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/PMS     (  960): releaseWL(1f45d5ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/NotificationService(  960): plugged=true pluggin=true
D/PMS     (  960): runPSCheck
D/HtcPowerSaver(  960): Checking...
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1632): service - handleMessage() stop self
,D/AutoSetting( 1632): service - handleMessage() quit looper,
D/AutoSetting( 1632): service - onDestroy() END
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/TelephonyReceiver( 1547): switchBindHtcMsgCursor: null
,D/PMS     (  960): releaseWL(8a100d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  960): Failed to find a new network - expiring NetTransition Wakelock
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1632): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1d9e1136
D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/Process (  960): killProcessQuiet, pid=6237
I/ActivityManager(  960): Killing 6237:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6237,
,D/PMS     (  960): acquireWL(3c1bc33b): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{1000},
,D/libc    (  960): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  960): sending alarm PendingIntent{22fcaff5: PendingIntentRecord{2fb1c18a android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=192470, Int=0
,D/libc    (  960): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  960): sending alarm PendingIntent{3e6eab3: PendingIntentRecord{3e46a870 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=208457, Int=0
,D/libc    (  960): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
V/AlarmManager(  960): sending alarm PendingIntent{7f04a58: PendingIntentRecord{3006a7b1 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=213297, Int=0
D/libc    (  960): [NET] android_getaddrinfofornet-, pass to proxy
V/AlarmManager(  960): sending alarm PendingIntent{1dd38496: PendingIntentRecord{7795817 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=193951, Int=0
D/libc    (  960): [NET] android_getaddrinfo_proxy+
D/libc    (  960): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    (  960): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  960): acquireWL(204bb404): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(204bb404): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(3c1bc33b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  960): acquireWL(39d20c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
,D/PMS     (  960): releaseWL(39d20c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  960): updateBatteryInfo
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): runPSCheck
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  960): acquireWL(2cd99be9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(2cd99be9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/PMS     (  960): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  960): acquireWL(255e906e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000},
,V/AlarmManager(  960): sending alarm PendingIntent{3e6eab3: PendingIntentRecord{3e46a870 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=268457, Int=0
,V/AlarmManager(  960): sending alarm PendingIntent{c237f9c: PendingIntentRecord{aa70da5 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453391113339, Int=0
,D/PMS     (  960): releaseWL(255e906e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  960): acquireWL(21e7457a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(21e7457a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  960): plugged=true pluggin=true,
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  960): battery changed pluggedType: 2
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  960): >> updateStatus
,D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  960): acquireWL(1cfff12b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(1cfff12b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): handleMessage: E msg.what=155652
D/PMS     (  960): runPSCheck
D/WifiController(  960): processMsg: DeviceActiveState
,D/HtcPowerSaver(  960): Checking...
D/WifiController(  960): processMsg: StaEnabledState,
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): processMsg: DefaultState
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  960): acquireWL(6b6f988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
,I/BatteryService(  960): n_update end
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/PMS     (  960): releaseWL(6b6f988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): handleMessage: E msg.what=155652
D/PMS     (  960): runPSCheck
D/WifiController(  960): processMsg: DeviceActiveState
D/HtcPowerSaver(  960): Checking...
D/WifiController(  960): processMsg: StaEnabledState
,I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): processMsg: DefaultState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  960): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): << updateStatus
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(231fdf21): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(231fdf21): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): handleMessage: E msg.what=155652
D/PMS     (  960): runPSCheck
D/WifiController(  960): processMsg: DeviceActiveState
D/HtcPowerSaver(  960): Checking...
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: DefaultState
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): << updateStatus
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1547): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1547): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1547): sku_id=118
,D/ContactMessageStore( 1547): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1547): start background delete task...
,D/ContactMessageStore( 1547): size: 0 , 0
,D/ContactMessageStore( 1547): Background delete complete
,D/PMS     (  960): acquireWL(1f143f46): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end,
D/PMS     (  960): releaseWL(1f143f46): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  960): updateBatteryInfo,
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  960): runPSCheck
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): >> updateStatus
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/UsbnetService(  960): onReceive BATTERY_CHANGED
,D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(1d0a7507): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
,I/BatteryService(  960): n_update end
,D/PMS     (  960): releaseWL(1d0a7507): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/NotificationService(  960): plugged=true pluggin=true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): runPSCheck
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): Checking...
,D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  960): >> updateStatus
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(17862634): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(17862634): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  960): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  960): Checking...
,D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  960): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: StaEnabledState
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  960): processMsg: DefaultState
I/HtcPowerSaver(  960): << updateStatus
D/WifiController(  960): handleMessage: X
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  960): acquireWL(23fa4c5d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(23fa4c5d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  960): updateBatteryInfo
D/PMS     (  960): runPSCheck
,D/HtcPowerSaver(  960): Checking...,
,I/HtcPowerSaver(  960): >> updateStatus,
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  960): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  960): << updateStatus
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive-
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  960): battery changed pluggedType: 2
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  960): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(1c509d2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
,D/PMS     (  960): releaseWL(1c509d2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  960): updateBatteryInfo
D/NotificationService(  960): plugged=true pluggin=true
D/PMS     (  960): runPSCheck
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): >> updateStatus
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  960): onReceive BATTERY_CHANGED
,I/HtcPowerSaver(  960): << updateStatus
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(344f5aa3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000},
V/AlarmManager(  960): sending alarm PendingIntent{3e6eab3: PendingIntentRecord{3e46a870 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=388456, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{307971a0: PendingIntentRecord{26145159 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=943105, Int=0
,I/bt-btm  ( 3257): Received oneshot timer event complete
,I/bt-btm  ( 3257): btm_ble_timeout
I/bt-btm  ( 3257): btm_gen_resolvable_private_addr
,D/PMS     (  960): acquireWL(2b45f11e): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3257 1002 null
D/PMS     (  960): releaseWL(344f5aa3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
D/bt-btm  ( 3257): btm_ble_rand_enc_complete
I/bt-btm  ( 3257): btm_gen_resolve_paddr_low
D/bt-smp  ( 3257): smp_encrypt_data
W/bt-smp  ( 3257): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3257): Plain text(LSB ~ MSB) = 6e 15 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3257): Encrypted text(LSB ~ MSB) = ff 82 73 e4 0c 0f d8 49 4e 07 0a 2c 2a 33 80 bf 
I/bt-btm  ( 3257): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3257): Stopping oneshot timer
D/bt-btm  ( 3257): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  960): releaseWL(2b45f11e): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  960): acquireWL(1772fdff): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{3e6eab3: PendingIntentRecord{3e46a870 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=988457, Int=0
,V/AlarmManager(  960): sending alarm PendingIntent{379407cc: PendingIntentRecord{182faa15 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453391786378, Int=0
D/SmartSyncUtils( 6944): isEpsOn(), nState = 0
,D/PMS     (  960): releaseWL(1772fdff): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  960): acquireWL(335c012a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6944 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6944): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6944): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6944): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6944): SettingOnTime = 1453442400000, randomSettingOnTime = 1453439644000
,D/SmartSyncScreenOnOffTimeReceiver( 6944): SettingOffTime = 1453420800000, randomSettingOffTime = 1453426863000
D/SmartSyncScreenOnOffTimeReceiver( 6944): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6944): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6944): bNightModeTurnOffOnce = false
,D/PMS     (  960): releaseWL(335c012a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  960): acquireWL(37037b1b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
I/BatteryService(  960): n_update end
,D/PMS     (  960): releaseWL(37037b1b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(ddfd4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(ddfd4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  960): runPSCheck
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): BroadcastReceiver::onReceive-
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
D/PowerUI ( 1221): closing low battery warning: level=100
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(196dd291): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(196dd291): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState,
D/WifiController(  960): handleMessage: X
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  960): User[0] Flushing usage stats to disk
,D/PMS     (  960): acquireWL(371105f6): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{3dd655a: PendingIntentRecord{17c1c38b android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805712, Int=0,
,V/AlarmManager(  960): sending alarm PendingIntent{3e6eab3: PendingIntentRecord{3e46a870 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1048457, Int=0,
V/AlarmManager(  960): sending alarm PendingIntent{3454adf7: PendingIntentRecord{19198464 android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1150050, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{3f8c06cd: PendingIntentRecord{83f8b82 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453392006153, Int=1800000
,I/ActivityManager(  960): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=7288 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
V/AlarmManager(  960): sending alarm PendingIntent{81c3293: PendingIntentRecord{3c1c82d0 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,I/ActivityManager(  960): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7301 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  960): sending alarm PendingIntent{4df42c9: PendingIntentRecord{9deddce com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453391693817, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{36cd64ef: PendingIntentRecord{5deefdf com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453391742136, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{2a0efbfc: PendingIntentRecord{1a104285 com.htc.task broadcastIntent}}, i=com.htc.task.statistics, t=1, cnt=1, w=1453391921769, Int=0
,D/HtcSystemUPManager(  960): UPAlarmListener onAlarmArrival
,D/HtcSystemUPManager(  960): AlarmScheduler_INEXACT [onReceive] end,
D/HtcSystemUPManager(  960): com.htc.upm.AlarmScheduler$SchedulerBase$1@314751bb
D/HtcSystemUPManager(  960): UPAlarmListener [SYSTEM_UP_UPLOAD] cur = 1453392006234, last = 1453305521593, freq = 86400000
,D/PMS     (  960): acquireWL(50f08da): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4571 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): acquireWL(17978201): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4571 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(50f08da): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/ContextImpl( 6944): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,D/PowerUsageList:PowerUsageHelper( 6944): MY_DEBUG = false
,W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,I/ActivityManager(  960): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=7332 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
D/PowerUsageService( 6944): repeat time = 1453392906284
,I/EventLogService( 4571): Aggregate from 1453390870692 (log), 1453390206119 (data)
,W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
D/HtcSystemUPManager(  960): HtcSystemUPHandler sendService() has been called
D/HtcSystemUPManager(  960): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
I/HtcSystemUPManager(  960): HtcSystemUPDataStore Send UPLOAD message to UP service 
,D/HtcAppUPService( 1632): HtcUPDataProvider bulkInsert() has been called.
,I/ImageRamCache( 7288): create image Cache, size: 31457280.
,I/ImageRamCache( 7288): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 7288): create image Cache, size: 31457280.
,W/ResourcesManager( 7332): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/HtcAppUPService( 1632): HtcUPServiceStore Store Version: 1 Data version: 1 File total length: 9 bytes.  Data length: 0bytes,
I/FeedSettings( 7288): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/HtcAppUPService( 1632): HtcUPServiceStore Uploading is triggered by System...,
I/FeedSettings( 7288): GroupBudget 0.500000 0.380000
I/FeedSettings( 7288): GroupBudget 60 45 15
D/HtcAppUPService( 1632): HtcUPService onCreate()
D/HtcAppUPService( 1632): PolicyStore [Init] Get cached policy bundle
D/HtcAppUPService( 1632): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.SYSTEM_UP_NOTIFY cmp=com.htc.sense.hsp/.upservice.HtcUPService (has extras) }, this = com.htc.sense.hsp.upservice.HtcUPService@2a720f1e
I/Prism.ExternalStringMa_( 7288): changeLocale(): en_GB
,D/HtcSystemUPManager(  960): HtcSystemUPHandler send to UPService takes: 43 ms
,D/HtcAppUPService( 1632): appid: tellhtc_client, category: usage_report, key: enable, value: 1, due date: -1, current time: 1453392006368, default value: null
D/HtcAppUPService( 1632): HtcUPServicePreference Upload schedule enable? false
D/HtcAppUPService( 1632): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.SYSTEM_UP_NOTIFY
,I/Prism.AllAppsOptionsMa_( 7288): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 7288): loadGridSize() with Alternative
,D/HtcAppUPService( 1632): ReportUploader User Profiling function had been closed by user
I/HtcAppUPService( 1632): HtcUPServiceStore Clear data store!
D/HtcAppUPService( 1632): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,D/PMS     (  960): releaseWL(371105f6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10069}
D/HtcAppUPService( 1632): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
D/HtcAppUPService( 1632): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2a720f1e
,D/PMS     (  960): releaseWL(17978201): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,E/cutils-trace( 7361): Error opening trace file: Permission denied (13),
I/dex2oat ( 7361): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/PowerUsageList:PowerUsageHelper( 6944): PowerProfile::POWER_SCREEN_FULL = 154.8
I/dex2oat ( 7361): dex2oat: override thread count:4
D/libc    ( 7288): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4
,D/libc    ( 7288): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7288): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    ( 7288): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7288): [NET] android_getaddrinfo_proxy+
D/libc    ( 7288): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 7288): [NET] android_getaddrinfo_proxy-, NODATA
E/[CSBICLIENT][v12][BiLogUploadService]( 7288): Exception on getConfig()
,D/PowerUsageList:BatterySipperExt( 6944): gen(), null == sipper.uidObj, userId = 0
,I/ActivityManager(  960): Killing 6849:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=6849
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6849
,D/Process (  960): killProcessQuiet, pid=7002
I/ActivityManager(  960): Killing 7002:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 7002,
,I/dex2oat ( 7361): dex2oat took 564.191ms (threads: 4),
,I/PushClient( 7301): ApplicationMonitor {1a1fd8ee}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 7301): ApplicationMonitor {1a1fd8ee}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 7301): ApplicationMonitor {1a1fd8ee}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7301): ApplicationMonitor {1a1fd8ee}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7301): ApplicationMonitor {1a1fd8ee}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 7301): ApplicationMonitor {1a1fd8ee}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7301): ApplicationMonitor {1a1fd8ee}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 7301): ApplicationMonitor {1a1fd8ee}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7301): ApplicationMonitor {1a1fd8ee}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7301): PnsModel {f28b669}: update(): Update registration caused by: alarm,
,I/PushClient( 7301): PnsConfigModel {3994f2b4}: <init>(): Use dm-client for provisioning.,
,W/System.err( 7301): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 7301): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 7301): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7301): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  960): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7374 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 7374): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7374 dbg=false s=true,
,I/DeviceManagement( 7374): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 7374): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7374): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 7374): WorkflowService: Starting workflow service,
,I/DeviceManagement( 7374): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@6db00f0] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 7374): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7374): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 7374): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7374): SessionStateController: Checking invariants...
,I/DeviceManagement( 7374): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7374): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7374): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7374): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@6db00f0],
,I/DeviceManagement( 7374): WorkflowService: Stopping workflow service
,D/Process (  960): killProcessQuiet, pid=6296
,I/ActivityManager(  960): Killing 6296:com.android.settings/1000 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6296,
D/WifiService(  960): Client connection lost with reason: 4
,I/PushClient( 7301): PnsModel {f28b669}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  960): killProcessQuiet, pid=6978
I/ActivityManager(  960): Killing 6978:com.htc.mobiledata/u0a46 (adj 15): empty #17,
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6978
,W/SQLiteConnectionPool( 7288): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,D/PMS     (  960): acquireWL(36756765): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(36756765): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  960): updateBatteryInfo
D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
D/PMS     (  960): runPSCheck
D/HtcPowerSaver(  960): Checking...
I/HtcPowerSaver(  960): >> updateStatus
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(129bfc3a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(129bfc3a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  960): updateBatteryInfo,
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): runPSCheck
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
,D/WifiController(  960): handleMessage: X
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
