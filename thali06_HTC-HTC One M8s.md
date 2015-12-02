#### Test 52445159d291820_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
,I/ActivityManager(  961): Killing 5538:com.htc.musicenhancer/u0a49 (adj 15): empty #17
--------- beginning of main
D/Process (  961): killProcessQuiet, pid=5538
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  961): Recipient 5538
E/cutils-trace( 6613): Error opening trace file: Permission denied (13)
W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 2
D/CustomizationManager( 6613): ====startRecUseTime====
D/htc.customization.log.level( 6613):  is 
W/CustomizationLogLevel( 6613): Level value is invalid, use default level 2
D/CustomizationManager( 6613):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 6613): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6613): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6613): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6613): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6613): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6613): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6613): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6613): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6613): Parsing tag category name = system
I/CustomizationCIDLoader( 6613): Parsing tag category name = application
I/CustomizationCIDLoader( 6613): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6613): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6613): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6613): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6613): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6613): add string-array item, value = 42507
I/CustomizationCIDLoader( 6613): add string-array item, value = 21902
I/CustomizationCIDLoader( 6613): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6613): add string-array item, value = 23420
I/CustomizationCIDLoader( 6613): add string-array item, value = 22299
I/CustomizationCIDLoader( 6613): add string-array item, value = 24002
I/CustomizationCIDLoader( 6613): add string-array item, value = 23210
I/CustomizationCIDLoader( 6613): add string-array item, value = 23205
I/CustomizationCIDLoader( 6613): add string-array item, value = 23806
I/CustomizationCIDLoader( 6613): add string-array item, value = 23430
I/CustomizationCIDLoader( 6613): add string-array item, value = 23408
I/CustomizationCIDLoader( 6613): add string-array item, value = 27205
I/CustomizationCIDLoader( 6613): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6613): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6613):  Read CID file spent 0.089 (s)
D/CustomizationManager( 6613):  All configurations done spent 0.089 (s)
I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6613 on display 0
D/PMS     (  961): acquireHCC(3040a49e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 961 1000 null
D/PMS     (  961): acquireHCC(2de26b7f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 961 1000 null
I/ActivityManager(  961): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6631 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  961): Display changed displayId=0
D/DotMatrix( 1309): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1309): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1488): [trimMemory] 20
I/WebViewFactory( 6631): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6631): Time to load native libraries: 14 ms (timestamps 638-652),
,I/LibraryLoader( 6631): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6631): Binding Chromium to main looper Looper (main, tid 1) {f5ced7},
I/LibraryLoader( 6631): Expected native library version number "",actual native library version number ""
,I/chromium( 6631): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6631): Initializing chromium process, singleProcess=true,
,W/art     ( 6631): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6631): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6631): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6631): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6631): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6631): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6631): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6631): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6631): Local Branch: 
I/Adreno-EGL( 6631): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6631): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6631):                  d74aa161a12b9c6fc6332151
,W/System.err(  961): java.lang.Throwable: stack dump,
W/System.err(  961): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  961): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  961): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  961): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  961): Message: MESSAGE_REGISTER_ADAPTER,
D/BluetoothManagerService(  961): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8782813:true
,D/BluetoothAdapter( 6631): 324960627: getState(). Returning 12
,W/art     ( 6631): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6631): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6631): CordovaWebView is running on device made by: HTC
,W/art     ( 6631): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6631): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6631): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
W/HtcSystemUPManager(  961): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  961): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  961): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  961): hiding MENU key
D/StatusBarManagerService(  961): setSystemUiVisibility(0x0)
,D/StatusBarManagerService(  961): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  961): hiding MENU key
,D/FindExtension( 6631): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6631): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1110c219, mServedView=org.apache.cordova.engine.SystemWebView{179c72de VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2e50bcbf
,I/InputMethodManagerService(  961): Disable input method client, pid=1488
D/StatusBarManagerService(  961): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6631): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  961): Displayed com.test.thalitest/.MainActivity: +644ms (total +690ms),
,W/BindingManager( 6631): Cannot call determinedVisibility() - never saw a connection for the pid: 6631
,D/JsMessageQueue( 6631): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6631): JniHelper::setJavaVM(0xab43f8f8), pthread_self() = -1401562624,
D/JX-Cordova( 6631): jxcore cordova android initializing
,W/jxcore-log( 6631): Initializing JXcore engine,
W/jxcore-log( 6631): JXcore engine is ready
,W/jxcore-log( 6631): Starting JXcore engine
,W/jxcore-log( 6631): Platform android,
W/jxcore-log( 6631): 
W/jxcore-log( 6631): Process ARCH arm
W/jxcore-log( 6631): 
,D/PMS     (  961): releaseHCC(3040a49e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  961): releaseHCC(2de26b7f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6631): JXcore Cordova bridge is ready!,
I/jxcore-log( 6631): 
W/jxcore-log( 6631): JXcore engine is started
,I/chromium( 6631): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6631): Toggling radios to true
I/jxcore-log( 6631): 
D/BluetoothAdapter( 6631): enable(): BT is already enabled..!
,D/WifiService(  961): New client listening to asynchronous messages
E/WifiTrafficPoller(  961): ADD_CLIENT: 8
,D/WifiManager( 6631): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  961): MONITOR_LOG
D/WifiService(  961): setWifiEnabled: true pid=6631, uid=10366
W/Settings:Agent(  961): name: wifi_on
E/WifiService(  961): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  961): value: 2
I/WifiService(  961): isSprintWifiRestricted(): false
W/Settings:Agent(  961): >> traceCallingStack()
I/WifiService(  961): isMdmWifiRestricted(): false
W/Settings:Agent(  961): Process.myPid(): 961
W/Settings:Agent(  961): Process.myTid(): 990
W/Settings:Agent(  961): Process.myUid(): 1000
W/Settings:Agent(  961): 
W/Settings:Agent(  961): 
W/System.err(  961): java.lang.Throwable: stack dump
,W/System.err(  961): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  961): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  961): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  961): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  961): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  961): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  961): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
,W/System.err(  961): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  961): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  961): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  961): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  961): 
W/Settings:Agent(  961): << traceCallingStack(): 11(ms)
D/WifiController(  961): handleMessage: E msg.what=155656
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): handleMessage: X,
D/WifiManager( 6631): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  961): handleMessage: E msg.what=131145
E/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiManager( 6631): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  961):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  961): processMsg: L2ConnectedState
E/WifiStateMachine(  961):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
,D/wpa_supplicant( 1341): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1341): wlan0: Cancelling scan request
D/wpa_supplicant( 1341): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1341): TDLS: Tear down peers
D/wpa_supplicant( 1341): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6631): Radios toggled
I/jxcore-log( 6631): 
,D/wpa_supplicant( 1341): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1341): wlan0: Deauthentication notification
D/wpa_supplicant( 1341): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1341): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1341): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1341): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1341): enter disconnect check
I/wpa_supplicant( 1341): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1341): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1341): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  961): interfaceLinkStateChanged wlan0, false
D/Tethering(  961): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  961): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  961): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  961): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  961): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  961): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  961): interfaceLinkStateChanged wlan0, false
D/Tethering(  961): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  961): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  961): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  961): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  961): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  961): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/wpa_supplicant( 1341): TDLS: Remove peers on disassociation
D/UsbDeviceManager(  961): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1341): wlan0: Disconnect event - remove keys
D/PMS     (  961): acquireWL(79bbbac): PARTIAL_WAKE_LOCK  NetworkStats 0x1 961 1000 null
D/UsbnetService(  961): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1341): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1341): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1341): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a07bef88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1341):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1341): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1341): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1341): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1341): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1341): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1341): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1341): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1341): EAPOL: External notification - portValid=0
D/WifiDisplayAdapter(  961): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  961):     Client/Owner: Client
D/WifiDisplayAdapter(  961):     GroupId: 
D/WifiDisplayAdapter(  961):     Passphrase: 
D/WifiDisplayAdapter(  961):     SessionId: 0
D/WifiDisplayAdapter(  961):     IP Address: }
D/wpa_supplicant( 1341): EAPOL: External notification - EAP success=0
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE i,d=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1341): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1341): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1341): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1341): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1341): EAPOL: External notification - portValid=0
D/HTCRequest(  961): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  961): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1341): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1341): Wireless event: cmd=0x8b15 len=24
D/HTCRequest(  961): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1341): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1341): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
E/WifiStateMachine(  961): transitionTo: destState=DisconnectingState
D/wpa_supplicant( 1341): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  961): handleMessage: new destination call exit/enter
E/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiMonitor(  961): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  961): invokeExitMethods: ConnectedState
E/WifiStateMachine(  961): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  961): release()
E/WifiStateMachine(  961): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  961): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  961): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  961): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
,E/WifiStateMachine(  961): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  961): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  961): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1341): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1341): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1341): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1341): Power_Mode_Type mode = 0
I/wpa_supplicant( 1341): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  961): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  961): setDhcpActive: false
,V/NativeCrypto( 1872): Read error: ssl=0x558d5ea510: I/O error during system call, Connection timed out
,D/libc    (  961): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  961): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  961): acquireWL(3858075): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  961): releaseWL(79bbbac): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,E/WifiStateMachine(  961): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
V/NetworkPolicy(  961): updateNetworkEnabledLocked()
V/NetworkPolicy(  961): updateNotificationsLocked()
E/WifiStateMachine(  961): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  961): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  961): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  961): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/ConnectivityService(  961): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc    (  961): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  961): NetworkAgent != null
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  961): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  961): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/TetherSettings( 5833): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5833): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5833): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5833): Cust_ConnectToPC   : spcsc>false
D/        ( 5833): Cust_ConnectToPC   : IPT>true
D/        ( 5833): Cust_ConnectToPC   : Singel_USB>false
V/NativeCrypto( 1872): SSL shutdown failed: ssl=0x558d5ea510: I/O error during system call, Broken pipe
E/WifiTrafficPoller(  961): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/libc    (  961): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  961): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  961): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  961): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  961): stopDataStallAlarm 
E/WifiTrafficPoller(  961): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiDataStallTracker(  961): ENABLE_DATA_MONITOR_POLL false Token 3
W/Settings( 5833): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  961): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  961): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/SmartNS_Utility( 5833): hasRemovableStorageSlot: true
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
,D/wpa_supplicant( 1341): wlan0: Control interface command 'SAVE_CONFIG'
D/SmartNS_Utility( 5833): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/wpa_supplicant( 1341): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/SmartNS_NSReceiver( 5833): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/wpa_supplicant( 1341): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully,
D/wpa_supplicant( 1341): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  961): invokeEnterMethods: DisconnectingState
,E/WifiStateMachine(  961):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  961): Start Disconnecting Watchdog 1
E/WifiStateMachine(  961): handleMessage: X
D/ConnectivityService(  961): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  961): handleMessage: E msg.what=131146
E/WifiStateMachine(  961): processMsg: DisconnectingState
,E/WifiStateMachine(  961):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  961): processMsg: ConnectModeState
E/WifiStateMachine(  961): WiFiDisplay: getWifidisplayApEnabled=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  961): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  961):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  961): DefaultState{ when=-3ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  961): Forcing reevaluation
D/wpa_supplicant( 1341): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1341): Fast associate: Old scan results
D/wpa_supplicant( 1341): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1341): wpa_supplicant_scan enter
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  961): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): wlan0: State: DISCONNECTED -> SCANNING
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  961): Validated
D/wpa_supplicant( 1341): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1341): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1341): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1341): WPS:  * Request Type
D/wpa_supplicant( 1341): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1341): WPS:  * UUID-E
D/wpa_supplicant( 1341): WPS:  * Primary Device Type
D/wpa_supplicant( 1341): WPS:  * RF Bands (3)
D/wpa_supplicant( 1341): WPS:  * Association State
D/wpa_supplicant( 1341): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1341): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1341): WPS:  * Manufacturer
D/wpa_supplicant( 1341): WPS:  * Model Name
D/wpa_supplicant( 1341): WPS:  * Model Number
D/wpa_supplicant( 1341): WPS:  * Device Name
D/wpa_supplicant( 1341): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1341): P2P: * P2P IE header
D/wpa_supplicant( 1341): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1341): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1341): wlan0: Add radio work 'scan'@0x55a07c1680
D/wpa_supplicant( 1341): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1341): wlan0: Starting radio work 'scan'@0x55a07c1680 after 0.000106 second wait
D/wpa_supplicant( 1341): wlan0: nl80211: scan request
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  961): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  961): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1341): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1341): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1341): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1341): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1341): wlan0: Own scan request started a scan in 0.000309 seconds
I/wpa_supplicant( 1341): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  961): handleMessage: X
E/WifiStateMachine(  961): handleMessage: E msg.what=147460
E/WifiStateMachine(  961): processMsg: DisconnectingState
E/WifiTrafficPoller(  961): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  961):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133087
E/WifiStateMachine(  961): processMsg: ConnectModeState
D/HTCRequest(  961): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  961): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/,WifiStateMachine(  961):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133088
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  961): ConnectModeState: Network connection lost 
D/PMS     (  961): releaseWL(3858075): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  961): transitionTo: destState=DisconnectedState
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  961): handleMessage: new destination call exit/enter
E/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  961): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  961): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  961): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  961): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  961): DisconnectedState call setCountryCode()
E/WifiStateMachine(  961):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1341): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1341): wlan0: Cancelling scan request
,D/wpa_supplicant( 1341): wlan0: nl80211: sched_scan request
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
,W/ContextImpl( 5833): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5833): setISNotification
,D/SmartNS_Utility( 5833): usb_cable_connect = 1
,D/SmartNS_Utility( 5833): usb_denied = 0
I/SmartNS_PSService( 5833): usb notificaiton:true
E/WifiStateMachine(  961): WiFiDisplay: getWifidisplayApEnabled=false
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
,I/ActionCombine( 5833): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,D/SmartNS_Utility( 5833): usb_cable_connect = 1,
,D/SmartNS_Utility( 5833): usb_denied = 0
I/SmartNS_PSService( 5833): usb notificaiton:true
E/WifiStateMachine(  961): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/wpa_supplicant( 1341): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1341): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiP2pService(  961): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): wlan0: nl80211: Sched scan started
D/WifiP2pService(  961): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/WifiP2pService(  961): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1341): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/wpa_supplicant( 1341): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1341): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1341): wlan0: Scan completed in 0.048845 seconds
D/wpa_supplicant( 1341): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1341): wlan0: BSS: Start scan result update 7,
D/wpa_supplicant( 1341): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1341): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1341): wlan0: Radio work 'scan'@0x55a07c1680 done in 0.050371 seconds
D/wpa_supplicant( 1341): wlan0: No suitable network found
D/wpa_supplicant( 1341): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1341): wlan0: Cancelling sched scan
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  961): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1341): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1341): wlan0: Cancelling scan request
D/wpa_supplicant( 1341): p2p0: Updating scan results from sibling
,D/WifiMonitor(  961): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 1341): nl80211: Received scan results (0 BSSes)
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1341): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1341): BSS: last_scan_res_used=0/0
W/WifiMonitor(  961): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1341): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1341): p2p0: No suitable network found
D/wpa_supplicant( 1341): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1341): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1341): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  961): WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  961): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  961): handleMessage: X
E/WifiStateMachine(  961): handleMessage: E msg.what=131101
E/WifiStateMachine(  961): processMsg: DisconnectedState
E/WifiStateMachine(  961):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  961): processMsg: ConnectModeState
E/WifiStateMachine(  961):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  961): processMsg: DriverStartedState
E/WifiStateMachine(  961):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  961): processMsg: SupplicantStartedState
E/WifiStateMachine(  961):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  961): processMsg: DefaultState
E/WifiStateMachine(  961):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  961): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  961): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  961): handleMessage: X
E/WifiStateMachine(  961): handleMessage: E msg.what=147462
E/WifiStateMachine(  961): processMsg: DisconnectedState
,E/WifiStateMachine(  961):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=133138  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/SmartNS_NSReceiver( 5833): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  961): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  961): processMsg: ConnectModeState
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  961):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=133142  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  961): handleMessage: X
E/WifiStateMachine(  961): handleMessage: E msg.what=131212
E/WifiStateMachine(  961): processMsg: DisconnectedState
E/WifiStateMachine(  961):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: ConnectModeState
E/WifiStateMachine(  961):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  961): processMsg: DriverStartedState
E/WifiStateMachine(  961):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: SupplicantStartedState
E/WifiStateMachine(  961):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: DefaultState
E/WifiStateMachine(  961):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  961): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  961): handleMessage: X
,D/WifiNetworkAgent(  961): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  961): handleMessage: E msg.what=131212
E/WifiStateMachine(  961): processMsg: DisconnectedState
E/WifiStateMachine(  961):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: ConnectModeState
E/WifiStateMachine(  961):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: DriverStartedState
E/WifiStateMachine(  961):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: SupplicantStartedState
E/WifiStateMachine(  961):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: DefaultState
E/WifiStateMachine(  961):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  961): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  961): handleMessage: X
E/WifiStateMachine(  961): handleMessage: E msg.what=131212
E/WifiStateMachine(  961): processMsg: DisconnectedState
E/WifiStateMachine(  961):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: ConnectModeState
,E/WifiStateMachine(  961):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: DriverStartedState
E/WifiStateMachine(  961):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: SupplicantStartedState
,E/WifiStateMachine(  961):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): processMsg: DefaultState
E/WifiStateMachine(  961):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  961): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  961): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  961): handleMessage: X
E/WifiStateMachine(  961): handleMessage: E msg.what=147462
E/WifiStateMachine(  961): processMsg: DisconnectedState
E/WifiStateMachine(  961):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=133149  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  961): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  961): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  961): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  961): NetworkAgent == null
E/WifiStateMachine(  961): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  961): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  961): processMsg: ConnectModeState
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  961):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=133153  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  961): handleMessage: X
E/WifiStateMachine(  961): handleMessage: E msg.what=147461
E/WifiStateMachine(  961): processMsg: DisconnectedState
E/WifiTrafficPoller(  961): ENABLE_TRAFFIC_STATS_POLL false Token 17
W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  961):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:88 bcn=0
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  961): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  961):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:88 bcn=0
E/WifiStateMachine(  961): processMsg: DriverStartedState,
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  961):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:88 bcn=0
E/WifiStateMachine(  961): processMsg: SupplicantStartedState
E/WifiStateMachine(  961):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:88 bcn=0
D/WifiStateMachine(  961): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1341): wlan0: Control interface command 'LIST_DONGLES'
I/RemoteViews( 1221): reapply : com.android.settings 1 36
E/WifiStateMachine(  961): [1,449,086,863,482 ms] noteScanEnd no scan source
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1341): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  961): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@39a6d54f sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  961): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  961): NG700 c0:ff:d4:d3:aa:48 rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  961): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  961): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  961):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-55 freq=2462
E/WifiAutoJoinController (  961): Gonzos 38:f8:89:11:e9:11 rssi=-90 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  961): ageScanResultsOut delay 40000 size 3 now 1449086863484
E/WifiAutoJoinController (  961): newSupplicantResults size=3 known=1 true
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1341): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  961): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  961): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  961): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  961): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  961): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  961): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-55,-127) num=(1,0)
E/WifiAutoJoinController (  961): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  961): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  961): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  961): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  961): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-55 freq=2462
D/HtcWifiControlRoamOffload: (  961): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  961): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  961): Done attemptAutoJoin status=3
E/WifiConfigStore(  961):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  961): handleMessage: X
E/WifiStateMachine(  961): handleMessage: E msg.what=131215
E/WifiStateMachine(  961): processMsg: DisconnectedState
E/WifiStateMachine(  961):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-55 ;0 ,-127] any roam=0 rt=133162
E/WifiStateMachine(  961): processMsg: ConnectModeState
E/WifiStateMachine(  961):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-55, ;0 ,-127] any roam=0 rt=133162
E/WifiStateMachine(  961): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  961): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  961): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
D/ConnectivityService(  961): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  961):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  961):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  961): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  961): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  961): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  961): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  961): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  961): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  961): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
I/SecurityController( 1221): onLost 100
D/NetworkManagementService(  961): Removing idletimer
D/usbnet  (  961): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  961):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  961): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiConfigStore(  961): Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
D/WISPrService( 5833): >>>>>WISPrService start isConnected = true<<<<<
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
,W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1341): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  961): will read network variables netId=0
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/WifiService(  961): New client listening to asynchronous messages
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1341): Do not allow key_data field to be exposed
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiTrafficPoller(  961): ADD_CLIENT: 9
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/PMS     (  961): acquireWL(8ee287b): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 961 1000 null
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/CSLegacyTypeTracker(  961): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/ConnectivityService(  961): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  961): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  961):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  961): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1341): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1341): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1341): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  961): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1341): wlan0: Control interface command 'ENABLE_NETWORK 0'
D/FlexNetS( 6405): updateSvcAllowedInSettings:false
I/wpa_supplicant( 1341): ENABLE_NETWORK (0)
D/wpa_supplicant( 1341): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1341): wlan0: Setting scan request: 0.000000 sec
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
I/wpa_supplicant( 1341): wpa_supplicant_scan enter
D/wpa_supplicant( 1341): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1341): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1341): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1341): WPS:  * Request Type
D/wpa_supplicant( 1341): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1341): WPS:  * UUID-E
D/wpa_supplicant( 1341): WPS:  * Primary Device Type
D/wpa_supplicant( 1341): WPS:  * RF Bands (3)
D/wpa_supplicant( 1341): WPS:  * Association State
D/wpa_supplicant( 1341): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1341): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1341): WPS:  * Manufacturer
D/wpa_supplicant( 1341): WPS:  * Model Name
D/wpa_supplicant( 1341): WPS:  * Model Number
D/wpa_supplicant( 1341): WPS:  * Device Name
D/wpa_supplicant( 1341): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1341): P2P: * P2P IE header
D/wpa_supplicant( 1341): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1341): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1341): wlan0: Add radio work 'scan'@0x55a07c1680
D/wpa_supplicant( 1341): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1341): wlan0: Starting radio work 'scan'@0x55a07c1680 after 0.000034 second wait
D/wpa_supplicant( 1341): wlan0: nl80211: scan request
D/wpa_supplicant( 1341): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1341): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1341): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1341): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1341): wlan0: Own scan request started a scan in 0.000095 seconds
I/wpa_supplicant( 1341): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  961): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  961): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  961): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1341): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  961): will read network variables netId=0
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1341): Do not allow key_data field to be exposed
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/FlexNetS( 6405): updateSvcAllowedInSettings:false
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/WifiDisplayAdapter(  961): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  961):     Client/Owner: Client
D/WifiDisplayAdapter(  961):     GroupId: 
D/WifiDisplayAdapter(  961):     Passphrase: 
D/WifiDisplayAdapter(  961):     SessionId: 0
D/WifiDisplayAdapter(  961):     IP Address: }
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1341): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1341): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  961): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  961):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1341): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1341): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1341): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1341): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1341): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1341): wpa_supplicant_scan enter
D/wpa_supplicant( 1341): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1341): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1341): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  961): setLastSelectedConfiguration -1
E/WifiStateMachine(  961): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  961): handleMessage: new destination call exit/enter
E/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  961): invokeExitMethods: DisconnectedState
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1341): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  961): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  961): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  961): DisconnectedState call setCountryCode()
E/WifiStateMachine(  961):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1341): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1341): wlan0: Cancelling scan request
D/wpa_supplicant( 1341): wlan0: nl80211: sched_scan request
I/ActivityManager(  961): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6693 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/ConnectivityService(  961): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  961): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  961): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  961): acquireWL(27dee698): PARTIAL_WAKE_LOCK  NetworkStats 0x1 961 1000 null
D/Tethering(  961): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  961): ensureActiveMobilePolicyLocked()
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/ConnectivityService(  961): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/PMS     (  961): releaseWL(27dee698): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/NetworkPolicy(  961): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  961): updateNetworkEnabledLocked()
V/NetworkPolicy(  961): updateIfacesLocked()
D/DATA_ICON( 1221): dataConnected: false/false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  961): updateNotificationsLocked()
V/NetworkPolicy(  961): updateNetworkEnabledLocked()
V/NetworkPolicy(  961): updateNotificationsLocked()
D/FlexNetS( 6405): updateSvcAllowedInSettings:false
D/NetworkManagementService(  961): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/FlexNetS( 6405): updateSvcAllowedInSettings:false
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1341): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1341): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1341): wlan0: nl80211: Sched scan started
D/WifiP2pService(  961): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/WifiP2pService(  961): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): wlan0: nl80211: New scan results available
D/WifiP2pService(  961): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1341): wlan0: Event SCAN_RESULTS (3) received
W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/wpa_supplicant( 1341): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1341): wlan0: Scan completed in 0.044709 seconds
D/wpa_supplicant( 1341): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1341): wlan0: BSS: Start scan result update 8
D/wpa_supplicant( 1341): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
E/WifiStateMachine(  961): handleMessage: X
D/wpa_supplicant( 1341): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/WIFI    (  961): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1341): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to no match in scan
D/WIFI    (  961):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 1341): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1341): wlan0: New scan results available (own=1 ext=0)
D/WIFI    (  961): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1341): wlan0: Radio work 'scan'@0x55a07c1680 done in 0.045714 seconds
E/WifiStateMachine(  961): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/wpa_supplicant( 1341): wlan0: No suitable network found
D/wpa_supplicant( 1341): wlan0: Setting scan request: 15.000000 sec
E/WifiStateMachine(  961): handleMessage: E msg.what=131131
D/wpa_supplicant( 1341): wlan0: Cancelling sched scan
E/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/wpa_supplicant( 1341): nl80211: Sched scan stop sent (ret=0)
E/WifiMonitor(  961): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1341): wlan0: Cancelling scan request
D/wpa_supplicant( 1341): p2p0: Updating scan results from sibling
E/WifiMonitor(  961): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1341): nl80211: Received scan results (0 BSSes)
E/WifiStateMachine(  961):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  961): processMsg: ConnectModeState
D/wpa_supplicant( 1341): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1341): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1341): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1341): p2p0: No suitable network found
D/wpa_supplicant( 1341): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1341): wlan0: nl80211: Sched scan stopped
E/WifiStateMachine(  961):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/wpa_supplicant( 1341): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  961): WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  961): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  961): handleMessage: X
E/WifiStateMachine(  961): handleMessage: E msg.what=147461
E/WifiStateMachine(  961): processMsg: DisconnectedState
E/WifiStateMachine(  961):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:88 bcn=0
E/WifiStateMachine(  961): processMsg: ConnectModeState
E/WifiStateMachine(  961):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:88 bcn=0
E/WifiStateMachine(  961): processMsg: DriverStartedState
E/WifiStateMachine(  961):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:88 bcn=0
E/WifiStateMachine(  961): processMsg: SupplicantStartedState
E/WifiStateMachine(  961):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:88 bcn=0
D/WifiStateMachine(  961): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1341): wlan0: Control interface command 'LIST_DONGLES'
D/FlexNetS( 6405): updateSvcAllowedInSettings:false
E/WifiStateMachine(  961): [1,449,086,863,582 ms] noteScanEnd no scan source
W/WifiHW  (  961): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1341): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  961): handleMessage: X
W/WISPrService( 5833): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5833): trigger connection
D/WISPrService( 5833): continue
D/FlexNetS( 6405): updateSvcAllowedInSettings:false
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/FlexNetS( 6405): updateSvcAllowedInSettings:false
,D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WISPrService( 5833): start DataConnection,
D/libc    ( 5833): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5833): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5833): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5833): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5833): >>>>>WISPrService start isConnected = false<<<<<
,D/libc    ( 5833): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/WISPrService( 5833): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5833): [NET] android_getaddrinfofornet-, pass to proxy
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/libc    ( 5833): [NET] android_getaddrinfo_proxy+
D/libc    ( 5833): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/FlexNetS( 6405): updateSvcAllowedInSettings:false
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5833): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5833): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5833): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5833): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5833): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/FlexNetS( 6405): updateSvcAllowedInSettings:false
,D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/FlexNetS( 6405): updateSvcAllowedInSettings:false
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6405): updateSvcAllowedInSettings:false
D/WifiService(  961): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/libc    ( 5833): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5833): [NET] android_getaddrinfofornet-, err=8
,D/FlexNetS( 6405): updateSvcAllowedInSettings:false
,D/WISPrService( 5833): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/FlexNetS( 6405): updateSvcAllowedInSettings:false
,D/FlexNetS( 6405): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6405): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6693): [38a.2.]  listen tmrbb8
,D/MdProvGlob( 6469): remove item 101 (p2d27in193) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6693): [38a.2.] summary 118:p2 ignore
,D/Process (  961): killProcessQuiet, pid=6168
I/ActivityManager(  961): Killing 6168:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  961): Recipient 6168
,D/BluetoothManagerService(  961): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/jxcore-log( 6631): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6631): 
I/jxcore-log( 6631): my name is : HTC-HTC One M8s_PT840
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): attempting to connect to test coordinator
I/jxcore-log( 6631): ,
I/jxcore-log( 6631): check test folder
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): found test : ./testFindPeers.js
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): found test : ./testReConnect.js,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): found test : ./testSendData.js,
,I/jxcore-log( 6631): 
,I/jxcore-log( 6631): Test app app.js loaded
,I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6631): 
,I/chromium( 6631): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,D/GpsLocationProvider(  961): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
D/ConnectivityService(  961): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  961): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  961): acquireWL(c3a492d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 961 1000 null
D/GpsLocationProvider(  961): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  961): [AlarmQueuing] connectivity wifi: false
D/htcCheckinService(  961): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  961): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1488): [onReceive] WIFI(1): DISCONNECTED,
,I/ActivityManager(  961): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6727 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  961): No APN found to select.
,D/PMS     (  961): releaseWL(c3a492d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6693): [fa8.1.]  listen tmrbb8
,D/MdScDataSum( 6693): [fa8.1.] summary 118:p1 ignore,
,I/MusicStore( 6727): Database version: 120,
,D/VoldConnector(  961): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6727): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  961): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6727): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  961): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6727): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 6727): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6727): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6727): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6727): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6727): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@229c85aa: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6727): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6727): GMSCore installation verified
,I/ConfigStore( 6727): Config Database version: 1,
,I/PackageManager(  961):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6727, uid=10159, userID:0,
,D/WifiDisplayAdapter(  961): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  961):     Client/Owner: Client
D/WifiDisplayAdapter(  961):     GroupId: 
D/WifiDisplayAdapter(  961):     Passphrase: 
D/WifiDisplayAdapter(  961):     SessionId: 0
D/WifiDisplayAdapter(  961):     IP Address: }
,D/MediaRouterService(  961): Client com.google.android.music (pid 6727): Registered,
,D/WifiDisplayAdapter(  961): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  961):     Client/Owner: Client
D/WifiDisplayAdapter(  961):     GroupId: 
D/WifiDisplayAdapter(  961):     Passphrase: 
D/WifiDisplayAdapter(  961):     SessionId: 0
D/WifiDisplayAdapter(  961):     IP Address: }
,I/MediaRouter( 6727): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6727): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/PackageManager(  961):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6727, uid=10159, userID:0,
,D/AutoSetting( 1575): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1575): Util - no network available!,
,D/AutoSetting( 1575): service - onCreate()
D/MobileConnectivityChangeReceiver( 5641): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5641): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1575): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  961): request 19b3399a passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  961): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1575): service - mHandler: cancel location update
D/AutoSetting( 1575): service -           changes count: 0
I/GHttpClientFactory( 6727): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/iu.Environment( 4239): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4239): num queued entries: 0
I/iu.UploadsManager( 4239): num updated entries: 0
,I/iu.SyncManager( 4239): NEXT; no task
I/GoogleURLConnFactory( 6727): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4239): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/ActivityManager(  961): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6769 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/Babel   ( 6493): connection state changed from UNKNOWN to DISCONNECTED
,D/Process (  961): killProcessQuiet, pid=6380
I/ActivityManager(  961): Killing 6380:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  961): Recipient 6380
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/VoldConnector(  961): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6769): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  961): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6769): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6769): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6769):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6769):   adb logcat -s GAv4
,D/VoldConnector(  961): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6769): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  961): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/,
,W/ContextImpl( 6769): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6769): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6769): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6769): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6769): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6769): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6769): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6769): Time to load native libraries: 4 ms (timestamps 7918-7922)
,I/LibraryLoader( 6769): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6769): Binding Chromium to main looper Looper (main, tid 1) {3a0ff3b5}
,I/LibraryLoader( 6769): Expected native library version number "",actual native library version number ""
,I/chromium( 6769): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6769): Initializing chromium process, singleProcess=true
,W/art     ( 6769): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6769): ApplicationContext is null in ApplicationStatus
,W/chromium( 6769): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
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
,E/WifiStateMachine(  961): handleMessage: E msg.what=131168,
E/WifiStateMachine(  961): processMsg: DisconnectedState
,E/WifiStateMachine(  961):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  961): processMsg: ConnectModeState
E/WifiStateMachine(  961):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  961): processMsg: DriverStartedState
E/WifiStateMachine(  961):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  961): processMsg: SupplicantStartedState
,E/WifiStateMachine(  961):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  961): processMsg: DefaultState
E/WifiStateMachine(  961):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  961): handleMessage: X
,I/NSApplication( 6769): Starting up...,
,I/ActivityManager(  961): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6827 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  961): killProcessQuiet, pid=6334,
I/ActivityManager(  961): Killing 6334:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,I/ActivityManager(  961): Recipient 6334
,I/art     (  961): Explicit concurrent mark sweep GC freed 36846(1933KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 2.105ms total 182.032ms
,D/Process (  961): killProcessQuiet, pid=6435,
I/ActivityManager(  961): Killing 6435:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  961): Recipient 6435
D/WifiService(  961): Client connection lost with reason: 4
,D/PMS     (  961): acquireWL(2b5d8ef6): PARTIAL_WAKE_LOCK  *alarm* 0x1 961 1000 WorkSource{10024}
V/AlarmManager(  961): sending alarm PendingIntent{a902f7: PendingIntentRecord{8e7b564 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=139933, Int=0
,D/PMS     (  961): acquireWL(1344e3cd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  961): releaseWL(2b5d8ef6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1872): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1872): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1872): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1872): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1872): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  961): releaseWL(1344e3cd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/BluetoothAdapter( 6631): 324960627: getState(). Returning 12,
I/jxcore-log( 6631): BLE supported!!
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(2f4ba482): PARTIAL_WAKE_LOCK  *alarm* 0x1 961 1000 WorkSource{10024},
,V/AlarmManager(  961): sending alarm PendingIntent{2de0d793: PendingIntentRecord{191cc3d0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141204, Int=0
D/PMS     (  961): releaseWL(2f4ba482): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(381386ce): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6727 10159 null,
,I/PackageManager(  961):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6727, uid=10159, userID:0
,I/MusicLeanback( 6727): Conditions not met for autocaching. okToAttempt=false
,D/PMS     (  961): releaseWL(381386ce): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 6727): Stop autocaching.
,D/WearableService( 4904): callingUid 10024, callindPid: 4904
,E/GmsUtils( 6727): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6727): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/ContactMessageStore( 1433): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1433): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,D/GpsLocationProvider(  961): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  961): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,D/AutoSetting( 1575): service - handleMessage() stop self
,D/AutoSetting( 1575): service - handleMessage() quit looper
,D/AutoSetting( 1575): service - onDestroy() END
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(16f05d39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
,I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(16f05d39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  961): updateBatteryInfo
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  961): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  961): runPSCheck
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  961): Checking...
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  961): >> updateStatus
,D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/WifiController(  961): handleMessage: E msg.what=155652
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
,I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,D/TelephonyReceiver( 1433): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  961): acquireWL(13d53f7e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 961 1000 WorkSource{1000}
V/AlarmManager(  961): sending alarm PendingIntent{2c8756: PendingIntentRecord{26b603d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149674, Int=0
V/AlarmManager(  961): sending alarm PendingIntent{4989cdf: PendingIntentRecord{2840ed2c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1449086902594, Int=0
,V/AlarmManager(  961): sending alarm PendingIntent{7f093f5: PendingIntentRecord{1301d58a com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190479, Int=0
D/PMS     (  961): acquireWL(199427fb): PARTIAL_WAKE_LOCK  *backup* 0x1 961 1000 null
,D/PMS     (  961): acquireWL(2f65b018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
W/BackupManagerService(  961): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  961): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  961): releaseWL(199427fb): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  961): releaseWL(2f65b018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  961): releaseWL(13d53f7e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,D/PMS     (  961): releaseWL(8ee287b): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  961): Failed to find a new network - expiring NetTransition Wakelock
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(1f11b5c4): PARTIAL_WAKE_LOCK  *alarm* 0x1 961 1000 WorkSource{1000}
V/AlarmManager(  961): sending alarm PendingIntent{39844cad: PendingIntentRecord{77f8be2 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=208764, Int=0
,D/PMS     (  961): releaseWL(1f11b5c4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1575): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@397b5a69
D/Process (  961): killProcessQuiet, pid=5859
I/ActivityManager(  961): Killing 5859:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  961): Recipient 5859
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  961): acquireWL(20b99b73): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(20b99b73): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  961): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  961): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  961): runPSCheck
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  961): Checking...
D/UsbnetService(  961): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  961): >> updateStatus
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  961): << updateStatus
D/WifiController(  961): handleMessage: E msg.what=155652
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
D/PMS     (  961): acquireWL(2a566a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(2a566a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  961): updateBatteryInfo
D/PMS     (  961): runPSCheck
D/HtcPowerSaver(  961): Checking...
I/HtcPowerSaver(  961): >> updateStatus
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  961): << updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/WifiController(  961): handleMessage: E msg.what=155652
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(2c4606a9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 961 1000 WorkSource{1000}
V/AlarmManager(  961): sending alarm PendingIntent{2c8756: PendingIntentRecord{26b603d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209674, Int=0
,V/AlarmManager(  961): sending alarm PendingIntent{25887bcf: PendingIntentRecord{21eff95c com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1449087087349, Int=0
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
D/PMS     (  961): releaseWL(2c4606a9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(a4f6465): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(a4f6465): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  961): BroadcastReceiver::onReceive+
,D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  961): updateBatteryInfo
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  961): handleMessage: E msg.what=155652
D/PMS     (  961): runPSCheck
D/WifiController(  961): processMsg: DeviceActiveState
D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): processMsg: StaEnabledState
I/HtcPowerSaver(  961): >> updateStatus
D/WifiController(  961): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  961): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(1f82b53a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
,D/PMS     (  961): releaseWL(1f82b53a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/NotificationService(  961): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  961): updateBatteryInfo
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  961): runPSCheck
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  961): Checking...
D/UsbnetService(  961): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  961): >> updateStatus
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/WifiController(  961): handleMessage: E msg.what=155652
D/WifiController(  961): battery changed pluggedType: 2
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
,I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(22bb05eb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(22bb05eb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  961): updateBatteryInfo
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  961): runPSCheck
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): handleMessage: E msg.what=155652
I/HtcPowerSaver(  961): >> updateStatus
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): battery changed pluggedType: 2
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/ContactMessageStore( 1433): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1433): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1433): sku_id=118
,D/ContactMessageStore( 1433): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1433): start background delete task...,
,D/ContactMessageStore( 1433): size: 0 , 0
,D/ContactMessageStore( 1433): Background delete complete
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(4314f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(4314f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  961): updateBatteryInfo
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/PMS     (  961): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): handleMessage: E msg.what=155652
I/HtcPowerSaver(  961): >> updateStatus
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
,I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(28d6e1e1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(28d6e1e1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  961): updateBatteryInfo
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/PMS     (  961): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): handleMessage: E msg.what=155652
I/HtcPowerSaver(  961): >> updateStatus
D/WifiController(  961): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): battery changed pluggedType: 2
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  961): acquireWL(3156eb06): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
I/BatteryService(  961): n_update end
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/PMS     (  961): releaseWL(3156eb06): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/WifiController(  961): battery changed pluggedType: 2
D/WifiController(  961): handleMessage: E msg.what=155652
D/HtcPowerSaver(  961): updateBatteryInfo
,D/WifiController(  961): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  961): processMsg: StaEnabledState
D/PMS     (  961): runPSCheck
D/WifiController(  961): processMsg: DefaultState
D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): handleMessage: X
I/HtcPowerSaver(  961): >> updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  961): acquireWL(a4215c7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(a4215c7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  961): updateBatteryInfo
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  961): runPSCheck
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): handleMessage: E msg.what=155652
I/HtcPowerSaver(  961): >> updateStatus
,D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(1fb017f4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 961 1000 WorkSource{1000}
,V/AlarmManager(  961): sending alarm PendingIntent{2c8756: PendingIntentRecord{26b603d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=389674, Int=0
I/bt-btm  ( 2925): Received oneshot timer event complete
V/AlarmManager(  961): sending alarm PendingIntent{1ffebb1d: PendingIntentRecord{11e6b192 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=939811, Int=0
I/bt-btm  ( 2925): btm_ble_timeout
D/PMS     (  961): acquireWL(12404763): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 2925 1002 null
I/bt-btm  ( 2925): btm_gen_resolvable_private_addr
,D/bt-btm  ( 2925): btm_ble_rand_enc_complete
I/bt-btm  ( 2925): btm_gen_resolve_paddr_low
D/bt-smp  ( 2925): smp_encrypt_data
W/bt-smp  ( 2925): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 2925): Plain text(LSB ~ MSB) = 07 e3 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2925): Encrypted text(LSB ~ MSB) = 16 05 9a 87 83 a8 9a 24 10 1a b2 f6 f0 92 a5 e4 
,I/bt-btm  ( 2925): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 2925): Stopping oneshot timer
D/bt-btm  ( 2925): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
D/PMS     (  961): releaseWL(1fb017f4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  961): releaseWL(12404763): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(34b0bf60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(34b0bf60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  961): updateBatteryInfo
D/PMS     (  961): runPSCheck
D/HtcPowerSaver(  961): Checking...
I/HtcPowerSaver(  961): >> updateStatus
,D/PowerUI ( 1221): closing low battery warning: level=100
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  961): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  961): << updateStatus
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/WifiController(  961): handleMessage: E msg.what=155652
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(2dd0ec19): PARTIAL_WAKE_LOCK  *alarm* 0x1 961 1000 WorkSource{1000},
V/AlarmManager(  961): sending alarm PendingIntent{18e50a0f: PendingIntentRecord{39300a9c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=808138, Int=0,
V/AlarmManager(  961): sending alarm PendingIntent{2c8756: PendingIntentRecord{26b603d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=989674, Int=0
,I/ActivityManager(  961): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6868 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  961): sending alarm PendingIntent{1e3a54de: PendingIntentRecord{2665f6bf com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1449087477189, Int=0
V/AlarmManager(  961): sending alarm PendingIntent{152718c: PendingIntentRecord{3ef8ec08 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449087697762, Int=0
,I/ActivityManager(  961): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6882 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/ContextImpl( 6882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  961): releaseWL(2dd0ec19): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6882): MY_DEBUG = false,
,D/PowerUsageService( 6882): repeat time = 1449088620299,
,E/cutils-trace( 6912): Error opening trace file: Permission denied (13),
I/dex2oat ( 6912): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,I/dex2oat ( 6912): dex2oat: override thread count:4
,I/PowerUsageList:PowerUsageHelper( 6882): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6882): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6882): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6882): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 6882): calcPower(), no data
,D/Process (  961): killProcessQuiet, pid=5778
I/ActivityManager(  961): Killing 5778:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  961): Recipient 5778
,I/dex2oat ( 6912): dex2oat took 662.940ms (threads: 4)
,I/PushClient( 6868): ApplicationMonitor {30445ca9}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6868): ApplicationMonitor {30445ca9}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6868): ApplicationMonitor {30445ca9}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6868): ApplicationMonitor {30445ca9}: logBasicAppInfo(): VersionCode:             148001224,
I/PushClient( 6868): ApplicationMonitor {30445ca9}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk,
,I/PushClient( 6868): ApplicationMonitor {30445ca9}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6868): ApplicationMonitor {30445ca9}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6868): ApplicationMonitor {30445ca9}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6868): ApplicationMonitor {30445ca9}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6868): PnsModel {1ca05830}: update(): Update registration caused by: alarm
,I/PushClient( 6868): PnsConfigModel {38f21bc7}: <init>(): Use dm-client for provisioning.
,W/System.err( 6868): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6868): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6868): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6868): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  961): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6919 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6919): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6919 dbg=false s=true,
,I/DeviceManagement( 6919): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6919): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6919): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6919): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6919): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@135e8173] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6919): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6919): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6919): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6919): SessionStateController: Checking invariants...
,I/DeviceManagement( 6919): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6919): SessionStateController: Checking invariants...
,I/DeviceManagement( 6919): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6919): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@135e8173],
,I/DeviceManagement( 6919): WorkflowService: Stopping workflow service
,D/Process (  961): killProcessQuiet, pid=6556
I/ActivityManager(  961): Killing 6556:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6868): PnsModel {1ca05830}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  961): Recipient 6556
,D/Process (  961): killProcessQuiet, pid=6523,
,I/ActivityManager(  961): Killing 6523:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  961): Recipient 6523
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(793b18e): PARTIAL_WAKE_LOCK  *alarm* 0x1 961 1000 WorkSource{1000},
V/AlarmManager(  961): sending alarm PendingIntent{1bd00daf: PendingIntentRecord{1b55bc com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449087741620, Int=0
,D/SmartSyncUtils( 6882): isEpsOn(), nState = 0
,D/PMS     (  961): acquireWL(2b2af945): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6882 1000 null
,D/PMS     (  961): releaseWL(793b18e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  961): releaseWL(2b2af945): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  961): acquireWL(99d589a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6882 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6882): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6882): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6882): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6882): SettingOnTime = 1449122400000, randomSettingOnTime = 1449120588000
D/SmartSyncScreenOnOffTimeReceiver( 6882): SettingOffTime = 1449100800000, randomSettingOffTime = 1449103800000
,D/SmartSyncScreenOnOffTimeReceiver( 6882): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6882): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6882): bNightModeTurnOffOnce = false
,D/PMS     (  961): releaseWL(99d589a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  961): acquireWL(2a19d5cb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  961): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  961): releaseWL(2a19d5cb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  961): updateBatteryInfo
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  961): runPSCheck
D/UsbnetService(  961): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): handleMessage: E msg.what=155652
I/HtcPowerSaver(  961): >> updateStatus
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): battery changed pluggedType: 2
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
,I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(322611a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
,I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(322611a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  961): plugged=true pluggin=true
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  961): battery changed pluggedType: 2
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  961): updateBatteryInfo
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/PMS     (  961): runPSCheck
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  961): Checking...
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  961): >> updateStatus
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/WifiController(  961): handleMessage: E msg.what=155652
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  961): handleMessage: X
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/UsageStatsService(  961): User[0] Flushing usage stats to disk
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(386e4c1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  961): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  961): releaseWL(386e4c1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  961): updateBatteryInfo
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/PMS     (  961): runPSCheck
D/UsbnetService(  961): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  961): Checking...
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  961): >> updateStatus
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/WifiController(  961): battery changed pluggedType: 2
D/WifiController(  961): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(8686466): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null,
I/BatteryService(  961): n_update end,
D/UsbnetService(  961): BroadcastReceiver::onReceive+,
D/PMS     (  961): releaseWL(8686466): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/NotificationService(  961): plugged=true pluggin=true
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  961): updateBatteryInfo
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/PMS     (  961): runPSCheck
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  961): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  961): >> updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  961): battery changed pluggedType: 2
D/WifiController(  961): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  961): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  961): processMsg: StaEnabledState
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  961): processMsg: DefaultState
I/HtcPowerSaver(  961): << updateStatus
D/WifiController(  961): handleMessage: X
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  961): acquireWL(2fee03a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  961): n_update end
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  961): releaseWL(2fee03a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  961): updateBatteryInfo
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/PMS     (  961): runPSCheck
D/WifiController(  961): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): processMsg: DeviceActiveState
I/HtcPowerSaver(  961): >> updateStatus
D/WifiController(  961): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(279ea054): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  961): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  961): releaseWL(279ea054): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  961): updateBatteryInfo
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  961): runPSCheck
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): handleMessage: E msg.what=155652
I/HtcPowerSaver(  961): >> updateStatus
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(85c0bfd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(85c0bfd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/WifiController(  961): handleMessage: E msg.what=155652
D/WifiController(  961): battery changed pluggedType: 2
D/WifiController(  961): processMsg: DeviceActiveState
D/HtcPowerSaver(  961): updateBatteryInfo
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/PMS     (  961): runPSCheck
D/WifiController(  961): handleMessage: X
D/HtcPowerSaver(  961): Checking...
I/HtcPowerSaver(  961): >> updateStatus
,I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(1d8660f2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(1d8660f2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  961): updateBatteryInfo
D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  961): runPSCheck
,D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  961): Checking...
D/WifiController(  961): handleMessage: E msg.what=155652
I/HtcPowerSaver(  961): >> updateStatus
D/WifiController(  961): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  961): processMsg: StaEnabledState
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X
,I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(36f6dc0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 961 1000 WorkSource{1000}
V/AlarmManager(  961): sending alarm PendingIntent{2c8756: PendingIntentRecord{26b603d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1049674, Int=0
,V/AlarmManager(  961): sending alarm PendingIntent{c626af9: PendingIntentRecord{38159a3e com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1839825, Int=0
I/bt-btm  ( 2925): Received oneshot timer event complete
I/bt-btm  ( 2925): btm_ble_timeout
I/bt-btm  ( 2925): btm_gen_resolvable_private_addr
,D/PMS     (  961): acquireWL(25c09f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 2925 1002 null
,D/bt-btm  ( 2925): btm_ble_rand_enc_complete
I/bt-btm  ( 2925): btm_gen_resolve_paddr_low
D/bt-smp  ( 2925): smp_encrypt_data
W/bt-smp  ( 2925): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 2925): Plain text(LSB ~ MSB) = 0e 32 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2925): Encrypted text(LSB ~ MSB) = d2 2c 5e f4 c6 8d 15 ad 2e 0d 91 1d 5e e9 c7 15 
,I/bt-btm  ( 2925): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 2925): Stopping oneshot timer
D/bt-btm  ( 2925): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  961): Prepared write state in 25ms,
,I/ProcessStatsService(  961): Prepared write state in 9ms,
,I/ProcessStatsService(  961): Prepared write state in 7ms,
,I/ProcessStatsService(  961): Prepared write state in 7ms,
,D/PMS     (  961): releaseWL(36f6dc0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/ProcessStatsService(  961): Pruning old procstats: /data/system/procstats/state-2015-12-02-11-14-32.bin,
,D/PMS     (  961): releaseWL(25c09f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(2abda5ec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 961 1000 null
I/BatteryService(  961): n_update end
D/PMS     (  961): releaseWL(2abda5ec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/HeadsetStateMachine( 2925): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  961): plugged=true pluggin=true
D/UsbnetService(  961): BroadcastReceiver::onReceive+
D/WifiController(  961): battery changed pluggedType: 2
D/UsbnetService(  961): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  961):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  961): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  961): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  961): runPSCheck
D/WifiController(  961): handleMessage: E msg.what=155652
D/HtcPowerSaver(  961): Checking...
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  961): >> updateStatus
D/WifiController(  961): processMsg: DeviceActiveState
D/WifiController(  961): processMsg: StaEnabledState
D/WifiController(  961): processMsg: DefaultState
D/WifiController(  961): handleMessage: X,
,I/HtcPowerSaver(  961): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  961): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,D/PMS     (  961): acquireWL(3bd5bdb5): PARTIAL_WAKE_LOCK  *alarm* 0x1 961 1000 WorkSource{1000}
V/AlarmManager(  961): sending alarm PendingIntent{18e50a0f: PendingIntentRecord{39300a9c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1709701, Int=0
V/AlarmManager(  961): sending alarm PendingIntent{919d740: PendingIntentRecord{3b165679 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825969, Int=1800000
V/AlarmManager(  961): sending alarm PendingIntent{2c8756: PendingIntentRecord{26b603d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1889675, Int=0
V/AlarmManager(  961): sending alarm PendingIntent{8cd1c4a: PendingIntentRecord{292fc7bb com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449088430418, Int=1800000
,V/AlarmManager(  961): sending alarm PendingIntent{dd534d8: PendingIntentRecord{10f18031 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1851693, Int=0
V/AlarmManager(  961): sending alarm PendingIntent{22c8b316: PendingIntentRecord{3ef8ec08 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449088620299, Int=0
D/PMS     (  961): acquireWL(f092497): PARTIAL_WAKE_LOCK  NetworkStats 0x1 961 1000 null
,D/PMS     (  961): releaseWL(f092497): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  961): updateNetworkEnabledLocked()
V/NetworkPolicy(  961): updateNotificationsLocked()
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  961): acquireWL(13d4c684): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4239 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  961): acquireWL(1d14eaa2): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4239 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  961): releaseWL(13d4c684): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  961): releaseWL(3bd5bdb5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
D/PowerUsageList:PowerUsageHelper( 6882): MY_DEBUG = false
,D/PowerUsageService( 6882): repeat time = 1449089520384,
,I/EventLogService( 4239): Aggregate from 1449086832200 (log), 1449086630359 (data),
,D/LocationManagerService(  961): getAllProviders()=[passive, gps, network],
,D/PMS     (  961): releaseWL(1d14eaa2): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1872): Explicit concurrent mark sweep GC freed 14770(809KB) AllocSpace objects, 7(588KB) LOS objects, 49% free, 4MB/8MB, paused 959us total 55.189ms
,I/PowerUsageList:PowerUsageHelper( 6882): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6882): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6882): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6882): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 6882): calcPower(), no data,
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 6962): Error opening trace file: Permission denied (13)
I/jxcore-log( 6631): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6631): 
D/CustomizationManager( 6962): ====startRecUseTime====
D/htc.customization.log.level( 6962):  is 
W/CustomizationLogLevel( 6962): Level value is invalid, use default level 2
D/CustomizationManager( 6962):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6962): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6962): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6962): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6962): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6962): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6962): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6962): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6962): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6962): Parsing tag category name = system
I/CustomizationCIDLoader( 6962): Parsing tag category name = application
I/CustomizationCIDLoader( 6962): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6962): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6962): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6962): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6962): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6962): add string-array item, value = 42507
I/CustomizationCIDLoader( 6962): add string-array item, value = 21902
I/CustomizationCIDLoader( 6962): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6962): add string-array item, value = 23420
I/CustomizationCIDLoader( 6962): add string-array item, value = 22299
I/CustomizationCIDLoader( 6962): add string-array item, value = 24002
I/CustomizationCIDLoader( 6962): add string-array item, value = 23210
I/CustomizationCIDLoader( 6962): add string-array item, value = 23205
I/CustomizationCIDLoader( 6962): add string-array item, value = 23806
I/CustomizationCIDLoader( 6962): add string-array item, value = 23430
I/CustomizationCIDLoader( 6962): add string-array item, value = 23408
I/CustomizationCIDLoader( 6962): add string-array item, value = 27205
I/CustomizationCIDLoader( 6962): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6962): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6962):  Read CID file spent 0.112 (s)
D/CustomizationManager( 6962):  All configurations done spent 0.113 (s)
D/PackageManager(  961): deletePackageAsUser: pkg=com.test.thalitest, pid=6962, uid=2000 userid=0
I/ActivityManager(  961): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  961): killProcessQuiet, pid=6631
I/ActivityManager(  961): Killing 6631:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  961): Skipping PackageSetting{2db563de com.example.hello/10373} due to missing metadata
I/WindowState(  961): WIN DEATH: Window{58b3c03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  961): Recipient 6631
D/WifiService(  961): Client connection lost with reason: 4
E/InputEventReceiver( 1381): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{397b955f uid 10366 pid 6631} (c)'
D/Process (  961): killProcessQuiet, pid=6827
I/ActivityManager(  961): Killing 6827:com.android.chrome/u0a96 (adj 13): empty for 1803s
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  961): Recipient 6827
D/Process (  961): killProcessQuiet, pid=6769
I/ActivityManager(  961): Killing 6769:com.google.android.apps.magazines/u0a161 (adj 13): empty for 1804s
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  961): Recipient 6769
D/Process (  961): killProcessQuiet, pid=5641
I/ActivityManager(  961): Killing 5641:com.google.android.setupwizard/u0a77 (adj 13): empty for 1804s
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  961): Recipient 5641
D/Process (  961): killProcessQuiet, pid=6405
I/ActivityManager(  961): Killing 6405:com.htc.bgp/u0a11 (adj 13): empty for 1804s
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  961): Recipient 6405
D/Process (  961): killProcessQuiet, pid=6693
I/ActivityManager(  961): Killing 6693:com.htc.mobiledata:remote/u0a46 (adj 13): empty for 1805s
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  961): Recipient 6693
D/Process (  961): killProcessQuiet, pid=6469
I/ActivityManager(  961): Killing 6469:com.htc.mobiledata/u0a46 (adj 15): empty for 1805s
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  961): Recipient 6469
D/Process (  961): killProcessQuiet, pid=5833
I/ActivityManager(  961): Killing 5833:com.android.settings/1000 (adj 15): empty for 1808s
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  961): Recipient 5833
D/WifiService(  961): Client connection lost with reason: 4
I/ActivityManager(  961):   Force finishing activity ActivityRecord{2962a74c u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  961): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
W/ActivityManager(  961): Spurious death for ProcessRecord{c64cc20 6631:com.test.thalitest/u0a366}, curProc for 6631: null
W/SystemReader(  961): Cannot find grip_rejection_width, use default value instead
D/DotMatrix( 1309): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1309): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  961): acquireWL(383f0f9e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1811 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1811): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1708): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  961): releaseWL(383f0f9e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1708): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1673): Cleaning up data for package: com.test.thalitest
I/[PluginManager]RegisterService( 1575): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/art     ( 1488): Explicit concurrent mark sweep GC freed 6385(331KB) AllocSpace objects, 6(400KB) LOS objects, 34% free, 29MB/45MB, paused 1.346ms total 70.231ms
D/AccTypeManager( 1708): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Prism.ItemManager( 1488): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
D/PhoneApp( 1433): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1488): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/Prism.PackageStateRece_( 1488): action: android.intent.action.PACKAGE_REMOVED
I/Launcher( 1488): Deferring update until onResume
D/Launcher( 1488): waitUntilResume // bindAppsRemoved
I/[PluginManager]RegisterService( 1575): handle notify Blinkfeed plugin client changed
E/ExternalAccountType( 1708): Unsupported attribute readOnly
I/ActivityManager(  961): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/InputMethodManagerService(  961): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/art     (  446): Explicit concurrent mark sweep GC freed 8642(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 218us total 25.740ms
I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 135us total 19.126ms
W/ResourcesManager(  961): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 133us total 16.282ms
I/art     (  961): Explicit concurrent mark sweep GC freed 39538(2MB) AllocSpace objects, 15(1692KB) LOS objects, 33% free, 16MB/25MB, paused 1.848ms total 198.636ms
I/art     (  961): WaitForGcToComplete blocked for 198.413ms for cause Explicit
W/PackageManager(  961): Unable to load service info ResolveInfo{75059ae com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  961): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  961): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  961): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  961): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  961): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  961): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  961): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  961): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  961): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  961): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  961): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  961): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  961): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  961): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  961): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  961): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/ContextImpl( 6982): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/JobSchedulerService(  961): Receieved: android.intent.action.PACKAGE_REMOVED
D/StatusBarManagerService(  961): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  961): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  961): hiding MENU key
D/TaskPersister(  961): removeObsoleteFile: deleting file=8_task.xml
D/StatusBarManagerService(  961): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  961): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  961): hiding MENU key
D/FindExtension( 1488): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1488): Defer allocateBuffers to drawing time
I/ActivityManager(  961): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/InputMethodManagerService(  961): Got RemoteException sending setActive(false) notification to pid 6631 uid 10366
D/StatusBarManagerService(  961): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/art     (  961): Explicit concurrent mark sweep GC freed 8839(595KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.997ms total 199.396ms
I/ActivityManager(  961): Killing 5928:com.google.android.apps.plus/u0a167 (adj 15): empty for 1804s
D/Process (  961): killProcessQuiet, pid=5928
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  961): Recipient 5928
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7007): -onCreate()
V/Settings:HtcSettingsApplication( 7007): [7007/7007] onCreate()
I/ActivityManager(  961): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7033 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  961): killProcessQuiet, pid=6493
I/ActivityManager(  961): Killing 6493:com.google.android.talk/u0a112 (adj 15): empty for 1803s
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/Settings:HtcWirelessFeatureFlags( 7007): id/is att sku: 118/false
E/Settings:HtcWrapHeaderInfo( 7007): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7007): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7007): updateDevelopment, bPrefShow = true
I/ActivityManager(  961): Recipient 6493
E/Settings:HtcUmcWidgetEnabler( 7007): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]support         :false
I/ActivityManager(  961): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7007): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7007): isSupportVoWifi: null
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7007): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7007): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7007): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7007): [supportHomeButton]support         :false
I/ActivityManager(  961): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7007): isSupportVoWifi: null
E/ActivityThread( 7007): Failed to find provider info for com.htc.vowifi
I/PackageManager(  961):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7033, uid=10072, userID:0
W/global  ( 7033): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 7033): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 7033): [apache-http] Connection GC has been deprecated!
W/global  ( 7033): [apache-http] Connection GC has been deprecated!
E/RollingFileStream( 7033): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 7033): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  961): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7075 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 7033): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7033): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 7033): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 7033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 7033): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7033): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7033): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7033): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 7033): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 7033): Process: com.android.vending, PID: 7033
E/AndroidRuntime( 7033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7033): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 7033): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 7033): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 7033): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 7033): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7033): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7033): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  961): App crashed! Process: com.android.vending
E/SQLiteDatabase( 7033): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 7033): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7033): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7033): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7033): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7033): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7033): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 7033): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 7033): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 7033): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 7033): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 7033): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 7033): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 7033): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 7033): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 7033): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 7033): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 7033): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 7033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 7033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 7033): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 7033): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 7033): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 7033): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 7033): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 7033): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 7033): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 7033): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 7033): 	... 4 more
D/Process (  961): killProcessQuiet, pid=6727
I/ActivityManager(  961): Killing 6727:com.google.android.music:main/u0a159 (adj 15): empty for 1802s
E/DropBoxManagerService(  961): Can't write: system_app_crash
E/DropBoxManagerService(  961): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  961): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  961): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  961): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  961): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  961): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  961): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  961): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  961): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  961): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  961): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  961): 	... 5 more
D/Process (  961): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
I/PackageManager(  961):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7033, uid=10072, userID:0
E/SQLiteDatabase( 7033): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 7033): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 7033): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7033): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7033): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7033): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7033): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7033): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 7033): crash in the same process: AsyncTask #3
E/AndroidRuntime_3_crash( 7033): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 7033): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 7033): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 7033): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 7033): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 7033): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 7033): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 7033): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 7033): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 7033): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 7033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 7033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 7033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 7033): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 7033): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 7033): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 7033): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 7033): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 7033): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 7033): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 7033): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 7033): 	... 4 more
I/ActivityManager(  961): Recipient 6727
D/MediaRouterService(  961): Client com.google.android.music (pid 6727): Died!
I/Prism.ItemManager( 1488): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1488): loadItems() com.htc.launcher.pageview.WidgetManager@1f5f012c +
I/Prism.WidgetManager( 1488): onLoadItems() +
D/Process ( 7033): killProcess, pid=7033
D/Process ( 7033): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
W/ResourcesManager( 1488): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 7075): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7075): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7075): VM with version 2.1.0 has multidex support
I/MultiDex( 7075): install
I/MultiDex( 7075): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7075): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 7075): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7075): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c5fdbc0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7075): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  961): Recipient 7033
I/ActivityManager(  961): Process com.android.vending (pid 7033) has died
D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 5
I/TrimMemoryManager( 1488): [trimMemory] 5
D/ChimeraCfgMgr( 4239): Loading module com.google.android.gms.kids from APK com.google.android.gms
E/SQLiteLog( 1872): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1872): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x558d5803e0
W/NativeLibraryUtils( 7075): Failed to open lock file
W/NativeLibraryUtils( 7075): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7075): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7075): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7075): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7075): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7075): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7075): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7075): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7075): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7075): 	... 3 more
E/AndroidRuntime( 1872): FATAL EXCEPTION: main
E/AndroidRuntime( 1872): Process: com.google.process.gapps, PID: 1872
E/AndroidRuntime( 1872): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1872): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1872): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1872): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1872): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1872): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1872): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1872): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1872): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1872): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1872): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1872): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1872): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1872): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1872): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1872): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1872): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1872): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1872): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1872): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1872): 	... 9 more
E/ActivityManager(  961): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  961): Can't write: system_app_crash
E/DropBoxManagerService(  961): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  961): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  961): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  961): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  961): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  961): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  961): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  961): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  961): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  961): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  961): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  961): 	... 5 more
D/Process ( 1872): killProcess, pid=1872
D/Process ( 1872): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/ResourcesManager( 1488): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.

```
