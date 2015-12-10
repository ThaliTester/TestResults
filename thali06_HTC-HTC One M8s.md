#### Test 50650278d6c551a_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
,D/Process (  970): killProcessQuiet, pid=5588
--------- beginning of system
I/ActivityManager(  970): Killing 5588:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  970): Recipient 5588
E/cutils-trace( 6668): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6668): ====startRecUseTime====
D/htc.customization.log.level( 6668):  is 
W/CustomizationLogLevel( 6668): Level value is invalid, use default level 2
D/CustomizationManager( 6668):  Read ACC file spent 0.035 (s)
D/CIDMapFileReader( 6668): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6668): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6668): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6668): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6668): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6668): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6668): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6668): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6668): Parsing tag category name = system
I/CustomizationCIDLoader( 6668): Parsing tag category name = application
I/CustomizationCIDLoader( 6668): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6668): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6668): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6668): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6668): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6668): add string-array item, value = 42507
I/CustomizationCIDLoader( 6668): add string-array item, value = 21902
I/CustomizationCIDLoader( 6668): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6668): add string-array item, value = 23420
I/CustomizationCIDLoader( 6668): add string-array item, value = 22299
I/CustomizationCIDLoader( 6668): add string-array item, value = 24002
I/CustomizationCIDLoader( 6668): add string-array item, value = 23210
I/CustomizationCIDLoader( 6668): add string-array item, value = 23205
I/CustomizationCIDLoader( 6668): add string-array item, value = 23806
I/CustomizationCIDLoader( 6668): add string-array item, value = 23430
I/CustomizationCIDLoader( 6668): add string-array item, value = 23408
I/CustomizationCIDLoader( 6668): add string-array item, value = 27205
I/CustomizationCIDLoader( 6668): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6668): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6668):  Read CID file spent 0.070 (s)
D/CustomizationManager( 6668):  All configurations done spent 0.071 (s)
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6668 on display 0
D/PMS     (  970): acquireHCC(78b932e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
D/PMS     (  970): acquireHCC(d9decf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
W/asset   (  970): Copying FileAsset 0x55a237f830 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  970): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6686 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
V/ActivityManager(  970): Display changed displayId=0
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6686): Copying FileAsset 0xabf5e898 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1485): [trimMemory] 20
I/WebViewFactory( 6686): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6686): Time to load native libraries: 9 ms (timestamps 133-142)
I/LibraryLoader( 6686): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6686): Binding Chromium to main looper Looper (main, tid 1) {2f8ae596},
I/LibraryLoader( 6686): Expected native library version number "",actual native library version number ""
,I/chromium( 6686): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6686): Initializing chromium process, singleProcess=true,
,W/art     ( 6686): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6686): ApplicationContext is null in ApplicationStatus,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/chromium( 6686): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6686): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6686): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6686): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6686): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6686): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6686): Local Branch: 
I/Adreno-EGL( 6686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6686): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6686):                  d74aa161a12b9c6fc6332151
,W/System.err(  970): java.lang.Throwable: stack dump,
,W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	,at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8643a63:true
D/BluetoothAdapter( 6686): 1007142178: getState(). Returning 12
,W/art     ( 6686): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6686): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6686): CordovaWebView is running on device made by: HTC
,W/art     ( 6686): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6686): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  970): Activity pause timeout for ActivityRecord{21c1205c u0 com.test.thalitest/.MainActivity t8}
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6686): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000000),
,D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/StatusBarManagerService(  970): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
,D/FindExtension( 6686): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6686): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@18160aa0, mServedView=org.apache.cordova.engine.SystemWebView{105f7659 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@308ab21e,
I/InputMethodManagerService(  970): Disable input method client, pid=1485
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6686): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  970): Displayed com.test.thalitest/.MainActivity: +649ms (total +694ms)
,W/BindingManager( 6686): Cannot call determinedVisibility() - never saw a connection for the pid: 6686
,D/JsMessageQueue( 6686): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6686): JniHelper::setJavaVM(0xaadf38f8), pthread_self() = -1408015400
,D/JX-Cordova( 6686): jxcore cordova android initializing
,W/jxcore-log( 6686): Initializing JXcore engine,
W/jxcore-log( 6686): JXcore engine is ready
,W/jxcore-log( 6686): Starting JXcore engine
,W/jxcore-log( 6686): Platform android,
W/jxcore-log( 6686): 
W/jxcore-log( 6686): Process ARCH arm
W/jxcore-log( 6686): 
,D/PMS     (  970): releaseHCC(78b932e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  970): releaseHCC(d9decf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6686): JXcore Cordova bridge is ready!,
I/jxcore-log( 6686): 
W/jxcore-log( 6686): JXcore engine is started
I/Choreographer( 6686): Skipped 94 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6686): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6686): Toggling radios to true,
I/jxcore-log( 6686): 
,D/BluetoothAdapter( 6686): enable(): BT is already enabled..!,
,D/WifiService(  970): New client listening to asynchronous messages,
E/WifiTrafficPoller(  970): ADD_CLIENT: 8
D/WifiManager( 6686): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  970): MONITOR_LOG
D/WifiService(  970): setWifiEnabled: true pid=6686, uid=10366
W/Settings:Agent(  970): name: wifi_on
E/WifiService(  970): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  970): value: 2
I/WifiService(  970): isSprintWifiRestricted(): false
,W/Settings:Agent(  970): >> traceCallingStack()
I/WifiService(  970): isMdmWifiRestricted(): false
W/Settings:Agent(  970): Process.myPid(): 970
W/Settings:Agent(  970): Process.myTid(): 1765
,W/Settings:Agent(  970): Process.myUid(): 1000
W/Settings:Agent(  970): 
W/Settings:Agent(  970): 
W/System.err(  970): java.lang.Throwable: stack dump
,W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  970): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  970): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  970): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  970): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  970): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  970): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  970): 
W/Settings:Agent(  970): << traceCallingStack(): 17(ms)
,D/WifiController(  970): handleMessage: E msg.what=155656
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): handleMessage: X
D/WifiManager( 6686): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  970): handleMessage: E msg.what=131145
D/WifiManager( 6686): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1372): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1372): wlan0: Cancelling scan request
D/wpa_supplicant( 1372): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1372): TDLS: Tear down peers
D/wpa_supplicant( 1372): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6686): Radios toggled
I/jxcore-log( 6686): 
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6686): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6686): 
,I/jxcore-log( 6686): Perf Test app loaded loaded
I/jxcore-log( 6686): 
,I/jxcore-log( 6686): check test folder
I/jxcore-log( 6686): 
,I/jxcore-log( 6686): found test : ./testFindPeers.js
I/jxcore-log( 6686): 
,D/wpa_supplicant( 1372): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1372): wlan0: Deauthentication notification,
D/wpa_supplicant( 1372): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1372): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
,I/wpa_supplicant( 1372): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1372): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
E/wpa_supplicant( 1372): enter disconnect check
D/PMS     (  970): acquireWL(18bfcbc): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
I/wpa_supplicant( 1372): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1372): wlan0: Auto connect disabled: do not try to re-connect
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/wpa_supplicant( 1372): wlan0: Ignore connection failure indication since interface has been put into disconnected state
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  970): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  970): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  970): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  970): TetherInterfaceSM: wlan0: enter UnavailableState
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  970): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1372): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1372): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1372): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1372): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1372): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55b9ce2f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1372):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372): wlan0: State: COMPLETED -> DISCONNECTED
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/wpa_supplicant( 1372): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1372): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1372): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1372): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1372): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1372): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1372): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1372): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1372): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1372): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1372): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1372): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1372): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1372): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1372): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1372): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1372): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1372): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1372): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  970): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  970): invokeExitMethods: ConnectedState
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  970): WifiStateMachine: Leaving Connected state
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiPerfLock(  970): release()
E/WifiStateMachine(  970): PerfLock released for exiting ConnectedState
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  970): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prev,SupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  970): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  970): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  970): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  970): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1372): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1372): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1372): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1372): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1372): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1372): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1372): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect,
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/jxcore-log( 6686): found test : ./testSendData.js
I/jxcore-log( 6686): 
I/wpa_supplicant( 1372): Power_Mode_Type mode = 0
I/wpa_supplicant( 1372): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/TetherSettings( 5918): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/        ( 5918): Cust_ConnectToPC   : Internet_Sharing>true
D/WifiP2pService(  970): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/        ( 5918): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5918): Cust_ConnectToPC   : spcsc>false
D/        ( 5918): Cust_ConnectToPC   : IPT>true
D/        ( 5918): Cust_ConnectToPC   : Singel_USB>false
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1372): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
,D/WifiDataStallTracker(  970): setDhcpActive: false
,E/Netd    (  394): ifc_reset_connections failed on iface wlan0 for address 192.168.1.130/24 (Unknown error -1),
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  970): releaseWL(18bfcbc): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  970): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  970): setDetailed state send new extra info<unknown ssid>
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  970): NetworkAgent != null
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/Settings( 5918): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  970): updateNotificationsLocked()
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 14
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  970): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  970): stopDataStallAlarm 
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 3
E/SmartNS_Utility( 5918): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5918): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5918): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1372): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1372): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1372): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1372): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1372): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1372): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1372): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  970):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  970): Start Disconnecting Watchdog 1
E/WifiStateMachine(  970): handleMessage: X
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  970): handleMessage: E msg.what=131146
E/WifiStateMachine(  970): processMsg: DisconnectingState
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1372): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1372): Fast associate: Old scan results
D/wpa_supplicant( 1372): wlan0: Setting scan request: 0.000000 sec
,I/wpa_supplicant( 1372): wpa_supplicant_scan enter
D/wpa_supplicant( 1372): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1372): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1372): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1372): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1372): WPS:  * Request Type
D/wpa_supplicant( 1372): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1372): WPS:  * UUID-E
D/wpa_supplicant( 1372): WPS:  * Primary Device Type
D/wpa_supplicant( 1372): WPS:  * RF Bands (3)
D/wpa_supplicant( 1372): WPS:  * Association State
D/wpa_supplicant( 1372): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1372): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1372): WPS:  * Manufacturer
D/wpa_supplicant( 1372): WPS:  * Model Name
D/wpa_supplicant( 1372): WPS:  * Model Number
D/wpa_supplicant( 1372): WPS:  * Device Name
D/wpa_supplicant( 1372): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1372): P2P: * P2P IE header
D/wpa_supplicant( 1372): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1372): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1372): wlan0: Add radio work 'scan'@0x55b9cc5860
D/wpa_supplicant( 1372): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1372): wlan0: Starting radio work 'scan'@0x55b9cc5860 after 0.000041 second wait
D/wpa_supplicant( 1372): wlan0: nl80211: scan request
D/wpa_supplicant( 1372): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1372): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1372): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1372): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1372): wlan0: Own scan request started a scan in 0.000087 seconds
I/wpa_supplicant( 1372): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147460
E/WifiStateMachine(  970): processMsg: DisconnectingState
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  970):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133719
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133720
E/WifiStateMachine(  970): ConnectModeState: Network connection lost 
E/WifiStateMachine(  970): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter,
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  970): DisconnectedState call setCountryCode()
E/WifiStateMachine(  970):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1372): wlan0: Control interface command 'SET pno 1',
D/wpa_supplicant( 1372): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1372): wlan0: Cancelling scan request
,W/ContextImpl( 5918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5918): setISNotification
,D/SmartNS_Utility( 5918): usb_cable_connect = 1
D/SmartNS_Utility( 5918): usb_denied = 0
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/SmartNS_PSService( 5918): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 1372): wlan0: nl80211: sched_scan request
,I/ActionCombine( 5918): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 5918): usb_cable_connect = 1
,D/SmartNS_Utility( 5918): usb_denied = 0
I/SmartNS_PSService( 5918): usb notificaiton:true
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 5918): Tethered state change:false isNSOpening:false,
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/wpa_supplicant( 1372): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec,
D/wpa_supplicant( 1372): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1372): wlan0: nl80211: Sched scan started
E/WifiStateMachine(  970): handleMessage: X
,E/WifiStateMachine(  970): handleMessage: E msg.what=131101
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1372): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1372): wlan0: nl80211: New scan results available
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1372): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1372): wlan0: Event SCAN_RESULTS (3) received
W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/wpa_supplicant( 1372): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1372): wlan0: Scan completed in 0.048989 seconds
D/wpa_supplicant( 1372): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1372): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1372): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1372): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to no match in scan
E/WifiStateMachine(  970):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/wpa_supplicant( 1372): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1372): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1372): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1372): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1372): wlan0: Radio work 'scan'@0x55b9cc5860 done in 0.049867 seconds
D/wpa_supplicant( 1372): wlan0: Selecting BSS from priority group 284
D/wpa_supplicant( 1372): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-57 wps
D/wpa_supplicant( 1372): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1372): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1372): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
E/WifiStateMachine(  970):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1372):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
E/WifiStateMachine(  970): processMsg: DriverStartedState
D/wpa_supplicant( 1372): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1372): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55b9ce4c00  current_ssid=0x0
D/wpa_supplicant( 1372): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1372): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1372): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1372): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1372): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1372): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1372): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 ,03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1372): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1372): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1372): wlan0: Add radio work 'connect'@0x55b9cc5860
D/wpa_supplicant( 1372): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  970):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1372): wlan0: Starting radio work 'connect'@0x55b9cc5860 after 0.000049 second wait
I/wpa_supplicant( 1372): check if in concurrent case
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
I/wpa_supplicant( 1372): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  970):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  970): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=43 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  970): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  970): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=44 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
D/wpa_supplicant( 1372): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1372): wlan0: Cancelling sched scan
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=133769  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/wpa_supplicant( 1372): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1372): wlan0: Cancelling scan request
D/wpa_supplicant( 1372): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1372): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1372): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1372): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1372): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1372): RSN: PMKSA cache search - network_ctx=0x55b9ce4c00 try_opportunistic=0
D/wpa_supplicant( 1372): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1372): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1372): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1372): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1372): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1372): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1372): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1372): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1372): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1372): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1372): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1372): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1372): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1372): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1372): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=133769  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/wpa_supplicant( 1372): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1372): nl80211: Unsubscribe mgmt frames handle 0x888888dd3146c989 (mode change)
E/WifiStateMachine(  970): handleMessage: X
D/wpa_supplicant( 1372): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b9ce4100
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=0104
D/WifiNetworkAgent(  970): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=040a
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=040b
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=040c
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=040d
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=090a
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=090b
I/RemoteViews( 1222): reapply : com.android.settings 2 36
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=090c
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=090d
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=133770  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=0409506f9a09
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=7f506f9a09
E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=0801
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=040e
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=06
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=0a07
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=0a11
D/wpa_supplicant( 1372): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b9ce4100 match=0a1a
D/wpa_supplicant( 1372): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1372):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372):   * freq=2412
D/wpa_supplicant( 1372):   * freq_hint=2412
D/wpa_supplicant( 1372):   * SSID - hexdump(len=5): 4e 47 37 30 30
E/WifiStateMachine(  970): setDetailed state send new extra info"NG700"
D/wpa_supplicant( 1372):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1372):   * WPA Versions 0x2
D/wpa_supplicant( 1372):   * pairwise=0xfac04
D/wpa_supplicant( 1372):   * group=0xfac04
D/wpa_supplicant( 1372):   * akm=0xfac02
D/wpa_supplicant( 1372):   * Auth Type 0
D/wpa_supplicant( 1372): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55b9ce4c3a
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1372): nl80211: Connect request send successfully
D/wpa_supplicant( 1372): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1372): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1372): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1372): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1372): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1372): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1372): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  970): NetworkAgent == null
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 17
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=133776  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 dur:2275 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 dur:2275 bcn=0
E/WifiStateMachine(  970): processMsg: DriverStartedState
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  970):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 dur:2275 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=6 known=1 got=6 dur:2275 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1372): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  970): [1,449,754,850,699 ms] noteScanEnd no scan source
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1372): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2a8ac2ee sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  970): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2412
E/WifiAutoJoinController (  970): Gonzos 38:f8:89:11:e9:11 rssi=-84 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  970): UPC5999698 64:7c:34:12:7f:81 rssi=-90 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): UPC503894600 a0:c5:62:7a:49:97 rssi=-87 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 6 now 1449754850702
E/WifiAutoJoinController (  970): newSupplicantResults size=6 known=1 true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1372): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  970): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  970): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  970): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  970): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  970): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131213
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState CMD_TARGET_BSSID 44 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133787
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_TARGET_BSSID 44 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133787
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_TARGET_BSSID 44 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133788
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_TARGET_BSSID 44 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133788
E/WifiStateMachine(  970): handleMessage: X
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=133789  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info0x
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=133794  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  970): handleMessage: X
D/WISPrService( 5918): >>>>>WISPrService start isConnected = true<<<<<
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 9
E/WifiStateMachine(  970): handleMessage: E msg.what=131131
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): handleMessage: X
,D/ConnectivityService(  970): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  970): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/WIFI    (  970): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/NetworkManagementService(  970): Removing idletimer
E/WifiStateMachine(  970): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/usbnet  (  970): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524292
I/SecurityController( 1222): onLost 100
W/WISPrService( 5918): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5918): trigger connection
D/WISPrService( 5918): continue
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Disconnected - quitting
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:3
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/Choreographer( 6686): Skipped 86 frames!  The application may be doing too much work on its main thread.
I/chromium( 6686): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
D/PMS     (  970): acquireWL(1347d79a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 970 1000 null
D/CSLegacyTypeTracker(  970): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/WISPrService( 5918): start DataConnection
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5918): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  970): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/libc    ( 5918): [NET] android_getaddrinfofornet-, err=8
E/ConnectivityService(  970): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  970): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  970): acquireWL(3463e8cb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
V/NetworkPolicy(  970): ensureActiveMobilePolicyLocked()
D/Tethering(  970): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/libc    ( 5918): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/NetworkPolicy(  970): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/libc    ( 5918): [NET] android_getaddrinfofornet-, pass to proxy
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
D/libc    ( 5918): [NET] android_getaddrinfo_proxy+
V/NetworkPolicy(  970): updateIfacesLocked()
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
V/NetworkPolicy(  970): updateNotificationsLocked()
D/libc    ( 5918): [NET] android_getaddrinfo_proxy get netid:0
D/DATA_ICON( 1222): dataConnected: false/false
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/PMS     (  970): releaseWL(3463e8cb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5918): [NET] android_getaddrinfo_proxy-, NODATA
D/FlexNetS( 6554): updateSvcAllowedInSettings:false
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
D/FlexNetS( 6554): updateSvcAllowedInSettings:false
,I/ActivityManager(  970): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6751 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/FlexNetS( 6554): updateSvcAllowedInSettings:false
D/libc    ( 5918): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5918): [NET] android_getaddrinfofornet-, err=8
D/wpa_supplicant( 1372): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1372): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1372): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1372): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1372): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1372): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1372): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1372): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1372): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1372): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1372): nl80211: Connect event
D/wpa_supplicant( 1372): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1372): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1372): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1372): wlan0: Association info event
D/wpa_supplicant( 1372): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1372): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1372): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1372): wlan0: freq=2412 MHz
D/wpa_supplicant( 1372): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1372): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1372): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1372): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1372): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1372): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1372): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1372): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1372): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1372): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1372): TDLS: Remove peers on association
D/wpa_supplicant( 1372): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1372): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1372): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1372): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1372): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1372): EAPOL: enable timer tick
D/wpa_supplicant( 1372): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1372): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1372): wlan0: Cancelling scan request
I/wpa_supplicant( 1372): htc_wext_set_keepalive +
I/wpa_supplicant( 1372): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1372): getPrivFuncNum +	
I/wpa_supplicant( 1372): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1372): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
I/wpa_supplicant( 1372): htc_wext_set_keepalive - ret = 0
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChan,ge():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1372): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1372): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1372): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1372): wlan0:   EAPOL-Key type=2
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/wpa_supplicant( 1372): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1372): wlan0:   key_length=16 key_data_length=0
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1372):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/Tethering(  970): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1372):   key_nonce - hexdump(len=32): 9c 01 37 56 d6 30 be 49 c5 27 2d 67 d1 4f 86 c6 22 be d2 e5 8e 79 b4 76 2c f1 dd d9 c0 85 9d 39
D/wpa_supplicant( 1372):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1372):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1372):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1372):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1372): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1372): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1372): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  970): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=47 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  970): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  970): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  970): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=133892  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1372): WPA: Renewed SNonce - hexdump(len=32): 29 c3 0d 5c 6b a0 b0 a3 95 71 3d d8 e0 cb 7c 8c 38 fe bf a2 16 d0 53 5f 80 10 96 50 dd 34 2c e0
D/WifiMonitor(  970): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  970): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  970): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/wpa_sup,plicant( 1372): WPA: Nonce1 - hexdump(len=32): 29 c3 0d 5c 6b a0 b0 a3 95 71 3d d8 e0 cb 7c 8c 38 fe bf a2 16 d0 53 5f 80 10 96 50 dd 34 2c e0
D/wpa_supplicant( 1372): WPA: Nonce2 - hexdump(len=32): 9c 01 37 56 d6 30 be 49 c5 27 2d 67 d1 4f 86 c6 22 be d2 e5 8e 79 b4 76 2c f1 dd d9 c0 85 9d 39
D/wpa_supplicant( 1372): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1372): WPA: PTK - hexdump(len=48): [REMOVED]
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1372): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1372): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/PMS     (  970): acquireWL(421bff2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/wpa_supplicant( 1372): wlan0: WPA: Sending EAPOL-Key 2/4
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1372): WPA: KCK - hexdump(len=16): [REMOVED]
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1372): WPA: Derived Key MIC - hexdump(len=16): 01 34 60 b4 cf e4 f1 3c c1 dc 81 2a 52 42 7c 9a
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Tethering(  970): interfaceStatusChanged wlan0, true
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  970): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=133893  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  970): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147500
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  970): Enter handleAssociatedWithEvent
D/WifiStateMachine(  970): Associated
D/WifiStateMachine(  970): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  970): Exit handleAssociatedWithEvent
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=133898  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WISPrService( 5918): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/FlexNetS( 6554): updateSvcAllowedInSettings:false
E/WifiStateMachine(  970): NetworkAgent == null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/wpa_supplicant( 1372): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1372): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1372): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1372): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1372):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1372):   key_nonce - hexdump(len=32): 9c 01 37 56 d6 30 be 49 c5 27 2d 67 d1 4f 86 c6 22 be d2 e5 8e 79 b4 76 2c f1 dd d9 c0 85 9d 39
D/wpa_supplicant( 1372):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1372):   key_rsc - hexdump(len=8): c3 11 00 00 00 00 00 00
D/wpa_supplicant( 1372):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1372):   key_mic - hexdump(len=16): 49 44 35 ae 18 37 47 0b e8 a4 74 8c 89 76 ec f6
D/wpa_supplicant( 1372): RSN: encrypted key data - hexdump(len=56): 6c ab b3 6e 08 2c b6 2d e9 6a 4b 96 16 ab 9a a0 fe 90 9e f7 b0 92 63 27 bc dd 3f 40 3d bf 3b 06 ...
D/wpa_supplicant( 1372): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1372): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1372): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1372): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 9f 9f ...
D/wpa_supplicant( 1372): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1372): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1372): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1372): WPA: KCK - hexdump(len=16): [REMOVED]
D/PMS     (  970): releaseWL(421bff2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1372): WPA: Derived Key MIC - hexdump(len=16): 89 72 4c e7 e6 d3 0e 75 04 05 05 68 10 72 c5 d5
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1372): wlan0: WPA: Installing PTK to the driver
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1372): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55b9ce5390 key_idx=0 set_tx=1 seq_len=6 key_len=16
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
D/wpa_supplicant( 1372): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
V/NetworkPolicy(  970): updateNotificationsLocked()
D/wpa_supplicant( 1372): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1372):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1372): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1372): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1372): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1372): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1372): WPA: RSC - hexdump(len=6): c3 11 00 00 00 00
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/wpa_supplicant( 1372): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5585428e68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1372): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1372): nl80211: KEY_SEQ - hexdump(len=6): c3 11 00 00 00 00
D/wpa_supplicant( 1372):    broadcast key
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/wpa_supplicant( 1372): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1372): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1372): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/WifiMonitor(  970): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 1372): wlan0: Radio work 'connect'@0x55b9cc5860 done in 0.139350 seconds
I/wpa_supplicant( 1372): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=50 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1372): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
W/WifiMonitor(  970): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=51 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  970): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1372): wlan0: Connect to SSID: NG700
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/wpa_supplicant( 1372): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1372): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 1372): set send_ind_to_ndc = 0
I/wpa_supplicant( 1372): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1372): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1372): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1372): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1372): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1372): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1372): EAP: EAP entering state DISABLED
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1372): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1372): EAPOL: Supplicant port status: Authorized
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/wpa_supplicant( 1372): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=133908  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/wpa_supplicant( 1372): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1372): EAPOL authentication completed - result=SUCCESS
E/WifiStateMachine(  970): handleMessage: X
I/wpa_supplicant( 1372): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1372): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  970): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=53 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  970): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/Tethering(  970): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  970):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=133914  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=133916  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147459
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133916
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/FlexNetS( 6554): updateSvcAllowedInSettings:false
E/WifiStateMachine(  970):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133917
E/WifiStateMachine(  970): Network connection established
D/WifiStateMachine(  970): fetchFrequency(), freq = 2412
E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 22
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: DisconnectedState
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 23
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1372): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1372): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  970): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  970): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  970): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 24
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/FlexNetS( 6554): updateSvcAllowedInSettings:false
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  970): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  970): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  970): Got NetworkAgent Messenger
E/WifiStateMachine(  970): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  970): NetworkAgent connected
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1372): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1372): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1372): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1372): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1372): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1372): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1372): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  970): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  970): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  970): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  970): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1372): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1372): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1372): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1372): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1372): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1372): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1372): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): Start Dhcp Watchdog 2
E/WifiStateMachine(  970): handleMessage: X
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/TetherSettings( 5918): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5918): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5918): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5918): Cust_ConnectToPC   : spcsc>false
D/        ( 5918): Cust_ConnectToPC   : IPT>true
D/        ( 5918): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5918): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5918): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5918): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5918): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=133946  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=133947  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=133948  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=196612
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): processMsg: ObtainingIpState
W/ContextImpl( 5918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  970):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  970): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  970): acquireWL(33782797): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 970 1000 null
D/WifiStateMachine(  970): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  970): setDhcpActive: true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/SmartNS_Utility( 5918): setISNotification
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1372): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/SmartNS_Utility( 5918): usb_cable_connect = 1
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  970): do suspend false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
D/SmartNS_Utility( 5918): usb_denied = 0
I/SmartNS_PSService( 5918): usb notificaiton:true
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1372): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1372): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1372): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1372): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1372): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1372): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1372): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  970): Unexpected BatchedScanResults :null
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1372): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  970): noteBatchedScanstop()
E/WifiStateMachine(  970): handleMessage: X
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f138d88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  970): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f138d88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
D/SmartNS_Utility( 5918): usb_cable_connect = 1
D/SmartNS_Utility( 5918): usb_denied = 0
I/SmartNS_PSService( 5918): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
D/SmartNS_NSReceiver( 5918): Tethered state change:false isNSOpening:false
D/WISPrService( 5918): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5918): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/FlexNetS( 6554): updateSvcAllowedInSettings:false
,D/FlexNetS( 6554): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6751): [235.2.]  listen tmrbb8,
,D/FlexNetS( 6554): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6554): updateSvcAllowedInSettings:false
,D/FlexNetS( 6554): updateSvcAllowedInSettings:false
,D/FlexNetS( 6554): updateSvcAllowedInSettings:false
,D/FlexNetS( 6554): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6617): remove item 101 (p2d24in229) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6751): [235.2.] summary 118:p2 ignore
,D/FlexNetS( 6554): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6617): remove item 101 (p2d1in10) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6554): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6617): remove item 101 (p2in16) for 15:android.intent.action.ANY_DATA_STATE
,E/dhcpcd  ( 6782): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6782): version 5.5.6 starting
,E/dhcpcd  ( 6782): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6782): wlan0: using ClientID 01:90:**:c4:e6:4c:f8,
I/dhcpcd  ( 6782): autoip env[11]:autoip=DISABLE
,D/Process (  970): killProcessQuiet, pid=6208
I/ActivityManager(  970): Killing 6208:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6782): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6782): wlan0: sending REQUEST (xid 0x778dd978), next in 0.45 seconds
,I/ActivityManager(  970): Recipient 6208,
,I/dhcpcd  ( 6782): wlan0: sending REQUEST (xid 0x778dd978), next in 2.26 seconds,
,I/dhcpcd  ( 6782): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6782): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6782): autoip env[11]:autoip=DISABLE
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): processMsg: DefaultState
,E/WifiStateMachine(  970):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  970): handleMessage: X
,D/wpa_supplicant( 1372): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1372): EAPOL: disable timer tick
,I/dhcpcd  ( 6782): bind_interface: daemonise,
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=196613
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4,
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiP2pService(  970): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER POWERMODE 0'
D/PMS     (  970): releaseWL(33782797): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1372): Power_Mode_Type mode = 0
I/wpa_supplicant( 1372): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1372): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  970): setDhcpActive: false
E/WifiStateMachine(  970): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  970): WifiStateMachine DHCP successful
E/WifiStateMachine(  970): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  970): link address 192.168.1.130/24
,E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): gateway: /192.168.1.1
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1372): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1372): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1372): htc_wext_set_keepalive +
I/wpa_supplicant( 1372): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1372): getPrivFuncNum +	
I/wpa_supplicant( 1372): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1372): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1372): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1372): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1372): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131210
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1372): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1372): environment dirty rate=16 [6][1][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1372): wlan0: Control interface command 'BLACKLIST clear'
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/wpa_supplicant( 1372): wlan0: BLACKLIST CLEAR 
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=55 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): NetworkAgent != null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): transitionTo: destState=ConnectedState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  970): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  970): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  970): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  970): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiDataStallTracker(  970): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true,
D/ConnectivityService(  970): Adding iface wlan0 to network 101
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/HtcWifiWanDetect(  970): WAN detection
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -57, 3
D/HtcWifiWanDetect(  970): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 4
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 26
E/WifiStateMachine(  970): handleMessage: X
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected,
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5918): >>>>>WISPrService start isConnected = true<<<<<
E/ConnectivityService(  970): Unexpected mtu value: 0, wlan0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/ConnectivityService(  970): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  970): handleMessage: E msg.what=131131
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS,
E/WifiStateMachine(  970):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  970): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): handleMessage: X
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  970): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/Nat464Xlat(  970): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  970): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/WISPrService( 5918): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  970): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): currentScore = 0, newScore = 20
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Connected
D/ConnectivityService(  970):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/CSLegacyTypeTracker(  970): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  970): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  970): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  970): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  970): acquireWL(1f657df0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
V/NetworkPolicy(  970): ensureActiveMobilePolicyLocked()
D/ConnectivityService(  970): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  970): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/NetworkPolicy(  970): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateIfacesLocked()
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
V/NetworkPolicy(  970): updateNotificationsLocked()
,D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/PMS     (  970): releaseWL(1f657df0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/DATA_ICON( 1222): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
,I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
,D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,E/WifiStateMachine(  970): processMsg: ConnectedState
D/ConnectivityService(  970): identical MTU - not setting
E/WifiStateMachine(  970):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/Nat464Xlat(  970): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
E/WifiStateMachine(  970): processMsg: L2ConnectedState
D/ConnectivityService(  970): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  970):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns,
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  970):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns,
D/ConnectivityService(  970): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  970): processMsg: DriverStartedState
D/ConnectivityService(  970): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  970):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  970):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  970): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
E/WifiStateMachine(  970): handleMessage: X
,D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524295
,D/PMS     (  970): releaseWL(1347d79a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  970): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,D/PMS     (  970): acquireWL(2235ef69): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/GpsLocationProvider(  970): [handleMessage] UPDATE_NETWORK_STATE
I/AlarmManager(  970): [AlarmQueuing] connectivity wifi: false,
D/GpsLocationProvider(  970): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - original mNetworkConnected = true,
,I/ConnectivityHelper( 1485): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  970): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6814 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  970): No APN found to select.,
,D/PMS     (  970): releaseWL(2235ef69): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  970): acquireWL(2072728f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,D/PMS     (  970): releaseWL(2072728f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/MdScPhnSt( 6751): [4df.1.]  listen tmrbb8
,D/MdScDataSum( 6751): [4df.1.] summary 118:p1 ignore
,I/MusicStore( 6814): Database version: 120
,D/VoldConnector(  970): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6814): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  970): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6814): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  970): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6814): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6814): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6814): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6814): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6814): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6814): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@287d68d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6814): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6814): GMSCore installation verified,
,I/ConfigStore( 6814): Config Database version: 1,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6814, uid=10159, userID:0,
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,D/MediaRouterService(  970): Client com.google.android.music (pid 6814): Registered,
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: },
,I/MediaRouter( 6814): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6814): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6814): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6814): type=WIFI subType= reason=null isConnected=true,
,D/AutoSetting( 1575): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6411): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6411): onReceive CONNECTIVITY_CHANGE networkType=1
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6814, uid=10159, userID:0
,D/AutoSetting( 1575): service - onCreate()
,D/AutoSetting( 1575): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate,
D/AutoSetting( 1575): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  970): request 3ee4fb27 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052),
D/LocationManagerService(  970): provider request: passive ProviderRequest[ON interval=0]
,I/GHttpClientFactory( 6814): Using our fixed implementation of GMSCore's GoogleHttpClient,
,I/GoogleURLConnFactory( 6814): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4441): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4441): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  970): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6858 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6437): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 6437): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6437): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6437): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 6437): [NET] android_getaddrinfo_proxy+
D/libc    ( 6437): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/art     (  437): Explicit concurrent mark sweep GC freed 8648(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 236us total 29.792ms
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  437): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 23.522ms
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6437): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4441): [AccountUtils] Account not ready
W/Kids    ( 4441): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4441): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4441): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4441): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4441): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4441): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4441): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4441): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4441): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4441): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4441): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4441): 	at java.lang.Thread.run(Thread.java:818)
,I/art     (  437): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 315us total 23.180ms
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
,I/Babel   ( 6437): connection state changed from UNKNOWN to CONNECTED,
,I/art     (  970): Explicit concurrent mark sweep GC freed 54494(2MB) AllocSpace objects, 4(324KB) LOS objects, 33% free, 16MB/25MB, paused 1.584ms total 165.844ms
,D/VoldConnector(  970): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
I/GAv4    ( 6858): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6858):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6858):   adb logcat -s GAv4
W/ContextImpl( 6858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  970): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6858): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,D/VoldConnector(  970): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
W/GAv4    ( 6858): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  970): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/GAv4    ( 6858): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 6858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/global  ( 6858): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6858): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6858): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6858): Time to load native libraries: 2 ms (timestamps 8178-8180)
,I/LibraryLoader( 6858): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6858): Binding Chromium to main looper Looper (main, tid 1) {26b7ad8a},
,I/LibraryLoader( 6858): Expected native library version number "",actual native library version number "",
I/chromium( 6858): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6858): Initializing chromium process, singleProcess=true,
W/art     ( 6858): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6858): ApplicationContext is null in ApplicationStatus
,W/chromium( 6858): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    (  970): [NET] android_getaddrinfo_proxy+
,D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
E/libEGL  ( 6858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6858): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6858): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6858): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6858): Local Branch: 
I/Adreno-EGL( 6858): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6858): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6858):                  d74aa161a12b9c6fc6332151
,D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  970): [handleMessage] UPDATE_NETWORK_STATE
,I/AlarmManager(  970): [AlarmQueuing] connectivity wifi: true
D/GpsLocationProvider(  970): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  970): acquireWL(1e727fc2): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
I/NetworkMonitor( 6814): type=WIFI subType= reason=null isConnected=true
I/ConnectivityHelper( 1485): [onReceive] WIFI(1): CONNECTED
,D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,E/GpsLocationProvider(  970): No APN found to select.
,D/PMS     (  970): releaseWL(1e727fc2): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  970): acquireWL(31e3982f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,W/AudioManagerAndroid( 6858): Requires BLUETOOTH permission,
,D/PMS     (  970): releaseWL(31e3982f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MdScPhnSt( 6751): [c65.1.]  listen tmrbb8,
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  970): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
,I/NSApplication( 6858): Starting up...,
,D/MdScDataSum( 6751): [c65.1.] summary 118:p1 ignore
,I/ActivityManager(  970): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6922 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  970): Killing 6366:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=6366
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  970): Recipient 6366
,D/BluetoothAdapter( 6686): 1007142178: getState(). Returning 12
,I/jxcore-log( 6686): BLE supported!!,
I/jxcore-log( 6686): 
D/Process (  970): killProcessQuiet, pid=5945
I/ActivityManager(  970): Killing 5945:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131168,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
,E/WifiStateMachine(  970):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: DefaultState
,E/WifiStateMachine(  970):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): handleMessage: X
,I/ActivityManager(  970): Recipient 5945
,D/Process (  970): killProcessQuiet, pid=5124,
I/ActivityManager(  970): Killing 5124:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  970): Recipient 5124
,V/MusicLeanback( 6814): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AutoSetting( 1575): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6411): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6411): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1575): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1575): service - onStartCommand() screen is off, don't request location
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4441, uid=10024, userID:0,
,I/art     ( 3814): Explicit concurrent mark sweep GC freed 5121(266KB) AllocSpace objects, 0(0B) LOS objects, 57% free, 1510KB/3MB, paused 346us total 46.012ms,
,D/ChimeraCfgMgr( 4441): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4441): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4441): [AccountUtils] Account not ready
W/Kids    ( 4441): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4441): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4441): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4441): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4441): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4441): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4441): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4441): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4441): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4441): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4441): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4441): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
,D/PMS     (  970): acquireWL(2c3f1f17): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6814 10159 null,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6814, uid=10159, userID:0
,I/ActivityManager(  970): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6958 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
D/PMS     (  970): releaseWL(2c3f1f17): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6814): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6814): Stop autocaching.
,W/ResourcesManager( 6958): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6958): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6958): VM with version 2.1.0 has multidex support
I/MultiDex( 6958): install
,I/MultiDex( 6958): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6958): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6958): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6958): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26b4c383: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6958): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1880): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1880): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,D/WearableService( 6958): callingUid 10024, callindPid: 6958
,V/GmsCoreStatsServiceLauncher( 4441): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4441, uid=10024, userID:0,
,D/LocationInitializer( 4441): Restart initialization of location
,E/MDM     ( 1823): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6814): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6814): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  970): acquireWL(3795a059): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
,V/AlarmManager(  970): sending alarm PendingIntent{31904795: PendingIntentRecord{27c10aa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=143083, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{1f66941e: PendingIntentRecord{d0264ff com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143712, Int=0
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  970): releaseWL(3795a059): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024},
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  970): acquireWL(2104e2cc): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 970 1000 null
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  970): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  970): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  970): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  970): [reportHTCStatus] INJECT_XTRA_DATA, status: 0,
,D/GpsLocationProvider(  970):  [handleDownloadXtraData]inject done.
D/PMS     (  970): acquireWL(2d035fb8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/PMS     (  970): releaseWL(2104e2cc): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  970): releaseWL(2d035fb8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  970): killProcessQuiet, pid=5862
I/ActivityManager(  970): Killing 5862:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5862
,D/ContactMessageStore( 1434): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1434): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  970): acquireWL(31ea0191): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{144308f6: PendingIntentRecord{3189f4f7 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1449754884035, Int=0
D/PMS     (  970): acquireWL(e6abf64): PARTIAL_WAKE_LOCK  *backup* 0x1 970 1000 null
,D/PMS     (  970): releaseWL(31ea0191): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  970): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  970): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  970): releaseWL(e6abf64): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/AutoSetting( 1575): service - handleMessage() stop self,
,D/AutoSetting( 1575): service - handleMessage() quit looper,
D/AutoSetting( 1575): service - onDestroy() END
,D/PMS     (  970): acquireWL(151c25cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
,E/WifiStateMachine(  970): handleMessage: E msg.what=131165
I/BatteryService(  970): n_update end
E/WifiStateMachine(  970): processMsg: ConnectedState
D/PMS     (  970): releaseWL(151c25cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
E/WifiStateMachine(  970):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/HtcPowerSaver(  970): updateBatteryInfo
E/WifiStateMachine(  970): processMsg: L2ConnectedState
D/NotificationService(  970): plugged=true pluggin=true
E/WifiStateMachine(  970):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/PowerUI ( 1222): closing low battery warning: level=100
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/PMS     (  970): runPSCheck
E/WifiStateMachine(  970):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/HtcPowerSaver(  970): Checking...
E/WifiStateMachine(  970): processMsg: DriverStartedState
I/HtcPowerSaver(  970): >> updateStatus
E/WifiStateMachine(  970):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/WifiController(  970): battery changed pluggedType: 2
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
E/WifiStateMachine(  970):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
E/WifiStateMachine(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): << updateStatus
E/WifiStateMachine(  970):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): handleMessage: X
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1434): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,E/WifiStateMachine(  970): handleMessage: E msg.what=131326,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState what:131326 2 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  970): handleMessage: X
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1575): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1bf70230,
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  970): Killing 6505:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=6505
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6505
,D/PMS     (  970): acquireWL(1a0ebe82): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{31904795: PendingIntentRecord{27c10aa android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=203084, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{30dee993: PendingIntentRecord{34c66dd0 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=212304, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{2cd251c9: PendingIntentRecord{34ee40ce android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=225166, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{e848bef: PendingIntentRecord{3aec96fc com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190507, Int=0
,D/HtcSystemUPManager(  970): AlarmScheduler_INEXACT [onReceive] end
D/HtcSystemUPManager(  970): com.htc.upm.AlarmScheduler$SchedulerBase$1@c3067ba
D/HtcSystemUPManager(  970): UPAlarmListener onAlarmArrival
D/HtcSystemUPManager(  970): UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1449754942094, last = 1449733342082, freq = 21600000
,D/PMS     (  970): acquireWL(2fa54185): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/HtcSystemUPManager(  970): HtcSystemUPHandler sendService() has been called
D/HtcSystemUPManager(  970): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
D/HtcSystemUPManager(  970): HtcSystemUPHandler send to UPService takes: 3 ms
,D/PMS     (  970): releaseWL(1a0ebe82): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  970): acquireWL(15319bda): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2fa54185): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  970): releaseWL(15319bda): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(18aec994): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(18aec994): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(4f1c3d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(4f1c3d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1077cc32): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(23e55d83): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(3a163f39): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(1077cc32): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1880): Vacuum at: now=1449754942412 tag=VacuumService
,D/PMS     (  970): releaseWL(23e55d83): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(3d164edf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1880): Using platform SSLCertificateSocketFactory
,W/Uploader( 1880): No account for auth token provided
,D/PMS     (  970): releaseWL(3d164edf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(2e01b72c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2e01b72c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1880): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1880): [NET] android_getaddrinfo_proxy+
D/libc    ( 1880): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1880): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1880): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1880): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1880): No account for auth token provided,
,W/Uploader( 1880): No account for auth token provided,
,W/Uploader( 1880):  no longer exists, so no auth token.
,W/Uploader( 1880): No account for auth token provided,
,I/GLSUser ( 1880): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1880): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1880): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1880): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1880): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1880): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1880): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1880): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1880): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1880): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1880): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1880): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1880): ,	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1880): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
,W/Uploader( 1880): No account for auth token provided,
,D/PMS     (  970): releaseWL(3a163f39): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(281d1430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(281d1430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(3da868a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1880 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3da868a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  970): acquireWL(2c4e3e2e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/BatteryService(  970): n_update end
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): releaseWL(2c4e3e2e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/NotificationService(  970): plugged=true pluggin=true
D/PMS     (  970): runPSCheck
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
,D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  970): acquireWL(39d6adcf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(39d6adcf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo,
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  970): plugged=true pluggin=true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
,D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1372): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1372): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1372): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1372): wlan0: BSS: Remove id 3 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5

```
