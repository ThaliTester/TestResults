#### Test 558877588826def_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Process (  957): killProcessQuiet, pid=5559
--------- beginning of system
I/ActivityManager(  957): Killing 5559:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  957): Recipient 5559
W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,E/cutils-trace( 6522): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6522): ====startRecUseTime====
D/htc.customization.log.level( 6522):  is 
W/CustomizationLogLevel( 6522): Level value is invalid, use default level 2
D/CustomizationManager( 6522):  Read ACC file spent 0.048 (s)
D/CIDMapFileReader( 6522): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6522): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6522): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6522): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6522): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6522): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6522): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6522): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6522): Parsing tag category name = system
I/CustomizationCIDLoader( 6522): Parsing tag category name = application
I/CustomizationCIDLoader( 6522): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6522): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6522): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6522): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6522): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6522): add string-array item, value = 42507
I/CustomizationCIDLoader( 6522): add string-array item, value = 21902
I/CustomizationCIDLoader( 6522): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6522): add string-array item, value = 23420
I/CustomizationCIDLoader( 6522): add string-array item, value = 22299
I/CustomizationCIDLoader( 6522): add string-array item, value = 24002
I/CustomizationCIDLoader( 6522): add string-array item, value = 23210
I/CustomizationCIDLoader( 6522): add string-array item, value = 23205
I/CustomizationCIDLoader( 6522): add string-array item, value = 23806
I/CustomizationCIDLoader( 6522): add string-array item, value = 23430
I/CustomizationCIDLoader( 6522): add string-array item, value = 23408
I/CustomizationCIDLoader( 6522): add string-array item, value = 27205
I/CustomizationCIDLoader( 6522): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6522): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6522):  Read CID file spent 0.105 (s)
D/CustomizationManager( 6522):  All configurations done spent 0.105 (s)
I/ActivityManager(  957): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6522 on display 0
D/PMS     (  957): acquireHCC(280be252): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 957 1000 null
D/PMS     (  957): acquireHCC(9708923): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 957 1000 null
W/asset   (  957): Copying FileAsset 0x556c3a2c30 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  957): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6540 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  957): Display changed displayId=0
D/DotMatrix( 1307): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1307): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6540): Copying FileAsset 0xac0f7290 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1593): [trimMemory] 20
I/WebViewFactory( 6540): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6540): Time to load native libraries: 10 ms (timestamps 249-259)
,I/LibraryLoader( 6540): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6540): Binding Chromium to main looper Looper (main, tid 1) {186c5a9e}
,I/LibraryLoader( 6540): Expected native library version number "",actual native library version number ""
,I/chromium( 6540): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6540): Initializing chromium process, singleProcess=true,
,W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6540): ApplicationContext is null in ApplicationStatus
,W/chromium( 6540): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6540): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6540): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6540): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6540): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6540): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6540): Local Branch: 
I/Adreno-EGL( 6540): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6540): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6540):                  d74aa161a12b9c6fc6332151
,W/System.err(  957): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  957): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  957): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3be69477:true
W/System.err(  957): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  957): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  957): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  957): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6540): 977240746: getState(). Returning 12,
,W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6540): onDetachedFromWindow called when already detached. Ignoring,
D/SystemWebViewEngine( 6540): CordovaWebView is running on device made by: HTC
W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  957): Activity pause timeout for ActivityRecord{2c53e20 u0 com.test.thalitest/.MainActivity t8}
W/HtcSystemUPManager(  957): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/art     (  957): Explicit concurrent mark sweep GC freed 43349(2MB) AllocSpace objects, 4(936KB) LOS objects, 33% free, 16MB/25MB, paused 1.502ms total 138.840ms,
,W/chromium( 6540): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/StatusBarManagerService(  957): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  957): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  957): hiding MENU key
D/StatusBarManagerService(  957): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  957): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  957): hiding MENU key,
,D/FindExtension( 6540): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6540): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@b475968, mServedView=org.apache.cordova.engine.SystemWebView{190ef181 VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3b85226
,I/InputMethodManagerService(  957): Disable input method client, pid=1593
D/StatusBarManagerService(  957): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6540): reportFullscreenMode on inactive InputConnection
,W/BindingManager( 6540): Cannot call determinedVisibility() - never saw a connection for the pid: 6540,
,I/ActivityManager(  957): Displayed com.test.thalitest/.MainActivity: +766ms (total +812ms),
,D/JsMessageQueue( 6540): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6540): JniHelper::setJavaVM(0xaaf8a8f8), pthread_self() = -1407643056
,D/JX-Cordova( 6540): jxcore cordova android initializing
,W/jxcore-log( 6540): Initializing JXcore engine,
,W/jxcore-log( 6540): JXcore engine is ready
,W/jxcore-log( 6540): Starting JXcore engine
,D/PMS     (  957): releaseHCC(280be252): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  957): releaseHCC(9708923): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6540): Platform android
W/jxcore-log( 6540): 
W/jxcore-log( 6540): Process ARCH arm,
W/jxcore-log( 6540): 
,I/jxcore-log( 6540): JXcore Cordova bridge is ready!
I/jxcore-log( 6540): 
W/jxcore-log( 6540): JXcore engine is started,
I/Choreographer( 6540): Skipped 99 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6540): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6540): Toggling radios to true,
I/jxcore-log( 6540): 
,D/BluetoothAdapter( 6540): enable(): BT is already enabled..!
,E/WifiTrafficPoller(  957): ADD_CLIENT: 8
,D/WifiService(  957): New client listening to asynchronous messages
D/WifiManager( 6540): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  957): setWifiEnabled: true pid=6540, uid=10366
E/WifiService(  957): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  957): isSprintWifiRestricted(): false
,W/Settings:Agent(  957): MONITOR_LOG
I/WifiService(  957): isMdmWifiRestricted(): false
W/Settings:Agent(  957): name: wifi_on
W/Settings:Agent(  957): value: 2
W/Settings:Agent(  957): >> traceCallingStack()
W/Settings:Agent(  957): Process.myPid(): 957
W/Settings:Agent(  957): Process.myTid(): 1159
W/Settings:Agent(  957): Process.myUid(): 1000
W/Settings:Agent(  957): 
W/Settings:Agent(  957): 
W/System.err(  957): java.lang.Throwable: stack dump
,W/System.err(  957): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  957): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  957): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  957): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  957): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  957): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  957): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  957): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  957): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  957): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  957): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  957): 
W/Settings:Agent(  957): << traceCallingStack(): 16(ms)
D/WifiController(  957): handleMessage: E msg.what=155656
D/WifiController(  957): processMsg: DeviceActiveState
D/WifiController(  957): processMsg: StaEnabledState
D/WifiController(  957): handleMessage: X
D/WifiManager( 6540): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  957): handleMessage: E msg.what=131145
D/WifiManager( 6540): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  957): processMsg: ConnectedState
E/WifiStateMachine(  957):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  957): processMsg: L2ConnectedState
E/WifiStateMachine(  957):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1341): wlan0: Control interface command 'DISCONNECT'
,D/wpa_supplicant( 1341): wlan0: Cancelling scan request
I/jxcore-log( 6540): Radios toggled
I/jxcore-log( 6540): 
D/wpa_supplicant( 1341): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1341): TDLS: Tear down peers
D/wpa_supplicant( 1341): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6540): My device name is: HTC-HTC One M8s
I/jxcore-log( 6540): 
,D/wpa_supplicant( 1341): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1341): wlan0: Deauthentication notification
D/wpa_supplicant( 1341): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1341): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1341): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1341): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1341): enter disconnect check
I/wpa_supplicant( 1341): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1341): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1341): wlan0: Ignore connection failure indication since interface has been put into disconnected state
E/WifiMonitor(  957): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  957): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  957): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  957): interfaceLinkStateChanged wlan0, false
D/Tethering(  957): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  957): interfaceLinkStateChanged wlan0, false
,D/Tethering(  957): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  957): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  957): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  957): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  957): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1341): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1341): wlan0: Disconnect event - remove keys,
D/WifiDisplayAdapter(  957): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  957):     Client/Owner: Client,
D/WifiDisplayAdapter(  957):     GroupId: 
D/WifiDisplayAdapter(  957):     Passphrase: 
D/WifiDisplayAdapter(  957):     SessionId: 0
D/WifiDisplayAdapter(  957):     IP Address: }
D/wpa_supplicant( 1341): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/PMS     (  957): acquireWL(3c2a4c80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 957 1000 null
D/wpa_supplicant( 1341): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/UsbDeviceManager(  957): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1341): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55b5471f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiP2pService(  957): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341):    addr=c0:ff:d4:d3:aa:48
D/WifiP2pService(  957): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1341): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1341): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1341): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1341): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1341): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1341): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1341): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1341): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1341): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1341): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1341): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1341): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1341): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1341): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1341): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1341): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1341): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1341): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1341): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  957): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  957): handleMessage: new destination call exit/enter
E/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  957): invokeExitMethods: ConnectedState
E/WifiStateMachine(  957): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  957): release()
E/WifiStateMachine(  957): PerfLock released for exiting ConnectedState,
E/WifiStateMachine(  957): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  957): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  957): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  957): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  957): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  957): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  957): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
,D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=3): [REMOVED],
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/PMS     (  957): acquireWL(2c51c2b9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1341): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1341): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1341): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/HTCRequest(  957): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbnetService(  957): BroadcastReceiver::onReceive+
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/UsbnetService(  957): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  957): BroadcastReceiver::onReceive-
,D/WifiMonitor(  957): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  957): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
V/NetworkPolicy(  957): mWifiStateReceiver: meteredHint=false,EPS mode=false
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/ConnectivityService(  957): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1341): Power_Mode_Type mode = 0
I/wpa_supplicant( 1341): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1341): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  957): setDhcpActive: false
V/NativeCrypto( 1833): Read error: ssl=0x556bbb84d0: I/O error during system call, Connection timed out
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
D/TetherSettings( 5848): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5848): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5848): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5848): Cust_ConnectToPC   : spcsc>false
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/        ( 5848): Cust_ConnectToPC   : IPT>true
D/        ( 5848): Cust_ConnectToPC   : Singel_USB>false
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  957): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  957): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  957): NetworkAgent != null
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/Settings( 5848): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  957): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  957): stopDataStallAlarm 
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  957): ENABLE_DATA_MONITOR_POLL false Token 3
V/NativeCrypto( 1833): SSL shutdown failed: ssl=0x556bbb84d0: I/O error during system call, Broken pipe
,I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  957): autoRoamSetBSSID any key="NG700"WPA_PSK
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiConfigStore(  957): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/WifiHW  (  957): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  957): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/ConnectivityService(  957): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1341): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1341): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1341): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): Forcing reevaluation
E/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  957): invokeEnterMethods: DisconnectingState
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/SmartNS_Utility( 5848): hasRemovableStorageSlot: true
E/WifiStateMachine(  957):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  957): Start Disconnecting Watchdog 1
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  957): handleMessage: X
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): Validated
E/WifiStateMachine(  957): handleMessage: E msg.what=131146
D/PMS     (  957): releaseWL(2c51c2b9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  957): processMsg: DisconnectingState
D/SmartNS_Utility( 5848): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5848): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  957):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1341): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1341): Fast associate: Old scan results
D/wpa_supplicant( 1341): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1341): wpa_supplicant_scan enter
D/wpa_supplicant( 1341): wlan0: State: DISCONNECTED -> SCANNING
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
D/wpa_supplicant( 1341): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1341): wlan0: Add radio work 'scan'@0x55b5474680
D/wpa_supplicant( 1341): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1341): wlan0: Starting radio work 'scan'@0x55b5474680 after 0.000034 second wait
D/wpa_supplicant( 1341): wlan0: nl80211: scan request
D/wpa_supplicant( 1341): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  957): handleMessage: X
D/wpa_supplicant( 1341): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1341): wlan0: nl80211: Scan trigger
E/WifiStateMachine(  957): handleMessage: E msg.what=147460
D/wpa_supplicant( 1341): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1341): wlan0: Own scan request started a scan in 0.000073 seconds
E/WifiStateMachine(  957): processMsg: DisconnectingState
I/wpa_supplicant( 1341): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  957): Wifi,Monitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  957): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  957):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132818
E/WifiStateMachine(  957): processMsg: ConnectModeState
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  957): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  957): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  957): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  957):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132818
E/WifiStateMachine(  957): ConnectModeState: Network connection lost 
E/WifiStateMachine(  957): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  957): handleMessage: new destination call exit/enter
E/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  957): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  957): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  957): DisconnectedState call setCountryCode()
E/WifiStateMachine(  957):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1341): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1341): wlan0: Cancelling scan request
D/PMS     (  957): releaseWL(3c2a4c80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  957): updateNetworkEnabledLocked()
V/NetworkPolicy(  957): updateNotificationsLocked()
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ContextImpl( 5848): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1341): wlan0: nl80211: sched_scan request
I/SmartNS_Utility( 5848): setISNotification
D/SmartNS_Utility( 5848): usb_cable_connect = 1
D/SmartNS_Utility( 5848): usb_denied = 0
I/SmartNS_PSService( 5848): usb notificaiton:true
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
I/ActionCombine( 5848): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/SmartNS_Utility( 5848): usb_cable_connect = 1
D/SmartNS_Utility( 5848): usb_denied = 0
I/SmartNS_PSService( 5848): usb notificaiton:true
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 5848): Tethered state change:false isNSOpening:false
I/RemoteViews( 1218): reapply : com.android.settings 2 36
,I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1,
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/wpa_supplicant( 1341): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec,
,D/wpa_supplicant( 1341): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1341): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1341): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1341): wlan0: nl80211: New scan results available
,D/wpa_supplicant( 1341): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1341): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1341): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1341): wlan0: Scan completed in 0.046043 seconds
E/WifiStateMachine(  957): handleMessage: X
D/wpa_supplicant( 1341): nl80211: Received scan results (1 BSSes)
E/WifiStateMachine(  957): handleMessage: E msg.what=131101
E/WifiStateMachine(  957): processMsg: DisconnectedState
I/wpa_supplicant( 1341): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
D/wpa_supplicant( 1341): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1341): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1341): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1341): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1341): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
E/WifiStateMachine(  957):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1341): wlan0: Radio work 'scan'@0x55b5474680 done in 0.046857 seconds
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1341): wlan0: Selecting BSS from priority group 489
E/WifiMonitor(  957): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1341): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58 wps
D/wpa_supplicant( 1341): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1341): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1341): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1341):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1341): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/WifiMonitor(  957): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1341): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55b5473c00  current_ssid=0x0
D/wpa_supplicant( 1341): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341): wpa_supplicant_set_is_wep_security: 0
,W/WifiMonitor(  957): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1341): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1341): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1341): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1341): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
E/WifiStateMachine(  957):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  957): processMsg: DriverStartedState
D/wpa_supplicant( 1341): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1341): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1341): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1341): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1341): wlan0: Add radio work 'connect'@0x55b5474680
D/wpa_supplicant( 1341): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1341): wlan0: Starting radio work 'connect'@0x55b5474680 after 0.000081 second wait
I/wpa_supplicant( 1341): check if in concurrent case
E/WifiStateMachine(  957):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
I/wpa_supplicant( 1341): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  957):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  957): processMsg: DefaultState
E/WifiStateMachine(  957):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  957): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  957): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=147462
E/WifiStateMachine(  957): processMsg: DisconnectedState
E/WifiStateMachine(  957):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=132865  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  957): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  957): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=132865  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=131212
E/WifiStateMachine(  957): processMsg: DisconnectedState
E/WifiStateMachine(  957):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: DriverStartedState
D/wpa_supplicant( 1341): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1341): wlan0: Cancelling sched scan
E/WifiStateMachine(  957):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
D/WifiMonitor(  957): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=42 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1341): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1341): wlan0: Cancelling scan request
D/wpa_supplicant( 1341): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1341): wpas_start_assoc_cb, 1895
E/WifiStateMachine(  957):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_suppl,icant( 1341): wpas_start_assoc_cb, 1910
E/WifiStateMachine(  957): processMsg: DefaultState
D/wpa_supplicant( 1341): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1341): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1341): RSN: PMKSA cache search - network_ctx=0x55b5473c00 try_opportunistic=0
D/wpa_supplicant( 1341): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1341): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1341): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1341): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1341): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1341): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1341): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1341): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1341): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1341): wlan0: WPA: not using MGMT group cipher
E/WifiStateMachine(  957):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1341): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1341): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1341): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1341): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  957): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/wpa_supplicant( 1341): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1341): nl80211: Set mode ifindex 29 iftype 2 (STATION)
E/WifiStateMachine(  957): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=131212
D/wpa_supplicant( 1341): nl80211: Unsubscribe mgmt frames handle 0x888888dd3dcfb989 (mode change)
E/WifiStateMachine(  957): processMsg: DisconnectedState
D/wpa_supplicant( 1341): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b5473100
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=0104
E/WifiStateMachine(  957):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=040a
E/WifiStateMachine(  957): processMsg: ConnectModeState
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=040b
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=040c
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=040d
E/WifiStateMachine(  957):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=090a
E/WifiStateMachine(  957): processMsg: DriverStartedState
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=090b
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=090c
W/ContextImpl(  957): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=090d
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=0409506f9a09
E/WifiStateMachine(  957):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=7f506f9a09
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=0801
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=040e
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=06
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=0a07
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=0a11
E/WifiStateMachine(  957):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: DefaultState
D/wpa_supplicant( 1341): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b5473100 match=0a1a
D/wpa_supplicant( 1341): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1341):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341):   * freq=2412
D/wpa_supplicant( 1341):   * freq_hint=2412
D/wpa_supplicant( 1341):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1341):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1341):   * WPA Versions 0x2
D/wpa_supplicant( 1341):   * pairwise=0xfac04
D/wpa_supplicant( 1341):   * group=0xfac04
D/wpa_supplicant( 1341):   * akm=0xfac02
D/wpa_supplicant( 1341):   * Auth Type 0
D/wpa_supplicant( 1341): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55b5473c3a
E/WifiStateMachine(  957):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1341): nl80211: Connect request send successfully
D/wpa_supplicant( 1341): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1341): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1341): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1341): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1341): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1341): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1341): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  957): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  957): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=131212
E/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  957): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange(): SSID
E/WifiStateMachine(  957):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiMonitor(  957): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  957):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: DriverStartedState
E/WifiStateMachine(  957):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
E/WifiStateMachine(  957):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: DefaultState
E/WifiStateMachine(  957):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  957): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  957): handleMessage: X
D/WifiNetworkAgent(  957): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  957): handleMessage: E msg.what=147462
E/WifiStateMachine(  957): processMsg: DisconnectedState
E/WifiStateMachine(  957):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132871  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  957): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  957): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  957): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  957): NetworkAgent == null
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/RemoteViews( 1218): reapply : com.android.settings 1 36
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132874  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=147461
E/WifiStateMachine(  957): processMsg: DisconnectedState
E/WifiStateMachine(  957):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:2282 bcn=0
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:2282 bcn=0
E/WifiStateMachine(  957): processMsg: DriverStartedState
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  957):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:2282 bcn=0
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
E/WifiStateMachine(  957):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:2282 bcn=0
D/WifiStateMachine(  957): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1341): wlan0: Control interface command 'LIST_DONGLES'
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  957): [1,452,688,714,871 ms] noteScanEnd no scan source
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1341): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  957): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@176fecf7 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  957): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  957): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  957): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  957): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  957):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  957): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-86 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  957): Gonzos 38:f8:89:11:e9:11 rssi=-87 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  957): UPC503894600 a0:c5:62:7a:49:97 rssi=-80 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  957): ageScanResultsOut delay 40000 size 5 now 1452688714875
E/WifiAutoJoinController (  957): newSupplicantResults size=5 known=1 true
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1341): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  957): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  957): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  957): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  957): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  957): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  957):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=131213
E/WifiStateMachine(  957): processMsg: DisconnectedState
E/WifiStateMachine(  957):  DisconnectedState CMD_TARGET_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132888
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_TARGET_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132888
E/WifiStateMachine(  957): processMsg: DriverStartedState
E/WifiStateMachine(  957):  DriverStartedState CMD_TARGET_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132888
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
E/WifiStateMachine(  957):  SupplicantStartedState CMD_TARGET_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132889
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=147462
E/WifiStateMachine(  957): processMsg: DisconnectedState
E/WifiStateMachine(  957):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=132889  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  957): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  957): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  957): setDetailed state send new extra info0x
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5848): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  957): NetworkAgent == null
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 18
E/WifiStateMachine(  957):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=132894  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  957): handleMessage: X
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  957): ADD_CLIENT: 9
D/WifiService(  957): New client listening to asynchronous messages
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/ConnectivityService(  957): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  957):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  957):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  957): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  957): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  957): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): Disconnected - quitting
D/ConnectivityService(  957): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  957): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  957):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  957): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  957): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/usbnet  (  957): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  957):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  957): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524292
I/SecurityController( 1218): onLost 100
D/NetworkManagementService(  957): Removing idletimer
D/PMS     (  957): acquireWL(1b9a3e5f): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 957 1000 null
E/WifiStateMachine(  957): handleMessage: E msg.what=131131
D/CSLegacyTypeTracker(  957): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
E/WifiStateMachine(  957): processMsg: DisconnectedState
D/ConnectivityService(  957): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  957):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  957): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/ConnectivityService(  957): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine(  957):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
V/NetworkPolicy(  957): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  957): handleMessage: X
E/ConnectivityService(  957): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  957): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  957): acquireWL(1c27b0ac): PARTIAL_WAKE_LOCK  NetworkStats 0x1 957 1000 null
D/Tethering(  957): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/NetworkPolicy(  957): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  957): updateNetworkEnabledLocked()
V/NetworkPolicy(  957): updateIfacesLocked()
V/NetworkPolicy(  957): updateNotificationsLocked()
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WISPrService( 5848): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5848): trigger connection
D/WISPrService( 5848): continue
D/PMS     (  957): releaseWL(1c27b0ac): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
D/NetworkManagementService(  957): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
V/NetworkPolicy(  957): updateNetworkEnabledLocked()
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
V/NetworkPolicy(  957): updateNotificationsLocked()
D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5848): start DataConnection
D/libc    ( 5848): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5848): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5848): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5848): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5848): [NET] android_getaddrinfo_proxy+
D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/libc    ( 5848): [NET] android_getaddrinfo_proxy get netid:0
D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5848): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,I/ActivityManager(  957): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6607 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency,
,D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/libc    ( 5848): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 5848): [NET] android_getaddrinfofornet-, err=8
D/wpa_supplicant( 1341): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1341): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1341): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1341): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1341): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1341): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1341): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1341): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/Tethering(  957): interfaceLinkStateChanged wlan0, false
D/Tethering(  957): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1341): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 1341): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/UsbDeviceManager(  957): [USBNET] bCheckSuppFunc: cdc_network
,D/wpa_supplicant( 1341): nl80211: Connect event
D/PMS     (  957): acquireWL(21579a57): PARTIAL_WAKE_LOCK  NetworkStats 0x1 957 1000 null
D/wpa_supplicant( 1341): nl80211: Associated on 2412 MHz
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/wpa_supplicant( 1341): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1341): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1341): wlan0: Association info event
D/wpa_supplicant( 1341): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1341): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1341): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1341): wlan0: freq=2412 MHz
D/wpa_supplicant( 1341): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1341): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/Tethering(  957): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1341): wlan0: State: ASSOCIATING -> ASSOCIATED
D/Tethering(  957): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1341): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1341): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1341): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1341): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1341): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/wpa_supplicant( 1341): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1341): wlan0: WPA: Clear old PTK
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1341): TDLS: Remove peers on association
D/wpa_supplicant( 1341): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1341): EAPOL: External notification - portValid=0
D/HTCRequest(  957): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  957): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1341): EAPOL: External notification - EAP success=0
D/Tethering(  957): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1341): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1341): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1341): EAPOL: enable timer tick
D/wpa_supplicant( 1341): EAPOL: SUPP_BE entering state IDLE
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1341): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1341): wlan0: Cancelling scan request
I/wpa_supplicant( 1341): htc_wext_set_keepalive +
I/wpa_supplicant( 1341): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1341): getPrivFuncNum +	
I/wpa_supplicant( 1341): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1341): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1341): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  957): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1341): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1341): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1341): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1341): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1341): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1341):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1341):   key_nonce - hexdump(len=32): 7a 26 ca 75 80 42 eb c7 1e 63 f3 72 4a 7c 53 8a f8 d6 9e e9 f4 f5 81 d7 ea d3 2d cf b1 01 8f a7
D/WifiMonitor(  957): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
D/wpa_supplicant( 1341):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
E/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/wpa_supplicant( 1341):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=45 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1341):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
E/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiMonitor(  957): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1341):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/WifiMonitor(  957): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1341): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/HTCRequest(  957): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1341): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/HTCRequest(  957): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1341): RSN: msg 1/4 key data - hexdump(len=0):
,D/HTCRequest(  957): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  957): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  957): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  957): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  957): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  957):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=132992  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  957): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  957): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  957): processMsg: ConnectModeState
D/Tethering(  957): interfaceLinkStateChanged wlan0, true
D/Tethering(  957): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  957): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  957):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=132993  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=147500
E/WifiStateMachine(  957): processMsg: DisconnectedState
D/wpa_supplicant( 1341): WPA: Renewed SNonce - hexdump(len=32): c9 fa 56 86 6a a4 e9 12 5c 7c 35 e8 2e f7 17 23 13 07 19 fa 41 3e 76 7f 98 ef 8e 35 49 84 3e 94
D/wpa_supplicant( 1341): WPA: Nonce1 - hexdump(len=32): c9 fa 56 86 6a a4 e9 12 5c 7c 35 e8 2e f7 17 23 13 07 19 fa 41 3e 76 7f 98 ef 8e 35 49 84 3e 94
D/wpa_supplicant( 1341): WPA: Nonce2 - hexdump(len=32): 7a 26 ca 75 80 42 eb c7 1e 63 f3 72 4a 7c 53 8a f8 d6 9e e9 f4 f5 81 d7 ea d3 2d cf b1 01 8f a7
D/wpa_supplicant( 1341): WPA: PMK - hexdump(len=32): [REMOVED]
E/WifiStateMachine(  957):  DisconnectedState what:147500 0 0
D/wpa_supplicant( 1341): WPA: PTK - hexdump(len=48): [REMOVED]
E/WifiStateMachine(  957): processMsg: ConnectModeState
D/wpa_supplicant( 1341): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/Tethering(  957): sendTetherStateChangedBroadcast 1, 0, 0
D/wpa_supplicant( 1341): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/PMS     (  957): releaseWL(21579a57): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1341): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1341): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1341): WPA: Derived Key MIC - hexdump(len=16): e4 dd 2e af b5 3f 40 73 06 c2 44 66 f0 06 84 e0
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  957): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  957):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  957): Enter handleAssociatedWithEvent
D/WifiStateMachine(  957): Associated
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/UsbnetService(  957): BroadcastReceiver::onReceive+
,D/WifiMonitor(  957): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/UsbnetService(  957): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  957): BroadcastReceiver::onReceive-
D/WifiStateMachine(  957): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  957): Exit handleAssociatedWithEvent
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=131101
E/WifiStateMachine(  957): processMsg: DisconnectedState
D/FlexNetS( 6408): updateSvcAllowedInSettings:false
E/WifiStateMachine(  957):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  957): processMsg: DriverStartedState
E/WifiStateMachine(  957):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
E/WifiStateMachine(  957):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  957): processMsg: DefaultState
E/WifiStateMachine(  957):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  957): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  957): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  957): handleMessage: X
,E/WifiStateMachine(  957): handleMessage: E msg.what=147462
E/WifiStateMachine(  957): processMsg: DisconnectedState
E/WifiStateMachine(  957):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=132997  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  957): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  957): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  957): setDetailed state send new extra info"NG700"
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1341): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
V/NetworkPolicy(  957): updateNetworkEnabledLocked()
D/wpa_supplicant( 1341): wlan0:   EAPOL-Key type=2
V/NetworkPolicy(  957): updateNotificationsLocked()
D/wpa_supplicant( 1341): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1341): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1341):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
,D/wpa_supplicant( 1341):   key_nonce - hexdump(len=32): 7a 26 ca 75 80 42 eb c7 1e 63 f3 72 4a 7c 53 8a f8 d6 9e e9 f4 f5 81 d7 ea d3 2d cf b1 01 8f a7
D/wpa_supplicant( 1341):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1341):   key_rsc - hexdump(len=8): 88 09 00 00 00 00 00 00
D/wpa_supplicant( 1341):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1341):   key_mic - hexdump(len=16): 0e 51 7c e9 4b 8e 5c 24 df 56 00 ee dd 12 de a6
D/wpa_supplicant( 1341): RSN: encrypted key data - hexdump(len=56): 77 9b 8b e3 74 4b 7a 45 b9 92 1b 7e ff d6 13 e6 32 25 5a 29 c3 bc 6f 17 c6 85 22 68 1e 8c 92 3d ...
D/wpa_supplicant( 1341): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1341): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1341): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1341): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 04 29 ...
D/wpa_supplicant( 1341): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1341): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1341): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1341): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1341): WPA: Derived Key MIC - hexdump(len=16): 37 0e 41 d1 7a 8a 58 70 5d 1b 06 ae 4c 26 e2 cb
D/wpa_supplicant( 1341): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1341): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55b5474390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1341): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1341): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1341):    addr=c0:ff:d4:d3:aa:48
D/WISPrService( 5848): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/wpa_supplicant( 1341): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1341): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1341): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1341): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1341): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1341): WPA: RSC - hexdump(len=6): 88 09 00 00 00 00
D/wpa_supplicant( 1341): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x557afd8e68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1341): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1341): nl80211: KEY_SEQ - hexdump(len=6): 88 09 00 00 00 00
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1341):    broadcast key
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  957): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  957): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1341): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1341): wlan0: Cancelling authentication timeout
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
E/wpa_supplicant( 1341): wlan0: BLACKLIST REMOVE c0:,ff:d4:d3:aa:48
D/WifiMonitor(  957): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 1341): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1341): wlan0: Radio work 'connect'@0x55b5474680 done in 0.140300 seconds
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=48 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1341): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/WifiMonitor(  957): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1341): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  957): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=49 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  957): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1341): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1341): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1341): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  957): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=51 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  957): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1341): set send_ind_to_ndc = 0
I/wpa_supplicant( 1341): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1341): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1341): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1341): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1341): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1341): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1341): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1341): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1341): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1341): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1341): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1341): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/Tethering(  957): interfaceLinkStateChanged wlan0, true
D/Tethering(  957): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1341): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/FlexNetS( 6408): updateSvcAllowedInSettings:false
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  957): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  957): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  957): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  957): NetworkAgent == null
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
,E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=133009  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=147462
E/WifiStateMachine(  957): processMsg: DisconnectedState
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 20
E/WifiStateMachine(  957):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=133011  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  957): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  957): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=133011  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=147459
E/WifiStateMachine(  957): processMsg: DisconnectedState
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  957):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133013
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133014
E/WifiStateMachine(  957): Network connection established
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 21
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  957): fetchFrequency(), freq = 2412
E/WifiStateMachine(  957): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  957): NetworkAgent == null
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  957): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  957): handleMessage: new destination call exit/enter
E/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  957): invokeExitMethods: DisconnectedState
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1341): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  957): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  957): moveTempStackToStateStack: i=1,j=4
D/WifiDisplayAdapter(  957): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  957):     Client/Owner: Client
D/WifiDisplayAdapter(  957):     GroupId: 
D/WifiDisplayAdapter(  957):     Passphrase: 
D/WifiDisplayAdapter(  957):     SessionId: 0
D/WifiDisplayAdapter(  957):     IP Address: }
E/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  957): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  957): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  957): NetworkAgent == null
E/WifiStateMachine(  957): [sendNetworkS,tateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 22
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 23
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 24
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/ConnectivityService(  957): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  957): Got NetworkAgent Messenger
E/WifiStateMachine(  957): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  957): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  957): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  957): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  957): NetworkAgent connected
W/WifiHW  (  957): QCOM Debug skip set_network part for security concern!
D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SAVE_CONFIG'
D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1341): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 1341): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1341): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  957): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  957): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  957): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  957): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  957): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  957): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1341): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1341): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1341): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1341): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1341): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1341): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1341): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  957): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  957): Start Dhcp Watchdog 2
E/WifiStateMachine(  957): handleMessage: X
,E/WifiStateMachine(  957): handleMessage: E msg.what=147462
E/WifiStateMachine(  957): processMsg: ObtainingIpState
E/WifiStateMachine(  957):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=133044  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  957): processMsg: L2ConnectedState
E/WifiStateMachine(  957):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=133044  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=133045  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  957): handleMessage: E msg.what=131212
E/WifiStateMachine(  957): processMsg: ObtainingIpState
E/WifiStateMachine(  957):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: L2ConnectedState
D/PMS     (  957): acquireWL(395fd761): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 957 1000 null
E/WifiStateMachine(  957):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: DriverStartedState
E/WifiStateMachine(  957):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiStateMachine(  957): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
E/WifiStateMachine(  957):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: DefaultState
E/WifiStateMachine(  957):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  957): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=196612
E/WifiStateMachine(  957): processMsg: ObtainingIpState
E/WifiStateMachine(  957):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  957): processMsg: L2ConnectedState
E/WifiStateMachine(  957):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiDataStallTracker(  957): setDhcpActive: true
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1341): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/FlexNetS( 6408): updateSvcAllowedInSettings:false
,E/WifiStateMachine(  957): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  957): do suspend false
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1341): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1341): INFO - Deny active power mode because already has gateway
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,D/WISPrService( 5848): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1341): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  957): Unexpected BatchedScanResults :null
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1341): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1341): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1341): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1341): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1341): wlan0: Event DRIVER_GTK_REKEY (37) received
E/WifiStateMachine(  957): noteBatchedScanstop()
E/WifiStateMachine(  957): handleMessage: X
D/WifiP2pService(  957): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c05e76f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c05e76f target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 5848): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  957): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:2
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0,
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6408): updateSvcAllowedInSettings:false
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false
,D/TetherSettings( 5848): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5848): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5848): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5848): Cust_ConnectToPC   : spcsc>false
D/        ( 5848): Cust_ConnectToPC   : IPT>true
D/        ( 5848): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5848): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5848): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5848): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5848): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
,W/ContextImpl( 5848): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5848): setISNotification
D/SmartNS_Utility( 5848): usb_cable_connect = 1
,D/SmartNS_Utility( 5848): usb_denied = 0
I/SmartNS_PSService( 5848): usb notificaiton:true
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 5848): usb_cable_connect = 1
D/MdScPhnSt( 6607): [b52.2.]  listen tmrbb8
,D/SmartNS_Utility( 5848): usb_denied = 0
I/SmartNS_PSService( 5848): usb notificaiton:true
E/WifiStateMachine(  957): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1218): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5848): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false,
,I/RemoteViews( 1218): reapply : com.android.settings 1 36
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6470): remove item 101 (p2d24in228) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6607): [b52.2.] summary 118:p2 ignore
,D/MdProvGlob( 6470): remove item 101 (p2d1in17) for 15:android.intent.action.ANY_DATA_STATE,
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false,
,D/MdProvGlob( 6470): remove item 101 (p2in21) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false
,D/FlexNetS( 6408): updateSvcAllowedInSettings:false
,E/dhcpcd  ( 6635): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6635): version 5.5.6 starting
,E/dhcpcd  ( 6635): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6635): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6635): autoip env[11]:autoip=DISABLE
,D/Process (  957): killProcessQuiet, pid=6248,
I/ActivityManager(  957): Killing 6248:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6635): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6635): wlan0: sending REQUEST (xid 0x1bb00c40), next in 1.90 seconds
,I/ActivityManager(  957): Recipient 6248,
,D/wpa_supplicant( 1341): EAPOL: startWhen --> 0
D/wpa_supplicant( 1341): EAPOL: disable timer tick,
,D/libc    (  957): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  957): handleMessage: E msg.what=131212
E/WifiStateMachine(  957): processMsg: ObtainingIpState
E/WifiStateMachine(  957):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  957): processMsg: L2ConnectedState
D/ConnectivityService(  957): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  957):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  957): processMsg: DriverStartedState
E/WifiStateMachine(  957):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
E/WifiStateMachine(  957):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  957): processMsg: DefaultState
E/WifiStateMachine(  957):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  957): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES,
E/WifiStateMachine(  957): handleMessage: X
,I/dhcpcd  ( 6635): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6635): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6635): autoip env[11]:autoip=DISABLE
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  957): handleMessage: E msg.what=131212
E/WifiStateMachine(  957): processMsg: ObtainingIpState
E/WifiStateMachine(  957):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: L2ConnectedState
E/WifiStateMachine(  957):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: DriverStartedState
,E/WifiStateMachine(  957):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  957): processMsg: SupplicantStartedState
E/WifiStateMachine(  957):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): processMsg: DefaultState
,E/WifiStateMachine(  957):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  957): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false,
E/WifiStateMachine(  957): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  957): handleMessage: X
,I/dhcpcd  ( 6635): bind_interface: daemonise,
,D/libc    (  957): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  957): handleMessage: E msg.what=196613
E/WifiStateMachine(  957): processMsg: ObtainingIpState
E/WifiStateMachine(  957):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  957): processMsg: L2ConnectedState
E/WifiStateMachine(  957):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine(  957): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiP2pService(  957): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER POWERMODE 0'
D/WifiP2pService(  957): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1341): Power_Mode_Type mode = 0
I/wpa_supplicant( 1341): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/PMS     (  957): releaseWL(395fd761): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1341): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  957): setDhcpActive: false
E/WifiStateMachine(  957): handlePostDhcpSetup release wake lock during DHCP
,E/WifiStateMachine(  957): WifiStateMachine DHCP successful
E/WifiStateMachine(  957): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  957): link address 192.168.1.130/24
,E/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  957): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  957): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  957): gateway: /192.168.1.1
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1341): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1341): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1341): htc_wext_set_keepalive +
I/wpa_supplicant( 1341): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1341): getPrivFuncNum +	
I/wpa_supplicant( 1341): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1341): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1341): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1341): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1341): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  957): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=131210
E/WifiStateMachine(  957): processMsg: ObtainingIpState
E/WifiStateMachine(  957):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  957): processMsg: L2ConnectedState
E/WifiStateMachine(  957):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1341): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1341): environment dirty rate=14 [7][1][0]
E/WifiStateMachine(  957): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  957): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  957): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
W/WifiHW  (  957): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1341): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1341): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  957): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiStateMachine(  957): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=53 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  957): NetworkAgent != null
D/WifiWatchdogStateMachine(  957): RSSI current: 3 new: -58, 3
D/ConnectivityService(  957): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  957): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  957): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  957): Adding iface wlan0 to network 101
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/HtcWifiWanDetect(  957): WAN detection
E/WifiDataStallTracker(  957): ENABLE_DATA_MONITOR_POLL true Token 4
D/HtcWifiWanDetect(  957): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiDataStallTracker(  957): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NetworkPolicy(  957): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  957): transitionTo: destState=ConnectedState
V/NetworkPolicy(  957): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  957): handleMessage: new destination call exit/enter
E/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  957): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  957): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  957): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiTrafficPoller(  957): ENABLE_TRAFFIC_STATS_POLL false Token 26
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  957): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5848): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  957): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  957): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiStateMachine(  957): handleMessage: X
E/WifiStateMachine(  957): handleMessage: E msg.what=131131
E/WifiStateMachine(  957): processMsg: ConnectedState
E/WifiStateMachine(  957):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  957): processMsg: L2ConnectedState
D/ConnectivityService(  957): Adding Route [fe80::/64 -> :: wlan0] to network 101
,E/WifiStateMachine(  957):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  957): handleMessage: X
D/ConnectivityService(  957): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  957): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  957): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5848): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/Nat464Xlat(  957): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/WIFI    (  957): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  957): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  957):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
D/ConnectivityService(  957): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  957): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  957): rematching NetworkAgentInfo [WIFI () - 101]
,D/usbnet  (  957): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  957):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  957):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  957):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/usbnet  (  957): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  957):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  957): currentScore = 0, newScore = 20
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): Connected
D/ConnectivityService(  957):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  957): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): Validated
D/CSLegacyTypeTracker(  957): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/Tethering(  957): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  957): sendGeneralBroadcast, restrictEnable=false
D/Tethering(  957): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
,D/ConnectivityService(  957): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  957): sendGeneralBroadcastDelayed, restrictEnable=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  957): Validated
D/ConnectivityService(  957): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:NG700 elapse:1
V/NetworkPolicy(  957): ensureActiveMobilePolicyLocked()
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
D/ConnectivityService(  957): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/WIFI    (  957): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/PMS     (  957): acquireWL(2d153112): PARTIAL_WAKE_LOCK  NetworkStats 0x1 957 1000 null
D/WIFI    (  957):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  957): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  957): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  957):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  957): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  957):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  957):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  957): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  957): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  957): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  957): rematching NetworkAgentInfo [WIFI () - 101]
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  957):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
D/ConnectivityService(  957):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  957): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  957): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  957):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  957):  sen,ding notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  957): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  957): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  957): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  957): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkPolicy(  957): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  957): updateNetworkEnabledLocked()
V/NetworkPolicy(  957): updateIfacesLocked()
V/NetworkPolicy(  957): updateNotificationsLocked()
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/NetworkManagementService(  957): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/ConnectivityService(  957): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  957): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  957):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  957):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  957): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  957): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  957):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  957):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  957): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  957): releaseWL(2d153112): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1218): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NetworkPolicy(  957): updateNetworkEnabledLocked()
V/NetworkPolicy(  957): updateNotificationsLocked()
,D/ConnectivityService(  957): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  957): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  957): [AlarmQueuing] connectivity wifi: false
,D/htcCheckinService(  957): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  957): acquireWL(2ce590e3): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 957 1000 null
I/ConnectivityHelper( 1593): [onReceive] WIFI(1): CONNECTED
,D/PMS     (  957): acquireWL(2760ae0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 957 1000 null
D/GpsLocationProvider(  957): [handleMessage] UPDATE_NETWORK_STATE
,D/PMS     (  957): releaseWL(2760ae0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  957): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ActivityManager(  957): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6669 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  957): No APN found to select.,
,D/PMS     (  957): releaseWL(2ce590e3): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6607): [c74.1.]  listen tmrbb8
,D/MdScDataSum( 6607): [c74.1.] summary 118:p1 ignore
,I/MusicStore( 6669): Database version: 120,
,D/VoldConnector(  957): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  957): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
D/VoldConnector(  957): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 6669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/PMS     (  957): releaseWL(1b9a3e5f): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  957): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ResourcesManager( 6669): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6669): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6669): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6669): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6669): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37401972: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6669): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6669): GMSCore installation verified
,I/ConfigStore( 6669): Config Database version: 1,
,I/PackageManager(  957):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6669, uid=10159, userID:0,
,D/WifiDisplayAdapter(  957): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  957):     Client/Owner: Client
D/WifiDisplayAdapter(  957):     GroupId: 
D/WifiDisplayAdapter(  957):     Passphrase: 
D/WifiDisplayAdapter(  957):     SessionId: 0
D/WifiDisplayAdapter(  957):     IP Address: }
,D/MediaRouterService(  957): Client com.google.android.music (pid 6669): Registered,
,D/WifiDisplayAdapter(  957): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  957):     Client/Owner: Client
D/WifiDisplayAdapter(  957):     GroupId: 
D/WifiDisplayAdapter(  957):     Passphrase: 
D/WifiDisplayAdapter(  957):     SessionId: 0
D/WifiDisplayAdapter(  957):     IP Address: }
,I/MediaRouter( 6669): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6669): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6669): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6669): type=WIFI subType= reason=null isConnected=true
,I/PackageManager(  957):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6669, uid=10159, userID:0,
,D/AutoSetting( 1654): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6346): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6346): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1654): service - onCreate()
,D/AutoSetting( 1654): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,I/GHttpClientFactory( 6669): Using our fixed implementation of GMSCore's GoogleHttpClient
D/AutoSetting( 1654): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  957): request 290271b0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052),
D/LocationManagerService(  957): provider request: passive ProviderRequest[ON interval=0]
I/GoogleURLConnFactory( 6669): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc    ( 4486): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 4486): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 4486): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
I/ActivityManager(  957): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6714 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/libc    ( 4486): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4486): [NET] android_getaddrinfo_proxy+
D/libc    ( 4486): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1833): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1833): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1833): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1833): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 4486): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4384): [AccountUtils] Account not ready
W/Kids    ( 4384): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4384): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4384): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4384): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4384): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4384): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4384): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4384): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4384): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4384): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4384): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4384): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 2 40
,D/VoldConnector(  957): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6714): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  957): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
I/GAv4    ( 6714): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6714):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6714):   adb logcat -s GAv4
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6714): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  957): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6714): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  957): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6714): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6714): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6714): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6714): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/global  ( 6714): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6714): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6714): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6714): Time to load native libraries: 1 ms (timestamps 6875-6876)
,I/LibraryLoader( 6714): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6714): Binding Chromium to main looper Looper (main, tid 1) {19c195e3}
,I/LibraryLoader( 6714): Expected native library version number "",actual native library version number "",
,I/chromium( 6714): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6714): Initializing chromium process, singleProcess=true
,W/art     ( 6714): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6714): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6714): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6714): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6714): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6714): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6714): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6714): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6714): Local Branch: 
I/Adreno-EGL( 6714): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6714): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6714):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6714): Requires BLUETOOTH permission,
,I/NSApplication( 6714): Starting up...
,I/ActivityManager(  957): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6774 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  957): killProcessQuiet, pid=6134
I/ActivityManager(  957): Killing 6134:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  407): Explicit concurrent mark sweep GC freed 8648(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 201us total 49.843ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 116us total 19.617ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 131us total 16.066ms,
,I/ActivityManager(  957): Recipient 6134
,D/Process (  957): killProcessQuiet, pid=6301,
I/ActivityManager(  957): Killing 6301:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  957): Recipient 6301,
,D/Process (  957): killProcessQuiet, pid=5872
I/ActivityManager(  957): Killing 5872:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  957): Recipient 5872
,E/WifiStateMachine(  957): handleMessage: E msg.what=131168
E/WifiStateMachine(  957): processMsg: ConnectedState
E/WifiStateMachine(  957):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  957): processMsg: L2ConnectedState,
E/WifiStateMachine(  957):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  957): processMsg: DriverStartedState
E/WifiStateMachine(  957):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
E/WifiStateMachine(  957):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  957): processMsg: DefaultState
E/WifiStateMachine(  957):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  957): handleMessage: X
,D/libc    (  957): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  957): [NET] android_getaddrinfofornet-, err=8
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  957): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  957): [NET] android_getaddrinfo_proxy+
D/libc    (  957): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  957): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  957): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  957): [AlarmQueuing] connectivity wifi: true
,D/GpsLocationProvider(  957): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  957): acquireWL(12d5f518): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 957 1000 null
D/GpsLocationProvider(  957): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  957): acquireWL(1e56db71): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 957 1000 null
D/PMS     (  957): releaseWL(1e56db71): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/htcCheckinService(  957): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/NetworkMonitor( 6669): type=WIFI subType= reason=null isConnected=true
,I/ConnectivityHelper( 1593): [onReceive] WIFI(1): CONNECTED
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/HtcWifiWanDetect(  957): Find DNS Address www.htc.com/23.206.98.145
D/libc    (  957): [NET] android_getaddrinfo_proxy-, success
,V/MusicLeanback( 6669): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,E/GpsLocationProvider(  957): No APN found to select.
,D/PMS     (  957): releaseWL(12d5f518): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MobileConnectivityChangeReceiver( 6346): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6346): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1654): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MdScPhnSt( 6607): [bc2.1.]  listen tmrbb8
,D/AutoSetting( 1654): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1654): service - onStartCommand() screen is off, don't request location
,I/PackageManager(  957):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4384, uid=10024, userID:0,
,D/MdScDataSum( 6607): [bc2.1.] summary 118:p1 ignore
,I/art     (  957): Explicit concurrent mark sweep GC freed 59231(2MB) AllocSpace objects, 3(124KB) LOS objects, 33% free, 16MB/25MB, paused 1.842ms total 148.204ms
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1833): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1833): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1833): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1833): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/Kids    ( 4384): [AccountUtils] Account not ready
W/Kids    ( 4384): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4384): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4384): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4384): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4384): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4384): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4384): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4384): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4384): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4384): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4384): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4384): 	at java.lang.Thread.run(Thread.java:818)
I/RemoteViews( 1218): reapply : com.google.android.gms 2 40
,I/jxcore-log( 6540): Test app app.js loaded
I/jxcore-log( 6540): 
,I/chromium( 6540): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/PMS     (  957): acquireWL(12c482e1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6669 10159 null
,D/PMS     (  957): acquireWL(25ba81de): PARTIAL_WAKE_LOCK  *alarm* 0x1 957 1000 WorkSource{10024},
V/AlarmManager(  957): sending alarm PendingIntent{33af1fbf: PendingIntentRecord{29f6e68c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=141395, Int=0
,I/PackageManager(  957):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6669, uid=10159, userID:0
,D/PMS     (  957): releaseWL(12c482e1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6669): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6669): Stop autocaching.
,D/WearableService( 4761): callingUid 10024, callindPid: 4761
D/PMS     (  957): acquireWL(62e651): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/PMS     (  957): releaseWL(25ba81de): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1833): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1833): [NET] android_getaddrinfo_proxy+
D/libc    ( 1833): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1833): [NET] android_getaddrinfo_proxy-, success
,E/GmsUtils( 6669): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6669): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  957): acquireWL(3a17b24): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1833 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1833): Connected
,D/PMS     (  957): releaseWL(62e651): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): releaseWL(3a17b24): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  957): acquireWL(211e968d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): acquireWL(29f34042): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1833 10024 WorkSource{10024 com.google.android.gms},
,I/GCM     ( 4384): Message from null null,
E/GCM     ( 4384): Dropping message from null
,D/PMS     (  957): releaseWL(29f34042): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1833): Message class com.google.f.a.a.p,
D/PMS     (  957): releaseWL(211e968d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): acquireWL(2f32a853): PARTIAL_WAKE_LOCK  *alarm* 0x1 957 1000 WorkSource{10024},
V/AlarmManager(  957): sending alarm PendingIntent{b0d2590: PendingIntentRecord{136b0e89 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142373, Int=0
,D/PMS     (  957): releaseWL(2f32a853): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  957): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  957): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  957): acquireWL(29f91e8e): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 957 1000 null
,D/libc    (  957): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  957): [NET] android_getaddrinfofornet-, err=8
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  957): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  957): [NET] android_getaddrinfo_proxy+
D/libc    (  957): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  957): [NET] android_getaddrinfo_proxy-, success
D/libc    (  957): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  957): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  957): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  957): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  957): acquireWL(316c959a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 957 1000 null
D/GpsLocationProvider(  957): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  957): releaseWL(29f91e8e): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  957):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  957): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  957): releaseWL(316c959a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  957): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  957): acquireWL(2feccecb): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 957 1000 WorkSource{1000}
,V/AlarmManager(  957): sending alarm PendingIntent{355d67d2: PendingIntentRecord{cd360a3 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158008, Int=0,
V/AlarmManager(  957): sending alarm PendingIntent{ad816a8: PendingIntentRecord{22d905c1 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452688748219, Int=0
,D/PMS     (  957): acquireWL(2a6e7166): PARTIAL_WAKE_LOCK  *backup* 0x1 957 1000 null
,D/PMS     (  957): releaseWL(2feccecb): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/BackupManagerService(  957): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  957): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  957): releaseWL(2a6e7166): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/AutoSetting( 1654): service - handleMessage() stop self,
,D/AutoSetting( 1654): service - onDestroy() END
,D/AutoSetting( 1654): service - handleMessage() quit looper
,D/PMS     (  957): acquireWL(12778ca7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 957 1000 null,
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  957): n_update end
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  957): releaseWL(12778ca7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  957): updateBatteryInfo
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  957): plugged=true pluggin=true
,D/UsbnetService(  957): BroadcastReceiver::onReceive+
D/PMS     (  957): runPSCheck
D/UsbnetService(  957): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  957): Checking...
D/UsbnetService(  957):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  957): >> updateStatus
D/UsbnetService(  957): BroadcastReceiver::onReceive-
D/WifiController(  957): handleMessage: E msg.what=155652
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
,D/WifiController(  957): processMsg: DeviceActiveState
D/PowerUI ( 1218): closing low battery warning: level=100,
D/WifiController(  957): processMsg: StaEnabledState
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  957): processMsg: DefaultState
D/WifiController(  957): battery changed pluggedType: 2
D/WifiController(  957): handleMessage: X
,I/HtcPowerSaver(  957): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  957): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,E/WifiStateMachine(  957): handleMessage: E msg.what=131165,
E/WifiStateMachine(  957): processMsg: ConnectedState
E/WifiStateMachine(  957):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  957): processMsg: L2ConnectedState
E/WifiStateMachine(  957):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  957): processMsg: ConnectModeState
E/WifiStateMachine(  957):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  957): processMsg: DriverStartedState
E/WifiStateMachine(  957):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  957): processMsg: SupplicantStartedState
E/WifiStateMachine(  957):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  957): processMsg: DefaultState,
E/WifiStateMachine(  957):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  957): handleMessage: X
,D/TelephonyReceiver( 1541): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/WifiStateMachine(  957): handleMessage: E msg.what=131326,
,E/WifiStateMachine(  957): processMsg: ConnectedState,
E/WifiStateMachine(  957):  ConnectedState what:131326 2 0
E/WifiStateMachine(  957): processMsg: L2ConnectedState
E/WifiStateMachine(  957):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  957): handleMessage: X
,D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcAppUPService( 1654): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@105107d1
I/ActivityManager(  957): Killing 5793:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  957): killProcessQuiet, pid=5793
,D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  957): Recipient 5793
,D/PMS     (  957): acquireWL(39ebf554): PARTIAL_WAKE_LOCK  *alarm* 0x1 957 1000 WorkSource{10024},
V/AlarmManager(  957): sending alarm PendingIntent{212f3cfd: PendingIntentRecord{2e603df2 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189240, Int=0
,V/AlarmManager(  957): sending alarm PendingIntent{2d064c43: PendingIntentRecord{15bd12c0 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=212651, Int=0
D/PMS     (  957): acquireWL(1db7abf9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  957): releaseWL(39ebf554): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  957): acquireWL(1930473e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  957): releaseWL(1db7abf9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  957): releaseWL(1930473e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  957): acquireWL(3d9279d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): releaseWL(3d9279d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): acquireWL(2d8de131): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): releaseWL(2d8de131): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  957): acquireWL(3cec0016): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): acquireWL(3f86ed97): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): acquireWL(14ae5f6d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  957): releaseWL(3cec0016): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1833): Vacuum at: now=1452688794995 tag=VacuumService
,D/PMS     (  957): releaseWL(3f86ed97): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): acquireWL(31c2cc33): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms},
I/GoogleURLConnFactory( 1833): Using platform SSLCertificateSocketFactory
,D/PMS     (  957): releaseWL(31c2cc33): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  957): acquireWL(2c9aabf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): releaseWL(2c9aabf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1833): No account for auth token provided
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1833): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1833): [NET] android_getaddrinfo_proxy+
D/libc    ( 1833): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1833): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1833): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1833): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1833): No account for auth token provided
,W/Uploader( 1833): No account for auth token provided
,W/Uploader( 1833):  no longer exists, so no auth token.
,W/Uploader( 1833): No account for auth token provided,
,I/GLSUser ( 1833): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1833): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1833): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1833): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1833): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1833): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1833): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1833): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1833): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1833): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 4 40
,I/GLSUser ( 1833): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1833): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1833): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1833): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1833): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1833): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,E/Uploader( 1833): ,	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1833): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1833): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1833): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1833): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1218): reapply : com.google.android.gms 3 40
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  957): releaseWL(14ae5f6d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): acquireWL(12343c9e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): releaseWL(12343c9e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): acquireWL(2aea237f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  957): releaseWL(2aea237f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  957): acquireWL(fbbff4c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 957 1000 null
D/UsbnetService(  957): BroadcastReceiver::onReceive+
I/BatteryService(  957): n_update end
D/UsbnetService(  957): onReceive BATTERY_CHANGED
,D/PMS     (  957): releaseWL(fbbff4c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  957):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  957): plugged=true pluggin=true
D/UsbnetService(  957): BroadcastReceiver::onReceive-
D/WifiController(  957): battery changed pluggedType: 2
D/WifiController(  957): handleMessage: E msg.what=155652
D/HtcPowerSaver(  957): updateBatteryInfo
D/WifiController(  957): processMsg: DeviceActiveState
,D/PMS     (  957): runPSCheck
D/WifiController(  957): processMsg: StaEnabledState
D/HtcPowerSaver(  957): Checking...
D/WifiController(  957): processMsg: DefaultState
I/HtcPowerSaver(  957): >> updateStatus
D/WifiController(  957): handleMessage: X
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  957): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  957): << updateStatus
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  957): acquireWL(3b9d0b95): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 957 1000 null
I/BatteryService(  957): n_update end
D/PMS     (  957): releaseWL(3b9d0b95): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  957): BroadcastReceiver::onReceive+
D/NotificationService(  957): plugged=true pluggin=true
D/UsbnetService(  957): onReceive BATTERY_CHANGED
D/WifiController(  957): battery changed pluggedType: 2
D/UsbnetService(  957):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  957): BroadcastReceiver::onReceive-
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  957): handleMessage: E msg.what=155652
D/WifiController(  957): processMsg: DeviceActiveState
D/HtcPowerSaver(  957): updateBatteryInfo
D/WifiController(  957): processMsg: StaEnabledState
D/WifiController(  957): processMsg: DefaultState
D/WifiController(  957): handleMessage: X
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  957): runPSCheck
D/HeadsetStateMachine( 3092): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  957): Checking...
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  957): >> updateStatus
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  957): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  957): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1341): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
,D/wpa_supplicant( 1341): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1341): wlan0: BSS: Remove id 2 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1341): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 06:7c:34:12:7f:81]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 06:7c:34:12:7f:81
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  957): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,I/jxcore-log( 6540): --= Surplus to requirements =--,
I/jxcore-log( 6540): 
I/jxcore-log( 6540): ****TEST TOOK:  ms ****,
,I/jxcore-log( 6540): 
I/jxcore-log( 6540): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6540): 
,E/cutils-trace( 6839): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 6839): ====startRecUseTime====,
D/htc.customization.log.level( 6839):  is 
W/CustomizationLogLevel( 6839): Level value is invalid, use default level 2
,D/CustomizationManager( 6839):  Read ACC file spent 0.053 (s),
,D/CIDMapFileReader( 6839): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 6839): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__032,
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6839): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 6839): full path : /system/customize/CID/HTC__102.xml,
,I/CustomizationCIDLoader( 6839): Parsing tag category name = system
,I/CustomizationCIDLoader( 6839): Parsing tag category name = application
,I/CustomizationCIDLoader( 6839): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 6839): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6839): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6839): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6839): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 6839): add string-array item, value = 42507,
I/CustomizationCIDLoader( 6839): add string-array item, value = 21902
I/CustomizationCIDLoader( 6839): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6839): add string-array item, value = 23420
I/CustomizationCIDLoader( 6839): add string-array item, value = 22299
,I/CustomizationCIDLoader( 6839): add string-array item, value = 24002
I/CustomizationCIDLoader( 6839): add string-array item, value = 23210
I/CustomizationCIDLoader( 6839): add string-array item, value = 23205
I/CustomizationCIDLoader( 6839): add string-array item, value = 23806
I/CustomizationCIDLoader( 6839): add string-array item, value = 23430
,I/CustomizationCIDLoader( 6839): add string-array item, value = 23408
I/CustomizationCIDLoader( 6839): add string-array item, value = 27205
I/CustomizationCIDLoader( 6839): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 21902:C:1:0
,I/CustomizationCIDLoader( 6839): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 24002:D:0:0
,I/CustomizationCIDLoader( 6839): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 23430:C:1:0
,I/CustomizationCIDLoader( 6839): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6839): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6839):  Read CID file spent 0.110 (s)
D/CustomizationManager( 6839):  All configurations done spent 0.111 (s),
,D/PackageManager(  957): deletePackageAsUser: pkg=com.test.thalitest, pid=6839, uid=2000 userid=0,
,I/ActivityManager(  957): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
,D/Process (  957): killProcessQuiet, pid=6540
I/ActivityManager(  957): Killing 6540:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  957): Skipping PackageSetting{3679a326 com.example.hello/10374} due to missing metadata
,I/ActivityManager(  957): Recipient 6540,
I/WindowState(  957): WIN DEATH: Window{20ef8967 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/InputEventReceiver( 1394): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{15e15503 uid 10366 pid 6540} (c)'
D/WifiService(  957): Client connection lost with reason: 4
,I/ActivityManager(  957):   Force finishing activity ActivityRecord{2c53e20 u0 com.test.thalitest/.MainActivity t8},
,I/ActivityManager(  957): Force stopping com.test.thalitest appid=10366 user=0: pkg removed,
,I/ActivityManager(  957):   Force finishing activity ActivityRecord{2c53e20 u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  957): Duplicate finish request for ActivityRecord{2c53e20 u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  957): Spurious death for ProcessRecord{5a384aa 6540:com.test.thalitest/u0a366}, curProc for 6540: null
,W/SystemReader(  957): Cannot find grip_rejection_width, use default value instead,
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1307): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1307): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1757): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1757): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1899): Ignoring removeGeofence because network location is disabled.
D/PMS     (  957): acquireWL(94fc438): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1899 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  957): releaseWL(94fc438): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 1593): Explicit concurrent mark sweep GC freed 3167(147KB) AllocSpace objects, 1(112KB) LOS objects, 34% free, 29MB/45MB, paused 1.056ms total 81.216ms
I/Prism.ItemManager( 1593): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1593): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1593): Deferring update until onResume
D/Launcher( 1593): waitUntilResume // bindAppsRemoved
,D/PhoneApp( 1541): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/AccTypeManager( 1757): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1593): action: android.intent.action.PACKAGE_REMOVED
,D/VoicemailCleanupService( 1708): Cleaning up data for package: com.test.thalitest
I/[PluginManager]RegisterService( 1654): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1654): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  957): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6859 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/InputMethodManagerService(  957): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,E/ExternalAccountType( 1757): Unsupported attribute readOnly
,W/ResourcesManager(  957): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  957): Explicit concurrent mark sweep GC freed 30050(1987KB) AllocSpace objects, 6(324KB) LOS objects, 33% free, 16MB/25MB, paused 2.076ms total 228.604ms
I/art     (  957): WaitForGcToComplete blocked for 190.201ms for cause Explicit
,D/StatusBarManagerService(  957): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  957): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ContextImpl( 6859): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  957): hiding MENU key
,D/StatusBarManagerService(  957): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  957): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  957): hiding MENU key
,D/FindExtension( 1593): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1593): Defer allocateBuffers to drawing time
,I/ActivityManager(  957): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6883 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/InputMethodManagerService(  957): Got RemoteException sending setActive(false) notification to pid 6540 uid 10366
D/StatusBarManagerService(  957): swetImeWindowStatus vis=0 backDisposition=0
,I/ActivityManager(  957): Killing 6384:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
,D/Process (  957): killProcessQuiet, pid=6384
D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  957): Unable to load service info ResolveInfo{24582e61 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  957): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  957): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  957): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  957): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  957): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  957): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  957): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  957): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  957): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  957): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  957): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  957): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  957): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  957): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  957): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  957): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/JobSchedulerService(  957): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  957): Explicit concurrent mark sweep GC freed 9653(632KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.975ms total 227.943ms,
,I/ActivityManager(  957): Recipient 6384
,W/asset   (  957): Copying FileAsset 0x556bd11740 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.,
,I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
,D/TaskPersister(  957): removeObsoleteFile: deleting file=8_task.xml
,I/PackageManager(  957):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6883, uid=10072, userID:0
,W/global  ( 6883): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6883): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 6883): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6883): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6883): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/ProcessCpuTracker(  957): Skipping unknown process pid 6839
,I/ActivityManager(  957): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6922 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 6883): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 6883): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 6922): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6922): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PackageManager(  957):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6883, uid=10072, userID:0
,I/MultiDex( 6922): VM with version 2.1.0 has multidex support,
I/MultiDex( 6922): install
I/MultiDex( 6922): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  957): Killing 6438:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  957): killProcessQuiet, pid=6438,
,D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,V/JNIHelp ( 6922): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  957): Recipient 6438
D/WifiService(  957): Client connection lost with reason: 4
,W/ActivityThread( 6922): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6922): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ecbabc8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6922): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 6883): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 6883): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6883): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/SQLiteLog( 1833): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1833): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x556bad04e0
,E/AndroidRuntime( 1833): FATAL EXCEPTION: main
E/AndroidRuntime( 1833): Process: com.google.process.gapps, PID: 1833
E/AndroidRuntime( 1833): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1833): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1833): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1833): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1833): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1833): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1833): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1833): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1833): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1833): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1833): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1833): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1833): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1833): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1833): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1833): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1833): 	... 9 more
,E/ActivityManager(  957): App crashed! Process: com.google.process.gapps
,D/Process ( 1833): killProcess, pid=1833
,D/Process ( 1833): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 ,
W/NativeLibraryUtils( 6922): Failed to open lock file
W/NativeLibraryUtils( 6922): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6922): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 6922): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 6922): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 6922): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6922): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6922): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 6922): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 6922): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 6922): 	... 3 more
,E/DropBoxManagerService(  957): Can't write: system_app_crash
E/DropBoxManagerService(  957): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  957): ,	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  957): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  957): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  957): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  957): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  957): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  957): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  957): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  957): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  957): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  957): 	... 5 more
,D/Finsky  ( 6883): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  957): Recipient 1833
,I/ActivityThread( 6922): Removing dead content provider:android.content.ContentProviderProxy@f4bdb86
,I/ActivityManager(  957): Process com.google.process.gapps (pid 1833) has died,
,W/ActivityManager(  957): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
,W/ActivityManager(  957): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 11000ms
W/ActivityManager(  957): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
W/ActivityManager(  957): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,I/ActivityManager(  957): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=6957 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 6957): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6957): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6957): VM with version 2.1.0 has multidex support,
I/MultiDex( 6957): install
I/MultiDex( 6957): VM has multidex support, MultiDex support library is disabled.,
,I/GservicesProvider( 6957): Gservices pushing to system: true; secure/global: true,
,E/SQLiteDatabase( 6957): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.,
E/SQLiteDatabase( 6957): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6957): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6957): ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6957): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 6957): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 6957): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 6957): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
,E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 6957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/SQLiteDatabase( 6957): ,	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6957): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6957): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6957): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6957): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6957): FATAL EXCEPTION: main
E/AndroidRuntime( 6957): Process: com.google.process.gapps, PID: 6957
E/AndroidRuntime( 6957): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 6957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6957): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6957): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6957): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6957): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6957): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/AndroidRuntime( 6957): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6957): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6957): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 6957): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 6957): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 6957): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 6957): 	... 11 more
E/ActivityManager(  957): App crashed! Process: com.google.process.gapps
D/Process ( 6957): killProcess, pid=6957
D/Process ( 6957): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  957): Can't write: system_app_crash
E/DropBoxManagerService(  957): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  957): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  957): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  957): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  957): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  957): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  957): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  957): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  957): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  957): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  957): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  957): 	... 5 more
,I/ActivityManager(  957): Recipient 6957
I/ActivityManager(  957): Process com.google.process.gapps (pid 6957) has died
W/ActivityManager(  957): Service crashed 2 times, stopping: ServiceRecord{38ea82c3 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
W/ActivityManager(  957): Service crashed 2 times, stopping: ServiceRecord{2614bb7a u0 com.google.android.gms/.gcm.http.GoogleHttpService}
W/ActivityManager(  957): Service crashed 2 times, stopping: ServiceRecord{1b9c0ab9 u0 com.google.android.gms/.gcm.GcmService}
W/ActivityManager(  957): Service crashed 2 times, stopping: ServiceRecord{a159837 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,I/ActivityManager(  957): Start proc com.google.process.gapps for restart com.google.process.gapps: pid=6980 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/Prism.ItemManager( 1593): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
,I/Prism.ItemManager( 1593): loadItems() com.htc.launcher.pageview.WidgetManager@2b91c969 +,
I/Prism.WidgetManager( 1593): onLoadItems() +
,W/ResourcesManager( 6980): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6980): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 1593): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/MultiDex( 6980): VM with version 2.1.0 has multidex support
,I/MultiDex( 6980): install
I/MultiDex( 6980): VM has multidex support, MultiDex support library is disabled.
,I/GservicesProvider( 6980): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 6980): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 6980): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6980): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6980): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6980): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 6980): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 6980): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 6980): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 6980): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 6980): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 6980): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 6980): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 6980): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 6980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6980): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6980): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6980): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6980): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6980): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6980): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6980): FATAL EXCEPTION: main
E/AndroidRuntime( 6980): Process: com.google.process.gapps, PID: 6980
E/AndroidRuntime( 6980): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6980): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 6980): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 6980): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 6980): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 6980): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 6980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/AndroidRuntime( 6980): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6980): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6980): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6980): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6980): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6980): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6980): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6980): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6980): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6980): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 6980): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 6980): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 6980): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 6980): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 6980): 	... 11 more
,W/ActivityManager(  957): Process com.google.android.gms has crashed too many times: killing!
E/ActivityManager(  957): App crashed! Process: com.google.process.gapps
I/ActivityManager(  957): Killing 6980:com.google.process.gapps/u0a24 (adj 0): crash
D/Process (  957): killProcessQuiet, pid=6980
E/DropBoxManagerService(  957): Can't write: system_app_crash
E/DropBoxManagerService(  957): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  957): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  957): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  957): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  957): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  957): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  957): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  957): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  957): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  957): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  957): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  957): 	... 5 more
D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12134 ,
,W/ResourcesManager( 1593): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/ActivityManager(  957): Recipient 6980
,D/Process (  957): killProcessQuiet, pid=6922
I/ActivityManager(  957): Killing 6922:com.google.android.gms:car/u0a24 (adj 0): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
D/Process (  957): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:15264 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:15341 
W/ActivityManager(  957): Unable to launch app com.google.android.gsf/10024 for provider com.google.android.gsf.gservices: launching app became null
,W/asset   ( 1593): Copying FileAsset 0x556c046320 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1593): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1593): onLoadItems() -
I/Prism.ItemManager( 1593): loadItems() com.htc.launcher.pageview.WidgetManager@2b91c969 -
,E/SQLiteLog( 1593): (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=75] disk I/O error,
E/SQLiteDBG( 1593): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0x556ba5c6a0
,E/AndroidRuntime( 1593): FATAL EXCEPTION: TaskWorker,
E/AndroidRuntime( 1593): Process: com.htc.launcher, PID: 1593
E/AndroidRuntime( 1593): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1593): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1593): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1593): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1593): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1593): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1593): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1593): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 1593): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 1593): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1593): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1593): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1593): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1593): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1593): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
