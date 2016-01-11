#### Test 549702617e2936d_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6621): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6621): ====startRecUseTime====
D/htc.customization.log.level( 6621):  is 
W/CustomizationLogLevel( 6621): Level value is invalid, use default level 2
D/CustomizationManager( 6621):  Read ACC file spent 0.048 (s)
D/CIDMapFileReader( 6621): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6621): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6621): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6621): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6621): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6621): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6621): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6621): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6621): Parsing tag category name = system
I/CustomizationCIDLoader( 6621): Parsing tag category name = application
I/CustomizationCIDLoader( 6621): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6621): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6621): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6621): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6621): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6621): add string-array item, value = 42507
I/CustomizationCIDLoader( 6621): add string-array item, value = 21902
I/CustomizationCIDLoader( 6621): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6621): add string-array item, value = 23420
I/CustomizationCIDLoader( 6621): add string-array item, value = 22299
I/CustomizationCIDLoader( 6621): add string-array item, value = 24002
I/CustomizationCIDLoader( 6621): add string-array item, value = 23210
I/CustomizationCIDLoader( 6621): add string-array item, value = 23205
I/CustomizationCIDLoader( 6621): add string-array item, value = 23806
I/CustomizationCIDLoader( 6621): add string-array item, value = 23430
I/CustomizationCIDLoader( 6621): add string-array item, value = 23408
I/CustomizationCIDLoader( 6621): add string-array item, value = 27205
I/CustomizationCIDLoader( 6621): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6621): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6621):  Read CID file spent 0.102 (s)
D/CustomizationManager( 6621):  All configurations done spent 0.102 (s)
--------- beginning of system
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6621 on display 0
D/PMS     (  967): acquireHCC(17c82cee): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 967 1000 null
D/PMS     (  967): acquireHCC(bffd58f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 967 1000 null
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6639 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1307): [EventService]  onDisplayChanged: 0
V/ActivityManager(  967): Display changed displayId=0
D/DotMatrix( 1307): [EventService] mbHDMIConnect: false, mCoverOn:false
D/Process (  967): killProcessQuiet, pid=5581
I/ActivityManager(  967): Killing 5581:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/TrimMemoryManager( 1486): [trimMemory] 20
I/ActivityManager(  967): Recipient 5581
,I/WebViewFactory( 6639): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6639): Time to load native libraries: 9 ms (timestamps 488-497)
,I/LibraryLoader( 6639): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6639): Binding Chromium to main looper Looper (main, tid 1) {10a99e43}
,I/LibraryLoader( 6639): Expected native library version number "",actual native library version number ""
,I/chromium( 6639): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6639): Initializing chromium process, singleProcess=true
,W/art     ( 6639): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6639): ApplicationContext is null in ApplicationStatus
,W/chromium( 6639): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6639): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6639): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6639): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6639): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6639): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6639): Local Branch: 
I/Adreno-EGL( 6639): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6639): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6639):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  967): Message: MESSAGE_REGISTER_ADAPTER,
W/System.err(  967): java.lang.Throwable: stack dump
W/System.err(  967): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  967): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  967): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3781e6b4:true
,D/BluetoothAdapter( 6639): 381541279: getState(). Returning 12
,I/art     ( 1932): Explicit concurrent mark sweep GC freed 12573(671KB) AllocSpace objects, 7(588KB) LOS objects, 49% free, 4MB/8MB, paused 579us total 36.726ms
,W/art     ( 6639): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6639): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6639): CordovaWebView is running on device made by: HTC
,W/art     ( 6639): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6639): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  967): Activity pause timeout for ActivityRecord{a99b01c u0 com.test.thalitest/.MainActivity t8}
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6639): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  967): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
D/StatusBarManagerService(  967): setSystemUiVisibility(0x0)
,D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
,D/FindExtension( 6639): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6639): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2c3e5125, mServedView=org.apache.cordova.engine.SystemWebView{3ae002fa VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@19a5a0ab
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
I/InputMethodManagerService(  967): Disable input method client, pid=1486
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6639): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +685ms (total +731ms)
,W/BindingManager( 6639): Cannot call determinedVisibility() - never saw a connection for the pid: 6639
,D/JsMessageQueue( 6639): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6639): JniHelper::setJavaVM(0xaae458f8), pthread_self() = -1407830600
D/JX-Cordova( 6639): jxcore cordova android initializing
,W/jxcore-log( 6639): Initializing JXcore engine
W/jxcore-log( 6639): JXcore engine is ready
,W/jxcore-log( 6639): Starting JXcore engine,
,W/jxcore-log( 6639): Platform android
W/jxcore-log( 6639): 
W/jxcore-log( 6639): Process ARCH arm
W/jxcore-log( 6639): 
,D/PMS     (  967): releaseHCC(17c82cee): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  967): releaseHCC(bffd58f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6639): JXcore Cordova bridge is ready!,
I/jxcore-log( 6639): 
W/jxcore-log( 6639): JXcore engine is started
,I/Choreographer( 6639): Skipped 96 frames!  The application may be doing too much work on its main thread.,
I/chromium( 6639): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6639): Toggling radios to true,
I/jxcore-log( 6639): 
,D/BluetoothAdapter( 6639): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  967): ADD_CLIENT: 8
,D/WifiService(  967): New client listening to asynchronous messages
D/WifiManager( 6639): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  967): MONITOR_LOG
D/WifiService(  967): setWifiEnabled: true pid=6639, uid=10366
W/Settings:Agent(  967): name: wifi_on
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  967): value: 2
I/WifiService(  967): isSprintWifiRestricted(): false
W/Settings:Agent(  967): >> traceCallingStack()
I/WifiService(  967): isMdmWifiRestricted(): false
W/Settings:Agent(  967): Process.myPid(): 967
,W/Settings:Agent(  967): Process.myTid(): 1398
W/Settings:Agent(  967): Process.myUid(): 1000
W/Settings:Agent(  967): 
W/Settings:Agent(  967): 
,W/System.err(  967): java.lang.Throwable: stack dump,
,W/System.err(  967): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  967): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  967): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  967): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  967): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  967): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  967): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  967): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  967): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  967): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  967): 
W/Settings:Agent(  967): << traceCallingStack(): 15(ms)
D/WifiController(  967): handleMessage: E msg.what=155656
D/WifiManager( 6639): disconnect: Base Package Name=com.test.thalitest, uid=10366
,D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
E/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiController(  967): handleMessage: X
E/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiManager( 6639): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  967):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1347): wlan0: Cancelling scan request
D/wpa_supplicant( 1347): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1347): TDLS: Tear down peers
D/wpa_supplicant( 1347): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6639): Radios toggled
I/jxcore-log( 6639): 
,I/jxcore-log( 6639): My device name is: HTC-HTC One M8s,
I/jxcore-log( 6639): 
,D/wpa_supplicant( 1347): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1347): wlan0: Deauthentication notification
D/wpa_supplicant( 1347): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1347): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1347): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1347): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1347): enter disconnect check
I/wpa_supplicant( 1347): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1347): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1347): wlan0: Ignore connection failure indication since interface has been put into disconnected state
E/WifiMonitor(  967): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  967): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  967): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  967): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  967): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  967): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  967): sendTetherStateChangedBroadcast 0, 0, 0
D/PMS     (  967): acquireWL(16676c7c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
,D/wpa_supplicant( 1347): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1347): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1347): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1347): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/UsbDeviceManager(  967): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/wpa_supplicant( 1347): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x557381cf88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1347):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347): wlan0: State: COMPLETED -> DISCONNECTED
D/UsbnetService(  967): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/wpa_supplicant( 1347): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
,D/wpa_supplicant( 1347): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  967): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1347): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1347): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1347): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1347): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1347): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1347): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1347): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1347): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1347): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1347): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1347): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1347): EAPOL: External notification - portValid=0
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1347): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1347): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1347): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1347): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1347): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: ConnectedState
E/WifiStateMachine(  967): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  967): release()
E/WifiStateMachine(  967): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  967): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  967): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
,E/WifiStateMachine(  967): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  967): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1347): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1347): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1347): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/TetherSettings( 5810): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5810): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5810): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5810): Cust_ConnectToPC   : spcsc>false
D/        ( 5810): Cust_ConnectToPC   : IPT>true
D/        ( 5810): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5810): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5810): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5810): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1347): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1347): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1347): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1347): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1347): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1347): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1347): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
,D/WifiDataStallTracker(  967): setDhcpActive: false
,E/Netd    (  395): ifc_reset_connections failed on iface wlan0 for address 192.168.1.130/24 (Unknown error -1)
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
W/ContextImpl( 5810): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,E/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/SmartNS_Utility( 5810): setISNotification
E/WifiStateMachine(  967): NetworkAgent != null
,D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/SmartNS_Utility( 5810): usb_cable_connect = 1
D/SmartNS_Utility( 5810): usb_denied = 0
,I/SmartNS_PSService( 5810): usb notificaiton:true
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  967): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1347): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1347): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1347): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WifiDataStallTracker(  967): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  967): stopDataStallAlarm 
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 14
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1347): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1347): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1347): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1347): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  967): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  967):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  967): Start Disconnecting Watchdog 1
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131146
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  967): processMsg: DisconnectingState
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1347): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1347): Fast associate: Old scan results
D/wpa_supplicant( 1347): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1347): wpa_supplicant_scan enter
D/wpa_supplicant( 1347): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1347): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1347): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1347): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1347): WPS:  * Request Type
D/wpa_supplicant( 1347): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1347): WPS:  * UUID-E
D/wpa_supplicant( 1347): WPS:  * Primary Device Type
D/wpa_supplicant( 1347): WPS:  * RF Bands (3)
,D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1347): WPS:  * Association State
D/PMS     (  967): releaseWL(16676c7c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1347): WPS:  * Configuration Error (0)
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1347): WPS:  * Device Password ID (0)
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1347): WPS:  * Manufacturer
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1347): WPS:  * Model Name
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1347): WPS:  * Model Number
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
D/wpa_supplicant( 1347): WPS:  * Device Name
V/NetworkPolicy(  967): updateNotificationsLocked()
D/wpa_supplicant( 1347): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1347): P2P: * P2P IE header
D/wpa_supplicant( 1347): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1347): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1347): wlan0: Add radio work 'scan'@0x55737ff860
D/wpa_supplicant( 1347): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1347): wlan0: Starting radio work 'scan'@0x55737ff860 after 0.000052 second wait
D/wpa_supplicant( 1347): wlan0: nl80211: scan request
D/wpa_supplicant( 1347): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1347): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1347): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1347): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1347): wlan0: Own scan request started a scan in 0.000116 seconds
I/wpa_supplicant( 1347): wlan0: CTRL-EVENT-SCAN-STARTED 
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  967): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  967): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131101
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967): processMsg: DisconnectingState
E/WifiStateMachine(  967):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  967): Default got CMD_TETHER_STATE_CHANGE
I/ActionCombine( 5810): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147460
E/WifiStateMachine(  967): processMsg: DisconnectingState
E/WifiStateMachine(  967):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132875
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132876
E/WifiStateMachine(  967): ConnectModeState: Network connection lost 
E/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  967): DisconnectedState call setCountryCode()
E/WifiStateMachine(  967):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1347): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1347): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1347): wlan0: Cancelling scan request
D/SmartNS_Utility( 5810): usb_cable_connect = 1
D/SmartNS_Utility( 5810): usb_denied = 0
I/SmartNS_PSService( 5810): usb notificaiton:true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/wpa_supplicant( 1347): wlan0: nl80211: sched_scan request
D/SmartNS_NSReceiver( 5810): Tethered state change:false isNSOpening:false
I/RemoteViews( 1219): reapply : com.android.settings 1 36
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1219): reapply : com.android.settings 1 36
D/wpa_supplicant( 1347): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1347): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1347): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1347): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1347): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1347): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1347): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1347): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1347): wlan0: Scan completed in 0.046229 seconds
D/wpa_supplicant( 1347): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1347): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
E/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 1347): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1347): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1347): wlan0: New scan results available (own=1 ext=0)
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/wpa_supplicant( 1347): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1347): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1347): wlan0: Radio work 'scan'@0x55737ff860 done in 0.047276 seconds
D/wpa_supplicant( 1347): wlan0: Selecting BSS from priority group 477
D/wpa_supplicant( 1347): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-61 wps
D/wpa_supplicant( 1347): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1347): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1347): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1347):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1347): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1347): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x557381ec00  current_ssid=0x0
D/wpa_supplicant( 1347): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1347): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1347): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1347): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1347): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1347): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1347): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1347): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1347): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1347): wlan0: Add radio work 'connect'@0x55737ff860
D/wpa_supplicant( 1347): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=132918  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/wpa_supplicant( 1347): wlan0: Starting radio work 'connect'@0x55737ff860 after 0.000066 second wait
E/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/wpa_supplicant( 1347): check if in concurrent case
E/WifiStateMachine(  967): processMsg: ConnectModeState
I/wpa_supplicant( 1347): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  967): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=132919  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=45 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  967): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=46 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  967): handleMessage: X
D/WifiNetworkAgent(  967): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=132920  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1347): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1347): wlan0: Cancelling sched scan
E/WifiStateMachine(  967): NetworkAgent == null
I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1347): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1347): wlan0: Cancelling scan request
D/wpa_supplicant( 1347): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1347): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1347): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1347): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1347): wlan0: Automatic auth_alg selection: 0x1
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/wpa_supplicant( 1347): RSN: PMKSA cache search - network_ctx=0x557381ec00 try_opportunistic=0
D/wpa_supplicant( 1347): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1347): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1347): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1347): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1347): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1347): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1347): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1347): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1347): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1347): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1347): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1347): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1347): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1347): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1347): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1347): nl80211: Set mode ifindex 29 iftype 2 (STATION)
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=132923  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/wpa_supplicant( 1347): nl80211: Unsubscribe mgmt frames handle 0x888888ddfb096989 (mode change)
E/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 1347): nl80211: Subscribe to mgmt frames with non-AP handle 0x557381e100
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=0104
E/WifiStateMachine(  967): handleMessage: E msg.what=147461
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=040a
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=040b
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=040c
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=040d
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=090a
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=090b
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=090c
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=090d
E/WifiStateMachine(  967):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:216 bcn=0
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=0409506f9a09
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=7f506f9a09
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=0801
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=040e
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=06
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=0a07
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=0a11
D/wpa_supplicant( 1347): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x557381e100 match=0a1a
D/wpa_supplicant( 1347): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1347):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347):   * freq=2412
D/wpa_supplicant( 1347):   * freq_hint=2412
D/wpa_supplicant( 1347):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1347):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1347):   * WPA Versions 0x2
D/wpa_supplicant( 1347):   * pairwise=0xfac04
D/wpa_supplicant( 1347):   * group=0xfac04
D/wpa_supplicant( 1347):   * akm=0xfac02
E/WifiStateMachine(  967):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:216 bcn=0
D/wpa_supplicant( 1347):   * Auth Type 0
D/wpa_supplicant( 1347): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x557381ec3a
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:216 bcn=0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:216 bcn=0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1347): nl80211: Connect request send successfully
D/wpa_supplicant( 1347): wlan0: Setting authentication timeout: 10 sec 0 usec
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1347): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1347): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1347): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1347): wlan0: Control interface command 'LIST_DONGLES'
D/wpa_supplicant( 1347): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1347): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1347): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  967): [1,452,525,707,601 ms] noteScanEnd no scan source
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1347): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  967): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1aacfe3b sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  967): NG7005g c0:ff:d4:d3:aa:4a rssi=-49 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  967): NG700 c0:ff:d4:d3:aa:48 rssi=-61 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  967): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  967): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  967):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-61 freq=2412
E/WifiAutoJoinController (  967): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-86 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  967): UPC503894600 a0:c5:62:7a:49:97 rssi=-82 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  967): Gonzos 38:f8:89:11:e9:11 rssi=-84 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  967): UPC5999698 64:7c:34:12:7f:81 rssi=-86 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  967): m.m.netgear 00:26:f2:18:08:c8 rssi=-90 cap [WPA-PSK-TKIP][ESS] is not scored
E/WifiAutoJoinController (  967): ageScanResultsOut delay 40000 size 8 now 1452525707606
E/WifiAutoJoinController (  967): newSupplicantResults size=8 known=1 true
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1347): wlan0: Control interface command 'STATUS-NO_EVENTS'
D/WISPrService( 5810): >>>>>WISPrService start isConnected = true<<<<<
E/WifiAutoJoinController (  967): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  967): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  967): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  967): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  967): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  967):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131213
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_TARGET_BSSID 46 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132939
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_TARGET_BSSID 46 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132940
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_TARGET_BSSID 46 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132940
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_TARGET_BSSID 46 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132940
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=132942  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info0x
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 18
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=132946  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  967): handleMessage: X
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiService(  967): New client listening to asynchronous messages
E/WifiTrafficPoller(  967): ADD_CLIENT: 9
D/ConnectivityService(  967): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  967): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524292
D/ConnectivityService(  967): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Disconnected - quitting
D/ConnectivityService(  967): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  967): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  967): enter WifiNetworkFactory startNetwork. mIPTStart:false
I/SecurityController( 1219): onLost 100
D/usbnet  (  967): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkManagementService(  967): Removing idletimer
E/WifiStateMachine(  967): handleMessage: E msg.what=131131
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): handleMessage: X
W/WISPrService( 5810): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5810): trigger connection
D/WISPrService( 5810): continue
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
D/PMS     (  967): acquireWL(1a022d5a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 967 1000 null
D/CSLegacyTypeTracker(  967): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/WISPrService( 5810): start DataConnection
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc    ( 5810): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/libc    ( 5810): [NET] android_getaddrinfofornet-, err=8
E/ConnectivityService(  967): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/libc    ( 5810): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
V/NetworkPolicy(  967): ensureActiveMobilePolicyLocked()
D/libc    ( 5810): [NET] android_getaddrinfofornet-, pass to proxy
D/PMS     (  967): acquireWL(2a5aeb8b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
D/libc    ( 5810): [NET] android_getaddrinfo_proxy+
D/DATA_ICON( 1219): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/Tethering(  967): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  967): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/libc    ( 5810): [NET] android_getaddrinfo_proxy get netid:0
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
D/NetworkPolicy(  967): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateIfacesLocked()
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
D/DATA_ICON( 1219): dataConnected: false/false
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
V/NetworkPolicy(  967): updateNotificationsLocked()
D/libc    ( 5810): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  967): releaseWL(2a5aeb8b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateNotificationsLocked()
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false
,I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
,I/ActivityManager(  967): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6701 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/libc    ( 5810): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/libc    ( 5810): [NET] android_getaddrinfofornet-, err=8
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false
,D/WISPrService( 5810): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/wpa_supplicant( 1347): Wireless event: cmd=0x8c02 len=271
,I/wpa_supplicant( 1347): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1347): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1347): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1347): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1347): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1347): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1347): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1347): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1347): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1347): nl80211: Connect event
D/wpa_supplicant( 1347): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1347): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1347): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1347): wlan0: Association info event
D/wpa_supplicant( 1347): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1347): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1347): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1347): wlan0: freq=2412 MHz
D/wpa_supplicant( 1347): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1347): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1347): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1347): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1347): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1347): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1347): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1347): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1347): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1347): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1347): TDLS: Remove peers on association
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1347): EAPOL: External notification - portEnabled=0,
D/wpa_supplicant( 1347): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1347): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1347): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1347): EAPOL: SUPP_PAE entering state CONNECTING
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1347): EAPOL: enable timer tick
D/wpa_supplicant( 1347): EAPOL: SUPP_BE entering state IDLE
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1347): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1347): wlan0: Cancelling scan request
I/wpa_supplicant( 1347): htc_wext_set_keepalive +
I/wpa_supplicant( 1347): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1347): getPrivFuncNum +	
I/wpa_supplicant( 1347): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1347): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1347): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1347): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/wpa_supplicant( 1347): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1347): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1347): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1347): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
,D/wpa_supplicant( 1347): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1347):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1347):   key_nonce - hexdump(len=32): 18 52 ae 88 16 54 72 a4 bb f9 83 e8 5b 0e d9 4a 48 a3 ce 63 8a 91 54 9d 79 e3 90 9f 1e f4 f1 dd
D/wpa_supplicant( 1347):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1347):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1347):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1347):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1347): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
D/wpa_supplicant( 1347): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1347): RSN: msg 1/4 key data - hexdump(len=0):
,E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=49 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiMonitor(  967): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiMonitor(  967): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  967): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/HTCRequest(  967): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  967): WifiMonitor:getFreqFromEventString() 2412
D/FlexNetS( 6482): updateSvcAllowedInSettings:false
D/HTCRequest(  967): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  967): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  967): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  967): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=133043  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/PMS     (  967): acquireWL(32034103): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/UsbDeviceManager(  967): [USBNET] bCheckSuppFunc: cdc_network
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=133044  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147500
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/wpa_supplicant( 1347): WPA: Renewed SNonce - hexdump(len=32): a2 fd b3 43 0d c8 48 ad e5 57 c6 60 83 44 d0 64 25 cb 00 7d 72 c9 18 75 3d c3 b1 32 1d b1 ea fe
D/wpa_supplicant( 1347): WPA: Nonce1 - hexdump(len=32): a2 fd b3 43 0d c8 48 ad e5 57 c6 60 83 44 d0 64 25 cb 00 7d 72 c9 18 75 3d c3 b1 32 1d b1 ea fe
D/wpa_supplicant( 1347): WPA: Nonce2 - hexdump(len=32): 18 52 ae 88 16 54 72 a4 bb f9 83 e8 5b 0e d9 4a 48 a3 ce 63 8a 91 54 9d 79 e3 90 9f 1e f4 f1 dd
,D/wpa_supplicant( 1347): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1347): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1347): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiStateMachine(  967):  ConnectModeState what:147500 0 0
D/wpa_supplicant( 1347): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1347): wlan0: WPA: Sending EAPOL-Key 2/4
D/WifiStateMachine(  967): Enter handleAssociatedWithEvent
D/WifiStateMachine(  967): Associated
D/wpa_supplicant( 1347): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1347): WPA: Derived Key MIC - hexdump(len=16): 22 c9 e5 bd 4e 85 8e 6d f6 55 48 1f c7 6e d3 04
D/WifiStateMachine(  967): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): Exit handleAssociatedWithEvent
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=133045  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  967): interfaceLinkStateChanged wlan0, true
D/Tethering(  967): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=133050  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  967): handleMessage: X
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 21
V/Tethering(  967): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/FlexNetS( 6482): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1347): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1347): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1347): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1347): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1347):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1347):   key_nonce - hexdump(len=32): 18 52 ae 88 16 54 72 a4 bb f9 8,3 e8 5b 0e d9 4a 48 a3 ce 63 8a 91 54 9d 79 e3 90 9f 1e f4 f1 dd
D/wpa_supplicant( 1347):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1347):   key_rsc - hexdump(len=8): 4d 2b 00 00 00 00 00 00
D/wpa_supplicant( 1347):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1347):   key_mic - hexdump(len=16): af d6 01 82 f8 0f fa 6f eb 33 57 87 83 18 a0 70
D/wpa_supplicant( 1347): RSN: encrypted key data - hexdump(len=56): cf 38 d3 2d 99 ba f5 ef 31 b5 01 ca eb 88 e1 da 82 d2 d5 d9 ea 87 a8 17 36 7b 75 90 65 31 7c 32 ...
D/wpa_supplicant( 1347): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1347): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1347): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1347): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 6d 3b ...
D/wpa_supplicant( 1347): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1347): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1347): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1347): WPA: KCK - hexdump(len=16): [REMOVED]
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/wpa_supplicant( 1347): WPA: Derived Key MIC - hexdump(len=16): 54 7a 6b 3d 83 ea 48 f8 03 bc 2b 6f 51 50 68 5b
D/wpa_supplicant( 1347): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1347): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x557381f390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1347): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1347): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1347):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1347): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1347): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1347): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1347): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1347): WPA: RSC - hexdump(len=6): 4d 2b 00 00 00 00
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1347): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x556985de68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1347): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1347): nl80211: KEY_SEQ - hexdump(len=6): 4d 2b 00 00 00 00
D/wpa_supplicant( 1347):    broadcast key
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1347): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1347): wlan0: Cancelling authentication timeout
,E/wpa_supplicant( 1347): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1347): wlan0: Radio work 'connect'@0x55737ff860 done in 0.137787 seconds
I/wpa_supplicant( 1347): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1347): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/Tethering(  967): sendTetherStateChangedBroadcast 1, 0, 0
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=52 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine(  967): handleMessage: E msg.what=131101
E/WifiStateMachine(  967): processMsg: DisconnectedState
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=53 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  967): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine(  967):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/wpa_supplicant( 1347): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1347): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1347): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  967): Event [IFNAME=wlan0 Connect to SSID: NG700]
D/UsbnetService(  967): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=55 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  967): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1347): set send_ind_to_ndc = 0
,I/wpa_supplicant( 1347): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1347): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1347): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1347): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1347): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1347): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1347): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1347): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1347): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1347): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/WifiStateMachine(  967):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine(  967): processMsg: DriverStartedState
D/wpa_supplicant( 1347): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1347): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1347): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/WifiStateMachine(  967):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/wpa_supplicant( 1347): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiStateMachine(  967):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  967): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/Tethering(  967): interfaceLinkStateChanged wlan0, true
D/Tethering(  967): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=133061  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/PMS     (  967): releaseWL(32034103): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=133061  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147459
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133062
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133062
E/WifiStateMachine(  967): Network connection established
D/WifiStateMachine(  967): fetchFrequency(), freq = 2412
E/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/FlexNetS( 6482): updateSvcAllowedInSettings:false
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hin,t: false
E/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1347): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1347): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  967): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
E/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,V/NetworkPolicy(  967): updateNetworkEnabledLocked()
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 22
V/NetworkPolicy(  967): updateNotificationsLocked()
,D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 23
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 24
,I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  967): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  967): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  967): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  967): Got NetworkAgent Messenger
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  967): NetworkAgent connected
D/wpa_supplicant( 1347): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1347): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1347): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1347): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1347): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1347): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1347): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  967): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  967): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
E/WifiStateMachine(  967): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1347): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1347): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1347): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1347): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1347): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1347): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1347): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  967): Start Dhcp Watchdog 2
,E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=133091  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=133091  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=133092  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  967): handleMessage: X
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  967):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  967): handleMessage: E msg.what=196612
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
D/FlexNetS( 6482): updateSvcAllowedInSettings:false
E/WifiStateMachine(  967):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  967): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  967): acquireWL(3dfe2544): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 967 1000 null
D/WifiStateMachine(  967): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  967): setDhcpActive: true
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1347): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (,  967): do suspend false
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1347): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1347): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1347): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1347): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1347): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1347): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1347): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1347): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  967): noteBatchedScanstop(),
E/WifiStateMachine(  967): handleMessage: X
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f693084 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f693084 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 5810): >>>>>WISPrService start isConnected = false<<<<<
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WISPrService( 5810): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
D/TetherSettings( 5810): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5810): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5810): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5810): Cust_ConnectToPC   : spcsc>false
,D/        ( 5810): Cust_ConnectToPC   : IPT>true
D/        ( 5810): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5810): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5810): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5810): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5810): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
W/ContextImpl( 5810): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5810): setISNotification
D/SmartNS_Utility( 5810): usb_cable_connect = 1
,D/SmartNS_Utility( 5810): usb_denied = 0
I/SmartNS_PSService( 5810): usb notificaiton:true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 5810): usb_cable_connect = 1
,D/SmartNS_Utility( 5810): usb_denied = 0
I/SmartNS_PSService( 5810): usb notificaiton:true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1219): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 5810): Tethered state change:false isNSOpening:false,
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false,
,I/RemoteViews( 1219): reapply : com.android.settings 1 36
,D/MdScPhnSt( 6701): [b66.2.]  listen tmrbb8
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false
,D/FlexNetS( 6482): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6552): remove item 101 (p2d27in247) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6701): [b66.2.] summary 118:p2 ignore
,E/dhcpcd  ( 6731): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6731): version 5.5.6 starting
E/dhcpcd  ( 6731): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6731): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/ActivityManager(  967): Killing 6158:com.android.defcontainer/u0a15 (adj 15): empty #17
,I/dhcpcd  ( 6731): autoip env[11]:autoip=DISABLE
D/Process (  967): killProcessQuiet, pid=6158
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6731): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6731): wlan0: sending REQUEST (xid 0xf208427b), next in 1.83 seconds
,I/ActivityManager(  967): Recipient 6158,
,D/wpa_supplicant( 1347): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1347): EAPOL: disable timer tick
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false,
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
I/dhcpcd  ( 6731): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,I/dhcpcd  ( 6731): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6731): autoip env[11]:autoip=DISABLE
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
,E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  967): handleMessage: X
,I/dhcpcd  ( 6731): bind_interface: daemonise
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  967): releaseWL(3dfe2544): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967): handleMessage: E msg.what=196613
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER POWERMODE 0',
I/wpa_supplicant( 1347): Power_Mode_Type mode = 0
I/wpa_supplicant( 1347): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1347): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  967): setDhcpActive: false
E/WifiStateMachine(  967): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  967): WifiStateMachine DHCP successful
E/WifiStateMachine(  967): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  967): link address 192.168.1.130/24
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  967): gateway: /192.168.1.1
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1347): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1347): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1347): htc_wext_set_keepalive +
I/wpa_supplicant( 1347): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1347): getPrivFuncNum +	
I/wpa_supplicant( 1347): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1347): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1347): get_ip_address source addr = c0a80182
,I/wpa_supplicant( 1347): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1347): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  967): handleMessage: X,
E/WifiStateMachine(  967): handleMessage: E msg.what=131210
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1347): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1347): environment dirty rate=0 [7][0][0]
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72
,E/WifiConfigStore(  967): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1347): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1347): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  967): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=57 dispatchEvent: BLACKLIST CLEAR 
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -61, 3
E/WifiStateMachine(  967): NetworkAgent != null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -61, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED -1 -> 3
,E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -61, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiDataStallTracker(  967): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  967): WAN detection
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/HtcWifiWanDetect(  967): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  967): Adding iface wlan0 to network 101
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  967): transitionTo: destState=ConnectedState,
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 26
E/WifiStateMachine(  967): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  967): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5810): >>>>>WISPrService start isConnected = true<<<<<
E/ConnectivityService(  967): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  967): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiStateMachine(  967): handleMessage: X
D/ConnectivityService(  967): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  967): handleMessage: E msg.what=131131
D/ConnectivityService(  967): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): processMsg: L2ConnectedState
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine(  967): handleMessage: X
D/ConnectivityService(  967): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  967): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5810): >>>>>WISPrService start isConnected = true<<<<<
D/Nat464Xlat(  967): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  967): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967): currentScore = 0, newScore = 20
D/ConnectivityService(  967):    accepting network in place of null
D/ConnectivityService(  967): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  967): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  967): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  967): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  967): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  967): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  967): ensureActiveMobilePolicyLocked()
D/PMS     (  967): acquireWL(29789829): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
D/ConnectivityService(  967): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBand,width>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  967): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  967): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/DATA_ICON( 1219): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkPolicy(  967): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateIfacesLocked()
D/ConnectivityService(  967): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  967): updateNotificationsLocked()
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  967): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  967): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  967): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  967): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): Network NetworkAgentInfo [WIFI () - 101] was al,ready satisfying request 1. No change.
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
D/DATA_ICON( 1219): dataConnected: false/false
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:NG700 elapse:2
I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
D/PMS     (  967): releaseWL(29789829): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1219): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/DATA_ICON( 1219): dataConnected: false/false
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateNotificationsLocked()
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  967): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  967): acquireWL(3f6b77ae): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
D/GpsLocationProvider(  967): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  967): [AlarmQueuing] connectivity wifi: false
I/ConnectivityHelper( 1486): [onReceive] WIFI(1): CONNECTED
D/htcCheckinService(  967): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/ActivityManager(  967): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6764 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/art     (  414): Explicit concurrent mark sweep GC freed 8645(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 296us total 27.522ms,
,E/GpsLocationProvider(  967): No APN found to select.
,D/PMS     (  967): releaseWL(3f6b77ae): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
D/PMS     (  967): acquireWL(150ad8dc): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 967 1000 null
D/PMS     (  967): releaseWL(150ad8dc): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/art     (  414): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 141us total 22.530ms,
,D/MdScPhnSt( 6701): [5e4.1.]  listen tmrbb8
,I/art     (  414): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 134us total 16.558ms,
,D/MdScDataSum( 6701): [5e4.1.] summary 118:p1 ignore
,I/MusicStore( 6764): Database version: 120,
,D/VoldConnector(  967): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6764): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/PMS     (  967): releaseWL(1a022d5a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  967): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/VoldConnector(  967): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6764): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  967): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6764): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6764): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6764): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6764): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6764): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31963786: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
W/ActivityThread( 6764): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 6764): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6764): GMSCore installation verified
,I/ConfigStore( 6764): Config Database version: 1
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6764, uid=10159, userID:0,
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client,
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
,D/MediaRouterService(  967): Client com.google.android.music (pid 6764): Registered
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0,
D/WifiDisplayAdapter(  967):     IP Address: }
,I/MediaRouter( 6764): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6764): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6764): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6764): type=WIFI subType= reason=null isConnected=true,
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6764, uid=10159, userID:0,
,D/AutoSetting( 1575): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6364): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
,D/MobileConnectivityChangeReceiver( 6364): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1575): service - onCreate()
,I/GHttpClientFactory( 6764): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1575): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,I/GoogleURLConnFactory( 6764): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1575): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  967): request 3b67c153 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052),
D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/ChimeraCfgMgr( 4460): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4460): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6807 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6413): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6413): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6413): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6413): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6413): [NET] android_getaddrinfo_proxy+
D/libc    ( 6413): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1932): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1932): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1932): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1932): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1932): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6413): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4460): [AccountUtils] Account not ready
W/Kids    ( 4460): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4460): 	,at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4460): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4460): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4460): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4460): 	at com.google.android.gms.chimera.f.run(SourceFile:179),
W/Kids    ( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4460): 	at java.lang.Thread.run(Thread.java:818)
I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/Babel   ( 6413): connection state changed from UNKNOWN to CONNECTED
,I/art     (  967): Explicit concurrent mark sweep GC freed 54415(2MB) AllocSpace objects, 4(400KB) LOS objects, 33% free, 16MB/25MB, paused 1.977ms total 141.318ms,
,I/GAv4    ( 6807): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6807):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6807):   adb logcat -s GAv4
,D/VoldConnector(  967): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6807): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  967): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6807): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  967): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6807): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 6807): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/VoldConnector(  967): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6807): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6807): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6807): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/global  ( 6807): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6807): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6807): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6807): Time to load native libraries: 2 ms (timestamps 7086-7088),
I/LibraryLoader( 6807): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6807): Binding Chromium to main looper Looper (main, tid 1) {3a91ea67},
,I/LibraryLoader( 6807): Expected native library version number "",actual native library version number "",
I/chromium( 6807): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6807): Initializing chromium process, singleProcess=true,
,W/art     ( 6807): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6807): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6807): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6807): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6807): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6807): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6807): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6807): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6807): Local Branch: 
I/Adreno-EGL( 6807): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6807): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6807):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6807): Requires BLUETOOTH permission,
,I/NSApplication( 6807): Starting up...,
,D/Process (  967): killProcessQuiet, pid=6391
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6867 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  967): Killing 6391:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,E/libprocessgroup(  967): failed to kill 1 processes for processgroup 6391
,D/Process (  967): killProcessQuiet, pid=6319
I/ActivityManager(  967): Killing 6319:com.google.android.gms.unstable/u0a24 (adj 15): empty #18
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  967): Recipient 6391
,I/ActivityManager(  967): Recipient 6319
,D/Process (  967): killProcessQuiet, pid=5895,
I/ActivityManager(  967): Killing 5895:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/WifiStateMachine(  967): handleMessage: E msg.what=131168,
E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: L2ConnectedState
,E/WifiStateMachine(  967):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: DriverStartedState
,E/WifiStateMachine(  967):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: SupplicantStartedState,
E/WifiStateMachine(  967):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  967): handleMessage: X
,I/ActivityManager(  967): Recipient 5895,
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, err=8
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  967): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  967): [NET] android_getaddrinfo_proxy+
D/libc    (  967): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  967): [AlarmQueuing] connectivity wifi: true
D/GpsLocationProvider(  967): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  967): acquireWL(c764ce7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
,D/GpsLocationProvider(  967): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ConnectivityHelper( 1486): [onReceive] WIFI(1): CONNECTED
D/htcCheckinService(  967): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/NetworkMonitor( 6764): type=WIFI subType= reason=null isConnected=true
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  967): [NET] android_getaddrinfo_proxy-, success
,D/HtcWifiWanDetect(  967): Find DNS Address www.htc.com/104.81.130.175
,V/MusicLeanback( 6764): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  967): No APN found to select.
,D/PMS     (  967): releaseWL(c764ce7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  967): acquireWL(12d2973d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 967 1000 null
,D/PMS     (  967): releaseWL(12d2973d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MdScPhnSt( 6701): [6b2.1.]  listen tmrbb8,
D/AutoSetting( 1575): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6364): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6364): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1575): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1575): service - onStartCommand() screen is off, don't request location
,D/MdScDataSum( 6701): [6b2.1.] summary 118:p1 ignore
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4460, uid=10024, userID:0,
,D/ChimeraCfgMgr( 4460): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4460): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1932): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1932): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1932): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1932): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1932): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Kids    ( 4460): [AccountUtils] Account not ready
W/Kids    ( 4460): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4460): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4460): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4460): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4460): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4460): 	at java.lang.Thread.run(Thread.java:818)
,I/RemoteViews( 1219): reapply : com.google.android.gms 1 40
,I/jxcore-log( 6639): Test app app.js loaded,
I/jxcore-log( 6639): 
,I/chromium( 6639): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/PMS     (  967): acquireWL(45a06c4): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6764 10159 null
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6764, uid=10159, userID:0
,D/PMS     (  967): releaseWL(45a06c4): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6764): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6764): Stop autocaching.
,D/WearableService( 5149): callingUid 10024, callindPid: 5149
,E/GmsUtils( 6764): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 6764): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  967): acquireWL(284c4ac7): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024},
,V/AlarmManager(  967): sending alarm PendingIntent{42ea8f4: PendingIntentRecord{2010781d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143735, Int=0,
,D/PMS     (  967): releaseWL(284c4ac7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  967): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  967): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  967): acquireWL(2f0a2a92): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 967 1000 null
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  967): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  967): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  967): [NET] android_getaddrinfo_proxy+
,D/libc    (  967): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
,D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfo_proxy-, success
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS,
,D/GpsLocationProvider(  967): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  967): [reportHTCStatus] eventMask = 3 , status = 0,
,D/GpsLocationProvider(  967): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  967): acquireWL(3c9c5dde): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
D/GpsLocationProvider(  967):  [handleDownloadXtraData]inject done.
D/PMS     (  967): releaseWL(2f0a2a92): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  967): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  967): releaseWL(3c9c5dde): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1434): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1434): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1575): service - handleMessage() stop self
,D/AutoSetting( 1575): service - onDestroy() END
,D/AutoSetting( 1575): service - handleMessage() quit looper
,E/WifiStateMachine(  967): handleMessage: E msg.what=131165,
E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): handleMessage: X
,D/PMS     (  967): acquireWL(2ae1cbbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(2ae1cbbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  967): runPSCheck
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  967): Checking...
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  967): battery changed pluggedType: 2
,D/WifiController(  967): handleMessage: E msg.what=155652
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1434): switchBindHtcMsgCursor: null,
,D/PMS     (  967): acquireWL(22f2228c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
,V/AlarmManager(  967): sending alarm PendingIntent{3a27c452: PendingIntentRecord{a2bc323 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=145329, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{2be78dd5: PendingIntentRecord{68c79ea android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452525746589, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{bf164db: PendingIntentRecord{3ee4db78 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452525731251, Int=1800000
V/AlarmManager(  967): sending alarm PendingIntent{39203251: PendingIntentRecord{1db04ab6 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190997, Int=0
D/PMS     (  967): acquireWL(199773b7): PARTIAL_WAKE_LOCK  *backup* 0x1 967 1000 null
,W/BackupManagerService(  967): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  967): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  967): acquireWL(1483724): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4460 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(199773b7): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  967): releaseWL(22f2228c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
D/PMS     (  967): acquireWL(386e5c42): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1219): Weather sync is On,
D/PMS     (  967): acquireWL(4259453): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4460 10024 WorkSource{10024 com.google.android.gms}
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
D/PMS     (  967): releaseWL(1483724): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(256b22af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4460): Aggregate from 1452525676243 (log), 1452523931180 (data)
,D/PMS     (  967): releaseWL(386e5c42): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1932): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  967): releaseWL(256b22af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(4259453): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(1b8151c1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(1b8151c1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(193ecd66): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(193ecd66): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(2536b8a7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(3cb9b154): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(fda59f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(2536b8a7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1932): Vacuum at: now=1452525765962 tag=VacuumService,
,D/PMS     (  967): releaseWL(3cb9b154): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(3daa8ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1932): Using platform SSLCertificateSocketFactory
,D/PMS     (  967): releaseWL(3daa8ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(219d77f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1932): No account for auth token provided,
,D/PMS     (  967): releaseWL(219d77f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1932): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1932): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1932): [NET] android_getaddrinfo_proxy+
D/libc    ( 1932): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1932): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1932): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1932): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1932): No account for auth token provided,
,W/Uploader( 1932): No account for auth token provided,
,W/Uploader( 1932):  no longer exists, so no auth token.,
,W/Uploader( 1932): No account for auth token provided
,W/Uploader( 1932): No account for auth token provided,
,D/PMS     (  967): releaseWL(fda59f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): acquireWL(2409d6ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(2409d6ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): acquireWL(3e349ab5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(3e349ab5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiStateMachine(  967): handleMessage: E msg.what=131326,
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState what:131326 2 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  967): handleMessage: X
,D/PMS     (  967): acquireWL(2087354a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{3a27c452: PendingIntentRecord{a2bc323 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=205329, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{d0a6cbb: PendingIntentRecord{e3375d8 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=208711, Int=0
,D/PMS     (  967): releaseWL(2087354a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1575): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1946ba75
I/ActivityManager(  967): Killing 5845:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=5845
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  967): Recipient 5845
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  967): acquireWL(36e12d31): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
,I/BatteryService(  967): n_update end
,D/PMS     (  967): releaseWL(36e12d31): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): handleMessage: E msg.what=155652
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  967): acquireWL(1e8b5c16): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(1e8b5c16): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  967): plugged=true pluggin=true,
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbnetService(  967): onReceive BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): updateBatteryInfo
D/WifiController(  967): handleMessage: E msg.what=155652
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  967): processMsg: DeviceActiveState
D/PMS     (  967): runPSCheck
D/WifiController(  967): processMsg: StaEnabledState
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: X
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1347): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1347): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1347): wlan0: BSS: Remove id 5 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1347): wlan0: BSS: Remove id 2 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1347): wlan0: BSS: Remove id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 1347): wlan0: BSS: Remove id 7 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear' due to wpa_bss_flush_by_age
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 38:f8:89:11:e9:11]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 38:f8:89:11:e9:11
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 06:7c:34:12:7f:81]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 06:7c:34:12:7f:81
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 64:7c:34:12:7f:81]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 64:7c:34:12:7f:81
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:26:f2:18:08:c8]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:26:f2:18:08:c8,
,I/jxcore-log( 6639): TAP version 13
I/jxcore-log( 6639): 
,I/jxcore-log( 6639): # setup
I/jxcore-log( 6639): 
,I/jxcore-log( 6639): # multiplex can send data
I/jxcore-log( 6639): 
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/jxcore-log( 6639): # teardown,
I/jxcore-log( 6639): 
,I/jxcore-log( 6639): ok 1 String should be length:200,
I/jxcore-log( 6639): 
,I/jxcore-log( 6639): # setup,
I/jxcore-log( 6639): 
,I/jxcore-log( 6639): # muxServerBridge,
I/jxcore-log( 6639): 
,I/jxcore-log( 6639): # teardown,
I/jxcore-log( 6639): 
,I/jxcore-log( 6639): server bridge: new client socket,
I/jxcore-log( 6639): 
,I/jxcore-log( 6639): client bridge: new client socket,
,I/jxcore-log( 6639): 
,I/jxcore-log( 6639): client bridge: socket closed,
I/jxcore-log( 6639): 
,D/PMS     (  967): acquireWL(6691997): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{3a27c452: PendingIntentRecord{a2bc323 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=265330, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{dea6b6d: PendingIntentRecord{1cd923a2 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1452525915667, Int=0
,D/PMS     (  967): releaseWL(6691997): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  967): acquireWL(229bb833): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
,I/BatteryService(  967): n_update end
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  967): releaseWL(229bb833): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1219): closing low battery warning: level=100
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): battery changed pluggedType: 2,
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,D/HtcPowerSaver(  967): updateBatteryInfo
D/PMS     (  967): runPSCheck
D/HtcPowerSaver(  967): Checking...
,I/HtcPowerSaver(  967): >> updateStatus
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  967): acquireWL(18df27f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(18df27f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  967): updateBatteryInfo,
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: X
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  443): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1434): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1434): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1434): sku_id=118
D/ContactMessageStore( 1434): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1434): start background delete task...
,D/ContactMessageStore( 1434): size: 0 , 0,
D/ContactMessageStore( 1434): Background delete complete
,D/PMS     (  967): acquireWL(28cf5169): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(28cf5169): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): runPSCheck
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DeviceActiveState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: StaEnabledState
,D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PMS     (  967): acquireWL(2b49d7ee): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
D/UsbnetService(  967): onReceive BATTERY_CHANGED
,I/BatteryService(  967): n_update end
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): releaseWL(2b49d7ee): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): updateBatteryInfo
D/WifiController(  967): handleMessage: E msg.what=155652
D/NotificationService(  967): plugged=true pluggin=true
D/WifiController(  967): processMsg: DeviceActiveState
D/PMS     (  967): runPSCheck
D/WifiController(  967): processMsg: StaEnabledState
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: X
D/WifiController(  967): battery changed pluggedType: 2
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  967): << updateStatus
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(1e4fa48f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
,V/AlarmManager(  967): sending alarm PendingIntent{3a27c452: PendingIntentRecord{a2bc323 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=385330, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{1a6d31c: PendingIntentRecord{2c029b25 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940948, Int=0
,I/bt-btm  ( 3098): Received oneshot timer event complete
I/bt-btm  ( 3098): btm_ble_timeout
I/bt-btm  ( 3098): btm_gen_resolvable_private_addr
,D/PMS     (  967): acquireWL(2bff84fa): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3098 1002 null
,D/bt-btm  ( 3098): btm_ble_rand_enc_complete
,I/bt-btm  ( 3098): btm_gen_resolve_paddr_low
D/PMS     (  967): releaseWL(1e4fa48f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/bt-smp  ( 3098): smp_encrypt_data
W/bt-smp  ( 3098): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3098): Plain text(LSB ~ MSB) = 46 dd 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3098): Encrypted text(LSB ~ MSB) = 83 0a f3 98 d4 6a 61 6f 72 a3 47 44 5a 94 af 68 
I/bt-btm  ( 3098): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3098): Stopping oneshot timer
D/bt-btm  ( 3098): Starting oneshot timer type:103 timeout:900s
D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/PMS     (  967): releaseWL(2bff84fa): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  967): acquireWL(29abfaab): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024},
V/AlarmManager(  967): sending alarm PendingIntent{2fdc0508: PendingIntentRecord{1666c4a1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937089, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{a0aa75b: PendingIntentRecord{10e92bf8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805179, Int=0
,D/PMS     (  967): acquireWL(f30f6c6): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1932 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(f30f6c6): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  967): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6938 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  967): sending alarm PendingIntent{62d9687: PendingIntentRecord{38b069b4 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1452526522262, Int=0,
V/AlarmManager(  967): sending alarm PendingIntent{188a09dd: PendingIntentRecord{22675836 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452526542184, Int=0
,W/ContextImpl( 6513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  967): releaseWL(29abfaab): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6513): MY_DEBUG = false
,D/PowerUsageService( 6513): repeat time = 1452527442251,
,I/PowerUsageList:PowerUsageHelper( 6513): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6513): gen(), null == sipper.uidObj, userId = 0,
,E/cutils-trace( 6960): Error opening trace file: Permission denied (13)
I/dex2oat ( 6960): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6960): dex2oat: override thread count:4
,I/dex2oat ( 6960): dex2oat took 725.452ms (threads: 4),
,I/PushClient( 6938): ApplicationMonitor {1676d0b5}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6938): ApplicationMonitor {1676d0b5}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6938): ApplicationMonitor {1676d0b5}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6938): ApplicationMonitor {1676d0b5}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6938): ApplicationMonitor {1676d0b5}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6938): ApplicationMonitor {1676d0b5}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6938): ApplicationMonitor {1676d0b5}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6938): ApplicationMonitor {1676d0b5}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6938): ApplicationMonitor {1676d0b5}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6938): PnsModel {3bb24ec}: update(): Update registration caused by: alarm,
,I/PushClient( 6938): PnsConfigModel {15de9e33}: <init>(): Use dm-client for provisioning.
,W/System.err( 6938): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6938): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6938): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6938): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  967): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6967 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6967): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6967 dbg=false s=true
,I/DeviceManagement( 6967): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6967): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6967): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6967): WorkflowService: Starting workflow service
,I/DeviceManagement( 6967): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@16bddb9f] args=[Bundle[mParcelledData.dataSize=88]]
I/DeviceManagement( 6967): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6967): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6967): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6967): SessionStateController: Checking invariants...
,I/DeviceManagement( 6967): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6967): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6967): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6967): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@16bddb9f],
,I/DeviceManagement( 6967): WorkflowService: Stopping workflow service,
,D/Process (  967): killProcessQuiet, pid=6443
,I/ActivityManager(  967): Killing 6443:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6938): PnsModel {3bb24ec}: update(): The registration record has not expired yet. No need to update.,
I/ActivityManager(  967): Recipient 6443,
,I/ActivityManager(  967): Killing 6594:com.htc.calendar/u0a10 (adj 15): empty #17,
D/Process (  967): killProcessQuiet, pid=6594
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  967): Recipient 6594
,D/PMS     (  967): acquireWL(2b432f77): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{3a27c452: PendingIntentRecord{a2bc323 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=985329, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{111ba7e4: PendingIntentRecord{3446244d com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452526588762, Int=0
,D/SmartSyncUtils( 6513): isEpsOn(), nState = 0
,D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/PMS     (  967): releaseWL(2b432f77): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  967): acquireWL(17b1b02): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6513 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6513): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6513): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6513): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6513): SettingOnTime = 1452578400000, randomSettingOnTime = 1452577502000
D/SmartSyncScreenOnOffTimeReceiver( 6513): SettingOffTime = 1452556800000, randomSettingOffTime = 1452561269000
,D/SmartSyncScreenOnOffTimeReceiver( 6513): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6513): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6513): bNightModeTurnOffOnce = false
,D/PMS     (  967): releaseWL(17b1b02): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  967): acquireWL(9314c13): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024}
W/GCM     ( 1932): Heartbeat timeout, GCM connection reset -3,
V/AlarmManager(  967): sending alarm PendingIntent{18dd5e50: PendingIntentRecord{1666c4a1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1027553, Int=0
,D/PMS     (  967): releaseWL(9314c13): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/PMS     (  967): acquireWL(addb849): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,D/ConnectivityService(  967): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10024,
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  967): Validated NetworkAgentInfo [WIFI () - 101],
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Forcing reevaluation
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
D/ConnectivityService(  967): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524290
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SecurityController( 1219): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PMS     (  967): releaseWL(addb849): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(3e54e): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024}
,V/AlarmManager(  967): sending alarm PendingIntent{19da966f: PendingIntentRecord{24c20f7c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1032033, Int=0
D/PMS     (  967): acquireWL(3d409005): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): releaseWL(3e54e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1932): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1932): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1932): [NET] android_getaddrinfo_proxy+
D/libc    ( 1932): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1932): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1932): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1932): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  967): acquireWL(293d085a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1932 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1932): Connected
D/PMS     (  967): releaseWL(3d409005): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(293d085a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(37242a8b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1932): Message class com.google.f.a.a.p,
,D/PMS     (  967): releaseWL(37242a8b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  967): User[0] Flushing usage stats to disk
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  967): acquireWL(31dea768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  967): n_update end
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  967): releaseWL(31dea768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): onReceive BATTERY_CHANGED
,D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): Checking...
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652,
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): << updateStatus
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(353f2781): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(353f2781): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  967): updateBatteryInfo
,D/UsbnetService(  967): BroadcastReceiver::onReceive+,
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): runPSCheck
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): >> updateStatus
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  967): << updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  967): acquireWL(2a28e467): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
I/bt-btm  ( 3098): Received oneshot timer event complete
V/AlarmManager(  967): sending alarm PendingIntent{3a27c452: PendingIntentRecord{a2bc323 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1045330, Int=0
,I/bt-btm  ( 3098): btm_ble_timeout
V/AlarmManager(  967): sending alarm PendingIntent{37aad214: PendingIntentRecord{f35babd com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1840963, Int=0
I/bt-btm  ( 3098): btm_gen_resolvable_private_addr
D/PMS     (  967): acquireWL(3f448b2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3098 1002 null
,D/bt-btm  ( 3098): btm_ble_rand_enc_complete
I/bt-btm  ( 3098): btm_gen_resolve_paddr_low
D/bt-smp  ( 3098): smp_encrypt_data
W/bt-smp  ( 3098): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3098): Plain text(LSB ~ MSB) = 2c cd 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3098): Encrypted text(LSB ~ MSB) = 41 ba 6c 27 fe b9 6a 61 e3 f7 2f 24 81 a4 84 e4 
I/bt-btm  ( 3098): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3098): Stopping oneshot timer
D/bt-btm  ( 3098): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  967): Prepared write state in 15ms
,I/ProcessStatsService(  967): Prepared write state in 7ms
,I/ProcessStatsService(  967): Prepared write state in 8ms,
,D/PMS     (  967): releaseWL(2a28e467): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On,
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data,
,I/ProcessStatsService(  967): Pruning old procstats: /data/system/procstats/state-2016-01-11-03-09-31.bin,
,D/PMS     (  967): releaseWL(3f448b2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  967): acquireWL(8d56003): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000},
,V/AlarmManager(  967): sending alarm PendingIntent{b6cfb80: PendingIntentRecord{170845b9 android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1539300, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{a0aa75b: PendingIntentRecord{10e92bf8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1687584, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{36a9e7d0: PendingIntentRecord{25d943c9 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825117, Int=1800000
V/AlarmManager(  967): sending alarm PendingIntent{3a27c452: PendingIntentRecord{a2bc323 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1885329, Int=0,
D/HtcSystemUPManager(  967): UPAlarmListener onAlarmArrival
,V/AlarmManager(  967): sending alarm PendingIntent{39da3dfe: PendingIntentRecord{1143f95f com.htc.task broadcastIntent}}, i=com.htc.task.statistics, t=1, cnt=1, w=1452527114142, Int=0
D/HtcSystemUPManager(  967): UPAlarmListener [SYSTEM_UP_UPLOAD] cur = 1452527460007, last = 1452440713970, freq = 86400000
V/AlarmManager(  967): sending alarm PendingIntent{e664fac: PendingIntentRecord{18de8475 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1854741, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{a983c0a: PendingIntentRecord{22675836 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452527442251, Int=0
D/HtcSystemUPManager(  967): AlarmScheduler_INEXACT [onReceive] end
D/HtcSystemUPManager(  967): com.htc.upm.AlarmScheduler$SchedulerBase$1@13eb5cc4
,D/PMS     (  967): acquireWL(1ed8cc7b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
,D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/PMS     (  967): releaseWL(1ed8cc7b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateNotificationsLocked()
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,I/ActivityManager(  967): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=7003 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
,W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: abnormal_event, category: stability
D/HtcSystemUPManager(  967): HtcSystemUPHandler sendService() has been called,
,D/HtcSystemUPManager(  967): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
,I/HtcSystemUPManager(  967): HtcSystemUPDataStore Send UPLOAD message to UP service 
,W/ResourcesManager( 7003): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/HtcAppUPService( 1575): HtcUPDataProvider bulkInsert() has been called.,
,D/HtcAppUPService( 1575): HtcUPServiceStore Store Version: 1 Data version: 1 File total length: 9 bytes.  Data length: 0bytes,
,I/HtcAppUPService( 1575): HtcUPServiceStore Uploading is triggered by System...
,D/HtcAppUPService( 1575): HtcUPService onCreate(),
D/HtcAppUPService( 1575): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.SYSTEM_UP_NOTIFY cmp=com.htc.sense.hsp/.upservice.HtcUPService (has extras) }, this = com.htc.sense.hsp.upservice.HtcUPService@69eac09
,D/HtcAppUPService( 1575): PolicyStore [Init] Get cached policy bundle
,W/ContextImpl( 6513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
D/HtcSystemUPManager(  967): HtcSystemUPHandler send to UPService takes: 70 ms
,D/PMS     (  967): releaseWL(8d56003): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/HtcAppUPService( 1575): appid: tellhtc_client, category: usage_report, key: enable, value: 1, due date: -1, current time: 1452527460178, default value: null
D/HtcAppUPService( 1575): HtcUPServicePreference Upload schedule enable? false
D/HtcAppUPService( 1575): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.SYSTEM_UP_NOTIFY
,D/PowerUsageList:PowerUsageHelper( 6513): MY_DEBUG = false
,D/HtcAppUPService( 1575): ReportUploader User Profiling function had been closed by user
,I/HtcAppUPService( 1575): HtcUPServiceStore Clear data store!
D/PowerUsageService( 6513): repeat time = 1452528360183
D/HtcAppUPService( 1575): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,D/HtcAppUPService( 1575): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
D/HtcAppUPService( 1575): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@69eac09
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network],
,I/art     (  967): Explicit concurrent mark sweep GC freed 42359(2MB) AllocSpace objects, 14(1324KB) LOS objects, 33% free, 17MB/25MB, paused 2.104ms total 167.145ms
,I/GLSUser ( 1932): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1932): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1932): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1932): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1932): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 6513): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6513): gen(), null == sipper.uidObj, userId = 0,
,D/Process (  967): killProcessQuiet, pid=5810
I/ActivityManager(  967): Killing 5810:com.android.settings/1000 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5810
,D/WifiService(  967): Client connection lost with reason: 4
,D/PMS     (  967): acquireWL(c20a247): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
,I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(c20a247): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): runPSCheck
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): battery changed pluggedType: 2
,D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 7036): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7036): ====startRecUseTime====
D/htc.customization.log.level( 7036):  is 
W/CustomizationLogLevel( 7036): Level value is invalid, use default level 2
D/CustomizationManager( 7036):  Read ACC file spent 0.044 (s)
D/CIDMapFileReader( 7036): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7036): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7036): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7036): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7036): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7036): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7036): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7036): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7036): Parsing tag category name = system
I/CustomizationCIDLoader( 7036): Parsing tag category name = application
I/CustomizationCIDLoader( 7036): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7036): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7036): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7036): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7036): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7036): add string-array item, value = 42507
I/CustomizationCIDLoader( 7036): add string-array item, value = 21902
I/CustomizationCIDLoader( 7036): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7036): add string-array item, value = 23420
I/CustomizationCIDLoader( 7036): add string-array item, value = 22299
I/CustomizationCIDLoader( 7036): add string-array item, value = 24002
I/CustomizationCIDLoader( 7036): add string-array item, value = 23210
I/CustomizationCIDLoader( 7036): add string-array item, value = 23205
I/CustomizationCIDLoader( 7036): add string-array item, value = 23806
I/CustomizationCIDLoader( 7036): add string-array item, value = 23430
I/CustomizationCIDLoader( 7036): add string-array item, value = 23408
I/CustomizationCIDLoader( 7036): add string-array item, value = 27205
I/CustomizationCIDLoader( 7036): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7036): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7036):  Read CID file spent 0.093 (s)
D/CustomizationManager( 7036):  All configurations done spent 0.093 (s)
D/PackageManager(  967): deletePackageAsUser: pkg=com.test.thalitest, pid=7036, uid=2000 userid=0
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  967): killProcessQuiet, pid=6639
I/ActivityManager(  967): Killing 6639:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  967): Skipping PackageSetting{c59c3fa com.example.hello/10374} due to missing metadata
I/ActivityManager(  967): Recipient 6639
E/InputEventReceiver( 1381): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{3177476f uid 10366 pid 6639} (c)'
I/WindowState(  967): WIN DEATH: Window{5b4ed13 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  967): Client connection lost with reason: 4
D/Process (  967): killProcessQuiet, pid=5966
I/ActivityManager(  967): Killing 5966:com.google.android.apps.plus/u0a167 (adj 13): empty for 1802s
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  967): Recipient 5966
D/Process (  967): killProcessQuiet, pid=6867
I/ActivityManager(  967): Killing 6867:com.android.chrome/u0a96 (adj 13): empty for 1802s
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  967): Recipient 6867
I/ActivityManager(  967): Killing 6807:com.google.android.apps.magazines/u0a161 (adj 13): empty for 1802s
D/Process (  967): killProcessQuiet, pid=6807
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  967): Recipient 6807
D/Process (  967): killProcessQuiet, pid=6364
I/ActivityManager(  967): Killing 6364:com.google.android.setupwizard/u0a77 (adj 13): empty for 1802s
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  967): Recipient 6364
D/Process (  967): killProcessQuiet, pid=6482
I/ActivityManager(  967): Killing 6482:com.htc.bgp/u0a11 (adj 13): empty for 1803s
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  967): Recipient 6482
D/Process (  967): killProcessQuiet, pid=6701
I/ActivityManager(  967): Killing 6701:com.htc.mobiledata:remote/u0a46 (adj 15): empty for 1803s
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  967): Recipient 6701
D/Process (  967): killProcessQuiet, pid=6552
I/ActivityManager(  967): Killing 6552:com.htc.mobiledata/u0a46 (adj 15): empty for 1803s
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  967): Recipient 6552
I/ActivityManager(  967):   Force finishing activity ActivityRecord{a99b01c u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  967):   Force finishing activity ActivityRecord{a99b01c u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  967): Duplicate finish request for ActivityRecord{a99b01c u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  967): Spurious death for ProcessRecord{2540ea74 6639:com.test.thalitest/u0a366}, curProc for 6639: null
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  967): acquireWL(2dee0812): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1821 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1821): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1719): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  967): Cannot find grip_rejection_width, use default value instead
D/PMS     (  967): releaseWL(2dee0812): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1719): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1678): Cleaning up data for package: com.test.thalitest
D/PhoneApp( 1434): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1575): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/AccTypeManager( 1719): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1575): handle notify Blinkfeed plugin client changed
I/art     ( 1486): Explicit concurrent mark sweep GC freed 3693(184KB) AllocSpace objects, 4(356KB) LOS objects, 34% free, 29MB/45MB, paused 993us total 112.478ms
D/Prism.PackageStateRece_( 1486): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1486): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1486): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
E/ExternalAccountType( 1719): Unsupported attribute readOnly
I/ActivityManager(  967): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7056 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/Launcher( 1486): Deferring update until onResume
D/Launcher( 1486): waitUntilResume // bindAppsRemoved
I/art     (  967): Explicit concurrent mark sweep GC freed 19283(1479KB) AllocSpace objects, 3(316KB) LOS objects, 33% free, 16MB/25MB, paused 1.407ms total 207.139ms
I/art     (  967): WaitForGcToComplete blocked for 144.931ms for cause Explicit
W/PackageManager(  967): Unable to load service info ResolveInfo{1f8849c5 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  967): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  967): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  967): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  967): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  967): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  967): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  967): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  967): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  967): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  967): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  967): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/StatusBarManagerService(  967): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
D/StatusBarManagerService(  967): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
W/ContextImpl( 7056): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/FindExtension( 1486): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1486): Defer allocateBuffers to drawing time
I/ActivityManager(  967): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7079 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 6639 uid 10366
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
D/Process (  967): killProcessQuiet, pid=6764
I/ActivityManager(  967): Killing 6764:com.google.android.music:main/u0a159 (adj 15): empty for 1801s
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/JobSchedulerService(  967): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  967): Explicit concurrent mark sweep GC freed 5305(294KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.856ms total 185.235ms
I/ActivityManager(  967): Recipient 6764
D/MediaRouterService(  967): Client com.google.android.music (pid 6764): Died!
I/InputMethodManagerService(  967): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
D/TaskPersister(  967): removeObsoleteFile: deleting file=8_task.xml
W/ResourcesManager(  967): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7079): -onCreate()
V/Settings:HtcSettingsApplication( 7079): [7079/7079] onCreate()
D/Process (  967): killProcessQuiet, pid=5149
I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7107 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  967): Killing 5149:com.google.android.gms.wearable/u0a24 (adj 15): empty for 1801s
D/Settings:HtcWirelessFeatureFlags( 7079): id/is att sku: 118/false
E/Settings:HtcWrapHeaderInfo( 7079): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7079): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7079): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7079): isSupportMusicChannel(): false
I/ActivityManager(  967): Recipient 5149
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]support         :false
I/ActivityManager(  967): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7079): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7079): isSupportVoWifi: null
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7079): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7079): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7079): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7079): [supportHomeButton]support         :false
I/ActivityManager(  967): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7079): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7079): isSupportVoWifi: null
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7107, uid=10072, userID:0
W/global  ( 7107): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 7107): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 7107): [apache-http] Connection GC has been deprecated!
W/global  ( 7107): [apache-http] Connection GC has been deprecated!
E/RollingFileStream( 7107): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 7107): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  967): acquireWL(22c1d0ad): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024}
V/AlarmManager(  967): sending alarm PendingIntent{2ce8bfe2: PendingIntentRecord{1666c4a1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1932373, Int=0
I/ActivityManager(  967): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7148 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 7107): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7107): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 7107): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7107): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 7107): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7107): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7107): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7107): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7107): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7107): 	at java.lang.Thread.run(Thread.java:818)
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7107, uid=10072, userID:0
E/SQLiteDatabase( 7107): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 7107): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 7107): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7107): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7107): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7107): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime_2_crash( 7107): crash in the same process: libraries-thread
E/AndroidRuntime_2_crash( 7107): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 7107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 7107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 7107): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime_2_crash( 7107): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime_2_crash( 7107): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime_2_crash( 7107): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime_2_crash( 7107): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime_2_crash( 7107): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime_2_crash( 7107): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 7107): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 7107): Process: com.android.vending, PID: 7107
E/AndroidRuntime( 7107): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 7107): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 7107): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 7107): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 7107): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 7107): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 7107): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 7107): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 7107): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 7107): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7107): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime( 7107): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime( 7107): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime( 7107): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime( 7107): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime( 7107): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime( 7107): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 7107): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 7107): 	... 4 more
E/SQLiteDatabase( 7107): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7107): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 7107): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 7107): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7107): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7107): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7107): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7107): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7107): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 7107): crash in the same process: AsyncTask #3
E/AndroidRuntime_3_crash( 7107): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 7107): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 7107): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 7107): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 7107): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 7107): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 7107): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 7107): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 7107): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 7107): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 7107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 7107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 7107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 7107): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 7107): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 7107): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 7107): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 7107): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 7107): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 7107): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 7107): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 7107): 	... 4 more
E/ActivityManager(  967): App crashed! Process: com.android.vending
D/Process ( 7107): killProcess, pid=7107
E/DropBoxManagerService(  967): Can't write: system_app_crash
E/DropBoxManagerService(  967): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  967): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  967): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  967): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  967): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  967): 	... 5 more
W/ResourcesManager( 7148): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Process ( 7107): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
I/MultiDex( 7148): VM with version 2.1.0 has multidex support
I/MultiDex( 7148): install
I/MultiDex( 7148): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7148): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 7148): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7148): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36e1dd7c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7148): Installed default security provider GmsCore_OpenSSL
E/JavaBinder(  967): !!! FAILED BINDER TRANSACTION !!!
E/lowmemorykiller(  383): Error writing /proc/7107/oom_score_adj; errno=22
E/SQLiteLog( 1932): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1932): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x5587f60e20
E/AndroidRuntime( 1932): FATAL EXCEPTION: main
E/AndroidRuntime( 1932): Process: com.google.process.gapps, PID: 1932
E/AndroidRuntime( 1932): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1932): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1932): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1932): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1932): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1932): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1932): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1932): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1932): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1932): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1932): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1932): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1932): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1932): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1932): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1932): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1932): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1932): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1932): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1932): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1932): 	... 9 more
E/ActivityManager(  967): App crashed! Process: com.google.process.gapps
D/Process ( 1932): killProcess, pid=1932
D/Process ( 1932): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  967): Can't write: system_app_crash
E/DropBoxManagerService(  967): java.io.FileNotFoundException: /data/system/dropbox/drop150.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  967): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  967): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  967): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  967): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  967): 	... 5 more
W/NativeLibraryUtils( 7148): Failed to open lock file
W/NativeLibraryUtils( 7148): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7148): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7148): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7148): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7148): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7148): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7148): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7148): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7148): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7148): 	... 3 more
I/ActivityManager(  967): Recipient 7107
I/ActivityManager(  967): Process com.android.vending (pid 7107) has died
E/JavaBinder( 7148): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 7148): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 7148): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 7148): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 7148): !!! FAILED BINDER TRANSACTION !!!
I/Prism.ItemManager( 1486): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1486): loadItems() com.htc.launcher.pageview.WidgetManager@3b1c659a +
I/Prism.WidgetManager( 1486): onLoadItems() +
E/JavaBinder( 7148): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 7148): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 7148): !!! FAILED BINDER TRANSACTION !!!
W/ResourcesManager( 1486): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  967): Recipient 1932
I/ActivityManager(  967): Process com.google.process.gapps (pid 1932) has died
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 11000ms
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
I/ActivityThread( 7148): Removing dead content provider:android.content.ContentProviderProxy@2c9d86b2
I/ActivityManager(  967): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7182 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
```
