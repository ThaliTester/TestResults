#### Test 54970261ac9928f_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6447): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6447): ====startRecUseTime====
D/htc.customization.log.level( 6447):  is 
W/CustomizationLogLevel( 6447): Level value is invalid, use default level 2
D/CustomizationManager( 6447):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 6447): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6447): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6447): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6447): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6447): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6447): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6447): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6447): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6447): Parsing tag category name = system
I/CustomizationCIDLoader( 6447): Parsing tag category name = application
I/CustomizationCIDLoader( 6447): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6447): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6447): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6447): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6447): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6447): add string-array item, value = 42507
I/CustomizationCIDLoader( 6447): add string-array item, value = 21902
I/CustomizationCIDLoader( 6447): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6447): add string-array item, value = 23420
I/CustomizationCIDLoader( 6447): add string-array item, value = 22299
I/CustomizationCIDLoader( 6447): add string-array item, value = 24002
I/CustomizationCIDLoader( 6447): add string-array item, value = 23210
I/CustomizationCIDLoader( 6447): add string-array item, value = 23205
I/CustomizationCIDLoader( 6447): add string-array item, value = 23806
I/CustomizationCIDLoader( 6447): add string-array item, value = 23430
I/CustomizationCIDLoader( 6447): add string-array item, value = 23408
I/CustomizationCIDLoader( 6447): add string-array item, value = 27205
I/CustomizationCIDLoader( 6447): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6447): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6447):  Read CID file spent 0.105 (s)
D/CustomizationManager( 6447):  All configurations done spent 0.105 (s)
D/Process (  972): killProcessQuiet, pid=5653
--------- beginning of system
I/ActivityManager(  972): Killing 5653:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  972): Recipient 5653
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6447 on display 0
D/PMS     (  972): acquireHCC(12311c19): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 972 1000 null
D/PMS     (  972): acquireHCC(9cec4de): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 972 1000 null
I/ActivityManager(  972): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6465 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  972): Display changed displayId=0
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1588): [trimMemory] 20
I/WebViewFactory( 6465): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6465): Time to load native libraries: 10 ms (timestamps 774-784),
,I/LibraryLoader( 6465): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6465): Binding Chromium to main looper Looper (main, tid 1) {12df4c42},
I/LibraryLoader( 6465): Expected native library version number "",actual native library version number ""
,I/chromium( 6465): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6465): Initializing chromium process, singleProcess=true,
,W/art     ( 6465): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6465): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6465): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6465): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6465): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6465): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6465): OpenGL ES Shader Compiler Version: E031.25.03.01
,I/Adreno-EGL( 6465): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6465): Local Branch: 
I/Adreno-EGL( 6465): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6465): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6465):                  d74aa161a12b9c6fc6332151
,W/System.err(  972): java.lang.Throwable: stack dump,
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37641342:true,
,D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
,W/art     ( 6465): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6465): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6465): CordovaWebView is running on device made by: HTC,
,W/art     ( 6465): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6465): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6465): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/HtcSystemUPManager(  972): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
,D/StatusBarManagerService(  972): setSystemUiVisibility(0x0),
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  972): hiding MENU key
,D/FindExtension( 6465): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6465): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@22af46ec, mServedView=org.apache.cordova.engine.SystemWebView{32c54ab5 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@37c2254a
I/InputMethodManagerService(  972): Disable input method client, pid=1588,
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6465): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  972): Displayed com.test.thalitest/.MainActivity: +627ms (total +674ms)
,W/BindingManager( 6465): Cannot call determinedVisibility() - never saw a connection for the pid: 6465
,D/JsMessageQueue( 6465): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6465): JniHelper::setJavaVM(0xab3888f8), pthread_self() = -1402350720
,D/JX-Cordova( 6465): jxcore cordova android initializing
,W/jxcore-log( 6465): Initializing JXcore engine
W/jxcore-log( 6465): JXcore engine is ready
W/jxcore-log( 6465): Starting JXcore engine
,W/jxcore-log( 6465): Platform android
W/jxcore-log( 6465): 
W/jxcore-log( 6465): Process ARCH arm
W/jxcore-log( 6465): 
,D/PMS     (  972): releaseHCC(12311c19): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  972): releaseHCC(9cec4de): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null,
,D/ContactMessageStore( 1546): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1546): MSG_NOTIFY_CS_TO_SYNC <<
,I/jxcore-log( 6465): JXcore Cordova bridge is ready!,
I/jxcore-log( 6465): 
,W/jxcore-log( 6465): JXcore engine is started
,I/chromium( 6465): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6465): Toggling radios to true,
I/jxcore-log( 6465): 
,D/BluetoothAdapter( 6465): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  972): ADD_CLIENT: 9,
D/WifiService(  972): New client listening to asynchronous messages
D/WifiManager( 6465): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  972): MONITOR_LOG
D/WifiService(  972): setWifiEnabled: true pid=6465, uid=10366
W/Settings:Agent(  972): name: wifi_on
E/WifiService(  972): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  972): value: 2,
I/WifiService(  972): isSprintWifiRestricted(): false
W/Settings:Agent(  972): >> traceCallingStack()
I/WifiService(  972): isMdmWifiRestricted(): false
W/Settings:Agent(  972): Process.myPid(): 972
W/Settings:Agent(  972): Process.myTid(): 1770
W/Settings:Agent(  972): Process.myUid(): 1000
W/Settings:Agent(  972): 
W/Settings:Agent(  972): 
W/System.err(  972): java.lang.Throwable: stack dump,
,W/System.err(  972): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  972): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,W/System.err(  972): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  972): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  972): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  972): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  972): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  972): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  972): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  972): 
,W/Settings:Agent(  972): << traceCallingStack(): 14(ms)
D/WifiController(  972): handleMessage: E msg.what=155656
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): handleMessage: X
D/WifiManager( 6465): disconnect: Base Package Name=com.test.thalitest, uid=10366
,E/WifiStateMachine(  972): handleMessage: E msg.what=131145
E/WifiStateMachine(  972): processMsg: ConnectedState
D/WifiManager( 6465): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  972):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
D/wpa_supplicant( 1356): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
,D/wpa_supplicant( 1356): TDLS: Tear down peers
D/wpa_supplicant( 1356): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6465): Radios toggled
I/jxcore-log( 6465): 
,D/wpa_supplicant( 1356): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1356): wlan0: Deauthentication notification
D/wpa_supplicant( 1356): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1356): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1356): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1356): enter disconnect check
I/wpa_supplicant( 1356): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,E/WifiMonitor(  972): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  972): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  972): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1356): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1356): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
,D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  972): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  972): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  972): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  972): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
,D/UsbDeviceManager(  972): [USBNET] bCheckSuppFunc: cdc_network
,D/UsbnetService(  972): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  972): acquireWL(3c11709f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
D/wpa_supplicant( 1356): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1356): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a911af88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1356):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1356): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1356): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1356): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1356): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1356): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1356): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1356): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 0->0 (DORMANT)
,D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1356): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1356): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1356): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
E/WifiStateMachine(  972): transitionTo: destState=DisconnectingState
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1356): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine(  972): invokeExitMethods: ConnectedState
E/WifiStateMachine(  972): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  972): release()
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  972): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  972): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  972): invokeExitMethods: L2ConnectedState
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  972): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  972): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  972): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/WifiP2pService(  972): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/PMS     (  972): releaseWL(3c11709f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
V/NetworkPolicy(  972): updateNotificationsLocked()
E/WifiStateMachine(  972): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1356): Power_Mode_Type mode = 0
I/wpa_supplicant( 1356): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  972): setDhcpActive: false
D/TetherSettings( 4570): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4570): Cust_ConnectToPC   : Internet_Sharing>true
V/NativeCrypto( 1941): Read error: ssl=0x559daeb550: I/O error during system call, Connection timed out
,D/PMS     (  972): acquireWL(1db795ec): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1941): SSL shutdown failed: ssl=0x559daeb550: I/O error during system call, Broken pipe
D/        ( 4570): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4570): Cust_ConnectToPC   : spcsc>false
D/        ( 4570): Cust_ConnectToPC   : IPT>true
D/        ( 4570): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4570): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4570): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4570): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4570): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  972): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
V/NetworkPolicy(  972): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  972): setDetailed state send new extra info<unknown ssid>
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  972): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  972): NetworkAgent != null
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Validated
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
W/ContextImpl( 4570): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  972): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
,D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
,D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  972): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  972):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  972): Start Disconnecting Watchdog 1
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131146
E/WifiStateMachine(  972): processMsg: DisconnectingState
E/WifiStateMachine(  972):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
D/WifiDataStallTracker(  972): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  972): stopDataStallAlarm 
E/WifiStateMachine(  972):  ConnectModeState CMD_RECONNECT 0 0
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 14
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
E/WifiDataStallTracker(  972): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/wpa_supplicant( 1356): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1356): Fast associate: Old scan results
D/PMS     (  972): releaseWL(1db795ec): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1356): wlan0: Setting scan request: 0.000000 sec
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1356): wpa_supplicant_scan enter
D/wpa_supplicant( 1356): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1356): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1356): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1356): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1356): WPS:  * Request Type
D/wpa_supplicant( 1356): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1356): WPS:  * UUID-E
D/wpa_supplicant( 1356): WPS:  * Primary Device Type
D/wpa_supplicant( 1356): WPS:  * RF Bands (3)
D/wpa_supplicant( 1356): WPS:  * Association State
D/wpa_supplicant( 1356): WPS:  * Configuration Error (0)
,D/wpa_supplicant( 1356): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1356): WPS:  * Manufacturer
D/wpa_supplicant( 1356): WPS:  * Model Name
D/wpa_supplicant( 1356): WPS:  * Model Number
D/wpa_supplicant( 1356): WPS:  * Device Name
D/wpa_supplicant( 1356): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1356): P2P: * P2P IE header
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1356): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1356): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1356): wlan0: Add radio work 'scan'@0x55a90fd860
D/wpa_supplicant( 1356): wlan0: First radio work item in the queue - schedule start immediately
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  972): handleMessage: X
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  972): handleMessage: E msg.what=147460
D/wpa_supplicant( 1356): wlan0: Starting radio work 'scan'@0x55a90fd860 after 0.000049 second wait
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  972): processMsg: DisconnectingState
D/wpa_supplicant( 1356): wlan0: nl80211: scan request
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/WifiStateMachine(  972):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133175
E/WifiStateMachine(  972): processMsg: ConnectModeState
D/wpa_supplicant( 1356): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1356): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Scan trigger
E/WifiStateMachine(  972):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133175
D/wpa_supplicant( 1356): wlan0: Event SCAN_STARTED (49) received
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1356): wlan0: Own scan request started a scan in 0.000119 seconds
E/WifiStateMachine(  972): ConnectModeState: Network connection lost 
I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  972): transitionTo: destState=DisconnectedState
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  972): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=4
I/SmartNS_Utility( 4570): setISNotification
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  972): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  972): DisconnectedState call setCountryCode()
,E/WifiStateMachine(  972):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1356): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
D/SmartNS_Utility( 4570): usb_cable_connect = 1
D/SmartNS_Utility( 4570): usb_denied = 0
I/SmartNS_PSService( 4570): usb notificaiton:true
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1356): wlan0: nl80211: sched_scan request
D/SmartNS_Utility( 4570): usb_cable_connect = 1
D/SmartNS_Utility( 4570): usb_denied = 0
I/SmartNS_PSService( 4570): usb notificaiton:true
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1223): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 4570): Tethered state change:false isNSOpening:false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/wpa_supplicant( 1356): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
,D/wpa_supplicant( 1356): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1356): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1356): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1356): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1356): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1356): wlan0: Scan completed in 0.042771 seconds
D/wpa_supplicant( 1356): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1356): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
D/wpa_supplicant( 1356): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1356): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1356): wlan0: New scan results available (own=1 ext=0)
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131101
E/WifiStateMachine(  972): processMsg: DisconnectedState
D/wpa_supplicant( 1356): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1356): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1356): wlan0: Radio work 'scan'@0x55a90fd860 done in 0.043853 seconds
D/wpa_supplicant( 1356): wlan0: Selecting BSS from priority group 443
D/wpa_supplicant( 1356): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-60 wps
D/wpa_supplicant( 1356): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1356): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1356): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1356):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1356): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1356): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55a911cc00  current_ssid=0x0
D/wpa_supplicant( 1356): wlan0: Request association with c0:ff:d4:d3:aa:48
E/WifiStateMachine(  972):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1356): wpa_supplicant_set_is_wep_security: 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1356): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1356): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1356): wlan0: Add radio work 'connect'@0x55a90fd860
D/wpa_supplicant( 1356): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1356): wlan0: Starting radio work 'connect'@0x55a90fd860 after 0.000055 second wait
I/wpa_supplicant( 1356): check if in concurrent case
E/WifiStateMachine(  972):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
I/wpa_supplicant( 1356): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  972): processMsg: DriverStartedState,
E/WifiStateMachine(  972):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  972): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  972):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  972): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  972): handleMessage: X
D/WifiMonitor(  972): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=43 dispatchEvent: WPS-AP-AVAILABLE-AUTH 
W/WifiMonitor(  972): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  972): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=44 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  972):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=133220  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  972): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  972): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=133221  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131212
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
D/wpa_supplicant( 1356): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1356): wlan0: Cancelling sched scan
E/WifiStateMachine(  972):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
D/wpa_supplicant( 1356): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
I/RemoteViews( 1223): reapply : com.android.settings 1 36
D/wpa_supplicant( 1356): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1356): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1356): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1356): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1356): wlan0: Automatic auth_alg selection: 0x1
E/WifiStateMachine(  972):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1356): RSN: PMKSA cache search - network_ctx=0x55a911cc00 try_opportunistic=0
E/WifiStateMachine(  972): processMsg: DefaultState
D/wpa_supplicant( 1356): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1356): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1356): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1356): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1356): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1356): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1356): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1356): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1356): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1356): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiStateMachine(  972):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1356): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1356): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
E/WifiStateMachine(  972): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/wpa_supplicant( 1356): nl80211: Set mode ifindex 29 iftype 2 (STATION)
E/WifiStateMachine(  972): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  972): handleMessage: X
D/wpa_supplicant( 1356): nl80211: Unsubscribe mgmt frames handle 0x888888dd21994989 (mode change)
E/WifiStateMachine(  972): handleMessage: E msg.what=131212
E/WifiStateMachine(  972): processMsg: DisconnectedState
D/wpa_supplicant( 1356): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a911c100
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=0104
E/WifiStateMachine(  972):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=040a
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=040b
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=040c
E/WifiStateMachine(  972):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=040d
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=090a
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=090b
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=090c
E/WifiStateMachine(  972):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=090d
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=0409506f9a09
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=7f506f9a09
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=0801
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=040e
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=06
E/WifiStateMachine(  972):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=0a07
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=0a11
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a911c100 match=0a1a
D/wpa_supplicant( 1356): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1356):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356):   * freq=2412
D/wpa_supplicant( 1356):   * freq_hint=2412
D/wpa_supplicant( 1356):   * SSID - hexdump(len=5): 4e 47 37 30 30
E/WifiStateMachine(  972):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1356):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1356):   * WPA Versions 0x2
D/wpa_supplicant( 1356):   * pairwise=0xfac04
D/wpa_supplicant( 1356):   * group=0xfac04
D/wpa_supplicant( 1356):   * akm=0xfac02
D/wpa_supplicant( 1356):   * Auth Type 0
D/wpa_supplicant( 1356): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55a911cc3a
D/wpa_supplicant( 1356): nl80211: Connect request send successfully
D/wpa_supplicant( 1356): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1356): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1356): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1356): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1356): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1356): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  972): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  972): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  972): handleMessage: X
D/WifiNetworkAgent(  972): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=133224  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  972): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  972): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  972): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  972): NetworkAgent == null
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  972): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  972):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=133227  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  972): handleMessage: X
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  972): handleMessage: E msg.what=147461
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  972): processMsg: DisconnectedState
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  972):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:2204 bcn=0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  972):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:2204 bcn=0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:2204 bcn=0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:4
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  972):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:2204 bcn=0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1356): wlan0: Control interface command 'LIST_DONGLES'
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  972): [1,452,269,598,652 ms] noteScanEnd no scan source
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1356): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  972): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@39f5f64b sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  972): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiAutoJoinController (  972): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiConfigStore(  972): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  972): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  972):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  972): UPC503894600 a0:c5:62:7a:49:97 rssi=-81 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  972): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-84 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  972): UPC5999698 64:7c:34:12:7f:81 rssi=-86 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  972): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  972): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-84 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P] is not scored
E/WifiAutoJoinController (  972): ageScanResultsOut delay 40000 size 7 now 1452269598656
E/WifiAutoJoinController (  972): newSupplicantResults size=7 known=1 true
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1356): wlan0: Control interface command 'STATUS-NO_EVENTS'
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:2
E/WifiAutoJoinController (  972): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  972): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  972): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  972): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  972): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  972):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131213
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState CMD_TARGET_BSSID 44 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133236
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_TARGET_BSSID 44 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133236
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_TARGET_BSSID 44 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133237
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_TARGET_BSSID 44 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133237
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=133239  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  972): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  972): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  972): setDetailed state send new extra info0x
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  972): NetworkAgent == null
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=133242  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  972): handleMessage: X
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 19
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 4570): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  972): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  972): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Disconnected - quitting
D/ConnectivityService(  972): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524292
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/usbnet  (  972):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  972): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/usbnet  (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,I/SecurityController( 1223): onLost 100
D/NetworkManagementService(  972): Removing idletimer
E/WifiTrafficPoller(  972): ADD_CLIENT: 10
D/WifiService(  972): New client listening to asynchronous messages
D/PMS     (  972): acquireWL(2bb08c4a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 972 1000 null
D/Tethering(  972): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/CSLegacyTypeTracker(  972): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/Tethering(  972): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  972): acquireWL(302677bb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
V/NetworkPolicy(  972): ensureActiveMobilePolicyLocked()
E/ConnectivityService(  972): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/ConnectivityService(  972): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkPolicy(  972): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateIfacesLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
D/DATA_ICON( 1223): dataConnected: false/false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkManagementService(  972): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/PMS     (  972): releaseWL(302677bb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  972): handleMessage: E msg.what=131131
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  972): handleMessage: X
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/FlexNetS( 6333): updateSvcAllowedInSettings:false
,W/WISPrService( 4570): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/WISPrService( 4570): trigger connection
D/WISPrService( 4570): continue
,D/WISPrService( 4570): start DataConnection
,D/libc    ( 4570): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 4570): [NET] android_getaddrinfofornet-, err=8
D/FlexNetS( 6333): updateSvcAllowedInSettings:false
,D/libc    ( 4570): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    ( 4570): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4570): [NET] android_getaddrinfo_proxy+
D/libc    ( 4570): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 4570): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  972): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6526 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<,
D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
D/FlexNetS( 6333): updateSvcAllowedInSettings:false
D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency,
D/wpa_supplicant( 1356): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1356): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1356): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1356): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1356): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1356): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1356): nl80211: Connect event
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1356): nl80211: Associated on 2412 MHz
D/Tethering(  972): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1356): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1356): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1356): wlan0: Association info event
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1356): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): wlan0: freq=2412 MHz
D/wpa_supplicant( 1356): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1356): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1356): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1356): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1356): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1356): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1356): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1356): TDLS: Remove peers on association
D/wpa_supplicant( 1356): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1356): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1356): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1356): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1356): EAPOL: enable timer tick
D/wpa_supplicant( 1356): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1356): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
I/wpa_supplicant( 1356): htc_wext_set_keepalive +
I/wpa_supplicant( 1356): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1356): getPrivFuncNum +	
I/wpa_supplicant( 1356): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1356): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSI,D=00:00:00:00:00:00 SSID=NG700]
I/wpa_supplicant( 1356): htc_wext_set_keepalive - ret = 0
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1356): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1356): wlan0: Setting authentication timeout: 10 sec 0 usec
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1356): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1356): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1356): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/Tethering(  972): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1356): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1356):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1356):   key_nonce - hexdump(len=32): d3 9b da ff e3 78 51 f8 f6 75 b6 83 5b 98 45 15 91 d8 1a 84 26 13 cd 38 1d ca cc 23 db ca 24 83
D/PMS     (  972): acquireWL(2af65aa2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
D/wpa_supplicant( 1356):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/UsbDeviceManager(  972): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1356):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1356): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1356): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  972): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=47 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  972): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  972): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  972): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  972): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  972): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  972): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  972): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  972): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  972): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1356): WPA: Renewed SNonce - hexdump(len=32): 13 a6 26 60 03 37 c8 b6 ee fa 1d 8c 15 a5 bb 01 a9 8b cb 16 d8 a5 75 4d 62 bb ab 41 1d 88 66 ac
D/wpa_supplicant( 1356): WPA: Nonce1 - hexdump(len=32): 13 a6 26 60 03 37 c8 b6 ee fa 1d 8c 15 a5 bb 01 a9 8b cb 16 d8 a5 75 4d 62 bb ab 41 1d 88 66 ac,
D/wpa_supplicant( 1356): WPA: Nonce2 - hexdump(len=32): d3 9b da ff e3 78 51 f8 f6 75 b6 83 5b 98 45 15 91 d8 1a 84 26 13 cd 38 1d ca cc 23 db ca 24 83
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/wpa_supplicant( 1356): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1356): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1356): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1356): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1356): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1356): WPA: Derived Key MIC - hexdump(len=16): 48 db 90 8b a7 f0 bf 6c f0 53 1e f7 bf 74 10 09
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: DisconnectedState
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/Tethering(  972): interfaceStatusChanged wlan0, false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  972):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=133349  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  972): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  972): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=133350  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  972): interfaceLinkStateChanged wlan0, true
D/Tethering(  972): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=147500
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState what:147500 0 0
V/Tethering(  972): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState what:147500 0 0
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiStateMachine(  972): Enter handleAssociatedWithEvent
D/WifiStateMachine(  972): Associated
D/Tethering(  972): sendTetherStateChangedBroadcast 1, 0, 0
D/FlexNetS( 6333): updateSvcAllowedInSettings:false
D/WifiStateMachine(  972): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  972): Exit handleAssociatedWithEvent
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=133353  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  972): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  972): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/wpa_supplicant( 1356): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1356): wlan0:   EAPOL-Key type=2
E/WifiStateMachine(  972): setDetailed state send new extra info"NG700"
D/wpa_supplicant( 1356): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1356): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1356):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1356):   key_nonce - hexdump(len=32): d3 9b da ff e3 78 51 f8 f6 75 b6 83 5b 98 45 15 91 d8 1a 84 26 13 cd 38 1d ca cc 23 db ca 24 83
D/wpa_supplicant( 1356):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_rsc - hexdump(len=8): 62 33 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_mic - hexdump(len=16): b8 a3 b3 b8 d2 3a b2 50 4b 3c bf 17 30 d4 92 eb
D/wpa_supplicant( 1356): RSN: encrypted key data - hexdump(len=56): d8 ff 51 e8 40 df 40 92 4d 71 0f 3b 5f 54 08 00 bd 61 b4 d7 5e 9d 81 19 38 95 d7 44 7f ed 9d 7c ...
D/wpa_supplicant( 1356): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1356): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1356): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1356): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 22 85 ...
D/wpa_supplicant( 1356): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1356): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1356): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1356): WPA: Derived Key MIC - hexdump(len=16): 85 42 90 0a e6 e5 ce 4e e3 f7 5e 36 58 39 73 1e
D/wpa_supplicant( 1356): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55a911d390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1356): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1356): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1356):    addr=c0:ff:d4:d3:aa:48
E/WifiStateMachine(  972): NetworkAgent == null
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1356): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1356): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1356): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1356): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1356): WPA: RSC - hexdump(len=6): 62 33 00 00 00 00
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x556bcd3e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1356): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1356): nl80211: KEY_SEQ - hexdump(len=6): 62 33 00 00 00 00
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1356):    broadcast key
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  972): processMsg: ConnectModeState
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1356): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1356): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1356): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  972): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 1356): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=50 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1356): wlan0: Radio work 'connect'@0x55a90fd860 done in 0.136308 seconds
W/WifiMonitor(  972): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor(  972): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
I/wpa_supplicant( 1356): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=51 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  972): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine(  972):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=133356  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  972): handleMessage: X
E/wpa_supplicant( 1356): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/wpa_supplicant( 1356): set send_ind_to_ndc = 0
D/UsbnetService(  972): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/wpa_supplicant( 1356): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1356): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1356): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1356): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1356): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1356): EAP: EAP entering state DISABLED
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/wpa_supplicant( 1356): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1356): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1356): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1356): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1356): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/Tethering(  972): interfaceLinkStateChanged wlan0, true
D/Tethering(  972): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 21
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  972): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=53 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  972): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=133369  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  972): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  972): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/PMS     (  972): releaseWL(2af65aa2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=133371  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  972): handleMessage: X
D/FlexNetS( 6333): updateSvcAllowedInSettings:false
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
E/WifiStateMachine(  972): handleMessage: E msg.what=147459
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133372
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133372
E/WifiStateMachine(  972): Network connection established
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
D/WifiStateMachine(  972): fetchFrequency(), freq = 2412
E/WifiStateMachine(  972): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  972): NetworkAgent == null
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 4570): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  972): transitionTo: destState=ObtainingIpState
D/libc    ( 4570): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  972): invokeExitMethods: DisconnectedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1356): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  972): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  972): moveTempStackToStateStack: i=1,j=4
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  972): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  972): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  972): NetworkAgent == null
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/FlexNetS( 6333): updateSvcAllowedInSettings:false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 22
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 23
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 24
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 4570): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  972): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  972): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  972): Got NetworkAgent Messenger
E/WifiStateMachine(  972): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  972): NetworkAgent connected
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
W/ContextImpl( 4570): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/TetherSettings( 4570): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/        ( 4570): Cust_ConnectToPC   : Internet_Sharing>true
D/WifiStateMachine(  972): handlePreDhcpSetup Held wake lock during DHCP
D/        ( 4570): Cust_ConnectToPC   : Modem_Link>false
D/PMS     (  972): acquireWL(17e41187): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 972 1000 null
D/        ( 4570): Cust_ConnectToPC   : spcsc>false
D/WifiStateMachine(  972): handlePreDhcpSetup mBluetoothConnectionActive: false
D/        ( 4570): Cust_ConnectToPC   : IPT>true
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/        ( 4570): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  972): invokeEnterMethods: ObtainingIpState
W/Settings( 4570): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4570): hasRemovableStorageSlot: true
E/WifiStateMachine(  972): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
D/SmartNS_Utility( 4570): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
E/WifiStateMachine(  972): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  972): ObtainingIpAddress "NG700" nid=0
D/SmartNS_NSReceiver( 4570): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  972): Start Dhcp Watchdog 2
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131101
E/WifiStateMachine(  972): processMsg: ObtainingIpState
E/WifiStateMachine(  972):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
I/SmartNS_Utility( 4570): setISNotification
E/WifiStateMachine(  972):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  972): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: ObtainingIpState
E/WifiStateMachine(  972):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=133399  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiP2pService(  972): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b804c90 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  972): processMsg: L2ConnectedState
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b804c90 target=com.android.internal.util.StateMachine$SmHandler }
D/SmartNS_Utility( 4570): usb_cable_connect = 1
E/WifiStateMachine(  972):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=133400  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=133400  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  972): handleMessage: X
D/SmartNS_Utility( 4570): usb_denied = 0
I/SmartNS_PSService( 4570): usb notificaiton:true
E/WifiStateMachine(  972): handleMessage: E msg.what=131212
E/WifiStateMachine(  972): processMsg: ObtainingIpState
E/WifiStateMachine(  972):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  972):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  972): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=196612
E/WifiStateMachine(  972): processMsg: ObtainingIpState
E/WifiStateMachine(  972):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiDataStallTracker(  972): setDhcpActive: true
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/SmartNS_Utility( 4570): usb_cable_connect = 1
D/SmartNS_Utility( 4570): usb_denied = 0
I/SmartNS_PSService( 4570): usb notificaiton:true
E/WifiStateMachine(  972): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  972): do suspend false
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1356): INFO - Deny active power mode because already has gateway
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
D/wpa_supplicant( 1356): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1356): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
E/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  972): Unexpected BatchedScanResults :null
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  972): noteBatchedScanstop()
E/WifiStateMachine(  972): handleMessage: X
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/RemoteViews( 1223): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 4570): Tethered state change:false isNSOpening:false
D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 4570): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4570): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,I/RemoteViews( 1223): reapply : com.android.settings 1 36
,I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
,D/FlexNetS( 6333): updateSvcAllowedInSettings:false
,D/FlexNetS( 6333): updateSvcAllowedInSettings:false
,D/FlexNetS( 6333): updateSvcAllowedInSettings:false,
,D/MdScPhnSt( 6526): [251.2.]  listen tmrbb8
,D/FlexNetS( 6333): updateSvcAllowedInSettings:false
,D/FlexNetS( 6333): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6333): updateSvcAllowedInSettings:false
,D/FlexNetS( 6333): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6333): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6333): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6396): remove item 101 (p2d27in238) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6526): [251.2.] summary 118:p2 ignore
,I/ActivityManager(  972): Killing 6000:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  972): killProcessQuiet, pid=6000
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/dhcpcd  ( 6559): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6559): version 5.5.6 starting
,E/dhcpcd  ( 6559): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6559): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6559): autoip env[11]:autoip=DISABLE
,I/dhcpcd  ( 6559): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6559): wlan0: sending REQUEST (xid 0x41bd39b7), next in 1.63 seconds
,I/ActivityManager(  972): Recipient 6000,
,D/wpa_supplicant( 1356): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1356): EAPOL: disable timer tick
,I/dhcpcd  ( 6559): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6559): wlan0: leased 192.168.1.130 for 86400 seconds,
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/dhcpcd  ( 6559): autoip env[11]:autoip=DISABLE
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  972): handleMessage: E msg.what=131212
E/WifiStateMachine(  972): processMsg: ObtainingIpState
E/WifiStateMachine(  972):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0},
E/WifiStateMachine(  972): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  972): handleMessage: X
,I/dhcpcd  ( 6559): bind_interface: daemonise,
,D/libc    (  972): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  972): handleMessage: E msg.what=196613
E/WifiStateMachine(  972): processMsg: ObtainingIpState
E/WifiStateMachine(  972):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  972): processMsg: L2ConnectedState
,E/WifiStateMachine(  972):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  972): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER POWERMODE 0'
D/WifiP2pService(  972): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): Power_Mode_Type mode = 0
D/PMS     (  972): releaseWL(17e41187): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1356): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WifiP2pService(  972): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  972): setDhcpActive: false
E/WifiStateMachine(  972): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  972): WifiStateMachine DHCP successful
,E/WifiStateMachine(  972): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  972): link address 192.168.1.130/24
E/WifiStateMachine(  972): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  972): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  972): gateway: /192.168.1.1
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
,I/wpa_supplicant( 1356): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1356): htc_wext_set_keepalive +
I/wpa_supplicant( 1356): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1356): getPrivFuncNum +	
I/wpa_supplicant( 1356): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1356): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1356): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1356): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1356): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  972): handleMessage: X
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  972): handleMessage: E msg.what=131210
E/WifiStateMachine(  972): processMsg: ObtainingIpState
E/WifiStateMachine(  972):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1356): environment dirty rate=20 [5][1][0]
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1356): wlan0: Control interface command 'BLACKLIST clear'
V/NetworkPolicy(  972): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/wpa_supplicant( 1356): wlan0: BLACKLIST CLEAR 
D/HtcWifiWanDetect(  972): WAN detection
D/WifiMonitor(  972): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/HtcWifiWanDetect(  972): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=55 dispatchEvent: BLACKLIST CLEAR 
D/ConnectivityService(  972): Adding iface wlan0 to network 101
E/WifiStateMachine(  972): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  972): NetworkAgent != null
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  972): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 25
E/WifiDataStallTracker(  972): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  972): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
,I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,E/WifiStateMachine(  972): transitionTo: destState=ConnectedState
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  972): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  972): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  972): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  972): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 26
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NetworkPolicy(  972): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 4570): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  972): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  972): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  972): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  972): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131131
E/WifiStateMachine(  972): processMsg: ConnectedState
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  972):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  972): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,E/WifiStateMachine(  972): handleMessage: X
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  972): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/WISPrService( 4570): >>>>>WISPrService start isConnected = true<<<<<
D/Nat464Xlat(  972): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  972): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Connected
D/ConnectivityService(  972): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Validated
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  972): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  972): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972): currentScore = 0, newScore = 20
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972):    accepting network in place of null
D/usbnet  (  972):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/usbnet  (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  972): handleMessage: E msg.what=131212
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/CSLegacyTypeTracker(  972): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
E/WifiStateMachine(  972): processMsg: ConnectModeState
D/ConnectivityService(  972): sendGeneralBroadcast, restrictEnable=false
E/WifiStateMachine(  972):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  972): processMsg: DriverStartedState
,E/WifiStateMachine(  972):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  972): sendGeneralBroadcastDelayed, restrictEnable=false
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  972):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
V/NetworkPolicy(  972): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  972): processMsg: DefaultState
D/ConnectivityService(  972): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
E/WifiStateMachine(  972):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/PMS     (  972): acquireWL(16d7bc20): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
,D/Tethering(  972): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  972): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
,D/ConnectivityService(  972): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Validated
D/ConnectivityService(  972): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/ConnectivityService(  972): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  972): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
E/WifiStateMachine(  972): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  972): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  972): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  972): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  972): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/usbnet  (  972):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiStateMachine(  972): handleMessage: X
D/WIFI    (  972): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972): rematching NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIF,I    (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  972): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkPolicy(  972): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateIfacesLocked()
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1223): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  972): identical MTU - not setting
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/Nat464Xlat(  972): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
V/NetworkPolicy(  972): updateNotificationsLocked()
D/ConnectivityService(  972): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/SecurityController( 1223): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/DATA_ICON( 1223): dataConnected: false/false
D/NetworkManagementService(  972): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SecurityController( 1223): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524295
,D/PMS     (  972): releaseWL(16d7bc20): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1223): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524295
,D/DATA_ICON( 1223): dataConnected: false/false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  972): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  972): acquireWL(15ed09d9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 972 1000 null
D/GpsLocationProvider(  972): [handleMessage] UPDATE_NETWORK_STATE
,I/AlarmManager(  972): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  972): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  972): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/ConnectivityHelper( 1588): [onReceive] WIFI(1): CONNECTED
,D/PMS     (  972): releaseWL(2bb08c4a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  972): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  972): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6591 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  972): No APN found to select.
,D/PMS     (  972): releaseWL(15ed09d9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  972): acquireWL(1753aa7f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 972 1000 null
,D/PMS     (  972): releaseWL(1753aa7f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MdScPhnSt( 6526): [687.1.]  listen tmrbb8
,D/MdScDataSum( 6526): [687.1.] summary 118:p1 ignore
,I/MusicStore( 6591): Database version: 120,
,D/VoldConnector(  972): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6591): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  972): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6591): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  972): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6591): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,W/ResourcesManager( 6591): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6591): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6591): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6591): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6591): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11bba2f1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6591): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6591): GMSCore installation verified
,I/ConfigStore( 6591): Config Database version: 1,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6591, uid=10159, userID:0
,D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: ,
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
,D/MediaRouterService(  972): Client com.google.android.music (pid 6591): Registered
,D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
,I/MediaRouter( 6591): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6591): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6591): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6591): type=WIFI subType= reason=null isConnected=true,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6591, uid=10159, userID:0
,D/AutoSetting( 1657): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
D/MobileConnectivityChangeReceiver( 5762): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5762): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1657): service - onCreate()
,I/GHttpClientFactory( 6591): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6591): Using platform SSLCertificateSocketFactory,
,D/LocationManagerService(  972): request f06076 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/AutoSetting( 1657): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/LocationManagerService(  972): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1657): service - onStartCommand() screen is off, don't request location
,D/ChimeraCfgMgr( 2208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  972): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6638 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6211): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 6211): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6211): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6211): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6211): [NET] android_getaddrinfo_proxy+
D/libc    ( 6211): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1941): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1941): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1941): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1941): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6211): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 2208): [AccountUtils] Account not ready
W/Kids    ( 2208): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2208): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2208): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2208): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2208): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2208): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2208): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2208): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/Babel   ( 6211): connection state changed from UNKNOWN to CONNECTED
,I/art     (  972): Explicit concurrent mark sweep GC freed 59073(3MB) AllocSpace objects, 4(388KB) LOS objects, 33% free, 16MB/25MB, paused 1.706ms total 147.032ms
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,D/VoldConnector(  972): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  972): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/,
,W/ContextImpl( 6638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6638): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6638):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6638):   adb logcat -s GAv4
,D/VoldConnector(  972): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  972): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6638): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6638): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6638): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6638): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6638): [apache-http] Connection GC has been deprecated!
,I/ActivityManager(  972): Killing 6161:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=6161
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6161,
,I/WebViewFactory( 6638): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6638): Time to load native libraries: 24 ms (timestamps 7893-7917),
,I/LibraryLoader( 6638): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6638): Binding Chromium to main looper Looper (main, tid 1) {353c8d76},
,I/LibraryLoader( 6638): Expected native library version number "",actual native library version number ""
,I/chromium( 6638): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6638): Initializing chromium process, singleProcess=true,
,W/art     ( 6638): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6638): ApplicationContext is null in ApplicationStatus,
,D/PMS     (  972): acquireWL(4ea6e72): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{10024},
V/AlarmManager(  972): sending alarm PendingIntent{23a3f2c3: PendingIntentRecord{2697f740 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=138002, Int=0
,W/chromium( 6638): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6638): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6638): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6638): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6638): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6638): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6638): Local Branch: 
I/Adreno-EGL( 6638): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6638): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6638):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6638): Requires BLUETOOTH permission
,E/WifiStateMachine(  972): handleMessage: E msg.what=131168,
,E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  972): processMsg: ConnectModeState
,E/WifiStateMachine(  972):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  972): handleMessage: X,
I/NSApplication( 6638): Starting up...
,I/ActivityManager(  972): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6699 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  972): killProcessQuiet, pid=5139
I/ActivityManager(  972): Killing 5139:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/libc    (  972): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  972): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  972): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  972): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  972): [NET] android_getaddrinfo_proxy+
D/libc    (  972): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  972): [NET] android_getaddrinfo_proxy-, success
,D/HtcWifiWanDetect(  972): Find DNS Address www.htc.com/104.81.130.175
,I/ActivityManager(  972): Recipient 5139,
,D/GpsLocationProvider(  972): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
I/AlarmManager(  972): [AlarmQueuing] connectivity wifi: true
,D/PMS     (  972): acquireWL(1ff74896): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 972 1000 null
D/GpsLocationProvider(  972): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  972): acquireWL(2e6bcc17): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 972 1000 null,
D/GpsLocationProvider(  972): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  972): releaseWL(2e6bcc17): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/htcCheckinService(  972): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/ConnectivityHelper( 1588): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 6591): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  972): No APN found to select.
,D/PMS     (  972): releaseWL(1ff74896): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6526): [44d.1.]  listen tmrbb8
,D/MdScDataSum( 6526): [44d.1.] summary 118:p1 ignore
,D/Process (  972): killProcessQuiet, pid=5012
I/ActivityManager(  972): Killing 5012:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/art     ( 5517): Suspending all threads took: 6.457ms,
,I/ActivityManager(  972): Recipient 5012,
D/WifiService(  972): Client connection lost with reason: 4
,D/PMS     (  972): acquireWL(38a6270f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(4ea6e72): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
V/MusicLeanback( 6591): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1941): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1941): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1941): [NET] android_getaddrinfo_proxy+
D/libc    ( 1941): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/MobileConnectivityChangeReceiver( 5762): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 5762): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1657): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1657): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1657): service - onStartCommand() screen is off, don't request location
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1941): [NET] android_getaddrinfo_proxy-, success
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2208, uid=10024, userID:0,
,D/ChimeraCfgMgr( 2208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1941): [NET] android_getaddrinfofornet-, err=8
,D/ChimeraCfgMgr( 2208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1941): [NET] android_getaddrinfofornet-, err=8
,I/GLSUser ( 1941): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1941): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1941): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1941): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 2208): [AccountUtils] Account not ready
W/Kids    ( 2208): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2208): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2208): 	,at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2208): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2208): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2208): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2208): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2208): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
I/RemoteViews( 1223): reapply : com.google.android.gms 2 40
,D/PMS     (  972): acquireWL(2d6a0dd2): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1941 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1941): Connected
D/PMS     (  972): releaseWL(38a6270f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(2d6a0dd2): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  972): acquireWL(28ca0ea3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1941): Message class com.google.f.a.a.p,
D/PMS     (  972): releaseWL(28ca0ea3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6465): Test app app.js loaded,
I/jxcore-log( 6465): 
,I/chromium( 6465): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/PMS     (  972): acquireWL(24b02559): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6591 10159 null,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6591, uid=10159, userID:0
,I/ActivityManager(  972): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6743 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
D/PMS     (  972): releaseWL(24b02559): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6591): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6591): Stop autocaching.
,W/ResourcesManager( 6743): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6743): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6743): VM with version 2.1.0 has multidex support,
I/MultiDex( 6743): install
,I/MultiDex( 6743): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6743): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6743): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6743): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@215ff7f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6743): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1941): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1941): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2208): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 6743): callingUid 10024, callindPid: 6743,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2208, uid=10024, userID:0
,D/LocationInitializer( 2208): Restart initialization of location
,E/MDM     ( 1849): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6591): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6591): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  972): [handleMessage] DOWNLOAD_XTRA_DATA,
,D/GpsLocationProvider(  972): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  972): acquireWL(507950b): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 972 1000 null
,D/libc    (  972): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  972): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024,
D/libc    (  972): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  972): [NET] android_getaddrinfo_proxy+
D/libc    (  972): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  972): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  972): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  972): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  972): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  972): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  972): acquireWL(271876e7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 972 1000 null
D/GpsLocationProvider(  972):  [handleDownloadXtraData]inject done.
D/PMS     (  972): releaseWL(507950b): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/GpsLocationProvider(  972): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  972): releaseWL(271876e7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  972): Killing 6241:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  972): killProcessQuiet, pid=6241
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6241
,D/PMS     (  972): acquireWL(374f3294): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{10024}
,V/AlarmManager(  972): sending alarm PendingIntent{2099d13d: PendingIntentRecord{116cdd32 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=148915, Int=0
,D/PMS     (  972): releaseWL(374f3294): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/PMS     (  972): acquireWL(1d6b9a83): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{1000},
V/AlarmManager(  972): sending alarm PendingIntent{1436e400: PendingIntentRecord{2cd74439 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452269625928, Int=0
D/PMS     (  972): acquireWL(2b879a7e): PARTIAL_WAKE_LOCK  *backup* 0x1 972 1000 null
,D/PMS     (  972): releaseWL(1d6b9a83): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,W/BackupManagerService(  972): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  972): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  972): releaseWL(2b879a7e): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/AutoSetting( 1657): service - handleMessage() stop self
,D/AutoSetting( 1657): service - handleMessage() quit looper
,D/AutoSetting( 1657): service - onDestroy() END
,E/WifiStateMachine(  972): handleMessage: E msg.what=131165,
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  972): processMsg: DriverStartedState,
E/WifiStateMachine(  972):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  972): processMsg: DefaultState
,E/WifiStateMachine(  972):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  972): handleMessage: X
,D/PMS     (  972): acquireWL(15435bdf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): releaseWL(15435bdf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  972): runPSCheck
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  972): Checking...
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1546): switchBindHtcMsgCursor: null,
,E/WifiStateMachine(  972): handleMessage: E msg.what=131326,
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState what:131326 2 0
,E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  972): handleMessage: X
,D/PMS     (  972): acquireWL(126402c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{274b956: PendingIntentRecord{aaf4dd7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=174578, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{32deeaf5: PendingIntentRecord{2fee08a android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=210955, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{23abd6fb: PendingIntentRecord{ccd3318 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191113, Int=0
,D/PMS     (  972): acquireWL(15804171): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(126402c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  972): acquireWL(9f27b56): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): releaseWL(15804171): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  972): releaseWL(9f27b56): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(36cb4d30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(36cb4d30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): acquireWL(2934ada9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(2934ada9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): acquireWL(120d9f2e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(21e0facf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(25017b65): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): releaseWL(120d9f2e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1941): Vacuum at: now=1452269676655 tag=VacuumService
,I/GoogleURLConnFactory( 1941): Using platform SSLCertificateSocketFactory
,D/PMS     (  972): releaseWL(21e0facf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(59c74eb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1941): No account for auth token provided
,D/PMS     (  972): releaseWL(59c74eb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(27ff9248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(27ff9248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1941): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1941): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1941): [NET] android_getaddrinfo_proxy+
D/libc    ( 1941): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605,
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1941): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1941): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1941): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1941): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1941): No account for auth token provided,
,W/Uploader( 1941): No account for auth token provided,
,W/Uploader( 1941): No account for auth token provided,
,W/Uploader( 1941):  no longer exists, so no auth token.,
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1657): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@134bf85a
,I/ActivityManager(  972): Killing 5446:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  972): killProcessQuiet, pid=5446
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5446
,I/GLSUser ( 1941): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1941): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1941): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1941): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,E/Uploader( 1941): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1941): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1941): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1941): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1941): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1941): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1941): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1941): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1941): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1941): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1941): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1941): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1941): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  972): releaseWL(25017b65): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  972): acquireWL(215d448c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(215d448c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): acquireWL(2fe107d5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(2fe107d5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  972): acquireWL(16f16bea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(16f16bea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/HtcPowerSaver(  972): updateBatteryInfo
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: StaEnabledState
,I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/wpa_supplicant( 1356): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 6 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81
,D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 9e:93:4e:3e:ba:c5]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 9e:93:4e:3e:ba:c5
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81
,D/PMS     (  972): acquireWL(34a86edb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
,I/BatteryService(  972): n_update end
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PMS     (  972): releaseWL(34a86edb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: E msg.what=155652
D/PMS     (  972): runPSCheck
D/WifiController(  972): processMsg: DeviceActiveState
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6465): TAP version 13
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # multiplex can send data
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 1 String should be length:200
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # basic
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 2 sane,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # another,
I/jxcore-log( 6465): 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,D/PMS     (  972): acquireWL(15e01d78): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{274b956: PendingIntentRecord{aaf4dd7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=234578, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{34725cb6: PendingIntentRecord{17b51db7 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1452269812587, Int=0
,D/PMS     (  972): releaseWL(15e01d78): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/jxcore-log( 6465): ok 3 sane,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # successfully create a new pkcs12 file and return hash value,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 4 should be equal,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 5 null,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 6 (unnamed assert),
I/jxcore-log( 6465): 
I/jxcore-log( 6465): ok 7 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 8 should not throw
I/jxcore-log( 6465): 
I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # successfully read a previous pkcs12 file and return hash value,
I/jxcore-log( 6465): 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  972): acquireWL(39b59924): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
,I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(39b59924): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  972): Checking...
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 9 (unnamed assert),
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 10 (unnamed assert),
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 11 should not throw
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 12 should be equal,
I/jxcore-log( 6465): 
I/jxcore-log( 6465): ok 13 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # failed to extract public key because of corrupt pkcs12 file,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 14 should be equal,
,I/jxcore-log( 6465): ,
I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # failed to get mobile documents path,
I/jxcore-log( 6465): 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 15 should be equal,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #init should register the peerAvailabilityChanged event,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 16 should be equal,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 17 should be equal,
,I/jxcore-log( 6465): 
I/jxcore-log( 6465): ok 18 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #init should register the networkChanged event,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 19 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #startBroadcasting should throw on null device name
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 20 should throw,
I/jxcore-log( 6465): 
I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #startBroadcasting should throw on empty string device name,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 21 should throw,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #startBroadcasting should throw on non-number port,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 22 should throw,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #startBroadcasting should throw on NaN port,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 23 should throw,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #startBroadcasting should throw on negative port,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 24 should throw
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #startBroadcasting should throw on too large port
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6465): ok 25 should throw,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): ,
,I/jxcore-log( 6465): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6465): ,
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 26 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 27 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 28 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 29 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 30 should be equal
I/jxcore-log( 6465): 
I/jxcore-log( 6465): ok 31 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6465): 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 32 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 33 should be equal,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6465): 
,D/PMS     (  972): acquireWL(3cd35c8d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
,D/PMS     (  972): releaseWL(3cd35c8d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 34 should be equal,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 35 should be equal,
,I/jxcore-log( 6465): 
I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 36 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 37 should be equal
I/jxcore-log( 6465): 
I/jxcore-log( 6465): ok 38 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 39 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 40 should be equal,
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 41 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 42 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6465): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 43 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): ok 44 should be equal
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup
I/jxcore-log( 6465): 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6465): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6465): 
,D/PMS     (  972): acquireWL(2e3f8e42): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/BatteryService(  972): n_update end
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): releaseWL(2e3f8e42): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/NotificationService(  972): plugged=true pluggin=true
D/WifiController(  972): handleMessage: E msg.what=155652
D/PMS     (  972): runPSCheck
D/WifiController(  972): processMsg: DeviceActiveState
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6465): # teardown
I/jxcore-log( 6465): 
,D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962376.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962376.6465","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3412): BTA_JvCreateRecordByUser
D/bt-btm  ( 3412): BTM_AllocateSCN
D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962376.6465
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962376.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962376.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962376.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK
,I/jxcore-log( 6465): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 6465): 
,I/io.jxcore.node.ConnectionHelper( 6465): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
D/WifiP2pService(  972): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2114c4ec target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2114c4ec target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  972): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
I/bt-btif ( 3412): BTA_JvDeleteRecord
I/bt-btif ( 3412): BTA_JvRfcommStopServer
D/bt-btm  ( 3412): BTM_FreeSCN 
D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
I/jxcore-log( 6465): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
,D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
,D/WifiP2pService(  972): add a new client
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323337362e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323337362e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323337362e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323337361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323337361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323337361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
,D/WifiP2pService(  972): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  972): discovery change broadcast true
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  972): InactiveState{ when=-7ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/WifiP2pService(  972): P2pEnabledState{ when=-7ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/WifiP2pService(  972): P2pEnabledState clear service
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1356): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1356): WPS:  * Version (hardcoded 0x10)
D/WifiP2pService(  972): remove client information from framework
D/wpa_supplicant( 1356): WPS:  * Request Type
D/wpa_supplicant( 1356): WPS:  * Config Methods (4388)
D/WifiP2pService(  972): InactiveState{ when=-11ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): WPS:  * UUID-E
D/wpa_supplicant( 1356): WPS:  * Primary Device Type
,D/wpa_supplicant( 1356): WPS:  * RF Bands (3)
D/wpa_supplicant( 1356): WPS:  * Association State
D/wpa_supplicant( 1356): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1356): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1356): WPS:  * Manufacturer
D/WifiP2pService(  972): Stop discovery in Inactive state
D/wpa_supplicant( 1356): WPS:  * Model Name
D/WifiP2pService(  972): mFlushDisabled: false
D/wpa_supplicant( 1356): WPS:  * Model Number
D/wpa_supplicant( 1356): WPS:  * Device Name
D/wpa_supplicant( 1356): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 1356): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1356): P2P: * P2P IE header
D/wpa_supplicant( 1356): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1356): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1356): p2p0: Add radio work 'p2p-scan'@0x55a911d680
D/wpa_supplicant( 1356): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1356): p2p0: Starting radio work 'p2p-scan'@0x55a911d680 after 0.000138 second wait
D/wpa_supplicant( 1356): p2p0: nl80211: scan request
D/wpa_supplicant( 1356): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1356): Scan requested (ret=0) - scan timeout 10 seconds
D/WifiP2pService(  972): InactiveState{ when=-15ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): P2P: Running p2p_scan
,D/WifiP2pService(  972): P2pEnabledState{ when=-15ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/WifiP2pService(  972): P2pEnabledState clear service request
D/wpa_supplicant( 1356): p2p0: nl80211: Scan trigger
D/WifiP2pService(  972): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Event SCAN_STARTED (49) received
D/WifiP2pService(  972): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Own scan request started a scan in 0.000173 seconds
D/WifiP2pService(  972): discovery change broadcast false
,I/wpa_supplicant( 1356): p2p0: CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiMonitor(  972): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=62 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962468.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323337361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323337361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323337361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: Do not consider the scan results after stop_find
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=63 dispatchEvent: P2P-FIND-STOPPED 
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962468.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callin,gUser=0 foregroundUser=0
W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3412): BTA_JvCreateRecordByUser
D/bt-btm  ( 3412): BTM_AllocateSCN
D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962468.6465
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962468.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962468.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962468.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  972): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7e77dfe8 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323436382e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7e77dfe8 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323436382e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  972): P2pEnabledState add service
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323436382e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  972): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323436381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323436381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323436381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
,I/jxcore-log( 6465): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 6465): 
D/WifiP2pService(  972): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: p2p_scan is already running
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
D/WifiP2pService(  972): discovery change broadcast true
I/wpa_supplicant( 1356): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1356): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  972): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6465): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
I/bt-btif ( 3412): BTA_JvDeleteRecord
D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 3412): BTA_JvRfcommStopServer
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
D/bt-btm  ( 3412): BTM_FreeSCN 
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
D/WifiP2pService(  972): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/WifiP2pService(  972): P2pEnabledState clear service
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
,W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323436381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
D/WifiP2pService(  972): remove client information from framework
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323436381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
D/WifiP2pService(  972): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323436381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
,W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  972): Stop discovery in Inactive state
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
D/WifiP2pService(  972): mFlushDisabled: false
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  972): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/WifiP2pService(  972): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  972): P2pEnabledState clear service request
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
,I/jxcore-log( 6465): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
,D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P-FIND-STOPPED 
D/WifiP2pService(  972): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): discovery change broadcast false
,D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962531.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962531.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3412): BTA_JvCreateRecordByUser
,D/bt-btm  ( 3412): BTM_AllocateSCN
D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962531.6465
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962531.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962531.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962531.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323533312e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027",
D/WifiP2pService(  972): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f04e843a target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323533312e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f04e843a target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323533312e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027),
D/WifiP2pService(  972): P2pEnabledState add service
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323533311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  972): add a new client
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323533311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiP2pService(  972): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323533311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65),
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
D/WifiP2pService(  972): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK,
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  972): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/WifiP2pService(  972): P2pEnabledState clear service
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: p2p_scan is already running
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1356): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  972): remove client information from framework
D/wpa_supplicant( 1356): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiP2pService(  972): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  972): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6465): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 6465): 
I/io.jxcore.node.ConnectionHelper( 6465): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
D/WifiP2pService(  972): Stop discovery in Inactive state
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...
D/WifiP2pService(  972): mFlushDisabled: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
D/WifiP2pService(  972): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3412): BTA_JvDeleteRecord
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3412): BTA_JvRfcommStopServer
D/WifiP2pService(  972): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
D/WifiP2pService(  972): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-btm  ( 3412): BTM_FreeSCN 
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
D/WifiP2pService(  972): discovery change broadcast false
D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323533311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323533311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323533311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
,W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6465): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
,D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=67 dispatchEvent: P2P-FIND-STOPPED 
D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962571.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962571.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3412): BTA_JvCreateRecordByUser
D/bt-btm  ( 3412): BTM_AllocateSCN
D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
,I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
,I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962571.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962571.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962571.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962571.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  972): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b4a4b32 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323537312e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
,D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b4a4b32 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323537312e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  972): P2pEnabledState add service
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323537312e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  972): add a new client
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323537311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65",
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323537311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323537311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  972): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: p2p_scan is already running
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1356): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1356): P2P: Failed to start p2p_scan - another p2p_scan was already running
I/jxcore-log( 6465): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 6465): 
D/WifiP2pService(  972): discovery change broadcast true
D/WifiMonitor(  972): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6465): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
I/bt-btif ( 3412): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 3412): BTA_JvRfcommStopServer
D/bt-btm  ( 3412): BTM_FreeSCN 
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
D/WifiP2pService(  972): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
D/WifiP2pService(  972): P2pEnabledState clear service
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/WifiP2pService(  972): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  972): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323537311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323537311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323537311f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  972): Stop discovery in Inactive state
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
D/WifiP2pService(  972): mFlushDisabled: false
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=69 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
I/jxcore-log( 6465): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  972): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/WifiP2pService(  972): P2pEnabledState{ when=-4ms what=139307 arg2=5 target=com.and,roid.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  972): P2pEnabledState clear service request
D/WifiP2pService(  972): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): discovery change broadcast false
D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962612.6465,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962612.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3412): BTA_JvCreateRecordByUser
D/bt-btm  ( 3412): BTM_AllocateSCN
D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962612.6465
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962612.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962612.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962612.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323631322e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  972): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b646643a target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323631322e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b646643a target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323631322e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  972): P2pEnabledState add service
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323631321f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  972): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
D/WifiP2pService(  972): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323631321f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiP2pService(  972): discovery change broadcast true
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323631321f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK
,W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: p2p_scan is already running
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1356): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1356): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  972): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=70 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6465): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 6465): 
I/io.jxcore.node.ConnectionHelper( 6465): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
D/WifiP2pService(  972): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
,D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,I/bt-btif ( 3412): BTA_JvDeleteRecord
D/WifiP2pService(  972): P2pEnabledState clear service
I/bt-btif ( 3412): BTA_JvRfcommStopServer
D/WifiP2pService(  972): remove client information from framework
D/bt-btm  ( 3412): BTM_FreeSCN 
D/WifiP2pService(  972): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
D/WifiP2pService(  972): Stop discovery in Inactive state
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
D/WifiP2pService(  972): mFlushDisabled: false
D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
D/WifiP2pService(  972): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
D/WifiP2pService(  972): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
D/WifiP2pService(  972): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
D/WifiP2pService(  972): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
D/WifiP2pService(  972): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
D/WifiP2pService(  972): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323631321f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323631321f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323631321f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1356): P2P: Stopping find
,D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6465): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962659.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962659.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3412): BTA_JvCreateRecordByUser
D/bt-btm  ( 3412): BTM_AllocateSCN
D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962659.6465
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962659.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962659.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962659.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323635392e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  972): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@adf82be4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323635392e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@adf82be4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323635392e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  972): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
D/WifiP2pService(  972): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323635391f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323635391f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323635391f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65),
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  972): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: p2p_scan is already running
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  972): discovery change broadcast true
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1356): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1356): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  972): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
,E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=72 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6465): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 6465): 
I/io.jxcore.node.ConnectionHelper( 6465): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  972): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/WifiP2pService(  972): P2pEnabledState clear service
I/bt-btif ( 3412): BTA_JvDeleteRecord
D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
,I/bt-btif ( 3412): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
D/bt-btm  ( 3412): BTM_FreeSCN 
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323635391f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323635391f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323635391f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
D/WifiP2pService(  972): remove client information from framework
I/jxcore-log( 6465): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
D/WifiP2pService(  972): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/WifiP2pService(  972): Stop discovery in Inactive state
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
D/WifiP2pService(  972): mFlushDisabled: false
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
,D/WifiP2pService(  972): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/WifiP2pService(  972): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  972): P2pEnabledState clear service request
D/wpa_supplicant( 1356): P2P: Stopping find
D/WifiP2pService(  972): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  972): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/WifiP2pService(  972): discovery change broadcast false
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962707.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962707.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3412): BTA_JvCreateRecordByUser
D/bt-btm  ( 3412): BTM_AllocateSCN
,D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962707.6465
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962707.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962707.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962707.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
D/WifiP2pService(  972): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@adae5af0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@adae5af0 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323730372e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  972): P2pEnabledState add service
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323730372e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  972): add a new client
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323730372e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323730371f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323730371f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323730371f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
,W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  972): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: p2p_scan is already running
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
D/WifiP2pService(  972): discovery change broadcast true
I/wpa_supplicant( 1356): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1356): P2P: Failed to start p2p_scan - another p2p_scan was already running
D/WifiMonitor(  972): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=74 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6465): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 6465): 
,I/io.jxcore.node.ConnectionHelper( 6465): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
I/bt-btif ( 3412): BTA_JvDeleteRecord
I/bt-btif ( 3412): BTA_JvRfcommStopServer
D/bt-btm  ( 3412): BTM_FreeSCN 
D/WifiP2pService(  972): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
D/WifiP2pService(  972): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323730371f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323730371f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323730371f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
D/WifiP2pService(  972): remove client information from framework
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  972): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
I/jxcore-log( 6465): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  972): Stop discovery in Inactive state
D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
D/WifiP2pService(  972): mFlushDisabled: false
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
D/WifiP2pService(  972): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/WifiP2pService(  972): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): P2P: Stopping find
D/WifiP2pService(  972): P2pEnabledState clear service request
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/WifiP2pService(  972): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  972): discovery change broadcast false
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
,D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962758.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962758.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3412): BTA_JvCreateRecordByUser
D/bt-btm  ( 3412): BTM_AllocateSCN
D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962758.6465
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962758.6465","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962758.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962758.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323735382e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  972): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@80155ce4 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323735382e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@80155ce4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323735382e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  972): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
D/WifiP2pService(  972): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323735381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323735381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323735381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  972): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: p2p_scan is already running
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1356): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1356): P2P: Failed to start p2p_scan - another p2p_scan was already running
,I/jxcore-log( 6465): ok 59 Should be able to call startBroadcasting without error,
I/jxcore-log( 6465): 
D/WifiP2pService(  972): discovery change broadcast true
D/WifiMonitor(  972): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WifiP2pService(  972): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6465): stop
D/WifiP2pService(  972): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
D/WifiP2pService(  972): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...
D/WifiP2pService(  972): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  972): Stop discovery in Inactive state
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
D/WifiP2pService(  972): mFlushDisabled: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/WifiP2pService(  972): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
D/WifiP2pService(  972): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3412): BTA_JvDeleteRecord
D/WifiP2pService(  972): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
D/WifiP2pService(  972): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
D/WifiP2pService(  972): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
,D/WifiP2pService(  972): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
I/bt-btif ( 3412): BTA_JvRfcommStopServer
D/bt-btm  ( 3412): BTM_FreeSCN 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323735381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323735381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323735381f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6465): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=77 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962806.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962806.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 3412): BTA_JvCreateRecordByUser
D/bt-btm  ( 3412): BTM_AllocateSCN
D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962806.6465
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962806.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962806.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962806.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  972): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7fcb8bf0 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323830362e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
,D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7fcb8bf0 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323830362e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  972): P2pEnabledState add service
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323830362e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  972): add a new client
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323830361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323830361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323830361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK
D/WifiP2pService(  972): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: p2p_scan is already running
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
I/wpa_supplicant( 1356): p2p0: P2P: Reject scan trigger since one is already pending
D/wpa_supplicant( 1356): P2P: Failed to start p2p_scan - another p2p_scan was already running
I/jxcore-log( 6465): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 6465): 
D/WifiMonitor(  972): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WifiP2pService(  972): discovery change broadcast true
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=78 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6465): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  972): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/WifiP2pService(  972): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
D/WifiP2pService(  972): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
D/WifiP2pService(  972): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3412): BTA_JvDeleteRecord
D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 3412): BTA_JvRfcommStopServer
,D/bt-btm  ( 3412): BTM_FreeSCN 
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323830361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/WifiP2pService(  972): Stop discovery in Inactive state
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323830361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
D/WifiP2pService(  972): mFlushDisabled: false
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323830361f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
D/WifiP2pService(  972): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
D/WifiP2pService(  972): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/WifiP2pService(  972): P2pEnabledState clear service request
,D/wpa_supplicant( 1356): P2P: Stopping find
D/WifiP2pService(  972): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
D/WifiP2pService(  972): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/WifiP2pService(  972): discovery change broadcast false
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=79 dispatchEvent: P2P-FIND-STOPPED 
I/jxcore-log( 6465): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/BluetoothAdapter( 6465): 60418702: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962855.6465
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): bind: Binding a new listener
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962855.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 1356): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 1356): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1356): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1356): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1356): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1356): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1356): p2p0: Scan completed in 0.394157 seconds
D/wpa_supplicant( 1356): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1356): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
D/wpa_supplicant( 1356): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1356): p2p0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 1356): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1356): P2P: Ignore scan results
D/wpa_supplicant( 1356): p2p0: Radio work 'p2p-scan'@0x55a911d680 done in 0.395409 seconds
D/WifiMonitor(  972): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48]
,W/BluetoothAdapter( 6465): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3412): BTA_JvCreateRecordByUser
D/bt-btm  ( 3412): BTM_AllocateSCN
D/bt-sdp  ( 3412): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3412): BTA_JvRfcommStartServer
I/bt-btm  ( 3412): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3412):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): start: OK
I/io.jxcore.node.ConnectionHelper( 6465): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: Peer ID: 90:E7:C4:F6:69:77, peer name: 1452269962855.6465
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6465): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962855.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): start: {"pi":"90:E7:C4:F6:69:77","pn":"1452269962855.6465","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"1452269962855.6465","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  972): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@40d9fb68 target=com.android.internal.util.StateMachine$SmHandler },
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323835352e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@40d9fb68 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323835352e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
D/WifiP2pService(  972): P2pEnabledState add service,
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22313435323236393936323835352e36343635222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
D/WifiP2pService(  972): add a new client
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323835351f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
D/WifiP2pService(  972): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323835351f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65'
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_ADD bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323835351f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/WifiP2pService(  972): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): start: OK
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1356): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1356): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1356): P2P: Starting find (type=0)
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1356): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1356): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1356): WPS:  * Request Type
D/wpa_supplicant( 1356): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1356): WPS:  * UUID-E
D/wpa_supplicant( 1356): WPS:  * Primary Device Type
D/wpa_supplicant( 1356): WPS:  * RF Bands (3)
D/WifiP2pService(  972): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): WPS:  * Association State
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): WPS:  * Configuration Error (0)
D/WifiP2pService(  972): P2pEnabledState clear service
D/wpa_supplicant( 1356): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1356): WPS:  * Manufacturer
D/wpa_supplicant( 1356): WPS:  * Model Name
D/wpa_supplicant( 1356): WPS:  * Model Number
D/wpa_supplicant( 1356): WPS:  * Device Name
D/wpa_supplicant( 1356): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1356): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1356): P2P: * P2P IE header
D/wpa_supplicant( 1356): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1356): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1356): p2p0: Add radio work 'p2p-scan'@0x55a90fd860
D/wpa_supplicant( 1356): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1356): p2p0: Starting radio work 'p2p-scan'@0x55a90fd860 after 0.000114 second wait
D/WifiP2pService(  972): remove client information from framework
D/wpa_supplicant( 1356): p2p0: nl80211: scan request
D/wpa_supplicant( 1356): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1356): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1356): P2P: Running p2p_scan,
D/wpa_supplicant( 1356): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1356): p2p0: nl80211: Scan trigger
D/WifiP2pService(  972): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1356): p2p0: Own scan request started a scan in 0.000126 seconds
I/wpa_supplicant( 1356): p2p0: CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 6465): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6465): 
D/WifiMonitor(  972): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=81 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/io.jxcore.node.ConnectionHelper( 6465): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): stop: Stopping Bluetooth...
D/WifiP2pService(  972): Stop discovery in Inactive state
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): Shutting down...
D/WifiP2pService(  972): mFlushDisabled: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6465): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6465): onServerStopped
I/bt-btif ( 3412): BTA_JvDeleteRecord
I/bt-btif ( 3412): BTA_JvRfcommStopServer
D/bt-btm  ( 3412): BTM_FreeSCN 
D/WifiP2pService(  972): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-sdp  ( 3412): SDP_DeleteRecord ok, num_records:15
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3412): BTM_SEC_CLR[19]: id 61
D/WifiP2pService(  972): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6465): setState: NOT_STARTED
D/WifiP2pService(  972): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stop: Stopping peer discovery...
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6465): stop: Stopping services
D/WifiP2pService(  972): P2pEnabledState clear service request
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): stop: Stopping P2P device discovery...
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6465): release: No more listeners, de-initializing...
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323835351f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323835351f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001'
I/wpa_supplicant( 1356): [p2p command] (P2P_SERVICE_DEL bonjour 2d7b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22313435323236393936323835351f36343635222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6465): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6465): setState: NOT_STARTED
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_STOP_FIND"
,D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_STOP_FIND'
I/wpa_supplicant( 1356): [p2p command] (P2P_STOP_FIND)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=SEARCH)
I/wpa_supplicant( 1356): P2P-FIND-STOPPED 
D/wpa_supplicant( 1356): P2P: State SEARCH -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: Do not consider the scan results after stop_find
D/WifiMonitor(  972): Event [P2P-FIND-STOPPED ]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=82 dispatchEvent: P2P-FIND-STOPPED 
W/WifiHW  (  972): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 1356): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 1356): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1356): P2P: Stopping find
D/wpa_supplicant( 1356): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1356): P2P: State IDLE -> IDLE
D/wpa_supplicant( 1356): wpa_driver_set_ap_wps_p2p_ie: Entry
I/jxcore-log( 6465): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6465): 
,I/jxcore-log( 6465): # setup,
I/jxcore-log( 6465): 
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6465): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6465): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6465): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6465): Service requests cleared successfully
,D/wpa_supplicant( 1356): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0
D/wpa_supplicant( 1356): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1356): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1356): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1356): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1356): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1356): p2p0: Scan completed in 0.400793 seconds
D/wpa_supplicant( 1356): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1356): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1356): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-84
D/wpa_supplicant( 1356): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1356): p2p0: BSS: Add new id 1 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 1356): BSS: last_scan_res_used=2/32
,D/wpa_supplicant( 1356): P2P: Ignore scan results
D/wpa_supplicant( 1356): p2p0: Radio work 'p2p-scan'@0x55a90fd860 done in 0.401869 seconds
D/WifiMonitor(  972): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 1 9e:93:4e:3e:ba:c5]
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  972): acquireWL(3ad59ddc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(3ad59ddc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: DefaultState
,D/WifiController(  972): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): << updateStatus
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(17356ee5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(17356ee5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
D/PMS     (  972): runPSCheck
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  972): Checking...
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1546): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1546): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1546): sku_id=118
,D/ContactMessageStore( 1546): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1546): start background delete task...
,D/ContactMessageStore( 1546): size: 0 , 0
,D/ContactMessageStore( 1546): Background delete complete
,D/PMS     (  972): acquireWL(13a82dba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(13a82dba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1223): closing low battery warning: level=100
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1356): p2p0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
D/WifiMonitor(  972): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=84 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): p2p0: BSS: Remove id 1 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/WifiMonitor(  972): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 1 9e:93:4e:3e:ba:c5]
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=85 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 9e:93:4e:3e:ba:c5
,D/PMS     (  972): acquireWL(3466546b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(3466546b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
,D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(330cbbc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(330cbbc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
,D/PowerUI ( 1223): closing low battery warning: level=100,
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(22531461): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{274b956: PendingIntentRecord{aaf4dd7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=354578, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{119b6b86: PendingIntentRecord{993cc47 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=947034, Int=0
,I/bt-btm  ( 3412): Received oneshot timer event complete
I/bt-btm  ( 3412): btm_ble_timeout
I/bt-btm  ( 3412): btm_gen_resolvable_private_addr
,D/PMS     (  972): acquireWL(2215cc74): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3412 1002 null
,D/bt-btm  ( 3412): btm_ble_rand_enc_complete,
I/bt-btm  ( 3412): btm_gen_resolve_paddr_low
D/bt-smp  ( 3412): smp_encrypt_data
W/bt-smp  ( 3412): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3412): Plain text(LSB ~ MSB) = 55 21 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3412): Encrypted text(LSB ~ MSB) = bc 88 3d 88 b1 62 e8 ac 35 2e 3e 98 64 0a c6 41 
,I/bt-btm  ( 3412): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3412): Stopping oneshot timer
D/bt-btm  ( 3412): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1223): Weather sync is On
,D/PMS     (  972): releaseWL(22531461): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  972): releaseWL(2215cc74): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  972): acquireWL(3d4b959d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): releaseWL(3d4b959d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PMS     (  972): runPSCheck
D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
,D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(3532ba12): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{274b956: PendingIntentRecord{aaf4dd7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=954578, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{1736e5e3: PendingIntentRecord{cfd3be0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452270484643, Int=0
,D/SmartSyncUtils( 6364): isEpsOn(), nState = 0,
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/art     (  972): Explicit concurrent mark sweep GC freed 40039(2MB) AllocSpace objects, 3(200KB) LOS objects, 33% free, 16MB/25MB, paused 1.712ms total 207.724ms
D/PMS     (  972): acquireWL(1f50ee99): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6364 1000 null
D/PMS     (  972): releaseWL(3532ba12): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 6364): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6364): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6364): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6364): SettingOnTime = 1452319200000, randomSettingOnTime = 1452316441000
D/SmartSyncScreenOnOffTimeReceiver( 6364): SettingOffTime = 1452297600000, randomSettingOffTime = 1452303292000
,D/SmartSyncScreenOnOffTimeReceiver( 6364): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6364): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6364): bNightModeTurnOffOnce = false
,D/PMS     (  972): releaseWL(1f50ee99): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  972): acquireWL(217e655e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(217e655e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  972): plugged=true pluggin=true
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): Checking...,
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
,D/WifiController(  972): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(a67fd3f): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{10024},
V/AlarmManager(  972): sending alarm PendingIntent{3b2a360c: PendingIntentRecord{26b8db55 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1039376, Int=0
,D/PMS     (  972): acquireWL(847796a): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(847796a): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  972): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6806 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  972): sending alarm PendingIntent{1f692e5b: PendingIntentRecord{214aa6f8 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1452270192215, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{2f2086a6: PendingIntentRecord{44418e7 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=810133, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{778d7d1: PendingIntentRecord{2acf9878 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452270433470, Int=0
,W/ContextImpl( 6364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  972): releaseWL(a67fd3f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
D/PMS     (  972): acquireWL(a825537): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1941): Message class com.google.f.a.a.i
D/PowerUsageList:PowerUsageHelper( 6364): MY_DEBUG = false
,D/PMS     (  972): releaseWL(a825537): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/PowerUsageService( 6364): repeat time = 1452271404858
,I/PowerUsageList:PowerUsageHelper( 6364): PowerProfile::POWER_SCREEN_FULL = 154.8,
,E/cutils-trace( 6828): Error opening trace file: Permission denied (13),
I/dex2oat ( 6828): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6828): dex2oat: override thread count:4
,D/PowerUsageList:BatterySipperExt( 6364): gen(), null == sipper.uidObj, userId = 0,
,I/dex2oat ( 6828): dex2oat took 781.118ms (threads: 4),
,I/PushClient( 6806): ApplicationMonitor {2ef2b6bc}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6806): ApplicationMonitor {2ef2b6bc}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6806): ApplicationMonitor {2ef2b6bc}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6806): ApplicationMonitor {2ef2b6bc}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6806): ApplicationMonitor {2ef2b6bc}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6806): ApplicationMonitor {2ef2b6bc}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
I/PushClient( 6806): ApplicationMonitor {2ef2b6bc}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6806): ApplicationMonitor {2ef2b6bc}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6806): ApplicationMonitor {2ef2b6bc}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6806): PnsModel {25d452af}: update(): Update registration caused by: alarm,
,I/PushClient( 6806): PnsConfigModel {206749f2}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6806): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6806): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6806): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6806): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  972): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6836 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6836): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6836 dbg=false s=true
,I/DeviceManagement( 6836): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6836): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6836): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6836): WorkflowService: Starting workflow service
,I/DeviceManagement( 6836): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@399ea8e] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6836): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6836): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6836): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6836): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6836): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6836): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6836): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6836): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@399ea8e],
,I/DeviceManagement( 6836): WorkflowService: Stopping workflow service,
,D/Process (  972): killProcessQuiet, pid=6308
I/ActivityManager(  972): Killing 6308:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6308,
,I/PushClient( 6806): PnsModel {25d452af}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  972): killProcessQuiet, pid=6420
I/ActivityManager(  972): Killing 6420:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6420,
,D/PMS     (  972): acquireWL(3231be28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
,I/BatteryService(  972): n_update end
,D/PMS     (  972): releaseWL(3231be28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: DeviceActiveState
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(20e5741): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(20e5741): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
D/PMS     (  972): runPSCheck
D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): << updateStatus
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
,D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  972): User[0] Flushing usage stats to disk
,D/PMS     (  972): acquireWL(3bf724e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(3bf724e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  972): processMsg: DeviceActiveState
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
,D/WifiController(  972): processMsg: StaEnabledState
,D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(55cfa27): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
,D/PMS     (  972): releaseWL(55cfa27): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  972): updateBatteryInfo
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): << updateStatus
,D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  972): acquireWL(3df894d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  972): n_update end
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): releaseWL(3df894d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: StaEnabledState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(1028267d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(1028267d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo,
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
,D/NotificationService(  972): plugged=true pluggin=true
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: X
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(1e80a972): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(1e80a972): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  972): BroadcastReceiver::onReceive+,
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PMS     (  972): runPSCheck
D/WifiController(  972): handleMessage: E msg.what=155652
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(309511c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(309511c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo,
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  972): acquireWL(3115ad79): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000},
,V/AlarmManager(  972): sending alarm PendingIntent{274b956: PendingIntentRecord{aaf4dd7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1074578, Int=0,
,V/AlarmManager(  972): sending alarm PendingIntent{25abeabe: PendingIntentRecord{38ad071f com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1847046, Int=0,
I/bt-btm  ( 3412): Received oneshot timer event complete
,I/bt-btm  ( 3412): btm_ble_timeout
D/PMS     (  972): acquireWL(3ad1aa6c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3412 1002 null
I/bt-btm  ( 3412): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3412): btm_ble_rand_enc_complete
,I/bt-btm  ( 3412): btm_gen_resolve_paddr_low
D/bt-smp  ( 3412): smp_encrypt_data
W/bt-smp  ( 3412): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3412): Plain text(LSB ~ MSB) = 75 8c 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3412): Encrypted text(LSB ~ MSB) = 0d 91 97 5e 7b c2 3c f0 51 18 0c 70 9b 85 4e 9c 
I/bt-btm  ( 3412): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3412): Stopping oneshot timer
D/bt-btm  ( 3412): Starting oneshot timer type:103 timeout:900s
I/ProcessStatsService(  972): Prepared write state in 19ms
,I/ProcessStatsService(  972): Prepared write state in 7ms,
,I/ProcessStatsService(  972): Prepared write state in 7ms
,D/PMS     (  972): releaseWL(3115ad79): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/ProcessStatsService(  972): Pruning old procstats: /data/system/procstats/state-2016-01-07-23-16-00.bin
,D/PMS     (  972): releaseWL(3ad1aa6c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  972): acquireWL(28baa835): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
D/UsbnetService(  972): BroadcastReceiver::onReceive+,
I/BatteryService(  972): n_update end
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): releaseWL(28baa835): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): runPSCheck
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): Checking...
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): processMsg: DefaultState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(4b7f4ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(4b7f4ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 3412): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(2d24f63b): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{1000}
,I/ActivityManager(  972): Killing 6699:com.android.chrome/u0a96 (adj 13): empty for 1800s
D/Process (  972): killProcessQuiet, pid=6699
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
V/AlarmManager(  972): sending alarm PendingIntent{2f2086a6: PendingIntentRecord{44418e7 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1759435, Int=0
,I/ActivityManager(  972): Recipient 6699
,D/Process (  972): killProcessQuiet, pid=6638
I/ActivityManager(  972): Killing 6638:com.google.android.apps.magazines/u0a161 (adj 13): empty for 1800s
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  972): Recipient 6638
,D/Process (  972): killProcessQuiet, pid=5762
I/ActivityManager(  972): Killing 5762:com.google.android.setupwizard/u0a77 (adj 13): empty for 1800s
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  972): Recipient 5762
,D/Process (  972): killProcessQuiet, pid=6333
I/ActivityManager(  972): Killing 6333:com.htc.bgp/u0a11 (adj 13): empty for 1800s
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  972): Recipient 6333
,D/Process (  972): killProcessQuiet, pid=6526
I/ActivityManager(  972): Killing 6526:com.htc.mobiledata:remote/u0a46 (adj 13): empty for 1800s
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  972): Recipient 6526
,D/Process (  972): killProcessQuiet, pid=6396
I/ActivityManager(  972): Killing 6396:com.htc.mobiledata/u0a46 (adj 15): empty for 1800s
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  972): Recipient 6396
,D/Process (  972): killProcessQuiet, pid=4570
I/ActivityManager(  972): Killing 4570:com.android.settings/1000 (adj 15): empty for 1804s
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  972): Recipient 4570
D/WifiService(  972): Client connection lost with reason: 4
,V/AlarmManager(  972): sending alarm PendingIntent{3d8c9ecc: PendingIntentRecord{2b09f515 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825660, Int=1800000
,D/PMS     (  972): acquireWL(28650158): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
,D/PMS     (  972): releaseWL(28650158): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/AlarmManager(  972): sending alarm PendingIntent{274b956: PendingIntentRecord{aaf4dd7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1854578, Int=0
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
V/AlarmManager(  972): sending alarm PendingIntent{1b7a92b1: PendingIntentRecord{31c89396 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452270784327, Int=1800000
V/AlarmManager(  972): sending alarm PendingIntent{b62bb17: PendingIntentRecord{38d4db04 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1858833, Int=0
,I/ActivityManager(  972): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=6868 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
V/AlarmManager(  972): sending alarm PendingIntent{3674a8ed: PendingIntentRecord{38df2694 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452271361579, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{f725322: PendingIntentRecord{26b8db55 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1939435, Int=0,
,V/AlarmManager(  972): sending alarm PendingIntent{f46a370: PendingIntentRecord{1f7fe6e9 com.htc.cs.dm startService}}, i=com.htc.cs.action.EXECUTE_WORKFLOW, t=1, cnt=1, w=1452271020407, Int=0
,I/DeviceManagement( 6836): WorkflowService: Starting workflow service
V/AlarmManager(  972): sending alarm PendingIntent{23067f6e: PendingIntentRecord{2acf9878 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452271404858, Int=0
,D/PMS     (  972): acquireWL(21abf60f): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2208 10024 WorkSource{10024 com.google.android.gms},
,I/DeviceManagement( 6836): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@189fd4f8] args=[Bundle[mParcelledData.dataSize=56]]
I/DeviceManagement( 6836): UpdateWorkflow: ==================================================
I/DeviceManagement( 6836): UpdateWorkflow: TTL update...
I/DeviceManagement( 6836): UpdateWorkflow: ==================================================
D/PMS     (  972): acquireWL(28e708a5): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2208 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  972): releaseWL(21abf60f): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/DeviceManagement( 6836): SessionStateController: Checking invariants...
,D/PMS     (  972): acquireWL(183be42b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1941 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  972): releaseWL(183be42b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  972): releaseWL(2d24f63b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6364): MY_DEBUG = false
,D/PowerUsageService( 6364): repeat time = 1452272306070
,D/LocationManagerService(  972): getAllProviders()=[passive, gps, network]
,I/EventLogService( 2208): Aggregate from 1452269555604 (log), 1452268984274 (data)
,D/GCM     ( 1941): Message class com.google.f.a.a.i
D/PMS     (  972): acquireWL(34dea75d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1941 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  972): releaseWL(34dea75d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/DeviceManagement( 6836): BackgroundController: Invariants are unchanged.,
,I/DeviceManagement( 6836): Perf: *** Cache update - start...,
I/DeviceManagement( 6836): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 6836): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 6836): Perf: *** Enabled app cache update - complete: 1 ms
I/DeviceManagement( 6836): Perf: *** Config cache update - start...
,I/DeviceManagement( 6836): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 6836): ConfigCacheController: *** Updating stale config cache entries...
,I/GLSUser ( 1941): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1941): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1941): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1941): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6868, uid=10072, userID:0
D/PMS     (  972): releaseWL(28e708a5): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
W/global  ( 6868): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 6868): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 6868): [apache-http] Connection GC has been deprecated!
,TIME-OUT KILL (timeout was 1800000ms),I/PowerUsageList:PowerUsageHelper( 6364): PowerProfile::POWER_SCREEN_FULL = 154.8
I/art     ( 6836): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
I/art     ( 6836): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
D/PowerUsageList:BatterySipperExt( 6364): gen(), null == sipper.uidObj, userId = 0
W/global  ( 6868): [apache-http] Connection GC has been deprecated!
W/System.err( 6836): Starting the internal HTTP client
I/DeviceManagement( 6836): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
D/Finsky  ( 6868): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/art     ( 1941): Explicit concurrent mark sweep GC freed 38999(2MB) AllocSpace objects, 14(1004KB) LOS objects, 47% free, 4MB/8MB, paused 826us total 74.352ms
I/DeviceManagement( 6836): DeviceClientResource: Active network...
I/DeviceManagement( 6836):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/BuildInfo( 6836): Created new instance: com.htc.cs.lib.hms.BuildInfo@26333c0f
I/DeviceManagement( 6836): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
I/ActivityManager(  972): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6913 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 6868): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6868): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/art     (  437): Explicit concurrent mark sweep GC freed 8658(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 220us total 45.086ms
D/libc    ( 6836): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6868, uid=10072, userID:0
D/libc    ( 6836): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6836): [NET] android_getaddrinfo_proxy+
D/libc    ( 6836): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6836): [NET] android_getaddrinfo_proxy-, success
W/ResourcesManager( 6913): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6913): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc    ( 6836): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4
D/libc    ( 6836): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6836): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    ( 6836): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6836): [NET] android_getaddrinfo_proxy+
D/libc    ( 6836): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
I/art     (  437): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 404us total 24.491ms
I/MultiDex( 6913): VM with version 2.1.0 has multidex support
I/MultiDex( 6913): install
I/MultiDex( 6913): VM has multidex support, MultiDex support library is disabled.
I/art     (  437): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 203us total 23.814ms
D/Finsky  ( 6868): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/JNIHelp ( 6913): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 6868): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6868): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 6868): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityThread( 6913): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6913): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@215ff7f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6913): Installed default security provider GmsCore_OpenSSL
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6836): [NET] android_getaddrinfo_proxy-, success
D/Finsky  ( 6868): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/GCM     ( 1941): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1941): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2208): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/GLSUser ( 1941): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1941): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1941): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1941): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WearableService( 6743): callingUid 10024, callindPid: 6743
E/MDM     ( 1849): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2208, uid=10024, userID:0
D/LocationInitializer( 2208): Restart initialization of location
W/Finsky  ( 6868): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1941): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1941): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1941): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1941): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/Finsky  ( 6868): [1] GearheadStateMonitor.onReady: sIsProjecting:false
I/GLSUser ( 1941): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1941): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1941): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1941): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6868): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/DeviceManagement( 6836): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6836): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6836): DeviceClientResourceController: handleDirectives: []
I/System.out( 6836): isCompatible false
I/System.out( 6836): createObjectMapper
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
E/AndroidHttpClient( 6868): Leak found
E/AndroidHttpClient( 6868): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 6868): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 6868): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 6868): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 6868): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 6868): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 6868): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 6868): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 6868): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 6868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 6868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 6868): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 6868): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 6868): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 6868): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 6868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 6868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DeviceManagement( 6836): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
I/DeviceManagement( 6836): DeviceClientResource: Active network...
I/DeviceManagement( 6836):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/libc    ( 6836): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4
D/libc    ( 6836): [NET] android_getaddrinfofornet-, err=8
I/GLSUser ( 1941): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1941): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1941): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1941): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1941): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6868): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 6868): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6868): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6868): [1] DailyHygiene.reschedule: Scheduling new run in 81 minutes (failures=3)
D/DeviceConnectionService( 1849): client connected with version: 7571000
I/DeviceManagement( 6836): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6836): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6836): DeviceClientResourceController: handleDirectives: []
I/System.out( 6836): isCompatible false
I/System.out( 6836): createObjectMapper
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/System.out( 6836): isCompatible false
I/DeviceManagement( 6836): ConfigCacheController: *** Update config cache: updating 2 entries...
I/DeviceManagement( 6836): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
I/art     (  972): Explicit concurrent mark sweep GC freed 30818(1690KB) AllocSpace objects, 13(1428KB) LOS objects, 33% free, 16MB/25MB, paused 1.724ms total 155.998ms
I/DeviceManagement( 6836): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
I/DeviceManagement( 6836): ConfigCacheController: No changes need to be broadcasted.
I/DeviceManagement( 6836): AlarmController: Scheduling TTL alarm for: 2016.01.09 at 17:43:27.672 CET (due to: com.htc.launcher)
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=6836, uid=10099, userID:0
I/DeviceManagement( 6836): Perf: *** Config cache update - complete: 1800 ms
I/DeviceManagement( 6836): Perf: *** Cache update - complete: 1807 ms
I/DeviceManagement( 6836): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@189fd4f8]
I/DeviceManagement( 6836): WorkflowService: Stopping workflow service
E/cutils-trace( 6956): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6956): ====startRecUseTime====
D/htc.customization.log.level( 6956):  is 
W/CustomizationLogLevel( 6956): Level value is invalid, use default level 2
D/CustomizationManager( 6956):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 6956): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6956): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6956): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6956): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6956): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6956): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6956): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6956): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6956): Parsing tag category name = system
I/CustomizationCIDLoader( 6956): Parsing tag category name = application
I/CustomizationCIDLoader( 6956): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6956): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6956): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6956): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6956): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6956): add string-array item, value = 42507
I/CustomizationCIDLoader( 6956): add string-array item, value = 21902
I/CustomizationCIDLoader( 6956): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6956): add string-array item, value = 23420
I/CustomizationCIDLoader( 6956): add string-array item, value = 22299
I/CustomizationCIDLoader( 6956): add string-array item, value = 24002
I/CustomizationCIDLoader( 6956): add string-array item, value = 23210
I/CustomizationCIDLoader( 6956): add string-array item, value = 23205
I/CustomizationCIDLoader( 6956): add string-array item, value = 23806
I/CustomizationCIDLoader( 6956): add string-array item, value = 23430
I/CustomizationCIDLoader( 6956): add string-array item, value = 23408
I/CustomizationCIDLoader( 6956): add string-array item, value = 27205
I/CustomizationCIDLoader( 6956): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6956): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6956):  Read CID file spent 0.106 (s)
D/CustomizationManager( 6956):  All configurations done spent 0.107 (s)
D/PackageManager(  972): deletePackageAsUser: pkg=com.test.thalitest, pid=6956, uid=2000 userid=0
I/ActivityManager(  972): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  972): Killing 6465:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  972): killProcessQuiet, pid=6465
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  972): Skipping PackageSetting{1771a64a com.example.hello/10374} due to missing metadata
I/ActivityManager(  972): Recipient 6465
I/WindowState(  972): WIN DEATH: Window{3f2bd0f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/InputEventReceiver( 1405): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{26a20a3e uid 10366 pid 6465} (c)'
D/WifiService(  972): Client connection lost with reason: 4
I/ActivityManager(  972):   Force finishing activity ActivityRecord{eb9a6bf u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  972): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  972):   Force finishing activity ActivityRecord{eb9a6bf u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  972): Duplicate finish request for ActivityRecord{eb9a6bf u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  972): Spurious death for ProcessRecord{3e3d3d53 6465:com.test.thalitest/u0a366}, curProc for 6465: null
D/DotMatrix( 1311): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1311): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  972): acquireWL(26642b89): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1849 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1849): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1739): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  972): releaseWL(26642b89): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/SystemReader(  972): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1739): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/AccTypeManager( 1739): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/InputMethodManagerService(  972): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/ExternalAccountType( 1739): Unsupported attribute readOnly
I/art     ( 1588): Explicit concurrent mark sweep GC freed 7503(403KB) AllocSpace objects, 5(376KB) LOS objects, 34% free, 29MB/45MB, paused 1.033ms total 92.915ms
I/Prism.ItemManager( 1588): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1588): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1689): Cleaning up data for package: com.test.thalitest
D/PhoneApp( 1546): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1657): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/ResourcesManager(  972): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Launcher( 1588): Deferring update until onResume
D/Launcher( 1588): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1588): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1657): handle notify Blinkfeed plugin client changed
I/ActivityManager(  972): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6976 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/PackageManager(  972): Unable to load service info ResolveInfo{17c95d8f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  972): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  972): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  972): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  972): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  972): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  972): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  972): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  972): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  972): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  972): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  972): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/JobSchedulerService(  972): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  972): Explicit concurrent mark sweep GC freed 15610(1232KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 3.239ms total 217.665ms
D/TaskPersister(  972): removeObsoleteFile: deleting file=8_task.xml
D/StatusBarManagerService(  972): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
W/ContextImpl( 6976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/FindExtension( 1588): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1588): Defer allocateBuffers to drawing time
I/ActivityManager(  972): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7000 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
W/InputMethodManagerService(  972): Got RemoteException sending setActive(false) notification to pid 6465 uid 10366
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  972): Killing 5517:com.google.android.apps.plus/u0a167 (adj 15): empty for 1804s
D/Process (  972): killProcessQuiet, pid=5517
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  972): Recipient 5517
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7000): -onCreate()
V/Settings:HtcSettingsApplication( 7000): [7000/7000] onCreate()
D/Process (  972): killProcessQuiet, pid=6211
I/ActivityManager(  972): Killing 6211:com.google.android.talk/u0a112 (adj 15): empty for 1804s
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/Settings:HtcWirelessFeatureFlags( 7000): id/is att sku: 118/false
E/Settings:HtcWrapHeaderInfo( 7000): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7000): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7000): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7000): isSupportMusicChannel(): false
I/ActivityManager(  972): Recipient 6211
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]support         :false
E/SQLiteLog( 1941): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1941): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x559da38f90
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
E/ActivityManager(  972): App crashed! Process: com.google.process.gapps
D/Process ( 1941): killProcess, pid=1941
D/Process ( 1941): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/Settings:HtcVoWifiWidgetEnabler( 7000): isSupportVoWifi: null
I/ActivityManager(  972): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7000): Failed to find provider info for com.htc.vowifi
E/DropBoxManagerService(  972): Can't write: system_app_crash
E/DropBoxManagerService(  972): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  972): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  972): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  972): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  972): 	... 5 more
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7000): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7000): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7000): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7000): [supportHomeButton]support         :false
I/ActivityManager(  972): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7000): isSupportVoWifi: null
E/ActivityThread( 7000): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  972): Recipient 1941
I/ActivityManager(  972): Process com.google.process.gapps (pid 1941) has died
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 11000ms
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 31000ms
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 41000ms
I/ActivityManager(  972): Killing 6591:com.google.android.music:main/u0a159 (adj 15): empty for 1802s
D/Process (  972): killProcessQuiet, pid=6591
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.appDiedLocked:5130 
I/ActivityManager(  972): Recipient 6591
D/MediaRouterService(  972): Client com.google.android.music (pid 6591): Died!

```
