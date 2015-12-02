#### Test 5227736558f1fb0_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
--------- beginning of system,
I/ActivityManager(  964): Killing 5717:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=5717
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  964): Recipient 5717
E/cutils-trace( 6533): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6533): ====startRecUseTime====
D/htc.customization.log.level( 6533):  is 
W/CustomizationLogLevel( 6533): Level value is invalid, use default level 2
D/CustomizationManager( 6533):  Read ACC file spent 0.048 (s)
D/CIDMapFileReader( 6533): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6533): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6533): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6533): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6533): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6533): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6533): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6533): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6533): Parsing tag category name = system
I/CustomizationCIDLoader( 6533): Parsing tag category name = application
I/CustomizationCIDLoader( 6533): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6533): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6533): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6533): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6533): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6533): add string-array item, value = 42507
I/CustomizationCIDLoader( 6533): add string-array item, value = 21902
I/CustomizationCIDLoader( 6533): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6533): add string-array item, value = 23420
I/CustomizationCIDLoader( 6533): add string-array item, value = 22299
I/CustomizationCIDLoader( 6533): add string-array item, value = 24002
I/CustomizationCIDLoader( 6533): add string-array item, value = 23210
I/CustomizationCIDLoader( 6533): add string-array item, value = 23205
I/CustomizationCIDLoader( 6533): add string-array item, value = 23806
I/CustomizationCIDLoader( 6533): add string-array item, value = 23430
I/CustomizationCIDLoader( 6533): add string-array item, value = 23408
I/CustomizationCIDLoader( 6533): add string-array item, value = 27205
I/CustomizationCIDLoader( 6533): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6533): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6533):  Read CID file spent 0.102 (s)
D/CustomizationManager( 6533):  All configurations done spent 0.102 (s)
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6533 on display 0
D/PMS     (  964): acquireHCC(43cd7e9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 964 1000 null
D/PMS     (  964): acquireHCC(3ee71c6e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 964 1000 null
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6551 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
V/ActivityManager(  964): Display changed displayId=0
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1498): [trimMemory] 20
I/WebViewFactory( 6551): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6551): Time to load native libraries: 10 ms (timestamps 1434-1444),
,I/LibraryLoader( 6551): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6551): Binding Chromium to main looper Looper (main, tid 1) {3a4590b1},
I/LibraryLoader( 6551): Expected native library version number "",actual native library version number ""
,I/chromium( 6551): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6551): Initializing chromium process, singleProcess=true,
,W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6551): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6551): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6551): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6551): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 6551): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6551): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6551): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6551): Local Branch: 
I/Adreno-EGL( 6551): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6551): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6551):                  d74aa161a12b9c6fc6332151
,W/System.err(  964): java.lang.Throwable: stack dump
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  964): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@212d9107:true
,D/BluetoothAdapter( 6551): 703694573: getState(). Returning 12
,W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring,
W/AwContents( 6551): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6551): CordovaWebView is running on device made by: HTC
W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  964): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/ActivityManager(  964): Activity pause timeout for ActivityRecord{1e24cf0f u0 com.test.thalitest/.MainActivity t10}
,I/art     (  964): Explicit concurrent mark sweep GC freed 38186(2MB) AllocSpace objects, 3(936KB) LOS objects, 33% free, 16MB/25MB, paused 1.776ms total 135.772ms
,W/chromium( 6551): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  964): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
,D/StatusBarManagerService(  964): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
,D/FindExtension( 6551): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6551): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@24593ba3, mServedView=org.apache.cordova.engine.SystemWebView{2d3c3ea0 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2d7b9a59,
,I/InputMethodManagerService(  964): Disable input method client, pid=1498
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/StatusBarManagerService(  964): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6551): reportFullscreenMode on inactive InputConnection
,D/ContactMessageStore( 1443): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1443): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +779ms (total +824ms),
,W/BindingManager( 6551): Cannot call determinedVisibility() - never saw a connection for the pid: 6551
,D/JsMessageQueue( 6551): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6551): JniHelper::setJavaVM(0xab4448f8), pthread_self() = -1401509336
D/JX-Cordova( 6551): jxcore cordova android initializing
,W/jxcore-log( 6551): Initializing JXcore engine,
W/jxcore-log( 6551): JXcore engine is ready
,W/jxcore-log( 6551): Starting JXcore engine,
,D/PMS     (  964): releaseHCC(43cd7e9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  964): releaseHCC(3ee71c6e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6551): Platform android
W/jxcore-log( 6551): 
W/jxcore-log( 6551): Process ARCH arm
W/jxcore-log( 6551): 
,I/jxcore-log( 6551): JXcore Cordova bridge is ready!
I/jxcore-log( 6551): 
,W/jxcore-log( 6551): JXcore engine is started,
I/Choreographer( 6551): Skipped 97 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6551): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6551): Toggling radios to true
I/jxcore-log( 6551): 
,D/BluetoothAdapter( 6551): enable(): BT is already enabled..!
,D/WifiManager( 6551): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
E/WifiTrafficPoller(  964): ADD_CLIENT: 9
D/WifiService(  964): New client listening to asynchronous messages
D/WifiService(  964): setWifiEnabled: true pid=6551, uid=10366
W/Settings:Agent(  964): MONITOR_LOG
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  964): name: wifi_on
I/WifiService(  964): isSprintWifiRestricted(): false
W/Settings:Agent(  964): value: 2
I/WifiService(  964): isMdmWifiRestricted(): false
W/Settings:Agent(  964): >> traceCallingStack()
W/Settings:Agent(  964): Process.myPid(): 964
W/Settings:Agent(  964): Process.myTid(): 1747
W/Settings:Agent(  964): Process.myUid(): 1000
W/Settings:Agent(  964): 
W/Settings:Agent(  964): 
W/System.err(  964): java.lang.Throwable: stack dump
W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  964): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  964): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  964): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  964): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  964): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  964): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  964): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  964): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  964): 
,W/Settings:Agent(  964): << traceCallingStack(): 15(ms)
D/WifiController(  964): handleMessage: E msg.what=155656
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): handleMessage: X
D/WifiManager( 6551): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  964): handleMessage: E msg.what=131145
E/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiManager( 6551): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  964):  ConnectedState CMD_DISCONNECT 0 0
,E/WifiStateMachine(  964): processMsg: L2ConnectedState
E/WifiStateMachine(  964):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1371): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1371): wlan0: Cancelling scan request
D/wpa_supplicant( 1371): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1371): TDLS: Tear down peers
D/wpa_supplicant( 1371): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6551): Radios toggled
I/jxcore-log( 6551): 
,D/wpa_supplicant( 1371): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 1371): wlan0: Deauthentication notification
,D/wpa_supplicant( 1371): wlan0:  * reason 3 (locally generated)
,D/wpa_supplicant( 1371): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1371): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1371): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1371): enter disconnect check
I/wpa_supplicant( 1371): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
,E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  964): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  964): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  964): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1371): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1371): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  964): interfaceLinkStateChanged wlan0, false
D/Tethering(  964): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  964): interfaceLinkStateChanged wlan0, false
D/Tethering(  964): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  964): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  964): TetherInterfaceSM: wlan0: enter UnavailableState
D/Tethering(  964): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  964): sendTetherStateChangedBroadcast 0, 0, 0
D/PMS     (  964): acquireWL(e9700ef): PARTIAL_WAKE_LOCK  NetworkStats 0x1 964 1000 null
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  964): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  964): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  964): BroadcastReceiver::onReceive-
,D/wpa_supplicant( 1371): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1371): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1371): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1371): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1371): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55aaf4ef88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1371):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1371): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1371): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1371): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1371): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1371): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1371): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1371): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1371): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1371): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1371): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1371): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1371): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
D/wpa_supplicant( 1371): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1371): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1371): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1371): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1371): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1371): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1371): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1371): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  964): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  964): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  964): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/TetherSettings( 4584): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4584): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4584): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4584): Cust_ConnectToPC   : spcsc>false
D/        ( 4584): Cust_ConnectToPC   : IPT>true
D/        ( 4584): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4584): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiMonitor(  964): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/SmartNS_Utility( 4584): hasRemovableStorageSlot: true
E/WifiStateMachine(  964): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/SmartNS_Utility( 4584): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notificatio,n=false
E/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/SmartNS_NSReceiver( 4584): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  964): invokeExitMethods: ConnectedState
E/WifiStateMachine(  964): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  964): release()
E/WifiStateMachine(  964): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  964): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  964): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  964): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  964): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  964): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1371): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1371): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1371): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1371): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1371): Power_Mode_Type mode = 0
I/wpa_supplicant( 1371): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1371): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  964): setDhcpActive: false
W/ContextImpl( 4584): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  964): releaseWL(e9700ef): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/SmartNS_Utility( 4584): setISNotification
V/NativeCrypto( 1886): Read error: ssl=0x55a4c1a400: I/O error during system call, Connection timed out
D/SmartNS_Utility( 4584): usb_cable_connect = 1
,D/SmartNS_Utility( 4584): usb_denied = 0
D/PMS     (  964): acquireWL(206e67fc): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  964): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  964): [NET] android_getaddrinfofornet-, SUCCESS
I/SmartNS_PSService( 4584): usb notificaiton:true
,E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
V/NetworkPolicy(  964): updateNetworkEnabledLocked()
V/NetworkPolicy(  964): updateNotificationsLocked()
E/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  964): setDetailed state send new extra info<unknown ssid>
D/libc    (  964): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  964): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  964): NetworkAgent != null
D/ConnectivityService(  964): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  964): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  964): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NativeCrypto( 1886): SSL shutdown failed: ssl=0x55a4c1a400: I/O error during system call, Broken pipe
V/NetworkPolicy(  964): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  964): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiDataStallTracker(  964): stopDataStallAlarm 
E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiDataStallTracker(  964): ENABLE_DATA_MONITOR_POLL false Token 3
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  964): autoRoamSetBSSID any key="NG700"WPA_PSK
D/ConnectivityService(  964): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiConfigStore(  964): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  964): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): Validated
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1371): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1371): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1371): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/SmartNS_Utility( 4584): usb_cable_connect = 1
,E/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  964): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  964):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  964): Start Disconnecting Watchdog 1
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131146
E/WifiStateMachine(  964): processMsg: DisconnectingState
D/SmartNS_Utility( 4584): usb_denied = 0
I/SmartNS_PSService( 4584): usb notificaiton:true
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  964):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState CMD_RECONNECT 0 0
,W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1371): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1371): Fast associate: Old scan results
D/wpa_supplicant( 1371): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1371): wpa_supplicant_scan enter
D/wpa_supplicant( 1371): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1371): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1371): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1371): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1371): WPS:  * Request Type
D/wpa_supplicant( 1371): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1371): WPS:  * UUID-E
D/wpa_supplicant( 1371): WPS:  * Primary Device Type
D/wpa_supplicant( 1371): WPS:  * RF Bands (3)
D/wpa_supplicant( 1371): WPS:  * Association State
D/wpa_supplicant( 1371): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1371): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1371): WPS:  * Manufacturer
D/wpa_supplicant( 1371): WPS:  * Model Name
D/wpa_supplicant( 1371): WPS:  * Model Number
D/wpa_supplicant( 1371): WPS:  * Device Name
D/wpa_supplicant( 1371): WPS:  * Version2 (0x20)
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/wpa_supplicant( 1371): P2P: * P2P IE header
,D/wpa_supplicant( 1371): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1371): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1371): wlan0: Add radio work 'scan'@0x55aaf51680
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1371): wlan0: First radio work item in the queue - schedule start immediately
D/HTCRequest(  964): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1371): wlan0: Starting radio work 'scan'@0x55aaf51680 after 0.000067 second wait
D/HTCRequest(  964): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1371): wlan0: nl80211: scan request
D/HTCRequest(  964): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  964): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/wpa_supplicant( 1371): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1371): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1371): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1371): wlan0: Own scan request started a scan in 0.000119 seconds
I/wpa_supplicant( 1371): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  964): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  964): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=147460
E/WifiStateMachine(  964): processMsg: DisconnectingState
E/WifiStateMachine(  964):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=134078
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=134079
E/WifiStateMachine(  964): ConnectModeState: Network connection lost 
E/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  964): handleMessage: new destination call exit/enter
E/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  964): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=4
,E/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  964): DisconnectedState call setCountryCode()
E/WifiStateMachine(  964):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1371): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1371): wlan0: Cancelling scan request
D/SmartNS_NSReceiver( 4584): Tethered state change:false isNSOpening:false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
D/PMS     (  964): releaseWL(206e67fc): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
,D/wpa_supplicant( 1371): wlan0: nl80211: sched_scan request
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1,
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1371): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1371): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: Sched scan started
D/WifiP2pService(  964): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): wlan0: nl80211: New scan results available
D/WifiP2pService(  964): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1371): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1371): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1371): wlan0: Scan completed in 0.064349 seconds
D/wpa_supplicant( 1371): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1371): wlan0: BSS: Start scan result update 7,
D/wpa_supplicant( 1371): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1371): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1371): wlan0: Radio work 'scan'@0x55aaf51680 done in 0.065211 seconds
D/wpa_supplicant( 1371): wlan0: No suitable network found
D/wpa_supplicant( 1371): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1371): wlan0: Cancelling sched scan
D/wpa_supplicant( 1371): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1371): wlan0: Cancelling scan request
D/wpa_supplicant( 1371): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1371): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1371): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1371): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1371): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1371): p2p0: No suitable network found
D/wpa_supplicant( 1371): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: Sched scan stopped
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1371): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  964): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=40 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor(  964): WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  964): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131101
E/WifiStateMachine(  964): processMsg: DisconnectedState
E/WifiStateMachine(  964):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  964): processMsg: DriverStartedState
E/WifiStateMachine(  964):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
E/WifiStateMachine(  964):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  964): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  964): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=147462
E/WifiStateMachine(  964): processMsg: DisconnectedState
E/WifiStateMachine(  964):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=134147  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  964): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=134148  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131212
E/WifiStateMachine(  964): processMsg: DisconnectedState
E/WifiStateMachine(  964):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: DriverStartedState
E/WifiStateMachine(  964):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
,E/WifiStateMachine(  964):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  964): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131212
E/WifiStateMachine(  964): processMsg: DisconnectedState
E/WifiStateMachine(  964):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: DriverStartedState
E/WifiStateMachine(  964):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
,E/WifiStateMachine(  964):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  964): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  964): handleMessage: X
D/WifiNetworkAgent(  964): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  964): handleMessage: E msg.what=147462
E/WifiStateMachine(  964): processMsg: DisconnectedState
E/WifiStateMachine(  964):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=134155  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  964): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  964): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  964): NetworkAgent == null
E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  964): processMsg: ConnectModeState
,E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  964):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=134162  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=147461
E/WifiStateMachine(  964): processMsg: DisconnectedState
E/WifiStateMachine(  964):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:86 bcn=0
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:86 bcn=0
E/WifiStateMachine(  964): processMsg: DriverStartedState
,E/WifiStateMachine(  964):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:86 bcn=0
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
E/WifiStateMachine(  964):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:86 bcn=0
D/WifiStateMachine(  964): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1371): wlan0: Control interface command 'LIST_DONGLES'
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  964): [1,449,076,066,230 ms] noteScanEnd no scan source
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1371): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  964): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1ef82c69 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  964): NG7005g c0:ff:d4:d3:aa:4a rssi=-46 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  964): 01ABC c2:ff:d4:d3:aa:48 rssi=-55 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  964): NG700 c0:ff:d4:d3:aa:48 rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  964): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  964): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  964):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-55 freq=2462
E/WifiAutoJoinController (  964): UPC503894600 a0:c5:62:7a:49:97 rssi=-86 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  964): ageScanResultsOut delay 40000 size 4 now 1449076066233
E/WifiAutoJoinController (  964): newSupplicantResults size=4 known=1 true
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1371): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  964): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  964): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  964): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  964): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  964): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  964): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-55,-127) num=(1,0)
E/WifiAutoJoinController (  964): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  964): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  964): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  964): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  964): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-55 freq=2462
D/HtcWifiControlRoamOffload: (  964): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  964): Done attemptAutoJoin status=3
E/WifiConfigStore(  964):  writeKnownNetworkHistory() num networks:1 needWrite=false
,E/WifiStateMachine(  964): handleMessage: X
,E/WifiStateMachine(  964): handleMessage: E msg.what=131215
E/WifiStateMachine(  964): processMsg: DisconnectedState
E/WifiStateMachine(  964):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-55 ;0 ,-127] any roam=0 rt=134173
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-55 ;0 ,-127] any roam=0 rt=134173
E/WifiStateMachine(  964): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  964): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  964): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
,D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
D/WISPrService( 4584): >>>>>WISPrService start isConnected = true<<<<<
D/WifiService(  964): New client listening to asynchronous messages
E/WifiTrafficPoller(  964): ADD_CLIENT: 10
,E/WifiConfigStore(  964): Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=12): [REMOVED],
,W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1371): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  964): will read network variables netId=0
D/ConnectivityService(  964): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/ConnectivityService(  964): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/Nat464Xlat(  964): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/ConnectivityService(  964): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/ConnectivityService(  964): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/NetworkManagementService(  964): Removing idletimer
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/PMS     (  964): acquireWL(112a54da): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 964 1000 null
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/CSLegacyTypeTracker(  964): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/ConnectivityService(  964): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/wpa_supplicant( 1371): wlan0:, Control interface command 'GET_NETWORK 0 wep_key0'
E/ConnectivityService(  964): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
V/NetworkPolicy(  964): ensureActiveMobilePolicyLocked()
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
E/ConnectivityService(  964): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/PMS     (  964): acquireWL(2f7cbd0b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 964 1000 null
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1371): Do not allow key_data field to be exposed
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/PMS     (  964): releaseWL(2f7cbd0b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/NetworkPolicy(  964): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
V/NetworkPolicy(  964): updateNetworkEnabledLocked()
E/WifiConfigStore(  964): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
V/NetworkPolicy(  964): updateIfacesLocked()
E/WifiConfigStore(  964):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  964): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
V/NetworkPolicy(  964): updateNotificationsLocked()
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1371): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1371): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1371): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
E/WifiStateMachine(  964): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
I/SecurityController( 1221): onLost 100
D/wpa_supplicant( 1371): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1371): ENABLE_NETWORK (0)
D/DATA_ICON( 1221): dataConnected: false/false
D/wpa_supplicant( 1371): CTRL_IFACE: ENABLE_NETWORK id=0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1371): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1371): wpa_supplicant_scan enter
D/wpa_supplicant( 1371): wlan0: Starting AP scan for wildcard SSID
V/NetworkPolicy(  964): updateNetworkEnabledLocked()
D/wpa_supplicant( 1371): WPS: Building WPS IE for Probe Request
V/NetworkPolicy(  964): updateNotificationsLocked()
D/wpa_supplicant( 1371): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1371): WPS:  * Request Type
D/wpa_supplicant( 1371): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1371): WPS:  * UUID-E
D/wpa_supplicant( 1371): WPS:  * Primary Device Type
D/wpa_supplicant( 1371): WPS:  * RF Bands (3)
D/wpa_supplicant( 1371): WPS:  * Association State
D/wpa_supplicant( 1371): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1371): WPS:  * Device Password ID (0)
D/NetworkManagementService(  964): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/wpa_supplicant( 1371): WPS:  * Manufacturer
D/wpa_supplicant( 1371): WPS:  * Model Name
D/wpa_supplicant( 1371): WPS:  * Model Number
D/wpa_supplicant( 1371): WPS:  * Device Name
D/wpa_supplicant( 1371): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1371): P2P: * P2P IE header
D/wpa_supplicant( 1371): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1371): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1371): wlan0: Add radio work 'scan'@0x55aaf51680
D/wpa_supplicant( 1371): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1371): wlan0: Starting radio work 'scan'@0x55aaf51680 after 0.000026 second wait
D/wpa_supplicant( 1371): wlan0: nl80211: scan request
D/wpa_supplicant( 1371): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/wpa_supplicant( 1371): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1371): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1371): wlan0: Own scan request started a scan in 0.000059 seconds
I/wpa_supplicant( 1371): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/usbnet  (  964): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiMonitor(  964): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  964): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/usbnet  (  964):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  964): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1371): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  964): will read network variables netId=0
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): Disconnected - quitting
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/Tethering(  964): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1371): Do not allow key_data field to be exposed
D/Tethering(  964): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:2
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1371): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1371): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  964): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  964):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1371): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1371): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1371): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1371): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1371): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1371): wpa_supplicant_scan enter
D/wpa_supplicant( 1371): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1371): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1371): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  964): setLastSelectedConfiguration -1
E/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  964): handleMessage: new destination call exit/enter
E/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1371): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  964): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,E/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  964): DisconnectedState call setCountryCode()
E/WifiStateMachine(  964):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1371): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1371): wlan0: Cancelling scan request
D/wpa_supplicant( 1371): wlan0: nl80211: sched_scan request
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6419): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1371): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1371): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1371): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1371): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1371): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1371): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1371): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1371): wlan0: Scan completed in 0.041500 seconds
D/wpa_supplicant( 1371): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1371): wlan0: BSS: Start scan result update 8
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to no match in scan
E/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to no match in scan
E/WifiStateMachine(  964): handleMessage: E msg.what=131131
E/WifiStateMachine(  964): processMsg: DisconnectedState
D/wpa_supplicant( 1371): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1371): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1371): wlan0: Radio work 'scan'@0x55aaf51680 done in 0.042405 seconds
D/wpa_supplicant( 1371): wlan0: No suitable network found
D/wpa_supplicant( 1371): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1371): wlan0: Cancelling sched scan
D/wpa_supplicant( 1371): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1371): wlan0: Cancelling scan request
D/wpa_supplicant( 1371): p2p0: Updating scan results from sibling
E/WifiStateMachine(  964):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  964): processMsg: ConnectModeState
D/wpa_supplicant( 1371): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1371): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1371): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1371): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1371): p2p0: No suitable network found
E/WifiStateMachine(  964):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WifiP2pService(  964): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): wlan0: nl80211: Sched scan stopped
D/WifiP2pService(  964): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiStateMachine(  964): handleMessage: X
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WIFI    (  964): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
D/WIFI    (  964):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48]
D/WIFI    (  964): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48
E/WifiStateMachine(  964): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  964): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiMonitor(  964): WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  964): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  964): handleMessage: E msg.what=147461
E/WifiStateMachine(  964): processMsg: DisconnectedState
E/WifiStateMachine(  964):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:86 bcn=0
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:86 bcn=0
E/WifiStateMachine(  964): processMsg: DriverStartedState
E/WifiStateMachine(  964):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:86 bcn=0
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
E/WifiStateMachine(  964):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:86 bcn=0
D/WifiStateMachine(  964): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1371): wlan0: Control interface command 'LIST_DONGLES'
I/ActivityManager(  964): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6612 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
E/WifiStateMachine(  964): [1,449,076,066,329 ms] noteScanEnd no scan source
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1371): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
W/WISPrService( 4584): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4584): trigger connection
D/WISPrService( 4584): continue
E/WifiStateMachine(  964): handleMessage: X
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/WISPrService( 4584): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4584): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/FlexNetS( 6419): updateSvcAllowedInSettings:false
D/WISPrService( 4584): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4584): start DataConnection
D/libc    ( 4584): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4584): [NET] android_getaddrinfofornet-, err=8
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/WISPrService( 4584): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4584): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4584): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 4584): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4584): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4584): [NET] android_getaddrinfo_proxy+
D/libc    ( 4584): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/WISPrService( 4584): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7,
D/WISPrService( 4584): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/libc    ( 4584): [NET] android_getaddrinfo_proxy-, NODATA
D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/libc    ( 4584): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 4584): [NET] android_getaddrinfofornet-, err=8
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/WISPrService( 4584): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs,
D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia,
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6419): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6612): [6c.2.]  listen tmrbb8,
,D/MdProvGlob( 6481): remove item 101 (p2d27in222) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 6612): [6c.2.] summary 118:p2 ignore
,D/Process (  964): killProcessQuiet, pid=6090
I/ActivityManager(  964): Killing 6090:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 6090,
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/jxcore-log( 6551): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): my name is : HTC-HTC One M8s_PT4776,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): attempting to connect to test coordinator,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): check test folder
,I/jxcore-log( 6551): 
,I/jxcore-log( 6551): found test : ./testFindPeers.js,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): found test : ./testReConnect.js,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): found test : ./testSendData.js,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): Test app app.js loaded
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/chromium( 6551): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  964): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  964): [AlarmQueuing] connectivity wifi: false
D/PMS     (  964): acquireWL(3079ba94): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 964 1000 null
D/htcCheckinService(  964): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/GpsLocationProvider(  964): [handleMessage] UPDATE_NETWORK_STATE
,D/htcCheckinService(  964): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/GpsLocationProvider(  964): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true,
D/NetworkChangeNotifierAutoDetect( 5029): Network connectivity changed, type is: 6
I/ConnectivityHelper( 1498): [onReceive] WIFI(1): DISCONNECTED
,I/ActivityManager(  964): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6643 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  964): No APN found to select.
,D/PMS     (  964): releaseWL(3079ba94): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6612): [dda.1.]  listen tmrbb8
,D/MdScDataSum( 6612): [dda.1.] summary 118:p1 ignore
,I/MusicStore( 6643): Database version: 120,
,D/VoldConnector(  964): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6643): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  964): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6643): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  964): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6643): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6643): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6643): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 6643): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6643): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6643): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d03fd8c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6643): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6643): GMSCore installation verified,
,I/ConfigStore( 6643): Config Database version: 1,
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6643, uid=10159, userID:0,
,D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: ,
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
,D/MediaRouterService(  964): Client com.google.android.music (pid 6643): Registered
,D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
,I/MediaRouter( 6643): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6643): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6643, uid=10159, userID:0,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/GHttpClientFactory( 6643): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1579): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 5803): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 5803): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1579): Util - no network available!
,I/GoogleURLConnFactory( 6643): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1579): service - onCreate()
,D/AutoSetting( 1579): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  964): request 4b043be passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0],
D/AutoSetting( 1579): service - mHandler: cancel location update
D/AutoSetting( 1579): service -           changes count: 0
,I/iu.Environment( 2200): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2200): num queued entries: 0,
,I/iu.UploadsManager( 2200): num updated entries: 0
,I/iu.SyncManager( 2200): NEXT; no task,
,D/ChimeraCfgMgr( 2200): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6686 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/Babel   ( 6298): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  964): Killing 6171:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  964): killProcessQuiet, pid=6171
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 6171
,D/VoldConnector(  964): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6686): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  964): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6686): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6686): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6686):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6686):   adb logcat -s GAv4
,D/VoldConnector(  964): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6686): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  964): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6686): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6686): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6686): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6686): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6686): [apache-http] Connection GC has been deprecated!
,W/global  ( 6686): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6686): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6686): Time to load native libraries: 3 ms (timestamps 8776-8779),
,I/LibraryLoader( 6686): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6686): Binding Chromium to main looper Looper (main, tid 1) {235ad8df},
,I/LibraryLoader( 6686): Expected native library version number "",actual native library version number "",
,I/chromium( 6686): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6686): Initializing chromium process, singleProcess=true,
,W/art     ( 6686): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6686): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6686): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6686): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6686): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6686): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6686): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6686): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6686): Local Branch: 
I/Adreno-EGL( 6686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6686): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6686):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6686): Requires BLUETOOTH permission,
,I/NSApplication( 6686): Starting up...
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6744 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  964): Killing 5134:com.google.android.gms.wearable/u0a24 (adj 15): empty #17,
D/Process (  964): killProcessQuiet, pid=5134
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiStateMachine(  964): handleMessage: E msg.what=131168
E/WifiStateMachine(  964): processMsg: DisconnectedState
E/WifiStateMachine(  964):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  964): processMsg: ConnectModeState
,E/WifiStateMachine(  964):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  964): processMsg: DriverStartedState
E/WifiStateMachine(  964):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
E/WifiStateMachine(  964):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  964): processMsg: DefaultState,
E/WifiStateMachine(  964):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  964): handleMessage: X
,I/ActivityManager(  964): Recipient 5134
,D/PMS     (  964): acquireWL(3e22befa): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{10024}
V/AlarmManager(  964): sending alarm PendingIntent{3a57acab: PendingIntentRecord{532cf08 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=139195, Int=0
,D/Process (  964): killProcessQuiet, pid=5029,
,I/ActivityManager(  964): Killing 5029:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  964): Recipient 5029,
D/WifiService(  964): Client connection lost with reason: 4
,D/PMS     (  964): acquireWL(2da9d3b4): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1886 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  964): releaseWL(3e22befa): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/libc    ( 1886): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1886): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 1886): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1886): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1886): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1886): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND),
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1886): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  964): releaseWL(2da9d3b4): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,D/BluetoothAdapter( 6551): 703694573: getState(). Returning 12,
,I/jxcore-log( 6551): BLE supported!!,
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(17c63352): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6643 10159 null,
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6643, uid=10159, userID:0,
,I/ActivityManager(  964): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6775 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
D/PMS     (  964): releaseWL(17c63352): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6643): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6643): Stop autocaching.
,W/ResourcesManager( 6775): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6775): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6775): VM with version 2.1.0 has multidex support,
I/MultiDex( 6775): install
I/MultiDex( 6775): VM has multidex support, MultiDex support library is disabled.,
,V/JNIHelp ( 6775): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6775): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6775): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32d1e32: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6775): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1886): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1886): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 2200): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 6775): callingUid 10024, callindPid: 6775
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2200, uid=10024, userID:0,
,D/LocationInitializer( 2200): Restart initialization of location
,E/MDM     ( 1814): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6643): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6643): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  964): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  964): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/Process (  964): killProcessQuiet, pid=6328
I/ActivityManager(  964): Killing 6328:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 6328
,D/PMS     (  964): acquireWL(33bd397c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000},
V/AlarmManager(  964): sending alarm PendingIntent{353300af: PendingIntentRecord{2746ccbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=147935, Int=0
,V/AlarmManager(  964): sending alarm PendingIntent{20fd7205: PendingIntentRecord{3985425a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=148808, Int=0,
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  964): releaseWL(33bd397c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(390dc8b): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{1000},
V/AlarmManager(  964): sending alarm PendingIntent{6627168: PendingIntentRecord{14e82981 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1449076091645, Int=0
D/PMS     (  964): acquireWL(3e452a26): PARTIAL_WAKE_LOCK  *backup* 0x1 964 1000 null
,D/PMS     (  964): releaseWL(390dc8b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  964): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  964): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  964): releaseWL(3e452a26): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6551): 
,W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/AutoSetting( 1579): service - handleMessage() stop self
,D/AutoSetting( 1579): service - handleMessage() quit looper
D/AutoSetting( 1579): service - onDestroy() END
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(15aeb667): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(15aeb667): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  964): Checking...
I/HtcPowerSaver(  964): >> updateStatus
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,D/TelephonyReceiver( 1443): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  964): releaseWL(112a54da): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  964): Failed to find a new network - expiring NetTransition Wakelock
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(31a13c14): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000},
V/AlarmManager(  964): sending alarm PendingIntent{353300af: PendingIntentRecord{2746ccbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=207935, Int=0,
V/AlarmManager(  964): sending alarm PendingIntent{d6cdcbd: PendingIntentRecord{19c9c2b2 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=212302, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{3be65203: PendingIntentRecord{1f600580 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191567, Int=0
D/PMS     (  964): acquireWL(1e8f87b9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1886 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): releaseWL(1e8f87b9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/WeatherUtility( 1221): Weather sync is On,
D/PMS     (  964): releaseWL(31a13c14): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1579): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3fc5e2a9
I/ActivityManager(  964): Killing 5486:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=5486
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 5486
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  964): acquireWL(3e97e675): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  964): n_update end
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  964): releaseWL(3e97e675): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  964): Checking...
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  964): >> updateStatus
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): ,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(2262f60a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
D/UsbnetService(  964): BroadcastReceiver::onReceive+
I/BatteryService(  964): n_update end
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/PMS     (  964): releaseWL(2262f60a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964): BroadcastReceiver::onReceive-
,D/NotificationService(  964): plugged=true pluggin=true
D/PMS     (  964): runPSCheck
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  964): Checking...
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  964): >> updateStatus
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  964): acquireWL(20d5fe7b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000},
,V/AlarmManager(  964): sending alarm PendingIntent{353300af: PendingIntentRecord{2746ccbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=267934, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{68d74f1: PendingIntentRecord{74268d6 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1449076277902, Int=0
,D/PMS     (  964): releaseWL(20d5fe7b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(3ebc0757): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(3ebc0757): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  964): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  964): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  964): Checking...
D/UsbnetService(  964): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  964): >> updateStatus
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  964): battery changed pluggedType: 2
,D/UsbnetService(  964): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  964): handleMessage: E msg.what=155652
I/HtcPowerSaver(  964): << updateStatus
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/ContactMessageStore( 1443): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1443): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1443): sku_id=118
D/ContactMessageStore( 1443): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1443): start background delete task...
,D/ContactMessageStore( 1443): size: 0 , 0
D/ContactMessageStore( 1443): Background delete complete
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  964): acquireWL(495d244): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  964): n_update end
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  964): releaseWL(495d244): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/HtcPowerSaver(  964): updateBatteryInfo
D/PMS     (  964): runPSCheck
D/HtcPowerSaver(  964): Checking...
I/HtcPowerSaver(  964): >> updateStatus
,I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(3e736f2d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  964): n_update end
,D/PMS     (  964): releaseWL(3e736f2d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/PMS     (  964): runPSCheck
D/WifiController(  964): handleMessage: E msg.what=155652
D/HtcPowerSaver(  964): Checking...
D/WifiController(  964): processMsg: DeviceActiveState
I/HtcPowerSaver(  964): >> updateStatus
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  964): handleMessage: X
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  964): << updateStatus
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(2cd43c62): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(2cd43c62): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  964): updateBatteryInfo
D/PMS     (  964): runPSCheck
D/HtcPowerSaver(  964): Checking...
I/HtcPowerSaver(  964): >> updateStatus
,I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  964): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  964): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(168fc1f3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000}
V/AlarmManager(  964): sending alarm PendingIntent{353300af: PendingIntentRecord{2746ccbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=387935, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{d57ff6d: PendingIntentRecord{399927a2 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=809323, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{1d3fceb0: PendingIntentRecord{3144d129 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=945791, Int=0
,I/ActivityManager(  964): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6812 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  964): sending alarm PendingIntent{20bdbcae: PendingIntentRecord{1cda8a4f com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1449076544296, Int=0
,I/bt-btm  ( 3401): Received oneshot timer event complete
I/bt-btm  ( 3401): btm_ble_timeout
I/bt-btm  ( 3401): btm_gen_resolvable_private_addr
,I/art     (  964): Explicit concurrent mark sweep GC freed 41743(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 1.809ms total 191.073ms
,D/PMS     (  964): acquireWL(274b25dc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3401 1002 null
,D/bt-btm  ( 3401): btm_ble_rand_enc_complete
I/bt-btm  ( 3401): btm_gen_resolve_paddr_low
,D/bt-smp  ( 3401): smp_encrypt_data
W/bt-smp  ( 3401): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3401): Plain text(LSB ~ MSB) = 12 60 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3401): Encrypted text(LSB ~ MSB) = 7c cf 34 b5 5b a2 2b 36 67 b7 b0 51 1d 70 0a 3d 
I/bt-btm  ( 3401): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3401): Stopping oneshot timer
,D/bt-btm  ( 3401): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  964): releaseWL(168fc1f3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,E/cutils-trace( 6833): Error opening trace file: Permission denied (13)
I/dex2oat ( 6833): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6833): dex2oat: override thread count:4
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/dex2oat ( 6833): dex2oat took 683.645ms (threads: 4)
,I/PushClient( 6812): ApplicationMonitor {f10ffb3}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6812): ApplicationMonitor {f10ffb3}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6812): ApplicationMonitor {f10ffb3}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6812): ApplicationMonitor {f10ffb3}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6812): ApplicationMonitor {f10ffb3}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6812): ApplicationMonitor {f10ffb3}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
I/PushClient( 6812): ApplicationMonitor {f10ffb3}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6812): ApplicationMonitor {f10ffb3}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6812): ApplicationMonitor {f10ffb3}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6812): PnsModel {3b40d922}: update(): Update registration caused by: alarm
,I/PushClient( 6812): PnsConfigModel {36b0821}: <init>(): Use dm-client for provisioning.
,D/PMS     (  964): releaseWL(274b25dc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,W/System.err( 6812): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6812): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6812): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6812): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  964): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6841 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6841): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6841 dbg=false s=true,
,I/DeviceManagement( 6841): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6841): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6841): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6841): WorkflowService: Starting workflow service
,I/DeviceManagement( 6841): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@29f186ed] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6841): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6841): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6841): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6841): SessionStateController: Checking invariants...
,I/DeviceManagement( 6841): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6841): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6841): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6841): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@29f186ed],
,I/DeviceManagement( 6841): WorkflowService: Stopping workflow service
,D/Process (  964): killProcessQuiet, pid=6394
,I/ActivityManager(  964): Killing 6394:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 6394
,I/PushClient( 6812): PnsModel {3b40d922}: update(): The registration record has not expired yet. No need to update.
,D/Process (  964): killProcessQuiet, pid=6451
I/ActivityManager(  964): Killing 6451:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 6451
,D/WifiService(  964): Client connection lost with reason: 4
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(17575699): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null,
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(17575699): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  964): plugged=true pluggin=true
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  964): Checking...
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  964): >> updateStatus
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): battery changed pluggedType: 2
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  964): processMsg: DeviceActiveState
,D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(1fe8ad5e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000}
V/AlarmManager(  964): sending alarm PendingIntent{353300af: PendingIntentRecord{2746ccbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=987935, Int=0
,V/AlarmManager(  964): sending alarm PendingIntent{2f98a53f: PendingIntentRecord{1411be0c com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449076951195, Int=0
,I/ActivityManager(  964): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=6867 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/art     (  407): Explicit concurrent mark sweep GC freed 8642(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 258us total 49.418ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 191us total 21.562ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 187us total 22.761ms
,D/SmartSyncUtils( 6867): isEpsOn(), nState = 0
,D/PMS     (  964): releaseWL(1fe8ad5e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/PMS     (  964): acquireWL(3cbdc355): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6867 1000 null
I/ActivityManager(  964): Killing 6506:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=6506
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/PMS     (  964): releaseWL(3cbdc355): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  964): acquireWL(170e416a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6867 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6867): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6867): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6867): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6867): SettingOnTime = 1449122400000, randomSettingOnTime = 1449120834000
,D/SmartSyncScreenOnOffTimeReceiver( 6867): SettingOffTime = 1449100800000, randomSettingOffTime = 1449107896000
,D/SmartSyncScreenOnOffTimeReceiver( 6867): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6867): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6867): bNightModeTurnOffOnce = false
,I/ActivityManager(  964): Recipient 6506
,D/PMS     (  964): releaseWL(170e416a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  964): acquireWL(2afc565b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(2afc565b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): BroadcastReceiver::onReceive-
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiController(  964): handleMessage: E msg.what=155652
,D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  964): processMsg: DeviceActiveState
D/PMS     (  964): runPSCheck
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): processMsg: StaEnabledState
D/HtcPowerSaver(  964): Checking...
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  964): >> updateStatus
D/WifiController(  964): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  964): handleMessage: X
,I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(1522aef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(1522aef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  964): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/PMS     (  964): runPSCheck
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  964): Checking...
D/UsbnetService(  964): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  964): >> updateStatus
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(1ce43fd1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
I/BatteryService(  964): n_update end
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  964): releaseWL(1ce43fd1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/PMS     (  964): runPSCheck
D/WifiController(  964): handleMessage: X
D/HtcPowerSaver(  964): Checking...
I/HtcPowerSaver(  964): >> updateStatus
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(5470a36): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(5470a36): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  964): runPSCheck
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  964): Checking...
D/WifiController(  964): handleMessage: E msg.what=155652
I/HtcPowerSaver(  964): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): processMsg: DeviceActiveState
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  964): processMsg: StaEnabledState
I/HtcPowerSaver(  964): << updateStatus
D/WifiController(  964): processMsg: DefaultState
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  964): handleMessage: X
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/UsageStatsService(  964): User[0] Flushing usage stats to disk
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(1ffd37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(1ffd37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  964): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  964): updateBatteryInfo
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  964): Checking...
D/UsbnetService(  964): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  964): >> updateStatus
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(1c4fc2a4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(1c4fc2a4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  964): Checking...
D/WifiController(  964): handleMessage: E msg.what=155652
I/HtcPowerSaver(  964): >> updateStatus
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): processMsg: StaEnabledState
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  964): processMsg: DefaultState
I/HtcPowerSaver(  964): << updateStatus
,D/WifiController(  964): handleMessage: X
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(a1c080d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  964): releaseWL(a1c080d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderNotification, total:1
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=98
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  964): updateBatteryInfo
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  964): Checking...
D/WifiController(  964): handleMessage: E msg.what=155652
I/HtcPowerSaver(  964): >> updateStatus
,D/WifiController(  964): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  964): processMsg: StaEnabledState
I/HtcPowerSaver(  964): updateStatus (8000,98,-1,false,false,false,-1)
D/WifiController(  964): processMsg: DefaultState
I/HtcPowerSaver(  964): << updateStatus
D/WifiController(  964): handleMessage: X
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3401): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 3401): Disconnected process message: 11, size: 0
W/ContextImpl( 6867): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 4584): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4584): Cust_ConnectToPC   : Internet_Sharing>true
W/ContextImpl( 4584): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
D/        ( 4584): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4584): Cust_ConnectToPC   : spcsc>false,
D/        ( 4584): Cust_ConnectToPC   : IPT>true
D/        ( 4584): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4584): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 4584): Index of the first 1 = -1
W/ContextImpl( 4584): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 4584): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4584): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4584): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4584): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4584): [ACC]android_networking:tethering_guard_support=false
W/SystemReader( 4584): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,I/BatteryController( 1221): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(86d35d3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000}
,V/AlarmManager(  964): sending alarm PendingIntent{353300af: PendingIntentRecord{2746ccbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1047935, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{11186510: PendingIntentRecord{308e1809 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449077479901, Int=1800000
,V/AlarmManager(  964): sending alarm PendingIntent{17c92a0e: PendingIntentRecord{151fda17 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449076900036, Int=0
,D/PMS     (  964): acquireWL(4b5c2f): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2200 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/ContextImpl( 6867): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  964): acquireWL(36f1d91a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2200 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): releaseWL(4b5c2f): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): releaseWL(86d35d3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6867): MY_DEBUG = false
,D/PowerUsageService( 6867): repeat time = 1449078379969
,I/EventLogService( 2200): Aggregate from 1449076021434 (log), 1449075679856 (data)
,D/PMS     (  964): releaseWL(36f1d91a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 6867): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6867): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6867): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6867): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 6867): calcPower(), no data
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/PMS     (  964): acquireWL(39c46ce6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/BatteryService(  964): n_update end
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  964): releaseWL(39c46ce6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=99
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: DeviceActiveState
D/HtcPowerSaver(  964): updateBatteryInfo
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
,D/PMS     (  964): runPSCheck
D/HtcPowerSaver(  964): Checking...
I/HtcPowerSaver(  964): >> updateStatus
,I/HtcPowerSaver(  964): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(11b4a227): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(11b4a227): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  964): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  964): plugged=true pluggin=true
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  964): Checking...
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  964): >> updateStatus
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=99
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): battery changed pluggedType: 2
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): processMsg: DefaultState
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  964): handleMessage: X
,I/HtcPowerSaver(  964): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(247b1cd4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000}
V/AlarmManager(  964): sending alarm PendingIntent{353300af: PendingIntentRecord{2746ccbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1587935, Int=0
,V/AlarmManager(  964): sending alarm PendingIntent{d57ff6d: PendingIntentRecord{399927a2 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1665868, Int=0
,V/AlarmManager(  964): sending alarm PendingIntent{2b2c0e7d: PendingIntentRecord{3fda7172 android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1727522, Int=0,
D/HtcSystemUPManager(  964): AlarmScheduler_INEXACT [onReceive] end
D/HtcSystemUPManager(  964): com.htc.upm.AlarmScheduler$SchedulerBase$1@d2c84b0
D/HtcSystemUPManager(  964): UPAlarmListener onAlarmArrival
D/HtcSystemUPManager(  964): UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1449077659600, last = 1449056059587, freq = 21600000
,D/PMS     (  964): releaseWL(247b1cd4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/HtcSystemUPManager(  964): HtcSystemUPHandler sendService() has been called
,D/HtcSystemUPManager(  964): HtcSystemUPDataStore [sendToService] No data needs to be sent to service,
D/HtcSystemUPManager(  964): HtcSystemUPHandler send to UPService takes: 1 ms
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(2ebf39c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null,
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(2ebf39c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  964): updateBatteryInfo
,D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/NotificationService(  964): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  964): runPSCheck
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  964): Checking...
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=99
D/UsbnetService(  964): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  964): >> updateStatus
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  964): handleMessage: E msg.what=155652
,D/WifiController(  964): processMsg: DeviceActiveState
I/HtcPowerSaver(  964): updateStatus (8000,99,-1,false,false,false,-1)
D/WifiController(  964): processMsg: StaEnabledState
I/HtcPowerSaver(  964): << updateStatus
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(1ad73240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
,I/BatteryService(  964): n_update end
,D/PMS     (  964): releaseWL(1ad73240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/NotificationService(  964): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderNotification, total:0
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964): onReceive BATTERY_CHANGED
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: DeviceActiveState
,D/HtcPowerSaver(  964): updateBatteryInfo
D/WifiController(  964): processMsg: StaEnabledState
D/PMS     (  964): runPSCheck
D/WifiController(  964): processMsg: DefaultState
D/HtcPowerSaver(  964): Checking...
D/WifiController(  964): handleMessage: X
,I/HtcPowerSaver(  964): >> updateStatus
D/HeadsetStateMachine( 3401): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3401): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3401): Disconnected process message: 11, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/ContextImpl( 6867): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  964): << updateStatus
,D/TetherSettings( 4584): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4584): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4584): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4584): Cust_ConnectToPC   : spcsc>false
W/ContextImpl( 4584): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
D/        ( 4584): Cust_ConnectToPC   : IPT>true
D/        ( 4584): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4584): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 4584): Index of the first 1 = -1
,W/ContextImpl( 4584): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
W/Settings( 4584): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4584): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4584): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4584): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(3351af1f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 964 1000 WorkSource{1000},
V/AlarmManager(  964): sending alarm PendingIntent{353300af: PendingIntentRecord{2746ccbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1767935, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{e1d326c: PendingIntentRecord{13539035 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1846030, Int=0
I/bt-btm  ( 3401): Received oneshot timer event complete
I/bt-btm  ( 3401): btm_ble_timeout
I/bt-btm  ( 3401): btm_gen_resolvable_private_addr
,D/PMS     (  964): acquireWL(2e82bcca): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3401 1002 null
,I/ProcessStatsService(  964): Prepared write state in 10ms
,D/bt-btm  ( 3401): btm_ble_rand_enc_complete
I/bt-btm  ( 3401): btm_gen_resolve_paddr_low
D/bt-smp  ( 3401): smp_encrypt_data
W/bt-smp  ( 3401): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3401): Plain text(LSB ~ MSB) = e2 32 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3401): Encrypted text(LSB ~ MSB) = 01 ee 94 0f a0 bd 6f 95 e1 aa a5 ec 40 0f a1 ef 
I/bt-btm  ( 3401): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3401): Stopping oneshot timer
D/bt-btm  ( 3401): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  964): releaseWL(3351af1f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/ProcessStatsService(  964): Pruning old procstats: /data/system/procstats/state-2015-12-02-02-14-31.bin
,D/PMS     (  964): releaseWL(2e82bcca): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,D/PMS     (  964): acquireWL(316c1e3b): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{1000},
V/AlarmManager(  964): sending alarm PendingIntent{170e0526: PendingIntentRecord{37edf567 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825935, Int=1800000
D/PMS     (  964): acquireWL(18e10958): PARTIAL_WAKE_LOCK  NetworkStats 0x1 964 1000 null
V/AlarmManager(  964): sending alarm PendingIntent{353300af: PendingIntentRecord{2746ccbc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1887935, Int=0
V/AlarmManager(  964): sending alarm PendingIntent{3ab9fab1: PendingIntentRecord{177db96 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1858518, Int=0
,D/PMS     (  964): releaseWL(18e10958): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  964): updateNetworkEnabledLocked()
V/NetworkPolicy(  964): updateNotificationsLocked()
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  964): releaseWL(316c1e3b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1886): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1886): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1886): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1886): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1886): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1886): Explicit concurrent mark sweep GC freed 14129(756KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 706us total 38.996ms,
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6551): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 6908): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6908): ====startRecUseTime====
D/htc.customization.log.level( 6908):  is 
W/CustomizationLogLevel( 6908): Level value is invalid, use default level 2
D/CustomizationManager( 6908):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6908): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6908): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6908): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6908): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6908): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6908): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6908): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6908): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6908): Parsing tag category name = system
I/CustomizationCIDLoader( 6908): Parsing tag category name = application
I/CustomizationCIDLoader( 6908): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6908): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6908): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6908): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6908): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6908): add string-array item, value = 42507
I/CustomizationCIDLoader( 6908): add string-array item, value = 21902
I/CustomizationCIDLoader( 6908): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6908): add string-array item, value = 23420
I/CustomizationCIDLoader( 6908): add string-array item, value = 22299
I/CustomizationCIDLoader( 6908): add string-array item, value = 24002
I/CustomizationCIDLoader( 6908): add string-array item, value = 23210
I/CustomizationCIDLoader( 6908): add string-array item, value = 23205
I/CustomizationCIDLoader( 6908): add string-array item, value = 23806
I/CustomizationCIDLoader( 6908): add string-array item, value = 23430
I/CustomizationCIDLoader( 6908): add string-array item, value = 23408
I/CustomizationCIDLoader( 6908): add string-array item, value = 27205
I/CustomizationCIDLoader( 6908): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6908): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6908):  Read CID file spent 0.084 (s)
D/CustomizationManager( 6908):  All configurations done spent 0.084 (s)
D/PackageManager(  964): deletePackageAsUser: pkg=com.test.thalitest, pid=6908, uid=2000 userid=0
D/Process (  964): killProcessQuiet, pid=6551
I/ActivityManager(  964): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
I/ActivityManager(  964): Killing 6551:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
W/PackageSettings(  964): Skipping PackageSetting{1cdc87a0 com.example.hello/10373} due to missing metadata
I/ActivityManager(  964): Recipient 6551
I/WindowState(  964): WIN DEATH: Window{1ded5782 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/InputEventReceiver( 1387): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{3a9d69ce uid 10366 pid 6551} (c)'
D/WifiService(  964): Client connection lost with reason: 4
D/Process (  964): killProcessQuiet, pid=5970
I/ActivityManager(  964): Killing 5970:com.google.android.apps.plus/u0a167 (adj 13): empty for 1802s
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  964): Recipient 5970
D/Process (  964): killProcessQuiet, pid=6744
I/ActivityManager(  964): Killing 6744:com.android.chrome/u0a96 (adj 13): empty for 1803s
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  964): Recipient 6744
D/Process (  964): killProcessQuiet, pid=6686
I/ActivityManager(  964): Killing 6686:com.google.android.apps.magazines/u0a161 (adj 13): empty for 1804s
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  964): Recipient 6686
I/ActivityManager(  964): Killing 5803:com.google.android.setupwizard/u0a77 (adj 13): empty for 1804s
D/Process (  964): killProcessQuiet, pid=5803
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  964): Recipient 5803
D/Process (  964): killProcessQuiet, pid=6419
I/ActivityManager(  964): Killing 6419:com.htc.bgp/u0a11 (adj 13): empty for 1804s
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  964): Recipient 6419
D/Process (  964): killProcessQuiet, pid=6612
I/ActivityManager(  964): Killing 6612:com.htc.mobiledata:remote/u0a46 (adj 15): empty for 1805s
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  964): Recipient 6612
D/Process (  964): killProcessQuiet, pid=6481
I/ActivityManager(  964): Killing 6481:com.htc.mobiledata/u0a46 (adj 15): empty for 1805s
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  964): Recipient 6481
I/ActivityManager(  964):   Force finishing activity ActivityRecord{1e24cf0f u0 com.test.thalitest/.MainActivity t10}
I/ActivityManager(  964): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
W/ActivityManager(  964): Spurious death for ProcessRecord{3cde4007 6551:com.test.thalitest/u0a366}, curProc for 6551: null
W/SystemReader(  964): Cannot find grip_rejection_width, use default value instead
D/DotMatrix( 1311): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1311): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1713): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  964): acquireWL(ff68f5d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1814): Ignoring removeGeofence because network location is disabled.
D/PMS     (  964): releaseWL(ff68f5d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1713): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1688): Cleaning up data for package: com.test.thalitest
D/PhoneApp( 1443): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/AccTypeManager( 1713): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1579): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/art     ( 1498): Explicit concurrent mark sweep GC freed 6204(318KB) AllocSpace objects, 7(600KB) LOS objects, 34% free, 29MB/45MB, paused 1.520ms total 148.158ms
D/Prism.PackageStateRece_( 1498): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1498): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1498): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
E/ExternalAccountType( 1713): Unsupported attribute readOnly
I/Launcher( 1498): Deferring update until onResume
D/Launcher( 1498): waitUntilResume // bindAppsRemoved
I/[PluginManager]RegisterService( 1579): handle notify Blinkfeed plugin client changed
I/ActivityManager(  964): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6928 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/art     (  964): Explicit concurrent mark sweep GC freed 30470(2MB) AllocSpace objects, 12(1048KB) LOS objects, 33% free, 16MB/24MB, paused 1.508ms total 254.278ms
I/art     (  964): WaitForGcToComplete blocked for 251.469ms for cause Explicit
D/StatusBarManagerService(  964): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
W/ContextImpl( 6928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  964): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
D/FindExtension( 1498): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/PackageManager(  964): Unable to load service info ResolveInfo{3e332fda com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  964): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  964): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  964): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  964): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  964): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  964): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  964): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  964): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  964): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  964): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  964): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/InputMethodManagerService(  964): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ThreadedRenderer( 1498): Defer allocateBuffers to drawing time
W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 6551 uid 10366
I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6953 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/StatusBarManagerService(  964): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  964): Killing 6298:com.google.android.talk/u0a112 (adj 15): empty for 1804s
D/Process (  964): killProcessQuiet, pid=6298
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager(  964): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     (  964): Explicit concurrent mark sweep GC freed 5798(305KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 3.394ms total 209.768ms
D/JobSchedulerService(  964): Receieved: android.intent.action.PACKAGE_REMOVED
E/libprocessgroup(  964): failed to kill 1 processes for processgroup 6298
I/ActivityManager(  964): Recipient 6298
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
D/TaskPersister(  964): removeObsoleteFile: deleting file=10_task.xml
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6953, uid=10072, userID:0
W/global  ( 6953): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 6953): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 6953): [apache-http] Connection GC has been deprecated!
W/global  ( 6953): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 6953): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  964): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6994 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 6953): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6953): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 6953): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 6953): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 6953): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6953): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6953): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6953): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6953): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 6953): Process: com.android.vending, PID: 6953
E/AndroidRuntime( 6953): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6953): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 6953): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 6953): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 6953): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6953): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6953): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6953): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 6953): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6953): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 6953): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6953): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6953): 	at java.lang.Thread.run(Thread.java:818)
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6953, uid=10072, userID:0
E/ActivityManager(  964): App crashed! Process: com.android.vending
E/AndroidRuntime_2_crash( 6953): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 6953): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 6953): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 6953): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 6953): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 6953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 6953): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 6953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 6953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 6953): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 6953): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 6953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 6953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 6953): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 6953): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 6953): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 6953): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 6953): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 6953): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 6953): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 6953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 6953): 	... 4 more
E/SQLiteDatabase( 6953): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6953): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 6953): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 6953): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6953): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6953): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 6953): killProcess, pid=6953
E/AndroidRuntime_3_crash( 6953): crash in the same process: AsyncTask #2
E/AndroidRuntime_3_crash( 6953): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 6953): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 6953): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 6953): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 6953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 6953): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 6953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 6953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 6953): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 6953): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 6953): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 6953): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 6953): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 6953): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 6953): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 6953): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 6953): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 6953): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 6953): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 6953): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 6953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 6953): 	... 4 more
E/DropBoxManagerService(  964): Can't write: system_app_crash
E/DropBoxManagerService(  964): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  964): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  964): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  964): 	... 5 more
W/ResourcesManager( 6994): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6994): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Process ( 6953): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
I/MultiDex( 6994): VM with version 2.1.0 has multidex support
I/MultiDex( 6994): install
I/MultiDex( 6994): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6994): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 6994): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6994): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32d1e32: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6994): Installed default security provider GmsCore_OpenSSL
E/JavaBinder(  964): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  964): Killing 6643:com.google.android.music:main/u0a159 (adj 15): empty for 1801s
E/lowmemorykiller(  382): Error writing /proc/6953/oom_score_adj; errno=22
D/Process (  964): killProcessQuiet, pid=6643
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager(  964): Recipient 6953
I/ActivityManager(  964): Recipient 6643
D/MediaRouterService(  964): Client com.google.android.music (pid 6643): Died!
I/ActivityManager(  964): Process com.android.vending (pid 6953) has died
D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 5
I/TrimMemoryManager( 1498): [trimMemory] 5
D/ChimeraCfgMgr( 2200): Loading module com.google.android.gms.kids from APK com.google.android.gms
E/SQLiteLog( 1886): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1886): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x55a4800d40
E/AndroidRuntime( 1886): FATAL EXCEPTION: main
E/AndroidRuntime( 1886): Process: com.google.process.gapps, PID: 1886
E/AndroidRuntime( 1886): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1886): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1886): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1886): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1886): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1886): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1886): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1886): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1886): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1886): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1886): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1886): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1886): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1886): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1886): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1886): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1886): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1886): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1886): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1886): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1886): 	... 9 more
E/ActivityManager(  964): App crashed! Process: com.google.process.gapps
D/Process ( 1886): killProcess, pid=1886
E/DropBoxManagerService(  964): Can't write: system_app_crash
E/DropBoxManagerService(  964): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  964): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  964): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  964): 	... 5 more
D/Process ( 1886): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/NativeLibraryUtils( 6994): Failed to open lock file
W/NativeLibraryUtils( 6994): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6994): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 6994): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 6994): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 6994): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6994): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6994): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 6994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 6994): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 6994): 	... 3 more
W/BulkCursor( 6994): Remote process exception when closing
I/ActivityManager(  964): Recipient 1886
I/ActivityManager(  964): Process com.google.process.gapps (pid 1886) has died
W/ActivityManager(  964): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
W/ActivityManager(  964): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
I/ActivityManager(  964): Killing 6994:com.google.android.gms:car/u0a24 (adj 0): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
D/Process (  964): killProcessQuiet, pid=6994
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:15264 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:15341 
I/Prism.ItemManager( 1498): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1498): loadItems() com.htc.launcher.pageview.WidgetManager@33a80640 +
I/Prism.WidgetManager( 1498): onLoadItems() +
W/ResourcesManager( 1498): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  964): Recipient 6994
W/RocketImpressions( 2200): ClearcutLogger connection suspended: 1
W/ResourcesManager( 1498): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  964): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7027 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/PMS     (  964): acquireWL(2803f2dd): PARTIAL_WAKE_LOCK  *alarm* 0x1 964 1000 WorkSource{10072}
V/AlarmManager(  964): sending alarm PendingIntent{319bee52: PendingIntentRecord{76da523 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449077877425, Int=0
D/PMS     (  964): releaseWL(2803f2dd): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}

```
