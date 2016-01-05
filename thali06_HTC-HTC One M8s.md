#### Test 550731521dbc378_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,E/cutils-trace( 6676): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6676): ====startRecUseTime====
D/htc.customization.log.level( 6676):  is 
W/CustomizationLogLevel( 6676): Level value is invalid, use default level 2
D/CustomizationManager( 6676):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 6676): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6676): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6676): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6676): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6676): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6676): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6676): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6676): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6676): Parsing tag category name = system
I/CustomizationCIDLoader( 6676): Parsing tag category name = application
I/CustomizationCIDLoader( 6676): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6676): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6676): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6676): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6676): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6676): add string-array item, value = 42507
I/CustomizationCIDLoader( 6676): add string-array item, value = 21902
I/CustomizationCIDLoader( 6676): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6676): add string-array item, value = 23420
I/CustomizationCIDLoader( 6676): add string-array item, value = 22299
I/CustomizationCIDLoader( 6676): add string-array item, value = 24002
I/CustomizationCIDLoader( 6676): add string-array item, value = 23210
I/CustomizationCIDLoader( 6676): add string-array item, value = 23205
I/CustomizationCIDLoader( 6676): add string-array item, value = 23806
I/CustomizationCIDLoader( 6676): add string-array item, value = 23430
I/CustomizationCIDLoader( 6676): add string-array item, value = 23408
I/CustomizationCIDLoader( 6676): add string-array item, value = 27205
I/CustomizationCIDLoader( 6676): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6676): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6676):  Read CID file spent 0.097 (s)
D/CustomizationManager( 6676):  All configurations done spent 0.097 (s)
--------- beginning of system
I/ActivityManager(  982): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6676 on display 0
D/PMS     (  982): acquireHCC(1ca554ac): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 982 1000 null
D/PMS     (  982): acquireHCC(3b39a575): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 982 1000 null
W/asset   (  982): Copying FileAsset 0x55b5cdb010 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  982): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6694 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  982): Display changed displayId=0
D/DotMatrix( 1359): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1359): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6694): Copying FileAsset 0xac191a28 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1611): [trimMemory] 20
I/WebViewFactory( 6694): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6694): Time to load native libraries: 10 ms (timestamps 1446-1456)
,I/LibraryLoader( 6694): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6694): Binding Chromium to main looper Looper (main, tid 1) {319ee39f},
I/LibraryLoader( 6694): Expected native library version number "",actual native library version number ""
,I/chromium( 6694): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6694): Initializing chromium process, singleProcess=true,
,W/art     ( 6694): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6694): ApplicationContext is null in ApplicationStatus
,W/chromium( 6694): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6694): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6694): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 6694): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6694): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6694): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6694): Local Branch: 
I/Adreno-EGL( 6694): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6694): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6694):                  d74aa161a12b9c6fc6332151
,W/System.err(  982): java.lang.Throwable: stack dump,
,D/BluetoothManagerService(  982): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  982): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d0a6029:true
W/System.err(  982): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  982): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  982): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  982): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6694): 479730363: getState(). Returning 12,
,W/art     ( 6694): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6694): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6694): CordovaWebView is running on device made by: HTC
,W/art     ( 6694): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6694): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  982): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6694): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  982): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  982): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  982): hiding MENU key
,D/StatusBarManagerService(  982): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  982): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  982): hiding MENU key
,D/FindExtension( 6694): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6694): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1802a2a1, mServedView=org.apache.cordova.engine.SystemWebView{30327cc6 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2ea7a487
,I/PhoneStatusBar( 1236): setImeWindowStatus(false,false)
I/InputMethodManagerService(  982): Disable input method client, pid=1611
D/StatusBarManagerService(  982): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6694): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  982): Displayed com.test.thalitest/.MainActivity: +612ms (total +656ms),
,W/BindingManager( 6694): Cannot call determinedVisibility() - never saw a connection for the pid: 6694
,D/JsMessageQueue( 6694): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6694): JniHelper::setJavaVM(0xab0268f8), pthread_self() = -1405880320
D/JX-Cordova( 6694): jxcore cordova android initializing
,D/Process (  982): killProcessQuiet, pid=5601,
I/ActivityManager(  982): Killing 5601:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  982): Recipient 5601
,W/jxcore-log( 6694): Initializing JXcore engine,
W/jxcore-log( 6694): JXcore engine is ready
,W/jxcore-log( 6694): Starting JXcore engine,
,W/jxcore-log( 6694): Platform android,
W/jxcore-log( 6694): 
W/jxcore-log( 6694): Process ARCH arm
W/jxcore-log( 6694): 
,D/PMS     (  982): releaseHCC(1ca554ac): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  982): releaseHCC(3b39a575): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6694): JXcore Cordova bridge is ready!
I/jxcore-log( 6694): 
W/jxcore-log( 6694): JXcore engine is started,
I/Choreographer( 6694): Skipped 102 frames!  The application may be doing too much work on its main thread.
I/chromium( 6694): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6694): Toggling radios to true,
I/jxcore-log( 6694): 
,D/BluetoothAdapter( 6694): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  982): ADD_CLIENT: 8,
D/WifiService(  982): New client listening to asynchronous messages
,D/WifiManager( 6694): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366,
W/Settings:Agent(  982): MONITOR_LOG
D/WifiService(  982): setWifiEnabled: true pid=6694, uid=10366
W/Settings:Agent(  982): name: wifi_on
E/WifiService(  982): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  982): value: 2
I/WifiService(  982): isSprintWifiRestricted(): false
W/Settings:Agent(  982): >> traceCallingStack()
I/WifiService(  982): isMdmWifiRestricted(): false
,W/Settings:Agent(  982): Process.myPid(): 982
W/Settings:Agent(  982): Process.myTid(): 1652
W/Settings:Agent(  982): Process.myUid(): 1000
W/Settings:Agent(  982): 
W/Settings:Agent(  982): 
W/System.err(  982): java.lang.Throwable: stack dump
,W/System.err(  982): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  982): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  982): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  982): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  982): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  982): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  982): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  982): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  982): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
,W/System.err(  982): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  982): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  982): 
W/Settings:Agent(  982): << traceCallingStack(): 15(ms)
D/WifiController(  982): handleMessage: E msg.what=155656
D/WifiController(  982): processMsg: DeviceActiveState
D/WifiController(  982): processMsg: StaEnabledState
D/WifiController(  982): handleMessage: X
D/WifiManager( 6694): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  982): handleMessage: E msg.what=131145
E/WifiStateMachine(  982): processMsg: ConnectedState
D/WifiManager( 6694): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  982):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6694): Radios toggled
I/jxcore-log( 6694): 
E/WifiStateMachine(  982): processMsg: L2ConnectedState
D/BluetoothManagerService(  982): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiStateMachine(  982):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
,D/wpa_supplicant( 1352): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1352): wlan0: Cancelling scan request
D/wpa_supplicant( 1352): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1352): TDLS: Tear down peers
D/wpa_supplicant( 1352): wpa_driver_nl80211_disconnect(reason_code=3)
D/BluetoothManagerService(  982): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6694): Received device characteristics:
I/jxcore-log( 6694): Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6694): Bluetooth name: HTC One M8s
I/jxcore-log( 6694): Device name: HTC-HTC One M8s
I/jxcore-log( 6694): 
,I/jxcore-log( 6694): Perf Test app loaded loaded,
I/jxcore-log( 6694): 
,I/jxcore-log( 6694): check test folder
I/jxcore-log( 6694): 
,I/jxcore-log( 6694): found test : ./testFindPeers.js
I/jxcore-log( 6694): 
,D/wpa_supplicant( 1352): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1352): wlan0: Deauthentication notification
D/wpa_supplicant( 1352): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1352): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1352): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1352): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1352): enter disconnect check
I/wpa_supplicant( 1352): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  982): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  982): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  982): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1352): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1352): wlan0: Ignore connection failure indication since interface has been put into disconnected state
,D/Tethering(  982): interfaceLinkStateChanged wlan0, false
,D/Tethering(  982): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  982): interfaceLinkStateChanged wlan0, false
,D/Tethering(  982): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  982): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  982): TetherInterfaceSM: wlan0: enter UnavailableState
,E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  982): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 1352): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1352): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1352): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1352): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/Tethering(  982): sendTetherStateChangedBroadcast 0, 0, 0
D/wpa_supplicant( 1352): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5565b1af88 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 1352):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1352): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1352): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1352): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1352): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1352): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1352): nl80211: Skip set_supp_port(unauthorized) while not associated
D/WifiDisplayAdapter(  982): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  982):     Client/Owner: Client
D/WifiDisplayAdapter(  982):     GroupId: 
D/WifiDisplayAdapter(  982):     Passphrase: 
D/WifiDisplayAdapter(  982):     SessionId: 0
D/WifiDisplayAdapter(  982):     IP Address: }
D/wpa_supplicant( 1352): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1352): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1352): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1352): wlan0: State: DISCONNECTED -> DISCONNECTED
D/PMS     (  982): acquireWL(22c4146a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 982 1000 null
D/wpa_supplicant( 1352): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1352): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/UsbDeviceManager(  982): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1352): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1352): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1352): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1352): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1352): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1352): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1352): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  982): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  982): handleMessage: new destination call exit/enter
E/WifiStateMachine(  982): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  982): invokeExitMethods: ConnectedState
E/WifiStateMachine(  982): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  982): release()
E/WifiStateMachine(  982): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  982): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  982): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  982): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  982): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  982): handleNetworkDisconnect "NG700" nid=0
,E/WifiConfigStore(  982): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  982): QCOM Debug skip set_network part for security concern!
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/wpa_supplicant( 1352): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1352): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1352): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbnetService(  982): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/HTCRequest(  982): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1352): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1352): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WifiP2pService(  982): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1352): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1352): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiMonitor(  982): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  982): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1352): Power_Mode_Type mode = 0
I/wpa_supplicant( 1352): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  982): setDhcpActive: false
V/NativeCrypto( 1971): Read error: ssl=0x55b5620990: I/O error during system call, Connection timed out
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  982): acquireWL(3fb12d5b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
I/jxcore-log( 6694): found test : ./testSendData.js
I/jxcore-log( 6694): 
,E/WifiStateMachine(  982): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  982): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  982): NetworkAgent != null
D/ConnectivityService(  982): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  982): mWifiStateReceiver: meteredHint=false,EPS mode=false,
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED connected
,D/libc    (  982): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  982): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  982): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  982): releaseWL(22c4146a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  982): autoRoamSetBSSID any key="NG700"WPA_PSK
V/NetworkPolicy(  982): updateNetworkEnabledLocked()
E/WifiConfigStore(  982): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/NetworkPolicy(  982): updateNotificationsLocked()
W/WifiHW  (  982): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1352): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1352): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1352): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/PMS     (  982): releaseWL(3fb12d5b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
V/NativeCrypto( 1971): SSL shutdown failed: ssl=0x55b5620990: I/O error during system call, Broken pipe
D/wpa_supplicant( 1352): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1352): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/wpa_supplicant( 1352): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1352): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  982): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  982): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  982): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  982):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  982): Start Disconnecting Watchdog 1
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131146
E/WifiStateMachine(  982): processMsg: DisconnectingState
E/WifiStateMachine(  982):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1352): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1352): Fast associate: Old scan results
,D/wpa_supplicant( 1352): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1352): wpa_supplicant_scan enter
D/wpa_supplicant( 1352): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1352): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1352): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * Request Type
D/wpa_supplicant( 1352): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Primary Device Type
D/wpa_supplicant( 1352): WPS:  * RF Bands (3)
D/wpa_supplicant( 1352): WPS:  * Association State
D/wpa_supplicant( 1352): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1352): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1352): WPS:  * Manufacturer
D/wpa_supplicant( 1352): WPS:  * Model Name
D/wpa_supplicant( 1352): WPS:  * Model Number
D/wpa_supplicant( 1352): WPS:  * Device Name
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
E/WifiStateMachine(  982): handleMessage: X
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1352): wlan0: Add radio work 'scan'@0x5565afdaa0
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  982): handleMessage: E msg.what=147460
D/wpa_supplicant( 1352): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  982): processMsg: DisconnectingState
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1352): wlan0: Starting radio work 'scan'@0x5565afdaa0 after 0.000054 second wait
D/wpa_supplicant( 1352): wlan0: nl80211: scan request
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  982): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  982): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/WifiStateMachine(  982):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=135155
E/WifiStateMachine(  982): processMsg: ConnectModeState
D/wpa_supplicant( 1352): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiDataStallTracker(  982): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  982): stopDataStallAlarm 
D/wpa_supplicant( 1352): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1352): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1352): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1352): wlan0: Own scan request started a scan in 0.000119 seconds
I/wpa_supplicant( 1352): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  982):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=135156
E/WifiStateMachine(  982): ConnectModeState: Network connection lost 
E/WifiStateMachine(  982): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  982): handleMessage: new destination call exit/enter
E/WifiDataStallTracker(  982): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiStateMachine(  982): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  982): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  982): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  982): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  982): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  982): DisconnectedState call setCountryCode()
E/WifiStateMachine(  982):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1352): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1352): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1352): wlan0: Cancelling scan request
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): wlan0: nl80211: sched_scan request
D/TetherSettings( 5926): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5926): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5926): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5926): Cust_ConnectToPC   : spcsc>false
D/        ( 5926): Cust_ConnectToPC   : IPT>true
D/        ( 5926): Cust_ConnectToPC   : Singel_USB>false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): Validated
W/Settings( 5926): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5926): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5926): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5926): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ContextImpl( 5926): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5926): setISNotification
D/SmartNS_Utility( 5926): usb_cable_connect = 1
D/SmartNS_Utility( 5926): usb_denied = 0
I/SmartNS_PSService( 5926): usb notificaiton:true
D/wpa_supplicant( 1352): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
,D/wpa_supplicant( 1352): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1352): wlan0: nl80211: Sched scan started
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1352): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1352): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1352): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1352): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1352): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1352): wlan0: Scan completed in 0.037930 seconds
D/wpa_supplicant( 1352): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1352): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
D/wpa_supplicant( 1352): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1352): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1352): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1352): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1352): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1352): wlan0: Radio work 'scan'@0x5565afdaa0 done in 0.038978 seconds
D/wpa_supplicant( 1352): wlan0: Selecting BSS from priority group 413
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1352): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58 wps
E/WifiMonitor(  982): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1352): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1352): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1352): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1352):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1352): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/WifiMonitor(  982): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 1352): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x5565b1cc00  current_ssid=0x0
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=42 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1352): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): wpa_supplicant_set_is_wep_security: 0
W/WifiMonitor(  982): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1352): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1352): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1352): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1352): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1352): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1352): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1352): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1352): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1352): wlan0: Add radio work 'connect'@0x5565afdaa0
D/wpa_supplicant( 1352): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): wlan0: Starting radio work 'connect'@0x5565afdaa0 after 0.000060 second wait
I/wpa_supplicant( 1352): check if in concurrent case
I/wpa_supplicant( 1352): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  982): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=43 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/ActionCombine( 5926): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/wpa_supplicant( 1352): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1352): wlan0: Cancelling sched scan
D/wpa_supplicant( 1352): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1352): wlan0: Cancelling scan request
D/wpa_supplicant( 1352): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1352): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1352): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1352): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1352): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1352): RSN: PMKSA cache search - network_ctx=0x5565b1cc00 try_opportunistic=0
D/wpa_supplicant( 1352): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1352): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1352): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1352): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1352): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1352): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1352): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1352): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1352): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1352): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1352): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1352): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1352): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1352): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1352): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1352): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1352): nl80211: Unsubscribe mgmt frames handle 0x888888dded394989 (mode change)
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1352): nl80211: Subscribe to mgmt frames with non-AP handle 0x5565b1c100
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=0104
D/HTCRequest(  982): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=040a
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=040b
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=040c
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=040d
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=090a
D/WifiMonitor(  982): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=090b
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=090c
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=090d
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=0409506f9a09
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=7f506f9a09
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=0801
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=040e
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=06
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=0a07
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=0a11
D/wpa_supplicant( 1352): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5565b1c100 match=0a1a
D/wpa_supplicant( 1352): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1352):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352):   * freq=2412
D/wpa_supplicant( 1352):   * freq_hint=2412
D/wpa_supplicant( 1352):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1352):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1352):   * WPA Versions 0x2
D/wpa_supplicant( 1352):   * pairwise=0xfac04
D/wpa_supplicant( 1352):   * group=0xfac04
D/wpa_supplicant( 1352):   * akm=0xfac02
D/wpa_supplicant( 1352):   * Auth Type 0
D/wpa_supplicant( 1352): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5565b1cc3a
D/wpa_supplicant( 1352): nl80211: Connect request send successfully
D/wpa_supplicant( 1352): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1352): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1352): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1352): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1352): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1352): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1352): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131101
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  982): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  982): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=147462
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=135203  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  982): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  982): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=135203  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  982): handleMessage: X
D/WifiNetworkAgent(  982): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  982): handleMessage: E msg.what=131212
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
I/QuickSettingWifi( 1236): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:3
E/WifiStateMachine(  982):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  982): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131212
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  982): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  982): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131212
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  982): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=147462
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=135211  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  982): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  982): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  982): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/SmartNS_Utility( 5926): usb_cable_connect = 1
E/WifiStateMachine(  982): NetworkAgent == null
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/SmartNS_Utility( 5926): usb_denied = 0
I/SmartNS_PSService( 5926): usb notificaiton:true
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  982): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  982):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=135217  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=147461
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:88 bcn=0
E/WifiStateMachine(  982): processMsg: ConnectModeState
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  982):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:88 bcn=0
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:88 bcn=0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:88 bcn=0
D/WifiStateMachine(  982): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1352): wlan0: Control interface command 'LIST_DONGLES'
I/RemoteViews( 1236): reapply : com.android.settings 1 36
W/ContextImpl(  982): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  982): [1,451,989,177,446 ms] noteScanEnd no scan source
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/wpa_supplicant( 1352): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  982): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2b6d4b17 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  982): NG7005g c0:ff:d4:d3:aa:4a rssi=-49 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiAutoJoinController (  982): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  982): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  982): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  982):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiAutoJoinController (  982): UPC503894600 a0:c5:62:7a:49:97 rssi=-80 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  982): UPC243894600 a0:c5:62:7a:49:96 rssi=-86 cap [WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  982): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-90 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  982): UPC5999698 64:7c:34:12:7f:81 rssi=-90 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiAutoJoinController (  982): Gonzos 38:f8:89:11:e9:11 rssi=-89 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiAutoJoinController (  982): ageScanResultsOut delay 40000 size 7 now 1451989177450
E/WifiAutoJoinController (  982): newSupplicantResults size=7 known=1 true
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1352): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  982): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  982): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  982): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  982): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  982): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  982):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131213
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=135227
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=135227
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=135227
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_TARGET_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=135228
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=147462
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=135228  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  982): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  982): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  982): setDetailed state send new extra info0x
D/SmartNS_NSReceiver( 5926): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  982): NetworkAgent == null
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=135232  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  982): handleMessage: X
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 18
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 19
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1236): reapply : com.android.settings 2 36
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  982): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  982): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  982): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1236): CM callback handler got msg 524292
I/SecurityController( 1236): onLost 100
D/WIFI    (  982): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  982): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  982):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  982): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  982): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/NetworkManagementService(  982): Removing idletimer
E/WifiStateMachine(  982): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/usbnet  (  982): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  982):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  982): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WISPrService( 5926): >>>>>WISPrService start isConnected = true<<<<<
I/chromium( 6694): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  982): acquireWL(32666ed1): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 982 1000 null
E/WifiTrafficPoller(  982): ADD_CLIENT: 9
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/Tethering(  982): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/CSLegacyTypeTracker(  982): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/Tethering(  982): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  982): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiService(  982): New client listening to asynchronous messages
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  982): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
E/ConnectivityService(  982): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/ConnectivityService(  982): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/PMS     (  982): acquireWL(32070d36): PARTIAL_WAKE_LOCK  NetworkStats 0x1 982 1000 null
D/DATA_ICON( 1236): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/DATA_ICON( 1236): dataConnected: false/false
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  982): releaseWL(32070d36): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  982): ensureActiveMobilePolicyLocked()
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/NetworkPolicy(  982): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  982): updateNetworkEnabledLocked()
,V/NetworkPolicy(  982): updateIfacesLocked()
V/NetworkPolicy(  982): updateNotificationsLocked()
E/WifiStateMachine(  982): handleMessage: E msg.what=131131
E/WifiStateMachine(  982): processMsg: DisconnectedState
V/NetworkPolicy(  982): updateNetworkEnabledLocked()
V/NetworkPolicy(  982): updateNotificationsLocked()
E/WifiStateMachine(  982):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  982): processMsg: ConnectModeState
,E/WifiStateMachine(  982):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/NetworkManagementService(  982): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  982): handleMessage: X
,W/WISPrService( 5926): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5926): trigger connection
D/WISPrService( 5926): continue
,D/WISPrService( 5926): start DataConnection
,D/libc    ( 5926): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5926): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  982): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6757 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5926): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5926): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5926): [NET] android_getaddrinfo_proxy+
D/libc    ( 5926): [NET] android_getaddrinfo_proxy get netid:0
,D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/libc    ( 5926): [NET] android_getaddrinfo_proxy-, NODATA
,D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/FlexNetS( 6559): updateSvcAllowedInSettings:false
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1352): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1352): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1352): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1352): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1352): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1352): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1352): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1352): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1352): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1352): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1352): nl80211: Connect event
D/wpa_supplicant( 1352): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1352): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1352): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1352): wlan0: Association info event
D/wpa_supplicant( 1352): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1352): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1352): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1352): wlan0: freq=2412 MHz
D/wpa_supplicant( 1352): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1352): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1352): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1352): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1352): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1352): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): wlan0: WPA: clearing AP WPA IE
D/Tethering(  982): interfaceLinkStateChanged wlan0, false
D/Tethering(  982): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1352): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1352): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1352): wlan0: WPA: Association event - clear replay counter
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1352): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1352): TDLS: Remove peers on association
D/wpa_supplicant( 1352): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1352): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1352): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1352): EAPOL: External notification - portEnabled=1
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1352): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1352): EAPOL: enable timer tick
D/wpa_supplicant( 1352): EAPOL: SUPP_BE entering state IDLE
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1352): wlan0: Setting authentication timeout: 10 sec 0 usec
D/HTCRequest(  982): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1352): wlan0: Cancelling scan, request
I/wpa_supplicant( 1352): htc_wext_set_keepalive +
I/wpa_supplicant( 1352): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1352): getPrivFuncNum +	
I/wpa_supplicant( 1352): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1352): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1352): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1352): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1352): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1352): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1352): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1352): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1352):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1352):   key_nonce - hexdump(len=32): 99 aa 8a 4f 03 1e e6 5e c2 36 34 22 b7 11 a2 a8 11 88 78 2d 30 83 c0 d5 71 c6 a6 4e 5f 8a f6 e4
D/WifiMonitor(  982): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1352):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1352):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1352):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1352):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1352): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  982): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
D/Tethering(  982): interfaceLinkStateChanged wlan0, false
D/Tethering(  982): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1352): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=46 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1352): RSN: msg 1/4 key data - hexdump(len=0):
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  982): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  982): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  982): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  982): interfaceLinkStateChanged wlan0, false
D/Tethering(  982): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  982): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1352): WPA: Renewed SNonce - hexdump(len=32): 65 54 17 b1 98 44 9c 54 79 81 d3 03 8c 49 d7 3b ce 0c 35 ec 69 25 5d 56 22 1c eb d8 17 65 ca 05
D/wpa_supplicant( 1352): WPA: Nonce1 - hexdump(len=32): 65 54 17 b1 98 44 9c 54 79 81 d3 03 8c 49 d7 3b ce 0c 35 ec 69 25 5d 56 22 1c eb d8 17 65 ca 05
D/wpa_supplicant( 1352): WPA: Nonce2 - hexdump(len=32): 99 aa 8a 4f 03 1e e6 5e c2 36 34 22 b7 11 a2 a8 11 88 78 2d 30 83 c0 d5 71 c6 a6 4e 5f 8a f6 e4
D/wpa_supplicant( 1352): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1352): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1352): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 1352): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1352): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1352): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1352): WPA: Derived Key MIC - hexdump(len=16): 07 f1 02 30 34 34 2c 39 16 4b a1 bd bd 55 11 b2
D/Tethering(  982): interfaceLinkStateChanged wlan0, true
D/Tethering(  982): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  982): TetherInterfaceSM: wlan0: enter InitialState
D/HTCRequest(  982): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  982): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  982): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/UsbDeviceManager(  982): [USBNET] bCheckSuppFunc: cdc_network
D/WifiMonitor(  982): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  982): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  982): acquireWL(30472709): PARTIAL_WAKE_LOCK  NetworkStats 0x1 982 1000 null
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  982): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  982): handleMessage: E msg.what=147462
D/WifiMonitor(  982): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=135332  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  982): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  982): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  982): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  982): processMsg: ConnectModeState
D/UsbnetService(  982): BroadcastReceiver::onReceive+
E/WifiStateMachine(  982):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=135332  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/UsbnetService(  982): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  982): BroadcastReceiver::onReceive-
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=147500
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  982): Enter handleAssociatedWithEvent
D/WifiStateMachine(  982): Associated
D/WifiStateMachine(  982): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  982): Exit handleAssociatedWithEvent
E/WifiStateMachine(  982): handleMessage: X
D/FlexNetS( 6559): updateSvcAllowedInSettings:false
E/WifiStateMachine(  982): handleMessage: E msg.what=147462
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=135335  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  982): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  982): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  982): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1352): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1352): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1352): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1352): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1352):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1352):   key_nonce - hexdump(len=32): 99 aa 8a 4f 03 1e e6 5e c2 36 34 22 b7 11 a2 a8 11 88 78 2d 30 83 c0 d5 71 c6 a6 4e 5f 8a f6 e4
D/wpa_supplicant( 1352):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1352):   key_rsc - hexdump(len=8): a8 c0 00 00 00 00 00 00
D/wpa_supplicant( 1352):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1352):   key_mic - hexdump(len=16): cb 42 df 69 47 37 7c 87 74 c6 de 9d 7c fb 4e f3
E/WifiStateMachine(  982): NetworkAgent == null
D/wpa_supplicant( 1352): RSN: encrypted key data - hexdump(len=56): 61 83 e9 e8 0f ee ee af 67 b8 f4 0e cf 6c a2 23 34 89 92 98 22 36 42 60 13 0d 15 dc a0 07 f2 49 ...
D/wpa_supplicant( 1352): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1352): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1352): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1352): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 83 e9 ...
D/wpa_supplicant( 1352): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1352): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1352): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1352): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1352): WPA: Derived Key MIC - hexdump(len=16): 63 f0 83 7d 16 7e 50 57 a8 ed 7d db 19 ac 21 18
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1352): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1352): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5565b1d390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1352): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1352): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1352):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1352): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1352): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1352): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1352): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1352): WPA: RSC - hexdump(len=6): a8 c0 00 00 00 00
D/PMS     (  982): releaseWL(30472709): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
V/NetworkPolicy(  982): updateNetworkEnabledLocked()
D/wpa_supplicant( 1352): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5555e6be68 key_idx=2 set_tx=0 seq_len=6 key_len=16
V/NetworkPolicy(  982): updateNotificationsLocked()
D/wpa_supplicant( 1352): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1352): nl80211: KEY_SEQ - hexdump(len=6): a8 c0 00 00 00 00
D/wpa_supplicant( 1352):    broadcast key
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  982): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  982): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1352): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1352): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1352): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1352): wlan0: Radio work 'connect'@0x5565afdaa0 done in 0.145126 seconds
I/wpa_supplicant( 1352): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1352): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 20
E/wpa_supplicant( 1352): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1352): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1352): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  982): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=49 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  982): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  982): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=50 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1352): set send_ind_to_ndc = 0
E/WifiMonitor(  982): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine(  982): processMsg: ConnectModeState
I/wpa_supplicant( 1352): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1352): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1352): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1352): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1352): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1352): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1352): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1352): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1352): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1352): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  982): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=52 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  982): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1352): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1352): EAPOL authentication completed - result=SUCCESS
D/HTCRequest(  982): WifiMonitor,:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1352): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  982): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1352): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiStateMachine(  982):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=135341  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor(  982): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131101
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  982): processMsg: DisconnectedState
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  982):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  982):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
D/Tethering(  982): interfaceLinkStateChanged wlan0, true
D/Tethering(  982): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  982):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  982): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  982): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  982): handleMessage: X
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  982): handleMessage: E msg.what=147462
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=135347  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  982): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  982): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=135348  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=147459
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=135349
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=135349
E/WifiStateMachine(  982): Network connection established
D/WifiStateMachine(  982): fetchFrequency(), freq = 2412
E/WifiStateMachine(  982): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
D/FlexNetS( 6559): updateSvcAllowedInSettings:false
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
E/WifiStateMachine(  982): NetworkAgent == null
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    ( 5926): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5926): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  982): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  982): handleMessage: new destination call exit/enter
E/WifiStateMachine(  982): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  982): invokeExitMethods: DisconnectedState
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1352): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1352): CTRL_IFACE SET 'pno'='0'
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDisplayAdapter(  982): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  982):     Client/Owner: Client
D/WifiDisplayAdapter(  982):     GroupId: 
D/WifiDisplayAdapter(  982):     Passphrase: 
D/WifiDisplayAdapter(  982):     SessionId: 0
D/WifiDisplayAdapter(  982):     IP Address: }
E/WifiStateMachine(  982): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  982): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  982): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  982): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  982): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  982): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  982): NetworkAgent == null
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5926): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 22
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 23
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  982): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  982): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  982): Got NetworkAgent Messenger
E/WifiStateMachine(  982): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  982): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  982): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  982): NetworkAgent connected
W/WifiHW  (  982): QCOM Debug skip set_network part for security concern!
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/wpa_supplicant( 1352): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1352): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1352): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1352): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1352): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 24
D/wpa_supplicant( 1352): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1352): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  982): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  982): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  982): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  982): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  982): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  982): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1352): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1352): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1352): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/FlexNetS( 6559): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1352): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1352): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1352): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1352): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  982): Start Dhcp Watchdog 2
E/WifiStateMachine(  982): handleMessage: X
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  982): handleMessage: E msg.what=147462
E/WifiStateMachine(  982): processMsg: ObtainingIpState
E/WifiStateMachine(  982):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=135374  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  982): processMsg: L2ConnectedState
E/WifiStateMachine(  982):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=135375  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=135376  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131212
E/WifiStateMachine(  982): processMsg: ObtainingIpState
E/WifiStateMachine(  982):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: L2ConnectedState
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  982):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  982):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
D/FlexNetS( 6559): updateSvcAllowedInSettings:false
E/WifiStateMachine(  982):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  982): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  982): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/WifiStateMachine(  982): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  982): handleMessage: X
D/PMS     (  982): acquireWL(b4a6472): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 982 1000 null
E/WifiStateMachine(  982): handleMessage: E msg.what=196612
D/WifiStateMachine(  982): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  982): processMsg: ObtainingIpState
E/WifiStateMachine(  982):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  982): processMsg: L2ConnectedState
E/WifiStateMachine(  982):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiDataStallTracker(  982): setDhcpActive: true
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  982): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
E/native  (  982): do suspend false
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1352): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1352): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1352): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1352): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  982): Unexpected BatchedScanResults :null
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  982): noteBatchedScanstop()
E/WifiStateMachine(  982): handleMessage: X
D/WifiP2pService(  982): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b87617b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b87617b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6559): updateSvcAllowedInSettings:false
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
D/FlexNetS( 6559): updateSvcAllowedInSettings:false
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:0
D/TetherSettings( 5926): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5926): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5926): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5926): Cust_ConnectToPC   : spcsc>false
D/        ( 5926): Cust_ConnectToPC   : IPT>true
D/        ( 5926): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5926): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 5926): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/SmartNS_Utility( 5926): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5926): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5926): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
I/SmartNS_Utility( 5926): setISNotification
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
D/SmartNS_Utility( 5926): usb_cable_connect = 1
D/SmartNS_Utility( 5926): usb_denied = 0
I/SmartNS_PSService( 5926): usb notificaiton:true
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 5926): usb_cable_connect = 1
,D/SmartNS_Utility( 5926): usb_denied = 0
I/SmartNS_PSService( 5926): usb notificaiton:true
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1236): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5926): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false,
I/RemoteViews( 1236): reapply : com.android.settings 2 36
,D/MdScPhnSt( 6757): [ff2.2.]  listen tmrbb8,
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6625): remove item 101 (p2d22in224) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 6757): [ff2.2.] summary 118:p2 ignore
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
D/MdProvGlob( 6625): remove item 101 (p2in11) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6625): remove item 101 (p2in9) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6625): remove item 101 (p2d1in15) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 6625): remove item 101 (p2in11) for 15:android.intent.action.ANY_DATA_STATE,
,E/dhcpcd  ( 6788): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6788): version 5.5.6 starting
E/dhcpcd  ( 6788): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6788): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6788): autoip env[11]:autoip=DISABLE
,D/Process (  982): killProcessQuiet, pid=6209
I/ActivityManager(  982): Killing 6209:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6788): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6788): wlan0: sending REQUEST (xid 0x2346bcba), next in 1.37 seconds
,I/ActivityManager(  982): Recipient 6209
,D/wpa_supplicant( 1352): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1352): EAPOL: disable timer tick
,I/dhcpcd  ( 6788): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6788): wlan0: leased 192.168.1.130 for 86400 seconds
I/dhcpcd  ( 6788): autoip env[11]:autoip=DISABLE
,D/libc    (  982): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  982): handleMessage: E msg.what=131212
E/WifiStateMachine(  982): processMsg: ObtainingIpState
E/WifiStateMachine(  982):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: L2ConnectedState
E/WifiStateMachine(  982):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  982): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  982): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  982): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  982): handleMessage: X,
,D/libc    (  982): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  982): handleMessage: E msg.what=131212
E/WifiStateMachine(  982): processMsg: ObtainingIpState
E/WifiStateMachine(  982):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  982): processMsg: L2ConnectedState
,E/WifiStateMachine(  982):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine(  982): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  982): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4,
D/ConnectivityService(  982): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  982): handleMessage: X
,I/dhcpcd  ( 6788): bind_interface: daemonise,
,D/libc    (  982): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  982): handleMessage: E msg.what=196613
,E/WifiStateMachine(  982): processMsg: ObtainingIpState
E/WifiStateMachine(  982):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  982): processMsg: L2ConnectedState
,E/WifiStateMachine(  982):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine(  982): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER POWERMODE 0'
,I/wpa_supplicant( 1352): Power_Mode_Type mode = 0,
I/wpa_supplicant( 1352): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WifiP2pService(  982): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/PMS     (  982): releaseWL(b4a6472): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  982): setDhcpActive: false
,E/WifiStateMachine(  982): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  982): WifiStateMachine DHCP successful
E/WifiStateMachine(  982): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
,D/ConnectivityService(  982): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  982): link address 192.168.1.130/24
E/WifiStateMachine(  982): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  982): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  982): gateway: /192.168.1.1
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1352): WiFi gateway: 0x101a8c0
,I/wpa_supplicant( 1352): htc_wext_set_keepalive +
I/wpa_supplicant( 1352): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1352): getPrivFuncNum +	
I/wpa_supplicant( 1352): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1352): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1352): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1352): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1352): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  982): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  982): handleMessage: X
,E/WifiStateMachine(  982): handleMessage: E msg.what=131210
E/WifiStateMachine(  982): processMsg: ObtainingIpState
E/WifiStateMachine(  982):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  982): processMsg: L2ConnectedState
E/WifiStateMachine(  982):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1352): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1352): environment dirty rate=50 [6][3][0]
,E/WifiStateMachine(  982): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  982): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
,D/WifiWatchdogStateMachine(  982): RSSI current: 3 new: -58, 3
,E/WifiConfigStore(  982): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1352): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1352): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  982): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/WIFI_ICON( 1236): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  982): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=54 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  982): NetworkAgent != null
D/ConnectivityService(  982): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/ConnectivityService(  982): Adding iface wlan0 to network 101
,E/WifiStateMachine(  982): transitionTo: destState=ConnectedState
D/HtcWifiWanDetect(  982): WAN detection
E/WifiStateMachine(  982): handleMessage: new destination call exit/enter
E/WifiStateMachine(  982): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
V/NetworkPolicy(  982): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  982): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  982): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  982): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  982): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  982): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
D/HtcWifiWanDetect(  982): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
D/WifiDataStallTracker(  982): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiStateMachine(  982): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 25
E/WifiDataStallTracker(  982): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  982): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  982): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 26
,D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5926): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  982): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  982): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  982): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  982): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  982): Setting Dns servers for network 101 to [/192.168.1.1]
,D/libc    (  982): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/Nat464Xlat(  982): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true,
E/WifiStateMachine(  982): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  982): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  982): handleMessage: X
D/ConnectivityService(  982): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  982): handleMessage: E msg.what=131131,
D/ConnectivityService(  982): rematching NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  982): processMsg: ConnectedState
D/ConnectivityService(  982):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  982): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  982):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  982):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  982):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  982): processMsg: L2ConnectedState
D/ConnectivityService(  982): currentScore = 0, newScore = 20
D/usbnet  (  982):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  982):    accepting network in place of null
D/usbnet  (  982): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  982): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  982): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): Connected
D/ConnectivityService(  982): sendGeneralBroadcast, restrictEnable=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  982): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): Validated
D/ConnectivityService(  982): sendGeneralBroadcastDelayed, restrictEnable=false
E/WifiStateMachine(  982):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  982): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  982): processMsg: ConnectModeState
D/PMS     (  982): acquireWL(3c56961f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 982 1000 null
E/WifiStateMachine(  982):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
V/NetworkPolicy(  982): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  982): handleMessage: X
D/ConnectivityService(  982): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/WIFI    (  982): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  982): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  982):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth,>=1048576Kbps]
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  982): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Tethering(  982): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  982): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Tethering(  982): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  982): Validated NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  982): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): Validated
D/ConnectivityService(  982):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  982): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  982):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  982):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  982): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  982): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  982): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  982): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  982):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  982): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  982): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkPolicy(  982): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/ConnectivityManager.CallbackHandler( 1236): CM callback handler got msg 524290
V/NetworkPolicy(  982): updateNetworkEnabledLocked()
I/SecurityController( 1236): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  982): updateIfacesLocked()
D/ConnectivityManager.CallbackHandler( 1236): CM callback handler got msg 524290
D/ConnectivityService(  982): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  982): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  982): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  982): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  982): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  982):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  982,):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  982): updateNotificationsLocked()
D/ConnectivityService(  982): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  982): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  982): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PMS     (  982): releaseWL(3c56961f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1236): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
I/SecurityController( 1236): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  982): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/ConnectivityManager.CallbackHandler( 1236): CM callback handler got msg 524290
D/WISPrService( 5926): >>>>>WISPrService start isConnected = true<<<<<
D/DATA_ICON( 1236): dataConnected: false/false
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/SecurityController( 1236): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1236): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
V/NetworkPolicy(  982): updateNetworkEnabledLocked()
V/NetworkPolicy(  982): updateNotificationsLocked()
D/DATA_ICON( 1236): dataConnected: false/false
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/QuickSettingWifi( 1236): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I/QuickSettingWifi( 1236): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/PMS     (  982): releaseWL(32666ed1): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  982): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  982): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  982): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  982): [AlarmQueuing] connectivity wifi: false,
D/htcCheckinService(  982): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  982): acquireWL(d958d6c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 982 1000 null
D/GpsLocationProvider(  982): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  982): acquireWL(274c4f35): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 982 1000 null
D/PMS     (  982): releaseWL(274c4f35): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  982): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ConnectivityHelper( 1611): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  982): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6822 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  982): No APN found to select.
,D/PMS     (  982): releaseWL(d958d6c): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,D/MdScPhnSt( 6757): [98.1.]  listen tmrbb8,
,D/MdScDataSum( 6757): [98.1.] summary 118:p1 ignore
,I/MusicStore( 6822): Database version: 120,
,D/VoldConnector(  982): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6822): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  982): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6822): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  982): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6822): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 6822): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6822): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2dd7ee12: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
W/ActivityThread( 6822): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 6822): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6822): GMSCore installation verified
I/ConfigStore( 6822): Config Database version: 1
,I/PackageManager(  982):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6822, uid=10159, userID:0,
,D/WifiDisplayAdapter(  982): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  982):     Client/Owner: Client
D/WifiDisplayAdapter(  982):     GroupId: 
D/WifiDisplayAdapter(  982):     Passphrase: 
D/WifiDisplayAdapter(  982):     SessionId: 0
D/WifiDisplayAdapter(  982):     IP Address: }
,D/MediaRouterService(  982): Client com.google.android.music (pid 6822): Registered,
,D/WifiDisplayAdapter(  982): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  982):     Client/Owner: Client
D/WifiDisplayAdapter(  982):     GroupId: 
D/WifiDisplayAdapter(  982):     Passphrase: 
D/WifiDisplayAdapter(  982):     SessionId: 0
D/WifiDisplayAdapter(  982):     IP Address: }
,I/MediaRouter( 6822): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6822): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6822): type=WIFI subType= reason=null isConnected=true
,I/art     (  982): Explicit concurrent mark sweep GC freed 60427(3MB) AllocSpace objects, 5(808KB) LOS objects, 33% free, 16MB/25MB, paused 3.124ms total 225.182ms,
,I/NetworkMonitor( 6822): type=WIFI subType= reason=null isConnected=true
,D/AutoSetting( 1675): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
I/PackageManager(  982):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6822, uid=10159, userID:0,
D/MobileConnectivityChangeReceiver( 6415): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 6415): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1675): service - onCreate()
,I/GHttpClientFactory( 6822): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1675): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1675): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  982): request 6394a31 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  982): provider request: passive ProviderRequest[ON interval=0]
,I/GoogleURLConnFactory( 6822): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/ActivityManager(  982): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6867 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6465): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 6465): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6465): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6465): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6465): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6465): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1971): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1971): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1971): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1971): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6465): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4440): [AccountUtils] Account not ready,
W/Kids    ( 4440): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4440): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4440): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4440): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4440): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4440): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4440): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4440): 	at com.google.android.gms.kids.account.t.a(SourceFile:62),
W/Kids    ( 4440): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4440): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4440): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4440): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1359): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1236): reapply : com.google.android.gms 2 40
,I/Babel   ( 6465): connection state changed from UNKNOWN to CONNECTED
,D/VoldConnector(  982): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
W/ContextImpl( 6867): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,I/GAv4    ( 6867): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6867):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6867):   adb logcat -s GAv4,
D/VoldConnector(  982): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
W/ContextImpl( 6867): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,D/VoldConnector(  982): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6867): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  982): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6867): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6867): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6867): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6867): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/global  ( 6867): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6867): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6867): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6867): Time to load native libraries: 5 ms (timestamps 9733-9738),
,I/LibraryLoader( 6867): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6867): Binding Chromium to main looper Looper (main, tid 1) {26f14e03}
,I/LibraryLoader( 6867): Expected native library version number "",actual native library version number "",
,I/chromium( 6867): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6867): Initializing chromium process, singleProcess=true
,W/art     ( 6867): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6867): ApplicationContext is null in ApplicationStatus
,W/chromium( 6867): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6867): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6867): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6867): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6867): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6867): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6867): Local Branch: 
I/Adreno-EGL( 6867): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6867): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6867):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6867): Requires BLUETOOTH permission,
,I/NSApplication( 6867): Starting up...,
,D/libc    (  982): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
I/ActivityManager(  982): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6927 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/libc    (  982): [NET] android_getaddrinfofornet-, err=8
,I/ActivityManager(  982): Killing 6443:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  982): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  982): [NET] android_getaddrinfo_proxy+
D/libc    (  982): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
D/Process (  982): killProcessQuiet, pid=6443
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  405): Explicit concurrent mark sweep GC freed 8630(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 260us total 34.960ms,
,D/ConnectivityService(  982): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/art     (  405): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 175us total 22.669ms,
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  982): Find DNS Address www.htc.com/104.81.130.175
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  982): [NET] android_getaddrinfo_proxy-, success
,D/BluetoothAdapter( 6694): 479730363: getState(). Returning 12,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6694): BLE is supported
I/jxcore-log( 6694): 
,I/art     (  405): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 166us total 21.902ms,
,I/ActivityManager(  982): Recipient 6443,
,E/WifiStateMachine(  982): handleMessage: E msg.what=131168,
,E/WifiStateMachine(  982): processMsg: ConnectedState
,E/WifiStateMachine(  982):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  982): processMsg: L2ConnectedState,
E/WifiStateMachine(  982):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
,E/WifiStateMachine(  982):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  982): handleMessage: X
,I/ActivityManager(  982): Killing 6371:com.google.android.gms.unstable/u0a24 (adj 15): empty #18
D/Process (  982): killProcessQuiet, pid=6371
,D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  982): Recipient 6371
,I/AlarmManager(  982): [AlarmQueuing] connectivity wifi: true
D/htcCheckinService(  982): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/PMS     (  982): acquireWL(2bb972b6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 982 1000 null
D/GpsLocationProvider(  982): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  982): acquireWL(dad7bb7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 982 1000 null
I/ConnectivityHelper( 1611): [onReceive] WIFI(1): CONNECTED
D/PMS     (  982): releaseWL(dad7bb7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NetworkMonitor( 6822): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  982): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  982): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,E/GpsLocationProvider(  982): No APN found to select.,
,D/PMS     (  982): releaseWL(2bb972b6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6757): [f86.1.]  listen tmrbb8
,D/MdScDataSum( 6757): [f86.1.] summary 118:p1 ignore
,D/Process (  982): killProcessQuiet, pid=5950,
I/ActivityManager(  982): Killing 5950:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  982): Recipient 5950,
,V/MusicLeanback( 6822): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/MobileConnectivityChangeReceiver( 6415): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6415): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1675): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1675): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1675): service - onStartCommand() screen is off, don't request location
,I/PackageManager(  982):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4440, uid=10024, userID:0
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1971): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1971): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1971): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1971): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4440): [AccountUtils] Account not ready
W/Kids    ( 4440): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4440): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4440): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4440): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4440): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4440): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4440): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4440): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4440): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4440): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4440): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4440): 	at java.lang.Thread.run(Thread.java:818)
,I/RemoteViews( 1236): reapply : com.google.android.gms 2 40
,D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1359): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  982): acquireWL(4cb90fd): PARTIAL_WAKE_LOCK  *alarm* 0x1 982 1000 WorkSource{10024},
V/AlarmManager(  982): sending alarm PendingIntent{318801f2: PendingIntentRecord{3aacc043 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=143781, Int=0
,D/PMS     (  982): acquireWL(14f476c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): releaseWL(4cb90fd): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1971): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1971): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1971): [NET] android_getaddrinfo_proxy+
D/libc    ( 1971): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/PMS     (  982): acquireWL(21104b3e): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6822 10159 null,
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1971): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1971): [NET] android_getaddrinfofornet-, err=8
,I/PackageManager(  982):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6822, uid=10159, userID:0
,D/PMS     (  982): releaseWL(21104b3e): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
,I/MusicLeanback( 6822): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6822): Stop autocaching.
,D/WearableService( 4857): callingUid 10024, callindPid: 4857,
,D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1971): [NET] android_getaddrinfofornet-, err=8
,E/GmsUtils( 6822): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6822): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/PMS     (  982): acquireWL(25791969): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1971): Connected
,D/PMS     (  982): releaseWL(14f476c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): releaseWL(25791969): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  982): acquireWL(2a83ffee): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1971): Message class com.google.f.a.a.p
,D/PMS     (  982): releaseWL(2a83ffee): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/PMS     (  982): acquireWL(3242ac8f): PARTIAL_WAKE_LOCK  *alarm* 0x1 982 1000 WorkSource{10024}
,V/AlarmManager(  982): sending alarm PendingIntent{3c913b1c: PendingIntentRecord{1d80e325 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=145526, Int=0
,D/PMS     (  982): releaseWL(3242ac8f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/GpsLocationProvider(  982): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  982): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  982): acquireWL(28b42cfa): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 982 1000 null
,D/libc    (  982): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, err=8
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  982): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  982): [NET] android_getaddrinfo_proxy+
D/libc    (  982): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  982): [NET] android_getaddrinfo_proxy-, success
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  982): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  982): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  982): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  982):  [handleDownloadXtraData]inject done.
D/PMS     (  982): acquireWL(26881ec6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 982 1000 null
,D/GpsLocationProvider(  982): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  982): releaseWL(28b42cfa): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  982): releaseWL(26881ec6): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1562): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1562): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  982): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  982): acquireWL(34799e87): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 982 1000 WorkSource{1000},
,V/AlarmManager(  982): sending alarm PendingIntent{1112d5aa: PendingIntentRecord{2d9af59b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157774, Int=0
V/AlarmManager(  982): sending alarm PendingIntent{97fd1b4: PendingIntentRecord{228951dd android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1451989212961, Int=0
D/PMS     (  982): acquireWL(39576152): PARTIAL_WAKE_LOCK  *backup* 0x1 982 1000 null
,W/BackupManagerService(  982): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  982): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  982): releaseWL(39576152): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/WeatherUtility( 1236): Weather sync is On
D/PMS     (  982): releaseWL(34799e87): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,D/AutoSetting( 1675): service - handleMessage() stop self,
,D/AutoSetting( 1675): service - onDestroy() END,
D/AutoSetting( 1675): service - handleMessage() quit looper
,E/WifiStateMachine(  982): handleMessage: E msg.what=131165
E/WifiStateMachine(  982): processMsg: ConnectedState
,E/WifiStateMachine(  982):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  982): processMsg: L2ConnectedState
E/WifiStateMachine(  982):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
,E/WifiStateMachine(  982):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  982): handleMessage: X
,D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  982): acquireWL(21479c23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  982): releaseWL(21479c23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/WifiController(  982): battery changed pluggedType: 2
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  982): updateBatteryInfo
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/PMS     (  982): runPSCheck
D/WifiController(  982): handleMessage: E msg.what=155652
D/HtcPowerSaver(  982): Checking...
D/WifiController(  982): processMsg: DeviceActiveState
I/HtcPowerSaver(  982): >> updateStatus
D/WifiController(  982): processMsg: StaEnabledState
D/PowerUI ( 1236): closing low battery warning: level=100
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  982): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1562): switchBindHtcMsgCursor: null,
,E/WifiStateMachine(  982): handleMessage: E msg.what=131326,
E/WifiStateMachine(  982): processMsg: ConnectedState
E/WifiStateMachine(  982):  ConnectedState what:131326 2 0
E/WifiStateMachine(  982): processMsg: L2ConnectedState
E/WifiStateMachine(  982):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  982): handleMessage: X
,D/HtcUPManager( 1236): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcAppUPService( 1675): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@27f650f1
D/HtcUPManager( 1236): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  982): Killing 5867:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  982): killProcessQuiet, pid=5867
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  982): Recipient 5867
,D/PMS     (  982): acquireWL(23225520): PARTIAL_WAKE_LOCK  *alarm* 0x1 982 1000 WorkSource{10024}
V/AlarmManager(  982): sending alarm PendingIntent{224e2ed9: PendingIntentRecord{266409e com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=193585, Int=0
D/PMS     (  982): acquireWL(56dd77f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  982): sending alarm PendingIntent{32a7a34c: PendingIntentRecord{3de9df95 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=212770, Int=0
,D/PMS     (  982): releaseWL(23225520): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  982): acquireWL(20f1c8aa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  982): releaseWL(56dd77f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  982): releaseWL(20f1c8aa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): acquireWL(8950fe4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): releaseWL(8950fe4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  982): acquireWL(a76c4d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): acquireWL(1ad6c302): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): acquireWL(32854650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  982): releaseWL(a76c4d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  982): acquireWL(17720d4e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): releaseWL(17720d4e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1971): Vacuum at: now=1451989255336 tag=VacuumService,
,D/PMS     (  982): releaseWL(1ad6c302): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  982): acquireWL(13f19e6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms},
I/GoogleURLConnFactory( 1971): Using platform SSLCertificateSocketFactory
,W/Uploader( 1971): No account for auth token provided,
,D/PMS     (  982): releaseWL(13f19e6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): acquireWL(d65b05a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): releaseWL(d65b05a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1971): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1971): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1971): [NET] android_getaddrinfo_proxy+
D/libc    ( 1971): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1971): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1971): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1971): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1971): No account for auth token provided,
,W/Uploader( 1971): No account for auth token provided,
,W/Uploader( 1971):  no longer exists, so no auth token.,
,W/Uploader( 1971): No account for auth token provided,
,W/Uploader( 1971): No account for auth token provided,
,I/GLSUser ( 1971): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1971): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1971): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1971): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1359): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1236): reapply : com.google.android.gms 3 40,
,E/Uploader( 1971): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1971): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1971): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1971): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1971): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1971): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1971): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1971): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1971): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1971): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1971): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1971): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1971): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  982): releaseWL(32854650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  982): acquireWL(32dee380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): releaseWL(32dee380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  982): acquireWL(7380db9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  982): releaseWL(7380db9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  982): acquireWL(3d2265fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(3d2265fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  982): updateBatteryInfo,
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  982): plugged=true pluggin=true
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  982): runPSCheck
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  982): Checking...
D/UsbnetService(  982): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  982): >> updateStatus
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/WifiController(  982): battery changed pluggedType: 2
,D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): handleMessage: E msg.what=155652
D/WifiController(  982): processMsg: DeviceActiveState
D/WifiController(  982): processMsg: StaEnabledState
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  982): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1352): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1352): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 1352): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1352): wlan0: BSS: Remove id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1352): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1352): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:96]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:96
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81],
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6694): Connected to the server!
I/jxcore-log( 6694): 
,I/chromium( 6694): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  982): acquireWL(232d015f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 982 1000 WorkSource{1000},
V/AlarmManager(  982): sending alarm PendingIntent{1112d5aa: PendingIntentRecord{2d9af59b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217774, Int=0
,V/AlarmManager(  982): sending alarm PendingIntent{3042cc75: PendingIntentRecord{3e3ae40a com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1451989385209, Int=0
,V/AlarmManager(  982): sending alarm PendingIntent{1a4a547b: PendingIntentRecord{2985a298 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1451989431766, Int=1800000
,D/PMS     (  982): acquireWL(3f00baf1): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4440 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  982): releaseWL(232d015f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  982): acquireWL(a1fbd57): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4440 10024 WorkSource{10024 com.google.android.gms}
D/WeatherUtility( 1236): Weather sync is On
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
D/PMS     (  982): releaseWL(3f00baf1): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4440): Aggregate from 1451989142643 (log), 1451987631723 (data),
,D/PMS     (  982): releaseWL(a1fbd57): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  982): acquireWL(1378d7f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null,
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(1378d7f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  982): updateBatteryInfo
,I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/NotificationService(  982): plugged=true pluggin=true
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
,D/PMS     (  982): runPSCheck
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  982): Checking...
D/UsbnetService(  982): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  982): >> updateStatus
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  982): battery changed pluggedType: 2
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/PowerUI ( 1236): closing low battery warning: level=100,
D/WifiController(  982): handleMessage: E msg.what=155652
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): processMsg: DeviceActiveState
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  982): processMsg: StaEnabledState
I/HtcPowerSaver(  982): << updateStatus
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6694): --- start :testFindPeers.js---
I/jxcore-log( 6694): 
,I/jxcore-log( 6694): testFindPeers created [object Object]
I/jxcore-log( 6694): 
,I/jxcore-log( 6694): serverPort is 8876
I/jxcore-log( 6694): 
,D/BluetoothAdapter( 6694): 479730363: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  982): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6694): start: Peer ID: 90:E7:C4:F6:69:77, peer name: HTC One M8s
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6694): bind: Binding a new listener
D/BluetoothManagerService(  982): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6694): initialize: My bluetooth address is 90:E7:C4:F6:69:77
,D/BluetoothManagerService(  982): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6694): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6694): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  982): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6694): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3119): BTA_JvCreateRecordByUser
D/bt-btm  ( 3119): BTM_AllocateSCN
D/bt-sdp  ( 3119): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 3119): BTA_JvRfcommStartServer
I/bt-btm  ( 3119): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 3119):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6694): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6694): start: OK
I/io.jxcore.node.ConnectionHelper( 6694): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6694): Waiting for incoming connections...
D/BluetoothManagerService(  982): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): start: Peer ID: 90:E7:C4:F6:69:77, peer name: HTC One M8s
,D/BluetoothManagerService(  982): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6694): verifyIdentityString: Identity string created: {"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6694): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): start: {"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6694): start: Identity string: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6694): start: OK
I/jxcore-log( 6694): StartBroadcasting started ok
I/jxcore-log( 6694): 
,I/chromium( 6694): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 6694): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 6694): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService(  982): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@31348cfe target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@31348cfe target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  982): P2pEnabledState add service
D/WifiP2pService(  982): add a new client
,W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 467b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22485443204f6e65204d3873222c227261223a2239303a45373a43343a46363a36393a3737227dc027"
D/wpa_supplicant( 1352): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 467b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22485443204f6e65204d3873222c227261223a2239303a45373a43343a46363a36393a3737227dc027'
I/wpa_supplicant( 1352): [p2p command] (P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 467b227069223a2239303a45373a43343a46363a36393a3737222c22706e223a22485443204f6e65204d3873222c227261223a2239303a45373a43343a46363a36393a3737227dc027)
W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_SERVICE_ADD bonjour 467b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22687463206f6e65206d3873222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65"
,D/wpa_supplicant( 1352): p2p0: Control interface command 'P2P_SERVICE_ADD bonjour 467b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22687463206f6e65206d3873222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65',
D/WifiP2pService(  982): InactiveState{ when=-6ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1352): [p2p command] (P2P_SERVICE_ADD bonjour 467b227069223a2239303a65373a63343a66363a36393a3737222c22706e223a22687463206f6e65206d3873222c227261223a2239303a65373a63343a66363a36393a3737227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65)
D/WifiP2pService(  982): P2pEnabledState{ when=-7ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_FIND 120"
D/WifiP2pService(  982): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6694): Local service added successfully
D/wpa_supplicant( 1352): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1352): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1352): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1352): P2P: Starting find (type=0)
D/wpa_supplicant( 1352): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): P2P: State IDLE -> SEARCH
D/wpa_supplicant( 1352): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * Request Type
D/wpa_supplicant( 1352): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Primary Device Type
D/wpa_supplicant( 1352): WPS:  * RF Bands (3)
D/wpa_supplicant( 1352): WPS:  * Association State
D/wpa_supplicant( 1352): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1352): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1352): WPS:  * Manufacturer
,D/wpa_supplicant( 1352): WPS:  * Model Name
D/wpa_supplicant( 1352): WPS:  * Model Number
D/wpa_supplicant( 1352): WPS:  * Device Name
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-scan'@0x5565afdaa0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-scan'@0x5565afdaa0 after 0.000074 second wait
D/wpa_supplicant( 1352): p2p0: nl80211: scan request
D/wpa_supplicant( 1352): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1352): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 1352): P2P: Running p2p_scan
D/wpa_supplicant( 1352): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1352): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1352): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1352): p2p0: Own scan request started a scan in 0.000091 seconds
I/wpa_supplicant( 1352): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=61 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/wpa_supplicant( 1352): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1352): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1352): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1352): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1352): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1352): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1352): p2p0: Scan completed in 0.392836 seconds
D/wpa_supplicant( 1352): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1352): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
D/wpa_supplicant( 1352): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1352): p2p0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 1352): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-scan'@0x5565afdaa0 done in 0.393725 seconds
D/wpa_supplicant( 1352): P2P: Scan results received (1 BSS)
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x2008
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 1352): P2P: Ignore scan data without P2P Device Info or P2P Device Id
D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): P2P: Starting short listen state (state=SEARCH)
,D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-listen'@0x5565afdaa0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-listen'@0x5565afdaa0 after 0.000065 second wait
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd SET_AP_WPS_P2P_IE 2 len = 0, 190
D/wpa_supplicant( 1352): nl80211: Enable Probe Request reporting nl_preq=0x5565b1d6a0
D/wpa_supplicant( 1352): nl80211: Register frame type=0x40 (WLAN_FC_STYPE_PROBE_REQ) nl_handle=0x5565b1d6a0 match=
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 1352): nl80211: Remain-on-channel cookie 0xffffffc04d181400 for freq=2437 MHz duration=102
,D/wpa_supplicant( 1352): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=102 cookie=0xffffffc04d181400 (match))
D/wpa_supplicant( 1352): p2p0: Event REMAIN_ON_CHANNEL (21) received
D/wpa_supplicant( 1352): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0 pending_action_tx_done=0)
D/wpa_supplicant( 1352): P2P: Starting Listen timeout(0,102400) on freq=2437 based on callback
,D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.122400 sec
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=0a:ec:a9:50:76:28 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=267
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
,D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE,
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
,D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Created device entry based on Probe Req: 0a:ec:a9:50:76:28 dev_capab=0x25 group_capab=0x0 name='Thali Test (Galaxy A3)' listen_freq=2412
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0,
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
,D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 0a:ec:a9:50:76:28 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=0a:ec:a9:50:76:28 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=267
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2,
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
,D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
,D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 0a:ec:a9:50:76:28 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=a2:39:f7:70:12:80 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=254
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
,D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5,
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 11
D/wpa_supplicant( 1352): P2P: Created device entry based on Probe Req: a2:39:f7:70:12:80 dev_capab=0x25 group_capab=0x0 name='G3s-1' listen_freq=2462
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0,
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
,D/wpa_supplicant( 1352): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 11
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
,D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= a2:39:f7:70:12:80 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=215
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE,
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Created device entry based on Probe Req: 02:9a:02:7b:60:ac dev_capab=0x25 group_capab=0x0 name='G3-1' listen_freq=2412
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 02:9a:02:7b:60:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=215
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388,
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
,D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
,D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 02:9a:02:7b:60:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
,D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=215
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
,D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
,D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
,D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 02:9a:02:7b:60:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
,D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=215
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
,D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
,D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 02:9a:02:7b:60:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2,
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): P2P: Driver is still in listen state - stop it
D/wpa_supplicant( 1352): nl80211: Cancel remain-on-channel with cookie 0xffffffc04d181400
,D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry,
D/wpa_supplicant( 1352): nl80211: Disable Probe Request reporting nl_preq=0x888888dded395e29
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-listen'@0x5565afdaa0 done in 0.167561 seconds
D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
,D/wpa_supplicant( 1352): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0xffffffc04d181400 (match))
D/wpa_supplicant( 1352): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (22) received
D/wpa_supplicant( 1352): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
D/wpa_supplicant( 1352): P2P: Driver ended Listen state (freq=2437)
,D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): P2P: Starting search
D/wpa_supplicant( 1352): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * Request Type
D/wpa_supplicant( 1352): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Primary Device Type
,D/wpa_supplicant( 1352): WPS:  * RF Bands (3)
D/wpa_supplicant( 1352): WPS:  * Association State
D/wpa_supplicant( 1352): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1352): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1352): WPS:  * Manufacturer
D/wpa_supplicant( 1352): WPS:  * Model Name
D/wpa_supplicant( 1352): WPS:  * Model Number
D/wpa_supplicant( 1352): WPS:  * Device Name
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20),
D/wpa_supplicant( 1352): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-scan'@0x5565afdaa0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-scan'@0x5565afdaa0 after 0.000051 second wait
D/wpa_supplicant( 1352): p2p0: nl80211: scan request
D/wpa_supplicant( 1352): nl80211: P2P probe - mask SuppRates
,D/wpa_supplicant( 1352): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1352): P2P: Running p2p_scan
D/wpa_supplicant( 1352): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1352): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1352): p2p0: Event SCAN_STARTED (49) received
,D/wpa_supplicant( 1352): p2p0: Own scan request started a scan in 0.000100 seconds
I/wpa_supplicant( 1352): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=63 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1352): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1352): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1352): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1352): nl80211: Scan included frequencies: 2412 2437 2462
D/wpa_supplicant( 1352): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1352): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1352): p2p0: Scan completed in 0.135526 seconds
D/wpa_supplicant( 1352): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1352): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1352): [NULL] 0a:ec:a9:50:76:28 freq=2412 level=-43
I/wpa_supplicant( 1352): [NULL] a2:39:f7:70:12:80 freq=2462 level=-47
I/wpa_supplicant( 1352): [NULL] 7e:f9:0e:37:96:ac freq=2412 level=-50
D/wpa_supplicant( 1352): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1352): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-scan'@0x5565afdaa0 done in 0.136440 seconds
D/wpa_supplicant( 1352): P2P: Scan results received (4 BSS)
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x2008
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 1352): P2P: Ignore scan data without P2P Device Info or P2P Device Id
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/WifiP2pService(  982): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  982):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler },
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  982):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/WifiP2pService(  982): InactiveState{ when=-2ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  982):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 4488
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
,D/WifiP2pService(  982): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  982):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 4488
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 13 length 43
D/WifiDisplayController(  982): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/wpa_supplicant( 1352): P2P: * Device Info: addr 0a:ec:a9:50:76:28 primary device type 10-0050F204-5 device name 'Thali Test (Galaxy A3)' config methods 0x188
D/WifiP2pService(  982): InactiveState{ when=-5ms what=147477 obj=Device: A5-1
D/WifiP2pService(  982):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Update peer 0a:ec:a9:50:76:28 config_methods 0x0 -> 0x188
D/WifiP2pService(  982): P2pEnabledState{ when=-5ms what=147477 obj=Device: A5-1
D/WifiP2pService(  982):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Peer found with Listen frequency 2412 MHz (rx_time=464.858754)
D/WifiDisplayController(  982): Received WIFI_P2P_PEERS_CHANGED_ACTION.
I/wpa_supplicant( 1352): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/WifiP2pService(  982): InactiveState{ when=-1ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/WifiP2pService(  982): DefaultState{ when=-1ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/WifiP2pService(  982): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 13 length 26
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1352): P2P: * Device Info: addr a2:39:f7:70:12:80 primary device type 10-0050F204-5 device name 'G3s-1' config methods 0x1188
D/WifiP2pService(  982): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Update peer a2:39:f7:70:12:80 config_methods 0x0 -> 0x1188
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Peer found with Listen frequency 2462 MHz (rx_time=464.858754)
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1352): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/WifiDisplayController(  982): Received list of peers.
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/WifiDisplayController(  982):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Attribute 13 length 25
D/WifiDisplayController(  982):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: * Device Info: addr 7e:f9:0e:37:96:ac primary device type 10-0050F204-5 device name 'A5-1' config methods 0x188
D/WifiDisplayController(  982): Received list of peers.
D/wpa_supplicant( 1352): P2P: Update peer 7e:f9:0e:37:96:ac config_methods 0x0 -> 0x188
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Peer found with Listen frequency 2412 MHz (rx_time=464.858754)
D/WifiDisplayController(  982):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
I/wpa_supplicant( 1352): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiDisplayController(  982):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
,D/WifiDisplayController(  982): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/wpa_supplicant( 1352): P2P: Starting short listen state (state=SEARCH)
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  982): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1]
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  982): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1]
D/WifiDisplayController(  982): Received list of peers.
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/WifiMonitor(  982): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1]
D/WifiDisplayController(  982):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiDisplayController(  982):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
,D/WifiP2pService(  982): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/WifiP2pService(  982): P2pEnabledState add service request
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-listen'@0x5565b24a80
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-listen'@0x5565b24a80 after 0.000082 second wait
,D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd SET_AP_WPS_P2P_IE 2 len = 0, 190
D/wpa_supplicant( 1352): nl80211: Enable Probe Request reporting nl_preq=0x5565b25580
D/wpa_supplicant( 1352): nl80211: Register frame type=0x40 (WLAN_FC_STYPE_PROBE_REQ) nl_handle=0x5565b25580 match=
D/wpa_supplicant( 1352): nl80211: Remain-on-channel cookie 0xffffffc04d183000 for freq=2437 MHz duration=307
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/WifiP2pManager( 6694): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): Service request added successfully
D/wpa_supplicant( 1352): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=307 cookie=0xffffffc04d183000 (match))
D/wpa_supplicant( 1352): p2p0: Event REMAIN_ON_CHANNEL (21) received
D/wpa_supplicant( 1352): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0 pending_action_tx_done=0)
D/wpa_supplicant( 1352): P2P: Starting Listen timeout(0,307200) on freq=2437 based on callback
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.327200 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=0a:ec:a9:50:75:42 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=249
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
,D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Created device entry based on Probe Req: 0a:ec:a9:50:75:42 dev_capab=0x25 group_capab=0x0 name='A3-1' listen_freq=2412
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE,
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header,
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 0a:ec:a9:50:75:42 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=44:80:eb:7b:5a:07 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=222
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Created device entry based on Probe Req: 44:80:eb:7b:5a:07 dev_capab=0x21 group_capab=0x0 name='XT1072_23d5' listen_freq=2437
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 44:80:eb:7b:5a:07 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
,D/wpa_supplicant( 1352): nl80211: RX frame sa=44:80:eb:7b:5a:07 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=222
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
,D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
,D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 44:80:eb:7b:5a:07 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=44:80:eb:7b:5a:07 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=222
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
,D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
,D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 44:80:eb:7b:5a:07 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
,D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=44:80:eb:7b:5a:07 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=222
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
,D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
,D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 44:80:eb:7b:5a:07 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=44:80:eb:7b:5a:07 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=222
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 44:80:eb:7b:5a:07 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
,D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=a2:39:f7:6f:c9:5d freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=279
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
,D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country DC(0x04) Regulatory Class 81 Channel Number 11
D/wpa_supplicant( 1352): P2P: Created device entry based on Probe Req: a2:39:f7:6f:c9:5d dev_capab=0x25 group_capab=0x0 name='G4-1' listen_freq=2462
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
,D/wpa_supplicant( 1352): P2P: * Listen Channel: Country DC(0x04) Regulatory Class 81 Channel Number 11
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= a2:39:f7:6f:c9:5d noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=a2:39:f7:70:12:80 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=250
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 11
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 11
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
,D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= a2:39:f7:70:12:80 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=215
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 02:9a:02:7b:60:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=215
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 02:9a:02:7b:60:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
,D/wpa_supplicant( 1352): nl80211: RX frame sa=0a:ec:a9:50:76:28 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=267
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5,
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 0a:ec:a9:50:76:28 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2,
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=215
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
,D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 02:9a:02:7b:60:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
,D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=215
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
,D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state,
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 02:9a:02:7b:60:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
,D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=215
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
,D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
,D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country CZ(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 02:9a:02:7b:60:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=0a:ec:a9:50:76:28 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=267
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
,D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
,D/wpa_supplicant( 1352): nl80211: send_mlme - da= 0a:ec:a9:50:76:28 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=44:80:eb:7b:5a:07 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=222
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
,D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 44:80:eb:7b:5a:07 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=44:80:eb:7b:5a:07 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=222
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
,D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
,D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
,D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 44:80:eb:7b:5a:07 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
,D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=44:80:eb:7b:5a:07 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=222
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
,D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 21 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country US(0x04) Regulatory Class 81 Channel Number 6
,D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 44:80:eb:7b:5a:07 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
,D/wpa_supplicant( 1352): nl80211: RX frame sa=7e:f9:0e:51:18:23 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=267
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
,D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Created device entry based on Probe Req: 7e:f9:0e:51:18:23 dev_capab=0x25 group_capab=0x0 name='Thali Test (Galaxy A5)' listen_freq=2412
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
,D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 7e:f9:0e:51:18:23 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=7e:f9:0e:37:96:ac freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=249
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
,D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= 7e:f9:0e:37:96:ac noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH)
D/wpa_supplicant( 1352): P2P: Driver is still in listen state - stop it
,D/wpa_supplicant( 1352): nl80211: Cancel remain-on-channel with cookie 0xffffffc04d183000
,D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): nl80211: Disable Probe Request reporting nl_preq=0x888888dded3add09
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-listen'@0x5565b24a80 done in 0.372937 seconds
D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
D/wpa_supplicant( 1352): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
,D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0xffffffc04d183000 (match))
D/wpa_supplicant( 1352): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (22) received
D/wpa_supplicant( 1352): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
D/wpa_supplicant( 1352): P2P: Driver ended Listen state (freq=2437)
D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): P2P: Starting search,
D/wpa_supplicant( 1352): WPS: Building WPS IE for Probe Request
,D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * Request Type
,D/wpa_supplicant( 1352): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1352): WPS:  * UUID-E
,D/wpa_supplicant( 1352): WPS:  * Primary Device Type
D/wpa_supplicant( 1352): WPS:  * RF Bands (3)
,D/wpa_supplicant( 1352): WPS:  * Association State
D/wpa_supplicant( 1352): WPS:  * Configuration Error (0)
,D/wpa_supplicant( 1352): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1352): WPS:  * Manufacturer,
D/wpa_supplicant( 1352): WPS:  * Model Name
D/wpa_supplicant( 1352): WPS:  * Model Number
,D/wpa_supplicant( 1352): WPS:  * Device Name
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 1352): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1352): P2P: * P2P IE header
,D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Listen Channel: Regulatory Class 81 Channel 6,
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-scan'@0x5565b228d0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-scan'@0x5565b228d0 after 0.000081 second wait
,D/wpa_supplicant( 1352): p2p0: nl80211: scan request
D/wpa_supplicant( 1352): nl80211: P2P probe - mask SuppRates
,D/wpa_supplicant( 1352): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1352): P2P: Running p2p_scan
D/wpa_supplicant( 1352): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1352): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1352): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1352): p2p0: Own scan request started a scan in 0.000162 seconds
I/wpa_supplicant( 1352): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=67 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1352): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1352): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1352): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1352): nl80211: Scan included frequencies: 2412 2437 2462
D/wpa_supplicant( 1352): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1352): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1352): p2p0: Scan completed in 0.109292 seconds
D/wpa_supplicant( 1352): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 1352): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1352): [NULL] 0a:ec:a9:50:76:28 freq=2412 level=-43
I/wpa_supplicant( 1352): [NULL] a2:39:f7:70:12:80 freq=2462 level=-47
I/wpa_supplicant( 1352): [NULL] 7e:f9:0e:37:96:ac freq=2412 level=-50
I/wpa_supplicant( 1352): [NULL] 52:55:27:f0:fd:0b freq=2437 level=-58
D/wpa_supplicant( 1352): p2p0: BSS: Start scan result update 3
D/wpa_supplicant( 1352): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-scan'@0x5565b228d0 done in 0.110763 seconds
D/wpa_supplicant( 1352): P2P: Scan results received (5 BSS)
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x2008
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 1352): P2P: Ignore scan data without P2P Device Info or P2P Device Id
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 13 length 43
D/wpa_supplicant( 1352): P2P: * Device Info: addr 0a:ec:a9:50:76:28 primary device type 10-0050F204-5 device name 'Thali Test (Galaxy A3)' config methods 0x188
D/wpa_supplicant( 1352): P2P: Do not update peer entry based on old frame (rx_time=464.857126 last_seen=465.192973)
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00,
D/wpa_supplicant( 1352): P2P: Attribute 13 length 26
D/WifiP2pService(  982): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  982):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: * Device Info: addr a2:39:f7:70:12:80 primary device type 10-0050F204-5 device name 'G3s-1' config methods 0x1188
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  982):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Do not update peer entry based on old frame (rx_time=464.857126 last_seen=465.026668)
D/WifiDisplayController(  982): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/WifiP2pService(  982): DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/WifiDisplayController(  982): Received list of peers.
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/WifiDisplayController(  982):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
,D/wpa_supplicant( 1352): P2P: Attribute 13 length 25
D/WifiDisplayController(  982):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: * Device Info: addr 7e:f9:0e:37:96:ac primary device type 10-0050F204-5 device name 'A5-1' config methods 0x188
D/WifiDisplayController(  982):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Do not update peer entry based on old frame (rx_time=464.857126 last_seen=465.213770)
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/WifiP2pService(  982): DefaultState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
,D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 13 length 33
D/wpa_supplicant( 1352): P2P: * Device Info: addr 52:55:27:f0:fd:0b primary device type 10-0050F204-5 device name 'Android_8ae2' config methods 0x188
D/wpa_supplicant( 1352): P2P: Update peer 52:55:27:f0:fd:0b config_methods 0x0 -> 0x188
D/wpa_supplicant( 1352): P2P: Peer found with Listen frequency 2437 MHz (rx_time=465.847126)
,I/wpa_supplicant( 1352): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): P2P: Starting short listen state (state=SEARCH)
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-listen'@0x5565b22e50
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-listen'@0x5565b22e50 after 0.000077 second wait
,D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd SET_AP_WPS_P2P_IE 2 len = 0, 190
D/wpa_supplicant( 1352): nl80211: Enable Probe Request reporting nl_preq=0x5565b25580
D/wpa_supplicant( 1352): nl80211: Register frame type=0x40 (WLAN_FC_STYPE_PROBE_REQ) nl_handle=0x5565b25580 match=
D/wpa_supplicant( 1352): nl80211: Remain-on-channel cookie 0xffffffc04d181400 for freq=2437 MHz duration=307
D/WifiMonitor(  982): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1]
,E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b,
,D/wpa_supplicant( 1352): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=307 cookie=0xffffffc04d181400 (match))
D/wpa_supplicant( 1352): p2p0: Event REMAIN_ON_CHANNEL (21) received
D/wpa_supplicant( 1352): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0 pending_action_tx_done=0)
D/wpa_supplicant( 1352): P2P: Starting Listen timeout(0,307200) on freq=2437 based on callback
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.327200 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/WifiP2pService(  982): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): nl80211: RX frame sa=a2:39:f7:70:12:80 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=250
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/WifiP2pService(  982): P2pEnabledState discover services
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 11
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
,D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 11
,D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
,D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= a2:39:f7:70:12:80 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01"
D/wpa_supplicant( 1352): p2p0: Control interface command 'P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01'
I/wpa_supplicant( 1352): [p2p command] (P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01)
,D/wpa_supplicant( 1352): P2P: Added SD Query 0x5565b21120
W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_FIND 120"
D/wpa_supplicant( 1352): p2p0: Control interface command 'P2P_FIND 120'
I/wpa_supplicant( 1352): [p2p command] (P2P_FIND 120)
D/wpa_supplicant( 1352): p2p0: P2P: Use 500 ms search delay due to concurrent operation on interface wlan0
D/wpa_supplicant( 1352): P2P: Starting find (type=0)
,D/wpa_supplicant( 1352): P2P: Clear timeout (state=SEARCH)
D/wpa_supplicant( 1352): nl80211: Cancel remain-on-channel with cookie 0xffffffc04d181400
,D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): nl80211: Disable Probe Request reporting nl_preq=0x888888dded3add09
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-listen'@0x5565b22e50 done in 0.057514 seconds
D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 1352): WPS:  * Request Type
D/wpa_supplicant( 1352): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Primary Device Type
D/wpa_supplicant( 1352): WPS:  * RF Bands (3)
D/wpa_supplicant( 1352): WPS:  * Association State
D/wpa_supplicant( 1352): WPS:  * Configuration Error (0)
,D/wpa_supplicant( 1352): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1352): WPS:  * Manufacturer
D/wpa_supplicant( 1352): WPS:  * Model Name
D/wpa_supplicant( 1352): WPS:  * Model Number
D/wpa_supplicant( 1352): WPS:  * Device Name
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
,D/wpa_supplicant( 1352): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-scan'@0x5565b22950
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-scan'@0x5565b22950 after 0.000107 second wait
D/wpa_supplicant( 1352): p2p0: nl80211: scan request
D/wpa_supplicant( 1352): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1352): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1352): P2P: Running p2p_scan
D/wpa_supplicant( 1352): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0xffffffc04d181400 (match))
D/wpa_supplicant( 1352): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (22) received
,D/wpa_supplicant( 1352): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
D/wpa_supplicant( 1352): P2P: Driver ended Listen state (freq=2437)
D/wpa_supplicant( 1352): P2P: Skip stop_listen since not in listen_only state.
D/wpa_supplicant( 1352): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1352): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1352): p2p0: Event SCAN_STARTED (49) received
,D/wpa_supplicant( 1352): p2p0: Own scan request started a scan in 0.000205 seconds
I/wpa_supplicant( 1352): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=69 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): Service discovery started successfully
,D/wpa_supplicant( 1352): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1352): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1352): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1352): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1352): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1352): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1352): p2p0: Scan completed in 0.369948 seconds
D/wpa_supplicant( 1352): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 1352): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1352): [NULL] 0a:ec:a9:50:76:28 freq=2412 level=-43,
I/wpa_supplicant( 1352): [NULL] a2:39:f7:70:12:80 freq=2462 level=-47
I/wpa_supplicant( 1352): [NULL] 7e:f9:0e:37:96:ac freq=2412 level=-50
I/wpa_supplicant( 1352): [NULL] 52:55:27:f0:fd:0b freq=2437 level=-58
D/wpa_supplicant( 1352): p2p0: BSS: Start scan result update 4
,D/wpa_supplicant( 1352): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-scan'@0x5565b22950 done in 0.371075 seconds
D/wpa_supplicant( 1352): P2P: Scan results received (5 BSS)
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x2008
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
,D/wpa_supplicant( 1352): P2P: Ignore scan data without P2P Device Info or P2P Device Id
D/wpa_supplicant( 1352): P2P: Ignore old scan result for 0a:ec:a9:50:76:28 (rx_time=464.859735)
D/wpa_supplicant( 1352): P2P: Ignore old scan result for a2:39:f7:70:12:80 (rx_time=464.859735)
D/wpa_supplicant( 1352): P2P: Ignore old scan result for 7e:f9:0e:37:96:ac (rx_time=464.859735)
D/wpa_supplicant( 1352): P2P: Ignore old scan result for 52:55:27:f0:fd:0b (rx_time=465.849735)
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 52:55:27:f0:fd:0b
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b22ca0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b22ca0 after 0.000166 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2437 dst=52:55:27:f0:fd:0b src=92:e7:c4:e6:4c:f8 bssid=52:55:27:f0:fd:0b len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2437 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=52:55:27:f0:fd:0b type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2437 dst=52:55:27:f0:fd:0b src=92:e7:c4:e6:4c:f8 bssid=52:55:27:f0:fd:0b result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b22ca0 done in 0.032617 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 7e:f9:0e:51:18:23
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b22e40
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b22e40 after 0.000102 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=7e:f9:0e:51:18:23 src=92:e7:c4:e6:4c:f8 bssid=7e:f9:0e:51:18:23 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04975fa00 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=7e:f9:0e:51:18:23 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=7e:f9:0e:51:18:23 src=92:e7:c4:e6:4c:f8 bssid=7e:f9:0e:51:18:23 result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
,D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=7e:f9:0e:51:18:23 freq=2412 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=152
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=7e:f9:0e:51:18:23 Category=4 DataLen=127 freq=2412 MHz
D/wpa_supplicant( 1352): GAS: No pending query found for 7e:f9:0e:51:18:23 dialog token 0,
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b22e40 done in 0.045274 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04975fa00
,D/wpa_supplicant( 1352): P2P: Clear timeout (state=SD_DURING_FIND),
D/wpa_supplicant( 1352): P2P: Received GAS Initial Response from 7e:f9:0e:51:18:23 (len=126)
D/wpa_supplicant( 1352): P2P: dialog_token=0 status_code=0 comeback_delay=0
D/wpa_supplicant( 1352): P2P: Query Response Length: 115
D/wpa_supplicant( 1352): P2P: Service Update Indicator: 3
D/wpa_supplicant( 1352): P2P: Service Response TLV
D/wpa_supplicant( 1352): P2P: Service Protocol Type 1
D/wpa_supplicant( 1352): P2P: Service Transaction ID 1
,D/wpa_supplicant( 1352): P2P: Status Code ID 0
D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:6f:c9:5d
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000097 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
D/WifiMonitor(  982): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000101000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=70 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000101000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
,D/WifiP2pService(  982): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6694): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6694): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 6694): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 6694): 
I/jxcore-log( 6694): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 6694): 
I/jxcore-log( 6694): weAreDoneNow
I/jxcore-log( 6694): 
I/jxcore-log( 6694): done, now sending data to server
I/jxcore-log( 6694): 
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=7e:f9:0e:51:18:23 freq=2412 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=152
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=7e:f9:0e:51:18:23 Category=4 DataLen=127 freq=2412 MHz
D/wpa_supplicant( 1352): GAS: No pending query found for 7e:f9:0e:51:18:23 dialog token 0
D/wpa_supplicant( 1352): P2P: Ignore unexpected GAS Initial Response from 7e:f9:0e:51:18:23
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
,D/wpa_supplicant( 1352): nl80211: Frame TX status event,
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04975c800 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:6f:c9:5d type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.040436 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04975c800
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 44:80:eb:7b:5a:07
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000068 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2437 dst=44:80:eb:7b:5a:07 src=92:e7:c4:e6:4c:f8 bssid=44:80:eb:7b:5a:07 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2437 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=44:80:eb:7b:5a:07 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2437 dst=44:80:eb:7b:5a:07 src=92:e7:c4:e6:4c:f8 bssid=44:80:eb:7b:5a:07 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.016644 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 0a:ec:a9:50:75:42
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=0a:ec:a9:50:75:42 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:75:42 len=39,
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=0a:ec:a9:50:75:42 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=0a:ec:a9:50:75:42 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:75:42 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.013005 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 7e:f9:0e:37:96:ac
,D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=7e:f9:0e:37:96:ac src=92:e7:c4:e6:4c:f8 bssid=7e:f9:0e:37:96:ac len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=7e:f9:0e:37:96:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=7e:f9:0e:37:96:ac src=92:e7:c4:e6:4c:f8 bssid=7e:f9:0e:37:96:ac result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=7e:f9:0e:37:96:ac freq=2412 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=134
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=7e:f9:0e:37:96:ac Category=4 DataLen=109 freq=2412 MHz
D/wpa_supplicant( 1352): GAS: No pending query found for 7e:f9:0e:37:96:ac dialog token 0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.020581 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: Clear timeout (state=SD_DURING_FIND),
D/WifiP2pService(  982): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Received GAS Initial Response from 7e:f9:0e:37:96:ac (len=108)
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: dialog_token=0 status_code=0 comeback_delay=0
,D/WifiP2pService(  982): P2pEnabledState receive service response
D/wpa_supplicant( 1352): P2P: Query Response Length: 97
D/wpa_supplicant( 1352): P2P: Service Update Indicator: 3
D/wpa_supplicant( 1352): P2P: Service Response TLV
D/wpa_supplicant( 1352): P2P: Service Protocol Type 1
D/wpa_supplicant( 1352): P2P: Service Transaction ID 1,
D/wpa_supplicant( 1352): P2P: Status Code ID 0
D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
D/WifiMonitor(  982): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6694): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6694): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018304 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
,D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183400 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1,
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022538 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183400
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 0a:ec:a9:50:76:28
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000071 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=0a:ec:a9:50:76:28 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:76:28 len=39,
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=0a:ec:a9:50:76:28 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=0a:ec:a9:50:76:28 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:76:28 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.019519 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 52:55:27:f0:fd:0b
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2437 dst=52:55:27:f0:fd:0b src=92:e7:c4:e6:4c:f8 bssid=52:55:27:f0:fd:0b len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2437 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=52:55:27:f0:fd:0b type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2437 dst=52:55:27:f0:fd:0b src=92:e7:c4:e6:4c:f8 bssid=52:55:27:f0:fd:0b result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016924 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:6f:c9:5d
,D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000065 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183400 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:6f:c9:5d type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.019018 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183400
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
,D/wpa_supplicant( 1352): P2P: Start Service Discovery with 44:80:eb:7b:5a:07
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2437 dst=44:80:eb:7b:5a:07 src=92:e7:c4:e6:4c:f8 bssid=44:80:eb:7b:5a:07 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2437 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=44:80:eb:7b:5a:07 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2437 dst=44:80:eb:7b:5a:07 src=92:e7:c4:e6:4c:f8 bssid=44:80:eb:7b:5a:07 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016972 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 0a:ec:a9:50:75:42
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=0a:ec:a9:50:75:42 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:75:42 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=52:55:27:f0:fd:0b freq=2437 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=137
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=52:55:27:f0:fd:0b Category=4 DataLen=112 freq=2437 MHz
D/wpa_supplicant( 1352): GAS: No pending query found for 52:55:27:f0:fd:0b dialog token 0
D/wpa_supplicant( 1352): P2P: Ignore unexpected GAS Initial Response from 52:55:27:f0:fd:0b
D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=0a:ec:a9:50:75:42 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=0a:ec:a9:50:75:42 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:75:42 result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=0a:ec:a9:50:75:42 freq=2412 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=134
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=0a:ec:a9:50:75:42 Category=4 DataLen=109 freq=2412 MHz
,D/wpa_supplicant( 1352): GAS: No pending query found for 0a:ec:a9:50:75:42 dialog token 0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.045457 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: Clear timeout (state=SD_DURING_FIND),
D/WifiP2pService(  982): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Received GAS Initial Response from 0a:ec:a9:50:75:42 (len=108)
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler },
D/wpa_supplicant( 1352): P2P: dialog_token=0 status_code=0 comeback_delay=0
D/WifiP2pService(  982): P2pEnabledState receive service response
D/wpa_supplicant( 1352): P2P: Query Response Length: 97
D/wpa_supplicant( 1352): P2P: Service Update Indicator: 3
D/wpa_supplicant( 1352): P2P: Service Response TLV
D/wpa_supplicant( 1352): P2P: Service Protocol Type 1
,D/wpa_supplicant( 1352): P2P: Service Transaction ID 1
D/wpa_supplicant( 1352): P2P: Status Code ID 0
D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000059 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
D/WifiMonitor(  982): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=72 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6694): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6694): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.029900 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022964 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 0a:ec:a9:50:76:28
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=0a:ec:a9:50:76:28 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:76:28 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=0a:ec:a9:50:76:28 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=0a:ec:a9:50:76:28 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:76:28 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012434 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 52:55:27:f0:fd:0b
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000079 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2437 dst=52:55:27:f0:fd:0b src=92:e7:c4:e6:4c:f8 bssid=52:55:27:f0:fd:0b len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2437 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=52:55:27:f0:fd:0b type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2437 dst=52:55:27:f0:fd:0b src=92:e7:c4:e6:4c:f8 bssid=52:55:27:f0:fd:0b result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=52:55:27:f0:fd:0b freq=2437 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=137
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=52:55:27:f0:fd:0b Category=4 DataLen=112 freq=2437 MHz
D/wpa_supplicant( 1352): GAS: No pending query found for 52:55:27:f0:fd:0b dialog token 0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.024410 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: Clear timeout (state=SD_DURING_FIND),
D/WifiP2pService(  982): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Received GAS Initial Response from 52:55:27:f0:fd:0b (len=111)
,D/WifiP2pService(  982): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: dialog_token=0 status_code=0 comeback_delay=0
D/WifiP2pService(  982): P2pEnabledState receive service response
D/wpa_supplicant( 1352): P2P: Query Response Length: 100,
D/wpa_supplicant( 1352): P2P: Service Update Indicator: 3
D/wpa_supplicant( 1352): P2P: Service Response TLV
D/wpa_supplicant( 1352): P2P: Service Protocol Type 1
D/wpa_supplicant( 1352): P2P: Service Transaction ID 1
,D/wpa_supplicant( 1352): P2P: Status Code ID 0
D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:6f:c9:5d
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000059 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/WifiMonitor(  982): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224e657875732035222c227261223a2233343a46433a45463a31313a41453a3637227dc027]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224e657875732035222c227261223a2233343a46433a45463a31313a41453a3637227dc027
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 6694): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b,
D/io.jxcore.node.ConnectionHelper( 6694): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:6f:c9:5d type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.016700 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 44:80:eb:7b:5a:07
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2437 dst=44:80:eb:7b:5a:07 src=92:e7:c4:e6:4c:f8 bssid=44:80:eb:7b:5a:07 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2437 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=44:80:eb:7b:5a:07 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2437 dst=44:80:eb:7b:5a:07 src=92:e7:c4:e6:4c:f8 bssid=44:80:eb:7b:5a:07 result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND,
D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0
D/wpa_supplicant( 1352): nl80211: RX frame sa=44:80:eb:7b:5a:07 freq=2437 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=136
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
,D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=44:80:eb:7b:5a:07 Category=4 DataLen=111 freq=2437 MHz
D/wpa_supplicant( 1352): GAS: No pending query found for 44:80:eb:7b:5a:07 dialog token 0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.017083 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: Clear timeout (state=SD_DURING_FIND),
D/WifiP2pService(  982): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Received GAS Initial Response from 44:80:eb:7b:5a:07 (len=110)
,D/WifiP2pService(  982): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: dialog_token=0 status_code=0 comeback_delay=0
D/WifiP2pService(  982): P2pEnabledState receive service response
D/wpa_supplicant( 1352): P2P: Query Response Length: 99
,D/wpa_supplicant( 1352): P2P: Service Update Indicator: 3
D/wpa_supplicant( 1352): P2P: Service Response TLV
D/wpa_supplicant( 1352): P2P: Service Protocol Type 1
D/wpa_supplicant( 1352): P2P: Service Transaction ID 1
D/wpa_supplicant( 1352): P2P: Status Code ID 0
,D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000059 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/WifiMonitor(  982): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 3 57000101000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=74 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 3 57000101000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 6694): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: , device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 6694): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018718 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000078 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022509 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 0a:ec:a9:50:76:28
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=0a:ec:a9:50:76:28 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:76:28 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=0a:ec:a9:50:76:28 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=0a:ec:a9:50:76:28 src=92:e7:c4:e6:4c:f8 bssid=0a:ec:a9:50:76:28 result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): P2P: Timeout (state=SD_DURING_FIND),
D/wpa_supplicant( 1352): P2P: Service Discovery Query timeout
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.216213 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:6f:c9:5d
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000052 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:6f:c9:5d type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.022400 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181c00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.018466 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181c00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000066 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1,
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.024136 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:6f:c9:5d
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20980
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20980 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:6f:c9:5d type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:6f:c9:5d src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:6f:c9:5d result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
,D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=a2:39:f7:6f:c9:5d freq=2462 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=134
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=a2:39:f7:6f:c9:5d Category=4 DataLen=109 freq=2462 MHz
D/wpa_supplicant( 1352): GAS: No pending query found for a2:39:f7:6f:c9:5d dialog token 0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20980 done in 0.060477 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: Clear timeout (state=SD_DURING_FIND)
D/WifiP2pService(  982): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Received GAS Initial Response from a2:39:f7:6f:c9:5d (len=108)
,D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: dialog_token=0 status_code=0 comeback_delay=0
D/WifiP2pService(  982): P2pEnabledState receive service response
D/wpa_supplicant( 1352): P2P: Query Response Length: 97
D/wpa_supplicant( 1352): P2P: Service Update Indicator: 3
D/wpa_supplicant( 1352): P2P: Service Response TLV,
D/wpa_supplicant( 1352): P2P: Service Protocol Type 1
D/wpa_supplicant( 1352): P2P: Service Transaction ID 1
D/wpa_supplicant( 1352): P2P: Status Code ID 0
D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH
,D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000096 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/WifiMonitor(  982): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6694): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6694): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc06632cc00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018990 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc06632cc00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000054 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13,
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016361 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000,
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0,
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.020051 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
,D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13,
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016877 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000064 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012372 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
,D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1),
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016529 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012539 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016443 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012360 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.021332 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012189 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000099 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc06632ea00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.023010 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification,
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc06632ea00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018986 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification,
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000065 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016504 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1,
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012496 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1,
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016529 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012675 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.017171 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018557 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait,
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1,
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016404 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000064 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012464 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181c00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022355 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181c00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000098 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc06632d800 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.030039 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification,
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc06632d800
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022515 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183400 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018591 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183400
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80,
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022880 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00,
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018455 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.021682 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13,
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0,
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.019249 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016558 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012938 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016355 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
,D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012716 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60,
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39,
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1,
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016257 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
,D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012416 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60,
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.024535 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000064 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012408 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification,
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016245 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0,
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012161 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13,
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022769 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000059 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018630 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1),
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022428 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait,
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012402 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016322 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0,
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012639 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016409 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
,D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.016883 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000065 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016267 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0,
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
,D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018581 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1,
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022660 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1),
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018966 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000,
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016702 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification,
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.017320 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022531 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012405 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.023041 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000065 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012728 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13,
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.017493 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012705 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.017183 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000073 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183400 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.013234 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183400
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016748 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1),
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018738 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183400 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022667 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183400
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39,
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.019058 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000098 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39,
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc06632f600 (match) (ack=0)
,D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.023716 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc06632f600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000071 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012986 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000065 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022935 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018459 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022495 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0,
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018800 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000,
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60,
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13,
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016583 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012746 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200,
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
,D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016753 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181c00 (match) (ack=0)
,D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.013050 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181c00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.023084 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
,D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012834 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00,
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016598 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.019084 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016317 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000062 second wait,
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018691 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000066 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022476 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181e00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012632 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181e00,
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016457 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification,
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000100 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1),
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04975dc00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018685 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04975dc00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022929 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.015944 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.023166 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1,
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018798 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181c00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.028212 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification,
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181c00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018246 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016555 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181c00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.012342 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181c00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016511 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification,
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait,
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183400 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0,
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.019051 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183400
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60,
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000060 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181c00 (match) (ack=0)
,D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016946 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181c00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
,D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000136 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.019010 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39,
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022321 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181c00 (match) (ack=0)
,D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018586 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181c00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016683 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification,
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018442 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000065 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181c00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame,
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.022809 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181c00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000099 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc06632ce00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
,D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.030733 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc06632ce00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181200 (match) (ack=0)
,D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
,D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.017003 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
,D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
,D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018439 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.016272 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000063 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181200 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754,
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.018677 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181200
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000062 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received,
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.021307 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 02:9a:02:7b:60:ac
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0,
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000065 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=02:9a:02:7b:60:ac type=0 stype=13,
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=02:9a:02:7b:60:ac src=92:e7:c4:e6:4c:f8 bssid=02:9a:02:7b:60:ac result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1,
D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=02:9a:02:7b:60:ac freq=2412 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=134
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=02:9a:02:7b:60:ac Category=4 DataLen=109 freq=2412 MHz
,D/wpa_supplicant( 1352): GAS: No pending query found for 02:9a:02:7b:60:ac dialog token 0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.044921 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600,
,D/wpa_supplicant( 1352): P2P: Clear timeout (state=SD_DURING_FIND),
D/WifiP2pService(  982): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Received GAS Initial Response from 02:9a:02:7b:60:ac (len=108)
,D/WifiP2pService(  982): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: dialog_token=0 status_code=0 comeback_delay=0
D/WifiP2pService(  982): P2pEnabledState receive service response
,D/wpa_supplicant( 1352): P2P: Query Response Length: 97
D/wpa_supplicant( 1352): P2P: Service Update Indicator: 3
D/wpa_supplicant( 1352): P2P: Service Response TLV
D/wpa_supplicant( 1352): P2P: Service Protocol Type 1,
D/wpa_supplicant( 1352): P2P: Service Transaction ID 1
D/wpa_supplicant( 1352): P2P: Status Code ID 0
D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH
,D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
,D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000061 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
D/WifiMonitor(  982): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 02:9a:02:7b:60:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-SERV-DISC-RESP 02:9a:02:7b:60:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6694): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 6694): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.034357 seconds,
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20a60 after 0.000064 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d183000 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20a60 done in 0.037450 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d183000
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with a2:39:f7:70:12:80
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565affac0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565affac0 after 0.000064 second wait,
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2462 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d181600 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=a2:39:f7:70:12:80 type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
,D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2462 dst=a2:39:f7:70:12:80 src=92:e7:c4:e6:4c:f8 bssid=a2:39:f7:70:12:80 result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=a2:39:f7:70:12:80 freq=2462 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=135
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=a2:39:f7:70:12:80 Category=4 DataLen=110 freq=2462 MHz
D/wpa_supplicant( 1352): GAS: No pending query found for a2:39:f7:70:12:80 dialog token 0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565affac0 done in 0.026401 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d181600
,D/wpa_supplicant( 1352): P2P: Clear timeout (state=SD_DURING_FIND)
D/WifiP2pService(  982): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Received GAS Initial Response from a2:39:f7:70:12:80 (len=109)
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: dialog_token=0 status_code=0 comeback_delay=0
D/WifiP2pService(  982): P2pEnabledState receive service response
D/wpa_supplicant( 1352): P2P: Query Response Length: 98
D/wpa_supplicant( 1352): P2P: Service Update Indicator: 3
D/wpa_supplicant( 1352): P2P: Service Response TLV
D/wpa_supplicant( 1352): P2P: Service Protocol Type 1
D/wpa_supplicant( 1352): P2P: Service Transaction ID 1
D/wpa_supplicant( 1352): P2P: Status Code ID 0
D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH
D/wpa_supplicant( 1352): P2P: Starting short listen state (state=SEARCH)
D/WifiMonitor(  982): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000101000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=77 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000101000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-listen'@0x5565affa60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-listen'@0x5565affa60 after 0.000106 second wait
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd SET_AP_WPS_P2P_IE 2 len = 0, 190
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/wpa_supplicant( 1352): nl80211: Enable Probe Request reporting nl_preq=0x5565b22820
D/wpa_supplicant( 1352): nl80211: Register frame type=0x40 (WLAN_FC_STYPE_PROBE_REQ) nl_handle=0x5565b22820 match=
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
D/wpa_supplicant( 1352): nl80211: Remain-on-channel cookie 0xffffffc06632f600 for freq=2437 MHz duration=307
,I/io.jxcore.node.ConnectionHelper( 6694): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6694): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,D/wpa_supplicant( 1352): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=307 cookie=0xffffffc06632f600 (match))
D/wpa_supplicant( 1352): p2p0: Event REMAIN_ON_CHANNEL (21) received
D/wpa_supplicant( 1352): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0 pending_action_tx_done=1)
D/wpa_supplicant( 1352): P2P: Starting Listen timeout(0,307200) on freq=2437 based on callback
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.327200 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=a2:39:f7:70:12:80 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=250
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 11
,D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
,D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
,D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country XX(0x04) Regulatory Class 81 Channel Number 11
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00,
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= a2:39:f7:70:12:80 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=ee:1f:72:63:11:86 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=291
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Created device entry based on Probe Req: ee:1f:72:63:11:86 dev_capab=0x25 group_capab=0x0 name='S5-1' listen_freq=2412
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= ee:1f:72:63:11:86 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): P2P: Driver is still in listen state - stop it
D/wpa_supplicant( 1352): nl80211: Cancel remain-on-channel with cookie 0xffffffc06632f600
,D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry,
D/wpa_supplicant( 1352): nl80211: Disable Probe Request reporting nl_preq=0x888888dded3aa0a9
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-listen'@0x5565affa60 done in 0.371295 seconds
D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
D/wpa_supplicant( 1352): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
,D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0xffffffc06632f600 (match))
D/wpa_supplicant( 1352): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (22) received
D/wpa_supplicant( 1352): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
D/wpa_supplicant( 1352): P2P: Driver ended Listen state (freq=2437)
D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
,D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH)
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): P2P: Starting search
D/wpa_supplicant( 1352): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * Request Type
D/wpa_supplicant( 1352): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Primary Device Type
D/wpa_supplicant( 1352): WPS:  * RF Bands (3)
D/wpa_supplicant( 1352): WPS:  * Association State
D/wpa_supplicant( 1352): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1352): WPS:  * Device Password ID (0)
,D/wpa_supplicant( 1352): WPS:  * Manufacturer
D/wpa_supplicant( 1352): WPS:  * Model Name
D/wpa_supplicant( 1352): WPS:  * Model Number
D/wpa_supplicant( 1352): WPS:  * Device Name
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-scan'@0x5565b20a60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-scan'@0x5565b20a60 after 0.000081 second wait
D/wpa_supplicant( 1352): p2p0: nl80211: scan request
D/wpa_supplicant( 1352): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1352): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1352): P2P: Running p2p_scan
D/wpa_supplicant( 1352): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1352): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1352): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1352): p2p0: Own scan request started a scan in 0.000159 seconds
I/wpa_supplicant( 1352): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1352): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1352): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1352): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1352): nl80211: Scan included frequencies: 2412 2437 2462
D/wpa_supplicant( 1352): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1352): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1352): p2p0: Scan completed in 0.131136 seconds
D/wpa_supplicant( 1352): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 1352): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1352): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-85
I/wpa_supplicant( 1352): [NULL] 7e:f9:0e:51:18:23 freq=2412 level=-55
D/wpa_supplicant( 1352): p2p0: BSS: Start scan result update 5
D/wpa_supplicant( 1352): p2p0: BSS: Add new id 1 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 1352): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-scan'@0x5565b20a60 done in 0.132322 seconds
D/wpa_supplicant( 1352): P2P: Scan results received (3 BSS)
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x2008
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 1352): P2P: Ignore scan data without P2P Device Info or P2P Device Id
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 06 Group Capability 09
D/WifiP2pService(  982): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  982):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  982):  primary type: 3-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 128
D/WifiP2pService(  982):  grpcapab: 9
D/WifiP2pService(  982):  devcapab: 4
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 13 length 45
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  982):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  982):  primary type: 3-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 128
D/WifiP2pService(  982):  grpcapab: 9
D/WifiP2pService(  982):  devcapab: 4
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/WifiP2pService(  982): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  982):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 14 length 0
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  982):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: * Group Info
D/WifiDisplayController(  982): Received WIFI_P2P_PEERS_CHAN,GED_ACTION.
D/wpa_supplicant( 1352): P2P: Update peer 9e:93:4e:3e:3a:c5 config_methods 0x0 -> 0x80
D/WifiDisplayController(  982): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/wpa_supplicant( 1352): P2P: Peer found with Listen frequency 2437 MHz (rx_time=472.347467)
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1352): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/WifiP2pService(  982): DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 13 length 43
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: * Device Info: addr 7e:f9:0e:51:18:23 primary device type 10-0050F204-5 device name 'Thali Test (Galaxy A5)' config methods 0x188
D/WifiP2pService(  982): InactiveState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Update peer 7e:f9:0e:51:18:23 config_methods 0x0 -> 0x188
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Peer found with Listen frequency 2412 MHz (rx_time=472.347467)
D/WifiP2pService(  982): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1352): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiDisplayController(  982): Received list of peers.
D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/WifiDisplayController(  982):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Start Service Discovery with ee:1f:72:63:11:86,
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/WifiDisplayController(  982):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0,
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20e00
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/WifiDisplayController(  982):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20e00 after 0.000068 second wait
D/WifiDisplayController(  982):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=ee:1f:72:63:11:86 src=92:e7:c4:e6:4c:f8 bssid=ee:1f:72:63:11:86 len=39
D/WifiDisplayController(  982): Received list of peers.
,D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
D/WifiDisplayController(  982):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 1 9e:93:4e:3e:ba:c5]
,D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/WifiMonitor(  982): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1]
D/WifiDisplayController(  982):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0,
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=80 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/WifiMonitor(  982): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1]
D/WifiDisplayController(  982):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
,E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=81 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiDisplayController(  982):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180a00 (match) (ack=0)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=ee:1f:72:63:11:86 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=1 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=ee:1f:72:63:11:86 src=92:e7:c4:e6:4c:f8 bssid=ee:1f:72:63:11:86 result=1
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=0
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b20e00 done in 0.029175 seconds
D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
,D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180a00
,D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH,
D/wpa_supplicant( 1352): P2P: Start Service Discovery with ee:1f:72:63:11:86
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b24a50
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b24a50 after 0.000058 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=ee:1f:72:63:11:86 src=92:e7:c4:e6:4c:f8 bssid=ee:1f:72:63:11:86 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=ee:1f:72:63:11:86 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=ee:1f:72:63:11:86 src=92:e7:c4:e6:4c:f8 bssid=ee:1f:72:63:11:86 result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
,D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): P2P: Timeout (state=SD_DURING_FIND),
D/wpa_supplicant( 1352): P2P: Service Discovery Query timeout
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b24a50 done in 0.216293 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH,
D/wpa_supplicant( 1352): P2P: Starting short listen state (state=SEARCH)
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
,D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info,
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-listen'@0x5565b23d10
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-listen'@0x5565b23d10 after 0.000049 second wait,
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd SET_AP_WPS_P2P_IE 2 len = 0, 190
D/wpa_supplicant( 1352): nl80211: Enable Probe Request reporting nl_preq=0x5565b23d70
D/wpa_supplicant( 1352): nl80211: Register frame type=0x40 (WLAN_FC_STYPE_PROBE_REQ) nl_handle=0x5565b23d70 match=,
D/wpa_supplicant( 1352): nl80211: Remain-on-channel cookie 0xffffffc04d180200 for freq=2437 MHz duration=307
,D/wpa_supplicant( 1352): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=307 cookie=0xffffffc04d180200 (match))
D/wpa_supplicant( 1352): p2p0: Event REMAIN_ON_CHANNEL (21) received
D/wpa_supplicant( 1352): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0 pending_action_tx_done=1)
,D/wpa_supplicant( 1352): P2P: Starting Listen timeout(0,307200) on freq=2437 based on callback
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.327200 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=ee:1f:72:63:11:86 freq=2412 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=134
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=ee:1f:72:63:11:86 Category=4 DataLen=109 freq=2412 MHz
,D/wpa_supplicant( 1352): GAS: No pending query found for ee:1f:72:63:11:86 dialog token 0
D/wpa_supplicant( 1352): P2P: Ignore unexpected GAS Initial Response from ee:1f:72:63:11:86
,D/wpa_supplicant( 1352): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0xffffffc04d180200 (match))
D/wpa_supplicant( 1352): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (22) received
D/wpa_supplicant( 1352): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-listen'@0x5565b23d10 done in 0.335566 seconds
D/wpa_supplicant( 1352): P2P: Driver ended Listen state (freq=2437)
,D/wpa_supplicant( 1352): P2P: Skip stop_listen since not in listen_only state.
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/wpa_supplicant( 1352): nl80211: Disable Probe Request reporting nl_preq=0x888888dded3ab5f9
,D/wpa_supplicant( 1352): P2P: Starting search
,D/wpa_supplicant( 1352): WPS: Building WPS IE for Probe Request
,D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 1352): WPS:  * Request Type
D/wpa_supplicant( 1352): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Primary Device Type
D/wpa_supplicant( 1352): WPS:  * RF Bands (3)
D/wpa_supplicant( 1352): WPS:  * Association State,
D/wpa_supplicant( 1352): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1352): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1352): WPS:  * Manufacturer
D/wpa_supplicant( 1352): WPS:  * Model Name
D/wpa_supplicant( 1352): WPS:  * Model Number
,D/wpa_supplicant( 1352): WPS:  * Device Name
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
,D/wpa_supplicant( 1352): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-scan'@0x5565b239b0
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-scan'@0x5565b239b0 after 0.000087 second wait
D/wpa_supplicant( 1352): p2p0: nl80211: scan request
,D/wpa_supplicant( 1352): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1352): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1352): P2P: Running p2p_scan
D/wpa_supplicant( 1352): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1352): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1352): p2p0: Event SCAN_STARTED (49) received
,D/wpa_supplicant( 1352): p2p0: Own scan request started a scan in 0.000165 seconds
I/wpa_supplicant( 1352): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=82 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1352): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1352): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1352): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1352): nl80211: Scan included frequencies: 2412 2437 2462
D/wpa_supplicant( 1352): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1352): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1352): p2p0: Scan completed in 0.141026 seconds
D/wpa_supplicant( 1352): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 1352): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1352): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
I/wpa_supplicant( 1352): [NULL] 7e:f9:0e:51:18:23 freq=2412 level=-55
D/wpa_supplicant( 1352): p2p0: BSS: Start scan result update 6
D/wpa_supplicant( 1352): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-scan'@0x5565b239b0 done in 0.142401 seconds
D/wpa_supplicant( 1352): P2P: Scan results received (3 BSS)
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x2008
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 1352): P2P: Ignore scan data without P2P Device Info or P2P Device Id
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x0
,D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 06 Group Capability 09,
D/wpa_supplicant( 1352): P2P: Attribute 13 length 45
D/wpa_supplicant( 1352): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/wpa_supplicant( 1352): P2P: Attribute 14 length 0
D/wpa_supplicant( 1352): P2P: * Group Info,
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
,D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
,D/wpa_supplicant( 1352): P2P: Attribute 13 length 43
D/wpa_supplicant( 1352): P2P: * Device Info: addr 7e:f9:0e:51:18:23 primary device type 10-0050F204-5 device name 'Thali Test (Galaxy A5)' config methods 0x188
D/wpa_supplicant( 1352): P2P: Do not update peer entry based on old frame (rx_time=472.347182 last_seen=472.347467)
D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): P2P: Starting short listen state (state=SEARCH)
,D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header,
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-listen'@0x5565b24b20
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-listen'@0x5565b24b20 after 0.000069 second wait
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd SET_AP_WPS_P2P_IE 2 len = 0, 190
D/wpa_supplicant( 1352): nl80211: Enable Probe Request reporting nl_preq=0x5565b25580,
D/wpa_supplicant( 1352): nl80211: Register frame type=0x40 (WLAN_FC_STYPE_PROBE_REQ) nl_handle=0x5565b25580 match=
D/wpa_supplicant( 1352): nl80211: Remain-on-channel cookie 0xffffffc04d180200 for freq=2437 MHz duration=307
,D/wpa_supplicant( 1352): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=307 cookie=0xffffffc04d180200 (match))
D/wpa_supplicant( 1352): p2p0: Event REMAIN_ON_CHANNEL (21) received
D/wpa_supplicant( 1352): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0 pending_action_tx_done=1)
,D/wpa_supplicant( 1352): P2P: Starting Listen timeout(0,307200) on freq=2437 based on callback
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.327200 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=ee:1f:72:18:8b:78 freq=2437 ssi_signal=0 stype=4 (WLAN_FC_STYPE_PROBE_REQ) len=309
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Created device entry based on Probe Req: ee:1f:72:18:8b:78 dev_capab=0x25 group_capab=0x0 name='Thali Test (Galaxy S5)' listen_freq=2412
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Device Password ID: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
,D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 6 length 5
D/wpa_supplicant( 1352): P2P: * Listen Channel: Country PL(0x04) Regulatory Class 81 Channel Number 1
D/wpa_supplicant( 1352): P2P: Reply to P2P Probe Request in Listen state
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
,D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): nl80211: send_mlme - da= ee:1f:72:18:8b:78 noack=1 freq=0 no_cck=0 offchanok=0 wait_time=0 fc=0x50 (WLAN_FC_STYPE_PROBE_RESP) nlmode=2
D/wpa_supplicant( 1352): nl80211: Use last_mgmt_freq=2437
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): P2P: Driver is still in listen state - stop it
,D/wpa_supplicant( 1352): nl80211: Cancel remain-on-channel with cookie 0xffffffc04d180200
,D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/wpa_supplicant( 1352): nl80211: Disable Probe Request reporting nl_preq=0x888888dded3add09
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-listen'@0x5565b24b20 done in 0.373646 seconds
D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
,D/wpa_supplicant( 1352): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0xffffffc04d180200 (match))
D/wpa_supplicant( 1352): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (22) received
D/wpa_supplicant( 1352): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
,D/wpa_supplicant( 1352): P2P: Driver ended Listen state (freq=2437)
D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 1352): P2P: Starting search
D/wpa_supplicant( 1352): WPS: Building WPS IE for Probe Request
,D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * Request Type
D/wpa_supplicant( 1352): WPS:  * Config Methods (4388)
D/wpa_supplicant( 1352): WPS:  * UUID-E,
D/wpa_supplicant( 1352): WPS:  * Primary Device Type
D/wpa_supplicant( 1352): WPS:  * RF Bands (3)
D/wpa_supplicant( 1352): WPS:  * Association State
D/wpa_supplicant( 1352): WPS:  * Configuration Error (0),
D/wpa_supplicant( 1352): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1352): WPS:  * Manufacturer
D/wpa_supplicant( 1352): WPS:  * Model Name
,D/wpa_supplicant( 1352): WPS:  * Model Number
D/wpa_supplicant( 1352): WPS:  * Device Name
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): WPS:  * Request to Enroll (1)
,D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-scan'@0x5565b24b20,
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-scan'@0x5565b24b20 after 0.000048 second wait
D/wpa_supplicant( 1352): p2p0: nl80211: scan request
,D/wpa_supplicant( 1352): nl80211: P2P probe - mask SuppRates
D/wpa_supplicant( 1352): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1352): P2P: Running p2p_scan
D/wpa_supplicant( 1352): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0,
D/wpa_supplicant( 1352): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1352): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1352): p2p0: Own scan request started a scan in 0.000101 seconds
,I/wpa_supplicant( 1352): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=83 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1352): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1352): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1352): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1352): nl80211: Scan included frequencies: 2412 2437 2462
D/wpa_supplicant( 1352): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1352): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1352): p2p0: Scan completed in 0.141542 seconds
D/wpa_supplicant( 1352): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 1352): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1352): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
I/wpa_supplicant( 1352): [NULL] 7e:f9:0e:51:18:23 freq=2412 level=-55
D/wpa_supplicant( 1352): p2p0: BSS: Start scan result update 7
D/wpa_supplicant( 1352): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-scan'@0x5565b24b20 done in 0.142582 seconds
D/wpa_supplicant( 1352): P2P: Scan results received (3 BSS)
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x2008
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 1352): P2P: Ignore scan data without P2P Device Info or P2P Device Id
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 06 Group Capability 09
D/wpa_supplicant( 1352): P2P: Attribute 13 length 45
D/wpa_supplicant( 1352): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/wpa_supplicant( 1352): P2P: Attribute 14 length 0
D/wpa_supplicant( 1352): P2P: * Group Info
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/wpa_supplicant( 1352): P2P: Attribute 13 length 43
D/wpa_supplicant( 1352): P2P: * Device Info: addr 7e:f9:0e:51:18:23 primary device type 10-0050F204-5 device name 'Thali Test (Galaxy A5)' config methods 0x188
D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with ee:1f:72:18:8b:78
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b25580
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b25580 after 0.000067 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=ee:1f:72:18:8b:78 src=92:e7:c4:e6:4c:f8 bssid=ee:1f:72:18:8b:78 len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
,D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d180200 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=ee:1f:72:18:8b:78 type=0 stype=13
,D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=ee:1f:72:18:8b:78 src=92:e7:c4:e6:4c:f8 bssid=ee:1f:72:18:8b:78 result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
D/wpa_supplicant( 1352): P2P: State SEARCH -> SD_DURING_FIND
D/wpa_supplicant( 1352): P2P: Set timeout (state=SD_DURING_FIND): 0.200000 sec
,D/wpa_supplicant( 1352): P2P: Timeout (state=SD_DURING_FIND),
D/wpa_supplicant( 1352): P2P: Service Discovery Query timeout
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-send-action'@0x5565b25580 done in 0.226680 seconds
,D/wpa_supplicant( 1352): Off-channel: Action frame sequence done notification
D/wpa_supplicant( 1352): nl80211: Cancel TX frame wait: cookie=0xffffffc04d180200
,D/wpa_supplicant( 1352): P2P: State SD_DURING_FIND -> SEARCH,
D/wpa_supplicant( 1352): P2P: Starting short listen state (state=SEARCH)
D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Device Info
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-listen'@0x5565affa60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-listen'@0x5565affa60 after 0.000062 second wait
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry
,D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd SET_AP_WPS_P2P_IE 2 len = 0, 190
D/wpa_supplicant( 1352): nl80211: Enable Probe Request reporting nl_preq=0x5565b25fe0
D/wpa_supplicant( 1352): nl80211: Register frame type=0x40 (WLAN_FC_STYPE_PROBE_REQ) nl_handle=0x5565b25fe0 match=
D/wpa_supplicant( 1352): nl80211: Remain-on-channel cookie 0xffffffc04d180200 for freq=2437 MHz duration=204
,D/wpa_supplicant( 1352): nl80211: Drv Event 55 (NL80211_CMD_REMAIN_ON_CHANNEL) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=0 freq=2437 channel_type=0 duration=204 cookie=0xffffffc04d180200 (match))
D/wpa_supplicant( 1352): p2p0: Event REMAIN_ON_CHANNEL (21) received
D/wpa_supplicant( 1352): Off-channel: Send Action callback (without_roc=0 pending_action_tx=0x0 pending_action_tx_done=1)
D/wpa_supplicant( 1352): P2P: Starting Listen timeout(0,204800) on freq=2437 based on callback
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.224800 sec
,D/wpa_supplicant( 1352): nl80211: BSS Event 59 (NL80211_CMD_FRAME) received for p2p0,
D/wpa_supplicant( 1352): nl80211: RX frame sa=ee:1f:72:18:8b:78 freq=2412 ssi_signal=0 stype=13 (WLAN_FC_STYPE_ACTION) len=152
D/wpa_supplicant( 1352): p2p0: Event RX_MGMT (20) received
,D/wpa_supplicant( 1352): p2p0: Received Action frame: SA=ee:1f:72:18:8b:78 Category=4 DataLen=127 freq=2412 MHz
D/wpa_supplicant( 1352): GAS: No pending query found for ee:1f:72:18:8b:78 dialog token 0
D/wpa_supplicant( 1352): P2P: Ignore unexpected GAS Initial Response from ee:1f:72:18:8b:78
,D/wpa_supplicant( 1352): nl80211: Drv Event 56 (NL80211_CMD_CANCEL_REMAIN_ON_CHANNEL) received for p2p0,
D/wpa_supplicant( 1352): nl80211: Remain-on-channel event (cancel=1 freq=2437 channel_type=0 duration=0 cookie=0xffffffc04d180200 (match))
D/wpa_supplicant( 1352): p2p0: Event CANCEL_REMAIN_ON_CHANNEL (22) received
D/wpa_supplicant( 1352): P2P: Cancel remain-on-channel callback (p2p_long_listen=0 ms pending_action_tx=0x0)
,D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-listen'@0x5565affa60 done in 0.241626 seconds
D/wpa_supplicant( 1352): P2P: Driver ended Listen state (freq=2437)
D/wpa_supplicant( 1352): P2P: Skip stop_listen since not in listen_only state.
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): P2P: Delay search operation by 500 ms
D/wpa_supplicant( 1352): P2P: Set timeout (state=SEARCH): 0.500000 sec
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/wpa_supplicant( 1352): P2P: Timeout (state=SEARCH),
D/wpa_supplicant( 1352): wpa_driver_set_ap_wps_p2p_ie: Entry,
D/wpa_supplicant( 1352): nl80211: Disable Probe Request reporting nl_preq=0x888888dded3ad769
,D/wpa_supplicant( 1352): P2P: Starting search
,D/wpa_supplicant( 1352): WPS: Building WPS IE for Probe Request,
,D/wpa_supplicant( 1352): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1352): WPS:  * Request Type
D/wpa_supplicant( 1352): WPS:  * Config Methods (4388)
,D/wpa_supplicant( 1352): WPS:  * UUID-E
D/wpa_supplicant( 1352): WPS:  * Primary Device Type
D/wpa_supplicant( 1352): WPS:  * RF Bands (3)
D/wpa_supplicant( 1352): WPS:  * Association State
D/wpa_supplicant( 1352): WPS:  * Configuration Error (0)
,D/wpa_supplicant( 1352): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1352): WPS:  * Manufacturer
D/wpa_supplicant( 1352): WPS:  * Model Name
D/wpa_supplicant( 1352): WPS:  * Model Number
D/wpa_supplicant( 1352): WPS:  * Device Name
,D/wpa_supplicant( 1352): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1352): WPS:  * Request to Enroll (1)
D/wpa_supplicant( 1352): P2P: * P2P IE header
D/wpa_supplicant( 1352): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1352): P2P: * Listen Channel: Regulatory Class 81 Channel 6
,D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-scan'@0x5565affa60
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-scan'@0x5565affa60 after 0.000085 second wait
D/wpa_supplicant( 1352): p2p0: nl80211: scan request
D/wpa_supplicant( 1352): nl80211: P2P probe - mask SuppRates
,D/wpa_supplicant( 1352): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1352): P2P: Running p2p_scan
D/wpa_supplicant( 1352): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for p2p0
D/wpa_supplicant( 1352): p2p0: nl80211: Scan trigger
D/wpa_supplicant( 1352): p2p0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1352): p2p0: Own scan request started a scan in 0.000168 seconds,
I/wpa_supplicant( 1352): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  982): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=84 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED ,
,D/wpa_supplicant( 1352): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for p2p0,
D/wpa_supplicant( 1352): p2p0: nl80211: New scan results available
D/wpa_supplicant( 1352): nl80211: Scan probed for SSID 'DIRECT-'
D/wpa_supplicant( 1352): nl80211: Scan included frequencies: 2412 2437 2462
D/wpa_supplicant( 1352): p2p0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1352): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1352): p2p0: Scan completed in 0.150953 seconds
D/wpa_supplicant( 1352): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 1352): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1352): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
I/wpa_supplicant( 1352): [NULL] 92:b6:86:43:73:1c freq=2412 level=-43
I/wpa_supplicant( 1352): [NULL] a2:39:f7:6f:c9:5d freq=2462 level=-54
I/wpa_supplicant( 1352): [NULL] 7e:f9:0e:51:18:23 freq=2412 level=-55
D/wpa_supplicant( 1352): p2p0: BSS: Start scan result update 8
D/wpa_supplicant( 1352): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1352): p2p0: Radio work 'p2p-scan'@0x5565affa60 done in 0.152391 seconds
D/wpa_supplicant( 1352): P2P: Scan results received (5 BSS)
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x2008
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
,D/wpa_supplicant( 1352): P2P: Ignore scan data without P2P Device Info or P2P Device Id
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/WifiP2pService(  982): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  982):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x0
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  982):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 392
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
,D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 6-0050F204-1
D/WifiP2pService(  982): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  982):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 4488
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  982):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  982):  primary type: 10-0050F204-5
D/WifiP2pService(  982):  secondary type: null
D/WifiP2pService(  982):  wps: 4488
D/WifiP2pService(  982):  grpcapab: 0
D/WifiP2pService(  982):  devcapab: 37
D/WifiP2pService(  982):  status: 3
D/WifiP2pService(  982):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/WifiDisplayController(  982): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/wpa_supplicant( 1352): P2P: * Device Capability 06 Group Capability 09
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1352): P2P: Attribute 13 length 45
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: * Device Info: addr 9e:93:4e:3e:3a:c5 primary device type 3-0050F204-5 device name 'DIRECT-qjWorkCentre 3025' config methods 0x80
D/WifiP2pService(  982): DefaultState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 14 length 0
D/WifiDisplayController(  982): Received list of peers.
D/wpa_supplicant( 1352): P2P: * Group Info
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/WifiDisplayController(  982):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/WifiDisplayController(  982):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/WifiDisplayController(  982):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/WifiDisplayController(  982):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/WifiDisplayController(  982):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Attribute 13 length 28
D/WifiDisplayController(  982):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: * Device Info: addr 92:b6:86:43:73:1c primary device type 10-0050F204-5 device name 'Note4-1' config methods 0x188
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Update peer 92:b6:86:43:73:1c config_methods 0x0 -> 0x188
D/WifiDisplayController(  982): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/wpa_supplicant( 1352): P2P: Peer found with Listen frequency 2412 MHz (rx_time=475.777532)
,D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1352): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x5388
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/WifiDisplayController(  982): Received list of peers.
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
,D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/WifiDisplayController(  982):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Attribute 13 length 25
D/WifiDisplayController(  982):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: * Device Info: addr a2:39:f7:6f:c9:5d primary device type 10-0050F204-5 device name 'G4-1' config methods 0x1188
D/WifiDisplayController(  982):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Update peer a2:39:f7:6f:c9:5d config_methods 0x0 -> 0x1188
D/WifiDisplayController(  982):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Peer found with Listen frequency 2462 MHz (rx_time=475.777532)
D/WifiDisplayController(  982):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
,I/wpa_supplicant( 1352): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiDisplayController(  982):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Parsing WPS IE
D/WifiDisplayController(  982):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: falseWFD DeviceInfo: 0, WFD CtrlPort: 0, WFD MaxThroughput: 0
D/wpa_supplicant( 1352): P2P: Config Methods (WPS): 0x4388
D/WifiP2pService(  982): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Primary Device Type (WPS): 10-0050F204-5
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Parsing P2P IE
D/WifiP2pService(  982): DefaultState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 2 length 2
,D/WifiP2pService(  982): InactiveState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: * Device Capability 25 Group Capability 00
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): P2P: Attribute 13 length 43
D/WifiP2pService(  982): P2pEnabledState clear service request
D/wpa_supplicant( 1352): P2P: * Device Info: addr 7e:f9:0e:51:18:23 primary device type 10-0050F204-5 device name 'Thali Test (Galaxy A5)' config methods 0x188
D/wpa_supplicant( 1352): P2P: State SEARCH -> SEARCH
D/wpa_supplicant( 1352): P2P: Start Service Discovery with 92:b6:86:43:73:1c
D/wpa_supplicant( 1352): P2P: Schedule new radio work for Action frame TX (listen_freq=-1 send_freq=-1)
D/wpa_supplicant( 1352): p2p0: Add radio work 'p2p-send-action'@0x5565b20e00
D/wpa_supplicant( 1352): p2p0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 1352): p2p0: Starting radio work 'p2p-send-action'@0x5565b20e00 after 0.000070 second wait
D/wpa_supplicant( 1352): Off-channel: Send action frame: freq=2412 dst=92:b6:86:43:73:1c src=92:e7:c4:e6:4c:f8 bssid=92:b6:86:43:73:1c len=39
D/wpa_supplicant( 1352): nl80211: Send Action frame (ifindex=30, freq=2412 MHz wait=5000 ms no_cck=1)
D/WifiMonitor(  982): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=85 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/WifiMonitor(  982): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1]
E/WifiMonitor(  982): WifiMonitor:p2p0 cnt=86 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_SERV_DISC_CANCEL_REQ 5565b21120"
,D/wpa_supplicant( 1352): p2p0: Control interface command 'P2P_SERV_DISC_CANCEL_REQ 5565b21120',
I/wpa_supplicant( 1352): [p2p command] (P2P_SERV_DISC_CANCEL_REQ 5565b21120)
D/wpa_supplicant( 1352): P2P: Cancel pending SD query 0x5565b21120
D/wpa_supplicant( 1352): nl80211: Drv Event 60 (NL80211_CMD_FRAME_TX_STATUS) received for p2p0
D/wpa_supplicant( 1352): nl80211: Frame TX status event
D/wpa_supplicant( 1352): nl80211: Action TX status: cookie=0ffffffc04d182800 (match) (ack=1)
D/wpa_supplicant( 1352): p2p0: Event TX_STATUS (18) received
D/wpa_supplicant( 1352): p2p0: EVENT_TX_STATUS dst=92:b6:86:43:73:1c type=0 stype=13
D/wpa_supplicant( 1352): Off-channel: Delete matching pending action frame
D/wpa_supplicant( 1352): Off-channel: TX status result=0 cb=0x5555d88754
D/wpa_supplicant( 1352): P2P: Action frame TX callback (state=5 freq=2412 dst=92:b6:86:43:73:1c src=92:e7:c4:e6:4c:f8 bssid=92:b6:86:43:73:1c result=0
D/wpa_supplicant( 1352): P2P: Service Discovery Query TX callback: success=1
F/libc    ( 1352): Fatal signal 11 (SIGSEGV), code 1, fault addr 0x10 in tid 1352 (wpa_supplicant)
W/libc    ( 1352): Security Level: (1), Debug inforamtion is controlled by the DUMPABLE flag.
I/libc    ( 1352): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
D/WifiP2pService(  982): InactiveState{ when=0 what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pEnabledState add service request
,D/WifiP2pManager( 6694): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): Service request added successfully
,D/PMS     (  982): acquireWL(29b4aa47): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null,
I/BatteryService(  982): n_update end
,D/PMS     (  982): releaseWL(29b4aa47): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  982): updateBatteryInfo,
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  982): runPSCheck
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  982): Checking...
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  982): >> updateStatus
,D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  982): battery changed pluggedType: 2
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1236): closing low battery warning: level=100
D/WifiController(  982): handleMessage: E msg.what=155652
,D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): processMsg: DeviceActiveState
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  982): processMsg: StaEnabledState
I/HtcPowerSaver(  982): << updateStatus
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01",
D/WifiP2pService(  982): InactiveState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6694): Failed to start the service discovery, got error code: 3
D/WifiP2pService(  982): P2pEnabledState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pEnabledState discover services
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 3
,D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING  - connection closed],
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=87 dispatchEvent: CTRL-EVENT-TERMINATING  - connection closed
D/WifiMonitor(  982): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  982): handleMessage: E msg.what=147458
E/WifiStateMachine(  982): processMsg: ConnectedState
E/WifiStateMachine(  982):  ConnectedState SUP_DISCONNECTION_EVENT 87 0
E/WifiStateMachine(  982): processMsg: L2ConnectedState
E/WifiStateMachine(  982):  L2ConnectedState SUP_DISCONNECTION_EVENT 87 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState SUP_DISCONNECTION_EVENT 87 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
E/WifiStateMachine(  982):  DriverStartedState SUP_DISCONNECTION_EVENT 87 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState SUP_DISCONNECTION_EVENT 87 0
E/WifiStateMachine(  982): Connection lost, restart supplicant
I/wpa_ctrl(  982): [wpa_ctrl_close] ctrl=0x55b56eac30
I/wpa_ctrl(  982): [wpa_ctrl_close] ctrl=0x55b592f0c0
,W/Settings( 6465): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): Got discovery timeout, restarting...
E/WifiStateMachine(  982): setWifiState: disabled
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): setState: RESTARTING
D/WifiP2pService(  982): InactiveState{ when=0 what=139268 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): Failed to shutdown P2P device discovery, got error code: 0
D/WifiStateMachine(  982): Enter handleNetworkDisconnect
,E/WifiStateMachine(  982): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
E/WifiStateMachine(  982): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  982): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  982): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WIFI_ICON( 1236): updateWifiState: WIFI_STATE_CHANGED disabled
,E/WifiConfigStore(  982): failed to set BSSID: any
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1236): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
E/WifiStateMachine(  982): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,W/Settings( 1879): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiDataStallTracker(  982): setDhcpActive: false
,D/WifiP2pService(  982): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1971): Read error: ssl=0x55b5687090: I/O error during system call, Connection timed out
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  982): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  982): acquireWL(7b85274): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  982): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  982): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1971): SSL shutdown failed: ssl=0x55b5687090: I/O error during system call, Broken pipe
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
,D/PMS     (  982): acquireWL(2c52a39d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
D/ConnectivityService(  982): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10024
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): Validated
,D/ConnectivityService(  982): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  982): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  982):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  982):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  982): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  982): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  982): NetworkAgent != null
I/ActivityManager(  982): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6996 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/ConnectivityManager.CallbackHandler( 1236): CM callback handler got msg 524290
D/ConnectivityService(  982): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PMS     (  982): releaseWL(7b85274): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  982): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
I/SecurityController( 1236): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  982): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  982): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  982): autoRoamSetBSSID any key="NG700"WPA_PSK,
E/WifiConfigStore(  982): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  982): failed to set BSSID: any
D/WifiStateMachine(  982): Exit handleNetworkDisconnect
E/WifiStateMachine(  982): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  982): handleMessage: new destination call exit/enter
D/WifiDisplayAdapter(  982): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  982):     Client/Owner: Client
D/WifiDisplayAdapter(  982):     GroupId: 
D/WifiDisplayAdapter(  982):     Passphrase: 
D/WifiDisplayAdapter(  982):     SessionId: 0
D/WifiDisplayAdapter(  982):     IP Address: }
E/WifiStateMachine(  982): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  982): invokeExitMethods: ConnectedState
E/WifiStateMachine(  982): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  982): release()
E/WifiStateMachine(  982): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  982): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  982): invokeExitMethods: L2ConnectedState
,E/WifiStateMachine(  982): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  982): invokeExitMethods: DriverStartedState
E/WifiStateMachine(  982): Unexpected BatchedScanResults :null
E/WifiStateMachine(  982): noteBatchedScanstop()
,I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  982): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  982): [1,451,989,548,085 ms] noteScanEnd no scan source
E/WifiStateMachine(  982): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  982): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  982): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131212
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  982): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  982):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
D/WifiP2pService(  982): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  982):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  982): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  982): handleMessage: X
I/QuickSettingWifi( 1236): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
E/WifiStateMachine(  982): handleMessage: E msg.what=131212
E/WifiStateMachine(  982): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  982):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
,I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1236): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  982):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 27
D/WifiDataStallTracker(  982): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  982): stopDataStallAlarm 
,E/WifiStateMachine(  982): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  982): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131212
E/WifiStateMachine(  982): processMsg: WaitForP2pDisableState
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 28
E/WifiDataStallTracker(  982): ENABLE_DATA_MONITOR_POLL false Token 5
E/WifiTrafficPoller(  982): ENABLE_TRAFFIC_STATS_POLL false Token 29
E/WifiStateMachine(  982):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
,E/WifiStateMachine(  982):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiP2pService(  982): discovery change broadcast false
E/WifiStateMachine(  982): processMsg: DefaultState
D/WifiDisplayController(  982): Received WIFI_P2P_PEERS_CHANGED_ACTION.
E/WifiStateMachine(  982):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  982): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  982): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  982): handleMessage: X
D/WifiNetworkAgent(  982): NetworkAgent: NetworkAgent channel lost
D/WifiMonitor(  982): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@fd1f9ee
D/WifiScanningService(  982): SCAN_AVAILABLE : 1
D/RttService(  982): SCAN_AVAILABLE : 1
D/WifiScanningService(  982): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  982): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pDisablingState
D/WifiP2pService(  982): P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  982): p2p socket connection lost
D/WifiP2pService(  982): P2pDisabledState
D/WifiP2pService(  982): P2pDisabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  982): handleMessage: E msg.what=131205
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  982): processMsg: WaitForP2pDisableState
D/WifiP2pService(  982): P2pDisabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  982):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiDisplayController(  982): Received list of peers.
E/WifiStateMachine(  982): transitionTo: destState=InitialState
E/WifiStateMachine(  982): handleMessage: new destination call exit/enter
E/WifiStateMachine(  982): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  982): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  982): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  982): moveTempStackToStateStack: i=0,j=1
D/PMS     (  982): acquireWL(3b87a3e3): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 982 1000 null
E/WifiStateMachine(  982): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  982): invokeEnterMethods: InitialState
D/WifiDisplayController(  982): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayAdapter(  982): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  982):     Client/Owner: Client
D/WifiDisplayAdapter(  982):     GroupId: 
D/WifiDisplayAdapter(  982):     Passphrase: 
D/WifiDisplayAdapter(  982):     SessionId: 0
D/WifiDisplayAdapter(  982):     IP Address: }
D/WifiP2pService(  982): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pDisabledState{ when=-1ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): DefaultState{ when=-2ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): stop: Stopping services
D/WISPrService( 5926): >>>>>WISPrService start isConnected = true<<<<<
,V/AudioService(  982): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  982):     Client/Owner: Client
V/AudioService(  982):     GroupId: 
V/AudioService(  982):     Passphrase: 
V/AudioService(  982):     SessionId: 0
V/AudioService(  982):     IP Address: }
D/HtcEffectManagerBase(  982): onEventChanged id=5 status=false
D/HtcEffectManager(  982): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  982): convertEffect before=902
D/HtcEffectManager(  982): convertEffect after=902
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6694): setState: NOT_INITIALIZED
D/WifiP2pService(  982): P2pDisabledState{ when=0 what=139298 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  982): DefaultState{ when=0 what=139298 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6694): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6694): onP2pDeviceListChanged: 0 device(s) discovered
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): Uncaught exception: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer.onP2pDeviceListChanged(WifiPeerDiscoverer.java:164)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer$MyPeerListListener.onPeersAvailable(WifiP2pDeviceDiscoverer.java:285)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler.handleMessage(WifiP2pManager.java:776)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at android.os.Looper.loop(Looper.java:155)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6694): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/WifiP2pService(  982): P2pDisabledState{ when=-1ms what=139268 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): DefaultState{ when=-1ms what=139268 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): P2pDisabledState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): DefaultState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1236): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/QuickSettingWifi( 1236): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
,I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1236): receive.wifiConnect:false wifiAPname:null elapse:0
,D/usbnet  (  982): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
D/ConnectivityService(  982): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  982):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
,D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  982):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  982): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  982): Disconnected - quitting
D/Nat464Xlat(  982): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1236): CM callback handler got msg 524292
D/ConnectivityService(  982): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SecurityController( 1236): onLost 101
D/ConnectivityService(  982): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  982): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkManagementService(  982): Removing idletimer
D/PMS     (  982): acquireWL(114221e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 982 1000 null
D/CSLegacyTypeTracker(  982): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=false
D/ConnectivityService(  982): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  982): acquireWL(12badc99): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/Tethering(  982): interfaceLinkStateChanged wlan0, false
D/Tethering(  982): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false,
D/Tethering(  982): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  982): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  982): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,I/art     (  982): Explicit concurrent mark sweep GC freed 43776(2MB) AllocSpace objects, 4(284KB) LOS objects, 33% free, 16MB/25MB, paused 1.907ms total 204.315ms
,D/Tethering(  982): interfaceLinkStateChanged wlan0, false
D/Tethering(  982): interfaceStatusChanged wlan0, false,
D/ConnectivityService(  982): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
E/ConnectivityService(  982): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  982): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering(  982): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkPolicy(  982): ensureActiveMobilePolicyLocked()
D/Tethering(  982): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
,D/PMS     (  982): acquireWL(36069b3f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 982 1000 null
D/DATA_ICON( 1236): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/UsbnetService(  982): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/UsbDeviceManager(  982): [USBNET] bCheckSuppFunc: cdc_network
D/DATA_ICON( 1236): dataConnected: false/false
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/NetworkPolicy(  982): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.,
V/NetworkPolicy(  982): updateNetworkEnabledLocked()
,V/NetworkPolicy(  982): updateIfacesLocked()
V/NetworkPolicy(  982): updateNotificationsLocked()
D/NetworkManagementService(  982): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/PMS     (  982): releaseWL(36069b3f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  982): acquireWL(15d77c0c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 982 1000 null
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,D/PMS     (  982): releaseWL(15d77c0c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  982): updateNetworkEnabledLocked()
,V/NetworkPolicy(  982): updateNotificationsLocked()
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,V/NetworkPolicy(  982): updateNetworkEnabledLocked()
V/NetworkPolicy(  982): updateNotificationsLocked()
,D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800,
,D/PMS     (  982): acquireWL(360841c2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri,
,D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/HtcWiFiWidget_WiFiWidgetProvider( 6996): onWiFiStateChanged() for widget: ,
D/HtcWiFiWidget_WiFiWidgetProvider( 6996): updateWidget(context) for widget: 
,D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/PMS     (  982): releaseWL(2c52a39d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/MdScPhnSt( 6757): [40d.1.]  listen tmrbb8
D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun,
,D/WifiService(  982): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet,
,D/Batterystats( 4440): User is not opted-in to Usage & Diagnostics.
D/Procstats( 4440): User is not opted-in to Usage & Diagnostics.
,D/PMS     (  982): releaseWL(12badc99): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  982): releaseWL(360841c2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  982): acquireWL(2c1cb80e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/TetherSettings( 5926): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5926): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5926): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5926): Cust_ConnectToPC   : spcsc>false
D/        ( 5926): Cust_ConnectToPC   : IPT>true
D/        ( 5926): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5926): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5926): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5926): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 5926): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,W/ContextImpl( 5926): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 ,
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
I/SmartNS_Utility( 5926): setISNotification
D/SmartNS_Utility( 5926): usb_cable_connect = 1
,D/SmartNS_Utility( 5926): usb_denied = 0
I/SmartNS_PSService( 5926): usb notificaiton:true
,E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  982): releaseWL(2c1cb80e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  982): acquireWL(3122d22f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/MdProvGlob( 6625): remove item 101 (p2d13in133) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6757): [40d.1.] summary 118:p2 ignore
D/SmartNS_Utility( 5926): usb_cable_connect = 1
D/SmartNS_Utility( 5926): usb_denied = 0
,I/SmartNS_PSService( 5926): usb notificaiton:true
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,D/MdProvGlob( 6625): remove item 101 (p2in10) for 15:android.intent.action.ANY_DATA_STATE
D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1236): reapply : com.android.settings 1 36
D/PMS     (  982): releaseWL(3122d22f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  982): acquireWL(738003c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,D/SmartNS_NSReceiver( 5926): Tethered state change:false isNSOpening:false
D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/PMS     (  982): releaseWL(738003c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/RemoteViews( 1236): reapply : com.android.settings 2 36
,D/MdProvGlob( 6625): remove item 101 (p2d2in23) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6625): remove item 101 (p2d1in18) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6625): remove item 101 (p2d2in20) for 15:android.intent.action.ANY_DATA_STATE,
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6625): remove item 101 (p2d1in15) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 6625): remove item 101 (p2in12) for 15:android.intent.action.ANY_DATA_STATE,
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6625): remove item 101 (p2in10) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6625): remove item 101 (p2in14) for 15:android.intent.action.ANY_DATA_STATE,
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/FlexNetS( 6559): updateSvcAllowedInSettings:false
,D/Tethering(  982): interfaceLinkStateChanged wlan0, false
,D/Tethering(  982): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  982): interfaceRemoved wlan0
,E/Tethering(  982): attempting to remove unknown iface (wlan0), ignoring
,D/Tethering(  982): interfaceLinkStateChanged p2p0, false,
D/Tethering(  982): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  982): interfaceRemoved p2p0,
E/Tethering(  982): attempting to remove unknown iface (p2p0), ignoring
,E/WifiStateMachine(  982): handleMessage: X,
D/PMS     (  982): releaseWL(3b87a3e3): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  982): handleMessage: E msg.what=131131
E/WifiStateMachine(  982): processMsg: InitialState
E/WifiStateMachine(  982):  InitialState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  982): handleMessage: X
D/WIFI    (  982): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  982):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/WIFI    (  982): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiStateMachine(  982): handleMessage: E msg.what=131101
E/WifiStateMachine(  982): processMsg: InitialState
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  982):  InitialState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  982): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  982): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  982): handleMessage: X
D/WISPrService( 5926): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5926): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/ActivityManager(  982): Killing 6495:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  982): killProcessQuiet, pid=6495
,D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  982): Recipient 6495
,D/GpsLocationProvider(  982): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
D/ConnectivityService(  982): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  982): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  982): acquireWL(d5291c5): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 982 1000 null
D/GpsLocationProvider(  982): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  982): [AlarmQueuing] connectivity wifi: false
D/htcCheckinService(  982): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  982): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1611): [onReceive] WIFI(1): DISCONNECTED
,V/MusicLeanback( 6822): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,E/GpsLocationProvider(  982): No APN found to select.,
,D/PMS     (  982): releaseWL(d5291c5): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/AutoSetting( 1675): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6415): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6415): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1675): Util - no network available!
,D/AutoSetting( 1675): service - onCreate()
,D/MdScPhnSt( 6757): [994.1.]  listen tmrbb8
,D/AutoSetting( 1675): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  982): request 6394a31 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  982): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1675): service - mHandler: cancel location update
D/AutoSetting( 1675): service -           changes count: 0
,I/iu.Environment( 4440): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4440): num queued entries: 0
I/iu.UploadsManager( 4440): num updated entries: 0
,I/iu.SyncManager( 4440): NEXT; no task
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/MdScDataSum( 6757): [994.1.] summary 118:p1 ignore
,I/Babel   ( 6465): connection state changed from CONNECTED to DISCONNECTED
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 4
,E/WifiStateMachine(  982): handleMessage: E msg.what=131083
D/PMS     (  982): acquireWL(37641040): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 982 1000 null
E/WifiStateMachine(  982): processMsg: InitialState
E/WifiStateMachine(  982):  InitialState CMD_START_SUPPLICANT 0 0
,D/WifiP2pService(  982): P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  982): interfaceAdded wlan0
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbDeviceManager(  982): [USBNET] bCheckSuppFunc: cdc_network
V/Tethering(  982): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  982): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/UsbnetService(  982): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/PMS     (  982): acquireWL(2226743b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 982 1000 null
,D/Tethering(  982): interfaceLinkStateChanged wlan0, false
D/Tethering(  982): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/TetherSettings( 5926): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5926): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5926): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5926): Cust_ConnectToPC   : spcsc>false
D/        ( 5926): Cust_ConnectToPC   : IPT>true
D/        ( 5926): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5926): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UsbDeviceManager(  982): [USBNET] bCheckSuppFunc: cdc_network
E/SmartNS_Utility( 5926): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5926): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/Tethering(  982): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
W/ContextImpl( 5926): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/SmartNS_NSReceiver( 5926): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
V/Tethering(  982): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  982): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  982): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/UsbnetService(  982): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/Tethering(  982): interfaceAdded p2p0
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  982): p2p0 is not a tetherable iface, ignoring
,V/NetworkPolicy(  982): updateNetworkEnabledLocked()
D/Tethering(  982): interfaceLinkStateChanged p2p0, false
D/PMS     (  982): releaseWL(2226743b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  982): updateNotificationsLocked()
I/SmartNS_Utility( 5926): setISNotification
D/PMS     (  982): acquireWL(226ba758): PARTIAL_WAKE_LOCK  NetworkStats 0x1 982 1000 null
D/SmartNS_Utility( 5926): usb_cable_connect = 1
D/SmartNS_Utility( 5926): usb_denied = 0
I/SmartNS_PSService( 5926): usb notificaiton:true
D/Tethering(  982): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  982): releaseWL(37641040): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/PMS     (  982): releaseWL(226ba758): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/libc    (  982): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
V/NetworkPolicy(  982): updateNetworkEnabledLocked(),
D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
V/NetworkPolicy(  982): updateNotificationsLocked()
,E/WifiStateMachine(  982): setWifiState: enabling
,E/WifiStateMachine(  982): Supplicant start successful
D/SmartNS_Utility( 5926): usb_cable_connect = 1
D/WifiMonitor(  982): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  982): connecting to supplicant
D/SmartNS_Utility( 5926): usb_denied = 0
E/WifiHW  (  982): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
I/SmartNS_PSService( 5926): usb notificaiton:true
D/WIFI_ICON( 1236): updateWifiState: WIFI_STATE_CHANGED disabled
I/IntentController( 1236): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1236): reapply : com.android.settings 1 36
D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_NSReceiver( 5926): Tethered state change:false isNSOpening:false
,D/TetherSettings( 5926): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5926): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5926): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5926): Cust_ConnectToPC   : spcsc>false
D/        ( 5926): Cust_ConnectToPC   : IPT>true
D/        ( 5926): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5926): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5926): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5926): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5926): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5926): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/SmartNS_Utility( 5926): setISNotification
,D/SmartNS_Utility( 5926): usb_cable_connect = 1
,D/SmartNS_Utility( 5926): usb_denied = 0
I/SmartNS_PSService( 5926): usb notificaiton:true
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 7047): wpa_supplicant v2.3-devel-5.0.2
D/wpa_supplicant( 7047): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 7047): random: Trying to read entropy from /dev/random
D/SmartNS_Utility( 5926): usb_cable_connect = 1
D/SmartNS_Utility( 5926): usb_denied = 0
I/SmartNS_PSService( 5926): usb notificaiton:true
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 7047): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 7047): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 7047): Using Android control socket 'wpa_wlan0'
,I/wpa_supplicant( 7047): Successfully initialized wpa_supplicant
D/wpa_supplicant( 7047): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 7047): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 7047): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
I/RemoteViews( 1236): reapply : com.android.settings 1 36
D/wpa_supplicant( 7047): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 7047): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 7047): update_config=1
D/wpa_supplicant( 7047): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 7047): device_name='Android_608e'
D/wpa_supplicant( 7047): manufacturer='HTC'
D/wpa_supplicant( 7047): model_name='HTC_PHONE'
D/wpa_supplicant( 7047): model_number='1234'
D/wpa_supplicant( 7047): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 7047): p2p_oper_reg_class=126
D/wpa_supplicant( 7047): p2p_oper_channel=149
D/wpa_supplicant( 7047): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 7047): persistent_reconnect=1
D/wpa_supplicant( 7047): key_mgmt_offload=1
I/wpa_supplicant( 7047): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 7047): nl80211: RFKILL status not available
D/wpa_supplicant( 7047): nl80211: Using driver-based roaming
D/wpa_supplicant( 7047): nl80211: TDLS supported
D/wpa_supplicant( 7047): nl80211: TDLS external setup
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 7047): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0,
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Su,pported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 7047): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 7047): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 7047): nl80211: interface p2p0 in phy phy1
D/wpa_supplicant( 7047): nl80211: Set mode ifindex 32 iftype 2 (STATION)
D/wpa_supplicant( 7047): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b4f9ffd0
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=0104
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=040a
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=040b
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=040c
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=040d
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=090a
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=090b
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=090c
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=090d
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=0409506f9a09
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=7f506f9a09
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=0801
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=040e
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=06
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=0a07
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=0a11
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4f9ffd0 match=0a1a
D/wpa_supplicant( 7047): netlink: Operstate: ifindex=32 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 7047): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 7047): Add interface p2p0 to a new radio phy1
I/wpa_supplicant( 7047): htc_wext_command_init +
E/wpa_supplicant( 7047): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 7047): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  982): interfaceLinkStateChanged p2p0, false
D/Tethering(  982): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  982): interfaceLinkStateChanged p2p0, false
D/Tethering(  982): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 5926): Tethered state change:false isNSOpening:false
D/DotMatrix( 1359): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/HtcWiFiWidget_WiFiWidgetProvider( 6996): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 6996): updateWidget(context) for widget: 
I/RemoteViews( 1236): reapply : com.android.settings 0 36
I/RemoteViews( 1236): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1236): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
,I/wpa_supplicant( 7047): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 7047):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 7047):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 7047):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=32 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=32 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=32 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=32 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=32 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=32 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 7047): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 7047): nl80211: Flush PMKIDs
D/wpa_supplicant( 7047): p2p0: State: DISCONNECTED -> INACTIVE
,D/wpa_supplicant( 7047): TDLS: TDLS operation supported by driver
,D/wpa_supplicant( 7047): TDLS: Driver uses external link setup
D/wpa_supplicant( 7047): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 7047): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 7047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 7047): nl80211: Skip set_supp_port(unauthorized) while not associated
,D/wpa_supplicant( 7047): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 7047): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 7047): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 7047): Using existing control interface directory.
,D/wpa_supplicant( 7047): P2P: Add operating class 81
,D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 7047): P2P: Add operating class 115
,D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 7047): P2P: Add operating class 116
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 24 2c
,D/wpa_supplicant( 7047): P2P: Add operating class 117
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 28 30
,D/wpa_supplicant( 7047): P2P: Own listen channel: 81:6
D/wpa_supplicant( 7047): P2P: Configured operating channel: 126:149
D/wpa_supplicant( 7047): P2P: initialized
,D/wpa_supplicant( 7047): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 7047): P2P: cli_channels:
D/wpa_supplicant( 7047): p2p0: Added interface p2p0
D/wpa_supplicant( 7047): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 7047): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 7047): netlink: Operstate: ifindex=32 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 7047): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 7047): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 7047): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 7047): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 7047): disable_scan_offload=1
D/wpa_supplicant( 7047): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 7047): update_config=1
D/wpa_supplicant( 7047): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 7047): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 7047): manufacturer='HTC'
D/wpa_supplicant( 7047): model_name='HTC One M8s'
D/wpa_supplicant( 7047): model_number='HTC One M8s'
D/wpa_supplicant( 7047): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 7047): hs20=1
D/wpa_supplicant( 7047): interworking=1
D/wpa_supplicant( 7047): external_sim=1
D/wpa_supplicant( 7047): key_mgmt_offload=1
,D/wpa_supplicant( 7047): Priority group 413
D/wpa_supplicant( 7047):    id=0 ssid='NG700'
I/wpa_supplicant( 7047): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 7047): nl80211: RFKILL status not available
,D/wpa_supplicant( 7047): nl80211: Using driver-based roaming
D/wpa_supplicant( 7047): nl80211: TDLS supported
D/wpa_supplicant( 7047): nl80211: TDLS external setup
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 7047): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 7047): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offload,s 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80,211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 7047): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 7047): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 7047): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 7047): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 7047): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 7047): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 7047): nl80211: interface wlan0 in phy phy1
D/wpa_supplicant( 7047): nl80211: Set mode ifindex 31 iftype 2 (STATION)
D/wpa_supplicant( 7047): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b4fbf100
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=0104
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=040a
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=040b
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=040c
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=040d
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=090a
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=090b
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=090c
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=090d
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=0409506f9a09
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=7f506f9a09
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=0801
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=040e
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=06
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=0a07
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=0a11
D/wpa_supplicant( 7047): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b4fbf100 match=0a1a
D/Tethering(  982): interfaceLinkStateChanged wlan0, false
D/Tethering(  982): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 7047): netlink: Operstate: ifindex=31 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 7047): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 7047): nl80211: Use separate P2P group interface
D/wpa_supplicant( 7047): Add interface wlan0 to existing radio phy1
I/wpa_supplicant( 7047): htc_wext_command_init +
I/wpa_supplicant( 7047): htc_wext_command_init -
I/wpa_supplicant( 7047): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 7047): Don't set 00 to countryID.conf
D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 7047): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 7047): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=00
D/wpa_supplicant( 7047): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 7047): P2P: Add operating class 81
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 7047): P2P: Update channel list
D/wpa_supplicant( 7047): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 7047): P2P: cli_channels:
D/wpa_supplicant( 7047): p2p0: Updating hw mode
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=00
D/wpa_supplicant( 7047): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=00
D/wpa_supplicant( 7047): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 7047): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
,I/wpa_supplicant( 7047): wapi_supplicant_init: Init WAI packet wlan0
,D/wpa_supplicant( 7047):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 7047):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 7047):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=31 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=31 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=31 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=31 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=31 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 7047): wpa_driver_nl80211_set_key: ifindex=31 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 7047): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 7047): nl80211: Flush PMKIDs
,D/wpa_supplicant( 7047): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 7047): TDLS: Driver uses external link setup
D/wpa_supplicant( 7047): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 7047): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 7047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 7047): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 7047): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
,D/wpa_supplicant( 7047): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 7047): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 7047): Using existing control interface directory.
,I/wpa_supplicant( 7047): set country (DE) from /data/misc/wifi/countryID.conf
,I/wpa_supplicant( 7047): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
,D/wpa_supplicant( 7047): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 7047): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
,D/wpa_supplicant( 7047): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 7047): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 7047): P2P: Add operating class 81
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 7047): P2P: Add operating class 115
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 7047): P2P: Add operating class 116
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 7047): P2P: Add operating class 117
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 7047): P2P: Update channel list
D/wpa_supplicant( 7047): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 7047): P2P: cli_channels:
D/wpa_supplicant( 7047): p2p0: Updating hw mode
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 7047): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
,I/wpa_supplicant( 7047): Auto country group 1: ch36
D/wpa_supplicant( 7047): wlan0: Added interface wlan0
D/wpa_supplicant( 7047): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 7047): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 7047): netlink: Operstate: ifindex=31 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 7047): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 7047): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 7047): RTM_NEWLINK: ifi_index=32 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 7047): RTM_NEWLINK: ifi_index=32 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 7047): RTM_NEWLINK: ifi_index=31 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 7047): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 7047): nl80211: Regulatory domain change
D/wpa_supplicant( 7047):  * initiator=1
D/wpa_supplicant( 7047):  * type=1
D/wpa_supplicant( 7047): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 7047): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=WORLD
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 7047): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 7047): P2P: Add operating class 81
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 7047): P2P: Add operating class 115
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 7047): P2P: Add operating class 116
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 7047): P2P: Add operating class 117
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 7047): P2P: Update channel list
D/wpa_supplicant( 7047): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 7047): P2P: cli_channels:
D/wpa_supplicant( 7047): p2p0: Updating hw mode
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 7047): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 7047): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 7047): nl80211: Regulatory domain change
D/wpa_supplicant( 7047):  * initiator=1
D/wpa_supplicant( 7047):  * type=0
D/wpa_supplicant( 7047):  * alpha2=DE
D/wpa_supplicant( 7047): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 7047): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 7047): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 7047): P2P: Add operating class 81
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 7047): P2P: Add operating class 115
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 7047): P2P: Add operating class 116
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 7047): P2P: Add operating class 117
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 7047): P2P: Update channel list
D/wpa_supplicant( 7047): P2P: channe,ls: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 7047): P2P: cli_channels:
D/wpa_supplicant( 7047): p2p0: Updating hw mode
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 7047): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  982): interfaceLinkStateChanged p2p0, false
D/Tethering(  982): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  982): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 7047): RTM_NEWLINK: ifi_index=32 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 7047): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_982-6\x00,
E/WifiStateMachine(  982): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  982): handleMessage: new destination call exit/enter
E/WifiStateMachine(  982): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null,
E/WifiStateMachine(  982): invokeExitMethods: InitialState,
E/WifiStateMachine(  982): moveTempStackToStateStack: i=0,j=1
D/WifiDisplayAdapter(  982): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  982):     Client/Owner: Client
D/WifiDisplayAdapter(  982):     GroupId: 
D/WifiDisplayAdapter(  982):     Passphrase: 
D/WifiDisplayAdapter(  982):     SessionId: 0
D/WifiDisplayAdapter(  982):     IP Address: }
E/WifiStateMachine(  982): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WIFI_ICON( 1236): updateWifiState: WIFI_STATE_CHANGED enabled
E/WifiStateMachine(  982): invokeEnterMethods: SupplicantStartingState
D/StatusBar.NetworkController( 1236): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131101
E/WifiStateMachine(  982): processMsg: SupplicantStartingState
E/WifiStateMachine(  982):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  982): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  982): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131101
E/WifiStateMachine(  982): processMsg: SupplicantStartingState
E/WifiStateMachine(  982):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  982): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  982): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=147457
E/WifiStateMachine(  982): processMsg: SupplicantStartingState
E/WifiStateMachine(  982):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiStateMachine(  982): Supplicant connection established
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 7047): set wifi ON
E/WifiStateMachine(  982): setWifiState: enabled
E/WifiStateMachine(  982): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  982):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 0 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 7047): SET_SCREEN_ON:Off
I/wpa_supplicant( 7047): htc_wext_set_keepalive +
I/wpa_supplicant( 7047): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 7047): getPrivFuncNum +	
I/wpa_supplicant( 7047): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 7047): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 7047): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 7047): get_ip_address source addr = ffffffff
I/wpa_supplicant( 7047): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 7047): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  982): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  982): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  982): handleScreenStateChanged Exit: false
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER MACADDR'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'update_config'='1'
D/wpa_s,upplicant( 7047): update_config=1
D/wpa_supplicant( 7047): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WifiConfigStore(  982): Loading config and enabling all networks 
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 7047): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 7047): wpa_supplicant_ctrl_iface_list_networks: return size = 47
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
I/IntentController( 1236): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 7047): Do not allow key_data field to be exposed
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
,D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/HtcWiFiWidget_WiFiWidgetProvider( 6996): onWiFiStateChanged() for widget: 
,W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 7047): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 7047): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/HtcWiFiWidget_WiFiWidgetProvider( 6996): updateWidget(context) for widget: 
E/WifiConfigStore(  982): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
,D/wpa_supplicant( 7047): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 7047): device_name='m8qlul_htc_europe'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 7047): manufacturer='HTC'
,W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 7047): model_name='HTC One M8s'
,W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 7047): model_number='HTC One M8s'
,W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 7047): config_methods='physical_display virtual_push_button'
,W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,E/WifiStateMachine(  982): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  982): handleMessage: new destination call exit/enter
E/WifiStateMachine(  982): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  982): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  982): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  982): moveTempStackToStateStack: i=0,j=2
,E/WifiStateMachine(  982): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  982): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 7047): wlan0: Setting scan interval: 15 sec
W/Settings( 6465): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  982): Setting external_sim to 1
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/WifiP2pService(  982): P2pDisabledState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  982): DefaultState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 7047): external_sim=1
D/WifiStateMachine(  982): Setting OUI to DA-A1-19
I/WifiNative-HAL(  982): startHal
E/wifi    (  982): getStaticLongField sWifiHalHandle 0x7f7580c360
I/WifiNative-HAL(  982): Could not start hal
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0",
D/wpa_supplicant( 7047): wlan0: Control interface command 'STA_AUTOCONNECT 0'
E/WifiStateMachine(  982): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  982): Driverstarted State enter
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
,D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  982): DriverStartedState call setCountryCode()
,E/WifiStateMachine(  982): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
,D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
,W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
,W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
,D/WifiDataStallTracker(  982): setDhcpActive: false
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 7047): wlan0: Control interface command 'STATUS'
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=87 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  982): transitionTo: destState=DisconnectedState
D/HTCRequest(  982): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/native  (  982): do suspend false
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/HTCRequest(  982): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/WifiMonitor(  982): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET ps 1',
D/wpa_supplicant( 7047): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 7047): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiP2pService(  982): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler },
E/WifiStateMachine(  982): Driverstarted State enter done
E/WifiStateMachine(  982): handleMessage: new destination call exit/enter
E/WifiStateMachine(  982): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  982): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  982): moveTempStackToStateStack: i=0,j=4
D/WifiScanningService(  982): SCAN_AVAILABLE : 3
E/WifiStateMachine(  982): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  982): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  982): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  982): DisconnectedState call setCountryCode()
D/RttService(  982): SCAN_AVAILABLE : 3
E/WifiStateMachine(  982):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/RttService(  982): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 7047): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 7047): wlan0: nl80211: sched_scan request
,D/libc    (  982): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
,D/libc    (  982): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiScanningService(  982): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  982): startHal
,I/QuickSettingWifi( 1236): receive.wifiState:WIFI_STATE_ENABLED setEnable:true,
,D/wpa_supplicant( 7047): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec,
D/wpa_supplicant( 7047): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiP2pService(  982): P2pEnablingState
D/wpa_supplicant( 7047): wlan0: nl80211: Sched scan started
D/WifiP2pService(  982): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  982): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  982): P2p socket connection successful
E/WifiStateMachine(  982): handleMessage: X
D/WifiP2pService(  982): P2pEnabledState
W/WifiHW  (  982): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/WifiP2pService(  982): sending p2p connection changed broadcast
D/wpa_supplicant( 7047): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/WifiDisplayController(  982): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/wpa_supplicant( 7047): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/WifiDisplayController(  982): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/wpa_supplicant( 7047): p2p0: Control interface command 'SET persistent_reconnect 1'
D/WifiDisplayController(  982): mWfdEnabled :false, networkInfo.isConnected() :false
D/wpa_supplicant( 7047): CTRL_IFACE SET 'persistent_reconnect'='1'
D/WifiDisplayAdapter(  982): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  982):     Client/Owner: Client
D/WifiDisplayAdapter(  982):     GroupId: 
D/WifiDisplayAdapter(  982):     Passphrase: 
D/WifiDisplayAdapter(  982):     SessionId: 0
D/WifiDisplayAdapter(  982):     IP Address: }
D/wpa_supplicant( 7047): persistent_reconnect=1
D/WifiP2pService(  982): DeviceAddress: 92:e7:c4:e6:4c:f8
D/wpa_supplicant( 7047): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 7047): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 7047): P2P: Set Operating channel: reg_class 126 channel 149
E/WifiStateMachine(  982): handleMessage: E msg.what=131154
E/WifiStateMachine(  982): processMsg: DisconnectedState
V/AudioService(  982): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  982):     Client/Owner: Client
V/AudioService(  982):     GroupId: 
V/AudioService(  982):     Passphrase: 
V/AudioService(  982):     SessionId: 0
V/AudioService(  982):     IP Address: }
E/WifiStateMachine(  982):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
D/HtcEffectManagerBase(  982): onEventChanged id=5 status=false
E/WifiStateMachine(  982): processMsg: ConnectModeState
D/HtcEffectManager(  982): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  982): convertEffect before=902
D/HtcEffectManager(  982): convertEffect after=902
W/WifiHW  (  982): QCOM Debug wifi_send_command "SET device_name Android_608e"
E/WifiStateMachine(  982):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
D/wpa_supplicant( 7047): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/WifiP2pService(  982): sending p2p persistent groups changed broadcast
D/wpa_supplicant( 7047): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
,D/WifiP2pService(  982): InactiveState
D/wpa_supplicant( 7047): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 7047): device_name='Android_608e'
E/wifi    (  982): getStaticLongField sWifiHalHandle 0x7f7257c520
I/WifiNative-HAL(  982): Could not start hal
E/WifiScanningService(  982): could not start HAL
W/WifiHW  (  982): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
D/wpa_supplicant( 7047): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 7047): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
,D/wpa_supplicant( 7047): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 7047): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 7047): P2P: New SSID postfix: -Android_608e
E/WifiStateMachine(  982):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
W/WifiHW  (  982): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 7047): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
,D/wpa_supplicant( 7047): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 7047): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'device_type'='10-0050F204-5'
W/WifiHW  (  982): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
E/WifiStateMachine(  982):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
D/wpa_supplicant( 7047): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 7047): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
E/WifiStateMachine(  982): processMsg: DefaultState
D/wpa_supplicant( 7047): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 7047): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 7047): config_methods='virtual_push_button physical_display keypad'
,W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 7047): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/WifiDisplayController(  982): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  982):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  982):  primary type: 10-0050F204-5
D/WifiDisplayController(  982):  secondary type: null
D/WifiDisplayController(  982):  wps: 0
D/WifiDisplayController(  982):  grpcapab: 0
D/WifiDisplayController(  982):  devcapab: 0
D/WifiDisplayController(  982):  status: 3
D/WifiDisplayController(  982):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  982):  WFD CtrlPort: 0
D/WifiDisplayController(  982):  WFD MaxThroughput: 0
I/wpa_supplicant( 7047): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 7047): Single channel concurrency preference: sta
E/WifiStateMachine(  982):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
,D/WifiNative-HAL(  982): p2pGetDeviceAddress
W/WifiHW  (  982): QCOM Debug wifi_send_command "STATUS"
E/WifiStateMachine(  982): handleMessage: X
D/wpa_supplicant( 7047): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
E/WifiStateMachine(  982): handleMessage: E msg.what=131323
E/WifiStateMachine(  982): processMsg: DisconnectedState
D/WifiNative-HAL(  982): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_FLUSH"
E/WifiStateMachine(  982):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
D/wpa_supplicant( 7047): p2p0: Control interface command 'P2P_FLUSH'
,I/wpa_supplicant( 7047): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 7047): P2P: Stopping find
D/wpa_supplicant( 7047): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 7047): P2P: State IDLE -> IDLE
D/wpa_supplicant( 7047): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 7047): P2P: Stopping find
D/wpa_supplicant( 7047): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 7047): P2P: State IDLE -> IDLE
D/wpa_supplicant( 7047): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  982): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
,E/WifiStateMachine(  982):  ConnectModeState what:131323 0 0
D/wpa_supplicant( 7047): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
E/WifiStateMachine(  982): processMsg: DriverStartedState
I/wpa_supplicant( 7047): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  982): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 7047): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 7047): wpa_supplicant_ctrl_iface_list_networks: return size = 34
E/WifiStateMachine(  982):  DriverStartedState what:131323 0 0
W/WifiHW  (  982): QCOM Debug wifi_send_command "SAVE_CONFIG"
,E/WifiStateMachine(  982): processMsg: SupplicantStartedState
D/wpa_supplicant( 7047): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 7047): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 7047): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 7047): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  982):  SupplicantStartedState what:131323 0 0
D/wpa_supplicant( 7047): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
E/WifiStateMachine(  982): processMsg: DefaultState
D/wpa_supplicant( 7047): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 7047): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  982):  DefaultState what:131323 0 0
E/WifiStateMachine(  982): setOperatorSSID enter
E/WifiStateMachine(  982): handleMessage: X
,E/WifiStateMachine(  982): handleMessage: E msg.what=131104
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState what:131104 0 0
W/Settings(  982): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 7047): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 7047): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 7047): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
,E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=131162
E/WifiStateMachine(  982): processMsg: DisconnectedState
E/WifiStateMachine(  982):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  982): processMsg: DriverStartedState
,E/WifiStateMachine(  982):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  982): set frequency band 0
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 7047): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 7047): SETBAND: 0
D/wpa_supplicant( 7047): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 7047): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 7047): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  982): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  982): WifiMonitor:wlan0 cnt=88 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  982): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  982): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 7047): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 7047): P2P: Add operating class 81
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 7047): P2P: Add operating class 115
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 7047): P2P: Add operating class 116
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 7047): P2P: Add operating class 117
D/wpa_supplicant( 7047): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 7047): P2P: Update channel list
D/wpa_supplicant( 7047): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/wpa_supplicant( 7047): P2P: cli_channels:
D/wpa_supplicant( 7047): p2p0: Updating hw mode
D/wpa_supplicant( 7047): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 7047): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 7047): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 7047): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 7047): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  982): did set frequency band 0
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 7047): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  982): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 7047): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 7047): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 7047): wlan0: Cancelling sched scan
D/wpa_supplicant( 7047): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 7047): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 7047): wpa_supplicant_scan enter
D/wpa_supplicant( 7047): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 7047): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 7047): wlan0: nl80211: Sched scan stopped,
D/wpa_supplicant( 7047): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  982): done set frequency band 0
,D/WifiStateMachine(  982): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiStateMachine(  982): [MLHD] enter handleMediaLinkEvent DriverStartedState
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=147462
E/WifiStateMachine(  982): processMsg: DisconnectedState
,E/WifiStateMachine(  982):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 87 0 rt=512358  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  982): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  982): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 87 0 rt=512358  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  982): handleMessage: X
E/WifiStateMachine(  982): handleMessage: E msg.what=143371
E/WifiStateMachine(  982): processMsg: DisconnectedState
,E/WifiStateMachine(  982):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  982): processMsg: ConnectModeState
E/WifiStateMachine(  982):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  982): processMsg: DriverStartedState
,E/WifiStateMachine(  982):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  982): processMsg: SupplicantStartedState
E/WifiStateMachine(  982):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  982): processMsg: DefaultState
E/WifiStateMachine(  982):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  982): handleMessage: X
,D/wpa_supplicant( 7047): EAPOL: disable timer tick,
,D/wpa_supplicant( 7047): EAPOL: disable timer tick
,D/PMS     (  982): acquireWL(3ae340b1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 982 1000 WorkSource{1000},
V/AlarmManager(  982): sending alarm PendingIntent{1112d5aa: PendingIntentRecord{2d9af59b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397774, Int=0
V/AlarmManager(  982): sending alarm PendingIntent{a5ea996: PendingIntentRecord{3aacc043 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=515233, Int=0
D/PMS     (  982): acquireWL(1fe1917): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1971): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1971): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1971): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1971): [NET] android_getaddrinfo_proxy+
D/libc    ( 1971): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1971): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  982): releaseWL(1fe1917): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  982): releaseWL(3ae340b1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1236): Weather sync is On
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,I/ActivityManager(  982): Waited long enough for: ServiceRecord{3f14624b u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  418): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  982): acquireWL(39fe104): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null,
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(39fe104): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  982): updateBatteryInfo
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  982): runPSCheck
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  982): Checking...
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  982): >> updateStatus
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  982): battery changed pluggedType: 2
D/WifiController(  982): handleMessage: E msg.what=155652
D/PowerUI ( 1236): closing low battery warning: level=100
D/WifiController(  982): processMsg: DeviceActiveState
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): processMsg: StaEnabledState
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  982): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1675): service - handleMessage() stop self,
,D/AutoSetting( 1675): service - handleMessage() quit looper
,D/AutoSetting( 1675): service - onDestroy() END
,D/PMS     (  982): releaseWL(114221e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  982): Failed to find a new network - expiring NetTransition Wakelock
,D/PMS     (  982): acquireWL(eba36ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(eba36ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  982): updateBatteryInfo
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1236): closing low battery warning: level=100
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/PMS     (  982): runPSCheck
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  982): Checking...
,D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  982): >> updateStatus
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/WifiController(  982): handleMessage: E msg.what=155652
D/WifiController(  982): processMsg: DeviceActiveState
D/WifiController(  982): battery changed pluggedType: 2
D/WifiController(  982): processMsg: StaEnabledState
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
,I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  982): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1562): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1562): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1562): sku_id=118
D/ContactMessageStore( 1562): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1562): start background delete task...
,D/ContactMessageStore( 1562): size: 0 , 0
D/ContactMessageStore( 1562): Background delete complete
,D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  982): acquireWL(2a53c922): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  982): n_update end
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/PMS     (  982): releaseWL(2a53c922): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  982): updateBatteryInfo
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  982): runPSCheck
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  982): Checking...
D/WifiController(  982): handleMessage: E msg.what=155652
I/HtcPowerSaver(  982): >> updateStatus
D/WifiController(  982): processMsg: DeviceActiveState
D/WifiController(  982): battery changed pluggedType: 2
D/WifiController(  982): processMsg: StaEnabledState
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  982): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  982): acquireWL(3f412fb3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 982 1000 WorkSource{1000},
V/AlarmManager(  982): sending alarm PendingIntent{1112d5aa: PendingIntentRecord{2d9af59b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=517774, Int=0
,I/ActivityManager(  982): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7053 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  982): sending alarm PendingIntent{22bc0970: PendingIntentRecord{119054e9 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1451989704511, Int=0
,D/PMS     (  982): releaseWL(3f412fb3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1236): Weather sync is On
,W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data,
,E/cutils-trace( 7075): Error opening trace file: Permission denied (13),
I/dex2oat ( 7075): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,I/dex2oat ( 7075): dex2oat: override thread count:4
,I/dex2oat ( 7075): dex2oat took 559.253ms (threads: 4),
,I/PushClient( 7053): ApplicationMonitor {2ea98b31}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 7053): ApplicationMonitor {2ea98b31}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
,I/PushClient( 7053): ApplicationMonitor {2ea98b31}: logBasicAppInfo(): VersionName:             1.2.853019,
,I/PushClient( 7053): ApplicationMonitor {2ea98b31}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7053): ApplicationMonitor {2ea98b31}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7053): ApplicationMonitor {2ea98b31}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7053): ApplicationMonitor {2ea98b31}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7053): ApplicationMonitor {2ea98b31}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 7053): ApplicationMonitor {2ea98b31}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7053): PnsModel {2c8a8bd8}: update(): Update registration caused by: alarm,
,I/PushClient( 7053): PnsConfigModel {130df28f}: <init>(): Use dm-client for provisioning.
,W/System.err( 7053): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 7053): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 7053): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7053): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  982): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7082 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7082): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7082 dbg=false s=true,
,I/DeviceManagement( 7082): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 7082): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7082): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 7082): WorkflowService: Starting workflow service,
,I/DeviceManagement( 7082): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1c981abb] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 7082): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7082): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 7082): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7082): SessionStateController: Checking invariants...
,I/DeviceManagement( 7082): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7082): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7082): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7082): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1c981abb],
,I/DeviceManagement( 7082): WorkflowService: Stopping workflow service
,I/ActivityManager(  982): Killing 6590:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
D/Process (  982): killProcessQuiet, pid=6590
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  982): Recipient 6590
,D/WifiService(  982): Client connection lost with reason: 4
,I/PushClient( 7053): PnsModel {2c8a8bd8}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  982): killProcessQuiet, pid=6649
I/ActivityManager(  982): Killing 6649:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  982): Recipient 6649,
,D/PMS     (  982): acquireWL(31e4bed2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(31e4bed2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  982): updateBatteryInfo
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/PMS     (  982): runPSCheck
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  982): Checking...
D/UsbnetService(  982): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  982): >> updateStatus
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/WifiController(  982): battery changed pluggedType: 2
,D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1236): closing low battery warning: level=100
D/WifiController(  982): handleMessage: E msg.what=155652
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  982): processMsg: DeviceActiveState
I/HtcPowerSaver(  982): << updateStatus
D/WifiController(  982): processMsg: StaEnabledState
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  982): acquireWL(18f56ba3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
,D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/PMS     (  982): releaseWL(18f56ba3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  982): updateBatteryInfo
,D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/PMS     (  982): runPSCheck
D/WifiController(  982): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  982): Checking...
D/WifiController(  982): processMsg: DeviceActiveState
I/HtcPowerSaver(  982): >> updateStatus
D/WifiController(  982): processMsg: StaEnabledState
D/PowerUI ( 1236): closing low battery warning: level=100
D/WifiController(  982): processMsg: DefaultState
,D/WifiController(  982): battery changed pluggedType: 2
D/WifiController(  982): handleMessage: X
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  982): << updateStatus
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  982): acquireWL(a5caea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(a5caea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  982): updateBatteryInfo
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/PowerUI ( 1236): closing low battery warning: level=100
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  982): plugged=true pluggin=true,
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/PMS     (  982): runPSCheck
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  982): Checking...
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  982): >> updateStatus
,D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/WifiController(  982): battery changed pluggedType: 2
D/WifiController(  982): handleMessage: E msg.what=155652
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): processMsg: DeviceActiveState
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  982): processMsg: StaEnabledState
,I/HtcPowerSaver(  982): << updateStatus
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  982): acquireWL(166b4a59): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 982 1000 WorkSource{1000}
,V/AlarmManager(  982): sending alarm PendingIntent{1112d5aa: PendingIntentRecord{2d9af59b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=697774, Int=0
I/bt-btm  ( 3119): Received oneshot timer event complete
V/AlarmManager(  982): sending alarm PendingIntent{162bf61e: PendingIntentRecord{ee91eff com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=943326, Int=0,
I/bt-btm  ( 3119): btm_ble_timeout
I/bt-btm  ( 3119): btm_gen_resolvable_private_addr
,D/PMS     (  982): acquireWL(18ee14cc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3119 1002 null,
,D/bt-btm  ( 3119): btm_ble_rand_enc_complete,
I/bt-btm  ( 3119): btm_gen_resolve_paddr_low
D/bt-smp  ( 3119): smp_encrypt_data
W/bt-smp  ( 3119): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3119): Plain text(LSB ~ MSB) = ff 98 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3119): Encrypted text(LSB ~ MSB) = 48 a6 68 86 e4 91 81 01 fb 3a 90 f9 61 47 a3 7c 
I/bt-btm  ( 3119): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3119): Stopping oneshot timer
D/bt-btm  ( 3119): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  982): releaseWL(166b4a59): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1236): Weather sync is On
,W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,D/PMS     (  982): releaseWL(18ee14cc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  982): acquireWL(97d3315): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(97d3315): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/HtcPowerSaver(  982): updateBatteryInfo
,D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/PMS     (  982): runPSCheck
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  982): Checking...
D/UsbnetService(  982): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  982): >> updateStatus
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  982): battery changed pluggedType: 2
D/WifiController(  982): handleMessage: E msg.what=155652
D/PowerUI ( 1236): closing low battery warning: level=100
D/WifiController(  982): processMsg: DeviceActiveState
D/WifiController(  982): processMsg: StaEnabledState
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  982): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  982): acquireWL(71d562a): PARTIAL_WAKE_LOCK  *alarm* 0x1 982 1000 WorkSource{1000}
V/AlarmManager(  982): sending alarm PendingIntent{17c6c896: PendingIntentRecord{2ac54c17 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806406, Int=0
,V/AlarmManager(  982): sending alarm PendingIntent{1112d5aa: PendingIntentRecord{2d9af59b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=997774, Int=0
V/AlarmManager(  982): sending alarm PendingIntent{63aac1b: PendingIntentRecord{c3c576a com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451990012623, Int=0
,I/ActivityManager(  982): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=7108 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/WeatherUtility( 1236): Weather sync is On
,W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,W/ContextImpl( 7108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  982): releaseWL(71d562a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 7108): MY_DEBUG = false,
,D/PowerUsageService( 7108): repeat time = 1451990940242,
,I/PowerUsageList:PowerUsageHelper( 7108): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 7108): gen(), null == sipper.uidObj, userId = 0,
,D/Process (  982): killProcessQuiet, pid=4857
I/ActivityManager(  982): Killing 4857:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  982): Recipient 4857
,D/PMS     (  982): acquireWL(c8aeb91): PARTIAL_WAKE_LOCK  *alarm* 0x1 982 1000 WorkSource{1000},
,V/AlarmManager(  982): sending alarm PendingIntent{2e12aaf6: PendingIntentRecord{3e4deef7 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1451990057795, Int=0
,D/SmartSyncUtils( 7108): isEpsOn(), nState = 0
,D/PMS     (  982): acquireWL(10083164): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7108 1000 null,
,D/PMS     (  982): releaseWL(c8aeb91): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  982): releaseWL(10083164): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  982): acquireWL(29e1afcd): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7108 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 7108): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 7108): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 7108): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 7108): SettingOnTime = 1452060000000, randomSettingOnTime = 1452058159000
,D/SmartSyncScreenOnOffTimeReceiver( 7108): SettingOffTime = 1452038400000, randomSettingOffTime = 1452041896000
,D/SmartSyncScreenOnOffTimeReceiver( 7108): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 7108): bNightMode = true,
D/SmartSyncScreenOnOffTimeReceiver( 7108): bNightModeTurnOffOnce = false
,D/PMS     (  982): releaseWL(29e1afcd): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  982): acquireWL(1e368082): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(1e368082): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  982): updateBatteryInfo
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  982): plugged=true pluggin=true
,D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  982): runPSCheck
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/WifiController(  982): battery changed pluggedType: 2
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  982): Checking...
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/HtcPowerSaver(  982): >> updateStatus
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/PowerUI ( 1236): closing low battery warning: level=100
D/WifiController(  982): handleMessage: E msg.what=155652
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): processMsg: DeviceActiveState
D/WifiController(  982): processMsg: StaEnabledState
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  982): << updateStatus
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  982): acquireWL(1ee88393): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
,D/UsbnetService(  982): BroadcastReceiver::onReceive+
I/BatteryService(  982): n_update end
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/PMS     (  982): releaseWL(1ee88393): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  982): updateBatteryInfo
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/PMS     (  982): runPSCheck
D/WifiController(  982): handleMessage: E msg.what=155652
D/HtcPowerSaver(  982): Checking...
D/WifiController(  982): processMsg: DeviceActiveState
I/HtcPowerSaver(  982): >> updateStatus
D/WifiController(  982): processMsg: StaEnabledState
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  982): << updateStatus
D/WifiController(  982): processMsg: DefaultState
D/NotificationService(  982): plugged=true pluggin=true
D/WifiController(  982): handleMessage: X
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  982): battery changed pluggedType: 2
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/PowerUI ( 1236): closing low battery warning: level=100
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  982): User[0] Flushing usage stats to disk
,D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  982): acquireWL(17c8ffd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  982): n_update end
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  982): releaseWL(17c8ffd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  982): updateBatteryInfo
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  982): battery changed pluggedType: 2
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/PMS     (  982): runPSCheck
,D/WifiController(  982): handleMessage: E msg.what=155652
D/HtcPowerSaver(  982): Checking...
D/WifiController(  982): processMsg: DeviceActiveState
I/HtcPowerSaver(  982): >> updateStatus
D/WifiController(  982): processMsg: StaEnabledState
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  982): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  982): acquireWL(9667bc9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(9667bc9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/PowerUI ( 1236): closing low battery warning: level=100
D/HtcPowerSaver(  982): updateBatteryInfo
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  982): BroadcastReceiver::onReceive+
,D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/PMS     (  982): runPSCheck
,D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  982): Checking...
D/UsbnetService(  982): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  982): >> updateStatus
D/WifiController(  982): handleMessage: E msg.what=155652
D/WifiController(  982): battery changed pluggedType: 2
D/WifiController(  982): processMsg: DeviceActiveState
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  982): processMsg: StaEnabledState
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  982): processMsg: DefaultState
I/HtcPowerSaver(  982): << updateStatus
D/WifiController(  982): handleMessage: X
,D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  982): acquireWL(d022ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
D/UsbnetService(  982): BroadcastReceiver::onReceive+
I/BatteryService(  982): n_update end
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/PMS     (  982): releaseWL(d022ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  982): updateBatteryInfo
D/WifiController(  982): handleMessage: E msg.what=155652
D/WifiController(  982): battery changed pluggedType: 2
D/WifiController(  982): processMsg: DeviceActiveState
D/PMS     (  982): runPSCheck
D/WifiController(  982): processMsg: StaEnabledState
D/HtcPowerSaver(  982): Checking...
D/WifiController(  982): processMsg: DefaultState
I/HtcPowerSaver(  982): >> updateStatus
,D/WifiController(  982): handleMessage: X
D/PowerUI ( 1236): closing low battery warning: level=100
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  982): << updateStatus
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  982): acquireWL(3c8dc5ef): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(3c8dc5ef): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  982): updateBatteryInfo
D/PMS     (  982): runPSCheck
D/HtcPowerSaver(  982): Checking...
I/HtcPowerSaver(  982): >> updateStatus
D/PowerUI ( 1236): closing low battery warning: level=100
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  982): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  982): << updateStatus
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/WifiController(  982): battery changed pluggedType: 2
,I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  982): handleMessage: E msg.what=155652
D/WifiController(  982): processMsg: DeviceActiveState
D/WifiController(  982): processMsg: StaEnabledState
D/WifiController(  982): processMsg: DefaultState
,D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  982): handleMessage: X
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  982): acquireWL(12520b85): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 982 1000 WorkSource{1000}
I/bt-btm  ( 3119): Received oneshot timer event complete
V/AlarmManager(  982): sending alarm PendingIntent{1112d5aa: PendingIntentRecord{2d9af59b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1057774, Int=0
V/AlarmManager(  982): sending alarm PendingIntent{3a4f9dda: PendingIntentRecord{69ad20b com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1843349, Int=0
I/bt-btm  ( 3119): btm_ble_timeout
I/bt-btm  ( 3119): btm_gen_resolvable_private_addr
,D/PMS     (  982): acquireWL(3b6cf8e8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3119 1002 null,
,D/bt-btm  ( 3119): btm_ble_rand_enc_complete
I/bt-btm  ( 3119): btm_gen_resolve_paddr_low
D/bt-smp  ( 3119): smp_encrypt_data
W/bt-smp  ( 3119): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 3119): Plain text(LSB ~ MSB) = 7f 57 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3119): Encrypted text(LSB ~ MSB) = 1b 15 58 91 62 96 c2 db 7d 39 1c 56 fd 4c 5d bd 
I/bt-btm  ( 3119): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3119): Stopping oneshot timer
D/bt-btm  ( 3119): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  982): Prepared write state in 22ms,
,I/ProcessStatsService(  982): Prepared write state in 7ms,
,I/ProcessStatsService(  982): Prepared write state in 7ms,
,D/PMS     (  982): releaseWL(12520b85): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1236): Weather sync is On,
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,I/ProcessStatsService(  982): Pruning old procstats: /data/system/procstats/state-2016-01-04-16-01-01.bin
,D/PMS     (  982): releaseWL(3b6cf8e8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  982): acquireWL(2cacdb01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(2cacdb01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  982): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  982): updateBatteryInfo
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/NotificationService(  982): plugged=true pluggin=true
D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  982): runPSCheck
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  982): Checking...
I/HtcPowerSaver(  982): >> updateStatus
D/WifiController(  982): handleMessage: E msg.what=155652
D/WifiController(  982): processMsg: DeviceActiveState
D/WifiController(  982): battery changed pluggedType: 2
D/WifiController(  982): processMsg: StaEnabledState
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  982): << updateStatus
D/PowerUI ( 1236): closing low battery warning: level=100
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  982): acquireWL(1419bda6): PARTIAL_WAKE_LOCK  *alarm* 0x1 982 1000 WorkSource{1000}
,V/AlarmManager(  982): sending alarm PendingIntent{17c6c896: PendingIntentRecord{2ac54c17 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1717809, Int=0
V/AlarmManager(  982): sending alarm PendingIntent{1112d5aa: PendingIntentRecord{2d9af59b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1897774, Int=0
V/AlarmManager(  982): sending alarm PendingIntent{3b2283e7: PendingIntentRecord{c3c576a com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451990940242, Int=0
,W/ContextImpl( 7108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 7108): MY_DEBUG = false
D/PMS     (  982): releaseWL(1419bda6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageService( 7108): repeat time = 1451991840292
D/WeatherUtility( 1236): Weather sync is On
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,I/PowerUsageList:PowerUsageHelper( 7108): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 7108): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  982): acquireWL(1e8b263d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 982 1000 null
I/BatteryService(  982): n_update end
D/PMS     (  982): releaseWL(1e8b263d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  982): updateBatteryInfo
,D/UsbnetService(  982): BroadcastReceiver::onReceive+,
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  982): onReceive BATTERY_CHANGED
D/NotificationService(  982): plugged=true pluggin=true
,D/UsbnetService(  982):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  982): runPSCheck
D/UsbnetService(  982): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  982): Checking...
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  982): >> updateStatus
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  982): battery changed pluggedType: 2
D/DotMatrix( 1359): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/DotMatrix( 1359): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  982): handleMessage: E msg.what=155652
I/HtcPowerSaver(  982): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  982): processMsg: DeviceActiveState
I/HtcPowerSaver(  982): << updateStatus
D/WifiController(  982): processMsg: StaEnabledState
D/WifiController(  982): processMsg: DefaultState
D/WifiController(  982): handleMessage: X
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 7142): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7142): ====startRecUseTime====
D/htc.customization.log.level( 7142):  is 
W/CustomizationLogLevel( 7142): Level value is invalid, use default level 2
D/CustomizationManager( 7142):  Read ACC file spent 0.042 (s)
D/CIDMapFileReader( 7142): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7142): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7142): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7142): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7142): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7142): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7142): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7142): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7142): Parsing tag category name = system
I/CustomizationCIDLoader( 7142): Parsing tag category name = application
I/CustomizationCIDLoader( 7142): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7142): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7142): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7142): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7142): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7142): add string-array item, value = 42507
I/CustomizationCIDLoader( 7142): add string-array item, value = 21902
I/CustomizationCIDLoader( 7142): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7142): add string-array item, value = 23420
I/CustomizationCIDLoader( 7142): add string-array item, value = 22299
I/CustomizationCIDLoader( 7142): add string-array item, value = 24002
I/CustomizationCIDLoader( 7142): add string-array item, value = 23210
I/CustomizationCIDLoader( 7142): add string-array item, value = 23205
I/CustomizationCIDLoader( 7142): add string-array item, value = 23806
I/CustomizationCIDLoader( 7142): add string-array item, value = 23430
I/CustomizationCIDLoader( 7142): add string-array item, value = 23408
I/CustomizationCIDLoader( 7142): add string-array item, value = 27205
I/CustomizationCIDLoader( 7142): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7142): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7142):  Read CID file spent 0.088 (s)
D/CustomizationManager( 7142):  All configurations done spent 0.089 (s)
D/PackageManager(  982): deletePackageAsUser: pkg=com.test.thalitest, pid=7142, uid=2000 userid=0
I/ActivityManager(  982): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  982): killProcessQuiet, pid=6694
I/ActivityManager(  982): Killing 6694:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  982): Skipping PackageSetting{28e74dc6 com.example.hello/10374} due to missing metadata
I/ActivityManager(  982): Recipient 6694
I/WindowState(  982): WIN DEATH: Window{231ea599 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/InputEventReceiver( 1425): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{3f2b0255 uid 10366 pid 6694} (c)'
D/WifiService(  982): Client connection lost with reason: 4
I/bt-btif ( 3119): BTA_JvDeleteRecord
D/bt-sdp  ( 3119): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 3119): BTA_JvRfcommStopServer
D/bt-btm  ( 3119): BTM_FreeSCN 
I/bt-btm  ( 3119): BTM_SEC_CLR[19]: id 61
I/ActivityManager(  982):   Force finishing activity ActivityRecord{3573490a u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  982): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  982):   Force finishing activity ActivityRecord{3573490a u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  982): Duplicate finish request for ActivityRecord{3573490a u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  982): Spurious death for ProcessRecord{37140e32 6694:com.test.thalitest/u0a366}, curProc for 6694: null
D/DotMatrix( 1359): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1359): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1359): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  982): acquireWL(1b43fd00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1879 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1879): Ignoring removeGeofence because network location is disabled.
W/SystemReader(  982): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1760): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  982): releaseWL(1b43fd00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1760): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PhoneApp( 1562): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/VoicemailCleanupService( 1721): Cleaning up data for package: com.test.thalitest
I/[PluginManager]RegisterService( 1675): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/art     ( 1611): Explicit concurrent mark sweep GC freed 2628(145KB) AllocSpace objects, 7(604KB) LOS objects, 34% free, 29MB/45MB, paused 944us total 78.584ms
D/Prism.PackageStateRece_( 1611): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1611): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1611): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1760): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1611): Deferring update until onResume
D/Launcher( 1611): waitUntilResume // bindAppsRemoved
I/[PluginManager]RegisterService( 1675): handle notify Blinkfeed plugin client changed
I/ActivityManager(  982): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7162 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/ExternalAccountType( 1760): Unsupported attribute readOnly
I/InputMethodManagerService(  982): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/art     (  982): Explicit concurrent mark sweep GC freed 54891(3MB) AllocSpace objects, 15(1428KB) LOS objects, 33% free, 16MB/25MB, paused 1.616ms total 193.579ms
I/art     (  982): WaitForGcToComplete blocked for 190.471ms for cause Explicit
D/StatusBarManagerService(  982): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  982): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  982): hiding MENU key
D/StatusBarManagerService(  982): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  982): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  982): hiding MENU key
D/FindExtension( 1611): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/ContextImpl( 7162): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
I/ThreadedRenderer( 1611): Defer allocateBuffers to drawing time
W/InputMethodManagerService(  982): Got RemoteException sending setActive(false) notification to pid 6694 uid 10366
D/StatusBarManagerService(  982): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  982): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7190 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  982): killProcessQuiet, pid=6625
I/ActivityManager(  982): Killing 6625:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager(  982): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/PackageManager(  982): Unable to load service info ResolveInfo{2731fb60 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  982): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  982): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  982): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  982): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  982): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  982): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  982): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  982): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  982): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  982): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  982): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  982): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  982): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  982): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  982): Recipient 6625
D/JobSchedulerService(  982): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  982): Explicit concurrent mark sweep GC freed 8748(459KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 5.498ms total 236.150ms
D/TaskPersister(  982): removeObsoleteFile: deleting file=8_task.xml
I/PhoneStatusBar( 1236): setImeWindowStatus(false,false)
W/asset   (  982): Copying FileAsset 0x55b5c269c0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/PackageManager(  982):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7190, uid=10072, userID:0
W/global  ( 7190): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 7190): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 7190): [apache-http] Connection GC has been deprecated!
W/global  ( 7190): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 7190): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  982): acquireWL(2e03313): PARTIAL_WAKE_LOCK  *alarm* 0x1 982 1000 WorkSource{1000}
V/AlarmManager(  982): sending alarm PendingIntent{10f22b7e: PendingIntentRecord{21d118df android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1826305, Int=1800000
V/AlarmManager(  982): sending alarm PendingIntent{1cb7b950: PendingIntentRecord{18907749 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1856002, Int=0
I/ActivityManager(  982): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7227 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 7190): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7190): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PackageManager(  982):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7190, uid=10072, userID:0
W/ResourcesManager( 7227): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7227): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7227): VM with version 2.1.0 has multidex support
I/MultiDex( 7227): install
I/MultiDex( 7227): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  982): Killing 6757:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  982): killProcessQuiet, pid=6757
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager(  982): Recipient 6757
D/Finsky  ( 7190): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7190): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 7190): [1] GmsCoreHelper.cleanupNlp: result=false type=4
E/SQLiteLog( 1971): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1971): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x55b55c0f90
E/AndroidRuntime( 1971): FATAL EXCEPTION: main
E/AndroidRuntime( 1971): Process: com.google.process.gapps, PID: 1971
E/AndroidRuntime( 1971): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1971): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1971): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1971): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1971): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1971): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1971): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1971): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1971): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1971): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1971): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1971): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1971): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1971): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1971): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1971): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1971): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1971): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1971): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1971): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1971): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1971): 	... 9 more
E/ActivityManager(  982): App crashed! Process: com.google.process.gapps
V/JNIHelp ( 7227): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Process ( 1971): killProcess, pid=1971
D/Process ( 1971): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  982): Can't write: system_app_crash
E/DropBoxManagerService(  982): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  982): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  982): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  982): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  982): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  982): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  982): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  982): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  982): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  982): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  982): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  982): 	... 5 more
W/ActivityThread( 7227): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7227): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b2a3d68: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7227): Installed default security provider GmsCore_OpenSSL
D/Finsky  ( 7190): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/JavaBinder( 4440): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  982): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue(  982): Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
W/BroadcastQueue(  982): android.os.TransactionTooLargeException
W/BroadcastQueue(  982): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  982): 	at android.os.BinderProxy.transact(Binder.java:504)
W/BroadcastQueue(  982): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:921)
W/BroadcastQueue(  982): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:254)
W/BroadcastQueue(  982): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:989)
W/BroadcastQueue(  982): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17013)
W/BroadcastQueue(  982): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:475)
W/BroadcastQueue(  982): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/BroadcastQueue(  982): 	at android.os.Binder.execTransact(Binder.java:454)
W/GmsClient( 4440): Remote exception occurred
W/GmsClient( 4440): android.os.TransactionTooLargeException
W/GmsClient( 4440): 	at android.os.BinderProxy.transactNative(Native Method)
W/GmsClient( 4440): 	at android.os.BinderProxy.transact(Binder.java:504)
W/GmsClient( 4440): 	at com.google.android.gms.common.internal.bu.b(SourceFile:1948)
W/GmsClient( 4440): 	at com.google.android.gms.common.internal.aq.a(SourceFile:1297)
W/GmsClient( 4440): 	at com.google.android.gms.common.api.ar.a(SourceFile:906)
W/GmsClient( 4440): 	at com.google.android.gms.common.api.au.run(SourceFile:799)
W/GmsClient( 4440): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/GmsClient( 4440): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/GmsClient( 4440): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/GmsClient( 4440): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/GmsClient( 4440): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  982): Recipient 1971
I/ActivityThread( 7227): Removing dead content provider:android.content.ContentProviderProxy@16220581
W/ActivityManager(  982): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
W/ActivityManager(  982): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 11000ms
W/ActivityManager(  982): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
W/ActivityManager(  982): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
I/ActivityManager(  982): Start proc com.google.process.gapps for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver: pid=7262 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ActivityManager(  982): Spurious death for ProcessRecord{2f1acf2d 7262:com.google.process.gapps/u0a24}, curProc for 1971: null
I/GservicesProvider( 7262): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 7262): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7262): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7262): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7262): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7262): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7262): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7262): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7262): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7262): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7262): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7262): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7262): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7262): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7262): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7262): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7262): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7262): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7262): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7262): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7262): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7262): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7262): FATAL EXCEPTION: main
E/AndroidRuntime( 7262): Process: com.google.process.gapps, PID: 7262
E/AndroidRuntime( 7262): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7262): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7262): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7262): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7262): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7262): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7262): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7262): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7262): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7262): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7262): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7262): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7262): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7262): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7262): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7262): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7262): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7262): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7262): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7262): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7262): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7262): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7262): 	... 11 more
E/ActivityManager(  982): App crashed! Process: com.google.process.gapps
W/ActivityManager(  982): Process com.google.process.gapps has crashed too many times: killing!
D/Process (  982): killProcessQuiet, pid=7262
I/ActivityManager(  982): Killing 7262:com.google.process.gapps/u0a24 (adj 0): crash
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12134 
E/DropBoxManagerService(  982): Can't write: system_app_crash
E/DropBoxManagerService(  982): java.io.FileNotFoundException: /data/system/dropbox/drop150.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  982): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  982): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  982): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  982): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  982): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  982): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  982): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  982): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  982): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  982): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  982): 	... 5 more
I/ActivityManager(  982): Recipient 7262
D/Process (  982): killProcessQuiet, pid=7227
I/ActivityManager(  982): Killing 7227:com.google.android.gms:car/u0a24 (adj 0): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
D/Process (  982): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:15264 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:15341 
W/ActivityManager(  982): Unable to launch app com.google.android.gsf/10024 for provider com.google.android.gsf.gservices: launching app became null
I/Prism.ItemManager( 1611): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1611): loadItems() com.htc.launcher.pageview.WidgetManager@27294ea8 +
I/Prism.WidgetManager( 1611): onLoadItems() +
W/ResourcesManager( 1611): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  982): Recipient 7227
W/ActivityManager(  982): Spurious death for ProcessRecord{2f1acf2d 7262:com.google.process.gapps/u0a24}, curProc for 7262: null
W/ActivityManager(  982): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
V/AlarmManager(  982): sending alarm PendingIntent{1edd537b: PendingIntentRecord{1732a96e com.android.vending startService}}, i=null, t=0, cnt=1, w=1451990986181, Int=0
D/Finsky  ( 7190): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/ActivityManager(  982): Start proc com.google.process.gapps for service com.google.android.gms/.auth.GoogleAccountAuthenticatorService: pid=7285 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 1611): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7285): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7285): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7285): VM with version 2.1.0 has multidex support
I/MultiDex( 7285): install
I/MultiDex( 7285): VM has multidex support, MultiDex support library is disabled.
I/GservicesProvider( 7285): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 7285): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7285): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7285): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7285): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7285): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7285): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7285): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7285): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7285): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7285): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7285): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7285): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7285): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7285): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7285): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7285): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7285): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7285): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7285): FATAL EXCEPTION: main
E/AndroidRuntime( 7285): Process: com.google.process.gapps, PID: 7285
E/AndroidRuntime( 7285): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7285): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7285): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7285): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7285): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7285): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7285): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7285): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7285): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7285): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7285): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7285): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7285): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7285): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7285): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7285): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7285): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7285): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7285): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7285): 	... 11 more
E/DropBoxManagerService(  982): Can't write: system_app_crash
E/DropBoxManagerService(  982): java.io.FileNotFoundException: /data/system/dropbox/drop151.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  982): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  982): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  982): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  982): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  982): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  982): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  982): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  982): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  982): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  982): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  982): 	... 5 more
E/ActivityManager(  982): App crashed! Process: com.google.process.gapps
D/Process ( 7285): killProcess, pid=7285
D/Process ( 7285): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/asset   ( 1611): Copying FileAsset 0x55b5a5c210 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/ActivityManager(  982): Recipient 7285
I/ActivityManager(  982): Process com.google.process.gapps (pid 7285) has died
W/ActivityManager(  982): Scheduling restart of crashed service com.google.android.gms/.auth.GoogleAccountAuthenticatorService in 10728ms

```
