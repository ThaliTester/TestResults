#### Test 50650278d1b06e8_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6491): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6491): ====startRecUseTime====
D/htc.customization.log.level( 6491):  is 
W/CustomizationLogLevel( 6491): Level value is invalid, use default level 2
D/CustomizationManager( 6491):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6491): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6491): Parsing tag category name = system
I/CustomizationCIDLoader( 6491): Parsing tag category name = application
I/CustomizationCIDLoader( 6491): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6491): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6491): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6491): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6491): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6491): add string-array item, value = 42507
I/CustomizationCIDLoader( 6491): add string-array item, value = 21902
I/CustomizationCIDLoader( 6491): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6491): add string-array item, value = 23420
I/CustomizationCIDLoader( 6491): add string-array item, value = 22299
I/CustomizationCIDLoader( 6491): add string-array item, value = 24002
I/CustomizationCIDLoader( 6491): add string-array item, value = 23210
I/CustomizationCIDLoader( 6491): add string-array item, value = 23205
I/CustomizationCIDLoader( 6491): add string-array item, value = 23806
I/CustomizationCIDLoader( 6491): add string-array item, value = 23430
I/CustomizationCIDLoader( 6491): add string-array item, value = 23408
I/CustomizationCIDLoader( 6491): add string-array item, value = 27205
I/CustomizationCIDLoader( 6491): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6491):  Read CID file spent 0.101 (s)
D/CustomizationManager( 6491):  All configurations done spent 0.101 (s)
--------- beginning of system
I/ActivityManager(  989): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6491 on display 0
D/PMS     (  989): acquireHCC(10bf805a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 989 1000 null
D/PMS     (  989): acquireHCC(1a41428b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 989 1000 null
I/ActivityManager(  989): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6509 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1329): [EventService]  onDisplayChanged: 0
V/ActivityManager(  989): Display changed displayId=0
D/DotMatrix( 1329): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1503): [trimMemory] 20
D/Process (  989): killProcessQuiet, pid=5715
I/ActivityManager(  989): Killing 5715:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/WebViewFactory( 6509): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/ActivityManager(  989): Recipient 5715
,I/LibraryLoader( 6509): Time to load native libraries: 9 ms (timestamps 265-274),
,I/LibraryLoader( 6509): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6509): Binding Chromium to main looper Looper (main, tid 1) {e373a86}
I/LibraryLoader( 6509): Expected native library version number "",actual native library version number ""
I/chromium( 6509): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6509): Initializing chromium process, singleProcess=true
,W/art     ( 6509): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6509): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6509): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6509): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6509): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 6509): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6509): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6509): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6509): Local Branch: 
I/Adreno-EGL( 6509): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6509): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6509):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  989): Message: MESSAGE_REGISTER_ADAPTER,
D/BluetoothManagerService(  989): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@655915f:true
W/System.err(  989): java.lang.Throwable: stack dump
W/System.err(  989): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  989): ,	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  989): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  989): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6509): 557611282: getState(). Returning 12
,W/art     ( 6509): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6509): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6509): CordovaWebView is running on device made by: HTC
,W/art     ( 6509): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6509): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  989): Activity pause timeout for ActivityRecord{1291df68 u0 com.test.thalitest/.MainActivity t8},
W/HtcSystemUPManager(  989): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,W/chromium( 6509): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/StatusBarManagerService(  989): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  989): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  989): hiding MENU key
D/StatusBarManagerService(  989): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  989): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  989): hiding MENU key
,D/FindExtension( 6509): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6509): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@31b07410, mServedView=org.apache.cordova.engine.SystemWebView{3fde7b09 VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2d2d510e
,I/PhoneStatusBar( 1235): setImeWindowStatus(false,false)
I/InputMethodManagerService(  989): Disable input method client, pid=1503
D/StatusBarManagerService(  989): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6509): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  989): Displayed com.test.thalitest/.MainActivity: +692ms (total +737ms)
,W/BindingManager( 6509): Cannot call determinedVisibility() - never saw a connection for the pid: 6509
,D/JsMessageQueue( 6509): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6509): JniHelper::setJavaVM(0xab3768f8), pthread_self() = -1402337984
,D/JX-Cordova( 6509): jxcore cordova android initializing
,W/jxcore-log( 6509): Initializing JXcore engine
,W/jxcore-log( 6509): JXcore engine is ready
,W/jxcore-log( 6509): Starting JXcore engine,
,W/jxcore-log( 6509): Platform android
W/jxcore-log( 6509): 
W/jxcore-log( 6509): Process ARCH arm
W/jxcore-log( 6509): 
,D/PMS     (  989): releaseHCC(10bf805a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  989): releaseHCC(1a41428b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6509): JXcore Cordova bridge is ready!,
I/jxcore-log( 6509): 
W/jxcore-log( 6509): JXcore engine is started
I/Choreographer( 6509): Skipped 95 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6509): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,D/ContactMessageStore( 1451): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1451): MSG_NOTIFY_CS_TO_SYNC <<
,I/jxcore-log( 6509): Toggling radios to true
I/jxcore-log( 6509): 
,D/BluetoothAdapter( 6509): enable(): BT is already enabled..!
,E/WifiTrafficPoller(  989): ADD_CLIENT: 9
D/WifiService(  989): New client listening to asynchronous messages
,D/WifiManager( 6509): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  989): MONITOR_LOG
D/WifiService(  989): setWifiEnabled: true pid=6509, uid=10366
E/WifiService(  989): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  989): name: wifi_on
I/WifiService(  989): isSprintWifiRestricted(): false,
W/Settings:Agent(  989): value: 2
I/WifiService(  989): isMdmWifiRestricted(): false
W/Settings:Agent(  989): >> traceCallingStack()
W/Settings:Agent(  989): Process.myPid(): 989
W/Settings:Agent(  989): Process.myTid(): 2151
W/Settings:Agent(  989): Process.myUid(): 1000
,W/Settings:Agent(  989): 
W/Settings:Agent(  989): 
W/System.err(  989): java.lang.Throwable: stack dump
,W/System.err(  989): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  989): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  989): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  989): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  989): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  989): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  989): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  989): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  989): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  989): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  989): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  989): 
W/Settings:Agent(  989): << traceCallingStack(): 18(ms)
D/WifiController(  989): handleMessage: E msg.what=155656
D/WifiController(  989): processMsg: DeviceActiveState
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): handleMessage: X
D/WifiManager( 6509): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  989): handleMessage: E msg.what=131145
D/WifiManager( 6509): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  989): processMsg: ConnectedState
E/WifiStateMachine(  989):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/jxcore-log( 6509): Radios toggled
I/jxcore-log( 6509): 
D/wpa_supplicant( 1386): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1386): wlan0: Cancelling scan request
D/wpa_supplicant( 1386): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1386): TDLS: Tear down peers
D/wpa_supplicant( 1386): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  989): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6509): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6509): 
,I/jxcore-log( 6509): Perf Test app loaded loaded,
I/jxcore-log( 6509): 
I/Choreographer( 6509): Skipped 77 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 6509): check test folder
I/jxcore-log( 6509): 
,I/jxcore-log( 6509): found test : ./testFindPeers.js,
I/jxcore-log( 6509): 
,D/wpa_supplicant( 1386): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1386): wlan0: Deauthentication notification
D/wpa_supplicant( 1386): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1386): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1386): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1386): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1386): enter disconnect check
I/wpa_supplicant( 1386): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/Tethering(  989): interfaceLinkStateChanged wlan0, false
D/Tethering(  989): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1386): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1386): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  989): interfaceLinkStateChanged wlan0, false
D/Tethering(  989): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  989): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
,D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  989): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  989): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  989): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
V/Tethering(  989): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  989): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  989): sendTetherStateChangedBroadcast 0, 0, 0
,D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/UsbnetService(  989): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbDeviceManager(  989): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/PMS     (  989): acquireWL(1d131c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 989 1000 null
D/TetherSettings( 4592): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4592): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4592): Cust_ConnectToPC   : Modem_Link>false
D/wpa_supplicant( 1386): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1386): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1386): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1386): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/        ( 4592): Cust_ConnectToPC   : spcsc>false
D/wpa_supplicant( 1386): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55b66e8f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1386):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1386): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1386): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1386): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1386): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1386): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1386): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1386): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1386): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1386): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1386): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1386): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1386): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1386): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1386): EAPOL: External notification - portValid=0
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1386): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/HTCRequest(  989): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1386): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1386): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1386): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1386): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  989): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/        ( 4592): Cust_ConnectToPC   : IPT>true
D/        ( 4592): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  989): transitionTo: destState=DisconnectingState
D/WifiDisplayAdapter(  989): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  989):     Client/Owner: Client
D/WifiDisplayAdapter(  989):     GroupId: 
D/WifiDisplayAdapter(  989):     Passphrase: 
,D/WifiDisplayAdapter(  989):     SessionId: 0
D/WifiDisplayAdapter(  989):     IP Address: }
W/Settings( 4592): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  989): handleMessage: new destination call exit/enter
E/SmartNS_Utility( 4592): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4592): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
E/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  989): invokeExitMethods: ConnectedState
E/WifiStateMachine(  989): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  989): release()
E/WifiStateMachine(  989): PerfLock released for exiting ConnectedState
D/SmartNS_NSReceiver( 4592): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  989): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  989): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  989): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  989): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  989): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  989): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1386): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1386): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1386): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1386): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1386): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/PMS     (  989): releaseWL(1d131c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1386): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1386): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,V/NetworkPolicy(  989): updateNetworkEnabledLocked()
V/NetworkPolicy(  989): updateNotificationsLocked()
E/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1386): Power_Mode_Type mode = 0
I/wpa_supplicant( 1386): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  989): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  989): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1386): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  989): setDhcpActive: false
,W/ContextImpl( 4592): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
V/NativeCrypto( 1954): Read error: ssl=0x55954d7660: I/O error during system call, Connection timed out
E/WifiStateMachine(  989): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  989): setDetailed state send new extra info<unknown ssid>
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
I/jxcore-log( 6509): found test : ./testSendData.js
I/jxcore-log( 6509): 
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/PMS     (  989): acquireWL(bed5261): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
I/SmartNS_Utility( 4592): setISNotification
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 13
V/NetworkPolicy(  989): mWifiStateReceiver: meteredHint=false,EPS mode=false
,V/NativeCrypto( 1954): SSL shutdown failed: ssl=0x55954d7660: I/O error during system call, Broken pipe
D/SmartNS_Utility( 4592): usb_cable_connect = 1
E/WifiStateMachine(  989): NetworkAgent != null
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  989): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  989): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/SmartNS_Utility( 4592): usb_denied = 0
I/SmartNS_PSService( 4592): usb notificaiton:true
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiDataStallTracker(  989): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  989): stopDataStallAlarm 
,E/WifiDataStallTracker(  989): ENABLE_DATA_MONITOR_POLL false Token 3
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  989): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  989): autoRoamSetBSSID any key="NG700"WPA_PSK
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiConfigStore(  989): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): Forcing reevaluation
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1386): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1386): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1386): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): Validated
D/wpa_supplicant( 1386): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1386): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1386): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1386): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
,E/WifiStateMachine(  989): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  989):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  989): Start Disconnecting Watchdog 1
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131146
E/WifiStateMachine(  989): processMsg: DisconnectingState
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  989):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_RECONNECT 0 0,
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1386): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1386): Fast associate: Old scan results
D/wpa_supplicant( 1386): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1386): wpa_supplicant_scan enter
D/wpa_supplicant( 1386): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1386): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1386): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1386): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1386): WPS:  * Request Type
D/wpa_supplicant( 1386): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1386): WPS:  * UUID-E
D/wpa_supplicant( 1386): WPS:  * Primary Device Type
D/wpa_supplicant( 1386): WPS:  * RF Bands (3)
D/PMS     (  989): releaseWL(bed5261): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1386): WPS:  * Association State
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1386): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1386): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1386): WPS:  * Manufacturer
D/wpa_supplicant( 1386): WPS:  * Model Name
D/wpa_supplicant( 1386): WPS:  * Model Number
D/wpa_supplicant( 1386): WPS:  * Device Name
D/wpa_supplicant( 1386): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 1386): P2P: * P2P IE header
D/wpa_supplicant( 1386): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1386): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1386): wlan0: Add radio work 'scan'@0x55b66cb860
D/wpa_supplicant( 1386): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  989): handleMessage: X
D/wpa_supplicant( 1386): wlan0: Starting radio work 'scan'@0x55b66cb860 after 0.000040 second wait
D/wpa_supplicant( 1386): wlan0: nl80211: scan request
E/WifiStateMachine(  989): handleMessage: E msg.what=147460
E/WifiStateMachine(  989): processMsg: DisconnectingState
D/wpa_supplicant( 1386): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1386): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1386): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1386): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1386): wlan0: Own scan request started a scan in 0.000080 seconds
I/wpa_supplicant( 1386): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  989):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133906
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  989): processMsg: ConnectModeState
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  989): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  989): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,E/WifiStateMachine(  989):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133906
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  989): ConnectModeState: Network connection lost 
E/WifiStateMachine(  989): transitionTo: destState=DisconnectedState
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  989): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  989): handleMessage: new destination call exit/enter
E/WifiMonitor(  989): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  989): invokeExitMethods: DisconnectingState
,E/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  989): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  989): DisconnectedState call setCountryCode()
E/WifiStateMachine(  989):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1386): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1386): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1386): wlan0: Cancelling scan request
,D/wpa_supplicant( 1386): wlan0: nl80211: sched_scan request,
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/SmartNS_Utility( 4592): usb_cable_connect = 1
D/SmartNS_Utility( 4592): usb_denied = 0
I/SmartNS_PSService( 4592): usb notificaiton:true
,E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1235): reapply : com.android.settings 2 36
,D/SmartNS_NSReceiver( 4592): Tethered state change:false isNSOpening:false,
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1235): reapply : com.android.settings 1 36,
I/QuickSettingWifi( 1235): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
I/jxcore-log( 6509): found test : ./testSendData2.js
I/jxcore-log( 6509): 
D/wpa_supplicant( 1386): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1386): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1386): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1386): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
E/WifiStateMachine(  989): handleMessage: X
D/wpa_supplicant( 1386): wlan0: nl80211: New scan results available
E/WifiStateMachine(  989): handleMessage: E msg.what=131101
D/wpa_supplicant( 1386): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
E/WifiStateMachine(  989): processMsg: DisconnectedState
D/wpa_supplicant( 1386): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1386): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1386): wlan0: Scan completed in 0.043005 seconds
D/wpa_supplicant( 1386): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1386): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1386): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1386): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1386): wlan0: New scan results available (own=1 ext=0)
E/WifiStateMachine(  989):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
D/wpa_supplicant( 1386): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1386): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1386): wlan0: Radio work 'scan'@0x55b66cb860 done in 0.043833 seconds
D/wpa_supplicant( 1386): wlan0: Selecting BSS from priority group 387
E/WifiStateMachine(  989):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1386): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-57 wps
E/WifiStateMachine(  989): processMsg: DriverStartedState
D/wpa_supplicant( 1386): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1386): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1386): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1386):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1386): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1386): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55b66eac00  current_ssid=0x0
D/wpa_supplicant( 1386): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1386): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1386): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1386): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
E/WifiStateMachine(  989):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1386): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/wpa_supplicant( 1386): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1386): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1386): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1386): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1386): wlan0:, Add radio work 'connect'@0x55b66cb860
D/wpa_supplicant( 1386): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1386): wlan0: Starting radio work 'connect'@0x55b66cb860 after 0.000080 second wait
I/wpa_supplicant( 1386): check if in concurrent case
E/WifiStateMachine(  989):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
I/wpa_supplicant( 1386): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  989): processMsg: DefaultState
E/WifiStateMachine(  989):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  989): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  989): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=147462
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  989): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  989): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  989): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  989): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiStateMachine(  989):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=133951  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=40 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  989): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=133951  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131212
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
D/wpa_supplicant( 1386): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1386): wlan0: Cancelling sched scan
E/WifiStateMachine(  989):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DriverStartedState
D/wpa_supplicant( 1386): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1386): wlan0: Cancelling scan request
D/wpa_supplicant( 1386): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1386): wpas_start_assoc_cb, 1895
E/WifiStateMachine(  989):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1386): wpas_start_assoc_cb, 1910
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/wpa_supplicant( 1386): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1386): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1386): RSN: PMKSA cache search - network_ctx=0x55b66eac00 try_opportunistic=0
D/wpa_supplicant( 1386): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1386): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1386): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1386): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1386): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1386): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1386): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1386): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1386): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1386): wlan0: WPA: not using MGMT group cipher
E/WifiStateMachine(  989):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DefaultState
D/wpa_supplicant( 1386): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1386): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1386): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1386): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1386): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
E/WifiStateMachine(  989):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1386): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1386): nl80211: Unsubscribe mgmt frames handle 0x888888dd3ee62989 (mode change)
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  989): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  989): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/wpa_supplicant( 1386): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b66ea100
E/WifiStateMachine(  989): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=0104
E/WifiStateMachine(  989): handleMessage: X
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=040a
E/WifiStateMachine(  989): handleMessage: E msg.what=131212
E/WifiStateMachine(  989): processMsg: DisconnectedState
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=040b
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=040c
D/WifiMonitor(  989): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=040d
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=090a
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=090b
E/WifiStateMachine(  989):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=090c
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=090d
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=0409506f9a09
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=7f506f9a09
E/WifiStateMachine(  989):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DriverStartedState
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=0801
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=040e
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=06
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=0a07
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=0a11
D/wpa_supplicant( 1386): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b66ea100 match=0a1a
E/WifiStateMachine(  989):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/wpa_supplicant( 1386): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1386):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386):   * freq=2412
D/wpa_supplicant( 1386):   * freq_hint=2412
D/wpa_supplicant( 1386):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1386):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1386):   * WPA Versions 0x2
D/wpa_supplicant( 1386):   * pairwise=0xfac04
D/wpa_supplicant( 1386):   * group=0xfac04
D/wpa_supplicant( 1386):   * akm=0xfac02
D/wpa_supplicant( 1386):   * Auth Type 0
D/wpa_supplicant( 1386): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55b66eac3a
E/WifiStateMachine(  989):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DefaultState
E/WifiStateMachine(  989):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1386): nl80211: Connect request send successfully
D/wpa_supplicant( 1386): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1386): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1386): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1386): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1386): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1386): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1386): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  989): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  989): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131212
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/jxcore  ( 6509): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 6509): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
E/WifiStateMachine(  989):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
E/WifiStateMachine(  989):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DefaultState
I/chromium( 6509): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/WifiStateMachine(  989):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  989): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  989): handleMessage: X
D/WifiNetworkAgent(  989): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  989): handleMessage: E msg.what=147462
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=133957  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  989): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  989): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  989): NetworkAgent == null
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=133964  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=147461
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2122 bcn=0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2122 bcn=0
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2122 bcn=0
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
E/WifiStateMachine(  989):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:2122 bcn=0
D/WifiStateMachine(  989): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1386): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  989): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  989): [1,450,655,552,994 ms] noteScanEnd no scan source
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1386): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  989): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@216673bf sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  989): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  989): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  989): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  989): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  989):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2412
E/WifiAutoJoinController (  989): UPC503894600 a0:c5:62:7a:49:97 rssi=-88 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  989): ageScanResultsOut delay 40000 size 3 now 1450655552997
E/WifiAutoJoinController (  989): newSupplicantResults size=3 known=1 true
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1386): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  989): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  989): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  989): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  989): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  989): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  989):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131213
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133971
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133971
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133971
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
E/WifiStateMachine(  989):  SupplicantStartedState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133972
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=147462
E/WifiStateMachine(  989): processMsg: DisconnectedState
D/WISPrService( 4592): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  989):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=133979  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  989): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  989): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  989): setDetailed state send new extra info0x
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  989): NetworkAgent == null
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  989): processMsg: ConnectModeState
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  989):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=133982  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  989): handleMessage: X
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:22
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 18
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:0
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiTrafficPoller(  989): ADD_CLIENT: 10
D/WifiService(  989): New client listening to asynchronous messages
D/ConnectivityService(  989): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  989): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  989): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  989): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  989): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkManagementService(  989): Removing idletimer
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): Disconnected - quitting
D/WIFI    (  989): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  989):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  989): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  989):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  989): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/PMS     (  989): acquireWL(1f233a47): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 989 1000 null
E/WifiStateMachine(  989): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/CSLegacyTypeTracker(  989): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/usbnet  (  989): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  989): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1235): CM callback handler got msg 524292
D/ConnectivityService(  989): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/SecurityController( 1235): onLost 100
D/PMS     (  989): acquireWL(17aba274): PARTIAL_WAKE_LOCK  NetworkStats 0x1 989 1000 null
D/Tethering(  989): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkPolicy(  989): ensureActiveMobilePolicyLocked()
D/Tethering(  989): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  989): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/DATA_ICON( 1235): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/ConnectivityService(  989): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkPolicy(  989): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  989): updateNetworkEnabledLocked()
V/NetworkPolicy(  989): updateIfacesLocked()
V/NetworkPolicy(  989): updateNotificationsLocked()
D/DATA_ICON( 1235): dataConnected: false/false
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  989): releaseWL(17aba274): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkManagementService(  989): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  989): handleMessage: E msg.what=131131
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  989): handleMessage: X
V/NetworkPolicy(  989): updateNetworkEnabledLocked()
V/NetworkPolicy(  989): updateNotificationsLocked()
W/WISPrService( 4592): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4592): trigger connection
D/WISPrService( 4592): continue
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/WISPrService( 4592): start DataConnection
D/libc    ( 4592): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4592): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/libc    ( 4592): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4592): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4592): [NET] android_getaddrinfo_proxy+
D/libc    ( 4592): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4592): [NET] android_getaddrinfo_proxy-, NODATA
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:0
D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/FlexNetS( 6375): updateSvcAllowedInSettings:false
,D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/FlexNetS( 6375): updateSvcAllowedInSettings:false,
,D/libc    ( 4592): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
I/ActivityManager(  989): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6573 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/libc    ( 4592): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 4592): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/wpa_supplicant( 1386): Wireless event: cmd=0x8c02 len=271
,I/wpa_supplicant( 1386): WEXT: Custom wireless event: 'BEACONIEs='
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/wpa_supplicant( 1386): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1386): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1386): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1386): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1386): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1386): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1386): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1386): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1386): nl80211: Connect event
D/wpa_supplicant( 1386): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1386): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1386): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1386): wlan0: Association info event
D/wpa_supplicant( 1386): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1386): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1386): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1386): wlan0: freq=2412 MHz
D/wpa_supplicant( 1386): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1386): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1386): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1386): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1386): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1386): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1386): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1386): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1386): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1386): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1386): TDLS: Remove peers on association
D/wpa_supplicant( 1386): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1386): EAPOL: External notification - portValid=0
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1386): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1386): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1386): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1386): EAPOL: enable timer tick
D/wpa_supplicant( 1386): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1386): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1386): wlan0: Cancelling scan request
I/wpa_supplicant( 1386): htc_wext_set_keepalive +
I/wpa_supplicant( 1386): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1386): getPrivFuncNum +	
I/wpa_supplicant( 1386): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1386): htc_wext_set_keepalive fnum = 0x8bf6
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1386): htc_wext_set_keepalive - ret = 0
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1386): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1386): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1386): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1386): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1386): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1386):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1386):   key_nonce - hexdump(len=32): fd db df cf e3 0c 03 1f 16 d2 00 5f 0b 0f b2 52 a3 bf 38 ef 51 1d 1b 71 a6 72 09 04 1c 6f 81 dc
D/StatusBar.NetworkController( 1235): dumpIc,on[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1386):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1386):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1386):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1386):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1386): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1386): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1386): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  989): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/UsbDeviceManager(  989): [USBNET] bCheckSuppFunc: cdc_network
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/PMS     (  989): acquireWL(38b72b3f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 989 1000 null
D/WifiMonitor(  989): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  989): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=43 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  989): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  989): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  989): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  989): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  989): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  989): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  989): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  989): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  989): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  989): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1386): WPA: Renewed SNonce - hexdump(len=32): 3a a1 0b b2 5c 23 6d 42 fc b0 94 f5 0f ea e7 c5 ef 8b dd b7 49 a7 c8 b8 f4 b9 8f af 03 bc 33 c0
D/WifiMonitor(  989): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/wpa_supplicant( 1386): WPA: Nonce1 - hexdump(len=32): 3a a1 0b b2 5c 23 6d 42 fc b0 94 f5 0f ea e7 c5 ef 8b dd b7 49 a7 c8 b8 f4 b9 8f af 03 bc 33 c0
D/wpa_supplicant( 1386): WPA: Nonce2 - hexdump(len=32): fd db df cf e3 0c 03 1f 16 d2 00 5f 0b 0f b2 52 a3 bf 38 ef 51 1d 1b 71 a6 72 09 04 1c 6f 81 dc
D/wpa_supplicant( 1386): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1386): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1386): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1386): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1386): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1386): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1386): WPA: Derived Key MIC - hexdump(len=16): c8 22 58 cd 81 7a 17 76 16 18 0c f3 1a e0 ab 16
D/Tethering(  989): interfaceLinkStateChanged wlan0, false
D/Tethering(  989): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  989): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/Tethering(  989): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  989):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=134080  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  989): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  989): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  989): processMsg: ConnectModeState
D/Tethering(  989): interfaceLinkStateChanged wlan0, false
D/Tethering(  989): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  989):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=134081  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  989): interfaceLinkStateChanged wlan0, true
D/Tethering(  989): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=147500
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  989): Enter handleAssociatedWithEvent
D/WifiStateMachine(  989): Associated
V/Tethering(  989): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1386): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
,D/wpa_supplicant( 1386): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1386): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1386): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1386):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1386):   key_nonce - hexdump(len=32): fd db df cf e3 0c 03 1f 16 d2 00 5f 0b 0f b2 52 a3 bf 38 ef 51 1d 1b 71 a6 72 09 04 1c 6f 81 dc
D/WifiStateMachine(  989): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/WifiStateMachine(  989): Exit handleAssociatedWithEvent
D/wpa_supplicant( 1386):   key_rsc - hexdump(len=8): c4 6a 00 00 00 00 00 00
D/wpa_supplicant( 1386):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1386):   key_mic - hexdump(len=16): 4f fa 7f ca 6b 17 30 90 9f 71 99 4a 19 96 7f 22
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/wpa_supplicant( 1386): RSN: encrypted key data - hexdump(len=56): 66 c6 c2 c7 a5 b0 9a c3 f7 28 26 53 5d f1 f4 06 f9 54 5a 3d db 0c 5a f7 9c 82 8a 60 b7 f6 13 4e ...
E/WifiStateMachine(  989): processMsg: DisconnectedState
D/wpa_supplicant( 1386): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1386): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/wpa_supplicant( 1386): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1386): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 4b 0f ...
D/PMS     (  989): releaseWL(38b72b3f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1386): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1386): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1386): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1386): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1386): WPA: Derived Key MIC - hexdump(len=16): 3f a4 24 2a f9 4e 38 d4 60 97 f1 77 0e b0 3a 48
D/wpa_supplicant( 1386): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1386): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55b66eb390 key_idx=0 set_tx=1 seq_len=6 key_len=16
V/NetworkPolicy(  989): updateNetworkEnabledLocked()
D/wpa_supplicant( 1386): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
V/NetworkPolicy(  989): updateNotificationsLocked()
D/wpa_supplicant( 1386): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1386):    addr=c0:ff:d4:d3:aa:48
E/WifiStateMachine(  989):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=134084  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  989): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  989): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  989): setDetailed state send new extra info"NG700"
D/WifiDisplayAdapter(  989): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  989):     Client/Owner: Client
D/WifiDisplayAdapter(  989):     GroupId: 
D/WifiDisplayAdapter(  989):     Passphrase: 
D/WifiDisplayAdapter(  989):     SessionId: 0
D/WifiDisplayAdapter(  989):     IP Address: }
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700,, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1386): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1386): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1386): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1386): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1386): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1386): WPA: RSC - hexdump(len=6): c4 6a 00 00 00 00
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1386): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x558d130e68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1386): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/HTCRequest(  989): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1386): nl80211: KEY_SEQ - hexdump(len=6): c4 6a 00 00 00 00
D/wpa_supplicant( 1386):    broadcast key
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  989): NetworkAgent == null
I/wpa_supplicant( 1386): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  989): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1386): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1386): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/WifiMonitor(  989): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 1386): wlan0: Radio work 'connect'@0x55b66cb860 done in 0.135573 seconds
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=46 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1386): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/WifiMonitor(  989): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1386): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  989): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  989): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/wpa_supplicant( 1386): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1386): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1386): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  989): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=49 dispatchEvent: Connect to SSID: NG700
E/WifiStateMachine(  989):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=134086  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/WifiMonitor(  989): couldn't identify event type - Connect to SSID: NG700
E/WifiStateMachin,e(  989): handleMessage: X
I/wpa_supplicant( 1386): set send_ind_to_ndc = 0
D/FlexNetS( 6375): updateSvcAllowedInSettings:false
I/wpa_supplicant( 1386): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1386): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1386): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1386): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1386): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1386): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1386): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1386): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1386): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1386): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1386): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1386): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1386): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  989): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  989): interfaceLinkStateChanged wlan0, true
D/Tethering(  989): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  989): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 20
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 21
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  989): handleMessage: E msg.what=147462
E/WifiStateMachine(  989): processMsg: DisconnectedState
D/Tethering(  989): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  989):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=134091  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  989): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/UsbnetService(  989): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  989): BroadcastReceiver::onReceive-
E/WifiStateMachine(  989): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=134092  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=147459
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=134093
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=134093
E/WifiStateMachine(  989): Network connection established
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateMachine(  989): fetchFrequency(), freq = 2412
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  989): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  989): NetworkAgent == null
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 22
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  989): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  989): handleMessage: new destination call exit/enter
E/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  989): invokeExitMethods: DisconnectedState
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1386): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1386): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  989): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  989): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  989): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  989): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  989): NetworkAgent == null
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 23
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
D/FlexNetS( 6375): updateSvcAllowedInSettings:false
D/ConnectivityService(  989): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  989): Got NetworkAgent Messenger
D/ConnectivityService(  989): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  989): NetworkAgent connected
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 24
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  989): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  989): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  989): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1386): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1386): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1386): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1386): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1386): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1386): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1386): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  989): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  989): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  989): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  989): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  989): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1386): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1386): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1386): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1386): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1386): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1386): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/wpa_supplicant( 1386): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  989): Start Dhcp Watchdog 2
E/WifiStateMachine(  989): handleMessage: X
D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  989): handleMessage: E msg.what=147462
E/WifiStateMachine(  989): processMsg: ObtainingIpState
E/WifiStateMachine(  989):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=134132  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=134132  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=134133  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131101
E/WifiStateMachine(  989): processMsg: ObtainingIpState
E/WifiStateMachine(  989):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/FlexNetS( 6375): updateSvcAllowedInSettings:false
E/WifiStateMachine(  989):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  989): processMsg: DefaultState
E/WifiStateMachine(  989):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  989): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  989): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  989): handleMessage: X
D/WISPrService( 4592): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  989): handleMessage: E msg.what=131212
E/WifiStateMachine(  989): processMsg: ObtainingIpState
E/WifiStateMachine(  989):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
E/WifiStateMachine(  989):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DefaultState
E/WifiStateMachine(  989):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WISPrService( 4592): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  989): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  989): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  989): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=196612
E/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
E/WifiStateMachine(  989):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  989): processMsg: L2ConnectedState
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiStateMachine(  989): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  989):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/PMS     (  989): acquireWL(81e1310): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 989 1000 null
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiDataStallTracker(  989): setDhcpActive: true
D/WifiStateMachine(  989): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1386): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
,E/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  989): do suspend false
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1386): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1386): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1386): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1386): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1386): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1386): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1386): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  989): Unexpected BatchedScanResults :null
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1386): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  989): noteBatchedScanstop()
E/WifiStateMachine(  989): handleMessage: X
D/WifiP2pService(  989): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c08773f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c08773f target=com.android.internal.util.StateMachine$SmHandler }
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/FlexNetS( 6375): updateSvcAllowedInSettings:false
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/FlexNetS( 6375): updateSvcAllowedInSettings:false
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:2
I/QuickSettingWifi( 1235): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
D/TetherSettings( 4592): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4592): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4592): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4592): Cust_ConnectToPC   : spcsc>false
D/        ( 4592): Cust_ConnectToPC   : IPT>true
W/ContextImpl( 4592): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 4592): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4592): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4592): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4592): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4592): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
I/SmartNS_Utility( 4592): setISNotification,
D/SmartNS_Utility( 4592): usb_cable_connect = 1
,D/SmartNS_Utility( 4592): usb_denied = 0
I/SmartNS_PSService( 4592): usb notificaiton:true
,E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 4592): usb_cable_connect = 1
,D/SmartNS_Utility( 4592): usb_denied = 0
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/SmartNS_PSService( 4592): usb notificaiton:true
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1235): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 4592): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/FlexNetS( 6375): updateSvcAllowedInSettings:false
,I/RemoteViews( 1235): reapply : com.android.settings 2 36
,D/FlexNetS( 6375): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6573): [cba.2.]  listen tmrbb8,
,D/FlexNetS( 6375): updateSvcAllowedInSettings:false
,D/FlexNetS( 6375): updateSvcAllowedInSettings:false
,D/FlexNetS( 6375): updateSvcAllowedInSettings:false
,D/FlexNetS( 6375): updateSvcAllowedInSettings:false
,D/FlexNetS( 6375): updateSvcAllowedInSettings:false
,D/FlexNetS( 6375): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6439): remove item 101 (p2d26in239) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6573): [cba.2.] summary 118:p2 ignore
,D/MdProvGlob( 6439): remove item 101 (p2in12) for 15:android.intent.action.ANY_DATA_STATE
,E/dhcpcd  ( 6602): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6602): version 5.5.6 starting
E/dhcpcd  ( 6602): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6602): wlan0: using ClientID 01:90:**:c4:e6:4c:f8,
I/dhcpcd  ( 6602): autoip env[11]:autoip=DISABLE
,D/MdScDataSum( 6573): [cba.12.] summary 118:p1 ignore
,D/Process (  989): killProcessQuiet, pid=6044
I/ActivityManager(  989): Killing 6044:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6602): wlan0: rebinding lease of 192.168.1.130
,I/dhcpcd  ( 6602): wlan0: sending REQUEST (xid 0x4a748790), next in 0.53 seconds
,I/ActivityManager(  989): Recipient 6044
,I/dhcpcd  ( 6602): wlan0: sending REQUEST (xid 0x4a748790), next in 2.58 seconds
,I/dhcpcd  ( 6602): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,D/wpa_supplicant( 1386): EAPOL: startWhen --> 0
D/wpa_supplicant( 1386): EAPOL: disable timer tick
,I/dhcpcd  ( 6602): wlan0: leased 192.168.1.130 for 86400 seconds
D/ConnectivityService(  989): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/dhcpcd  ( 6602): autoip env[11]:autoip=DISABLE
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  989): handleMessage: E msg.what=131212
E/WifiStateMachine(  989): processMsg: ObtainingIpState
E/WifiStateMachine(  989):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: L2ConnectedState,
E/WifiStateMachine(  989):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
E/WifiStateMachine(  989):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  989): processMsg: DefaultState
E/WifiStateMachine(  989):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  989): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  989): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  989): handleMessage: X
,D/PMS     (  989): acquireWL(1e39503c): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10024}
V/AlarmManager(  989): sending alarm PendingIntent{1f41a1c5: PendingIntentRecord{319a171a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=135216, Int=0
,D/PMS     (  989): acquireWL(9c1f24b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): releaseWL(1e39503c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1954): [NET] android_getaddrinfo_proxy+
D/libc    ( 1954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1954): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  989): acquireWL(9c1f24b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  989): releaseWL(9c1f24b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/dhcpcd  ( 6602): bind_interface: daemonise,
,D/libc    (  989): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS,
,D/libc    (  989): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  989): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  989): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/PMS     (  989): releaseWL(81e1310): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  989): handleMessage: E msg.what=196613
E/WifiStateMachine(  989): processMsg: ObtainingIpState
E/WifiStateMachine(  989):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1386): Power_Mode_Type mode = 0
I/wpa_supplicant( 1386): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/ConnectivityService(  989): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1386): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  989): setDhcpActive: false
E/WifiStateMachine(  989): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  989): WifiStateMachine DHCP successful
E/WifiStateMachine(  989): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  989): link address 192.168.1.130/24
E/WifiStateMachine(  989): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  989): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  989): gateway: /192.168.1.1
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1386): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1386): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1386): htc_wext_set_keepalive +
I/wpa_supplicant( 1386): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1386): getPrivFuncNum +	
I/wpa_supplicant( 1386): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1386): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1386): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1386): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1386): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  989): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131210
E/WifiStateMachine(  989): processMsg: ObtainingIpState
,E/WifiStateMachine(  989):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1386): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1386): environment dirty rate=16 [6][1][0]
,E/WifiStateMachine(  989): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  989): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
,E/WifiConfigStore(  989): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear",
D/wpa_supplicant( 1386): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1386): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  989): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=51 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  989): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
,E/WifiStateMachine(  989): NetworkAgent != null
D/WifiWatchdogStateMachine(  989): RSSI current: 3 new: -58, 3
D/ConnectivityService(  989): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  989): Adding iface wlan0 to network 101
D/WIFI_ICON( 1235): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  989): transitionTo: destState=ConnectedState
E/WifiStateMachine(  989): handleMessage: new destination call exit/enter
E/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  989): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  989): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  989): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  989): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiDataStallTracker(  989): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  989): WAN detection
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/HtcWifiWanDetect(  989): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiDataStallTracker(  989): ENABLE_DATA_MONITOR_POLL true Token 4
V/NetworkPolicy(  989): mWifiStateReceiver: meteredHint=false,EPS mode=false
,E/WifiDataStallTracker(  989): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 26
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1235): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  989): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1235): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 4592): >>>>>WISPrService start isConnected = true<<<<<
E/ConnectivityService(  989): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  989): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  989): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131131
E/WifiStateMachine(  989): processMsg: ConnectedState
,E/WifiStateMachine(  989):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine(  989): processMsg: L2ConnectedState
D/ConnectivityService(  989): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  989):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  989): handleMessage: X
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  989): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 4592): >>>>>WISPrService start isConnected = true<<<<<
,D/libc    (  989): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  989): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/Nat464Xlat(  989): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  989): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  989): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  989): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  989):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  989):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  989):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  989): currentScore = 0, newScore = 20
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  989):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): Connected
D/ConnectivityService(  989): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): Validated
D/usbnet  (  989): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  989):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  989): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI    (  989): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  989):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/CSLegacyTypeTracker(  989): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  989): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  989): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  989): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  989): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  989): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  989): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  989): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  989): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  989): ensureActiveMobilePolicyLocked()
D/PMS     (  989): acquireWL(299f9541): PARTIAL_WAKE_LOCK  NetworkStats 0x1 989 1000 null
,D/ConnectivityService(  989): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): Validated
,D/ConnectivityService(  989): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1235): CM callback handler got msg 524290
D/ConnectivityService(  989): Validated NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  989): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/DATA_ICON( 1235): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
,D/usbnet  (  989):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  989): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  989): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  989):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/SecurityController( 1235): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  989):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1235): CM callback handler got msg 524290
D/ConnectivityService(  989): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/WIFI    (  989): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  989): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  989):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  989): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1235): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  989): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1235): CM callback handler got msg 524290
D/ConnectivityService(  989): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
I/SecurityController( 1235): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  989): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  989): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  989): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  989): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  989):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  989):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  989): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  989): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/DATA_ICON( 1235): dataConnected: false/false
D/ConnectivityService(  989): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/DATA_ICON( 1235): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/NetworkPolicy(  989): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  989): updateNetworkEnabledLocked()
V/NetworkPolicy(  989): updateIfacesLocked()
V/NetworkPolicy(  989): updateNotificationsLocked()
D/DATA_ICON( 1235): dataConnected: false/false
D/StatusBar.NetworkController( 1235): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  989): releaseWL(299f9541): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkManagementService(  989): isBandwidthControlEnabled: doneSignal.getCount()= 0
V/NetworkPolicy(  989): updateNetworkEnabledLocked()
V/NetworkPolicy(  989): updateNotificationsLocked()
,I/QuickSettingWifi( 1235): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1235): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/libc    (  989): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  989): handleMessage: E msg.what=131212
E/WifiStateMachine(  989): processMsg: ConnectedState
,E/WifiStateMachine(  989):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  989): processMsg: ConnectModeState
,E/WifiStateMachine(  989):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns,
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
,E/WifiStateMachine(  989):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns,
E/WifiStateMachine(  989): processMsg: DefaultState
E/WifiStateMachine(  989):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine(  989): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  989): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,E/WifiStateMachine(  989): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  989): identical MTU - not setting
E/WifiStateMachine(  989): handleMessage: X
D/Nat464Xlat(  989): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
,D/ConnectivityManager.CallbackHandler( 1235): CM callback handler got msg 524295
D/ConnectivityService(  989): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  989): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  989): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1235): CM callback handler got msg 524295
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  989): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/PMS     (  989): releaseWL(1f233a47): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  989): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  989): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  989): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  989): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  989): [handleMessage] UPDATE_NETWORK_STATE
,D/PMS     (  989): acquireWL(9b28ae6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 989 1000 null
D/GpsLocationProvider(  989): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true,
D/PMS     (  989): acquireWL(1b3b6827): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 989 1000 null
,D/PMS     (  989): releaseWL(1b3b6827): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/htcCheckinService(  989): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/ConnectivityHelper( 1503): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  989): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6637 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  989): No APN found to select.
,D/PMS     (  989): releaseWL(9b28ae6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6573): [222.1.]  listen tmrbb8
,D/MdScDataSum( 6573): [222.1.] summary 118:p1 ignore
,I/MusicStore( 6637): Database version: 120,
,I/art     ( 1954): Explicit concurrent mark sweep GC freed 13056(704KB) AllocSpace objects, 7(588KB) LOS objects, 49% free, 4MB/8MB, paused 950us total 63.388ms,
,D/VoldConnector(  989): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6637): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  989): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6637): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  989): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6637): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6637): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6637): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6637): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6637): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6637): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1821c6da: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6637): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6637): GMSCore installation verified
,I/ConfigStore( 6637): Config Database version: 1,
,I/PackageManager(  989):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6637, uid=10159, userID:0,
,D/WifiDisplayAdapter(  989): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  989):     Client/Owner: Client
D/WifiDisplayAdapter(  989):     GroupId: 
D/WifiDisplayAdapter(  989):     Passphrase: 
D/WifiDisplayAdapter(  989):     SessionId: 0
D/WifiDisplayAdapter(  989):     IP Address: }
,D/MediaRouterService(  989): Client com.google.android.music (pid 6637): Registered,
,D/WifiDisplayAdapter(  989): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  989):     Client/Owner: Client
D/WifiDisplayAdapter(  989):     GroupId: 
D/WifiDisplayAdapter(  989):     Passphrase: 
D/WifiDisplayAdapter(  989):     SessionId: 0
D/WifiDisplayAdapter(  989):     IP Address: }
,I/MediaRouter( 6637): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6637): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6637): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6637): type=WIFI subType= reason=null isConnected=true
,I/PackageManager(  989):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6637, uid=10159, userID:0
,D/AutoSetting( 1589): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 5815): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5815): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1589): service - onCreate()
,I/GHttpClientFactory( 6637): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6637): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1589): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1589): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  989): request 1f76fe4b passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  989): provider request: passive ProviderRequest[ON interval=0]
,I/iu.SyncManager( 4228): SYNC; picasa accounts
,D/NetworkLogImpl( 4228): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4228): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
,I/iu.UploadsManager( 4228): num queued entries: 0
,I/iu.UploadsManager( 4228): num updated entries: 0
,I/iu.SyncManager( 4228): NEXT; no task
,D/PMS     (  989): acquireWL(31d11b85): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10024},
V/AlarmManager(  989): sending alarm PendingIntent{3a496dda: PendingIntentRecord{319a171a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=137860, Int=0
,D/ChimeraCfgMgr( 4228): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4228): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  989): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6683 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6255): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 6255): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6255): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6255): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 6255): [NET] android_getaddrinfo_proxy+
D/libc    ( 6255): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/art     (  989): Explicit concurrent mark sweep GC freed 60929(3MB) AllocSpace objects, 4(528KB) LOS objects, 33% free, 16MB/24MB, paused 1.709ms total 192.673ms,
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6255): [NET] android_getaddrinfo_proxy-, success
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
,I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Babel   ( 6255): connection state changed from UNKNOWN to CONNECTED,
,W/Kids    ( 4228): [AccountUtils] Account not ready
W/Kids    ( 4228): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4228): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4228): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4228): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4228): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4228): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4228): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4228): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4228): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4228): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1235): reapply : com.google.android.gms 2 40
,D/VoldConnector(  989): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6683): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6683): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6683):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6683):   adb logcat -s GAv4
D/VoldConnector(  989): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6683): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  989): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6683): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  989): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
W/GAv4    ( 6683): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6683): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6683): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6683): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6683): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6683): [apache-http] Connection GC has been deprecated!,
,D/libc    (  989): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
I/WebViewFactory( 6683): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/libc    (  989): [NET] android_getaddrinfofornet-, err=8
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  989): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  989): [NET] android_getaddrinfo_proxy+
D/libc    (  989): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  989): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  989): [AlarmQueuing] connectivity wifi: true
,D/GpsLocationProvider(  989): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  989): acquireWL(1f37fde1): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 989 1000 null
D/PMS     (  989): acquireWL(1737d706): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 989 1000 null
,D/htcCheckinService(  989): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/GpsLocationProvider(  989): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  989): releaseWL(1737d706): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  989): [NET] android_getaddrinfo_proxy-, success
D/HtcWifiWanDetect(  989): Find DNS Address www.htc.com/104.81.130.175
,D/GpsLocationProvider(  989): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ConnectivityHelper( 1503): [onReceive] WIFI(1): CONNECTED
I/NetworkMonitor( 6637): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  989): No APN found to select.
,D/PMS     (  989): releaseWL(1f37fde1): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,D/MdScPhnSt( 6573): [fa0.1.]  listen tmrbb8
,D/MdScDataSum( 6573): [fa0.1.] summary 118:p1 ignore
,I/LibraryLoader( 6683): Time to load native libraries: 23 ms (timestamps 8485-8508)
,I/LibraryLoader( 6683): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6683): Binding Chromium to main looper Looper (main, tid 1) {9f3d72b}
,I/LibraryLoader( 6683): Expected native library version number "",actual native library version number ""
,I/chromium( 6683): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6683): Initializing chromium process, singleProcess=true,
,W/art     ( 6683): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6683): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6683): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6683): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6683): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6683): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6683): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6683): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6683): Local Branch: 
I/Adreno-EGL( 6683): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6683): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6683):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6683): Requires BLUETOOTH permission
,I/NSApplication( 6683): Starting up...
,D/BluetoothAdapter( 6509): 557611282: getState(). Returning 12
,D/Process (  989): killProcessQuiet, pid=5122
I/ActivityManager(  989): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6747 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6509): setDiscoveryMode: Mode set to BLE
I/ActivityManager(  989): Killing 5122:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
,D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/jxcore-log( 6509): BLE supported!!
I/jxcore-log( 6509): 
,E/WifiStateMachine(  989): handleMessage: E msg.what=131168
,E/WifiStateMachine(  989): processMsg: ConnectedState
E/WifiStateMachine(  989):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
,E/WifiStateMachine(  989):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  989): processMsg: DefaultState
E/WifiStateMachine(  989):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  989): handleMessage: X
,I/ActivityManager(  989): Recipient 5122
,D/Process (  989): killProcessQuiet, pid=6206
I/ActivityManager(  989): Killing 6206:com.google.android.gms.unstable/u0a24 (adj 15): empty #18
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  989): Recipient 6206
,I/ActivityManager(  989): Killing 5024:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
D/Process (  989): killProcessQuiet, pid=5024
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  989): Recipient 5024,
D/WifiService(  989): Client connection lost with reason: 4
,D/PMS     (  989): acquireWL(28d97ab7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/PMS     (  989): releaseWL(31d11b85): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
V/MusicLeanback( 6637): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/libc    ( 1954): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1954): [NET] android_getaddrinfo_proxy+
D/libc    ( 1954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/AutoSetting( 1589): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 5815): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5815): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1589): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1589): service - onStartCommand() screen is off, don't request location,
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1954): [NET] android_getaddrinfo_proxy-, success
,I/PackageManager(  989):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4228, uid=10024, userID:0,
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,D/ChimeraCfgMgr( 4228): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4228): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4228): [AccountUtils] Account not ready
W/Kids    ( 4228): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4228): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4228): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4228): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4228): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4228): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4228): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4228): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4228): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4228): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1235): reapply : com.google.android.gms 3 40
,D/GCM     ( 1954): Connected
D/PMS     (  989): acquireWL(2d8d849a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): releaseWL(28d97ab7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  989): releaseWL(2d8d849a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): acquireWL(2cc491cb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1954): Message class com.google.f.a.a.p
,D/PMS     (  989): releaseWL(2cc491cb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  989): acquireWL(8a600c1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6637 10159 null,
,I/PackageManager(  989):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6637, uid=10159, userID:0
,D/PMS     (  989): releaseWL(8a600c1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
,I/MusicLeanback( 6637): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6637): Stop autocaching.
,I/ActivityManager(  989): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6787 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 6787): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6787): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6787): VM with version 2.1.0 has multidex support
I/MultiDex( 6787): install
I/MultiDex( 6787): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6787): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6787): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6787): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2073a70: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6787): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1954): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1954): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4228): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 6787): callingUid 10024, callindPid: 6787,
,I/PackageManager(  989):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4228, uid=10024, userID:0
,D/LocationInitializer( 4228): Restart initialization of location,
,E/MDM     ( 1847): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6637): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6637): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  989): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  989): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  989): acquireWL(67eaf33): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 989 1000 null
,D/libc    (  989): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  989): [NET] android_getaddrinfofornet-, err=8
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  989): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  989): [NET] android_getaddrinfo_proxy+
D/libc    (  989): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  989): [NET] android_getaddrinfo_proxy-, success,
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233392e),sn(),hints(known),family 0,flags 4
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  989): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  989): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  989): acquireWL(22eb0b8f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 989 1000 null
D/GpsLocationProvider(  989): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  989): releaseWL(67eaf33): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  989):  [handleDownloadXtraData]inject done.
D/GpsLocationProvider(  989): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
D/PMS     (  989): releaseWL(22eb0b8f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  989): acquireWL(3b33ae1c): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10024}
V/AlarmManager(  989): sending alarm PendingIntent{39b5da25: PendingIntentRecord{188357fa com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=147202, Int=0
,D/PMS     (  989): releaseWL(3b33ae1c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/Process (  989): killProcessQuiet, pid=6285,
I/ActivityManager(  989): Killing 6285:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6285
,D/PMS     (  989): acquireWL(3a16d1ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{1000},
,V/AlarmManager(  989): sending alarm PendingIntent{258ef3a1: PendingIntentRecord{1b9ef9c6 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1450655579597, Int=0
D/PMS     (  989): acquireWL(4db9008): PARTIAL_WAKE_LOCK  *backup* 0x1 989 1000 null
,D/PMS     (  989): releaseWL(3a16d1ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,W/BackupManagerService(  989): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  989): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  989): releaseWL(4db9008): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/ContextImpl(  989): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/AutoSetting( 1589): service - handleMessage() stop self,
,D/AutoSetting( 1589): service - onDestroy() END
,D/AutoSetting( 1589): service - handleMessage() quit looper,
,E/WifiStateMachine(  989): handleMessage: E msg.what=131165
E/WifiStateMachine(  989): processMsg: ConnectedState,
E/WifiStateMachine(  989):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
E/WifiStateMachine(  989):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  989): processMsg: DefaultState
E/WifiStateMachine(  989):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  989): handleMessage: X
,D/PMS     (  989): acquireWL(27eedd87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null,
I/BatteryService(  989): n_update end
D/PMS     (  989): releaseWL(27eedd87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
D/PowerUI ( 1235): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  989): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  989): battery changed pluggedType: 2
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  989): updateBatteryInfo
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/PMS     (  989): runPSCheck
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  989): Checking...
D/UsbnetService(  989): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  989): >> updateStatus
D/WifiController(  989): handleMessage: E msg.what=155652
D/WifiController(  989): processMsg: DeviceActiveState
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
,I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1451): switchBindHtcMsgCursor: null,
,E/WifiStateMachine(  989): handleMessage: E msg.what=131326,
E/WifiStateMachine(  989): processMsg: ConnectedState
E/WifiStateMachine(  989):  ConnectedState what:131326 2 0
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  989): handleMessage: X
,D/PMS     (  989): acquireWL(259da4b4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000}
V/AlarmManager(  989): sending alarm PendingIntent{84e7338: PendingIntentRecord{5d24f11 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=160972, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{238628dd: PendingIntentRecord{3880ec52 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=210774, Int=0
,V/AlarmManager(  989): sending alarm PendingIntent{3051cb23: PendingIntentRecord{3eca5820 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190780, Int=0
,D/PMS     (  989): acquireWL(2bc175d9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  989): releaseWL(259da4b4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1235): Weather sync is On,
W/WeatherTimeKeeper( 1235): [refreshWeatherData] no weather data,
,D/PMS     (  989): acquireWL(121d7b9e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  989): releaseWL(2bc175d9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  989): releaseWL(121d7b9e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): acquireWL(1b970b38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): releaseWL(1b970b38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): acquireWL(2a0b0711): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): releaseWL(2a0b0711): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): acquireWL(aff6076): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): acquireWL(f643677): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): acquireWL(1208034d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  989): releaseWL(aff6076): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1954): Vacuum at: now=1450655630170 tag=VacuumService
,D/PMS     (  989): releaseWL(f643677): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  989): acquireWL(3bdbc313): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1954): Using platform SSLCertificateSocketFactory
,D/PMS     (  989): releaseWL(3bdbc313): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  989): acquireWL(25b40950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): releaseWL(25b40950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1954): No account for auth token provided
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1954): [NET] android_getaddrinfo_proxy+
D/libc    ( 1954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1954): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1954): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1954): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1954): No account for auth token provided,
,W/Uploader( 1954): No account for auth token provided,
,W/Uploader( 1954): No account for auth token provided,
,W/Uploader( 1954):  no longer exists, so no auth token.,
,W/Uploader( 1954): No account for auth token provided,
,D/HtcUPManager( 1235): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1235): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1589): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3f4203ff
I/ActivityManager(  989): Killing 5498:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  989): killProcessQuiet, pid=5498
,D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 5498,
,I/GLSUser ( 1954): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1954): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1954): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1954): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1954): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1235): reapply : com.google.android.gms 4 40
E/Uploader( 1954): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1954): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1954): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1954): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1954): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1954): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  989): releaseWL(1208034d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  989): acquireWL(3dd18d14): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): releaseWL(3dd18d14): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  989): acquireWL(1cad59bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  989): releaseWL(1cad59bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  989): acquireWL(2c54fbb2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
I/BatteryService(  989): n_update end
D/PMS     (  989): releaseWL(2c54fbb2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  989): plugged=true pluggin=true
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1235): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  989): updateBatteryInfo
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
D/WifiController(  989): battery changed pluggedType: 2
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/PMS     (  989): runPSCheck
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  989): Checking...
D/UsbnetService(  989): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  989): >> updateStatus
D/WifiController(  989): handleMessage: E msg.what=155652
D/WifiController(  989): processMsg: DeviceActiveState
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1386): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1386): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a],
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
,I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PMS     (  989): acquireWL(228b9703): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  989): n_update end
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
D/PMS     (  989): releaseWL(228b9703): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1235): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  989): updateBatteryInfo
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/NotificationService(  989): plugged=true pluggin=true
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/PMS     (  989): runPSCheck
D/WifiController(  989): handleMessage: E msg.what=155652
D/HtcPowerSaver(  989): Checking...
D/WifiController(  989): processMsg: DeviceActiveState
I/HtcPowerSaver(  989): >> updateStatus
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): battery changed pluggedType: 2
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  989): acquireWL(cc46680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null,
I/BatteryService(  989): n_update end
,D/PMS     (  989): releaseWL(cc46680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  989): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1235): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  989): plugged=true pluggin=true
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
D/PMS     (  989): runPSCheck
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  989): Checking...
D/UsbnetService(  989): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  989): >> updateStatus
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  989): battery changed pluggedType: 2
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/WifiController(  989): handleMessage: E msg.what=155652
D/WifiController(  989): processMsg: DeviceActiveState
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  989): acquireWL(ddad4b9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000},
V/AlarmManager(  989): sending alarm PendingIntent{84e7338: PendingIntentRecord{5d24f11 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=220972, Int=0
,D/WeatherUtility( 1235): Weather sync is On
,W/WeatherTimeKeeper( 1235): [refreshWeatherData] no weather data
,D/PMS     (  989): releaseWL(ddad4b9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  989): acquireWL(35a6a05f): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10109},
V/AlarmManager(  989): sending alarm PendingIntent{5496aac: PendingIntentRecord{bcb0375 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1450655782736, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{1fc4f0a: PendingIntentRecord{243ee37b com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450655820119, Int=1800000
,D/PMS     (  989): acquireWL(4388598): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4228 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  989): releaseWL(35a6a05f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/PMS     (  989): acquireWL(99851d6): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4228 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  989): releaseWL(4388598): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4228): Aggregate from 1450655509421 (log), 1450654020074 (data)
,D/PMS     (  989): releaseWL(99851d6): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  989): acquireWL(291fb562): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null,
I/BatteryService(  989): n_update end
D/PMS     (  989): releaseWL(291fb562): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  989): plugged=true pluggin=true
I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  989): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  989): runPSCheck
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  989): Checking...
D/UsbnetService(  989): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  989): >> updateStatus
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/WifiController(  989): battery changed pluggedType: 2
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1235): closing low battery warning: level=100
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  989): handleMessage: E msg.what=155652
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  989): processMsg: DeviceActiveState
I/HtcPowerSaver(  989): << updateStatus
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  989): acquireWL(179046f3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000}
V/AlarmManager(  989): sending alarm PendingIntent{84e7338: PendingIntentRecord{5d24f11 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=460972, Int=0
,I/ActivityManager(  989): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6829 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  989): sending alarm PendingIntent{10fe6fb0: PendingIntentRecord{147d5e29 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1450655903528, Int=0
,D/PMS     (  989): releaseWL(179046f3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1235): Weather sync is On
,W/WeatherTimeKeeper( 1235): [refreshWeatherData] no weather data
,E/cutils-trace( 6850): Error opening trace file: Permission denied (13),
I/dex2oat ( 6850): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6850): dex2oat: override thread count:4
,I/dex2oat ( 6850): dex2oat took 697.439ms (threads: 4),
,I/PushClient( 6829): ApplicationMonitor {17e292e0}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6829): ApplicationMonitor {17e292e0}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6829): ApplicationMonitor {17e292e0}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6829): ApplicationMonitor {17e292e0}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6829): ApplicationMonitor {17e292e0}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6829): ApplicationMonitor {17e292e0}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6829): ApplicationMonitor {17e292e0}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6829): ApplicationMonitor {17e292e0}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6829): ApplicationMonitor {17e292e0}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/PushClient( 6829): PnsModel {98f38e3}: update(): Update registration caused by: alarm,
,I/PushClient( 6829): PnsConfigModel {b895136}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6829): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6829): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6829): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6829): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  989): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6857 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6857): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6857 dbg=false s=true
,I/DeviceManagement( 6857): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6857): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6857): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6857): WorkflowService: Starting workflow service
,I/DeviceManagement( 6857): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@98f38e3] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6857): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6857): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6857): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6857): SessionStateController: Checking invariants...
,I/DeviceManagement( 6857): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/art     (  989): Explicit concurrent mark sweep GC freed 31311(1581KB) AllocSpace objects, 4(284KB) LOS objects, 33% free, 16MB/24MB, paused 1.903ms total 166.732ms
,I/DeviceManagement( 6857): SessionStateController: Checking invariants...
,I/DeviceManagement( 6857): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6857): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@98f38e3],
,I/DeviceManagement( 6857): WorkflowService: Stopping workflow service
,D/Process (  989): killProcessQuiet, pid=6350
I/ActivityManager(  989): Killing 6350:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6350
,I/PushClient( 6829): PnsModel {98f38e3}: update(): The registration record has not expired yet. No need to update.
,D/Process (  989): killProcessQuiet, pid=6406
I/ActivityManager(  989): Killing 6406:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6406
,D/WifiService(  989): Client connection lost with reason: 4
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1451): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1451): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1451): sku_id=118
D/ContactMessageStore( 1451): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1451): start background delete task...
,D/ContactMessageStore( 1451): size: 0 , 0,
D/ContactMessageStore( 1451): Background delete complete
,D/PMS     (  989): acquireWL(3ea43b12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
I/BatteryService(  989): n_update end
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  989): releaseWL(3ea43b12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  989): updateBatteryInfo
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/PowerUI ( 1235): closing low battery warning: level=100
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/NotificationService(  989): plugged=true pluggin=true
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  989): runPSCheck
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  989): Checking...
I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  989): >> updateStatus
D/WifiController(  989): handleMessage: E msg.what=155652
D/WifiController(  989): battery changed pluggedType: 2
D/WifiController(  989): processMsg: DeviceActiveState
D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  989): << updateStatus
,I/ActivityManager(  989): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=6886 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true,
,W/ContextImpl( 6886): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 ,
,D/TetherSettings( 4592): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 4592): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4592): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4592): Cust_ConnectToPC   : spcsc>false
D/        ( 4592): Cust_ConnectToPC   : IPT>true
D/        ( 4592): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4592): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 4592): Index of the first 1 = -1
W/ContextImpl( 4592): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 4592): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 ,
W/Settings( 4592): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4592): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4592): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4592): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4592): [ACC]android_networking:tethering_guard_support=false
W/SystemReader( 4592): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,I/ActivityManager(  989): Killing 6464:com.htc.calendar/u0a10 (adj 15): empty #17,
D/Process (  989): killProcessQuiet, pid=6464
,D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6464,
,D/PMS     (  989): acquireWL(162524e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
I/BatteryService(  989): n_update end
D/PMS     (  989): releaseWL(162524e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  989): updateBatteryInfo
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
D/PowerUI ( 1235): closing low battery warning: level=100
I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  989): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  989): runPSCheck
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  989): Checking...
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  989): >> updateStatus
,D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/WifiController(  989): battery changed pluggedType: 2
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/WifiController(  989): handleMessage: E msg.what=155652
D/WifiController(  989): processMsg: DeviceActiveState
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): processMsg: DefaultState
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  989): handleMessage: X
I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  989): acquireWL(244d2399): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
I/BatteryService(  989): n_update end
D/PMS     (  989): releaseWL(244d2399): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  989): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  989): updateBatteryInfo
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/NotificationService(  989): plugged=true pluggin=true
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  989): runPSCheck
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  989): Checking...
D/WifiController(  989): handleMessage: E msg.what=155652
I/HtcPowerSaver(  989): >> updateStatus
D/WifiController(  989): processMsg: DeviceActiveState
D/WifiController(  989): battery changed pluggedType: 2
D/WifiController(  989): processMsg: StaEnabledState
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  989): processMsg: DefaultState
I/HtcPowerSaver(  989): << updateStatus
,D/WifiController(  989): handleMessage: X
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1235): closing low battery warning: level=100
I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true,
,I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  989): acquireWL(1706f65e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  989): n_update end
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
D/PMS     (  989): releaseWL(1706f65e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1235): closing low battery warning: level=100
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/NotificationService(  989): plugged=true pluggin=true
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  989): updateBatteryInfo
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  989): handleMessage: E msg.what=155652
D/PMS     (  989): runPSCheck
D/WifiController(  989): processMsg: DeviceActiveState
D/HtcPowerSaver(  989): Checking...
D/WifiController(  989): processMsg: StaEnabledState
I/HtcPowerSaver(  989): >> updateStatus
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): battery changed pluggedType: 2
D/WifiController(  989): handleMessage: X
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  989): acquireWL(17bbba3f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000},
V/AlarmManager(  989): sending alarm PendingIntent{84e7338: PendingIntentRecord{5d24f11 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=520973, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{1967af0c: PendingIntentRecord{17c36055 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=945584, Int=0
,I/bt-btm  ( 3400): Received oneshot timer event complete,
I/bt-btm  ( 3400): btm_ble_timeout
I/bt-btm  ( 3400): btm_gen_resolvable_private_addr
,D/PMS     (  989): acquireWL(3c481a6a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3400 1002 null,
,D/bt-btm  ( 3400): btm_ble_rand_enc_complete
,I/bt-btm  ( 3400): btm_gen_resolve_paddr_low
D/bt-smp  ( 3400): smp_encrypt_data
W/bt-smp  ( 3400): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3400): Plain text(LSB ~ MSB) = c6 46 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3400): Encrypted text(LSB ~ MSB) = 33 f8 98 53 19 ea 05 7e 29 7c 80 a2 2f 24 ee 6f 
I/bt-btm  ( 3400): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3400): Stopping oneshot timer
D/bt-btm  ( 3400): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  989): releaseWL(17bbba3f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1235): Weather sync is On
W/WeatherTimeKeeper( 1235): [refreshWeatherData] no weather data
,D/PMS     (  989): releaseWL(3c481a6a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  989): acquireWL(3abbbb5b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000},
V/AlarmManager(  989): sending alarm PendingIntent{84e7338: PendingIntentRecord{5d24f11 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1000972, Int=0,
V/AlarmManager(  989): sending alarm PendingIntent{3866aff8: PendingIntentRecord{1f26acd1 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450656436695, Int=0
,D/SmartSyncUtils( 6886): isEpsOn(), nState = 0
,D/WeatherUtility( 1235): Weather sync is On
,W/WeatherTimeKeeper( 1235): [refreshWeatherData] no weather data
,D/PMS     (  989): acquireWL(6c57336): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6886 1000 null,
D/PMS     (  989): releaseWL(3abbbb5b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/PMS     (  989): releaseWL(6c57336): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  989): acquireWL(1cf0b237): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6886 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6886): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6886): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6886): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6886): SettingOnTime = 1450677600000, randomSettingOnTime = 1450674712000
D/SmartSyncScreenOnOffTimeReceiver( 6886): SettingOffTime = 1450742400000, randomSettingOffTime = 1450745812000
D/SmartSyncScreenOnOffTimeReceiver( 6886): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6886): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6886): bNightModeTurnOffOnce = false
,D/PMS     (  989): acquireWL(3652d3a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{1000},
,V/AlarmManager(  989): sending alarm PendingIntent{3298450d: PendingIntentRecord{24ed8cc2 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450656436792, Int=0
D/PMS     (  989): releaseWL(1cf0b237): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6886): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  989): releaseWL(3652d3a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 6886): SMARTSYNC_TURN_OFF_NETWORK, current time = 1450656436824, randomOffTime = 1450745812000, newRandomOffTime = 1450745812000
D/SmartSyncDataLinkTurnOffService( 6886): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 1450674712000, randomMobileOnTime = 1450674712000
,D/SmartSyncUtils( 6886): getMobilePolicyEnabled, result = true,
D/SmartSyncDataLinkTurnOffService( 6886): turnOffMobile bPolicyEnabled = true
,E/WifiTrafficPoller(  989): ADD_CLIENT: 9,
D/WifiService(  989): New client listening to asynchronous messages
,D/SmartSyncUtils( 6886): isWifiHotSpotEnabled = false,
,D/SmartSyncDataLinkTurnOffService( 6886): turnOffMobile bCheckMobileData = false,
,D/LocationManagerService(  989): getProviders()=[gps, network],
D/LocationManagerService(  989): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  989): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1],
D/SmartSyncDataLinkTurnOffService( 6886): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6886): isCharging status = 5,
,D/SmartSyncDataLinkTurnOffService( 6886): turnOffWifi ui setting = true,
D/SmartSyncUtils( 6886): isWifiHotSpotEnabled = false
I/ActivityManager(  989): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6886): Failed to find provider info for com.htc.vowifi,
D/SmartSyncUtils( 6886): state = 0
,D/SmartSyncDataLinkTurnOffService( 6886): turnOffWifi bCheckWifiData = true,
,D/SmartSyncDataLinkTurnOffService( 6886): turnOffWifi bWifiConnected = true,
,D/PMS     (  989): acquireWL(36bb8610): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10024}
V/AlarmManager(  989): sending alarm PendingIntent{31112509: PendingIntentRecord{b8bb30e com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1040019, Int=0
D/PMS     (  989): acquireWL(5ddb12f): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1954 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  989): releaseWL(5ddb12f): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  989): sending alarm PendingIntent{313ba0a2: PendingIntentRecord{a0f133 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=810178, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{4baf33c: PendingIntentRecord{30af0595 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450656386692, Int=0
,W/ContextImpl( 6886): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  989): releaseWL(36bb8610): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6886): MY_DEBUG = false
,D/PowerUsageService( 6886): repeat time = 1450657359088,
,I/PowerUsageList:PowerUsageHelper( 6886): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6886): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  989): acquireWL(1ed3f21a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1954 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1954): Message class com.google.f.a.a.i
,D/PMS     (  989): releaseWL(1ed3f21a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): acquireWL(e1e314b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000}
,V/AlarmManager(  989): sending alarm PendingIntent{84e7338: PendingIntentRecord{5d24f11 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1060972, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{20e20728: PendingIntentRecord{f5b6c41 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450656616937, Int=0
W/ContextImpl( 6886): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncDataLinkTurnOffService( 6886): turnOffWifi ui setting = true
,D/SmartSyncUtils( 6886): isWifiHotSpotEnabled = false
I/ActivityManager(  989): Cannot resolve ContentProvider=com.htc.vowifi
,D/SmartSyncUtils( 6886): state = 0
E/ActivityThread( 6886): Failed to find provider info for com.htc.vowifi
D/SmartSyncDataLinkTurnOffService( 6886): turnOffWifi bCheckWifiData = false
D/SmartSyncDataLinkTurnOffService( 6886): turnOffWifi bWifiConnected = true
D/LocationManagerService(  989): getProviders()=[gps, network]
D/LocationManagerService(  989): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/PMS     (  989): releaseWL(e1e314b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/LocationManagerService(  989): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 6886): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6886): isCharging status = 5
,D/WeatherUtility( 1235): Weather sync is On
W/WeatherTimeKeeper( 1235): [refreshWeatherData] no weather data
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  989): User[0] Flushing usage stats to disk
,D/PMS     (  989): acquireWL(229c9727): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
I/BatteryService(  989): n_update end
D/PMS     (  989): releaseWL(229c9727): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  989): updateBatteryInfo,
D/PMS     (  989): runPSCheck
D/HtcPowerSaver(  989): Checking...
I/HtcPowerSaver(  989): >> updateStatus
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  989): << updateStatus
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/NotificationService(  989): plugged=true pluggin=true
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1235): closing low battery warning: level=100
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/WifiController(  989): handleMessage: E msg.what=155652
I/IntentController( 1235): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiController(  989): processMsg: DeviceActiveState
D/HeadsetStateMachine( 3400): Disconnected process message: 10, size: 0
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): battery changed pluggedType: 2
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
D/PowerUI ( 1235): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1235): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  989): acquireWL(2db18b7d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000}
V/AlarmManager(  989): sending alarm PendingIntent{84e7338: PendingIntentRecord{5d24f11 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1240972, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{2cc6aa72: PendingIntentRecord{1eb17ec3 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1845603, Int=0
,I/bt-btm  ( 3400): Received oneshot timer event complete
,D/PMS     (  989): acquireWL(34049340): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3400 1002 null
I/bt-btm  ( 3400): btm_ble_timeout
I/bt-btm  ( 3400): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3400): btm_ble_rand_enc_complete,
I/bt-btm  ( 3400): btm_gen_resolve_paddr_low
D/bt-smp  ( 3400): smp_encrypt_data
W/bt-smp  ( 3400): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3400): Plain text(LSB ~ MSB) = c0 d6 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3400): Encrypted text(LSB ~ MSB) = 49 dc a1 51 69 49 d2 1c f4 7c f4 e5 60 e7 e6 cb 
I/bt-btm  ( 3400): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3400): Stopping oneshot timer
D/bt-btm  ( 3400): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  989): Prepared write state in 21ms,
,D/PMS     (  989): releaseWL(2db18b7d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1235): Weather sync is On
W/WeatherTimeKeeper( 1235): [refreshWeatherData] no weather data
,I/ProcessStatsService(  989): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-39-49.bin,
,D/PMS     (  989): releaseWL(34049340): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,TIME-OUT KILL (timeout was 1800000ms)
```
