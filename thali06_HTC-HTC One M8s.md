#### Test 55613145c131883_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
I/ActivityManager(  958): Killing 5618:com.htc.musicenhancer/u0a49 (adj 15): empty #17
--------- beginning of main
D/Process (  958): killProcessQuiet, pid=5618
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  958): Recipient 5618
E/cutils-trace( 6719): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6719): ====startRecUseTime====
D/htc.customization.log.level( 6719):  is 
W/CustomizationLogLevel( 6719): Level value is invalid, use default level 2
D/CustomizationManager( 6719):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 6719): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6719): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6719): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6719): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6719): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6719): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6719): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6719): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6719): Parsing tag category name = system
I/CustomizationCIDLoader( 6719): Parsing tag category name = application
I/CustomizationCIDLoader( 6719): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6719): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6719): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6719): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6719): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6719): add string-array item, value = 42507
I/CustomizationCIDLoader( 6719): add string-array item, value = 21902
I/CustomizationCIDLoader( 6719): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6719): add string-array item, value = 23420
I/CustomizationCIDLoader( 6719): add string-array item, value = 22299
I/CustomizationCIDLoader( 6719): add string-array item, value = 24002
I/CustomizationCIDLoader( 6719): add string-array item, value = 23210
I/CustomizationCIDLoader( 6719): add string-array item, value = 23205
I/CustomizationCIDLoader( 6719): add string-array item, value = 23806
I/CustomizationCIDLoader( 6719): add string-array item, value = 23430
I/CustomizationCIDLoader( 6719): add string-array item, value = 23408
I/CustomizationCIDLoader( 6719): add string-array item, value = 27205
I/CustomizationCIDLoader( 6719): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6719): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6719):  Read CID file spent 0.098 (s)
D/CustomizationManager( 6719):  All configurations done spent 0.098 (s)
I/ActivityManager(  958): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6719 on display 0
D/PMS     (  958): acquireHCC(94d7c91): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 958 1000 null
D/PMS     (  958): acquireHCC(3b1867f6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 958 1000 null
I/ActivityManager(  958): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6737 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1331): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1331): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  958): Display changed displayId=0
I/TrimMemoryManager( 1633): [trimMemory] 20
W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 2
I/WebViewFactory( 6737): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6737): Time to load native libraries: 12 ms (timestamps 310-322),
,I/LibraryLoader( 6737): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6737): Binding Chromium to main looper Looper (main, tid 1) {1a589dc3},
I/LibraryLoader( 6737): Expected native library version number "",actual native library version number ""
,I/chromium( 6737): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6737): Initializing chromium process, singleProcess=true,
,W/art     ( 6737): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6737): ApplicationContext is null in ApplicationStatus
,W/chromium( 6737): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6737): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6737): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 6737): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6737): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6737): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6737): Local Branch: 
I/Adreno-EGL( 6737): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6737): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6737):                  d74aa161a12b9c6fc6332151
,W/System.err(  958): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  958): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  958): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@deb5eef:true
,D/BluetoothAdapter( 6737): 599647934: getState(). Returning 12
,W/art     ( 6737): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6737): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6737): CordovaWebView is running on device made by: HTC
,W/art     ( 6737): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6737): Attempt to remove local handle scope entry from IRT, ignoring,
,W/HtcSystemUPManager(  958): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
W/chromium( 6737): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  958): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
D/StatusBarManagerService(  958): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
,D/FindExtension( 6737): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6737): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@12d134a5, mServedView=org.apache.cordova.engine.SystemWebView{1dbbe07a VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3fbff02b
,I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
I/InputMethodManagerService(  958): Disable input method client, pid=1633
,D/StatusBarManagerService(  958): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6737): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  958): Displayed com.test.thalitest/.MainActivity: +627ms (total +678ms)
,W/BindingManager( 6737): Cannot call determinedVisibility() - never saw a connection for the pid: 6737,
,D/JsMessageQueue( 6737): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6737): JniHelper::setJavaVM(0xab3cb8f8), pthread_self() = -1401979048
,D/JX-Cordova( 6737): jxcore cordova android initializing
,W/jxcore-log( 6737): Initializing JXcore engine,
W/jxcore-log( 6737): JXcore engine is ready
,W/jxcore-log( 6737): Starting JXcore engine,
,W/jxcore-log( 6737): Platform android
W/jxcore-log( 6737): 
,W/jxcore-log( 6737): Process ARCH arm
W/jxcore-log( 6737): 
,D/PMS     (  958): releaseHCC(94d7c91): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  958): releaseHCC(3b1867f6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6737): JXcore Cordova bridge is ready!,
I/jxcore-log( 6737): 
W/jxcore-log( 6737): JXcore engine is started
I/Choreographer( 6737): Skipped 96 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6737): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6737): Toggling radios to true,
I/jxcore-log( 6737): 
,D/BluetoothAdapter( 6737): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  958): ADD_CLIENT: 8,
,D/WifiService(  958): New client listening to asynchronous messages,
D/WifiManager( 6737): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  958): setWifiEnabled: true pid=6737, uid=10366
W/Settings:Agent(  958): MONITOR_LOG
E/WifiService(  958): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  958): name: wifi_on
I/WifiService(  958): isSprintWifiRestricted(): false
W/Settings:Agent(  958): value: 2
,I/WifiService(  958): isMdmWifiRestricted(): false
W/Settings:Agent(  958): >> traceCallingStack()
W/Settings:Agent(  958): Process.myPid(): 958
W/Settings:Agent(  958): Process.myTid(): 1612
W/Settings:Agent(  958): Process.myUid(): 1000
W/Settings:Agent(  958): 
W/Settings:Agent(  958): 
W/System.err(  958): java.lang.Throwable: stack dump
,W/System.err(  958): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  958): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  958): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  958): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  958): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  958): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  958): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
,W/System.err(  958): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  958): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  958): 
,W/Settings:Agent(  958): << traceCallingStack(): 17(ms)
,D/WifiController(  958): handleMessage: E msg.what=155656
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): handleMessage: X
D/WifiManager( 6737): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  958): handleMessage: E msg.what=131145
E/WifiStateMachine(  958): processMsg: ConnectedState
D/WifiManager( 6737): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  958):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
,D/wpa_supplicant( 1309): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1309): wlan0: Cancelling scan request
D/wpa_supplicant( 1309): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1309): TDLS: Tear down peers
D/wpa_supplicant( 1309): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6737): Radios toggled
I/jxcore-log( 6737): 
,I/jxcore-log( 6737): My device name is: HTC-HTC One M8s,
I/jxcore-log( 6737): 
,D/wpa_supplicant( 1309): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1309): wlan0: Deauthentication notification
D/wpa_supplicant( 1309): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1309): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1309): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1309): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1309): enter disconnect check
I/wpa_supplicant( 1309): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1309): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1309): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  958): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  958): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,E/WifiMonitor(  958): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/Tethering(  958): interfaceLinkStateChanged wlan0, false
,D/Tethering(  958): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  958): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  958): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  958): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  958): acquireWL(3db62dd7): PARTIAL_WAKE_LOCK  NetworkStats 0x1 958 1000 null
D/Tethering(  958): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbDeviceManager(  958): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/UsbnetService(  958): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1309): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1309): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1309): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/Tethering(  958): interfaceLinkStateChanged wlan0, false
D/Tethering(  958): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1309): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1309): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x559ecb6f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
D/wpa_supplicant( 1309):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1309): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1309): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1309): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1309): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1309): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1309): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1309): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1309): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1309): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1309): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1309): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1309): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1309): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1309): EAPOL: External notification - portValid=0
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1309): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  958): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1309): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1309): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1309): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1309): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  958): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  958): handleMessage: new destination call exit/enter
E/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  958): invokeExitMethods: ConnectedState
D/WifiMonitor(  958): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  958): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  958): release()
E/WifiStateMachine(  958): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  958): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  958): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  958): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  958): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  958): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  958): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  958): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1309): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1309): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1309): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/TetherSettings( 5947): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5947): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5947): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5947): Cust_ConnectToPC   : spcsc>false
D/        ( 5947): Cust_ConnectToPC   : IPT>true
D/        ( 5947): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5947): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5947): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5947): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5947): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1309): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1309): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1309): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1309): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiP2pService(  958): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiP2pService(  958): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  958): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1309): Power_Mode_Type mode = 0
I/wpa_supplicant( 1309): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
W/ContextImpl( 5947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1309): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  958): setDhcpActive: false
,I/SmartNS_Utility( 5947): setISNotification
D/SmartNS_Utility( 5947): usb_cable_connect = 1
D/SmartNS_Utility( 5947): usb_denied = 0
V/NativeCrypto( 1845): Read error: ssl=0x558faea590: I/O error during system call, Connection timed out
I/SmartNS_PSService( 5947): usb notificaiton:true
,E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  958): acquireWL(13d336c4): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActionCombine( 5947): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/ConnectivityService(  958): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
V/NativeCrypto( 1845): SSL shutdown failed: ssl=0x558faea590: I/O error during system call, Broken pipe
D/ConnectivityService(  958): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/PMS     (  958): releaseWL(3db62dd7): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  958): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  958): setDetailed state send new extra info<unknown ssid>
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  958): NetworkAgent != null
,E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  958): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/SmartNS_Utility( 5947): usb_cable_connect = 1
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/SmartNS_Utility( 5947): usb_denied = 0,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): Forcing reevaluation
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected
I/SmartNS_PSService( 5947): usb notificaiton:true
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,V/NetworkPolicy(  958): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): Validated
V/NetworkPolicy(  958): updateNetworkEnabledLocked()
E/WifiStateMachine(  958): autoRoamSetBSSID any key="NG700"WPA_PSK
V/NetworkPolicy(  958): updateNotificationsLocked()
E/WifiConfigStore(  958): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  958): releaseWL(13d336c4): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
W/WifiHW  (  958): QCOM Debug skip set_network part for security concern!
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1309): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1309): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1309): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/WifiDataStallTracker(  958): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  958): stopDataStallAlarm 
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 14
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiDataStallTracker(  958): ENABLE_DATA_MONITOR_POLL false Token 3
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/wpa_supplicant( 1309): wlan0: Control interface command 'SAVE_CONFIG'
D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/wpa_supplicant( 1309): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1309): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
,D/wpa_supplicant( 1309): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  958): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  958):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  958): Start Disconnecting Watchdog 1
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131146
E/WifiStateMachine(  958): processMsg: DisconnectingState
E/WifiStateMachine(  958):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1309): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1309): Fast associate: Old scan results
D/wpa_supplicant( 1309): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1309): wpa_supplicant_scan enter
D/wpa_supplicant( 1309): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1309): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1309): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1309): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1309): WPS:  * Request Type
D/wpa_supplicant( 1309): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1309): WPS:  * UUID-E
D/wpa_supplicant( 1309): WPS:  * Primary Device Type
D/wpa_supplicant( 1309): WPS:  * RF Bands (3)
D/wpa_supplicant( 1309): WPS:  * Association State
D/wpa_supplicant( 1309): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1309): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1309): WPS:  * Manufacturer
D/wpa_supplicant( 1309): WPS:  * Model Name
D/wpa_supplicant( 1309): WPS:  * Model Number
D/wpa_supplicant( 1309): WPS:  * Device Name
D/wpa_supplicant( 1309): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1309): P2P: * P2P IE header
D/wpa_supplicant( 1309): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1309): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1309): wlan0: Add radio work 'scan'@0x559ecb9680
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1309): wlan0: First radio work item in the queue - schedule start immediately
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1309): wlan0: Starting radio work 'scan'@0x559ecb9680 after 0.000046 second wait
D/wpa_supplicant( 1309): wlan0: nl80211: scan request
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  958): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  958): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/wpa_supplicant( 1309): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1309): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1309): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1309): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1309): wlan0: Own scan request started a scan in 0.000103 seconds
I/wpa_supplicant( 1309): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  958): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  958): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147460
E/WifiStateMachine(  958): processMsg: DisconnectingState
E,/WifiStateMachine(  958):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132778
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132778
E/WifiStateMachine(  958): ConnectModeState: Network connection lost 
E/WifiStateMachine(  958): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  958): handleMessage: new destination call exit/enter
E/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  958): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  958): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  958): DisconnectedState call setCountryCode()
E/WifiStateMachine(  958):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1309): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1309): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1309): wlan0: Cancelling scan request
D/SmartNS_NSReceiver( 5947): Tethered state change:false isNSOpening:false
D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1309): wlan0: nl80211: sched_scan request
I/RemoteViews( 1219): reapply : com.android.settings 0 36
I/RemoteViews( 1219): reapply : com.android.settings 1 36
,I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1,
D/wpa_supplicant( 1309): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1309): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0,
D/wpa_supplicant( 1309): wlan0: nl80211: Sched scan started
,D/wpa_supplicant( 1309): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,D/wpa_supplicant( 1309): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1309): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1309): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1309): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1309): wlan0: Scan completed in 0.047207 seconds
D/wpa_supplicant( 1309): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1309): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
D/wpa_supplicant( 1309): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1309): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1309): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1309): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1309): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1309): wlan0: Radio work 'scan'@0x559ecb9680 done in 0.048027 seconds
D/wpa_supplicant( 1309): wlan0: Selecting BSS from priority group 499
D/wpa_supplicant( 1309): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-62 wps
D/wpa_supplicant( 1309): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1309): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1309): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
,D/wpa_supplicant( 1309):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1309): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1309): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x559ecb8c00  current_ssid=0x0
D/wpa_supplicant( 1309): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1309): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1309): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1309): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1309): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1309): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1309): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1309): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1309): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1309): wlan0: Add radio work 'connect'@0x559ecb9680
D/wpa_supplicant( 1309): wlan0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1309): wlan0: Starting radio work 'connect'@0x559ecb9680 after 0.000052 second wait
I/wpa_supplicant( 1309): check if in concurrent case
I/wpa_supplicant( 1309): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:2
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  958): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  958): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=42 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  958): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1309): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1309): wlan0: Cancelling sched scan
D/WifiMonitor(  958): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=43 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1309): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1309): wlan0: Cancelling scan request
D/wpa_supplicant( 1309): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1309): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1309): wpas_start_assoc_cb, 1910
,D/wpa_supplicant( 1309): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1309): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1309): RSN: PMKSA cache search - network_ctx=0x559ecb8c00 try_opportunistic=0
D/wpa_supplicant( 1309): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1309): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1309): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1309): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1309): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1309): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1309): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1309): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1309): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1309): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1309): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1309): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1309): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1309): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1309): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1309): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1309): nl80211: Unsubscribe mgmt frames handle 0x888888dd16430989 (mode change)
,D/wpa_supplicant( 1309): nl80211: Subscribe to mgmt frames with non-AP handle 0x559ecb8100
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=0104
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=040a
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=040b
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=040c
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=040d
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=090a
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=090b
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=090c
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=090d
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=0409506f9a09
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=7f506f9a09
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=0801
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=040e
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=06
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=0a07
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=0a11
D/wpa_supplicant( 1309): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559ecb8100 match=0a1a
D/wpa_supplicant( 1309): nl80211: Connect (ifindex=29)
,D/wpa_supplicant( 1309):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309):   * freq=2412
D/wpa_supplicant( 1309):   * freq_hint=2412
D/wpa_supplicant( 1309):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1309):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1309):   * WPA Versions 0x2
D/wpa_supplicant( 1309):   * pairwise=0xfac04
D/wpa_supplicant( 1309):   * group=0xfac04
D/wpa_supplicant( 1309):   * akm=0xfac02
D/wpa_supplicant( 1309):   * Auth Type 0
D/wpa_supplicant( 1309): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x559ecb8c3a
D/wpa_supplicant( 1309): nl80211: Connect request send successfully
D/wpa_supplicant( 1309): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1309): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1309): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1309): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1309): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1309): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1309): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131101
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
,E/WifiStateMachine(  958):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  958):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  958): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  958): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  958):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  958): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  958): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147462
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132831  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  958): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  958): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132831  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131212
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  958): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131212
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  958): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  958): handleMessage: X
D/WifiNetworkAgent(  958): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  958): handleMessage: E msg.what=131212
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  958): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147462
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=132838  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  958): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  958): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  958): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  958): NetworkAgent == null
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5947): >>>>>WISPrService start isConnected = true<<<<<
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 16
,I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=132845  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147461
E/WifiStateMachine(  958): processMsg: DisconnectedState
,E/WifiStateMachine(  958):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:85 bcn=0
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  958): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T],
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 17
W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  958):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:85 bcn=0
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:85 bcn=0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 dur:85 bcn=0
D/WifiStateMachine(  958): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1309): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  958): [1,452,773,898,935 ms] noteScanEnd no scan source
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1309): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/WifiService(  958): New client listening to asynchronous messages
E/WifiTrafficPoller(  958): ADD_CLIENT: 9
E/WifiStateMachine(  958): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@bdb6dbb sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  958): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  958): NG700 c0:ff:d4:d3:aa:48 rssi=-62 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  958): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  958): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  958):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-62 freq=2412
E/WifiAutoJoinController (  958): Gonzos 38:f8:89:11:e9:11 rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  958): UPC503894600 a0:c5:62:7a:49:97 rssi=-80 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  958): ageScanResultsOut delay 40000 size 5 now 1452773898938
E/WifiAutoJoinController (  958): newSupplicantResults size=5 known=1 true
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1309): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  958): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  958): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  958): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  958): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  958): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  958):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131213
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132855
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132856
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132856
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132856
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147462
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=132856  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  958): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  958): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  958): setDetailed state send new extra info0x
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  958): NetworkAgent == null
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 18
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=132862  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  958): handleMessage: X
D/ConnectivityService(  958): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  958):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  958):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  958): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  958): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  958): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  95,8): Disconnected - quitting
D/ConnectivityService(  958): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  958): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  958): Removing idletimer
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524292
D/usbnet  (  958):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  958): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/SecurityController( 1219): onLost 100
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiStateMachine(  958): handleMessage: E msg.what=131131
E/WifiStateMachine(  958): processMsg: DisconnectedState
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  958):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  958): handleMessage: X
D/WIFI    (  958): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  958):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  958): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  958): enter WifiNetworkFactory startNetwork. mIPTStart:false
W/WISPrService( 5947): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5947): trigger connection
D/WISPrService( 5947): continue
D/PMS     (  958): acquireWL(347774e2): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 958 1000 null
D/CSLegacyTypeTracker(  958): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  958): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  958): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  958): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/PMS     (  958): acquireWL(545d073): PARTIAL_WAKE_LOCK  NetworkStats 0x1 958 1000 null
D/Tethering(  958): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  958): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  958): ensureActiveMobilePolicyLocked()
D/WISPrService( 5947): start DataConnection
E/ConnectivityService(  958): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DATA_ICON( 1219): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5947): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5947): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  958): releaseWL(545d073): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkPolicy(  958): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  958): updateNetworkEnabledLocked()
V/NetworkPolicy(  958): updateIfacesLocked()
D/DATA_ICON( 1219): dataConnected: false/false
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  958): updateNotificationsLocked()
D/libc    ( 5947): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5947): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5947): [NET] android_getaddrinfo_proxy+
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5947): [NET] android_getaddrinfo_proxy get netid:0
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
V/NetworkPolicy(  958): updateNetworkEnabledLocked()
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
V/NetworkPolicy(  958): updateNotificationsLocked()
D/libc    ( 5947): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/NetworkManagementService(  958): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6581): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/FlexNetS( 6581): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
I/ActivityManager(  958): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6800 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    ( 5947): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5947): [NET] android_getaddrinfofornet-, err=8
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/FlexNetS( 6581): updateSvcAllowedInSettings:false
D/WISPrService( 5947): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
I/art     (  407): Explicit concurrent mark sweep GC freed 8638(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 234us total 22.792ms
,D/FlexNetS( 6581): updateSvcAllowedInSettings:false
,D/Tethering(  958): interfaceLinkStateChanged wlan0, false
D/PMS     (  958): acquireWL(3bf8daeb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 958 1000 null
D/Tethering(  958): interfaceStatusChanged wlan0, false
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbDeviceManager(  958): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1309): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1309): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1309): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1309): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1309): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1309): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1309): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1309): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/Tethering(  958): interfaceLinkStateChanged wlan0, false
D/Tethering(  958): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1309): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1309): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1309): nl80211: Connect event
D/wpa_supplicant( 1309): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1309): nl80211: Associated with c0:ff:d4:d3:aa:48
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1309): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1309): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1309): wlan0: Association info event
D/wpa_supplicant( 1309): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1309): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1309): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1309): wlan0: freq=2412 MHz
D/wpa_supplicant( 1309): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1309): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1309): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1309): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/Tethering(  958): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1309): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  958): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1309): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1309): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1309): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1309): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1309): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1309): TDLS: Remove peers on association
D/wpa_supplicant( 1309): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1309): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1309): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1309): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1309): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1309): EAPOL: enable timer tick
D/wpa_supplican,t( 1309): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1309): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1309): wlan0: Cancelling scan request
I/wpa_supplicant( 1309): htc_wext_set_keepalive +
I/wpa_supplicant( 1309): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1309): getPrivFuncNum +	
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
I/wpa_supplicant( 1309): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1309): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  958): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1309): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1309): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1309): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1309): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1309): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1309): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1309):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1309):   key_nonce - hexdump(len=32): fb 39 28 7e 93 02 8d dd d2 73 8d f5 4e ef 61 11 db 52 90 c0 8a 3d 6d 2f 65 d5 ec ab 80 60 6a c1
D/wpa_supplicant( 1309):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1309):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1309):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1309):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1309): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1309): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Tethering(  958): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1309): RSN: msg 1/4 key data - hexdump(len=0):
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1309): WPA: Renewed SNonce - hexdump(len=32): c9 d7 76 7a ff 8c 82 50 3c ee a9 02 fa 3f 15 9a b6 76 01 ea fa 59 14 9f dd 53 a3 91 05 52 58 61
V/Tethering(  958): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1309): WPA: Nonce1 - hexdump(len=32): c9 d7 76 7a ff 8c 82 50 3c ee a9 02 fa 3f 15 9a b6 76 01 ea fa 59 14 9f dd 53 a3 91 05 52 58 61
D/wpa_supplicant( 1309): WPA: Nonce2 - hexdump(len=32): fb 39 28 7e 93 02 8d dd d2 73 8d f5 4e ef 61 11 db 52 90 c0 8a 3d 6d 2f 65 d5 ec ab 80 60 6a c1
D/wpa_supplicant( 1309): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1309): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1309): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1309): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1309): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1309): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1309): WPA: Derived Key MIC - hexdump(len=16): b9 4f 6c 91 63 e8 b4 0a 11 7d 1f ae c2 fa bd 12
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  958): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  958): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  9,58): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/PMS     (  958): releaseWL(3bf8daeb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiMonitor(  958): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  958): handleMessage: E msg.what=147462
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=46 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiMonitor(  958): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  958): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
V/NetworkPolicy(  958): updateNetworkEnabledLocked()
D/HTCRequest(  958): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
V/NetworkPolicy(  958): updateNotificationsLocked()
D/HTCRequest(  958): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  958): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  958): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  958):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=132955  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  958): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/WifiMonitor(  958): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  958): handleAssociatedWithEvent. bLFR =false
E/WifiStateMachine(  958): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/WifiMonitor(  958): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
E/WifiStateMachine(  958): processMsg: ConnectModeState
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  958): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  958):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=132956  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor(  958): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147500
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  958): Enter handleAssociatedWithEvent
D/WifiStateMachine(  958): Associated
D/wpa_supplicant( 1309): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1309): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1309): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1309): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1309):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1309):   key_nonce - hexdump(len=32): fb 39 28 7e 93 02 8d dd d2 73 8d f5 4e ef 61 11 db 52 90 c0 8a 3d 6d 2f 65 d5 ec ab 80 60 6a c1
D/wpa_supplicant( 1309):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1309):   key_rsc - hexdump(len=8): 13 05 00 00 00 00 00 00
D/wpa_supplicant( 1309):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1309):   key_mic - hexdump(len=16): 99 b6 90 3b 70 e2 34 c0 16 8d b3 a5 54 b0 d7 e3
D/wpa_supplicant( 1309): RSN: encrypted key data - hexdump(len=56): 42 1a d1 43 35 ea f3 cd 26 9a 47 b3 46 f7 6d af cb 11 11 55 45 09 8a 51 23 64 24 77 4e fc ce 80 ...
D/wpa_supplicant( 1309): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1309): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1309): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1309): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 a6 39 ...
D/wpa_supplicant( 1309): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1309): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1309): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1309): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1309): WPA: Derived Key MIC - hexdump(len=16): 7b 27 e5 3e 81 0c 11 80 12 e8 68 da fc 9f f3 c1
D/wpa_supplicant( 1309): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1309): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x559ecb9390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1309): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1309): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1309):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  958): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  958): Exit handleAssociatedWithEvent
E/WifiStateMachine(  958): handleMessage: X
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 147us total 16.499ms
D/wpa_supplicant( 1309): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1309): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1309): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1309): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1309): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1309): WPA: RSC - hexdump(len=6): 13 05 00 00 00 00
D/wpa_supplicant( 1309): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x558c724e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1309): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1309): nl80211: KEY_SEQ - hexdump(len=6): 13 05 00 00 00 00
D/wpa_supplicant( 1309):    broadcast key
I/wpa_supplicant( 1309): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1309): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1309): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/wpa_supplicant( 1309): wlan0: Radio work 'connect'@0x559ecb9680 done in 0.136014 seconds
I/wpa_supplicant( 1309): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1309): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/UsbnetService(  958): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  958): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1309): wlan0: Connect to SSID: NG700
D/WifiMonitor(  958): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1309): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1309): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  958): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiStateMachine(  958): handleMessage: E msg.what=147462
D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=49 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  958): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  958): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=50 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  958): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1309): set send_ind_to_ndc = 0
I/wpa_supplicant( 1309): htc_wext_set_TX_TRACKING (1)+
D/WifiMonitor(  958): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=52 dispatchEvent: Connect to SSID: NG700
I/wpa_supplicant( 1309): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1309): EAPOL: External notification - portValid=1
W/WifiMonitor(  958): couldn't identify event type - Connect to SSID: NG700
D/wpa_supplicant( 1309): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1309): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1309): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1309): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1309): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1309): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1309): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  958):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=132962  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  958): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
D/HTCRequest(  958): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  958): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1309): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1309): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1309): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/WifiStateMachine(  958): setDetailed state send new extra info"NG700"
D/wpa_supplicant( 1309): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  958): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/Tethering(  958): interfaceLinkStateChanged wlan0, true
D/Tethering(  958): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  958): NetworkAgent == null
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  958): processMsg: ConnectModeState
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  958):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=132967  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131101
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  958):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
D/FlexNetS( 6581): updateSvcAllowedInSettings:false
E/WifiStateMachine(  958):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  958): processMsg: DefaultState
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  958):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  958): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  958): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147462
E/WifiStateMachine(  958): processMsg: DisconnectedState
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  958):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=132971  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  958): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  958): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/ConnectivityService(  958): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=132972  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/ConnectivityService(  958): Got NetworkAgent Messenger
E/WifiStateMachine(  958): handleMessage: X
D/ConnectivityService(  958): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  958): handleMessage: E msg.what=147459
D/ConnectivityService(  958): NetworkAgent connected
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=132973
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=132973
E/WifiStateMachine(  958): Network connection established
D/WifiStateMachine(  958): fetchFrequency(), freq = 2412
E/WifiStateMachine(  958): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  958): NetworkAgent == null
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  958): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  958): handleMessage: new destination call exit/enter
E/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  958): invokeExitMethods: DisconnectedState
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1309): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1309): CTRL_IFACE SET 'pno'='0'
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  958): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  958): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  958): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  958): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  958): NetworkAgent == null
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 22
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 23
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 144us total 18.221ms
E/WifiStateMachine(  958): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  958): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  958): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  958): QCOM Debug skip set_network part for security concern!
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 24
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1309): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1309): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1309): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/FlexNetS( 6581): updateSvcAllowedInSettings:false
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1309): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1309): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1309): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1309): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  958): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  958): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  958): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  958): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  958): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  958): QCOM Debug skip set_network part for security concern!
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1309): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1309): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1309): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1309): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1309): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1309): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1309): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  958): Start Dhcp Watchdog 2
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147462
E/WifiStateMachine(  958): processMsg: ObtainingIpState
E/WifiStateMachine(  958):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=132993  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  958): processMsg: L2ConnectedState
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  958):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=132994  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=132994  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  958): handleMessage: X
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
E/WifiStateMachine(  958): handleMessage: E msg.what=131212
E/WifiStateMachine(  958): processMsg: ObtainingIpState
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  958):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  958):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WISPrService( 5947): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  958): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  958): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  958): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=196612
E/WifiStateMachine(  958): processMsg: ObtainingIpState
D/WISPrService( 5947): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  958):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  958): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  958): acquireWL(22bbbbf): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 958 1000 null
D/WifiStateMachine(  958): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  958): setDhcpActive: true
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1309): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  958): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  958): do suspend false
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1309): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1309): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1309): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1309): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1309): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1309): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1309): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  958): Unexpected BatchedScanResults :null
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1309): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  958): noteBatchedScanstop()
E/WifiStateMachine(  958): handleMessage: X
D/WifiP2pService(  958): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14523b09 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  958): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14523b09 target=com.android.internal.util.StateMachine$SmHandler }
D/FlexNetS( 6581): updateSvcAllowedInSettings:false
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/FlexNetS( 6581): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiService(  958): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
D/TetherSettings( 5947): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5947): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5947): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5947): Cust_ConnectToPC   : spcsc>false
D/        ( 5947): Cust_ConnectToPC   : IPT>true
D/        ( 5947): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5947): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5947): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5947): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5947): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5947): setISNotification
D/SmartNS_Utility( 5947): usb_cable_connect = 1
D/SmartNS_Utility( 5947): usb_denied = 0
I/SmartNS_PSService( 5947): usb notificaiton:true
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
D/SmartNS_Utility( 5947): usb_cable_connect = 1
D/SmartNS_Utility( 5947): usb_denied = 0
I/SmartNS_PSService( 5947): usb notificaiton:true
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 5947): Tethered state change:false isNSOpening:false
I/RemoteViews( 1219): reapply : com.android.settings 1 36
D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/FlexNetS( 6581): updateSvcAllowedInSettings:false
I/RemoteViews( 1219): reapply : com.android.settings 1 36
,D/MdScPhnSt( 6800): [e6.2.]  listen tmrbb8
,D/FlexNetS( 6581): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6581): updateSvcAllowedInSettings:false
,D/FlexNetS( 6581): updateSvcAllowedInSettings:false
,D/FlexNetS( 6581): updateSvcAllowedInSettings:false
,D/FlexNetS( 6581): updateSvcAllowedInSettings:false
,D/FlexNetS( 6581): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6643): remove item 101 (p2d24in231) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6800): [e6.2.] summary 118:p2 ignore,
,D/MdProvGlob( 6643): remove item 101 (p2d1in13) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 6643): remove item 101 (p2in35) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6800): [e6.11.] summary 118:p1 ignore,
,E/dhcpcd  ( 6830): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6830): version 5.5.6 starting
E/dhcpcd  ( 6830): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6830): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6830): autoip env[11]:autoip=DISABLE
,I/ActivityManager(  958): Killing 6255:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=6255
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6830): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6830): wlan0: sending REQUEST (xid 0x489c2b81), next in 1.58 seconds
,I/ActivityManager(  958): Recipient 6255
,D/wpa_supplicant( 1309): EAPOL: startWhen --> 0
D/wpa_supplicant( 1309): EAPOL: disable timer tick
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  958): handleMessage: E msg.what=131212,
E/WifiStateMachine(  958): processMsg: ObtainingIpState
E/WifiStateMachine(  958):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  958): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState,
E/WifiStateMachine(  958):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  958): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  958): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  958): handleMessage: X
,I/dhcpcd  ( 6830): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6830): wlan0: leased 192.168.1.130 for 86400 seconds,
D/ConnectivityService(  958): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/dhcpcd  ( 6830): autoip env[11]:autoip=DISABLE
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  958): handleMessage: E msg.what=131212
E/WifiStateMachine(  958): processMsg: ObtainingIpState
E/WifiStateMachine(  958):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  958): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  958): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  958): handleMessage: X
,I/dhcpcd  ( 6830): bind_interface: daemonise,
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  958): handleMessage: E msg.what=196613
E/WifiStateMachine(  958): processMsg: ObtainingIpState
E/WifiStateMachine(  958):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  958): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1309): Power_Mode_Type mode = 0
I/wpa_supplicant( 1309): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  958): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  958): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1309): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  958): setDhcpActive: false
E/WifiStateMachine(  958): handlePostDhcpSetup release wake lock during DHCP
D/PMS     (  958): releaseWL(22bbbbf): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  958): WifiStateMachine DHCP successful
E/WifiStateMachine(  958): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  958): link address 192.168.1.130/24
E/WifiStateMachine(  958): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  958): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  958): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  958): gateway: /192.168.1.1
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1309): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1309): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1309): htc_wext_set_keepalive +
I/wpa_supplicant( 1309): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1309): getPrivFuncNum +	
I/wpa_supplicant( 1309): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1309): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1309): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1309): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1309): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  958): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  958): handleMessage: X
,E/WifiStateMachine(  958): handleMessage: E msg.what=131210
E/WifiStateMachine(  958): processMsg: ObtainingIpState
E/WifiStateMachine(  958):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1309): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1309): environment dirty rate=16 [6][1][0],
E/WifiStateMachine(  958): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  958): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72,
E/WifiConfigStore(  958): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
,D/WifiWatchdogStateMachine(  958): RSSI current: 3 new: -62, 3
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED -1 -> 3
D/wpa_supplicant( 1309): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1309): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  958): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=54 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  958): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/ConnectivityService(  958): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  958): NetworkAgent != null
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  958): transitionTo: destState=ConnectedState
E/WifiStateMachine(  958): handleMessage: new destination call exit/enter
D/HtcWifiWanDetect(  958): WAN detection
E/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/HtcWifiWanDetect(  958): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiStateMachine(  958): invokeExitMethods: ObtainingIpState
V/NetworkPolicy(  958): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  958): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  958): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
D/WifiDataStallTracker(  958): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiStateMachine(  958): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 25
E/WifiDataStallTracker(  958): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  958): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
E/WifiStateMachine(  958): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiStateMachine(  958): handleMessage: X
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  958): mWifiStateReceiver: meteredHint=false,EPS mode=false
,E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 26
D/ConnectivityService(  958): Adding iface wlan0 to network 101
,D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected,
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5947): >>>>>WISPrService start isConnected = true<<<<<
,E/WifiStateMachine(  958): handleMessage: E msg.what=131131
E/WifiStateMachine(  958): processMsg: ConnectedState
E/WifiStateMachine(  958):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  958): processMsg: ConnectModeState
,E/WifiStateMachine(  958):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  958): handleMessage: X
,D/WISPrService( 5947): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  958): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  958): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
,D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  958): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  958): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  958): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/Nat464Xlat(  958): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
,D/ConnectivityService(  958): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  958): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): Connected
D/ConnectivityService(  958): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  958):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): Validated
D/ConnectivityService(  958):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  958): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  958):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  958): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  958): currentScore = 0, newScore = 20
D/usbnet  (  958):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  958):    accepting network in place of null
D/WIFI    (  958):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  958): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  958): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  958): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/WIFI    (  958): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  958): sendGeneralBroadcast, restrictEnable=false
D/Tethering(  958): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  958): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  958): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  958): sendGeneralBroadcastDelayed, restrictEnable=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  958): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  958): Validated
V/NetworkPolicy(  958): ensureActiveMobilePolicyLocked()
D/WIFI    (  958): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  958): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/WIFI    (  958):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  958): acquireWL(7030b78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 958 1000 null
D/WIFI    (  958): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  958): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
D/ConnectivityService(  958):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  958):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  958): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TR,USTED&NOT_VPN] ]
D/ConnectivityService(  958): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  958):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  958): Validated NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  958): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  958): rematching NetworkAgentInfo [WIFI () - 101]
I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  958):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
D/ConnectivityService(  958):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  958): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  958): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  958):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  958):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  958): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  958): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  958): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  958): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/NetworkPolicy(  958): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  958): updateNetworkEnabledLocked()
V/NetworkPolicy(  958): updateIfacesLocked()
D/ConnectivityService(  958): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  958): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  958):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  958):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  958): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  958): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  958):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  958):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  958): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  958): updateNotificationsLocked()
D/DATA_ICON( 1219): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/NetworkManagementService(  958): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/PMS     (  958): releaseWL(7030b78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
D/DATA_ICON( 1219): dataConnected: false/false
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NetworkPolicy(  958): updateNetworkEnabledLocked()
,I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  958): updateNotificationsLocked()
I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/DATA_ICON( 1219): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,D/DATA_ICON( 1219): dataConnected: false/false
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  958): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  958): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  958): [AlarmQueuing] connectivity wifi: false
,D/PMS     (  958): acquireWL(9aa251): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 958 1000 null
D/PMS     (  958): acquireWL(3af1fab6): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 958 1000 null
,D/htcCheckinService(  958): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  958): releaseWL(3af1fab6): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  958): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  958): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ConnectivityHelper( 1633): [onReceive] WIFI(1): CONNECTED
D/PMS     (  958): releaseWL(347774e2): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  958): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  958): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6862 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  958): No APN found to select.
,D/PMS     (  958): releaseWL(9aa251): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6800): [ee8.1.]  listen tmrbb8
,D/MdScDataSum( 6800): [ee8.1.] summary 118:p1 ignore
,I/MusicStore( 6862): Database version: 120
,D/VoldConnector(  958): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6862): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  958): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6862): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  958): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6862): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6862): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6862): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6862): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6862): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6862): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3803ed06: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6862): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6862): GMSCore installation verified,
,I/ConfigStore( 6862): Config Database version: 1,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6862, uid=10159, userID:0,
,D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
,D/MediaRouterService(  958): Client com.google.android.music (pid 6862): Registered
,D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
,D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
,I/MediaRouter( 6862): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6862): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6862): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6862): type=WIFI subType= reason=null isConnected=true,
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6862, uid=10159, userID:0
,D/AutoSetting( 1546): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6462): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6462): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1546): service - onCreate()
,I/GHttpClientFactory( 6862): Using our fixed implementation of GMSCore's GoogleHttpClient,
,I/GoogleURLConnFactory( 6862): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1546): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1546): service - onStartCommand() screen is off, don't request location
D/LocationManagerService(  958): request 3294790f passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  958): provider request: passive ProviderRequest[ON interval=0]
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  958): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6906 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 6511): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6511): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6511): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6511): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6511): [NET] android_getaddrinfo_proxy+
D/libc    ( 6511): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1845): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1845): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1845): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1845): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6511): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4466): [AccountUtils] Account not ready
W/Kids    ( 4466): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4466): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4466): 	,at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4466): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4466): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4466): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4466): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4466): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4466): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4466): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4466): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4466): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
D/DotMatrix( 1331): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/Babel   ( 6511): connection state changed from UNKNOWN to CONNECTED,
,D/VoldConnector(  958): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6906): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  958): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
I/GAv4    ( 6906): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6906):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6906):   adb logcat -s GAv4
W/ContextImpl( 6906): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  958): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6906): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  958): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
W/GAv4    ( 6906): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6906): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6906): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6906): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/art     (  958): Explicit concurrent mark sweep GC freed 57211(2MB) AllocSpace objects, 3(124KB) LOS objects, 33% free, 16MB/25MB, paused 1.876ms total 140.630ms,
,W/global  ( 6906): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6906): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6906): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6906): Time to load native libraries: 1 ms (timestamps 7054-7055)
,I/LibraryLoader( 6906): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6906): Binding Chromium to main looper Looper (main, tid 1) {193b71e7},
,I/LibraryLoader( 6906): Expected native library version number "",actual native library version number "",
,I/chromium( 6906): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6906): Initializing chromium process, singleProcess=true,
,W/art     ( 6906): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6906): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6906): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6906): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6906): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6906): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6906): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6906): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6906): Local Branch: 
I/Adreno-EGL( 6906): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6906): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6906):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6906): Requires BLUETOOTH permission,
,I/NSApplication( 6906): Starting up...,
,I/ActivityManager(  958): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6966 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  958): killProcessQuiet, pid=6488
,I/ActivityManager(  958): Killing 6488:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 6488
,D/Process (  958): killProcessQuiet, pid=6417
I/ActivityManager(  958): Killing 6417:com.google.android.gms.unstable/u0a24 (adj 15): empty #18
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 6417
,E/WifiStateMachine(  958): handleMessage: E msg.what=131168
E/WifiStateMachine(  958): processMsg: ConnectedState
E/WifiStateMachine(  958):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  958): handleMessage: X
,I/ActivityManager(  958): Killing 5971:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  958): killProcessQuiet, pid=5971
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, err=8
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  958): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  958): [NET] android_getaddrinfo_proxy+,
D/libc    (  958): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  958): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/ActivityManager(  958): Recipient 5971,
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/HtcWifiWanDetect(  958): Find DNS Address www.htc.com/104.81.130.175
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  958): [NET] android_getaddrinfo_proxy-, success
,D/GpsLocationProvider(  958): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  958): [AlarmQueuing] connectivity wifi: true
D/GpsLocationProvider(  958): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  958): acquireWL(c9fd2ae): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 958 1000 null
,D/GpsLocationProvider(  958): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/NetworkMonitor( 6862): type=WIFI subType= reason=null isConnected=true
D/htcCheckinService(  958): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/ConnectivityHelper( 1633): [onReceive] WIFI(1): CONNECTED
,V/MusicLeanback( 6862): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  958): No APN found to select.
,D/PMS     (  958): releaseWL(c9fd2ae): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
D/PMS     (  958): acquireWL(11b1e4e5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 958 1000 null
,D/PMS     (  958): releaseWL(11b1e4e5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MobileConnectivityChangeReceiver( 6462): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6462): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1546): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1546): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1546): service - onStartCommand() screen is off, don't request location
,D/MdScPhnSt( 6800): [256.1.]  listen tmrbb8
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4466, uid=10024, userID:0
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/MdScDataSum( 6800): [256.1.] summary 118:p1 ignore,
,D/ChimeraCfgMgr( 4466): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1845): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1845): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1845): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1845): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4466): [AccountUtils] Account not ready
W/Kids    ( 4466): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4466): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4466): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4466): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4466): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4466): 	at com.google.android.gms.kids.account.k.d(SourceFile:103),
W/Kids    ( 4466): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4466): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4466): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4466): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4466): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4466): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1331): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,D/PMS     (  958): acquireWL(b7c435e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 958 1000 WorkSource{1000}
V/AlarmManager(  958): sending alarm PendingIntent{2f677aa3: PendingIntentRecord{337f11a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=113915, Int=0
,V/AlarmManager(  958): sending alarm PendingIntent{3923833f: PendingIntentRecord{27d6440c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=140219, Int=0
D/PMS     (  958): acquireWL(2c3ed155): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1845): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1845): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1845): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1845): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1845): [NET] android_getaddrinfo_proxy+
D/libc    ( 1845): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605,
,D/PMS     (  958): releaseWL(b7c435e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1845): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1845): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1845): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1845): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1845): [NET] android_getaddrinfofornet-, err=8,
,D/PMS     (  958): acquireWL(3745376a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1845 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1845): Connected,
,D/PMS     (  958): releaseWL(2c3ed155): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(3745376a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): acquireWL(2557145b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1845 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1845): Message class com.google.f.a.a.p,
D/PMS     (  958): releaseWL(2557145b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6737): Test app app.js loaded,
I/jxcore-log( 6737): 
I/Choreographer( 6737): Skipped 506 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6737): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/PMS     (  958): acquireWL(1e682dd1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6862 10159 null
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6862, uid=10159, userID:0,
,D/PMS     (  958): releaseWL(1e682dd1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 6862): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6862): Stop autocaching.
,D/WearableService( 4835): callingUid 10024, callindPid: 4835,
,E/GmsUtils( 6862): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6862): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  958): acquireWL(3d282c28): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{10024}
,V/AlarmManager(  958): sending alarm PendingIntent{167f2d41: PendingIntentRecord{153642e6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143610, Int=0
,D/PMS     (  958): releaseWL(3d282c28): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  958): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  958): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  958): acquireWL(3460c027): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 958 1000 null,
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  958): [NET] android_getaddrinfofornet-, err=8
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  958): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  958): [NET] android_getaddrinfo_proxy+
D/libc    (  958): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  958): [NET] android_getaddrinfo_proxy-, success
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  958): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  958): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  958): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  958):  [handleDownloadXtraData]inject done.,
D/PMS     (  958): acquireWL(130f37c3): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 958 1000 null
D/GpsLocationProvider(  958): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
D/PMS     (  958): releaseWL(3460c027): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  958): releaseWL(130f37c3): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1575): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1575): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  958): acquireWL(244a5840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null,
,I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(244a5840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  958): updateBatteryInfo
D/WifiController(  958): handleMessage: E msg.what=155652
D/PMS     (  958): runPSCheck
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  958): Checking...
D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  958): >> updateStatus
D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  958): battery changed pluggedType: 2
D/DotMatrix( 1331): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3117): Disconnected process message: 10, size: 0
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  958): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1546): service - handleMessage() stop self
,D/AutoSetting( 1546): service - handleMessage() quit looper
,D/AutoSetting( 1546): service - onDestroy() END
,E/WifiStateMachine(  958): handleMessage: E msg.what=131165
E/WifiStateMachine(  958): processMsg: ConnectedState,
E/WifiStateMachine(  958):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  958): handleMessage: X
,D/TelephonyReceiver( 1575): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  958): acquireWL(1c0b4379): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{1000}
,V/AlarmManager(  958): sending alarm PendingIntent{7f0c8be: PendingIntentRecord{3fa38d1f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452773939477, Int=0
D/PMS     (  958): acquireWL(329cb86c): PARTIAL_WAKE_LOCK  *backup* 0x1 958 1000 null
V/AlarmManager(  958): sending alarm PendingIntent{2f677aa3: PendingIntentRecord{337f11a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=173916, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{1c739e35: PendingIntentRecord{296cb2ca com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190348, Int=0
D/PMS     (  958): acquireWL(13fddc3b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  958): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  958): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  958): releaseWL(329cb86c): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  958): releaseWL(1c0b4379): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/PMS     (  958): acquireWL(2cd2ef58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): releaseWL(13fddc3b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  958): releaseWL(2cd2ef58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): acquireWL(240d122): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(240d122): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(179d97b3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(179d97b3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  958): acquireWL(19c45170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(3606fce9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): acquireWL(e4ffc0f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): releaseWL(19c45170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1845): Vacuum at: now=1452773956726 tag=VacuumService,
,D/PMS     (  958): releaseWL(3606fce9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  958): acquireWL(2fc97ea5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
I/GoogleURLConnFactory( 1845): Using platform SSLCertificateSocketFactory
,W/Uploader( 1845): No account for auth token provided,
,D/PMS     (  958): releaseWL(2fc97ea5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): acquireWL(15ff627a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(15ff627a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1845): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1845): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1845): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1845): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1845): [NET] android_getaddrinfo_proxy+
D/libc    ( 1845): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 1845): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1845): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1845): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1845): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1845): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1845): No account for auth token provided,
,W/Uploader( 1845): No account for auth token provided,
,W/Uploader( 1845):  no longer exists, so no auth token.,
,W/Uploader( 1845): No account for auth token provided,
,I/GLSUser ( 1845): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1845): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1845): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1845): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1845): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1845): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1845): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1845): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1845): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1845): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1845): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1845): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1845): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1845): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1845): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1845): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1845): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1331): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1331): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1219): reapply : com.google.android.gms 3 40
,D/PMS     (  958): releaseWL(e4ffc0f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): acquireWL(30537e1e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(30537e1e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): acquireWL(2d2e06ff): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(2d2e06ff): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiStateMachine(  958): handleMessage: E msg.what=131326,
E/WifiStateMachine(  958): processMsg: ConnectedState
E/WifiStateMachine(  958):  ConnectedState what:131326 2 0
E/WifiStateMachine(  958): processMsg: L2ConnectedState
E/WifiStateMachine(  958):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  958): handleMessage: X
,D/PMS     (  958): acquireWL(2af4dccc): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{1000},
V/AlarmManager(  958): sending alarm PendingIntent{37505b15: PendingIntentRecord{10355e2a android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=210024, Int=0
D/PMS     (  958): releaseWL(2af4dccc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1546): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@13c13df5
,D/Process (  958): killProcessQuiet, pid=5887
I/ActivityManager(  958): Killing 5887:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5887
,D/PMS     (  958): acquireWL(27e6141b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
,I/BatteryService(  958): n_update end
,D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PMS     (  958): releaseWL(27e6141b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  958): runPSCheck
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  958): Checking...
I/HtcPowerSaver(  958): >> updateStatus
D/DotMatrix( 1331): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1331): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): handleMessage: E msg.what=155652
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  958): processMsg: DeviceActiveState
I/HtcPowerSaver(  958): << updateStatus
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
D/HeadsetStateMachine( 3117): Disconnected process message: 10, size: 0
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1219): closing low battery warning: level=100
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1309): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1309): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97
D/wpa_supplicant( 1309): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6737): --= Surplus to requirements =--
I/jxcore-log( 6737): 
,I/jxcore-log( 6737): ****TEST TOOK:  ms ****,
I/jxcore-log( 6737): 
I/jxcore-log( 6737): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6737): 
,E/cutils-trace( 7031): Error opening trace file: Permission denied (13),
,D/CustomizationManager( 7031): ====startRecUseTime====,
D/htc.customization.log.level( 7031):  is 
W/CustomizationLogLevel( 7031): Level value is invalid, use default level 2
,D/CustomizationManager( 7031):  Read ACC file spent 0.063 (s),
,D/CIDMapFileReader( 7031): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 7031): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7031): Parsing tag item name = HTC__Y13
,D/CIDMapFileReader( 7031): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7031): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7031): Parsing tag item name = HTC__002,
D/CIDMapFileReader( 7031): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 7031): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 7031): Parsing tag category name = system,
,I/CustomizationCIDLoader( 7031): Parsing tag category name = application
,I/CustomizationCIDLoader( 7031): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 7031): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7031): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 7031): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7031): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 7031): add string-array item, value = 42507
I/CustomizationCIDLoader( 7031): add string-array item, value = 21902
I/CustomizationCIDLoader( 7031): add string-array item, value = 26006:26001.26002.26003
,I/CustomizationCIDLoader( 7031): add string-array item, value = 23420
I/CustomizationCIDLoader( 7031): add string-array item, value = 22299
I/CustomizationCIDLoader( 7031): add string-array item, value = 24002
I/CustomizationCIDLoader( 7031): add string-array item, value = 23210
I/CustomizationCIDLoader( 7031): add string-array item, value = 23205
,I/CustomizationCIDLoader( 7031): add string-array item, value = 23806
I/CustomizationCIDLoader( 7031): add string-array item, value = 23430
I/CustomizationCIDLoader( 7031): add string-array item, value = 23408
I/CustomizationCIDLoader( 7031): add string-array item, value = 27205
I/CustomizationCIDLoader( 7031): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7031): add string-array item, value = 21902:C:1:0
,I/CustomizationCIDLoader( 7031): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7031): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7031): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7031): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7031): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7031): add string-array item, value = 23205:D:0:0
,I/CustomizationCIDLoader( 7031): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7031): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7031): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7031): add string-array item, value = 27205:C:1:0
,D/CustomizationManager( 7031):  Read CID file spent 0.126 (s)
D/CustomizationManager( 7031):  All configurations done spent 0.126 (s)
,D/PackageManager(  958): deletePackageAsUser: pkg=com.test.thalitest, pid=7031, uid=2000 userid=0
,D/Process (  958): killProcessQuiet, pid=6737,
I/ActivityManager(  958): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  958): Killing 6737:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 ,
,W/PackageSettings(  958): Skipping PackageSetting{26c7a17a com.example.hello/10374} due to missing metadata
,I/ActivityManager(  958): Recipient 6737,
E/InputEventReceiver( 1408): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{13cb1956 uid 10366 pid 6737} (c)'
I/WindowState(  958): WIN DEATH: Window{35e99e8a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  958): Client connection lost with reason: 4
,I/ActivityManager(  958):   Force finishing activity ActivityRecord{375567f7 u0 com.test.thalitest/.MainActivity t8},
,W/ActivityManager(  958): Spurious death for ProcessRecord{3ef8f9b8 6737:com.test.thalitest/u0a366}, curProc for 6737: null
,I/ActivityManager(  958): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
,D/AccTypeManager( 1770): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/DotMatrix( 1331): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1331): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1331): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/SystemReader(  958): Cannot find grip_rejection_width, use default value instead
D/PMS     (  958): acquireWL(24a332f6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1860 10024 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 1770): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1860): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  958): releaseWL(24a332f6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PhoneApp( 1575): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/VoicemailCleanupService( 1724): Cleaning up data for package: com.test.thalitest
I/[PluginManager]RegisterService( 1546): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/AccTypeManager( 1770): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/art     ( 1633): Explicit concurrent mark sweep GC freed 3393(180KB) AllocSpace objects, 4(268KB) LOS objects, 34% free, 29MB/45MB, paused 888us total 103.038ms
,D/Prism.PackageStateRece_( 1633): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1633): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1633): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/[PluginManager]RegisterService( 1546): handle notify Blinkfeed plugin client changed
,I/Launcher( 1633): Deferring update until onResume
D/Launcher( 1633): waitUntilResume // bindAppsRemoved,
E/ExternalAccountType( 1770): Unsupported attribute readOnly
,I/ActivityManager(  958): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/InputMethodManagerService(  958): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
,W/ResourcesManager(  958): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/art     (  958): Explicit concurrent mark sweep GC freed 33507(2MB) AllocSpace objects, 5(240KB) LOS objects, 33% free, 16MB/25MB, paused 2.301ms total 238.908ms
,I/art     (  958): WaitForGcToComplete blocked for 237.041ms for cause Explicit
,D/StatusBarManagerService(  958): setSystemUiVisibility(0x700),
,D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
D/StatusBarManagerService(  958): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
,D/FindExtension( 1633): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/ContextImpl( 7051): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,I/ThreadedRenderer( 1633): Defer allocateBuffers to drawing time
,W/InputMethodManagerService(  958): Got RemoteException sending setActive(false) notification to pid 6737 uid 10366,
D/StatusBarManagerService(  958): swetImeWindowStatus vis=0 backDisposition=0
,I/ActivityManager(  958): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7076 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=6610
I/ActivityManager(  958): Killing 6610:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  958): Unable to load service info ResolveInfo{1eb7e9c7 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  958): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  958): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  958): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  958): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/PackageManager(  958): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  958): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  958): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  958): Explicit concurrent mark sweep GC freed 7907(517KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.726ms total 175.922ms
,D/JobSchedulerService(  958): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  958): Recipient 6610
,D/WifiService(  958): Client connection lost with reason: 4
,I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
D/TaskPersister(  958): removeObsoleteFile: deleting file=8_task.xml
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7076, uid=10072, userID:0,
,W/global  ( 7076): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7076): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 7076): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7076): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 7076): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  958): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7116 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7076): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7076): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SQLiteDatabase( 7076): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 7076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 7076): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7076): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7076): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7076): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 7076): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 7076): Process: com.android.vending, PID: 7076
E/AndroidRuntime( 7076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7076): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 7076): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 7076): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 7076): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 7076): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,E/AndroidRuntime( 7076): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7076): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  958): App crashed! Process: com.android.vending
,E/SQLiteDatabase( 7076): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.,
E/SQLiteDatabase( 7076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 7076): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7076): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7076): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7076): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7076): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7076): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 7076): killProcess, pid=7076
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  958): 	... 5 more,
E/AndroidRuntime_2_crash( 7076): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 7076): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 7076): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 7076): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 7076): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 7076): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 7076): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 7076): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 7076): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 7076): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 7076): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 7076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 7076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 7076): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 7076): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 7076): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 7076): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 7076): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 7076): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 7076): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 7076): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 7076): 	... 4 more
W/ResourcesManager( 7116): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7116): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SQLiteDatabase( 7076): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7076): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 7076): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 7076): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7076): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7076): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7076): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/SQLiteDatabase( 7076): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7076): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 7076): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
,I/MultiDex( 7116): VM with version 2.1.0 has multidex support,
I/MultiDex( 7116): install
,I/MultiDex( 7116): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7116): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 7116): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 7116): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@246adefc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7116): Installed default security provider GmsCore_OpenSSL
,E/lowmemorykiller(  383): Error writing /proc/7076/oom_score_adj; errno=22
I/ActivityManager(  958): Killing 6667:com.htc.calendar/u0a10 (adj 15): empty #17
,E/JavaBinder(  958): !!! FAILED BINDER TRANSACTION !!!
D/Process (  958): killProcessQuiet, pid=6667
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  958): Recipient 7076
,I/ActivityManager(  958): Recipient 6667,
,I/ActivityManager(  958): Process com.android.vending (pid 7076) has died
,E/SQLiteLog( 1845): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1845): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x558fa5f9d0
W/NativeLibraryUtils( 7116): Failed to open lock file
W/NativeLibraryUtils( 7116): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7116): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7116): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7116): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7116): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7116): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7116): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7116): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7116): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7116): 	... 3 more
,E/AndroidRuntime( 1845): FATAL EXCEPTION: main
E/AndroidRuntime( 1845): Process: com.google.process.gapps, PID: 1845
E/AndroidRuntime( 1845): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1845): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1845): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1845): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1845): 	,at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1845): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1845): 	at java.lang.reflect.Method.invoke(Native Method)
,E/AndroidRuntime( 1845): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1845): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1845): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1845): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1845): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1845): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1845): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1845): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1845): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1845): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1845): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1845): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1845): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1845): 	... 9 more
E/ActivityManager(  958): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
,E/DropBoxManagerService(  958): 	... 5 more
D/Process ( 1845): killProcess, pid=1845
D/Process ( 1845): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/ActivityManager(  958): Recipient 1845,
I/ActivityThread( 7116): Removing dead content provider:android.content.ContentProviderProxy@214d23da
,I/ActivityManager(  958): Process com.google.process.gapps (pid 1845) has died
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 30999ms
,I/ActivityManager(  958): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=7149 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 7149): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7149): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7149): VM with version 2.1.0 has multidex support
I/MultiDex( 7149): install
I/MultiDex( 7149): VM has multidex support, MultiDex support library is disabled.
,I/GservicesProvider( 7149): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7149): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7149): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7149): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7149): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7149): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7149): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7149): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7149): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7149): ,	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7149): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7149): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7149): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7149): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7149): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7149): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7149): 	,at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7149): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7149): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7149): 	,at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7149): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7149): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7149): FATAL EXCEPTION: main
E/AndroidRuntime( 7149): Process: com.google.process.gapps, PID: 7149
E/AndroidRuntime( 7149): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7149): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7149): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7149): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7149): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7149): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7149): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7149): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7149): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7149): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7149): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7149): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7149): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7149): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7149): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7149): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7149): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7149): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7149): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7149): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7149): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7149): 	... 11 more
E/ActivityManager(  958): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.op,en(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  958): 	... 5 more
D/Process ( 7149): killProcess, pid=7149
D/Process ( 7149): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/Prism.ItemManager( 1633): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1633): loadItems() com.htc.launcher.pageview.WidgetManager@1aab0a09 +
I/Prism.WidgetManager( 1633): onLoadItems() +
,W/ResourcesManager( 1633): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  958): Recipient 7149,
I/ActivityManager(  958): Process com.google.process.gapps (pid 7149) has died
W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{3bf62a55 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
,W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{2318c156 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{1fb33707 u0 com.google.android.gms/.gcm.GcmService}
W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{10d6a6c6 u0 com.google.android.gms/.gcm.http.GoogleHttpService}
,I/ActivityManager(  958): Start proc com.google.process.gapps for restart com.google.process.gapps: pid=7171 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 7171): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7171): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7171): VM with version 2.1.0 has multidex support
I/MultiDex( 7171): install
I/MultiDex( 7171): VM has multidex support, MultiDex support library is disabled.
,D/PMS     (  958): acquireWL(f500338): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 958 1000 WorkSource{1000},
V/AlarmManager(  958): sending alarm PendingIntent{2f677aa3: PendingIntentRecord{337f11a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=233916, Int=0
,I/ActivityManager(  958): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7192 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
V/AlarmManager(  958): sending alarm PendingIntent{1b5c9f11: PendingIntentRecord{370d1876 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452774078978, Int=0
,D/PMS     (  958): releaseWL(f500338): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
I/GservicesProvider( 7171): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7171): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7171): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7171): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7171): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7171): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7171): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7171): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7171): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7171): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7171): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7171): ,	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7171): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7171): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7171): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7171): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7171): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/AndroidRuntime( 7171): FATAL EXCEPTION: main
E/AndroidRuntime( 7171): Process: com.google.process.gapps, PID: 7171
E/AndroidRuntime( 7171): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7171): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7171): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7171): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7171): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7171): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7171): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7171): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7171): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7171): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7171): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7171): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7171): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7171): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7171): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7171): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7171): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7171): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7171): 	... 11 more
W/ActivityManager(  958): Process com.google.android.gms has crashed too many times: killing!
E/ActivityManager(  958): App crashed! Process: com.google.process.gapps
I/ActivityManager(  958): Killing 7171:com.google.process.gapps/u0a24 (adj 0): crash
D/Process (  958): killProcessQuiet, pid=7171
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  958): 	... 5 more
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12134 
,W/ResourcesManager( 1633): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,

```
