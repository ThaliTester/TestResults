#### Test 506502789b39735_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6672): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6672): ====startRecUseTime====
D/htc.customization.log.level( 6672):  is 
W/CustomizationLogLevel( 6672): Level value is invalid, use default level 2
D/CustomizationManager( 6672):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 6672): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6672): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6672): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6672): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6672): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6672): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6672): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6672): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6672): Parsing tag category name = system
I/CustomizationCIDLoader( 6672): Parsing tag category name = application
I/CustomizationCIDLoader( 6672): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6672): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6672): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6672): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6672): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6672): add string-array item, value = 42507
I/CustomizationCIDLoader( 6672): add string-array item, value = 21902
I/CustomizationCIDLoader( 6672): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6672): add string-array item, value = 23420
I/CustomizationCIDLoader( 6672): add string-array item, value = 22299
I/CustomizationCIDLoader( 6672): add string-array item, value = 24002
I/CustomizationCIDLoader( 6672): add string-array item, value = 23210
I/CustomizationCIDLoader( 6672): add string-array item, value = 23205
I/CustomizationCIDLoader( 6672): add string-array item, value = 23806
I/CustomizationCIDLoader( 6672): add string-array item, value = 23430
I/CustomizationCIDLoader( 6672): add string-array item, value = 23408
I/CustomizationCIDLoader( 6672): add string-array item, value = 27205
I/CustomizationCIDLoader( 6672): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6672): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6672):  Read CID file spent 0.107 (s)
D/CustomizationManager( 6672):  All configurations done spent 0.108 (s)
--------- beginning of system
D/PMS     (  947): acquireHCC(807cb19): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 947 1000 null
I/ActivityManager(  947): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6672 on display 0
D/PMS     (  947): acquireHCC(398947de): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 947 1000 null
I/ActivityManager(  947): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6690 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  947): Killing 5600:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=5600
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  947): Recipient 5600
,D/DotMatrix( 1333): [EventService]  onDisplayChanged: 0
V/ActivityManager(  947): Display changed displayId=0
D/DotMatrix( 1333): [EventService] mbHDMIConnect: false, mCoverOn:false
,I/TrimMemoryManager( 1583): [trimMemory] 20
,I/WebViewFactory( 6690): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6690): Time to load native libraries: 9 ms (timestamps 1027-1036),
,I/LibraryLoader( 6690): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6690): Binding Chromium to main looper Looper (main, tid 1) {14c89da6},
I/LibraryLoader( 6690): Expected native library version number "",actual native library version number ""
,I/chromium( 6690): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6690): Initializing chromium process, singleProcess=true,
,W/art     ( 6690): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6690): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6690): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6690): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6690): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6690): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6690): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6690): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6690): Local Branch: 
I/Adreno-EGL( 6690): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6690): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6690):                  d74aa161a12b9c6fc6332151
,W/System.err(  947): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  947): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  947): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  947): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  947): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  947): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@175555b7:true
,D/BluetoothAdapter( 6690): 649037373: getState(). Returning 12
,W/art     ( 6690): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6690): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6690): CordovaWebView is running on device made by: HTC
,W/art     ( 6690): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6690): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6690): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/HtcSystemUPManager(  947): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  947): setSystemUiVisibility(0xc0000000),
,D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  947): hiding MENU key
D/StatusBarManagerService(  947): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  947): hiding MENU key
,D/FindExtension( 6690): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6690): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1c08630, mServedView=org.apache.cordova.engine.SystemWebView{20fbf2a9 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@26ec002e,
,I/InputMethodManagerService(  947): Disable input method client, pid=1583,
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/StatusBarManagerService(  947): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6690): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  947): Displayed com.test.thalitest/.MainActivity: +641ms (total +892ms)
,W/BindingManager( 6690): Cannot call determinedVisibility() - never saw a connection for the pid: 6690,
,D/JsMessageQueue( 6690): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6690): JniHelper::setJavaVM(0xab3128f8), pthread_self() = -1402797936,
D/JX-Cordova( 6690): jxcore cordova android initializing
,W/jxcore-log( 6690): Initializing JXcore engine,
W/jxcore-log( 6690): JXcore engine is ready
,W/jxcore-log( 6690): Starting JXcore engine,
,D/PMS     (  947): releaseHCC(807cb19): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  947): releaseHCC(398947de): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6690): Platform android,
W/jxcore-log( 6690): 
W/jxcore-log( 6690): Process ARCH arm
W/jxcore-log( 6690): 
,I/jxcore-log( 6690): JXcore Cordova bridge is ready!
I/jxcore-log( 6690): 
W/jxcore-log( 6690): JXcore engine is started
,I/Choreographer( 6690): Skipped 94 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6690): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6690): Toggling radios to true,
I/jxcore-log( 6690): 
D/BluetoothAdapter( 6690): enable(): BT is already enabled..!
,D/WifiService(  947): New client listening to asynchronous messages,
,E/WifiTrafficPoller(  947): ADD_CLIENT: 8,
D/WifiService(  947): setWifiEnabled: true pid=6690, uid=10366
D/WifiManager( 6690): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366,
E/WifiService(  947): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  947): MONITOR_LOG
,I/WifiService(  947): isSprintWifiRestricted(): false
W/Settings:Agent(  947): name: wifi_on
I/WifiService(  947): isMdmWifiRestricted(): false
W/Settings:Agent(  947): value: 2,
W/Settings:Agent(  947): >> traceCallingStack()
W/Settings:Agent(  947): Process.myPid(): 947
W/Settings:Agent(  947): Process.myTid(): 1624
,W/Settings:Agent(  947): Process.myUid(): 1000
W/Settings:Agent(  947): 
W/Settings:Agent(  947): 
W/System.err(  947): java.lang.Throwable: stack dump
,W/System.err(  947): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  947): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  947): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  947): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  947): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  947): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  947): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  947): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  947): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  947): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  947): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  947): 
W/Settings:Agent(  947): << traceCallingStack(): 21(ms)
D/WifiController(  947): handleMessage: E msg.what=155656
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): handleMessage: X
,D/WifiManager( 6690): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  947): handleMessage: E msg.what=131145
D/WifiManager( 6690): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
I/jxcore-log( 6690): Radios toggled
I/jxcore-log( 6690): 
E/WifiStateMachine(  947):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1321): wlan0: Cancelling scan request
D/wpa_supplicant( 1321): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1321): TDLS: Tear down peers
D/wpa_supplicant( 1321): wpa_driver_nl80211_disconnect(reason_code=3)
D/BluetoothManagerService(  947): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6690): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6690): 
,I/jxcore-log( 6690): Perf Test app loaded loaded
I/jxcore-log( 6690): 
,I/jxcore-log( 6690): check test folder
I/jxcore-log( 6690): 
,I/jxcore-log( 6690): found test : ./testFindPeers.js,
I/jxcore-log( 6690): 
,D/wpa_supplicant( 1321): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1321): wlan0: Deauthentication notification
D/wpa_supplicant( 1321): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1321): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1321): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1321): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1321): enter disconnect check
I/wpa_supplicant( 1321): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/Tethering(  947): interfaceLinkStateChanged wlan0, false
D/Tethering(  947): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1321): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1321): wlan0: Ignore connection failure indication since interface has been put into disconnected state
,D/Tethering(  947): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  947): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  947): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  947): interfaceLinkStateChanged wlan0, false
D/Tethering(  947): interfaceStatusChanged wlan0, false
D/Tethering(  947): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  947): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  947): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  947): acquireWL(2bd4b79f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 947 1000 null
D/UsbnetService(  947): BroadcastReceiver::onReceive-
,D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  947): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  947): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  947): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1321): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1321): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1321): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1321): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 1321): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a160df88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
D/wpa_supplicant( 1321):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1321): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1321): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1321): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1321): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1321): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1321): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1321): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1321): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1321): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1321): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1321): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1321): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1321): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1321): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1321): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1321): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1321): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1321): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1321): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  947): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  947): handleMessage: new destination call exit/enter
E/WifiStateMachine(  947): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiMonitor(  947): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  947): invokeExitMethods: ConnectedState
,E/WifiStateMachine(  947): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  947): release()
E/WifiStateMachine(  947): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  947): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  947): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  947): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  947): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  947): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  947): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  947): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1321): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
,D/wpa_supplicant( 1321): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1321): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1321): wlan0: Control interface command 'SAVE_CONFIG'
D/WifiP2pService(  947): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1321): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WifiP2pService(  947): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1321): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1321): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  947): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1321): Power_Mode_Type mode = 0
I/wpa_supplicant( 1321): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1321): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  947): setDhcpActive: false
,V/NativeCrypto( 1968): Read error: ssl=0x55a7e5fd30: I/O error during system call, Connection timed out
,D/PMS     (  947): acquireWL(1d7ed0ec): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1968 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
D/TetherSettings( 5912): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5912): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5912): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 5912): Cust_ConnectToPC   : spcsc>false
D/        ( 5912): Cust_ConnectToPC   : IPT>true
D/        ( 5912): Cust_ConnectToPC   : Singel_USB>false
V/NativeCrypto( 1968): SSL shutdown failed: ssl=0x55a7e5fd30: I/O error during system call, Broken pipe
E/WifiStateMachine(  947): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  947): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  947): NetworkAgent != null
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 13
V/NetworkPolicy(  947): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  947): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): DefaultState{ when=-2ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  947): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/Settings( 5912): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiDataStallTracker(  947): stopDataStallAlarm 
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  947): ENABLE_DATA_MONITOR_POLL false Token 3
I/jxcore-log( 6690): found test : ./testSendData.js
I/jxcore-log( 6690): 
,I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/PMS     (  947): releaseWL(1d7ed0ec): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  947): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  947): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  947): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1321): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1321): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1321): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/SmartNS_Utility( 5912): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5912): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5912): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1321): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1321): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1321): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1321): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  947): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  947): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  947): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  947):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  947): Start Disconnecting Watchdog 1
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131146
E/WifiStateMachine(  947): processMsg: DisconnectingState
E/WifiStateMachine(  947):  DisconnectingState CMD_RECONNECT 0 0
D/PMS     (  947): releaseWL(2bd4b79f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  947): processMsg: ConnectModeState
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
E/WifiStateMachine(  947):  ConnectModeState CMD_RECONNECT 0 0
V/NetworkPolicy(  947): updateNotificationsLocked()
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1321): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1321): Fast associate: Old scan results
D/wpa_supplicant( 1321): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1321): wpa_supplicant_scan enter
D/wpa_supplicant( 1321): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1321): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1321): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1321): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1321): WPS:  * Request Type
D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1321): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1321): WPS:  * UUID-E
D/wpa_supplicant( 1321): WPS:  * Primary Device Type
D/wpa_supplicant( 1321): WPS:  * RF Bands (3)
D/wpa_supplicant( 1321): WPS:  * Association State
D/wpa_supplicant( 1321): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1321): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1321): WPS:  * Manufacturer
D/wpa_supplicant( 1321): WPS:  * Model Name
D/wpa_supplicant( 1321): WPS:  * Model Number
D/wpa_supplicant( 1321): WPS:  * Device Name
D/wpa_supplicant( 1321): WPS:  * Version2 (0x20)
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1321): P2P: * P2P IE header
D/wpa_supplicant( 1321): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1321): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1321): wlan0: Add radio work 'scan'@0x55a15f2ac0
D/wpa_supplicant( 1321): wlan0: First radio work item in the queue - schedule start immediately
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1321): wlan0: Starting radio work 'scan'@0x55a15f2ac0 after 0.000125 second wait
D/wpa_supplicant( 1321): wlan0: nl80211: scan request
D/HTCRequest(  947): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1321): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1321): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1321): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1321): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1321): wlan0: Own scan request started a scan in 0.000270 seconds
E/WifiStateMachine(  947): handleMessage: X
I/wpa_supplicant( 1321): wlan0: CTRL-EVENT-SCAN-STARTED 
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange(): SSID
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  947): handleMessage: E msg.what=131101
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  947): processMsg: DisconnectingState
D/WifiMonitor(  947): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  947): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  947): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  947):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  947): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  947): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=147460
E/WifiStateMachine(  947): processMsg: DisconnectingState
E/WifiStateMachine(  947):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=134650
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=134651
E/WifiStateMachine(  947): ConnectModeState: Network connection lost 
E/WifiStateMachine(  947): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  947): handleMessage: new destination call exit/enter
E/WifiStateMachine(  947): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  947): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  947): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  947): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  947): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  947): DisconnectedState call setCountryCode()
E/WifiStateMachine(  947):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1321): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1321): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1321): wlan0: Cancelling scan request
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): Validated
W/ContextImpl( 5912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5912): setISNotification
D/SmartNS_Utility( 5912): usb_cable_connect = 1
D/SmartNS_Utility( 5912): usb_denied = 0
,I/SmartNS_PSService( 5912): usb notificaiton:true
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1321): wlan0: nl80211: sched_scan request
I/ActionCombine( 5912): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/SmartNS_Utility( 5912): usb_cable_connect = 1
D/SmartNS_Utility( 5912): usb_denied = 0
I/SmartNS_PSService( 5912): usb notificaiton:true
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1222): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
D/SmartNS_NSReceiver( 5912): Tethered state change:false isNSOpening:false
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/wpa_supplicant( 1321): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1321): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1321): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1321): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1321): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1321): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1321): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1321): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1321): wlan0: Scan completed in 0.054250 seconds
D/wpa_supplicant( 1321): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1321): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59,
D/wpa_supplicant( 1321): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1321): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1321): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1321): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1321): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1321): wlan0: Radio work 'scan'@0x55a15f2ac0 done in 0.055964 seconds
D/wpa_supplicant( 1321): wlan0: Selecting BSS from priority group 342
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1321): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
,D/wpa_supplicant( 1321): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1321): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1321): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
E/WifiMonitor(  947): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1321):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1321): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1321): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55a160fc00  current_ssid=0x0
D/wpa_supplicant( 1321): wlan0: Request association with c0:ff:d4:d3:aa:48
D/WifiMonitor(  947): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,D/wpa_supplicant( 1321): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1321): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1321): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1321): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=40 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1321): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00,
D/wpa_supplicant( 1321): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
W/WifiMonitor(  947): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1321): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1321): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1321): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1321): wlan0: Add radio work 'connect'@0x55a15f2ac0
D/wpa_supplicant( 1321): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1321): wlan0: Starting radio work 'connect'@0x55a15f2ac0 after 0.000057 second wait
I/wpa_supplicant( 1321): check if in concurrent case
I/wpa_supplicant( 1321): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  947): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
,E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=41 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=147462
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=134702  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  947): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  947): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  947): processMsg: ConnectModeState
D/wpa_supplicant( 1321): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
E/WifiStateMachine(  947):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=134703  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/wpa_supplicant( 1321): wlan0: Cancelling sched scan
E/WifiStateMachine(  947): handleMessage: X
D/wpa_supplicant( 1321): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1321): wlan0: Cancelling scan request
E/WifiStateMachine(  947): handleMessage: E msg.what=131212
D/wpa_supplicant( 1321): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1321): wpas_start_assoc_cb, 1895
E/WifiStateMachine(  947): processMsg: DisconnectedState
D/wpa_supplicant( 1321): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1321): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1321): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1321): RSN: PMKSA cache search - network_ctx=0x55a160fc00 try_opportunistic=0
D/wpa_supplicant( 1321): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1321): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1321): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1321): wlan0: WPA: Selected mgmt group cipher 32
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/wpa_supplicant( 1321): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1321): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1321): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1321): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1321): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1321): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1321): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1321): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1321): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1321): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  947):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
D/wpa_supplicant( 1321): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1321): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1321): nl80211: Unsubscribe mgmt frames handle 0x888888dd29e87989 (mode change)
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  947): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  947):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
D/wpa_supplicant( 1321): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a160f100
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLA,N_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=0104
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=040a
D/WifiMonitor(  947): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=040b
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=040c
E/WifiStateMachine(  947):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=040d
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=090a
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=090b
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=090c
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=090d
E/WifiStateMachine(  947):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=0409506f9a09
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=7f506f9a09
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=0801
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=040e
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=06
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=0a07
W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  947):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=0a11
D/wpa_supplicant( 1321): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a160f100 match=0a1a
D/wpa_supplicant( 1321): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1321):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321):   * freq=2412
D/wpa_supplicant( 1321):   * freq_hint=2412
D/wpa_supplicant( 1321):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1321):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1321):   * WPA Versions 0x2
D/wpa_supplicant( 1321):   * pairwise=0xfac04
D/wpa_supplicant( 1321):   * group=0xfac04
E/WifiStateMachine(  947): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/wpa_supplicant( 1321):   * akm=0xfac02
D/wpa_supplicant( 1321):   * Auth Type 0
D/wpa_supplicant( 1321): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55a160fc3a
E/WifiStateMachine(  947): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  947): handleMessage: X
D/WifiNetworkAgent(  947): Networ,kAgent: NetworkAgent channel lost
E/WifiStateMachine(  947): handleMessage: E msg.what=131212
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
D/wpa_supplicant( 1321): nl80211: Connect request send successfully
D/wpa_supplicant( 1321): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1321): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1321): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1321): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1321): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1321): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1321): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  947):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  947): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131212
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  947): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=147462
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=134709  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  947): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  947): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  947): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  947): NetworkAgent == null
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=134712  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=147461
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:86 bcn=0
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:86 bcn=0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:86 bcn=0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  947):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:86 bcn=0
D/WifiStateMachine(  947): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1321): wlan0: Control interface command 'LIST_DONGLES'
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  947): [1,450,229,683,773 ms] noteScanEnd no scan source
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1321): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  947): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@ee38cfe sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  947): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  947): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  947): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  947): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  947):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  947): Gonzos 38:f8:89:11:e9:11 rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  947): 01ABC c2:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  947): UPC503894600 a0:c5:62:7a:49:97 rssi=-90 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  947): ageScanResultsOut delay 40000 size 5 now 1450229683776
E/WifiAutoJoinController (  947): newSupplicantResults size=5 known=1 true
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1321): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  947): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  947): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  947): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  947): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  947): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  947):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131213
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState CMD_TARGET_BSSID 41 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=134718
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState CMD_TARGET_BSSID 41 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=134719
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState CMD_TARGET_BSSID 41 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=134719
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState CMD_TARGET_BSSID 41 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=134719
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=147462
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=134720  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  947): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  947): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  947): setDetailed state send new extra info0x
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  947): NetworkAgent == null
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  947): processMsg: ConnectModeState
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  947):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=134725  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  947): handleMessage: X
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5912): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  947): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  947): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524292
D/WifiService(  947): New client listening to asynchronous messages
I/SecurityController( 1222): onLost 100
E/WifiTrafficPoller(  947): ADD_CLIENT: 9
D/ConnectivityService(  947): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  947): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  947): Removing idletimer
D/usbnet  (  947): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
D/usbnet  (  947):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  947):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  947): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/usbnet  (  947): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiStateMachine(  947): enter WifiNetworkFactory startNetwork. mIPTStart:false
I/chromium( 6690): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/WifiStateMachine(  947): handleMessage: E msg.what=131131
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  947): handleMessage: X
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
W/WISPrService( 5912): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5912): trigger connection
D/WISPrService( 5912): continue
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  947): acquireWL(3e5bf4a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 947 1000 null
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
D/CSLegacyTypeTracker(  947): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/FlexNetS( 6558): updateSvcAllowedInSettings:false
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5912): start DataConnection
D/libc    ( 5912): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5912): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5912): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5912): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5912): [NET] android_getaddrinfo_proxy+
D/libc    ( 5912): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5912): [NET] android_getaddrinfo_proxy-, NODATA
,D/Tethering(  947): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
I/ActivityManager(  947): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6753 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/Tethering(  947): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  947): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,E/ConnectivityService(  947): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/ConnectivityService(  947): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
,D/PMS     (  947): acquireWL(26572ebb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 947 1000 null
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
V/NetworkPolicy(  947): ensureActiveMobilePolicyLocked()
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  947): releaseWL(26572ebb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/NetworkPolicy(  947): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
V/NetworkPolicy(  947): updateIfacesLocked()
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  947): updateNotificationsLocked()
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
V/NetworkPolicy(  947): updateNotificationsLocked()
D/NetworkManagementService(  947): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/FlexNetS( 6558): updateSvcAllowedInSettings:false
,D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/wpa_supplicant( 1321): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1321): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1321): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1321): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1321): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1321): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1321): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1321): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1321): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1321): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1321): nl80211: Connect event
D/wpa_supplicant( 1321): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1321): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1321): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1321): wlan0: Association info event
I/art     (  415): Explicit concurrent mark sweep GC freed 8650(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 206us total 28.337ms
D/Tethering(  947): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1321): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/Tethering(  947): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1321): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1321): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1321): wlan0: freq=2412 MHz
D/wpa_supplicant( 1321): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1321): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1321): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1321): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1321): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1321): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1321): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1321): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1321): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1321): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1321): TDLS: Remove peers on association
D/wpa_supplicant( 1321): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1321): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1321): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1321): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1321): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1321): EAPOL: enable timer tick
D/wpa_supplicant( 1321): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1321): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1321): wlan0: Cancelling scan request
I/wpa_supplicant( 1321): htc_wext_set_keepalive +
I/wpa_supplicant( 1321): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1321): getPrivFuncNum +	
I/wpa_supplicant( 1321): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1321): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  947): interfaceLinkStateChanged wlan0, false
D/Tethering(  947): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1321): htc_wext_set_keepalive - ret = 0
E/WifiStateMachi,ne(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1321): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1321): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1321): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1321): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1321): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1321):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1321):   key_nonce - hexdump(len=32): 2c 4d 40 d5 82 90 39 1a cd 33 f0 8f b5 3c e2 4e 6c 6f 24 d1 64 21 de 03 44 be 92 7e 7a 5b 51 ed
D/wpa_supplicant( 1321):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/PMS     (  947): acquireWL(283eeda2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 947 1000 null
D/wpa_supplicant( 1321):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1321):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1321):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1321): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1321): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1321): RSN: msg 1/4 key data - hexdump(len=0):
D/Tethering(  947): interfaceLinkStateChanged wlan0, false
D/Tethering(  947): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  947): interfaceLinkStateChanged wlan0, true
D/Tethering(  947): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  947): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1321): WPA: Renewed SNonce - hexdump(len=32): 48 66 12 2c 97 3a 9f 9c 6c 6b 63 e7 c8 b6 f2 38 fd a5 0c 87 e0 70 30 10 5f 57 ca 6a 2b a5 77 12
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1321): WPA: Nonce1 - hexdump(len=32): 48 66 12 2c 97 3a 9f 9c 6c 6b 63 e7 c8 b6 f2 38 fd a5 0c 87 e0 70 30 10 5f 57 ca 6a 2b a5 77 12,
D/wpa_supplicant( 1321): WPA: Nonce2 - hexdump(len=32): 2c 4d 40 d5 82 90 39 1a cd 33 f0 8f b5 3c e2 4e 6c 6f 24 d1 64 21 de 03 44 be 92 7e 7a 5b 51 ed
D/wpa_supplicant( 1321): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1321): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1321): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1321): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1321): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1321): WPA: KCK - hexdump(len=16): [REMOVED]
D/UsbDeviceManager(  947): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1321): WPA: Derived Key MIC - hexdump(len=16): f4 57 a1 7b ba 6e 92 72 1b 8c e9 70 27 1e bb 1d
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  947): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  947): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  947): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=44 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  947): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  947): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  947): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  947): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  947): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  947): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  947): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  947): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  947): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  947): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  947): handleMessage: E msg.what=147462
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=134831  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  947): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  947): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=134832  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=147500
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState what:1,47500 0 0
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  947): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  947):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  947): Enter handleAssociatedWithEvent
D/WifiStateMachine(  947): Associated
D/Tethering(  947): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine(  947): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  947): Exit handleAssociatedWithEvent
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=147462
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=134837  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  947): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  947): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/wpa_supplicant( 1321): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1321): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1321): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1321): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1321):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1321):   key_nonce - hexdump(len=32): 2c 4d 40 d5 82 90 39 1a cd 33 f0 8f b5 3c e2 4e 6c 6f 24 d1 64 21 de 03 44 be 92 7e 7a 5b 51 ed
D/wpa_supplicant( 1321):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1321):   key_rsc - hexdump(len=8): 5c 76 00 00 00 00 00 00
D/wpa_supplicant( 1321):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1321):   key_mic - hexdump(len=16): 54 10 3f 19 86 7b c5 6e 77 fa 43 6f b3 94 29 a1
D/wpa_supplicant( 1321): RSN: encrypted key data - hexdump(len=56): 59 9a 51 84 1f c9 c5 9e f4 55 88 b3 ef 42 ae 7a bb 58 3e 01 37 07 52 50 ad c2 c1 40 60 a6 8d df ...
D/wpa_supplicant( 1321): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1321): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1321): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1321): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 e6 70 ...
D/wpa_supplicant( 1321): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1321): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1321): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1321): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1321): WPA: Derived Key MIC - hexdump(len=16): 00 51 b6 fe b9 a8 4a 0a 87 2c 72 8a 04 19 e9 bb
D/wpa_supplicant( 1321): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1321): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55a1610390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1321): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1321): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1321):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1321): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1321): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1321): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1321): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1321): WPA: RSC - hexdump(len=6): 5c 76 00 00 00 00
D/WifiMonitor(  947): Event [IFNAME=wlan0 CT,RL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1321): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5569678e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1321): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1321): nl80211: KEY_SEQ - hexdump(len=6): 5c 76 00 00 00 00
D/wpa_supplicant( 1321):    broadcast key
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1321): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1321): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1321): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/WifiMonitor(  947): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/PMS     (  947): releaseWL(283eeda2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1321): wlan0: Radio work 'connect'@0x55a15f2ac0 done in 0.137931 seconds
I/wpa_supplicant( 1321): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1321): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  947): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=47 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  947): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
D/WifiMonitor(  947): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
V/NetworkPolicy(  947): updateNotificationsLocked()
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=48 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  947): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/UsbnetService(  947): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
E/wpa_supplicant( 1321): wlan0: Connect to SSID: NG700
E/WifiStateMachine(  947): setDetailed state send new extra info"NG700"
D/wpa_supplicant( 1321): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1321): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  947): Event [IFNAME=wlan0 Connect to SSID: NG700]
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=50 dispatchEvent: Connect to SSID: NG700
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 1321): set send_ind_to_ndc = 0
W/WifiMonitor(  947): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1321): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1321): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1321): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1321): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1321): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1321): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1321): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1321): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1321): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1321): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1321): EAPOL: SUPP_BE entering state IDLE
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/wpa_supplicant( 1321): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1321): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1321): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  947): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  947): NetworkAgent == null
D/Tethering(  947): interfaceLinkStateChanged wlan0, true
D/Tethering(  947): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 20
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=134844  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  947): handleMessage: X
D/FlexNetS( 6558): updateSvcAllowedInSettings:false
D/libc    ( 5912): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5912): [NET] android_getaddrinfofornet-, err=8
I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 193us total 22.949ms
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  947): handleMessage: E msg.what=147462
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=134853  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  947): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  947): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=134854  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=147459
E/WifiStateMachine(  947): processMsg: DisconnectedState
E/WifiStateMachine(  947):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=134855
E/WifiStateMachine(  947): processMsg: ConnectModeState
D/WISPrService( 5912): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine(  947):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=134855
E/WifiStateMachine(  947): Network connection established
D/WifiStateMachine(  947): fetchFrequency(), freq = 2412
E/WifiStateMachine(  947): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  947): NetworkAgent == null
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  947): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  947): handleMessage: new destination call exit/enter
E/WifiStateMachine(  947): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  947): invokeExitMethods: DisconnectedState
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1321): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1321): CTRL_IFACE SET 'pno'='0'
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 22
E/WifiStateMachine(  947): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
E/WifiStateMachine(  947): moveTempStackToStateStack: i=1,j=4
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  947): moveTempStackToStateStack: i=0,j=5
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  947): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  947): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  947): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  947): NetworkAgent == null
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 23
D/FlexNetS( 6558): updateSvcAllowedInSettings:false
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  947): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  947): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  947): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  947): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  947): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  947): Got NetworkAgent Messenger
D/wpa_supplicant( 1321): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/wpa_supplicant( 1321): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/ConnectivityService(  947): NetworkAgent connected
D/wpa_supplicant( 1321): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 193us total 22.266ms
D/wpa_supplicant( 1321): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1321): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/wpa_supplicant( 1321): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1321): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  947): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  947): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  947): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  947): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  947): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  947): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1321): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1321): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1321): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1321): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1321): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 24
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1321): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1321): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  947): Start Dhcp Watchdog 2
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131101
E/WifiStateMachine(  947): processMsg: ObtainingIpState
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  947):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/WifiStateMachine(  947): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  947): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=147462
E/WifiStateMachine(  947): processMsg: ObtainingIpState
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  947):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=134881  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=134882  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  947): processMsg: ConnectModeState
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  947):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=134883  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  947): handleMessage: X
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
E/WifiStateMachine(  947): handleMessage: E msg.what=131212
D/ConnectivityService(  947): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  947): processMsg: ObtainingIpState
E/WifiStateMachine(  947):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
D/WISPrService( 5912): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  947):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
D/WifiStateMachine(  947): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  947):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
D/PMS     (  947): acquireWL(3100f887): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 947 1000 null
E/WifiStateMachine(  947):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiStateMachine(  947): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  947): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/WISPrService( 5912): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  947): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=196612
E/WifiStateMachine(  947): processMsg: ObtainingIpState
E/WifiStateMachine(  947):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiDataStallTracker(  947): setDhcpActive: true
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1321): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
E/WifiStateMachine(  947): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  947): do suspend false
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1321): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1321): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1321): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1321): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1321): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1321): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1321): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  947): Unexpected BatchedScanResults :null
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1321): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  947): noteBatchedScanstop()
E/WifiStateMachine(  947): handleMessage: X
D/WifiP2pService(  947): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1210bfea target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  947): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1210bfea target=com.android.internal.util.StateMachine$SmHandler }
D/FlexNetS( 6558): updateSvcAllowedInSettings:false
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6558): updateSvcAllowedInSettings:false
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6558): updateSvcAllowedInSettings:false,
,D/TetherSettings( 5912): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5912): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5912): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5912): Cust_ConnectToPC   : spcsc>false
D/        ( 5912): Cust_ConnectToPC   : IPT>true
D/        ( 5912): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5912): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5912): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5912): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5912): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
W/ContextImpl( 5912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
,I/SmartNS_Utility( 5912): setISNotification,
D/SmartNS_Utility( 5912): usb_cable_connect = 1
D/SmartNS_Utility( 5912): usb_denied = 0
I/SmartNS_PSService( 5912): usb notificaiton:true
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 5912): usb_cable_connect = 1,
D/SmartNS_Utility( 5912): usb_denied = 0
,I/SmartNS_PSService( 5912): usb notificaiton:true
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 5912): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/FlexNetS( 6558): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6753): [b85.2.]  listen tmrbb8
,D/FlexNetS( 6558): updateSvcAllowedInSettings:false
,D/FlexNetS( 6558): updateSvcAllowedInSettings:false
,D/FlexNetS( 6558): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6558): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6558): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6620): add item 101 (2:g3d27) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6558): updateSvcAllowedInSettings:false
,D/FlexNetS( 6558): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6620): remove item 101 (p3in15) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 6753): [b85.2.] summary 118:p2 ignore
,E/dhcpcd  ( 6784): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6784): version 5.5.6 starting,
E/dhcpcd  ( 6784): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6784): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6784): autoip env[11]:autoip=DISABLE
,I/ActivityManager(  947): Killing 6207:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  947): killProcessQuiet, pid=6207
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6784): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6784): wlan0: sending REQUEST (xid 0xf39a9473), next in 1.57 seconds
,I/ActivityManager(  947): Recipient 6207,
,D/wpa_supplicant( 1321): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1321): EAPOL: disable timer tick
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  947): handleMessage: E msg.what=131212
E/WifiStateMachine(  947): processMsg: ObtainingIpState
E/WifiStateMachine(  947):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
,E/WifiStateMachine(  947):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  947): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  947): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  947): handleMessage: X
,I/dhcpcd  ( 6784): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6784): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6784): autoip env[11]:autoip=DISABLE
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  947): handleMessage: E msg.what=131212,
,E/WifiStateMachine(  947): processMsg: ObtainingIpState,
E/WifiStateMachine(  947):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
,E/WifiStateMachine(  947):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  947): processMsg: ConnectModeState
D/ConnectivityService(  947): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  947):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState,
E/WifiStateMachine(  947):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  947): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  947): handleMessage: X
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  947): handleMessage: E msg.what=196613
E/WifiStateMachine(  947): processMsg: ObtainingIpState
E/WifiStateMachine(  947):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine(  947): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1321): Power_Mode_Type mode = 0
I/wpa_supplicant( 1321): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  947): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  947): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1321): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  947): setDhcpActive: false
D/PMS     (  947): releaseWL(3100f887): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  947): handlePostDhcpSetup release wake lock during DHCP
I/dhcpcd  ( 6784): bind_interface: daemonise
E/WifiStateMachine(  947): WifiStateMachine DHCP successful
E/WifiStateMachine(  947): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  947): link address 192.168.1.130/24
,E/WifiStateMachine(  947): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  947): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  947): gateway: /192.168.1.1
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1321): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1321): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1321): htc_wext_set_keepalive +
,I/wpa_supplicant( 1321): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1321): getPrivFuncNum +	
I/wpa_supplicant( 1321): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1321): htc_wext_set_keepalive fnum = 0x8bf6
D/ConnectivityService(  947): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/wpa_supplicant( 1321): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1321): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1321): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  947): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131210
E/WifiStateMachine(  947): processMsg: ObtainingIpState
,E/WifiStateMachine(  947):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1321): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1321): environment dirty rate=14 [7][1][0]
,E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  947): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1321): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1321): wlan0: BLACKLIST CLEAR 
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiMonitor(  947): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=52 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  947): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  947): NetworkAgent != null
,E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -59, 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  947): Adding iface wlan0 to network 101
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/WifiDataStallTracker(  947): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiDataStallTracker(  947): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  947): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HtcWifiWanDetect(  947): WAN detection
D/HtcWifiWanDetect(  947): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
V/NetworkPolicy(  947): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  947): transitionTo: destState=ConnectedState
E/WifiStateMachine(  947): handleMessage: new destination call exit/enter
E/WifiStateMachine(  947): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  947): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  947): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  947): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  947): invokeEnterMethods: ConnectedState
V/NetworkPolicy(  947): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 26
E/WifiStateMachine(  947): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  947): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5912): >>>>>WISPrService start isConnected = true<<<<<
E/ConnectivityService(  947): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  947): Adding Route [fe80::/64 -> :: wlan0] to network 101
,E/WifiStateMachine(  947): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  947): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  947): handleMessage: X
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  947): handleMessage: E msg.what=131131
E/WifiStateMachine(  947): processMsg: ConnectedState
D/ConnectivityService(  947): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
E/WifiStateMachine(  947):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  947): processMsg: ConnectModeState
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  947):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine(  947): handleMessage: X
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  947): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
,D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5912): >>>>>WISPrService start isConnected = true<<<<<
,D/Nat464Xlat(  947): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true,
D/ConnectivityService(  947): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  947): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  947):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  947):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  947): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  947):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  947): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947): currentScore = 0, newScore = 20
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  947):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): Connected
D/ConnectivityService(  947): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  947):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/CSLegacyTypeTracker(  947): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  947): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  947): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): Validated
D/ConnectivityService(  947): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  947): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  947): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkPolicy(  947): ensureActiveMobilePolicyLocked()
D/Tethering(  947): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  947): acquireWL(3ab2c720): PARTIAL_WAKE_LOCK  NetworkStats 0x1 947 1000 null
D/ConnectivityService(  947): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  947): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkPolicy(  947): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
V/NetworkPolicy(  947): updateIfacesLocked()
D/ConnectivityService(  947): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): Validated
D/ConnectivityService(  947): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  947):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  947): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
V/NetworkPolicy(  947): updateNotificationsLocked()
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  947): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  947): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  947):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  947): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/DATA_ICON( 1222): dataConnected: false/false
D/WIFI    (  947): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  947): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  947):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  947): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  947): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/PMS     (  947): releaseWL(3ab2c720): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/u,sbnet  (  947):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  947): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/DATA_ICON( 1222): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
V/NetworkPolicy(  947): updateNotificationsLocked()
,I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,D/PMS     (  947): releaseWL(3e5bf4a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  947): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  947): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  947): [AlarmQueuing] connectivity wifi: false
D/htcCheckinService(  947): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  947): acquireWL(198ab8d9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 947 1000 null
D/GpsLocationProvider(  947): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  947): acquireWL(3539029e): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 947 1000 null
D/GpsLocationProvider(  947): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  947): releaseWL(3539029e): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ConnectivityHelper( 1583): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  947): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6817 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  947): No APN found to select.,
,D/PMS     (  947): releaseWL(198ab8d9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
D/MdScPhnSt( 6753): [18d.1.]  listen tmrbb8
,D/MdScDataSum( 6753): [18d.1.] summary 118:p1 ignore
,I/MusicStore( 6817): Database version: 120,
,D/VoldConnector(  947): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,W/ContextImpl( 6817): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  947): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6817): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  947): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6817): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,W/ResourcesManager( 6817): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6817): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6817): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6817): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6817): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38672a25: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6817): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6817): GMSCore installation verified
,I/ConfigStore( 6817): Config Database version: 1,
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6817, uid=10159, userID:0,
,D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
,D/MediaRouterService(  947): Client com.google.android.music (pid 6817): Registered,
,D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
,I/MediaRouter( 6817): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6817): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6817): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6817): type=WIFI subType= reason=null isConnected=true
,D/MobileConnectivityChangeReceiver( 6413): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1653): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6413): onReceive CONNECTIVITY_CHANGE networkType=1,
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6817, uid=10159, userID:0
,D/AutoSetting( 1653): service - onCreate()
,D/AutoSetting( 1653): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,I/GHttpClientFactory( 6817): Using our fixed implementation of GMSCore's GoogleHttpClient
D/AutoSetting( 1653): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  947): request 3752fac9 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  947): provider request: passive ProviderRequest[ON interval=0]
,I/GoogleURLConnFactory( 6817): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4414): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4414): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/ActivityManager(  947): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6861 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 6463): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 6463): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6463): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6463): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6463): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6463): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1968): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1968): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1968): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1968): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1968): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6463): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4414): [AccountUtils] Account not ready
W/Kids    ( 4414): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4414): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4414): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4414): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4414): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4414): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4414): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4414): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4414): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4414): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/Babel   ( 6463): connection state changed from UNKNOWN to CONNECTED,
,D/VoldConnector(  947): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6861): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  947): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/,
W/ContextImpl( 6861): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6861): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6861):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6861):   adb logcat -s GAv4
,D/VoldConnector(  947): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
,W/ContextImpl( 6861): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  947): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6861): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6861): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6861): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6861): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/art     (  947): Explicit concurrent mark sweep GC freed 59961(3MB) AllocSpace objects, 4(348KB) LOS objects, 33% free, 16MB/25MB, paused 1.538ms total 193.239ms
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40,
,W/global  ( 6861): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6861): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6861): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6861): Time to load native libraries: 2 ms (timestamps 8901-8903),
I/LibraryLoader( 6861): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6861): Binding Chromium to main looper Looper (main, tid 1) {ca4949a},
,I/LibraryLoader( 6861): Expected native library version number "",actual native library version number "",
,I/chromium( 6861): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6861): Initializing chromium process, singleProcess=true,
,W/art     ( 6861): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6861): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6861): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6861): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6861): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6861): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6861): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6861): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6861): Local Branch: 
,I/Adreno-EGL( 6861): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6861): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6861):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6861): Requires BLUETOOTH permission,
,I/NSApplication( 6861): Starting up...
,I/ActivityManager(  947): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6921 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  947): killProcessQuiet, pid=6441
I/ActivityManager(  947): Killing 6441:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  947): Recipient 6441
,D/Process (  947): killProcessQuiet, pid=6368
I/ActivityManager(  947): Killing 6368:com.google.android.gms.unstable/u0a24 (adj 15): empty #18
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  947): Recipient 6368
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
,D/libc    (  947): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  947): [NET] android_getaddrinfo_proxy+
D/libc    (  947): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/jxcore-log( 6690): BLE advertisement not supported: Bluetooth LE advertising is not supported
,I/jxcore-log( 6690): 
,D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  947): [AlarmQueuing] connectivity wifi: true,
,I/ConnectivityHelper( 1583): [onReceive] WIFI(1): CONNECTED,
,I/NetworkMonitor( 6817): type=WIFI subType= reason=null isConnected=true
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  947): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  947): [NET] android_getaddrinfo_proxy-, success
,D/htcCheckinService(  947): ConnectivityReceiver - onReceive() - original mNetworkConnected = true,
,D/MdScPhnSt( 6753): [f43.1.]  listen tmrbb8,
,E/WifiStateMachine(  947): handleMessage: E msg.what=131168
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  947): processMsg: ConnectModeState
E/WifiStateMachine(  947):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  947): handleMessage: X
,D/MdScDataSum( 6753): [f43.1.] summary 118:p1 ignore
,D/GpsLocationProvider(  947): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
D/PMS     (  947): acquireWL(d6ef317): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 947 1000 null
,D/PMS     (  947): acquireWL(2118b304): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 947 1000 null
,D/PMS     (  947): releaseWL(2118b304): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  947): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  947): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,E/GpsLocationProvider(  947): No APN found to select.,
,D/PMS     (  947): releaseWL(d6ef317): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,D/Process (  947): killProcessQuiet, pid=5941,
I/ActivityManager(  947): Killing 5941:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  947): Recipient 5941,
,V/MusicLeanback( 6817): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6413): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6413): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1653): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1653): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1653): service - onStartCommand() screen is off, don't request location
,I/art     ( 3809): Explicit concurrent mark sweep GC freed 5338(290KB) AllocSpace objects, 0(0B) LOS objects, 57% free, 1520KB/3MB, paused 681us total 49.256ms
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4414, uid=10024, userID:0
,D/ChimeraCfgMgr( 4414): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4414): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1968): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1968): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1968): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1968): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1968): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1222): reapply : com.google.android.gms 1 40
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Kids    ( 4414): [AccountUtils] Account not ready
W/Kids    ( 4414): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4414): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4414): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4414): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4414): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4414): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4414): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4414): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4414): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4414): 	at java.lang.Thread.run(Thread.java:818)
,D/PMS     (  947): acquireWL(1adb2646): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{10024}
V/AlarmManager(  947): sending alarm PendingIntent{151cd007: PendingIntentRecord{3110e534 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=140416, Int=0
D/PMS     (  947): acquireWL(43f9f5d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1968 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(1adb2646): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1968): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1968): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1968): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1968): [NET] android_getaddrinfo_proxy+
D/libc    ( 1968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1968): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1968): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1968): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1968): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1968): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  947): acquireWL(109360d2): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1968): Connected
D/PMS     (  947): releaseWL(43f9f5d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(109360d2): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(2aac65a3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1968 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1968): Message class com.google.f.a.a.p,
,D/PMS     (  947): releaseWL(2aac65a3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  947): acquireWL(317120a0): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{10024},
V/AlarmManager(  947): sending alarm PendingIntent{20dbd459: PendingIntentRecord{e22b81e com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143173, Int=0
,D/PMS     (  947): releaseWL(317120a0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/PMS     (  947): acquireWL(1d7a6cc): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6817 10159 null,
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6817, uid=10159, userID:0,
,D/PMS     (  947): releaseWL(1d7a6cc): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 6817): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6817): Stop autocaching.
,D/WearableService( 4906): callingUid 10024, callindPid: 4906
,E/GmsUtils( 6817): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6817): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  947): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  947): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  947): acquireWL(514dfef): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 947 1000 null
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  947): [NET] android_getaddrinfofornet-, err=8
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  947): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  947): [NET] android_getaddrinfo_proxy+
D/libc    (  947): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  947): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  947): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  947): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  947): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  947): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  947):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  947): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  947): acquireWL(39798c0b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 947 1000 null
D/PMS     (  947): releaseWL(514dfef): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  947): releaseWL(39798c0b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  947): acquireWL(1cee2ae8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000},
V/AlarmManager(  947): sending alarm PendingIntent{2a75aed: PendingIntentRecord{1f441d22 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=150941, Int=0,
V/AlarmManager(  947): sending alarm PendingIntent{39eb2501: PendingIntentRecord{2e2b3fa6 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1450229717926, Int=0
,D/PMS     (  947): acquireWL(3632dde7): PARTIAL_WAKE_LOCK  *backup* 0x1 947 1000 null
,W/BackupManagerService(  947): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
,E/BackupManagerService(  947): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  947): releaseWL(3632dde7): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/PMS     (  947): releaseWL(1cee2ae8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/AutoSetting( 1653): service - handleMessage() stop self,
,D/AutoSetting( 1653): service - onDestroy() END
,D/AutoSetting( 1653): service - handleMessage() quit looper
,D/PMS     (  947): acquireWL(1aef0d94): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(1aef0d94): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  947): updateBatteryInfo
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  947): plugged=true pluggin=true
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  947): runPSCheck
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  947): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/WifiStateMachine(  947): handleMessage: E msg.what=131165,
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
,E/WifiStateMachine(  947):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  947): handleMessage: X
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/TelephonyReceiver( 1542): switchBindHtcMsgCursor: null
,E/WifiStateMachine(  947): handleMessage: E msg.what=131326,
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState what:131326 2 0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  947): handleMessage: X
,D/PMS     (  947): acquireWL(2264103d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000}
,V/AlarmManager(  947): sending alarm PendingIntent{2a75aed: PendingIntentRecord{1f441d22 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=210941, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{2dbbb032: PendingIntentRecord{21457183 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=211757, Int=0
,V/AlarmManager(  947): sending alarm PendingIntent{21796f00: PendingIntentRecord{1a867339 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191197, Int=0
,D/PMS     (  947): acquireWL(19709d7e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(2264103d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  947): acquireWL(3263a2df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1653): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1a5689c0
D/PMS     (  947): releaseWL(19709d7e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1968): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  947): releaseWL(3263a2df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(26065071): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): releaseWL(26065071): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(598de56): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(598de56): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(2590ed7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms}
,D/Process (  947): killProcessQuiet, pid=5855
I/ActivityManager(  947): Killing 5855:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 5855
,D/PMS     (  947): acquireWL(33bb03c4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(35dc89e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): releaseWL(2590ed7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1968): Vacuum at: now=1450229761186 tag=VacuumService
,D/PMS     (  947): releaseWL(33bb03c4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(1b469830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1968): Using platform SSLCertificateSocketFactory
,W/Uploader( 1968): No account for auth token provided,
D/PMS     (  947): releaseWL(1b469830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): acquireWL(48d9ca9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(48d9ca9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1968): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1968): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1968): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1968): [NET] android_getaddrinfo_proxy+
D/libc    ( 1968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1968): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1968): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1968): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1968): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1968): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1968): No account for auth token provided,
,W/Uploader( 1968): No account for auth token provided,
,W/Uploader( 1968):  no longer exists, so no auth token.,
,W/Uploader( 1968): No account for auth token provided,
,I/GLSUser ( 1968): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1968): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1968): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1968): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1968): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1968): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1968): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1968): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1968): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1968): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1968): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1968): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1968): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1968): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1968): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1968): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1968): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1968): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,W/Uploader( 1968): No account for auth token provided,
,D/PMS     (  947): releaseWL(35dc89e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(31086d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): releaseWL(31086d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): acquireWL(2a2a0219): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  947): releaseWL(2a2a0219): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  947): acquireWL(38dcb2de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(38dcb2de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): updateBatteryInfo
,D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): battery changed pluggedType: 2
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): processMsg: DeviceActiveState
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1321): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1321): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1321): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1321): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/jxcore-log( 6690): Connected to the server!,
I/jxcore-log( 6690): 
,I/chromium( 6690): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63),
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  947): acquireWL(2a2bfcbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(2a2bfcbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
,D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/HtcPowerSaver(  947): updateBatteryInfo
D/PMS     (  947): runPSCheck,
D/HtcPowerSaver(  947): Checking...
I/HtcPowerSaver(  947): >> updateStatus
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  947): acquireWL(1676ff8c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000},
,V/AlarmManager(  947): sending alarm PendingIntent{2a75aed: PendingIntentRecord{1f441d22 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=270941, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{2efd1eea: PendingIntentRecord{342da5db com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1450229890824, Int=0,
,I/ActivityManager(  947): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6989 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  947): sending alarm PendingIntent{25a8878: PendingIntentRecord{1af0db51 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1450229956370, Int=0
,D/WeatherUtility( 1222): Weather sync is On
D/PMS     (  947): releaseWL(1676ff8c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data,
,E/cutils-trace( 7010): Error opening trace file: Permission denied (13)
,I/dex2oat ( 7010): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7010): dex2oat: override thread count:4
,I/dex2oat ( 7010): dex2oat took 891.224ms (threads: 4),
,I/PushClient( 6989): ApplicationMonitor {337bdd00}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6989): ApplicationMonitor {337bdd00}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6989): ApplicationMonitor {337bdd00}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6989): ApplicationMonitor {337bdd00}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6989): ApplicationMonitor {337bdd00}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6989): ApplicationMonitor {337bdd00}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
,I/PushClient( 6989): ApplicationMonitor {337bdd00}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false,
I/PushClient( 6989): ApplicationMonitor {337bdd00}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6989): ApplicationMonitor {337bdd00}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6989): PnsModel {3534d783}: update(): Update registration caused by: alarm
,I/PushClient( 6989): PnsConfigModel {1549bc56}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6989): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6989): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6989): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6989): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  947): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7017 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7017): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7017 dbg=false s=true,
,I/DeviceManagement( 7017): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 7017): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7017): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 7017): WorkflowService: Starting workflow service,
,I/DeviceManagement( 7017): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3d0ee32] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7017): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7017): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7017): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7017): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7017): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7017): SessionStateController: Checking invariants...
,I/DeviceManagement( 7017): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7017): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3d0ee32],
,I/DeviceManagement( 7017): WorkflowService: Stopping workflow service
,D/Process (  947): killProcessQuiet, pid=6493
,I/ActivityManager(  947): Killing 6493:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6989): PnsModel {3534d783}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  947): Recipient 6493
,D/Process (  947): killProcessQuiet, pid=6587
I/ActivityManager(  947): Killing 6587:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 6587
,D/WifiService(  947): Client connection lost with reason: 4
,D/PMS     (  947): acquireWL(3513169a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(3513169a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  947): BroadcastReceiver::onReceive+,
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  947): updateBatteryInfo
,D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PMS     (  947): runPSCheck
D/WifiController(  947): handleMessage: E msg.what=155652
D/HtcPowerSaver(  947): Checking...
,D/WifiController(  947): processMsg: DeviceActiveState
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  947): acquireWL(3f1fbbcb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(3f1fbbcb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  947): BroadcastReceiver::onReceive+,
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PMS     (  947): runPSCheck
D/WifiController(  947): handleMessage: E msg.what=155652
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): processMsg: DeviceActiveState
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  947): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: X
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): << updateStatus
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  947): acquireWL(15bcffa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
,D/PMS     (  947): releaseWL(15bcffa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): onReceive BATTERY_CHANGED
,D/PMS     (  947): runPSCheck
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  947): >> updateStatus
,D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  947): acquireWL(3b4e3ac1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(3b4e3ac1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  947): runPSCheck
,D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  947): Checking...
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  947): >> updateStatus
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  947): BroadcastReceiver::onReceive+,
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  947): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  947): << updateStatus
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: E msg.what=155652
,D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1542): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1542): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1542): sku_id=118
D/ContactMessageStore( 1542): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1542): start background delete task...
,D/ContactMessageStore( 1542): size: 0 , 0
,D/ContactMessageStore( 1542): Background delete complete
,D/PMS     (  947): acquireWL(87c0266): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end,
D/PMS     (  947): releaseWL(87c0266): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PMS     (  947): runPSCheck
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): >> updateStatus
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
,D/WifiController(  947): handleMessage: X
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(266c49a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(266c49a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  947): plugged=true pluggin=true
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  947): updateBatteryInfo
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): onReceive BATTERY_CHANGED,
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(38b66e54): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(38b66e54): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  947): plugged=true pluggin=true
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(2442c1fd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000},
V/AlarmManager(  947): sending alarm PendingIntent{2a75aed: PendingIntentRecord{1f441d22 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=450941, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{e35def2: PendingIntentRecord{1809d943 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941515, Int=0
,I/bt-btm  ( 3101): Received oneshot timer event complete
I/bt-btm  ( 3101): btm_ble_timeout
I/bt-btm  ( 3101): btm_gen_resolvable_private_addr
,D/PMS     (  947): acquireWL(9361bc0): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3101 1002 null
,D/bt-btm  ( 3101): btm_ble_rand_enc_complete
I/bt-btm  ( 3101): btm_gen_resolve_paddr_low
,D/bt-smp  ( 3101): smp_encrypt_data
W/bt-smp  ( 3101): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3101): Plain text(LSB ~ MSB) = fd e5 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3101): Encrypted text(LSB ~ MSB) = ba bd 54 97 2f 36 ec 2c d0 44 6e 04 76 fb 44 57 
I/bt-btm  ( 3101): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3101): Stopping oneshot timer
D/bt-btm  ( 3101): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  947): releaseWL(2442c1fd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  947): releaseWL(9361bc0): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  947): acquireWL(1efe80f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(1efe80f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  947): updateBatteryInfo
D/PMS     (  947): runPSCheck
D/HtcPowerSaver(  947): Checking...
I/HtcPowerSaver(  947): >> updateStatus
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
D/NotificationService(  947): plugged=true pluggin=true
,D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/UsbnetService(  947): onReceive BATTERY_CHANGED
,D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(373ef83e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000}
,V/AlarmManager(  947): sending alarm PendingIntent{2a75aed: PendingIntentRecord{1f441d22 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=990941, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{3366c69f: PendingIntentRecord{314133ec com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450230562572, Int=0
,I/ActivityManager(  947): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=7045 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/SmartSyncUtils( 7045): isEpsOn(), nState = 0
,D/PMS     (  947): acquireWL(2b1d33b5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7045 1000 null
,D/Process (  947): killProcessQuiet, pid=6645
,I/ActivityManager(  947): Killing 6645:com.htc.calendar/u0a10 (adj 15): empty #17
D/PMS     (  947): releaseWL(373ef83e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 ,
,D/PMS     (  947): releaseWL(2b1d33b5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  947): acquireWL(342e5a4a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7045 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 7045): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 7045): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 7045): AlarmOnTime = -1,
,D/SmartSyncScreenOnOffTimeReceiver( 7045): SettingOnTime = 1450245600000, randomSettingOnTime = 1450244783000
,D/SmartSyncScreenOnOffTimeReceiver( 7045): SettingOffTime = 1450310400000, randomSettingOffTime = 1450314010000
,D/SmartSyncScreenOnOffTimeReceiver( 7045): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 7045): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 7045): bNightModeTurnOffOnce = false
,I/ActivityManager(  947): Recipient 6645
,D/PMS     (  947): acquireWL(367b2dbb): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{1000},
,V/AlarmManager(  947): sending alarm PendingIntent{1403a2d8: PendingIntentRecord{2c3a5631 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450230562998, Int=0
D/PMS     (  947): releaseWL(342e5a4a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 7045): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  947): releaseWL(367b2dbb): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 7045): SMARTSYNC_TURN_OFF_NETWORK, current time = 1450230563025, randomOffTime = 1450314010000, newRandomOffTime = 1450314010000
,D/SmartSyncDataLinkTurnOffService( 7045): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 1450244783000, randomMobileOnTime = 1450244783000
,D/SmartSyncUtils( 7045): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 7045): turnOffMobile bPolicyEnabled = true
,D/WifiService(  947): New client listening to asynchronous messages
E/WifiTrafficPoller(  947): ADD_CLIENT: 9
,D/SmartSyncUtils( 7045): isWifiHotSpotEnabled = false,
,D/SmartSyncDataLinkTurnOffService( 7045): turnOffMobile bCheckMobileData = false,
,D/LocationManagerService(  947): getProviders()=[gps, network],
D/LocationManagerService(  947): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  947): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1],
D/SmartSyncDataLinkTurnOffService( 7045): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0,
,D/SmartSyncUtils( 7045): isCharging status = 5,
,D/SmartSyncDataLinkTurnOffService( 7045): turnOffWifi ui setting = true
,D/SmartSyncUtils( 7045): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 7045): state = 0
I/ActivityManager(  947): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7045): Failed to find provider info for com.htc.vowifi
,D/SmartSyncDataLinkTurnOffService( 7045): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 7045): turnOffWifi bWifiConnected = true
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PMS     (  947): acquireWL(3ca4ea97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  947): n_update end
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PMS     (  947): releaseWL(3ca4ea97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/WifiController(  947): battery changed pluggedType: 2
,D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(197c1484): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{10024},
V/AlarmManager(  947): sending alarm PendingIntent{a2d246d: PendingIntentRecord{2f9fe8a2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1040745, Int=0,
V/AlarmManager(  947): sending alarm PendingIntent{266a1a6f: PendingIntentRecord{1015437c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805775, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{f439933: PendingIntentRecord{f1ecadd com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450230517495, Int=0
,D/PMS     (  947): acquireWL(8e7f4f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  947): releaseWL(8e7f4f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 7045): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  947): acquireWL(2437ecee): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1968 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1968): Message class com.google.f.a.a.i
,D/PMS     (  947): releaseWL(2437ecee): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/art     (  947): Explicit concurrent mark sweep GC freed 32370(1657KB) AllocSpace objects, 4(216KB) LOS objects, 33% free, 16MB/25MB, paused 2.149ms total 224.015ms
,D/PMS     (  947): releaseWL(197c1484): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 7045): MY_DEBUG = false
,D/PowerUsageService( 7045): repeat time = 1450231490086
,I/PowerUsageList:PowerUsageHelper( 7045): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 7045): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  947): acquireWL(2414958f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
,D/PMS     (  947): releaseWL(2414958f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): Checking...
I/HtcPowerSaver(  947): >> updateStatus
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(1def701c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000},
,V/AlarmManager(  947): sending alarm PendingIntent{2a75aed: PendingIntentRecord{1f441d22 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1050941, Int=0,
V/AlarmManager(  947): sending alarm PendingIntent{4c37425: PendingIntentRecord{e39e9fa com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450230743104, Int=0
,W/ContextImpl( 7045): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  947): releaseWL(1def701c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/SmartSyncDataLinkTurnOffService( 7045): turnOffWifi ui setting = true
,D/SmartSyncUtils( 7045): isWifiHotSpotEnabled = false
I/ActivityManager(  947): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7045): Failed to find provider info for com.htc.vowifi
D/SmartSyncUtils( 7045): state = 0
,D/SmartSyncDataLinkTurnOffService( 7045): turnOffWifi bCheckWifiData = false
D/SmartSyncDataLinkTurnOffService( 7045): turnOffWifi bWifiConnected = true
,D/LocationManagerService(  947): getProviders()=[gps, network]
D/LocationManagerService(  947): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  947): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 7045): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 7045): isCharging status = 5
,D/PMS     (  947): acquireWL(4917208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(4917208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  947): updateBatteryInfo
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  947): plugged=true pluggin=true
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
,D/WifiController(  947): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: X
,D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  947): User[0] Flushing usage stats to disk,
,D/PMS     (  947): acquireWL(3cdc2da1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(3cdc2da1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  947): updateBatteryInfo
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
,D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PMS     (  947): runPSCheck
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  947): >> updateStatus
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  947): << updateStatus
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  947): acquireWL(2b2cabc6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(2b2cabc6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  947): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PMS     (  947): runPSCheck
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  947): >> updateStatus
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  947): battery changed pluggedType: 2
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): processMsg: DeviceActiveState
I/HtcPowerSaver(  947): << updateStatus
,D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(1f7fa787): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(1f7fa787): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
,D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(27cfa6b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end,
,D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PMS     (  947): releaseWL(27cfa6b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): updateBatteryInfo
D/NotificationService(  947): plugged=true pluggin=true
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/PMS     (  947): runPSCheck
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): handleMessage: X
I/HtcPowerSaver(  947): >> updateStatus
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(1b6d02dd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(1b6d02dd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/NotificationService(  947): plugged=true pluggin=true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): processMsg: DefaultState
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): handleMessage: X
I/HtcPowerSaver(  947): << updateStatus
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PMS     (  947): acquireWL(3837be52): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  947): n_update end
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  947): releaseWL(3837be52): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): onReceive BATTERY_CHANGED
,D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): updateBatteryInfo
D/WifiController(  947): handleMessage: E msg.what=155652
D/PMS     (  947): runPSCheck
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): processMsg: DeviceActiveState
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(31253523): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
,D/PMS     (  947): releaseWL(31253523): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  947): plugged=true pluggin=true
,D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  947): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): processMsg: DeviceActiveState
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): processMsg: StaEnabledState
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(3f1a7a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null,
I/BatteryService(  947): n_update end
,D/PMS     (  947): releaseWL(3f1a7a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  947): plugged=true pluggin=true
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  947): runPSCheck
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): BroadcastReceiver::onReceive+
,I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  947): << updateStatus
D/PowerUI ( 1222): closing low battery warning: level=100
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(43befd9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
D/PMS     (  947): releaseWL(43befd9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  947): plugged=true pluggin=true
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  947): updateBatteryInfo
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  947): runPSCheck
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  947): Checking...
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  947): >> updateStatus
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): handleMessage: X
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  947): acquireWL(180c007f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 947 1000 WorkSource{1000},
V/AlarmManager(  947): sending alarm PendingIntent{2a75aed: PendingIntentRecord{1f441d22 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1230941, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{67d184c: PendingIntentRecord{3772b095 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1841530, Int=0
I/bt-btm  ( 3101): Received oneshot timer event complete
D/PMS     (  947): acquireWL(35e0c5aa): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3101 1002 null
I/bt-btm  ( 3101): btm_ble_timeout
I/bt-btm  ( 3101): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3101): btm_ble_rand_enc_complete
,I/bt-btm  ( 3101): btm_gen_resolve_paddr_low
D/bt-smp  ( 3101): smp_encrypt_data
W/bt-smp  ( 3101): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3101): Plain text(LSB ~ MSB) = 55 ac 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3101): Encrypted text(LSB ~ MSB) = 39 b3 c7 16 e0 29 94 17 ad c9 00 7b 40 8e 6f 20 
I/bt-btm  ( 3101): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3101): Stopping oneshot timer
D/bt-btm  ( 3101): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  947): Prepared write state in 13ms
,I/ProcessStatsService(  947): Prepared write state in 6ms,
,I/ProcessStatsService(  947): Prepared write state in 7ms
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,I/ProcessStatsService(  947): Prepared write state in 5ms
,I/ProcessStatsService(  947): Prepared write state in 5ms
D/PMS     (  947): releaseWL(180c007f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/ProcessStatsService(  947): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-15-03.bin
,D/PMS     (  947): releaseWL(35e0c5aa): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  947): acquireWL(386a259b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
,D/PMS     (  947): releaseWL(386a259b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): onReceive BATTERY_CHANGED
,D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  947): acquireWL(d896d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end
,D/PMS     (  947): releaseWL(d896d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/WifiController(  947): battery changed pluggedType: 2
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  947): runPSCheck
D/UsbnetService(  947): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  947): Checking...
D/WifiController(  947): handleMessage: E msg.what=155652
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): processMsg: DeviceActiveState,
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  947): processMsg: StaEnabledState
I/HtcPowerSaver(  947): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  947): processMsg: DefaultState
I/HtcPowerSaver(  947): << updateStatus
D/WifiController(  947): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1800000ms),D/PMS     (  947): acquireWL(141ac111): PARTIAL_WAKE_LOCK  *alarm* 0x1 947 1000 WorkSource{1000}
V/AlarmManager(  947): sending alarm PendingIntent{266a1a6f: PendingIntentRecord{1015437c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1760793, Int=0
D/Process (  947): killProcessQuiet, pid=6921
V/AlarmManager(  947): sending alarm PendingIntent{35b725a4: PendingIntentRecord{2d4b2f0d android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825718, Int=1800000
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/PMS     (  947): acquireWL(1a5d9276): PARTIAL_WAKE_LOCK  NetworkStats 0x1 947 1000 null
I/ActivityManager(  947): Killing 6921:com.android.chrome/u0a96 (adj 13): empty for 1800s
I/ActivityManager(  947): Recipient 6921
I/ActivityManager(  947): Killing 6861:com.google.android.apps.magazines/u0a161 (adj 13): empty for 1800s
D/Process (  947): killProcessQuiet, pid=6861
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  947): Recipient 6861
D/Process (  947): killProcessQuiet, pid=6413
I/ActivityManager(  947): Killing 6413:com.google.android.setupwizard/u0a77 (adj 13): empty for 1801s
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  947): Recipient 6413
I/ActivityManager(  947): Killing 6558:com.htc.bgp/u0a11 (adj 13): empty for 1801s
D/Process (  947): killProcessQuiet, pid=6558
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  947): Recipient 6558
I/ActivityManager(  947): Killing 6753:com.htc.mobiledata:remote/u0a46 (adj 13): empty for 1801s
D/Process (  947): killProcessQuiet, pid=6753
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  947): Recipient 6753
D/Process (  947): killProcessQuiet, pid=6620
I/ActivityManager(  947): Killing 6620:com.htc.mobiledata/u0a46 (adj 15): empty for 1801s
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  947): Recipient 6620
D/Process (  947): killProcessQuiet, pid=5912
I/ActivityManager(  947): Killing 5912:com.android.settings/1000 (adj 15): empty for 1804s
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  947): Recipient 5912
D/WifiService(  947): Client connection lost with reason: 4
V/AlarmManager(  947): sending alarm PendingIntent{2a75aed: PendingIntentRecord{1f441d22 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1890941, Int=0
D/PMS     (  947): releaseWL(1a5d9276): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
V/NetworkPolicy(  947): updateNotificationsLocked()
V/AlarmManager(  947): sending alarm PendingIntent{39bb8077: PendingIntentRecord{90424e4 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450231002991, Int=1800000
V/AlarmManager(  947): sending alarm PendingIntent{6595d4d: PendingIntentRecord{25086002 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1853738, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{155dad13: PendingIntentRecord{2f9fe8a2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1940809, Int=0
V/AlarmManager(  947): sending alarm PendingIntent{1350ab50: PendingIntentRecord{f1ecadd com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450231490086, Int=0
D/PMS     (  947): acquireWL(1d6b8149): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4414 10024 WorkSource{10024 com.google.android.gms}
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  947): acquireWL(32ec076f): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4414 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): releaseWL(1d6b8149): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): acquireWL(561e905): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1968 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): releaseWL(561e905): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 7045): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  947): releaseWL(141ac111): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 7045): MY_DEBUG = false
D/PowerUsageService( 7045): repeat time = 1450232391049
D/LocationManagerService(  947): getAllProviders()=[passive, gps, network]
I/EventLogService( 4414): Aggregate from 1450229647582 (log), 1450229202923 (data)
D/PMS     (  947): acquireWL(13cd8880): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1968 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1968): Message class com.google.f.a.a.i
D/PMS     (  947): releaseWL(13cd8880): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
I/GLSUser ( 1968): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1968): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1968): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1968): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1968): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  947): releaseWL(32ec076f): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
I/PowerUsageList:PowerUsageHelper( 7045): PowerProfile::POWER_SCREEN_FULL = 154.8
D/PowerUsageList:BatterySipperExt( 7045): gen(), null == sipper.uidObj, userId = 0
E/cutils-trace( 7087): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7087): ====startRecUseTime====
D/htc.customization.log.level( 7087):  is 
W/CustomizationLogLevel( 7087): Level value is invalid, use default level 2
D/CustomizationManager( 7087):  Read ACC file spent 0.045 (s)
D/CIDMapFileReader( 7087): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7087): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7087): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7087): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7087): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7087): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7087): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7087): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7087): Parsing tag category name = system
I/CustomizationCIDLoader( 7087): Parsing tag category name = application
I/CustomizationCIDLoader( 7087): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7087): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7087): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7087): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7087): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7087): add string-array item, value = 42507
I/CustomizationCIDLoader( 7087): add string-array item, value = 21902
I/CustomizationCIDLoader( 7087): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7087): add string-array item, value = 23420
I/CustomizationCIDLoader( 7087): add string-array item, value = 22299
I/CustomizationCIDLoader( 7087): add string-array item, value = 24002
I/CustomizationCIDLoader( 7087): add string-array item, value = 23210
I/CustomizationCIDLoader( 7087): add string-array item, value = 23205
I/CustomizationCIDLoader( 7087): add string-array item, value = 23806
I/CustomizationCIDLoader( 7087): add string-array item, value = 23430
I/CustomizationCIDLoader( 7087): add string-array item, value = 23408
I/CustomizationCIDLoader( 7087): add string-array item, value = 27205
I/CustomizationCIDLoader( 7087): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7087): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7087):  Read CID file spent 0.094 (s)
D/CustomizationManager( 7087):  All configurations done spent 0.094 (s)
D/PackageManager(  947): deletePackageAsUser: pkg=com.test.thalitest, pid=7087, uid=2000 userid=0
I/ActivityManager(  947): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  947): Killing 6690:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  947): killProcessQuiet, pid=6690
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
I/ActivityManager(  947): Recipient 6690
E/InputEventReceiver( 1396): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{fda0d3e uid 10366 pid 6690} (c)'
I/WindowState(  947): WIN DEATH: Window{2fd9a3f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  947): Client connection lost with reason: 4
I/ActivityManager(  947):   Force finishing activity ActivityRecord{70d6dbf u0 com.test.thalitest/.MainActivity t8}
W/ActivityManager(  947): Spurious death for ProcessRecord{7728d7b 6690:com.test.thalitest/u0a366}, curProc for 6690: null
W/PackageSettings(  947): Skipping PackageSetting{29f6c7a9 com.example.hello/10374} due to missing metadata
I/ActivityManager(  947): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
D/AccTypeManager( 1743): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/DotMatrix( 1333): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/PMS     (  947): acquireWL(3b03e798): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1333): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1858): Ignoring removeGeofence because network location is disabled.
W/SystemReader(  947): Cannot find grip_rejection_width, use default value instead
D/PMS     (  947): releaseWL(3b03e798): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1743): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/InputMethodManagerService(  947): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/[PluginManager]RegisterService( 1653): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/VoicemailCleanupService( 1688): Cleaning up data for package: com.test.thalitest
I/[PluginManager]RegisterService( 1653): handle notify Blinkfeed plugin client changed
D/PhoneApp( 1542): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/art     ( 1583): Explicit concurrent mark sweep GC freed 6128(312KB) AllocSpace objects, 6(580KB) LOS objects, 34% free, 29MB/45MB, paused 961us total 79.625ms
D/Prism.PackageStateRece_( 1583): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1583): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1583): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1743): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1583): Deferring update until onResume
D/Launcher( 1583): waitUntilResume // bindAppsRemoved
I/ActivityManager(  947): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7107 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/ResourcesManager(  947): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/ExternalAccountType( 1743): Unsupported attribute readOnly
I/art     (  947): Explicit concurrent mark sweep GC freed 32014(2MB) AllocSpace objects, 14(1256KB) LOS objects, 33% free, 16MB/24MB, paused 2.505ms total 195.890ms
I/art     (  947): WaitForGcToComplete blocked for 175.515ms for cause Explicit
W/ContextImpl( 7107): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  947): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  947): hiding MENU key
D/StatusBarManagerService(  947): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  947): hiding MENU key
D/FindExtension( 1583): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1583): Defer allocateBuffers to drawing time
W/InputMethodManagerService(  947): Got RemoteException sending setActive(false) notification to pid 6690 uid 10366
D/StatusBarManagerService(  947): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  947): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7130 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  947): Killing 6011:com.google.android.apps.plus/u0a167 (adj 15): empty for 1803s
D/Process (  947): killProcessQuiet, pid=6011
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/PackageManager(  947): Unable to load service info ResolveInfo{b7fc7e6 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  947): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  947): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  947): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  947): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  947): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  947): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  947): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  947): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  947): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  947): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  947): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/JobSchedulerService(  947): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  947): Explicit concurrent mark sweep GC freed 8055(458KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.532ms total 204.784ms
I/ActivityManager(  947): Recipient 6011
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/TaskPersister(  947): removeObsoleteFile: deleting file=8_task.xml
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7130): -onCreate()
V/Settings:HtcSettingsApplication( 7130): [7130/7130] onCreate()
I/ActivityManager(  947): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7155 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  947): killProcessQuiet, pid=6463
I/ActivityManager(  947): Killing 6463:com.google.android.talk/u0a112 (adj 15): empty for 1803s
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/Settings:HtcWirelessFeatureFlags( 7130): id/is att sku: 118/false
E/Settings:HtcWrapHeaderInfo( 7130): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7130): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7130): updateDevelopment, bPrefShow = true
I/ActivityManager(  947): Recipient 6463
E/Settings:HtcUmcWidgetEnabler( 7130): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]support         :false
I/ActivityManager(  947): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7130): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7130): isSupportVoWifi: null
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7130): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7130): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7130): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7130): [supportHomeButton]support         :false
I/ActivityManager(  947): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7130): isSupportVoWifi: null
E/ActivityThread( 7130): Failed to find provider info for com.htc.vowifi
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7155, uid=10072, userID:0
W/global  ( 7155): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 7155): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 7155): [apache-http] Connection GC has been deprecated!
W/global  ( 7155): [apache-http] Connection GC has been deprecated!
E/RollingFileStream( 7155): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 7155): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  947): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7198 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 7155): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7155): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 7155): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 7155): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7155): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7155): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7155): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7155): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 7155): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 7155): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 7155): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7155): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7155): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7155): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 7155): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 7155): Process: com.android.vending, PID: 7155
E/AndroidRuntime( 7155): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7155): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7155): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7155): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7155): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 7155): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 7155): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 7155): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 7155): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7155): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7155): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  947): App crashed! Process: com.android.vending
E/DropBoxManagerService(  947): Can't write: system_app_crash
E/DropBoxManagerService(  947): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  947): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  947): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  947): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  947): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  947): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  947): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  947): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  947): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  947): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  947): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  947): 	... 5 more
D/Process ( 7155): killProcess, pid=7155
I/ActivityManager(  947): Killing 6817:com.google.android.music:main/u0a159 (adj 15): empty for 1800s
D/Process (  947): killProcessQuiet, pid=6817
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
D/Process ( 7155): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
D/MediaRouterService(  947): Client com.google.android.music (pid 6817): Died!
I/ActivityManager(  947): Recipient 7155
I/ActivityManager(  947): Recipient 6817
I/TrimMemoryManager( 1583): [trimMemory] 5
I/ActivityManager(  947): Process com.android.vending (pid 7155) has died
D/HtcUPManager( 1222): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 5
D/ChimeraCfgMgr( 4414): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ResourcesManager( 7198): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7198): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Prism.ItemManager( 1583): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1583): loadItems() com.htc.launcher.pageview.WidgetManager@1a7bbacc +
I/Prism.WidgetManager( 1583): onLoadItems() +
I/MultiDex( 7198): VM with version 2.1.0 has multidex support
I/MultiDex( 7198): install
I/MultiDex( 7198): VM has multidex support, MultiDex support library is disabled.
W/ResourcesManager( 1583): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/JNIHelp ( 7198): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 7198): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7198): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2788db53: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7198): Installed default security provider GmsCore_OpenSSL
E/SQLiteLog( 1968): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1968): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x55a7d84d90
E/AndroidRuntime( 1968): FATAL EXCEPTION: main
E/AndroidRuntime( 1968): Process: com.google.process.gapps, PID: 1968
E/AndroidRuntime( 1968): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1968): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1968): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1968): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1968): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1968): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1968): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1968): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1968): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1968): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1968): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1968): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1968): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1968): 	... 9 more
E/DropBoxManagerService(  947): Can't write: system_app_crash
E/DropBoxManagerService(  947): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  947): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  947): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  947): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  947): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  947): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  947): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  947): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  947): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  947): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  947): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  947): 	... 5 more
E/ActivityManager(  947): App crashed! Process: com.google.process.gapps
D/Process ( 1968): killProcess, pid=1968
D/Process ( 1968): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/NativeLibraryUtils( 7198): Failed to open lock file
W/NativeLibraryUtils( 7198): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7198): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7198): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7198): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7198): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7198): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7198): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7198): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7198): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7198): 	... 3 more
W/ResourcesManager( 1583): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  947): Recipient 1968
I/ActivityManager(  947): Process com.google.process.gapps (pid 1968) has died
I/ActivityThread( 7198): Removing dead content provider:android.content.ContentProviderProxy@f73f989
W/ActivityManager(  947): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
W/ActivityManager(  947): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 11000ms
W/ActivityManager(  947): Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
W/ActivityManager(  947): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
I/ActivityManager(  947): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7228 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a

```
