#### Test 54312298c831015_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6652): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6652): ====startRecUseTime====
D/htc.customization.log.level( 6652):  is 
W/CustomizationLogLevel( 6652): Level value is invalid, use default level 2
D/CustomizationManager( 6652):  Read ACC file spent 0.032 (s)
D/CIDMapFileReader( 6652): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6652): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6652): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6652): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6652): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6652): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6652): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6652): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6652): Parsing tag category name = system
I/CustomizationCIDLoader( 6652): Parsing tag category name = application
I/CustomizationCIDLoader( 6652): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6652): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6652): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6652): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6652): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6652): add string-array item, value = 42507
I/CustomizationCIDLoader( 6652): add string-array item, value = 21902
I/CustomizationCIDLoader( 6652): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6652): add string-array item, value = 23420
I/CustomizationCIDLoader( 6652): add string-array item, value = 22299
I/CustomizationCIDLoader( 6652): add string-array item, value = 24002
I/CustomizationCIDLoader( 6652): add string-array item, value = 23210
I/CustomizationCIDLoader( 6652): add string-array item, value = 23205
I/CustomizationCIDLoader( 6652): add string-array item, value = 23806
I/CustomizationCIDLoader( 6652): add string-array item, value = 23430
I/CustomizationCIDLoader( 6652): add string-array item, value = 23408
I/CustomizationCIDLoader( 6652): add string-array item, value = 27205
I/CustomizationCIDLoader( 6652): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6652): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6652):  Read CID file spent 0.067 (s)
D/CustomizationManager( 6652):  All configurations done spent 0.068 (s)
--------- beginning of system
D/PMS     (  931): acquireHCC(33af72fc): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 931 1000 null
I/ActivityManager(  931): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6652 on display 0
D/PMS     (  931): acquireHCC(21a4ed85): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 931 1000 null
W/asset   (  931): Copying FileAsset 0x55c08647e0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  931): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6670 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  931): Display changed displayId=0
D/DotMatrix( 1329): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1329): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6670): Copying FileAsset 0xac28b868 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1619): [trimMemory] 20
I/WebViewFactory( 6670): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6670): Time to load native libraries: 13 ms (timestamps 0-13)
,I/LibraryLoader( 6670): Expected native library version number "",actual native library version number ""
,I/ActivityManager(  931): Killing 5594:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  931): killProcessQuiet, pid=5594
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,V/WebViewChromiumFactoryProvider( 6670): Binding Chromium to main looper Looper (main, tid 1) {1777ddf4}
,I/LibraryLoader( 6670): Expected native library version number "",actual native library version number ""
I/chromium( 6670): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6670): Initializing chromium process, singleProcess=true
,W/art     ( 6670): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6670): ApplicationContext is null in ApplicationStatus
,I/ActivityManager(  931): Recipient 5594
,W/chromium( 6670): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6670): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6670): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6670): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6670): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6670): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6670): Local Branch: 
I/Adreno-EGL( 6670): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6670): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6670):                  d74aa161a12b9c6fc6332151
,W/System.err(  931): java.lang.Throwable: stack dump
W/System.err(  931): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  931): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  931): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  931): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  931): Message: MESSAGE_REGISTER_ADAPTER,
D/BluetoothManagerService(  931): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@462b39:true
,D/BluetoothAdapter( 6670): 674162016: getState(). Returning 12
,W/art     ( 6670): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6670): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6670): CordovaWebView is running on device made by: HTC
,W/art     ( 6670): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6670): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  931): Activity pause timeout for ActivityRecord{d75d7da u0 com.test.thalitest/.MainActivity t8}
,W/HtcSystemUPManager(  931): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6670): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  931): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  931): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  931): hiding MENU key
,D/StatusBarManagerService(  931): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  931): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  931): hiding MENU key
,D/FindExtension( 6670): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6670): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@31bec78e, mServedView=org.apache.cordova.engine.SystemWebView{34dc6baf VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@23035bbc
,I/InputMethodManagerService(  931): Disable input method client, pid=1619,
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/StatusBarManagerService(  931): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6670): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  931): Displayed com.test.thalitest/.MainActivity: +651ms (total +695ms)
,W/BindingManager( 6670): Cannot call determinedVisibility() - never saw a connection for the pid: 6670,
,D/JsMessageQueue( 6670): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6670): JniHelper::setJavaVM(0xab1208f8), pthread_self() = -1404874216,
D/JX-Cordova( 6670): jxcore cordova android initializing
,W/art     ( 6670): Suspending all threads took: 6.610ms
,I/art     ( 6670): Background sticky concurrent mark sweep GC freed 28744(2MB) AllocSpace objects, 0(0B) LOS objects, 4% free, 11MB/12MB, paused 7.847ms total 33.350ms
,W/jxcore-log( 6670): Initializing JXcore engine,
W/jxcore-log( 6670): JXcore engine is ready
,W/jxcore-log( 6670): Starting JXcore engine,
,D/PMS     (  931): releaseHCC(33af72fc): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  931): releaseHCC(21a4ed85): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6670): Platform android,
W/jxcore-log( 6670): 
W/jxcore-log( 6670): Process ARCH arm
W/jxcore-log( 6670): 
,I/jxcore-log( 6670): JXcore Cordova bridge is ready!,
I/jxcore-log( 6670): 
W/jxcore-log( 6670): JXcore engine is started
,I/Choreographer( 6670): Skipped 100 frames!  The application may be doing too much work on its main thread.,
I/chromium( 6670): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6670): Toggling radios to true,
I/jxcore-log( 6670): 
,D/BluetoothAdapter( 6670): enable(): BT is already enabled..!,
,E/WifiTrafficPoller(  931): ADD_CLIENT: 8
D/WifiService(  931): New client listening to asynchronous messages
D/WifiManager( 6670): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  931): MONITOR_LOG,
D/WifiService(  931): setWifiEnabled: true pid=6670, uid=10366
W/Settings:Agent(  931): name: wifi_on
E/WifiService(  931): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  931): value: 2
I/WifiService(  931): isSprintWifiRestricted(): false
W/Settings:Agent(  931): >> traceCallingStack()
I/WifiService(  931): isMdmWifiRestricted(): false
W/Settings:Agent(  931): Process.myPid(): 931
W/Settings:Agent(  931): Process.myTid(): 1610
W/Settings:Agent(  931): Process.myUid(): 1000
W/Settings:Agent(  931): 
W/Settings:Agent(  931): 
W/System.err(  931): java.lang.Throwable: stack dump,
,W/System.err(  931): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  931): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  931): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  931): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  931): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  931): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  931): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  931): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  931): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  931): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  931): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  931): 
W/Settings:Agent(  931): << traceCallingStack(): 16(ms)
D/WifiController(  931): handleMessage: E msg.what=155656
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): handleMessage: X
D/WifiManager( 6670): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  931): handleMessage: E msg.what=131145
D/WifiManager( 6670): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1326): wlan0: Cancelling scan request
D/wpa_supplicant( 1326): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1326): TDLS: Tear down peers
D/wpa_supplicant( 1326): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6670): Radios toggled
I/jxcore-log( 6670): 
D/BluetoothManagerService(  931): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6670): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6670): 
,I/jxcore-log( 6670): Perf Test app loaded loaded
I/jxcore-log( 6670): 
,I/jxcore-log( 6670): check test folder
I/jxcore-log( 6670): 
,I/jxcore-log( 6670): found test : ./testFindPeers.js
I/jxcore-log( 6670): 
,D/wpa_supplicant( 1326): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1326): wlan0: Deauthentication notification
D/wpa_supplicant( 1326): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1326): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1326): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1326): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1326): enter disconnect check
I/wpa_supplicant( 1326): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/UsbDeviceManager(  931): [USBNET] bCheckSuppFunc: cdc_network
,E/WifiMonitor(  931): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/PMS     (  931): acquireWL(8964b3a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 931 1000 null
D/HTCRequest(  931): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/WifiDisplayAdapter(  931): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  931):     Client/Owner: Client
D/WifiDisplayAdapter(  931):     GroupId: 
D/WifiDisplayAdapter(  931):     Passphrase: 
D/WifiDisplayAdapter(  931):     SessionId: 0
D/WifiDisplayAdapter(  931):     IP Address: }
D/wpa_supplicant( 1326): wlan0: Auto connect disabled: do not try to re-connect,
D/wpa_supplicant( 1326): wlan0: Ignore connection failure indication since interface has been put into disconnected state
E/WifiMonitor(  931): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/Tethering(  931): interfaceLinkStateChanged wlan0, false
D/Tethering(  931): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  931): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  931): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  931): TetherInterfaceSM: wlan0: enter UnavailableState
D/Tethering(  931): interfaceLinkStateChanged wlan0, false
D/Tethering(  931): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  931): sendTetherStateChangedBroadcast 0, 0, 0
D/wpa_supplicant( 1326): TDLS: Remove peers on disassociation
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/wpa_supplicant( 1326): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1326): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1326): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1326): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a786ff88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1326):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1326): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1326): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/UsbnetService(  931): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/wpa_supplicant( 1326): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1326): EAPOL: SUPP_PAE entering state DISCONNECTED
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1326): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1326): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1326): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1326): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1326): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1326): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1326): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1326): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1326): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1326): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1326): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1326): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1326): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1326): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1326): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  931): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  931): handleMessage: new destination call exit/enter
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  931): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  931): invokeExitMethods: ConnectedState
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  931): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  931): release()
E/WifiStateMachine(  931): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  931): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  931): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  931): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  931): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  931): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  931): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  931): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET_NETWORK [,REMOVED]'
D/wpa_supplicant( 1326): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1326): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1326): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  931): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1326): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1326): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiMonitor(  931): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I/jxcore-log( 6670): found test : ./testSendData.js
I/jxcore-log( 6670): 
E/WifiStateMachine(  931): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1326): Power_Mode_Type mode = 0
I/wpa_supplicant( 1326): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  931): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  931): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  931): setDhcpActive: false
V/NativeCrypto( 1857): Read error: ssl=0x55c016d490: I/O error during system call, Connection timed out
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  931): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  931): setDetailed state send new extra info<unknown ssid>
D/PMS     (  931): acquireWL(1bc5e3eb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  931): NetworkAgent != null
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  931): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  931): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  931): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  931): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1326): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1326): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1326): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1326): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1326): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  931): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  931): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  931): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  931):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  931): Start Disconnecting Watchdog 1
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=131146
E/WifiStateMachine(  931): processMsg: DisconnectingState
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiStateMachine(  931):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1326): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1326): Fast associate: Old scan results
D/wpa_supplicant( 1326): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1326): wpa_supplicant_scan enter
D/wpa_supplicant( 1326): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1326): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1326): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1326): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1326): WPS:  * Request Type
D/wpa_supplicant( 1326): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1326): WPS:  * UUID-E
V/NetworkPolicy(  931): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/wpa_supplicant( 1326): WPS:  * Primary Device Type
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/wpa_supplicant( 1326): WPS:  * RF Bands (3)
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/wpa_supplicant( 1326): WPS:  * Association State
D/W,IFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1326): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1326): WPS:  * Device Password ID (0)
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1326): WPS:  * Manufacturer
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1326): WPS:  * Model Name
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1326): WPS:  * Model Number
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1326): WPS:  * Device Name
D/wpa_supplicant( 1326): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1326): P2P: * P2P IE header
D/wpa_supplicant( 1326): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1326): P2P: * Listen Channel: Regulatory Class 81 Channel 1
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1326): wlan0: Add radio work 'scan'@0x55a7852860
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1326): wlan0: First radio work item in the queue - schedule start immediately
D/HTCRequest(  931): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1326): wlan0: Starting radio work 'scan'@0x55a7852860 after 0.000053 second wait
,D/wpa_supplicant( 1326): wlan0: nl80211: scan request
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  931): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/wpa_supplicant( 1326): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1326): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1326): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1326): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1326): wlan0: Own scan request started a scan in 0.000115 seconds
I/wpa_supplicant( 1326): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
D/WifiDataStallTracker(  931): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WifiDataStallTracker(  931): stopDataStallAlarm 
E/WifiMonitor(  931): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  931): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  931): handleMessage: X
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  931): handleMessage: E msg.what=147460
E/WifiStateMachine(  931): processMsg: DisconnectingState
E/WifiDataStallTracker(  931): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiStateMachine(  931):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133684
E/WifiStateMachine(  931): processMsg: ConnectModeState
D/libc    (  931): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/libc    (  931): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  931):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=133686
E/WifiStateMachine(  931): ConnectModeState: Network connection lost 
E/WifiStateMachine(  931): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  931): handleMessage: new destination call exit/enter
E/WifiStateMachine(  931): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  931): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  931): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  931): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  931): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  931): DisconnectedState call setCountryCode()
E/WifiStateMachine(  931):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1326): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1326): wlan0: Cancelling scan request
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/TetherSettings( 5901): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5901): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5901): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5901): Cust_ConnectToPC   : spcsc>false
D/        ( 5901): Cust_ConnectToPC   : IPT>true
D/        ( 5901): Cust_ConnectToPC   : Singel_USB>false
D/PMS     (  931): releaseWL(8964b3a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NativeCrypto( 1857): SSL shutdown failed: ssl=0x55c016d490: I/O error during system call, Broken pipe
,V/NetworkPolicy(  931): updateNetworkEnabledLocked()
V/NetworkPolicy(  931): updateNotificationsLocked()
D/ConnectivityService(  931): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  931): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): Forcing reevaluation
,W/Settings( 5901): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): Validated
D/wpa_supplicant( 1326): wlan0: nl80211: sched_scan request
E/SmartNS_Utility( 5901): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5901): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/PMS     (  931): releaseWL(1bc5e3eb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/SmartNS_NSReceiver( 5901): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
,I/jxcore-log( 6670): found test : ./testSendData2.js
I/jxcore-log( 6670): 
,E/jxcore  ( 6670): Error!: missing ) after argument list
,E/jxcore  ( 6670): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/chromium( 6670): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ContextImpl( 5901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5901): setISNotification
,D/SmartNS_Utility( 5901): usb_cable_connect = 1,
D/SmartNS_Utility( 5901): usb_denied = 0
,I/SmartNS_PSService( 5901): usb notificaiton:true,
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 1326): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1326): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1326): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1326): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1326): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1326): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1326): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1326): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1326): wlan0: Scan completed in 0.047033 seconds
D/wpa_supplicant( 1326): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1326): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1326): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1326): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1326): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1326): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1326): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1326): wlan0: Radio work 'scan'@0x55a7852860 done in 0.048045 seconds
E/WifiMonitor(  931): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1326): wlan0: Selecting BSS from priority group 394
D/wpa_supplicant( 1326): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-57 wps
D/wpa_supplicant( 1326): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
E/WifiStateMachine(  931): handleMessage: X
D/WifiMonitor(  931): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 1326): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1326): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1326):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
E/WifiStateMachine(  931): handleMessage: E msg.what=131101
E/WifiStateMachine(  931): processMsg: DisconnectedState
D/wpa_supplicant( 1326): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
W/WifiMonitor(  931): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1326): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55a7871c00  current_ssid=0x0
D/wpa_supplicant( 1326): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1326): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1326): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1326): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1326): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1326): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1326): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1326): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1326): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1326): wlan0: Add radio work 'connect'@0x55a7852860
D/wpa_supplicant( 1326): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1326): wlan0: Starting radio work 'connect'@0x55a7,852860 after 0.000054 second wait
I/wpa_supplicant( 1326): check if in concurrent case
I/wpa_supplicant( 1326): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  931):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  931): processMsg: ConnectModeState
D/WifiMonitor(  931): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=40 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  931):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  931): processMsg: DriverStartedState
I/ActionCombine( 5901): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
E/WifiStateMachine(  931):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
E/WifiStateMachine(  931):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  931): processMsg: DefaultState
E/WifiStateMachine(  931):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  931): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  931): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  931): handleMessage: X
D/wpa_supplicant( 1326): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
E/WifiStateMachine(  931): handleMessage: E msg.what=147462
D/wpa_supplicant( 1326): wlan0: Cancelling sched scan
E/WifiStateMachine(  931): processMsg: DisconnectedState
D/wpa_supplicant( 1326): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1326): wlan0: Cancelling scan request
D/wpa_supplicant( 1326): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1326): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1326): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1326): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1326): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1326): RSN: PMKSA cache search - network_ctx=0x55a7871c00 try_opportunistic=0
D/wpa_supplicant( 1326): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1326): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1326): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1326): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1326): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1326): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1326): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1326): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1326): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1326): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1326): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1326): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1326): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1326): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  931):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=133733  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  931): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/wpa_supplicant( 1326): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
E/WifiStateMachine(  931): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/wpa_supplicant( 1326): nl80211: Set mode ifindex 29 iftype 2 (STATION)
E/WifiStateMachine(  931): processMsg: ConnectModeState
D/wpa_supplicant( 1326): nl80211: Unsubscribe mgmt frames handle 0x888888dd2f0f9989 (mode change)
D/wpa_supplicant( 1326): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a7871100
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=0104
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=040a
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  931): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=040b
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=040c
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=040d
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=090a
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=090b
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=090c
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=090d
D/WifiMonitor(  931): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=0409506f9a09
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=7f506f9a09
E/WifiStateMachine(  931):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=133734  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=0801
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=040e
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=06
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=0a07
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=0a11
E/WifiStateMachine(  931): handleMessage: X
D/wpa_supplicant( 1326): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7871100 match=0a1a
D/wpa_supplicant( 1326): nl80211: Connect (ifindex=29)
D/WifiNetworkAgent(  931): NetworkAgent: NetworkAgent channel lost
D/wpa_supplicant( 1326):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326):   * freq=2412
D/wpa_supplicant( 1326):   * freq_hint=2412
E/WifiStateMachine(  931): handleMessage: E msg.what=147462
D/wpa_supplicant( 1326):   * SSID - hexdump(len=5): 4e 47 37 30 30
E/WifiStateMachine(  931): processMsg: DisconnectedState
D/wpa_supplicant( 1326):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1326):   * WPA Versions 0x2
D/wpa_supplicant( 1326):   * pairwise=0xfac04
D/wpa_supplicant( 1326):   * group=0xfac04
D/wpa_supplicant( 1326):   * akm=0xfac02
D/wpa_supplicant( 1326):   * Auth Type 0
D/wpa_supplicant( 1326): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55a7871c3a
E/WifiStateMachine(  931):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=133735  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  931): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/wpa_supplicant( 1326): nl80211: Connect request send successfully
E/WifiStateMachine(  931): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/wpa_supplicant( 1326): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1326): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1326): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1326): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1326): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1326): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1326): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  931): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/SmartNS_Utility( 5901): usb_cable_connect = 1
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
D/SmartNS_Utility( 5901): usb_denied = 0
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/SmartNS_PSService( 5901): usb notificaiton:true
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5901): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  931): NetworkAgent == null
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=133754  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=147461
E/WifiStateMachine(  931): processMsg: DisconnectedState
E/WifiStateMachine(  931):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:229 bcn=0
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:229 bcn=0
E/WifiStateMachine(  931): processMsg: DriverStartedState
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  931):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:229 bcn=0
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  931):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:229 bcn=0
D/WifiStateMachine(  931): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1326): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  931): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  931): [1,450,738,922,820 ms] noteScanEnd no scan source
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1326): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  931): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@f406f76 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  931): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  931): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  931): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  931): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  931):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2412
E/WifiAutoJoinController (  931): UPC503894600 a0:c5:62:7a:49:97 rssi=-86 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  931): ageScanResultsOut delay 40000 size 3 now 1450738922822
E/WifiAutoJoinController (  931): newSupplicantResults size=3 known=1 true
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1326): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  931): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  931): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  931): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  931): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  931): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  931):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=131213
E/WifiStateMachine(  931): processMsg: DisconnectedState
E/WifiStateMachine(  931):  DisconnectedState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133763
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133763
E/WifiStateMachine(  931): processMsg: DriverStartedState
E/WifiStateMachine(  931):  DriverStartedState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133764
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
E/WifiStateMachine(  931):  SupplicantStartedState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=133764
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=147462
E/WifiStateMachine(  931): processMsg: DisconnectedState
E/WifiStateMachine(  931):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=133765  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  931): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  931): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  931): setDetailed state send new extra info0x
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  931): NetworkAgent == null
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 18
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  931): processMsg: ConnectModeState
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  931):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=133768  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  931): handleMessage: X
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 19
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5901): >>>>>WISPrService start isConnected = true<<<<<
D/WifiService(  931): New client listening to asynchronous messages
E/WifiTrafficPoller(  931): ADD_CLIENT: 9
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  931): handleMessage: E msg.what=131131
E/WifiStateMachine(  931): processMsg: DisconnectedState
E/WifiStateMachine(  931):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  931): handleMessage: X
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
W/WISPrService( 5901): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5901): trigger connection
D/WISPrService( 5901): continue
D/ConnectivityService(  931): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  931): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  931): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  931): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): Disconnected - quitting
D/ConnectivityService(  931): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524292
D/NetworkManagementService(  931): Removing idletimer
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI    (  931): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  931):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/WIFI    (  931): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  931): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/usbnet  (  931): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  931):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  931): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/SecurityController( 1222): onLost 100
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5901): start DataConnection
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5901): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5901): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5901): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5901): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5901): [NET] android_getaddrinfo_proxy+
D/libc    ( 5901): [NET] android_getaddrinfo_proxy get netid:0
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
,D/libc    (  416): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  416): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  416): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  416): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5901): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,D/PMS     (  931): acquireWL(13d7efe1): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 931 1000 null
,D/CSLegacyTypeTracker(  931): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
,D/ConnectivityService(  931): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  931): Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
D/ConnectivityService(  931): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  931): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  931): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
V/NetworkPolicy(  931): ensureActiveMobilePolicyLocked()
D/PMS     (  931): acquireWL(270de106): PARTIAL_WAKE_LOCK  NetworkStats 0x1 931 1000 null
E/ConnectivityService(  931): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkPolicy(  931): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  931): updateNetworkEnabledLocked()
V/NetworkPolicy(  931): updateIfacesLocked()
V/NetworkPolicy(  931): updateNotificationsLocked()
D/NetworkManagementService(  931): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/PMS     (  931): releaseWL(270de106): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  931): updateNetworkEnabledLocked()
D/FlexNetS( 6444): updateSvcAllowedInSettings:false
V/NetworkPolicy(  931): updateNotificationsLocked()
,D/wpa_supplicant( 1326): Wireless event: cmd=0x8c02 len=271,
I/wpa_supplicant( 1326): WEXT: Custom wireless event: 'BEACONIEs='
,D/wpa_supplicant( 1326): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1326): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1326): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1326): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1326): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1326): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1326): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1326): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1326): nl80211: Connect event
D/wpa_supplicant( 1326): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1326): nl80211: Associated with c0:ff:d4:d3:aa:48
I/ActivityManager(  931): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6735 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/wpa_supplicant( 1326): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1326): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1326): wlan0: Association info event
D/wpa_supplicant( 1326): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 1326): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1326): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1326): wlan0: freq=2412 MHz
D/Tethering(  931): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1326): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1326): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/Tethering(  931): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1326): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1326): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1326): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1326): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1326): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1326): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1326): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1326): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1326): TDLS: Remove peers on association
D/wpa_supplicant( 1326): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1326): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1326): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1326): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1326): EAPOL: SUPP_PAE entering state CONNECTING
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/wpa_supplicant( 1326): EAPOL: enable timer tick
D/wpa_supplicant( 1326): EAPOL: SUPP_BE entering state IDLE
D/UsbDeviceManager(  931): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1326): wlan0: Setting authentication timeout: 10 sec 0 usec
D/PMS     (  931): acquireWL(3a25ba19): PARTIAL_WAKE_LOCK  NetworkStats 0x1 931 1000 null
D/wpa_supplicant( 1326): wlan0: Cancelling scan request
I/wpa_supplicant( 1326): htc_wext_set_keepalive +
I/wpa_supplicant( 1326): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1326): getPrivFuncNum +	
I/wpa_supplicant( 1326): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1326): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1326): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1326): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1326): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1326): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1326): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1326): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1326):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1326):   key_nonce - hexdump(len=32): 0f f2 45 a9 5e 18 9e 37 c4 c0 c6 47 75 14 5a 36 53 65 4d 7a 2e f2 ee c5 31 e8 93 32 2b 23 db 82
D/wpa_supplicant( 1326):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1326):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1326):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1326):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1326): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1326): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 132,6): RSN: msg 1/4 key data - hexdump(len=0):
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  931): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  931): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  931): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=43 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  931): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  931): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  931): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  931): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  931): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  931): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  931): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  931): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  931): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  931): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  931): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  931): handleMessage: E msg.what=147462
E/WifiStateMachine(  931): processMsg: DisconnectedState
D/wpa_supplicant( 1326): WPA: Renewed SNonce - hexdump(len=32): 83 cd 8b 2e 09 3b 86 3c a2 bd 24 87 48 ef e6 18 4b 06 10 e1 36 e1 df db 51 e7 e3 ea 9a 25 74 5a
E/WifiStateMachine(  931):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=133861  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  931): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/wpa_supplicant( 1326): WPA: Nonce1 - hexdump(len=32): 83 cd 8b 2e 09 3b 86 3c a2 bd 24 87 48 ef e6 18 4b 06 10 e1 36 e1 df db 51 e7 e3 ea 9a 25 74 5a
E/WifiStateMachine(  931): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/wpa_supplicant( 1326): WPA: Nonce2 - hexdump(len=32): 0f f2 45 a9 5e 18 9e 37 c4 c0 c6 47 75 14 5a 36 53 65 4d 7a 2e f2 ee c5 31 e8 93 32 2b 23 db 82
D/wpa_supplicant( 1326): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1326): WPA: PTK - hexdump(len=48): [REMOVED]
D/PMS     (  931): releaseWL(3a25ba19): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  931): processMsg: ConnectModeState
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1326): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1326): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
V/NetworkPolicy(  931): updateNetworkEnabledLocked()
D/wpa_supplicant( 1326): wlan0: WPA: Sending EAPOL-Key 2/4
V/NetworkPolicy(  931): updateNotificationsLocked()
D/wpa_suppl,icant( 1326): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1326): WPA: Derived Key MIC - hexdump(len=16): d4 4c 7c fd 35 bd c6 b9 de 76 5d 9f c4 f8 cf e3
E/WifiStateMachine(  931):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=133862  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=147500
E/WifiStateMachine(  931): processMsg: DisconnectedState
E/WifiStateMachine(  931):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  931): Enter handleAssociatedWithEvent
D/WifiStateMachine(  931): Associated
D/Tethering(  931): interfaceLinkStateChanged wlan0, false
D/Tethering(  931): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  931): interfaceLinkStateChanged wlan0, false
D/Tethering(  931): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  931): interfaceLinkStateChanged wlan0, true
D/Tethering(  931): interfaceStatusChanged wlan0, true
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/Tethering(  931): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1326): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1326): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1326): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1326): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1326):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1326):   key_nonce - hexdump(len=32): 0f f2 45 a9 5e 18 9e 37 c4 c0 c6 47 75 14 5a 36 53 65 4d 7a 2e f2 ee c5 31 e8 93 32 2b 23 db 82
D/wpa_supplicant( 1326):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1326):   key_rsc - hexdump(len=8): a8 61 00 00 00 00 00 00
D/wpa_supplicant( 1326):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1326):   key_mic - hexdump(len=16): 2a 99 d3 1b 9a 55 0c 7d 28 18 d2 f8 aa c6 25 4e
D/wpa_supplicant( 1326): RSN: encrypted key data - hexdump(len=56): e6 6c 65 a4 a8 c6 06 9c a3 f4 fe 95 74 ca 60 e9 87 04 f3 e2 ac 0a 25 d0 6d 8a 9c 4f 32 68 aa 0e ...
D/wpa_supplicant( 1326): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1326): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1326): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1326): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 81 f8 ...
D/wpa_supplicant( 1326): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1326): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1326): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1326): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1326): WPA: Derived Key MIC - hexdump(len=16): e2 eb 2e dd b6 10 f9 e6 b8 d8 d7 77 b2 ac 9c 68
D/wpa_supplicant( 1326): wlan0: WPA: Installing PTK to the driver
D/Tethering(  931): sendTetherStateChangedBroadcast 1, 0, 0
D/wpa_supplicant( 1326): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55a7872390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1326): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1326): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1326):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  931): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  931): Exit handleAssociatedWithEvent
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=147462
E/WifiStateMachine(  931): processMsg: DisconnectedState
D/wpa_supplicant( 1326): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1326): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/UsbnetService(  931): BroadcastReceiver::onReceive+
E/WifiStateMachine(  931):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=133870  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  931): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
D/wpa_supplicant( 1326): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
E/WifiStateMachine(  931): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/wpa_supplicant( 1326): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1326): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/UsbnetService(  931): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1326): WPA: RSC - hexdump(len=6): a8 61 00 00 00 00
D/wpa_supplicant( 1326): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5586b25e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1326): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1326): nl80211: KEY_SEQ - hexdump(len=6): a8 61 00 00 00 00
D/wpa_supplicant( 1326):    broadcast key
I/wpa_supplicant( 1326): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1326): wlan0: Cancelling authentication timeout
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/wpa_supplicant( 1326): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1326): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1326): wlan0: Radio work 'connect'@0x55a7852860 done in 0.139670 seconds
D/HTCRequest(  931): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1326): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1326): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  931): setDetailed state send new extra info"NG700"
D/WifiMonitor(  931): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  931): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=46 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  931): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  931): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  931): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1326): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1326): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1326): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 1326): set send_ind_to_ndc = 0
I/wpa_supplicant( 1326): htc_wext_set_TX_TRACKING (1)+
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/wpa_supplicant( 1326): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1326): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1326): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1326): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1326): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1326): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1326): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1326): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1326): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1326): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1326): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1326): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiStateMachine(  931): NetworkAgent == null
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/Tethering(  931): interfaceLinkStateChanged wlan0, true
D/Tethering(  931): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/WifiMonitor(  931): Event [IFNAME=wlan0 Connect to SSID: NG700]
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  931):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=133882  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=49 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  931): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  931): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  931): handleMessage: X
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  931): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  931): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  931): handleMessage: E msg.what=131101
E/WifiStateMachine(  931): processMsg: DisconnectedState
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  931):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  931): processMsg: DriverStartedState
E/WifiStateMachine(  931):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
D/WifiDisplayAdapter(  931): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  931):     Client/Owner: Client
D/WifiDisplayAdapter(  931):     GroupId: 
D/WifiDisplayAdapter(  931):     Passphrase: 
D/WifiDisplayAdapter(  931):     SessionId: 0
D/WifiDisplayAdapter(  931):     IP Address: }
E/WifiStateMachine(  931):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  931): processMsg: DefaultState
E/WifiStateMachine(  931):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  931): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  931): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=147462
E/WifiStateMachine(  931): processMsg: DisconnectedState
E/WifiStateMachine(  931):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=133887  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  931): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  931): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=133888  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=147459
E/WifiStateMachine(  931): processMsg: DisconnectedState
E/WifiStateMachine(  931):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133889
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133890
E/WifiStateMachine(  931): Network connection established
D/WifiStateMachine(  931): fetchFrequency(), freq = 2412
E/WifiStateMachine(  931): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  931): NetworkAgent == null
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/FlexNetS( 6444): updateSvcAllowedInSettings:false
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 22
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  931): transitionTo: destState=ObtainingIpState
I/art     (  442): Explicit concurrent mark sweep GC freed 8635(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 216us total 33.781ms
E/WifiStateMachine(  931): handleMessage: new destination call exit/enter
E/WifiStateMachine(  931): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  931): invokeExitMethods: DisconnectedState
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1326): CTRL_IFACE SET 'pno'='0'
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  931): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  931): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  931): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  931): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  931): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  931): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/libc    ( 5901): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  931): NetworkAgent == null
D/libc    ( 5901): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 23
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 24
D/WISPrService( 5901): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  931): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  931): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  931): Got NetworkAgent Messenger
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  931): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  931): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  931): NetworkAgent connected
E/WifiConfigStore(  931): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  931): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1326): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1326): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1326): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/FlexNetS( 6444): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1326): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1326): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  931): invokeEnterMethods: ObtainingIpState
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  931): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  931): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  931): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  931): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  931): QCOM Debug skip set_network part for security concern!
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1326): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1326): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1326): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1326): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1326): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  931): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  931): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  931): Start Dhcp Watchdog 2
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=147462
E/WifiStateMachine(  931): processMsg: ObtainingIpState
E/WifiStateMachine(  931):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=133916  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=133917  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=133917  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  931): handleMessage: X
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  931): handleMessage: E msg.what=131212
E/WifiStateMachine(  931): processMsg: ObtainingIpState
I/art     (  442): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 190us total 22.485ms
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  931):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): processMsg: DriverStartedState
,E/WifiStateMachine(  931):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
E/WifiStateMachine(  931):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): processMsg: DefaultState
E/WifiStateMachine(  931):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  931): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=196612
D/ConnectivityService(  931): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  931): processMsg: ObtainingIpState
E/WifiStateMachine(  931):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  931): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  931): acquireWL(38c5138d): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 931 1000 null
D/WifiDataStallTracker(  931): setDhcpActive: true
D/WifiStateMachine(  931): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  931): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/FlexNetS( 6444): updateSvcAllowedInSettings:false
E/native  (  931): do suspend false
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1326): INFO - Deny active power mode because already has gateway
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1326): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
E/WifiStateMachine(  931): Unexpected BatchedScanResults :null
D/wpa_supplicant( 1326): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1326): wlan0: Event DRIVER_GTK_REKEY (37) received
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  931): noteBatchedScanstop()
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiP2pService(  931): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@172cb62e target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  931): handleMessage: X
D/WifiP2pService(  931): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@172cb62e target=com.android.internal.util.StateMachine$SmHandler }
D/TetherSettings( 5901): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5901): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5901): Cust_ConnectToPC   : Modem_Link>false
D/WISPrService( 5901): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/WISPrService( 5901): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/        ( 5901): Cust_ConnectToPC   : spcsc>false
D/        ( 5901): Cust_ConnectToPC   : IPT>true
D/        ( 5901): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5901): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5901): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5901): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5901): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
I/SmartNS_Utility( 5901): setISNotification
I/art     (  442): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 153us total 22.002ms
D/SmartNS_Utility( 5901): usb_cable_connect = 1
D/SmartNS_Utility( 5901): usb_denied = 0
I/SmartNS_PSService( 5901): usb notificaiton:true
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/SmartNS_Utility( 5901): usb_cable_connect = 1
D/SmartNS_Utility( 5901): usb_denied = 0
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
I/SmartNS_PSService( 5901): usb notificaiton:true
E/WifiStateMachine(  931): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5901): Tethered state change:false isNSOpening:false
D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  931): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6735): [45d.2.]  listen tmrbb8
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false
,D/FlexNetS( 6444): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6508): remove item 101 (p2d25in231) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6735): [45d.2.] summary 118:p2 ignore
,D/MdProvGlob( 6508): remove item 101 (p2in10) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6508): remove item 101 (p2in18) for 15:android.intent.action.ANY_DATA_STATE,
,E/dhcpcd  ( 6764): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6764): version 5.5.6 starting
E/dhcpcd  ( 6764): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6764): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6764): autoip env[11]:autoip=DISABLE
,D/Process (  931): killProcessQuiet, pid=6186,
I/ActivityManager(  931): Killing 6186:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6764): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6764): wlan0: sending REQUEST (xid 0xa125776d), next in 0.24 seconds
,I/ActivityManager(  931): Recipient 6186,
,I/dhcpcd  ( 6764): wlan0: sending REQUEST (xid 0xa125776d), next in 2.08 seconds,
,I/dhcpcd  ( 6764): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6764): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6764): autoip env[11]:autoip=DISABLE
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  931): handleMessage: E msg.what=131212
E/WifiStateMachine(  931): processMsg: ObtainingIpState
E/WifiStateMachine(  931):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): processMsg: ConnectModeState,
E/WifiStateMachine(  931):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): processMsg: DriverStartedState
E/WifiStateMachine(  931):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
,E/WifiStateMachine(  931):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  931): processMsg: DefaultState
E/WifiStateMachine(  931):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  931): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  931): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  931): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  931): handleMessage: X
,I/dhcpcd  ( 6764): bind_interface: daemonise
,D/wpa_supplicant( 1326): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1326): EAPOL: disable timer tick
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  931): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  931): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  931): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  931): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  931): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  931): handleMessage: E msg.what=196613
E/WifiStateMachine(  931): processMsg: ObtainingIpState
E/WifiStateMachine(  931):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  931): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1326): Power_Mode_Type mode = 0
I/wpa_supplicant( 1326): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  931): setDhcpActive: false
E/WifiStateMachine(  931): handlePostDhcpSetup release wake lock during DHCP
D/PMS     (  931): releaseWL(38c5138d): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/WifiStateMachine(  931): WifiStateMachine DHCP successful
E/WifiStateMachine(  931): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
,E/WifiStateMachine(  931): link address 192.168.1.130/24
,E/WifiStateMachine(  931): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  931): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false,
E/WifiStateMachine(  931): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  931): gateway: /192.168.1.1
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1326): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1326): htc_wext_set_keepalive +
I/wpa_supplicant( 1326): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1326): getPrivFuncNum +	
I/wpa_supplicant( 1326): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1326): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1326): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1326): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1326): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  931): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=131210
E/WifiStateMachine(  931): processMsg: ObtainingIpState
E/WifiStateMachine(  931):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
,E/WifiStateMachine(  931):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1326): environment dirty rate=0 [6][0][0]
,E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  931): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
,E/WifiConfigStore(  931): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
W/WifiHW  (  931): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1326): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1326): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  931): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=51 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  931): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
,E/WifiStateMachine(  931): NetworkAgent != null
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED -1 -> 3
,E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  931): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  931): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiWatchdogStateMachine(  931): RSSI current: 3 new: -58, 3
,E/WifiStateMachine(  931): transitionTo: destState=ConnectedState
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  931): handleMessage: new destination call exit/enter
D/ConnectivityService(  931): Adding iface wlan0 to network 101
E/WifiStateMachine(  931): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
V/NetworkPolicy(  931): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  931): invokeExitMethods: ObtainingIpState
V/NetworkPolicy(  931): mWifiStateReceiver: meteredHint=false,EPS mode=false
,E/WifiStateMachine(  931): moveTempStackToStateStack: i=0,j=5
D/HtcWifiWanDetect(  931): WAN detection
E/WifiStateMachine(  931): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/HtcWifiWanDetect(  931): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiStateMachine(  931): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  931): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  931): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiDataStallTracker(  931): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 25
E/WifiDataStallTracker(  931): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  931): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
E/WifiTrafficPoller(  931): ENABLE_TRAFFIC_STATS_POLL false Token 26
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WISPrService( 5901): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  931): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  931): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  931): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiStateMachine(  931): handleMessage: X
E/WifiStateMachine(  931): handleMessage: E msg.what=131131
,E/WifiStateMachine(  931): processMsg: ConnectedState
D/libc    (  416): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/ConnectivityService(  931): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  931):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  931): handleMessage: X
D/libc    (  416): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  931): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  416): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  931): Setting Dns servers for network 101 to [/192.168.1.1]
D/WISPrService( 5901): >>>>>WISPrService start isConnected = true<<<<<
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  416): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
,D/Nat464Xlat(  931): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
,D/ConnectivityService(  931): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  931): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  931): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931): rematching NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  931): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  931):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  931):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  931):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  931):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  931): currentScore = 0, newScore = 20
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): Connected
D/ConnectivityService(  931):    accepting network in place of null
D/WIFI    (  931): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  931): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  931): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  931): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  931): sendGeneralBroadcast, restrictEnable=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): Validated
D/ConnectivityService(  931): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  931): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  931): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  931): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
V/NetworkPolicy(  931): ensureActiveMobilePolicyLocked()
D/Tethering(  931): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  931): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  931): acquireWL(37a00baf): PARTIAL_WAKE_LOCK  NetworkStats 0x1 931 1000 null
,D/ConnectivityService(  931): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  931): Validated
D/ConnectivityService(  931): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  931): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  931): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  931):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  931):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/ConnectivityService(  931): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  931): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  931): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  931): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  931): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  931): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/NetworkPolicy(  931): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/WIFI    (  931):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  931): updateNetworkEnabledLocked()
D/WIFI    (  931): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
V/NetworkPolicy(  931): updateIfacesLocked()
D/usbnet  (  931): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931): Validated NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  931):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  931): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  931): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  931):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  931):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  931): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  931): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  931): updateNotificationsLocked()
D/ConnectivityService(  931): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
D/PMS     (  931): releaseWL(37a00baf): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/SecurityController( 1222): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/NetworkManagementService(  931): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DATA_ICON( 1222): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,V/NetworkPolicy(  931): updateNetworkEnabledLocked()
,V/NetworkPolicy(  931): updateNotificationsLocked()
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  931): handleMessage: E msg.what=131212
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  931): processMsg: DriverStartedState
,E/WifiStateMachine(  931):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
E/WifiStateMachine(  931):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  931): processMsg: DefaultState
D/ConnectivityService(  931): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
E/WifiStateMachine(  931):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  931): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  931): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  931): identical MTU - not setting
E/WifiStateMachine(  931): handleMessage: X
D/Nat464Xlat(  931): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
,D/ConnectivityService(  931): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  931): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  931): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  931):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524295
,D/ConnectivityService(  931): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524295
,D/PMS     (  931): acquireWL(2b0e7bbc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000},
V/AlarmManager(  931): sending alarm PendingIntent{30bbf3e6: PendingIntentRecord{e3b1d27 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=130939, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{2e462745: PendingIntentRecord{3833ee9a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=135672, Int=0
,D/PMS     (  931): acquireWL(25ebb3cb): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1857 10024 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1857): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1857): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1857): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1857): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1857): [NET] android_getaddrinfo_proxy+
D/libc    ( 1857): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  416): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  416): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/PMS     (  931): releaseWL(2b0e7bbc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/libc    (  416): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1857): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1857): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1857): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1857): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1857): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  931): acquireWL(102597a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1857 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1857): Connected
,D/PMS     (  931): releaseWL(25ebb3cb): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(102597a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): acquireWL(826f2c1): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1857): Message class com.google.f.a.a.p,
,D/PMS     (  931): releaseWL(826f2c1): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): releaseWL(13d7efe1): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  931): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  931): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  931): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  931): [handleMessage] UPDATE_NETWORK_STATE,
I/AlarmManager(  931): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  931): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  931): acquireWL(18d25a66): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 931 1000 null
,D/PMS     (  931): acquireWL(39ffc1a7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 931 1000 null
D/htcCheckinService(  931): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  931): releaseWL(39ffc1a7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ConnectivityHelper( 1619): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  931): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6802 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  931): No APN found to select.
,D/PMS     (  931): releaseWL(18d25a66): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6735): [8c7.1.]  listen tmrbb8
,D/MdScDataSum( 6735): [8c7.1.] summary 118:p1 ignore
,I/MusicStore( 6802): Database version: 120,
,D/VoldConnector(  931): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6802): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  931): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 6802): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  931): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 6802): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6802): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6802): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6802): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6802): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6802): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21e0b6fd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6802): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6802): GMSCore installation verified,
,I/ConfigStore( 6802): Config Database version: 1,
,I/PackageManager(  931):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6802, uid=10159, userID:0,
,D/WifiDisplayAdapter(  931): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  931):     Client/Owner: Client
D/WifiDisplayAdapter(  931):     GroupId: 
D/WifiDisplayAdapter(  931):     Passphrase: 
D/WifiDisplayAdapter(  931):     SessionId: 0
D/WifiDisplayAdapter(  931):     IP Address: }
,D/MediaRouterService(  931): Client com.google.android.music (pid 6802): Registered,
,D/WifiDisplayAdapter(  931): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  931):     Client/Owner: Client
D/WifiDisplayAdapter(  931):     GroupId: 
D/WifiDisplayAdapter(  931):     Passphrase: 
D/WifiDisplayAdapter(  931):     SessionId: 0
D/WifiDisplayAdapter(  931):     IP Address: }
,I/MediaRouter( 6802): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6802): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6802): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6802): type=WIFI subType= reason=null isConnected=true,
,D/AutoSetting( 1540): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,I/PackageManager(  931):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6802, uid=10159, userID:0
,D/MobileConnectivityChangeReceiver( 6394): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6394): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1540): service - onCreate(),
,D/AutoSetting( 1540): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1540): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  931): request 3b1d49d3 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  931): provider request: passive ProviderRequest[ON interval=0]
,D/ChimeraCfgMgr( 4462): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4462): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  931): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6844 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6555): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6555): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6555): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6555): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6555): [NET] android_getaddrinfo_proxy+
D/libc    ( 6555): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  416): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  416): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1857): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1857): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1857): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1857): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  416): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6555): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4462): [AccountUtils] Account not ready
W/Kids    ( 4462): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4462): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4462): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4462): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4462): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4462): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4462): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4462): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4462): 	at com.google.android.gms.chimera.f.run(SourceFile:179),
W/Kids    ( 4462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4462): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
,I/Babel   ( 6555): connection state changed from UNKNOWN to CONNECTED,
,I/art     (  931): Explicit concurrent mark sweep GC freed 54891(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 1.501ms total 181.134ms
,I/GHttpClientFactory( 6802): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6802): Using platform SSLCertificateSocketFactory
,I/GAv4    ( 6844): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6844):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6844):   adb logcat -s GAv4
,D/VoldConnector(  931): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6844): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/VoldConnector(  931): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6844): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6844): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/VoldConnector(  931): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6844): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  931): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6844): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6844): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6844): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6844): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6844): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6844): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6844): Time to load native libraries: 2 ms (timestamps 7880-7882),
I/LibraryLoader( 6844): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6844): Binding Chromium to main looper Looper (main, tid 1) {7aa0092},
,I/LibraryLoader( 6844): Expected native library version number "",actual native library version number ""
,I/chromium( 6844): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6844): Initializing chromium process, singleProcess=true,
,W/art     ( 6844): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6844): ApplicationContext is null in ApplicationStatus
,W/chromium( 6844): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6844): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6844): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6844): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6844): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6844): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6844): Local Branch: 
I/Adreno-EGL( 6844): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6844): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6844):                  d74aa161a12b9c6fc6332151
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  931): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    (  931): [NET] android_getaddrinfo_proxy+
D/libc    (  931): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  416): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  416): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,W/AudioManagerAndroid( 6844): Requires BLUETOOTH permission
,I/NSApplication( 6844): Starting up...
,D/ConnectivityService(  931): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/ActivityManager(  931): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6907 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/libc    (  416): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
I/ActivityManager(  931): Killing 6349:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  931): [NET] android_getaddrinfo_proxy-, success
D/Process (  931): killProcessQuiet, pid=6349,
D/HtcWifiWanDetect(  931): Find DNS Address www.htc.com/104.81.130.175
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  931): Recipient 6349,
,I/AlarmManager(  931): [AlarmQueuing] connectivity wifi: true
,D/GpsLocationProvider(  931): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  931): acquireWL(3f4edee0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 931 1000 null
D/PMS     (  931): acquireWL(3dbd5599): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 931 1000 null
,D/htcCheckinService(  931): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/GpsLocationProvider(  931): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  931): releaseWL(3dbd5599): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  931): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/NetworkMonitor( 6802): type=WIFI subType= reason=null isConnected=true
I/ConnectivityHelper( 1619): [onReceive] WIFI(1): CONNECTED
,E/GpsLocationProvider(  931): No APN found to select.
,D/PMS     (  931): releaseWL(3f4edee0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6735): [8d.1.]  listen tmrbb8
,D/MdScDataSum( 6735): [8d.1.] summary 118:p1 ignore
,D/Process (  931): killProcessQuiet, pid=6420,
I/ActivityManager(  931): Killing 6420:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 6420,
,D/BluetoothAdapter( 6670): 674162016: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6670): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6670): BLE supported!!
I/jxcore-log( 6670): 
,E/WifiStateMachine(  931): handleMessage: E msg.what=131168
,E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  931): processMsg: DriverStartedState
E/WifiStateMachine(  931):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
E/WifiStateMachine(  931):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  931): processMsg: DefaultState
E/WifiStateMachine(  931):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  931): handleMessage: X
,I/ActivityManager(  931): Killing 6476:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process (  931): killProcessQuiet, pid=6476
,D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  931): Recipient 6476
D/WifiService(  931): Client connection lost with reason: 4
,V/MusicLeanback( 6802): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AutoSetting( 1540): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6394): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6394): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1540): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1540): service - onStartCommand() screen is off, don't request location
,I/PackageManager(  931):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4462, uid=10024, userID:0,
,D/ChimeraCfgMgr( 4462): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4462): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1857): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1857): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1857): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1857): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Kids    ( 4462): [AccountUtils] Account not ready,
W/Kids    ( 4462): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4462): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4462): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4462): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4462): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4462): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4462): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4462): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4462): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4462): 	at java.lang.Thread.run(Thread.java:818)
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,D/PMS     (  931): acquireWL(1e50cd3c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6802 10159 null
,I/PackageManager(  931):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6802, uid=10159, userID:0
,D/WearableService( 5679): callingUid 10024, callindPid: 5679,
,I/MusicLeanback( 6802): Conditions not met for autocaching. okToAttempt=false,
D/PMS     (  931): releaseWL(1e50cd3c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6802): Stop autocaching.
,E/GmsUtils( 6802): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6802): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  931): acquireWL(1424c61f): PARTIAL_WAKE_LOCK  *alarm* 0x1 931 1000 WorkSource{10024},
V/AlarmManager(  931): sending alarm PendingIntent{22fffd6c: PendingIntentRecord{13bdff35 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143116, Int=0
,D/PMS     (  931): releaseWL(1424c61f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  931): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  931): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
D/PMS     (  931): acquireWL(23a5ffca): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 931 1000 null,
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  931): [NET] android_getaddrinfofornet-, err=8,
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  931): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  931): [NET] android_getaddrinfo_proxy+
D/libc    (  931): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  416): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  416): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  416): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  931): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  931): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233392e),sn(),hints(known),family 0,flags 4
D/libc    (  931): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  931): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  931): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  931): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  931):  [handleDownloadXtraData]inject done.
D/PMS     (  931): acquireWL(190c4e96): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 931 1000 null
D/PMS     (  931): releaseWL(23a5ffca): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/GpsLocationProvider(  931): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  931): releaseWL(190c4e96): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  931): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/AutoSetting( 1540): service - handleMessage() stop self
,D/AutoSetting( 1540): service - handleMessage() quit looper
D/AutoSetting( 1540): service - onDestroy() END
,D/PMS     (  931): acquireWL(8335a17): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/UsbnetService(  931): BroadcastReceiver::onReceive+
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(8335a17): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  931): updateBatteryInfo
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): handleMessage: E msg.what=155652
D/PMS     (  931): runPSCheck
D/WifiController(  931): processMsg: DeviceActiveState
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): processMsg: StaEnabledState
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/WifiStateMachine(  931): handleMessage: E msg.what=131165,
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  931): processMsg: ConnectModeState
E/WifiStateMachine(  931):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  931): processMsg: DriverStartedState,
E/WifiStateMachine(  931):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  931): processMsg: SupplicantStartedState
E/WifiStateMachine(  931):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  931): processMsg: DefaultState
E/WifiStateMachine(  931):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  931): handleMessage: X
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1560): switchBindHtcMsgCursor: null
,D/PMS     (  931): acquireWL(281a8e04): PARTIAL_WAKE_LOCK  *alarm* 0x1 931 1000 WorkSource{1000},
,V/AlarmManager(  931): sending alarm PendingIntent{26b6be22: PendingIntentRecord{1a0980b3 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1450738963705, Int=0
D/PMS     (  931): acquireWL(5abdfed): PARTIAL_WAKE_LOCK  *backup* 0x1 931 1000 null
V/AlarmManager(  931): sending alarm PendingIntent{30bbf3e6: PendingIntentRecord{e3b1d27 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=190939, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{38b48670: PendingIntentRecord{10738de9 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190979, Int=0
,D/PMS     (  931): acquireWL(21a69a6e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms},
,W/BackupManagerService(  931): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  931): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  931): releaseWL(5abdfed): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  931): releaseWL(281a8e04): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  931): acquireWL(3611750f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(21a69a6e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  931): releaseWL(3611750f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): acquireWL(3dc61121): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(3dc61121): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): acquireWL(7138946): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): releaseWL(7138946): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  931): acquireWL(2948f707): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): acquireWL(25bf8034): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): acquireWL(b6ef3d2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): releaseWL(2948f707): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1857): Vacuum at: now=1450738980360 tag=VacuumService
,I/GoogleURLConnFactory( 1857): Using platform SSLCertificateSocketFactory,
,D/PMS     (  931): releaseWL(25bf8034): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): acquireWL(31ee6ba0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(31ee6ba0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  931): acquireWL(50ec359): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): releaseWL(50ec359): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1857): No account for auth token provided,
,D/libc    ( 1857): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1857): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1857): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1857): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1857): [NET] android_getaddrinfo_proxy+
D/libc    ( 1857): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  416): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  416): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  416): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1857): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1857): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1857): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 1857): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1857): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1857): No account for auth token provided,
,W/Uploader( 1857): No account for auth token provided,
,W/Uploader( 1857):  no longer exists, so no auth token.,
,W/Uploader( 1857): No account for auth token provided,
,W/Uploader( 1857): No account for auth token provided,
,D/PMS     (  931): releaseWL(b6ef3d2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): acquireWL(345ea1cc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(345ea1cc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  931): acquireWL(115f3c15): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(115f3c15): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiStateMachine(  931): handleMessage: E msg.what=131326,
E/WifiStateMachine(  931): processMsg: ConnectedState
E/WifiStateMachine(  931):  ConnectedState what:131326 2 0
E/WifiStateMachine(  931): processMsg: L2ConnectedState
E/WifiStateMachine(  931):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  931): handleMessage: X
,D/PMS     (  931): acquireWL(37192b2a): PARTIAL_WAKE_LOCK  *alarm* 0x1 931 1000 WorkSource{1000}
V/AlarmManager(  931): sending alarm PendingIntent{2d5a5d1b: PendingIntentRecord{35ba0eb8 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=211143, Int=0
,D/PMS     (  931): releaseWL(37192b2a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcAppUPService( 1540): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@5026178
I/ActivityManager(  931): Killing 6532:com.htc.calendar/u0a10 (adj 15): empty #17
D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/Process (  931): killProcessQuiet, pid=6532
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 6532,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  931): acquireWL(2b048491): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/UsbnetService(  931): BroadcastReceiver::onReceive+
I/BatteryService(  931): n_update end
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/PMS     (  931): releaseWL(2b048491): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  931): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  931): updateBatteryInfo
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): handleMessage: E msg.what=155652
,D/PMS     (  931): runPSCheck
D/WifiController(  931): processMsg: DeviceActiveState
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): processMsg: StaEnabledState
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  931): acquireWL(a76cff6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  931): n_update end
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PMS     (  931): releaseWL(a76cff6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  931): updateBatteryInfo
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  931): runPSCheck
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  931): Checking...
D/UsbnetService(  931): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
,D/WifiController(  931): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1326): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1326): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  931): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  931): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  931): acquireWL(3637aff7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000}
V/AlarmManager(  931): sending alarm PendingIntent{30bbf3e6: PendingIntentRecord{e3b1d27 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=250939, Int=0
,V/AlarmManager(  931): sending alarm PendingIntent{18dbd8cd: PendingIntentRecord{d37f582 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1450739130179, Int=0
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  931): releaseWL(3637aff7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1857): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1857): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1857): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1857): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 3 40,
W/GLSActivity( 1857): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1857): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1857): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1857): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1857): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1857): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1857): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5925): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5925): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5925): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5925): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5925): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5925): 	,at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5925): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5925): Ignoring header User-Agent because its value was null.
,D/libc    ( 5925): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5925): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5925): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5925): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5925): [NET] android_getaddrinfo_proxy+
D/libc    ( 5925): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  416): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  416): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  416): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5925): [NET] android_getaddrinfo_proxy-, success,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1
,D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
D/PMS     (  931): acquireWL(25072894): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  931): n_update end
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  931): releaseWL(25072894): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  931): updateBatteryInfo
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  931): Checking...
I/HtcPowerSaver(  931): >> updateStatus
,D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  931): acquireWL(28e18f3d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  931): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
D/HtcPowerSaver(  931): updateBatteryInfo
D/WifiController(  931): processMsg: StaEnabledState
D/PMS     (  931): runPSCheck
D/WifiController(  931): processMsg: DefaultState
D/HtcPowerSaver(  931): Checking...
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): handleMessage: X
D/PMS     (  931): releaseWL(28e18f3d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1560): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1560): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1560): sku_id=118
D/ContactMessageStore( 1560): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1560): start background delete task...
,D/ContactMessageStore( 1560): size: 0 , 0
,D/ContactMessageStore( 1560): Background delete complete
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  931): acquireWL(27dcc332): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  931): n_update end
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  931): releaseWL(27dcc332): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  931): updateBatteryInfo
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  931): Checking...
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  931): acquireWL(27248883): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
,D/PMS     (  931): releaseWL(27248883): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0,
D/HtcPowerSaver(  931): updateBatteryInfo
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/PMS     (  931): runPSCheck
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  931): Checking...
D/UsbnetService(  931): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  931): << updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  931): acquireWL(24783a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/UsbnetService(  931): BroadcastReceiver::onReceive+
I/BatteryService(  931): n_update end
,D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/PMS     (  931): releaseWL(24783a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/NotificationService(  931): plugged=true pluggin=true
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): processMsg: StaEnabledState
D/HtcPowerSaver(  931): updateBatteryInfo
D/WifiController(  931): processMsg: DefaultState
D/PMS     (  931): runPSCheck
D/WifiController(  931): handleMessage: X
D/HtcPowerSaver(  931): Checking...
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  931): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  931): << updateStatus
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  931): acquireWL(4dce239): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000},
V/AlarmManager(  931): sending alarm PendingIntent{30bbf3e6: PendingIntentRecord{e3b1d27 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=370938, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{100fe07e: PendingIntentRecord{c9d29df com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940716, Int=0
,I/bt-btm  ( 3118): Received oneshot timer event complete,
I/bt-btm  ( 3118): btm_ble_timeout
,D/PMS     (  931): acquireWL(326f62c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3118 1002 null
I/bt-btm  ( 3118): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3118): btm_ble_rand_enc_complete,
I/bt-btm  ( 3118): btm_gen_resolve_paddr_low
D/bt-smp  ( 3118): smp_encrypt_data
W/bt-smp  ( 3118): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3118): Plain text(LSB ~ MSB) = 0d 6f 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3118): Encrypted text(LSB ~ MSB) = 7b 28 4e c8 a0 c1 21 fd e1 9b 02 00 3c 52 65 1c 
I/bt-btm  ( 3118): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3118): Stopping oneshot timer
D/bt-btm  ( 3118): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1222): Weather sync is On
,D/PMS     (  931): releaseWL(4dce239): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  931): releaseWL(326f62c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  931): acquireWL(8a068f5): PARTIAL_WAKE_LOCK  *alarm* 0x1 931 1000 WorkSource{10024},
V/AlarmManager(  931): sending alarm PendingIntent{2ec5868a: PendingIntentRecord{31d484fb com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450739635993, Int=1800000
,D/PMS     (  931): acquireWL(d234918): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4462 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  931): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6966 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  931): sending alarm PendingIntent{38db9f71: PendingIntentRecord{227d8156 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1450739443001, Int=0
,V/AlarmManager(  931): sending alarm PendingIntent{25799316: PendingIntentRecord{18988497 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805354, Int=0
,V/AlarmManager(  931): sending alarm PendingIntent{3d8fdec4: PendingIntentRecord{2df51c16 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450739756929, Int=0
,D/PMS     (  931): acquireWL(1bb9c1ad): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4462 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  931): releaseWL(d234918): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  931): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6986 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/EventLogService( 4462): Aggregate from 1450738893072 (log), 1450737835941 (data),
,W/ContextImpl( 6986): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  931): releaseWL(8a068f5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6986): MY_DEBUG = false
,D/PMS     (  931): releaseWL(1bb9c1ad): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageService( 6986): repeat time = 1450740657176
,E/cutils-trace( 7010): Error opening trace file: Permission denied (13)
I/dex2oat ( 7010): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7010): dex2oat: override thread count:4
,I/PowerUsageList:PowerUsageHelper( 6986): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6986): gen(), null == sipper.uidObj, userId = 0
,D/Process (  931): killProcessQuiet, pid=5925
I/ActivityManager(  931): Killing 5925:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 5925
,I/dex2oat ( 7010): dex2oat took 992.220ms (threads: 4),
,I/PushClient( 6966): ApplicationMonitor {2bd3eade}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6966): ApplicationMonitor {2bd3eade}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6966): ApplicationMonitor {2bd3eade}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6966): ApplicationMonitor {2bd3eade}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6966): ApplicationMonitor {2bd3eade}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6966): ApplicationMonitor {2bd3eade}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6966): ApplicationMonitor {2bd3eade}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6966): ApplicationMonitor {2bd3eade}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6966): ApplicationMonitor {2bd3eade}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6966): PnsModel {2e1b1a19}: update(): Update registration caused by: alarm,
,I/PushClient( 6966): PnsConfigModel {17c8ac24}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6966): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6966): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6966): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6966): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  931): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7018 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7018): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7018 dbg=false s=true
,I/DeviceManagement( 7018): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 7018): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7018): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 7018): WorkflowService: Starting workflow service
,I/DeviceManagement( 7018): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@579292a] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7018): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7018): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7018): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7018): SessionStateController: Checking invariants...
,I/DeviceManagement( 7018): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/art     (  931): Explicit concurrent mark sweep GC freed 31821(1657KB) AllocSpace objects, 7(792KB) LOS objects, 33% free, 16MB/24MB, paused 1.784ms total 156.977ms,
,I/DeviceManagement( 7018): SessionStateController: Checking invariants...
,I/DeviceManagement( 7018): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7018): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@579292a],
,I/DeviceManagement( 7018): WorkflowService: Stopping workflow service,
,D/Process (  931): killProcessQuiet, pid=5851,
I/ActivityManager(  931): Killing 5851:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 5851
,I/PushClient( 6966): PnsModel {2e1b1a19}: update(): The registration record has not expired yet. No need to update.
,D/Process (  931): killProcessQuiet, pid=6584
I/ActivityManager(  931): Killing 6584:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 6584
,D/PMS     (  931): acquireWL(32a5c292): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000}
V/AlarmManager(  931): sending alarm PendingIntent{30bbf3e6: PendingIntentRecord{e3b1d27 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=970939, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{20c88463: PendingIntentRecord{1548b860 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450739802342, Int=0
,D/SmartSyncUtils( 6986): isEpsOn(), nState = 0
,D/PMS     (  931): acquireWL(3263f119): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6986 1000 null
,D/WeatherUtility( 1222): Weather sync is On
D/PMS     (  931): releaseWL(32a5c292): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  931): releaseWL(3263f119): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  931): acquireWL(3a5975de): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6986 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6986): [updateNmRange] bManual = false,
D/SmartSyncScreenOnOffTimeReceiver( 6986): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6986): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6986): SettingOnTime = 1450764000000, randomSettingOnTime = 1450761246000
,D/SmartSyncScreenOnOffTimeReceiver( 6986): SettingOffTime = 1450742400000, randomSettingOffTime = 1450742952000
D/SmartSyncScreenOnOffTimeReceiver( 6986): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6986): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6986): bNightModeTurnOffOnce = false
,D/PMS     (  931): releaseWL(3a5975de): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  931): acquireWL(21b503bf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(21b503bf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  931): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  931): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  931): Checking...
D/UsbnetService(  931): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  931): >> updateStatus
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  931): processMsg: StaEnabledState
I/HtcPowerSaver(  931): << updateStatus
D/WifiController(  931): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  931): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  931): acquireWL(25f0fa8c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000}
,V/AlarmManager(  931): sending alarm PendingIntent{30bbf3e6: PendingIntentRecord{e3b1d27 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1030939, Int=0,
V/AlarmManager(  931): sending alarm PendingIntent{283985d5: PendingIntentRecord{3f0311ea com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1035998, Int=0
,D/PMS     (  931): acquireWL(8c01cdb): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1857 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): releaseWL(8c01cdb): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  931): acquireWL(2ef93378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(25f0fa8c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  931): acquireWL(3499aa51): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10176 com.google.android.youtube},
D/PMS     (  931): acquireWL(2f862b6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1857): Message class com.google.f.a.a.i
,D/PMS     (  931): releaseWL(2f862b6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  931): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7048 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  931): releaseWL(2ef93378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/ResourcesManager( 7048): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 7048): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7048): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 7048): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 7048): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 7048): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7048): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/cutils-trace( 7079): Error opening trace file: Permission denied (13)
I/dex2oat ( 7079): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads475738751.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads475738751.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,I/dex2oat ( 7079): dex2oat: override thread count:4
,E/YouTube MDX( 7048): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 7048): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,D/libc    ( 7048): [NET] android_getaddrinfofornet-, SUCCESS
,I/dex2oat ( 7079): dex2oat took 112.873ms (threads: 4)
,D/VoldConnector(  931): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 7048): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,D/VoldConnector(  931): SND -> {39 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 7048): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  931): SND -> {40 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
W/ContextImpl( 7048): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
D/VoldConnector(  931): SND -> {41 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
W/ContextImpl( 7048): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/InstanceID/Rpc( 7048): Found 10024
,D/VoldConnector(  931): SND -> {42 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 7048): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/PMS     (  931): acquireWL(2829cd4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(2829cd4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  931): releaseWL(3499aa51): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube}
,D/PMS     (  931): acquireWL(279524bb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(279524bb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  931): killProcessQuiet, pid=5901
,I/ActivityManager(  931): Killing 5901:com.android.settings/1000 (adj 15): empty #17
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  931): Recipient 5901
,D/WifiService(  931): Client connection lost with reason: 4
,D/libc    ( 7048): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7048): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7048): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 7048): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7048): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7048): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  416): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  416): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  416): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  416): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7048): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 7048): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7048): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7048): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7048): [NET] android_getaddrinfofornet-, err=8
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  931): acquireWL(2c9bc969): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  931): n_update end
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  931): releaseWL(2c9bc969): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  931): updateBatteryInfo
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/PMS     (  931): runPSCheck
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  931): Checking...
D/UsbnetService(  931): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  931): acquireWL(25e8efee): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
,I/BatteryService(  931): n_update end
,D/PMS     (  931): releaseWL(25e8efee): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  931): updateBatteryInfo
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  931): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  931): runPSCheck
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  931): Checking...
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  931): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  931): >> updateStatus
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
,D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  931): User[0] Flushing usage stats to disk
,D/PMS     (  931): acquireWL(1d5cdc8f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(1d5cdc8f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  931): updateBatteryInfo
D/PMS     (  931): runPSCheck
D/HtcPowerSaver(  931): Checking...
I/HtcPowerSaver(  931): >> updateStatus
,D/UsbnetService(  931): BroadcastReceiver::onReceive+,
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  931): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  931): << updateStatus
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  931): acquireWL(3157ab1c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(3157ab1c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  931): updateBatteryInfo,
D/UsbnetService(  931): onReceive BATTERY_CHANGED
,D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): handleMessage: E msg.what=155652
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): processMsg: DefaultState
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  931): handleMessage: X
I/HtcPowerSaver(  931): << updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  931): acquireWL(2c1e9325): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(2c1e9325): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  931): updateBatteryInfo
D/NotificationService(  931): plugged=true pluggin=true
D/PMS     (  931): runPSCheck
,D/HtcPowerSaver(  931): Checking...
I/HtcPowerSaver(  931): >> updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  931): << updateStatus
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  931): acquireWL(d781cfa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PMS     (  931): releaseWL(d781cfa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): BroadcastReceiver::onReceive-
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  931): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  931): updateBatteryInfo
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  931): runPSCheck
D/WifiController(  931): handleMessage: E msg.what=155652
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): processMsg: DeviceActiveState
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  931): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  931): acquireWL(3854b2ab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(3854b2ab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  931): updateBatteryInfo
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/PMS     (  931): runPSCheck
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  931): Checking...
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  931): >> updateStatus
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): battery changed pluggedType: 2,
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  931): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  931): processMsg: DeviceActiveState
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  931): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): processMsg: DefaultState
I/HtcPowerSaver(  931): << updateStatus
D/WifiController(  931): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  931): acquireWL(25c25d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
D/UsbnetService(  931): BroadcastReceiver::onReceive+
I/BatteryService(  931): n_update end
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/PMS     (  931): releaseWL(25c25d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  931): updateBatteryInfo
D/WifiController(  931): handleMessage: E msg.what=155652
D/NotificationService(  931): plugged=true pluggin=true
D/WifiController(  931): processMsg: DeviceActiveState
D/PMS     (  931): runPSCheck
D/WifiController(  931): processMsg: StaEnabledState
D/HtcPowerSaver(  931): Checking...
D/WifiController(  931): processMsg: DefaultState
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): handleMessage: X
D/WifiController(  931): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  931): << updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  931): acquireWL(84a3ca1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(84a3ca1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  931): updateBatteryInfo
D/PMS     (  931): runPSCheck,
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  931): Checking...
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  931): >> updateStatus
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
,D/UsbnetService(  931): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  931): << updateStatus
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/WifiController(  931): handleMessage: E msg.what=155652
,D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  931): acquireWL(2a9ce87): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 931 1000 WorkSource{1000},
,V/AlarmManager(  931): sending alarm PendingIntent{30bbf3e6: PendingIntentRecord{e3b1d27 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1090939, Int=0
I/bt-btm  ( 3118): Received oneshot timer event complete
V/AlarmManager(  931): sending alarm PendingIntent{22a441b4: PendingIntentRecord{112d01dd com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1840729, Int=0
I/bt-btm  ( 3118): btm_ble_timeout
I/bt-btm  ( 3118): btm_gen_resolvable_private_addr
,D/PMS     (  931): acquireWL(14a95152): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3118 1002 null
,D/bt-btm  ( 3118): btm_ble_rand_enc_complete
I/bt-btm  ( 3118): btm_gen_resolve_paddr_low
D/bt-smp  ( 3118): smp_encrypt_data
W/bt-smp  ( 3118): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3118): Plain text(LSB ~ MSB) = dd 7e 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3118): Encrypted text(LSB ~ MSB) = 02 11 2b 2b 1c 2c 82 c4 54 60 37 91 ae 73 1c 15 
I/bt-btm  ( 3118): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3118): Stopping oneshot timer
D/bt-btm  ( 3118): Starting oneshot timer type:103 timeout:900s
I/ProcessStatsService(  931): Prepared write state in 13ms
,I/ProcessStatsService(  931): Prepared write state in 12ms,
,I/ProcessStatsService(  931): Prepared write state in 12ms
,D/PMS     (  931): releaseWL(2a9ce87): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,I/ProcessStatsService(  931): Pruning old procstats: /data/system/procstats/state-2015-12-21-01-31-42.bin,
,D/PMS     (  931): releaseWL(14a95152): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  931): acquireWL(1a4acc23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(1a4acc23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1222): closing low battery warning: level=100
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  931): updateBatteryInfo
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
,D/UsbnetService(  931): BroadcastReceiver::onReceive+
D/NotificationService(  931): plugged=true pluggin=true,
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/PMS     (  931): runPSCheck
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  931): Checking...
D/UsbnetService(  931): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  931): >> updateStatus
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): battery changed pluggedType: 2
D/WifiController(  931): processMsg: DeviceActiveState
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): processMsg: StaEnabledState
D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  931): acquireWL(21dc520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 931 1000 null
I/BatteryService(  931): n_update end
D/PMS     (  931): releaseWL(21dc520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  931): BroadcastReceiver::onReceive+
,D/NotificationService(  931): plugged=true pluggin=true
D/UsbnetService(  931): onReceive BATTERY_CHANGED
D/WifiController(  931): battery changed pluggedType: 2
D/UsbnetService(  931):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  931): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  931): handleMessage: E msg.what=155652
D/WifiController(  931): processMsg: DeviceActiveState
D/WifiController(  931): processMsg: StaEnabledState
,D/WifiController(  931): processMsg: DefaultState
D/WifiController(  931): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  931): updateBatteryInfo
D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  931): runPSCheck
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  931): Checking...
I/HtcPowerSaver(  931): >> updateStatus
,I/HtcPowerSaver(  931): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  931): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  931): acquireWL(f7cded9): PARTIAL_WAKE_LOCK  *alarm* 0x1 931 1000 WorkSource{1000},
,V/AlarmManager(  931): sending alarm PendingIntent{25799316: PendingIntentRecord{18988497 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1687931, Int=0,
V/AlarmManager(  931): sending alarm PendingIntent{35d9a3dc: PendingIntentRecord{15bffce5 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825286, Int=1800000
V/AlarmManager(  931): sending alarm PendingIntent{30bbf3e6: PendingIntentRecord{e3b1d27 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1870939, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{18e7309e: PendingIntentRecord{374077f com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1853700, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{1dea134c: PendingIntentRecord{3f0311ea com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1936065, Int=0
V/AlarmManager(  931): sending alarm PendingIntent{7538f95: PendingIntentRecord{2df51c16 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450740657176, Int=0
D/PMS     (  931): acquireWL(3691b8aa): PARTIAL_WAKE_LOCK  NetworkStats 0x1 931 1000 null
,D/PMS     (  931): releaseWL(3691b8aa): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  931): updateNetworkEnabledLocked()
V/NetworkPolicy(  931): updateNotificationsLocked()
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  931): acquireWL(e4b1838): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(e4b1838): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6986): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  931): releaseWL(f7cded9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6986): MY_DEBUG = false
,D/PowerUsageService( 6986): repeat time = 1450741625203
,D/LocationManagerService(  931): getAllProviders()=[passive, gps, network]
,D/GCM     ( 1857): Message class com.google.f.a.a.i,
D/PMS     (  931): acquireWL(37e3ce6f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1857 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  931): releaseWL(37e3ce6f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/GLSUser ( 1857): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1857): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1857): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1857): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1857): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 6986): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6986): gen(), null == sipper.uidObj, userId = 0
,TIME-OUT KILL (timeout was 1800000ms),D/Process (  931): killProcessQuiet, pid=6844
I/ActivityManager(  931): Killing 6844:com.google.android.apps.magazines/u0a161 (adj 13): empty for 1802s
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  931): Recipient 6844
D/Process (  931): killProcessQuiet, pid=6555
I/ActivityManager(  931): Killing 6555:com.google.android.talk/u0a112 (adj 13): empty for 1802s
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  931): Recipient 6555
D/Process (  931): killProcessQuiet, pid=6394
I/ActivityManager(  931): Killing 6394:com.google.android.setupwizard/u0a77 (adj 13): empty for 1802s
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  931): Recipient 6394
D/Process (  931): killProcessQuiet, pid=6444
I/ActivityManager(  931): Killing 6444:com.htc.bgp/u0a11 (adj 13): empty for 1802s
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  931): Recipient 6444
D/Process (  931): killProcessQuiet, pid=6735
I/ActivityManager(  931): Killing 6735:com.htc.mobiledata:remote/u0a46 (adj 13): empty for 1802s
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/cutils-trace( 7140): Error opening trace file: Permission denied (13)
I/ActivityManager(  931): Recipient 6735
D/CustomizationManager( 7140): ====startRecUseTime====
D/htc.customization.log.level( 7140):  is 
W/CustomizationLogLevel( 7140): Level value is invalid, use default level 2
D/Process (  931): killProcessQuiet, pid=6508
I/ActivityManager(  931): Killing 6508:com.htc.mobiledata/u0a46 (adj 15): empty for 1802s
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/CustomizationManager( 7140):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 7140): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7140): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7140): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7140): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7140): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7140): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7140): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7140): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7140): Parsing tag category name = system
I/CustomizationCIDLoader( 7140): Parsing tag category name = application
I/CustomizationCIDLoader( 7140): Parsing tag category name = SettingsProvider
I/ActivityManager(  931): Recipient 6508
I/CustomizationCIDLoader( 7140): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7140): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7140): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7140): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7140): add string-array item, value = 42507
I/CustomizationCIDLoader( 7140): add string-array item, value = 21902
I/CustomizationCIDLoader( 7140): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7140): add string-array item, value = 23420
I/CustomizationCIDLoader( 7140): add string-array item, value = 22299
I/CustomizationCIDLoader( 7140): add string-array item, value = 24002
I/CustomizationCIDLoader( 7140): add string-array item, value = 23210
I/CustomizationCIDLoader( 7140): add string-array item, value = 23205
I/CustomizationCIDLoader( 7140): add string-array item, value = 23806
I/CustomizationCIDLoader( 7140): add string-array item, value = 23430
I/CustomizationCIDLoader( 7140): add string-array item, value = 23408
I/CustomizationCIDLoader( 7140): add string-array item, value = 27205
I/CustomizationCIDLoader( 7140): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7140): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7140):  Read CID file spent 0.099 (s)
D/CustomizationManager( 7140):  All configurations done spent 0.099 (s)
D/Process (  931): killProcessQuiet, pid=6907
I/ActivityManager(  931): Killing 6907:com.android.chrome/u0a96 (adj 15): empty for 1803s
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PackageManager(  931): deletePackageAsUser: pkg=com.test.thalitest, pid=7140, uid=2000 userid=0
I/ActivityManager(  931): Recipient 6907
W/PackageSettings(  931): Skipping PackageSetting{3bccbf01 com.example.hello/10374} due to missing metadata
I/ActivityManager(  931): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  931): killProcessQuiet, pid=6670
I/ActivityManager(  931): Killing 6670:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
I/WindowState(  931): WIN DEATH: Window{15ab54a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/InputEventReceiver( 1404): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1fbb9265 uid 10366 pid 6670} (c)'
D/WifiService(  931): Client connection lost with reason: 4
I/ActivityManager(  931): Recipient 6670
I/ActivityManager(  931):   Force finishing activity ActivityRecord{d75d7da u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  931): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  931):   Force finishing activity ActivityRecord{d75d7da u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  931): Duplicate finish request for ActivityRecord{d75d7da u0 com.test.thalitest/.MainActivity t8 f}
D/DotMatrix( 1329): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1329): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/SystemReader(  931): Cannot find grip_rejection_width, use default value instead
W/GeofencerStateMachine( 1799): Ignoring removeGeofence because network location is disabled.
W/ActivityManager(  931): Spurious death for ProcessRecord{29211c67 6670:com.test.thalitest/u0a366}, curProc for 6670: null
D/PMS     (  931): acquireWL(386aaa14): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1799 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  931): releaseWL(386aaa14): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/ResourcesManager( 1560): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/AccTypeManager( 1761): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/InputMethodManagerService(  931): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1761): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PhoneApp( 1560): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/VoicemailCleanupService( 1724): Cleaning up data for package: com.test.thalitest
I/art     ( 1619): Explicit concurrent mark sweep GC freed 7324(385KB) AllocSpace objects, 6(488KB) LOS objects, 34% free, 29MB/45MB, paused 1.316ms total 107.535ms
I/Prism.ItemManager( 1619): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1619): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1619): Deferring update until onResume
D/Launcher( 1619): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1619): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1540): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/ResourcesManager(  931): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/[PluginManager]RegisterService( 1540): handle notify Blinkfeed plugin client changed
I/ActivityManager(  931): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7161 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/AccTypeManager( 1761): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 1761): Unsupported attribute readOnly
I/art     (  931): Explicit concurrent mark sweep GC freed 35514(2MB) AllocSpace objects, 12(864KB) LOS objects, 33% free, 16MB/25MB, paused 1.652ms total 235.147ms
I/art     (  931): WaitForGcToComplete blocked for 211.004ms for cause Explicit
W/PackageManager(  931): Unable to load service info ResolveInfo{e5fb0a4 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  931): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  931): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  931): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  931): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  931): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  931): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  931): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  931): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  931): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  931): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  931): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  931): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  931): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  931): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  931): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  931): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/ContextImpl( 7161): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  931): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  931): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  931): hiding MENU key
D/StatusBarManagerService(  931): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  931): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  931): hiding MENU key
D/FindExtension( 1619): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1619): Defer allocateBuffers to drawing time
I/ActivityManager(  931): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7186 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  931): Killing 5994:com.google.android.apps.plus/u0a167 (adj 15): empty for 1803s
D/Process (  931): killProcessQuiet, pid=5994
W/InputMethodManagerService(  931): Got RemoteException sending setActive(false) notification to pid 6670 uid 10366
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/StatusBarManagerService(  931): swetImeWindowStatus vis=0 backDisposition=0
D/JobSchedulerService(  931): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  931): Explicit concurrent mark sweep GC freed 8007(497KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.633ms total 230.162ms
W/asset   (  931): Copying FileAsset 0x55c050cf80 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  931): Recipient 5994
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/TaskPersister(  931): removeObsoleteFile: deleting file=8_task.xml
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7186): -onCreate()
V/Settings:HtcSettingsApplication( 7186): [7186/7186] onCreate()
I/ActivityManager(  931): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7211 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  931): Killing 6802:com.google.android.music:main/u0a159 (adj 15): empty for 1800s
D/Process (  931): killProcessQuiet, pid=6802
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/Settings:HtcWirelessFeatureFlags( 7186): id/is att sku: 118/false
E/Settings:HtcWrapHeaderInfo( 7186): no such activity!
D/MediaRouterService(  931): Client com.google.android.music (pid 6802): Died!
I/ActivityManager(  931): Recipient 6802
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7186): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7186): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7186): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]support         :false
I/ActivityManager(  931): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7186): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7186): isSupportVoWifi: null
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7186): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7186): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7186): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7186): [supportHomeButton]support         :false
I/ActivityManager(  931): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7186): isSupportVoWifi: null
E/ActivityThread( 7186): Failed to find provider info for com.htc.vowifi
I/PackageManager(  931):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7211, uid=10072, userID:0
W/global  ( 7211): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 7211): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 7211): [apache-http] Connection GC has been deprecated!
W/global  ( 7211): [apache-http] Connection GC has been deprecated!
E/RollingFileStream( 7211): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 7211): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  931): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7254 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
E/SQLiteDatabase( 7211): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 7211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7211): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7211): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7211): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 7211): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 7211): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 7211): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7211): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7211): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7211): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 7211): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 7211): Process: com.android.vending, PID: 7211
E/AndroidRuntime( 7211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7211): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7211): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7211): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 7211): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 7211): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 7211): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 7211): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7211): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7211): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Settings( 7211): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/ActivityManager(  931): App crashed! Process: com.android.vending
W/Settings( 7211): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/Process ( 7211): killProcess, pid=7211
E/DropBoxManagerService(  931): Can't write: system_app_crash
E/DropBoxManagerService(  931): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  931): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  931): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  931): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  931): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  931): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  931): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  931): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  931): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  931): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  931): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  931): 	... 5 more
D/Process ( 7211): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
E/lowmemorykiller(  382): Error writing /proc/7211/oom_score_adj; errno=22
I/ActivityManager(  931): Killing 5679:com.google.android.gms.wearable/u0a24 (adj 15): empty for 1801s
D/Process (  931): killProcessQuiet, pid=5679
D/Process (  931): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
I/ActivityManager(  931): Recipient 5679
I/ActivityManager(  931): Recipient 7211
I/ActivityManager(  931): Process com.android.vending (pid 7211) has died
I/TrimMemoryManager( 1619): [trimMemory] 5
D/HtcUPManager( 1222): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 5
D/ChimeraCfgMgr( 4462): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ResourcesManager( 7254): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7254): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Prism.ItemManager( 1619): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1619): loadItems() com.htc.launcher.pageview.WidgetManager@3695237a +
I/Prism.WidgetManager( 1619): onLoadItems() +
I/MultiDex( 7254): VM with version 2.1.0 has multidex support
I/MultiDex( 7254): install
I/MultiDex( 7254): VM has multidex support, MultiDex support library is disabled.
W/ResourcesManager( 1619): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/JNIHelp ( 7254): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 7254): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7254): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ff048eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7254): Installed default security provider GmsCore_OpenSSL
E/SQLiteLog( 1857): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1857): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x55bfc71f70
E/AndroidRuntime( 1857): FATAL EXCEPTION: main
E/AndroidRuntime( 1857): Process: com.google.process.gapps, PID: 1857
E/AndroidRuntime( 1857): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1857): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1857): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1857): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1857): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1857): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1857): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1857): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1857): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1857): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1857): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1857): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1857): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1857): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1857): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1857): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1857): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1857): 	... 9 more
E/ActivityManager(  931): App crashed! Process: com.google.process.gapps
D/Process ( 1857): killProcess, pid=1857
D/Process ( 1857): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/NativeLibraryUtils( 7254): Failed to open lock file
W/NativeLibraryUtils( 7254): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7254): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7254): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7254): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7254): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7254): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7254): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7254): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7254): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7254): 	... 3 more
E/DropBoxManagerService(  931): Can't write: system_app_crash
E/DropBoxManagerService(  931): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  931): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  931): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  931): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  931): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  931): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  931): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  931): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  931): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  931): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  931): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  931): 	... 5 more
W/ResourcesManager( 1619): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  931): Recipient 1857
I/ActivityThread( 7254): Removing dead content provider:android.content.ContentProviderProxy@13fd5ce1
I/ActivityManager(  931): Process com.google.process.gapps (pid 1857) has died
W/ActivityManager(  931): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
W/ActivityManager(  931): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
I/ActivityManager(  931): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7284 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/art     (  442): Explicit concurrent mark sweep GC freed 8675(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 376us total 48.771ms

```
