#### Test 519863409bc5c94_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Process (  941): killProcessQuiet, pid=5595
--------- beginning of system
I/ActivityManager(  941): Killing 5595:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 5595
E/cutils-trace( 6674): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6674): ====startRecUseTime====
D/htc.customization.log.level( 6674):  is 
W/CustomizationLogLevel( 6674): Level value is invalid, use default level 2
D/CustomizationManager( 6674):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 6674): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6674): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6674): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6674): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6674): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6674): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6674): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6674): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6674): Parsing tag category name = system
I/CustomizationCIDLoader( 6674): Parsing tag category name = application
I/CustomizationCIDLoader( 6674): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6674): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6674): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6674): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6674): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6674): add string-array item, value = 42507
I/CustomizationCIDLoader( 6674): add string-array item, value = 21902
I/CustomizationCIDLoader( 6674): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6674): add string-array item, value = 23420
I/CustomizationCIDLoader( 6674): add string-array item, value = 22299
I/CustomizationCIDLoader( 6674): add string-array item, value = 24002
I/CustomizationCIDLoader( 6674): add string-array item, value = 23210
I/CustomizationCIDLoader( 6674): add string-array item, value = 23205
I/CustomizationCIDLoader( 6674): add string-array item, value = 23806
I/CustomizationCIDLoader( 6674): add string-array item, value = 23430
I/CustomizationCIDLoader( 6674): add string-array item, value = 23408
I/CustomizationCIDLoader( 6674): add string-array item, value = 27205
I/CustomizationCIDLoader( 6674): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6674): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6674):  Read CID file spent 0.100 (s)
D/CustomizationManager( 6674):  All configurations done spent 0.100 (s)
I/ActivityManager(  941): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6674 on display 0
D/PMS     (  941): acquireHCC(29f83709): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 941 1000 null
D/PMS     (  941): acquireHCC(196a5d0e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 941 1000 null
W/asset   (  941): Copying FileAsset 0x55b2a86b40 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  941): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6692 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  941): Display changed displayId=0
D/DotMatrix( 1309): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1309): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6692): Copying FileAsset 0xac6d3958 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1498): [trimMemory] 20
I/WebViewFactory( 6692): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6692): Time to load native libraries: 15 ms (timestamps 9303-9318)
I/LibraryLoader( 6692): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6692): Binding Chromium to main looper Looper (main, tid 1) {1ef39e05}
,I/LibraryLoader( 6692): Expected native library version number "",actual native library version number ""
,I/chromium( 6692): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6692): Initializing chromium process, singleProcess=true
,W/art     ( 6692): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6692): ApplicationContext is null in ApplicationStatus
,W/chromium( 6692): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6692): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6692): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6692): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6692): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6692): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6692): Local Branch: 
I/Adreno-EGL( 6692): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6692): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6692):                  d74aa161a12b9c6fc6332151
,W/System.err(  941): java.lang.Throwable: stack dump
,W/System.err(  941): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  941): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  941): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  941): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  941): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  941): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26e13927:true
,D/BluetoothAdapter( 6692): 437589377: getState(). Returning 12
,W/art     ( 6692): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6692): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6692): CordovaWebView is running on device made by: HTC
,W/art     ( 6692): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6692): Attempt to remove local handle scope entry from IRT, ignoring
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,W/chromium( 6692): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
W/HtcSystemUPManager(  941): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  941): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  941): hiding MENU key
D/StatusBarManagerService(  941): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
,D/FindExtension( 6692): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6692): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@34ebd357, mServedView=org.apache.cordova.engine.SystemWebView{2f17ae44 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@10c61b2d
I/InputMethodManagerService(  941): Disable input method client, pid=1498
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/StatusBarManagerService(  941): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6692): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  941): Displayed com.test.thalitest/.MainActivity: +624ms (total +671ms)
,W/BindingManager( 6692): Cannot call determinedVisibility() - never saw a connection for the pid: 6692
,D/JsMessageQueue( 6692): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6692): JniHelper::setJavaVM(0xab5688f8), pthread_self() = -1400192176
D/JX-Cordova( 6692): jxcore cordova android initializing
,W/jxcore-log( 6692): Initializing JXcore engine
W/jxcore-log( 6692): JXcore engine is ready
,W/jxcore-log( 6692): Starting JXcore engine
,W/jxcore-log( 6692): Platform android
W/jxcore-log( 6692): 
W/jxcore-log( 6692): Process ARCH arm
W/jxcore-log( 6692): 
,D/PMS     (  941): releaseHCC(29f83709): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  941): releaseHCC(196a5d0e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6692): JXcore Cordova bridge is ready!
I/jxcore-log( 6692): 
W/jxcore-log( 6692): JXcore engine is started
I/Choreographer( 6692): Skipped 94 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6692): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6692): Toggling radios to true
I/jxcore-log( 6692): 
,D/BluetoothAdapter( 6692): enable(): BT is already enabled..!
,E/WifiTrafficPoller(  941): ADD_CLIENT: 8
D/WifiService(  941): New client listening to asynchronous messages
,D/WifiManager( 6692): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  941): setWifiEnabled: true pid=6692, uid=10366
W/Settings:Agent(  941): MONITOR_LOG
E/WifiService(  941): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  941): name: wifi_on
I/WifiService(  941): isSprintWifiRestricted(): false
W/Settings:Agent(  941): value: 2
I/WifiService(  941): isMdmWifiRestricted(): false
W/Settings:Agent(  941): >> traceCallingStack()
W/Settings:Agent(  941): Process.myPid(): 941
W/Settings:Agent(  941): Process.myTid(): 1738
W/Settings:Agent(  941): Process.myUid(): 1000
W/Settings:Agent(  941): 
W/Settings:Agent(  941): 
,W/System.err(  941): java.lang.Throwable: stack dump
,W/System.err(  941): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  941): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  941): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  941): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  941): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  941): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  941): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  941): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  941): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  941): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  941): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  941): 
W/Settings:Agent(  941): << traceCallingStack(): 12(ms)
D/WifiController(  941): handleMessage: E msg.what=155656
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): handleMessage: X
D/WifiManager( 6692): disconnect: Base Package Name=com.test.thalitest, uid=10366
,D/WifiManager( 6692): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  941): handleMessage: E msg.what=131145
E/WifiStateMachine(  941): processMsg: ConnectedState
E/WifiStateMachine(  941):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  941): processMsg: L2ConnectedState
E/WifiStateMachine(  941):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
,I/jxcore-log( 6692): Radios toggled
I/jxcore-log( 6692): 
D/wpa_supplicant( 1356): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
D/wpa_supplicant( 1356): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1356): TDLS: Tear down peers
D/wpa_supplicant( 1356): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 1356): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1356): wlan0: Deauthentication notification
,D/wpa_supplicant( 1356): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1356): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1356): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1356): enter disconnect check
I/wpa_supplicant( 1356): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  941): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1356): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1356): wlan0: Ignore connection failure indication since interface has been put into disconnected state
,D/Tethering(  941): interfaceLinkStateChanged wlan0, false
D/Tethering(  941): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  941): interfaceLinkStateChanged wlan0, false
D/Tethering(  941): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  941): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/HTCRequest(  941): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  941): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
V/Tethering(  941): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  941): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  941): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbDeviceManager(  941): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): acquireWL(3a9ed50f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 941 1000 null
D/UsbnetService(  941): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1356): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1356): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x558abd0f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1356):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1356): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1356): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1356): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1356): nl80211: Skip set_supp_port(unauthorized) while not associated
,D/wpa_supplicant( 1356): EAPOL: SUPP_BE entering state INITIALIZE
,D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1356): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1356): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1356): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1356): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1356): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1356): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  941): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  941): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  941): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  941): handleMessage: new destination call exit/enter
E/WifiStateMachine(  941): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  941): invokeExitMethods: ConnectedState
E/WifiStateMachine(  941): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  941): release()
E/WifiStateMachine(  941): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  941): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  941): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  941): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  941): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  941): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  941): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  941): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (,  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1356): Power_Mode_Type mode = 0
I/wpa_supplicant( 1356): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  941): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  941): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDataStallTracker(  941): setDhcpActive: false
D/PMS     (  941): releaseWL(3a9ed50f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NativeCrypto( 1888): Read error: ssl=0x55b27615d0: I/O error during system call, Connection timed out
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
V/NetworkPolicy(  941): updateNotificationsLocked()
D/PMS     (  941): acquireWL(3325799c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1888 10024 WorkSource{10024 com.google.android.gms}
D/TetherSettings( 5922): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5922): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5922): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5922): Cust_ConnectToPC   : spcsc>false
D/        ( 5922): Cust_ConnectToPC   : IPT>true
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1888): SSL shutdown failed: ssl=0x55b27615d0: I/O error during system call, Broken pipe
E/WifiStateMachine(  941): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  941): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/        ( 5922): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  941): NetworkAgent != null
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 13
V/NetworkPolicy(  941): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/ConnectivityService(  941): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  941): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  941): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc    (  941): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
W/Settings( 5922): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  941): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  941): stopDataStallAlarm 
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  941): ENABLE_DATA_MONITOR_POLL false Token 3
D/ConnectivityService(  941): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): Forcing reevaluation
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): Validated
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  941): autoRoamSetBSSID any key="NG700"WPA_PSK
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiConfigStore(  941): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/PMS     (  941): releaseWL(3325799c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  941): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  941): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  941): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  941):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  941): Start Disconnecting Watchdog 1
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131146
E/WifiStateMachine(  941): processMsg: DisconnectingState
E/WifiStateMachine(  941):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState CMD_RECONNECT 0 0
,W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1356): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1356): Fast associate: Old scan results
D/wpa_supplicant( 1356): wlan0: Setting scan request: 0.000000 sec
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
D/wpa_supplicant( 1356): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1356): WPS:  * Manufacturer
D/wpa_supplicant( 1356): WPS:  * Model Name
D/wpa_supplicant( 1356): WPS:  * Model Number
D/wpa_supplicant( 1356): WPS:  * Device Name
D/wpa_supplicant( 1356): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1356): P2P: * P2P IE header
D/wpa_supplicant( 1356): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1356): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1356): wlan0: Add radio work 'scan'@0x558abb3860
D/wpa_supplicant( 1356): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1356): wlan0: Starting radio work 'scan'@0x558abb3860 after 0.000049 second wait
D/wpa_supplicant( 1356): wlan0: nl80211: scan request
D/wpa_supplicant( 1356): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1356): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1356): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1356): wlan0: Own scan request started a scan in 0.000119 seconds
I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-SCAN-STARTED 
E/SmartNS_Utility( 5922): hasRemovableStorageSlot: true
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/SmartNS_Utility( 5922): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  941): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/SmartNS_NSReceiver( 5922): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147460
E/WifiStateMachine(  941): processMsg: DisconnectingState
D/HTCRequest(  941): WifiMonitor:handleSupplicantStateChange(): SSID
E/WifiStateMachine(  941):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=131810
E/WifiStateMachine(  941): processMsg: ConnectModeState
D/WifiMonitor(  941): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  941): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  941): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  941):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=131811
E/WifiStateMachine(  941): ConnectModeState: Network connection lost 
E/WifiStateMachine(  941): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  941): handleMessage: new destination call exit/enter
E/WifiStateMachine(  941): setupTempStateStackWithStatesToEnter: X, mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  941): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  941): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  941): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  941): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  941): DisconnectedState call setCountryCode()
E/WifiStateMachine(  941):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1356): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1356): wlan0: nl80211: sched_scan request
,W/ContextImpl( 5922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5922): setISNotification
,D/SmartNS_Utility( 5922): usb_cable_connect = 1
D/SmartNS_Utility( 5922): usb_denied = 0
I/SmartNS_PSService( 5922): usb notificaiton:true
,E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 5922): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0,
D/SmartNS_Utility( 5922): usb_cable_connect = 1
,D/SmartNS_Utility( 5922): usb_denied = 0
D/WifiP2pService(  941): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/WifiP2pService(  941): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiP2pService(  941): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): wlan0: nl80211: Sched scan started
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131101
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
D/wpa_supplicant( 1356): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1356): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1356): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1356): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1356): wlan0: Scan completed in 0.044299 seconds
D/wpa_supplicant( 1356): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1356): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1356): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1356): wlan0: New scan results available (own=1 ext=0)
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  941):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
D/wpa_supplicant( 1356): wlan0: Radio work 'scan'@0x558abb3860 done in 0.045067 seconds
D/wpa_supplicant( 1356): wlan0: No suitable network found
D/wpa_supplicant( 1356): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1356): wlan0: Cancelling sched scan
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  941): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1356): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
D/wpa_supplicant( 1356): p2p0: Updating scan results from sibling
D/WifiMonitor(  941): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 1356): nl80211: Received scan results (0 BSSes)
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPS-AP-AVAILABLE 
E/WifiStateMachine(  941):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1356): p2p0: BSS: Start scan result update 1
W/WifiMonitor(  941): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine(  941): processMsg: DefaultState
D/wpa_supplicant( 1356): BSS: last_scan_res_used=0/0
,D/wpa_supplicant( 1356): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1356): p2p0: No suitable network found
D/wpa_supplicant( 1356): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1356): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  941): WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  941): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  941):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  941): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  941): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147462
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=131854  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  941): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  941): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=131855  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  941): handleMessage: X
D/WifiNetworkAgent(  941): NetworkAgent: NetworkAgent channel lost
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  941): handleMessage: E msg.what=131212
E/WifiStateMachine(  941): processMsg: DisconnectedState
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  941):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
I/RemoteViews( 1223): reapply : com.android.settings 2 36
E/WifiStateMachine(  941): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131212
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
,E/WifiStateMachine(  941):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/SmartNS_PSService( 5922): usb notificaiton:true
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  941): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  941): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=131212
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  941): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  941): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147462
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=131864  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  941): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  941): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  941): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  941): NetworkAgent == null
E/WifiStateMachine(  941): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/SmartNS_NSReceiver( 5922): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  941): processMsg: ConnectModeState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  941):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=131868  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  941): handleMessage: X
E/WifiStateMachine(  941): handleMessage: E msg.what=147461
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:87 bcn=0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:87 bcn=0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:87 bcn=0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:87 bcn=0
D/WifiStateMachine(  941): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1356): wlan0: Control interface command 'LIST_DONGLES'
,I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
,E/WifiStateMachine(  941): [1,448,880,676,658 ms] noteScanEnd no scan source
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1356): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 16
,E/WifiStateMachine(  941): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2f34b832 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  941): NG7005g c0:ff:d4:d3:aa:4a rssi=-46 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  941): NG700 c0:ff:d4:d3:aa:48 rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  941): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  941): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  941):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-55 freq=2462
E/WifiAutoJoinController (  941): 01ABC c2:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  941): Gonzos 38:f8:89:11:e9:11 rssi=-89 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  941): FunBox2-3E72 00:37:b7:9d:3e:72 rssi=-92 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
,E/WifiAutoJoinController (  941): ageScanResultsOut delay 40000 size 5 now 1448880676662
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiAutoJoinController (  941): newSupplicantResults size=5 known=1 true
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/wpa_supplicant( 1356): wlan0: Control interface command 'STATUS-NO_EVENTS'
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  941): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiAutoJoinController (  941): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  941): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  941): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  941): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  941): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  941): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-55,-127) num=(1,0)
E/WifiAutoJoinController (  941): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  941): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  941): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  941): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  941): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-55 freq=2462
D/HtcWifiControlRoamOffload: (  941): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  941): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiAutoJoinController (  941): Done attemptAutoJoin status=3
E/WifiConfigStore(  941):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  941): handleMessage: X
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  941): handleMessage: E msg.what=131215
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiStateMachine(  941):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-55 ;0 ,-127] any roam=0 rt=131882
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-55 ;0 ,-127] any roam=0 rt=131882
I/RemoteViews( 1223): reapply : com.android.settings 1 36
E/WifiStateMachine(  941): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  941): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  941): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
,D/ConnectivityService(  941): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  941):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  941): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  941): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  941): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  941): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  941): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  941): Removing idletimer
D/usbnet  (  941):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  941): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  941): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524292
I/SecurityController( 1223): onLost 100
,D/PMS     (  941): acquireWL(61acf7a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 941 1000 null
D/CSLegacyTypeTracker(  941): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  941): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  941): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  941): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/ConnectivityService(  941): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
V/NetworkPolicy(  941): ensureActiveMobilePolicyLocked()
D/Tethering(  941): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  941): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
,D/WISPrService( 5922): >>>>>WISPrService start isConnected = true<<<<<
D/PMS     (  941): acquireWL(36fdb32b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 941 1000 null
D/NetworkPolicy(  941): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
V/NetworkPolicy(  941): updateIfacesLocked()
V/NetworkPolicy(  941): updateNotificationsLocked()
E/WifiConfigStore(  941): Setting BSSID for "NG700"WPA_PSK to any
D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/NetworkManagementService(  941): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
,D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
,D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/DATA_ICON( 1223): dataConnected: false/false
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1356): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  941): will read network variables netId=0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx',
,D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/WifiService(  941): New client listening to asynchronous messages
D/wpa_supplicant( 1356): Do not allow key_data field to be exposed
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  9,41): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  941): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  941):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  941): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  941): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiTrafficPoller(  941): ADD_CLIENT: 9
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1356): ENABLE_NETWORK (0)
D/PMS     (  941): releaseWL(36fdb32b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1356): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1356): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1356): wpa_supplicant_scan enter
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
D/wpa_supplicant( 1356): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1356): WPS:  * Manufacturer
D/wpa_supplicant( 1356): WPS:  * Model Name
D/wpa_supplicant( 1356): WPS:  * Model Number
D/wpa_supplicant( 1356): WPS:  * Device Name
D/wpa_supplicant( 1356): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1356): P2P: * P2P IE header
D/wpa_supplicant( 1356): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1356): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1356): wlan0: Add radio work 'scan'@0x558abb3860
D/wpa_supplicant( 1356): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1356): wlan0: Starting radio work 'scan'@0x558abb3860 after 0.000027 second wait
D/wpa_supplicant( 1356): wlan0: nl80211: scan request
D/wpa_supplicant( 1356): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1356): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1356): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1356): wlan0: Own scan request started a scan in 0.000118 seconds
I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  941): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  941): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
V/NetworkPolicy(  941): updateNotificationsLocked()
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  941): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1356): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  941): will read network variables netId=0
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='priority'
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1356): Do not allow key_data field to be exposed
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1356): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1356): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  941): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  941):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1356): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1356): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1356): wpa_supplicant_scan enter
D/wpa_supplicant( 1356): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1356): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1356): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  941): setLastSelectedConfiguration -1
E/WifiStateMachine(  941): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  941): handleMessage: new destination call exit/enter
E/WifiStateMachine(  941): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  941): invokeExitMethods: DisconnectedState
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1356): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  941): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  941): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  941): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  941): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  941): DisconnectedState call setCountryCode()
E/WifiStateMachine(  941):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1356): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
D/wpa_supplicant( 1356): wlan0: nl80211: sched_scan request
D/FlexNetS( 6535): updateSvcAllowedInSettings:false
I/ActivityManager(  941): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6754 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/wpa_supplicant( 1356): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1356): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1356): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1356): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1356): wlan0: Event SCAN_RESULTS (3) received
D/WifiP2pService(  941): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): Got an original EVENT_SCAN_RESULTS
D/WifiP2pService(  941): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): wlan0: Scan completed in 0.040084 seconds
D/WifiP2pService(  941): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): nl80211: Received scan results (0 BSSes)
W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1356): wlan0: BSS: Start scan result update 8
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
E/WifiStateMachine(  941): handleMessage: X
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to no match in scan
D/WIFI    (  941): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to no match in scan
D/wpa_supplicant( 1356): wlan0: BSS: Remove id 4 BSSID 00:37:b7:9d:3e:72 SSID 'FunBox2-3E72' due to no match in scan
D/WIFI    (  941):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/wpa_supplicant( 1356): BSS: last_scan_res_used=0/32
D/WIFI    (  941): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/wpa_supplicant( 1356): wlan0: New scan results available (own=1 ext=0)
E/WifiStateMachine(  941): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/wpa_supplicant( 1356): wlan0: Radio work 'scan'@0x558abb3860 done in 0.041011 seconds
D/wpa_supplicant( 1356): wlan0: No suitable network found
E/WifiStateMachine(  941): handleMessage: E msg.what=131131
D/wpa_supplicant( 1356): wlan0: Setting scan request: 15.000000 sec
E/WifiStateMachine(  941): processMsg: DisconnectedState
D/wpa_supplicant( 1356): wlan0: Cancelling sched scan
D/wpa_supplicant( 1356): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
D/wpa_supplicant( 1356): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1356): nl80211: Received scan results (0 BSSes)
E/WifiStateMachine(  941):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  941): processMsg: ConnectModeState
D/wpa_supplicant( 1356): p2p0: BSS: Start scan result update 2
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1356): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1356): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1356): p2p0: No suitable network found
D/wpa_supplicant( 1356): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Sched scan stopped
E/WifiStateMachine(  941):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/wpa_supplicant( 1356): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  941): handleMessage: X
D/FlexNetS( 6535): updateSvcAllowedInSettings:false
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
D/WifiMonitor(  941): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:37:b7:9d:3e:72]
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:37:b7:9d:3e:72
E/WifiMonitor(  941): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  941): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  941): WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  941): handleMessage: E msg.what=147461
E/WifiStateMachine(  941): processMsg: DisconnectedState
E/WifiMonitor(  941): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  941):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:87 bcn=0
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:87 bcn=0
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:87 bcn=0
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:87 bcn=0
D/WifiStateMachine(  941): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1356): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  941): [1,448,880,676,748 ms] noteScanEnd no scan source
W/WifiHW  (  941): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1356): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  941): handleMessage: X
W/WISPrService( 5922): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5922): trigger connection
D/WISPrService( 5922): continue
D/FlexNetS( 6535): updateSvcAllowedInSettings:false
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/FlexNetS( 6535): updateSvcAllowedInSettings:false
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/WISPrService( 5922): start DataConnection
D/libc    ( 5922): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5922): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5922): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/WISPrService( 5922): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5922): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5922): [NET] android_getaddrinfo_proxy+
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/WISPrService( 5922): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5922): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5922): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5922): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WISPrService( 5922): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/FlexNetS( 6535): updateSvcAllowedInSettings:false
D/WISPrService( 5922): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5922): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5922): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5922): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false,
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false
,D/WifiService(  941): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/libc    ( 5922): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 5922): [NET] android_getaddrinfofornet-, err=8
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false
,D/WISPrService( 5922): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false
,D/FlexNetS( 6535): updateSvcAllowedInSettings:false,
,D/MdScPhnSt( 6754): [649.2.]  listen tmrbb8,
,D/MdProvGlob( 6598): remove item 101 (p2d27in201) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6754): [649.2.] summary 118:p2 ignore
,D/Process (  941): killProcessQuiet, pid=6210
,I/ActivityManager(  941): Killing 6210:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6210
,D/BluetoothManagerService(  941): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/jxcore-log( 6692): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): my name is : HTC-HTC One M8s_PT3670
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): attempting to connect to test coordinator
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): check test folder
I/jxcore-log( 6692): 
I/jxcore-log( 6692): found test : ./testFindPeers.js
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): found test : ./testReConnect.js
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): found test : ./testSendData.js
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): Test app app.js loaded,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
I/Choreographer( 6692): Skipped 152 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6692): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/ConnectivityService(  941): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  941): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
I/AlarmManager(  941): [AlarmQueuing] connectivity wifi: false
D/PMS     (  941): acquireWL(298d6034): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 941 1000 null
D/GpsLocationProvider(  941): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  941): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/htcCheckinService(  941): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  941): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/ConnectivityHelper( 1498): [onReceive] WIFI(1): DISCONNECTED
,I/ActivityManager(  941): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6786 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  941): No APN found to select.
,D/PMS     (  941): releaseWL(298d6034): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,D/MdScPhnSt( 6754): [13f.1.]  listen tmrbb8
,D/MdScDataSum( 6754): [13f.1.] summary 118:p1 ignore
,I/MusicStore( 6786): Database version: 120,
,D/VoldConnector(  941): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6786): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  941): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6786): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/VoldConnector(  941): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
W/ContextImpl( 6786): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/ResourcesManager( 6786): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6786): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 6786): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PMS     (  941): acquireWL(2c290ff7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{213f09bf: PendingIntentRecord{2589888c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=115216, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{20633e64: PendingIntentRecord{2c9c38cd com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=135289, Int=0
,D/WeatherUtility( 1223): Weather sync is On,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/ActivityThread( 6786): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6786): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1261bae9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6786): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6786): GMSCore installation verified
,I/ConfigStore( 6786): Config Database version: 1,
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6786, uid=10159, userID:0,
,D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: 
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
,D/MediaRouterService(  941): Client com.google.android.music (pid 6786): Registered
,D/WifiDisplayAdapter(  941): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  941):     Client/Owner: Client
D/WifiDisplayAdapter(  941):     GroupId: ,
D/WifiDisplayAdapter(  941):     Passphrase: 
D/WifiDisplayAdapter(  941):     SessionId: 0
D/WifiDisplayAdapter(  941):     IP Address: }
,I/MediaRouter( 6786): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6786): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6786, uid=10159, userID:0,
,D/AutoSetting( 1577): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6415): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/AutoSetting( 1577): Util - no network available!
,D/MobileConnectivityChangeReceiver( 6415): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1577): service - onCreate(),
,I/GHttpClientFactory( 6786): Using our fixed implementation of GMSCore's GoogleHttpClient,
,I/GoogleURLConnFactory( 6786): Using platform SSLCertificateSocketFactory,
,D/LocationManagerService(  941): request 12d59113 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  941): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1577): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1577): service - mHandler: cancel location update
,D/AutoSetting( 1577): service -           changes count: 0
,I/iu.Environment( 4441): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4441): num queued entries: 0
I/iu.UploadsManager( 4441): num updated entries: 0
,I/iu.SyncManager( 4441): NEXT; no task
,D/ChimeraCfgMgr( 4441): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  941): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6828 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/Babel   ( 6465): connection state changed from UNKNOWN to DISCONNECTED
I/ActivityManager(  941): Killing 6370:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  941): killProcessQuiet, pid=6370
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  451): Explicit concurrent mark sweep GC freed 8646(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 247us total 30.232ms
,I/art     (  451): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 21.694ms,
,I/art     (  451): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 21.515ms,
,I/ActivityManager(  941): Recipient 6370
,D/VoldConnector(  941): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6828): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  941): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6828): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6828): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6828):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6828):   adb logcat -s GAv4
,D/VoldConnector(  941): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6828): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  941): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
W/ContextImpl( 6828): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/GAv4    ( 6828): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6828): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6828): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/global  ( 6828): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6828): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6828): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6828): Time to load native libraries: 1 ms (timestamps 6193-6194),
I/LibraryLoader( 6828): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6828): Binding Chromium to main looper Looper (main, tid 1) {29da0110},
I/LibraryLoader( 6828): Expected native library version number "",actual native library version number ""
,I/chromium( 6828): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6828): Initializing chromium process, singleProcess=true,
,W/art     ( 6828): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6828): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6828): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6828): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6828): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6828): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6828): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6828): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6828): Local Branch: 
I/Adreno-EGL( 6828): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6828): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6828):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6828): Requires BLUETOOTH permission,
,I/NSApplication( 6828): Starting up...,
,I/ActivityManager(  941): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6886 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  941): Killing 6441:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  941): killProcessQuiet, pid=6441
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,I/ActivityManager(  941): Recipient 6441,
,I/ActivityManager(  941): Killing 5947:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  941): killProcessQuiet, pid=5947
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/WifiStateMachine(  941): handleMessage: E msg.what=131168,
E/WifiStateMachine(  941): processMsg: DisconnectedState
,E/WifiStateMachine(  941):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): processMsg: ConnectModeState
E/WifiStateMachine(  941):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): processMsg: DriverStartedState
E/WifiStateMachine(  941):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  941): processMsg: SupplicantStartedState
E/WifiStateMachine(  941):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): processMsg: DefaultState
E/WifiStateMachine(  941):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  941): handleMessage: X,
,I/ActivityManager(  941): Recipient 5947,
,D/PMS     (  941): acquireWL(6ff6954): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1888 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): releaseWL(2c290ff7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024},
,D/libc    ( 1888): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1888): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1888): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1888): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1888): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1888): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1888): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  941): releaseWL(6ff6954): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): BLE advertisement not supported: Not supported,
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(2722d1f2): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6786 10159 null,
,I/art     (  941): Explicit concurrent mark sweep GC freed 38572(2028KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.666ms total 157.839ms
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6786, uid=10159, userID:0,
,D/PMS     (  941): releaseWL(2722d1f2): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6786): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6786): Stop autocaching.
,D/WearableService( 5120): callingUid 10024, callindPid: 5120
,E/GmsUtils( 6786): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 6786): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(362fc36d): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{10024},
,V/AlarmManager(  941): sending alarm PendingIntent{332f9ba2: PendingIntentRecord{dfcd033 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142526, Int=0,
D/PMS     (  941): releaseWL(362fc36d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  941): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  941): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/ContactMessageStore( 1444): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1444): MSG_NOTIFY_CS_TO_SYNC <<
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6692): 
,W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1577): service - handleMessage() stop self
,D/AutoSetting( 1577): service - handleMessage() quit looper
D/AutoSetting( 1577): service - onDestroy() END,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(36865ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  941): n_update end
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  941): releaseWL(36865ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true,
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PMS     (  941): runPSCheck
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): battery changed pluggedType: 2
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  941): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: DefaultState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/TelephonyReceiver( 1444): switchBindHtcMsgCursor: null,
,D/PMS     (  941): acquireWL(c122969): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{3aaa3c8f: PendingIntentRecord{3e898b1c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1448880716533, Int=0
D/PMS     (  941): acquireWL(1c8fcfee): PARTIAL_WAKE_LOCK  *backup* 0x1 941 1000 null
,V/AlarmManager(  941): sending alarm PendingIntent{213f09bf: PendingIntentRecord{2589888c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=175215, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{3c9af325: PendingIntentRecord{37acfcfa com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189365, Int=0
,D/PMS     (  941): acquireWL(d1812ab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1888 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  941): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  941): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  941): releaseWL(1c8fcfee): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  941): releaseWL(d1812ab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  941): releaseWL(c122969): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  941): releaseWL(61acf7a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  941): Failed to find a new network - expiring NetTransition Wakelock
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(10432e87): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000},
V/AlarmManager(  941): sending alarm PendingIntent{283221b4: PendingIntentRecord{28d561dd android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=208521, Int=0
,D/PMS     (  941): releaseWL(10432e87): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1577): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2c9f8d4
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  941): Killing 5861:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  941): killProcessQuiet, pid=5861
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 5861
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(349a3152): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  941): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  941): releaseWL(349a3152): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  941): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  941): runPSCheck
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  941): Checking...
I/HtcPowerSaver(  941): >> updateStatus
D/PowerUI ( 1223): closing low battery warning: level=100
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): handleMessage: E msg.what=155652
,D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(181a2c23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(181a2c23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  941): updateBatteryInfo
,D/PMS     (  941): runPSCheck
D/HtcPowerSaver(  941): Checking...
I/HtcPowerSaver(  941): >> updateStatus,
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  941): << updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  941): plugged=true pluggin=true
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  941): processMsg: StaEnabledState
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/WifiController(  941): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: X
,D/WifiController(  941): battery changed pluggedType: 2
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(2a9a520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
,D/PMS     (  941): releaseWL(2a9a520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive+,
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive-
,D/PMS     (  941): runPSCheck
D/WifiController(  941): handleMessage: E msg.what=155652
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: StaEnabledState
,I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: X
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(294b3ed9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{213f09bf: PendingIntentRecord{2589888c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=235215, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{3ed9677f: PendingIntentRecord{b53f34c com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1448880886256, Int=0,
,I/ActivityManager(  941): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6925 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  941): sending alarm PendingIntent{1fa7ef95: PendingIntentRecord{7be98aa com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1448881004956, Int=0
,D/PMS     (  941): releaseWL(294b3ed9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,E/cutils-trace( 6946): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6946): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6946): dex2oat: override thread count:4
,I/dex2oat ( 6946): dex2oat took 977.008ms (threads: 4)
,I/PushClient( 6925): ApplicationMonitor {13138267}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6925): ApplicationMonitor {13138267}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6925): ApplicationMonitor {13138267}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6925): ApplicationMonitor {13138267}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6925): ApplicationMonitor {13138267}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk,
I/PushClient( 6925): ApplicationMonitor {13138267}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6925): ApplicationMonitor {13138267}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6925): ApplicationMonitor {13138267}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6925): ApplicationMonitor {13138267}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6925): PnsModel {2a4da626}: update(): Update registration caused by: alarm,
,I/PushClient( 6925): PnsConfigModel {2c711275}: <init>(): Use dm-client for provisioning.
,W/System.err( 6925): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6925): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6925): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6925): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  941): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6953 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6953): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6953 dbg=false s=true
,I/DeviceManagement( 6953): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6953): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6953): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6953): WorkflowService: Starting workflow service
,I/DeviceManagement( 6953): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2a4da626] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6953): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6953): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6953): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6953): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6953): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6953): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6953): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6953): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2a4da626],
,I/DeviceManagement( 6953): WorkflowService: Stopping workflow service,
,D/Process (  941): killProcessQuiet, pid=6566
I/ActivityManager(  941): Killing 6566:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6925): PnsModel {2a4da626}: update(): Start updating since the registration has expired.,
,I/ActivityManager(  941): Recipient 6566,
D/WifiService(  941): Client connection lost with reason: 4
,W/PushClient( 6925): GCMRegistrator {2cac81dc}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.,
W/PushClient( 6925):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6925):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 6925):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6925):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 6925):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
W/PushClient( 6925):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 6925):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 6925):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6925):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6925):   
,D/GCM     ( 1888): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER,
,D/libc    ( 1888): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 1888): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1888): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 1888): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1888): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1888): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1888): [NET] android_getaddrinfo_proxy-, NODATA
,E/PushClient( 6925): PnsModel {2a4da626}: update(): com.htc.lib1.cs.push.exception.UpdateRegistrationFailedException: SERVICE_NOT_AVAILABLE,
E/PushClient( 6925):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:198)
E/PushClient( 6925):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
E/PushClient( 6925):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
E/PushClient( 6925):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PushClient( 6925):   	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PushClient( 6925):   	at android.os.Looper.loop(Looper.java:155)
E/PushClient( 6925):   	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PushClient( 6925):   Caused by: java.io.IOException: SERVICE_NOT_AVAILABLE
E/PushClient( 6925):   	at com.google.android.gms.gcm.GoogleCloudMessaging.register(Unknown Source)
E/PushClient( 6925):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.registerGCM(GCMRegistrator.java:301)
E/PushClient( 6925):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:196)
E/PushClient( 6925):   	... 6 more
E/PushClient( 6925):   
,I/PushClient( 6925): CentralClientRetryPolicy {1ef39e05}: scheduleUpdateRetry(): Waiting for network connectivity...,
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=1, flag=1, pid=6925, uid=10071, userID:0
,D/Process (  941): killProcessQuiet, pid=6622
I/ActivityManager(  941): Killing 6622:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6622
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/Prism.ItemManager( 1498): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
I/Prism.ItemManager( 1498): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1725): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  941): Cannot find grip_rejection_width, use default value instead,
,D/AccTypeManager( 1725): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  941): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/[PluginManager]RegisterService( 1577): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.pns
I/[PluginManager]RegisterService( 1577): handle notify Blinkfeed plugin client changed
,D/AccTypeManager( 1725): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1444): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,I/ActivityManager(  941): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6988 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/ExternalAccountType( 1725): Unsupported attribute readOnly,
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6988, uid=10072, userID:0
,W/global  ( 6988): [apache-http] Connection GC has been deprecated!
,W/PackageManager(  941): Unable to load service info ResolveInfo{2fa05261 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  941): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  941): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  941): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  941): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  941): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  941): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  941): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  941): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  941): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  941): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029),
W/PackageManager(  941): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/Finsky  ( 6988): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 6988): [apache-http] Connection GC has been deprecated!
,W/global  ( 6988): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 6988): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  941): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7026 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 6988): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
W/Settings( 6988): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7026): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7026): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6988, uid=10072, userID:0,
,I/MultiDex( 7026): VM with version 2.1.0 has multidex support
,I/MultiDex( 7026): install
I/MultiDex( 7026): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6988): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 6988): [1] 2.run: Finished loading 1 libraries.
,V/JNIHelp ( 7026): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/Finsky  ( 6988): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,D/PackageBroadcastService( 4441): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.pns
,D/Finsky  ( 6988): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PMS     (  941): acquireWL(258e8164): PARTIAL_WAKE_LOCK  AsyncService 0x1 6016 10167 null
D/PMS     (  941): releaseWL(258e8164): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/PeopleContactsSync( 4441): CP2 sync disabled
,D/PMS     (  941): acquireWL(99f1393): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6016 10167 null
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4441, uid=10024, userID:0
D/PMS     (  941): acquireWL(7644fd0): PARTIAL_WAKE_LOCK  Icing 0x1 4441 10024 WorkSource{10024 com.google.android.gms}
,W/ActivityThread( 7026): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7026): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3225c937: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7026): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  941): releaseWL(99f1393): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/PMS     (  941): releaseWL(7644fd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  941): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7058 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,I/ActivityManager(  941): Killing 6496:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  941): killProcessQuiet, pid=6496
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6496
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/GCM     ( 1888): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1888): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4441): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/PMS     (  941): acquireWL(28d41b85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(28d41b85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  941): updateBatteryInfo
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): Checking...
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: DeviceActiveState
,D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,D/WearableService( 5120): callingUid 10024, callindPid: 5120
,I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4441, uid=10024, userID:0
,E/MDM     ( 1812): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/UpdateIcingCorporaServi( 7058): Updating corpora: APPS=com.htc.cs.pns, CONTACTS=MAYBE
,D/LocationInitializer( 4441): Restart initialization of location
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/LocationManagerService(  941): getProviders()=[passive]
,I/ActivityManager(  941): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7093 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,V/Finsky  ( 6988): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/UpdateIcingCorporaServi( 7058): UpdateCorporaTask done [took 147 ms] updated apps [took 146 ms] ,
,D/Process (  941): killProcessQuiet, pid=6598
I/ActivityManager(  941): Killing 6598:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6598
,D/Finsky  ( 6988): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
D/PMS     (  941): acquireWL(30edbc18): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{10072}
V/AlarmManager(  941): sending alarm PendingIntent{17189671: PendingIntentRecord{1fb4ac56 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448881018797, Int=0
D/PMS     (  941): releaseWL(30edbc18): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6988): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Prism.ItemManager( 1498): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1498): loadItems() com.htc.launcher.pageview.WidgetManager@6d1d449 +
I/Prism.WidgetManager( 1498): onLoadItems() +
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ResourcesManager( 1498): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ResourcesManager( 1498): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/art     (  941): Explicit concurrent mark sweep GC freed 24824(1358KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.399ms total 169.376ms
,W/Finsky  ( 6988): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/asset   ( 1498): Copying FileAsset 0x55b2c39a30 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/AndroidHttpClient( 6988): Leak found,
E/AndroidHttpClient( 6988): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 6988): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 6988): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 6988): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 6988): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 6988): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 6988): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 6988): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 6988): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 6988): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 6988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 6988): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 6988): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 6988): 	at java.lang.reflect.Method.invoke(Native Method)
,E/AndroidHttpClient( 6988): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 6988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 6988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/Prism.WidgetManager( 1498): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1498): onLoadItems() -
I/Prism.ItemManager( 1498): loadItems() com.htc.launcher.pageview.WidgetManager@6d1d449 -
,D/PhoneApp( 1444): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1444): -- N1 =0
,D/PhoneApp( 1444): -- N2 =0
,D/PhoneApp( 1444): -- N3 =0
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1888): Explicit concurrent mark sweep GC freed 15747(908KB) AllocSpace objects, 7(332KB) LOS objects, 49% free, 4MB/8MB, paused 1.237ms total 84.085ms
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6988): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6988): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6988): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6988): [1] DailyHygiene.reschedule: Scheduling new run in 877 minutes (failures=5)
,D/DeviceConnectionService( 1812): client connected with version: 7571000
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/Process (  941): killProcessQuiet, pid=6754,
I/ActivityManager(  941): Killing 6754:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6754
,D/Process (  941): killProcessQuiet, pid=6535
I/ActivityManager(  941): Killing 6535:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  941): Recipient 6535,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(3e3c6c54): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000},
,V/AlarmManager(  941): sending alarm PendingIntent{213f09bf: PendingIntentRecord{2589888c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=475215, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{28f70cf2: PendingIntentRecord{2c4e6f43 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448881034420, Int=0,
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data,
D/PMS     (  941): releaseWL(3e3c6c54): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/Finsky  ( 6988): [698] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 6988): [1] 5.onFinished: Installation state replication succeeded.,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(141df9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(141df9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1223): closing low battery warning: level=100
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): handleMessage: E msg.what=155652
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): processMsg: DeviceActiveState
,D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/HtcPowerSaver(  941): updateBatteryInfo
D/PMS     (  941): runPSCheck
D/HtcPowerSaver(  941): Checking...
I/HtcPowerSaver(  941): >> updateStatus
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  941): << updateStatus
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  941): acquireWL(1d5c06f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  941): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  941): releaseWL(1d5c06f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
,D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/ContactMessageStore( 1444): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1444): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1444): sku_id=118
,D/ContactMessageStore( 1444): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1444): start background delete task...
,D/ContactMessageStore( 1444): size: 0 , 0
,D/ContactMessageStore( 1444): Background delete complete
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): ,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(27e5063e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(27e5063e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): << updateStatus
,D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1888): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1888): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1888): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1888): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1888): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1888): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1888): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6988): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6988): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6988): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6988): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 4 40
,W/System  ( 6988): Ignoring header User-Agent because its value was null.
,D/libc    ( 6988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6988): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6988): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6988): [NET] android_getaddrinfo_proxy+
D/libc    ( 6988): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6988): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(248352f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(248352f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/HtcPowerSaver(  941): updateBatteryInfo
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  941): runPSCheck
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): Checking...
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  941): >> updateStatus
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): ,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(24cfa069): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(24cfa069): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  941): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  941): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(297d7aee): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(297d7aee): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  941): plugged=true pluggin=true
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  941): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): onReceive BATTERY_CHANGED
,I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: E msg.what=155652
,D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(27f60b8f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
,V/AlarmManager(  941): sending alarm PendingIntent{213f09bf: PendingIntentRecord{2589888c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=535215, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{3ae2ae1c: PendingIntentRecord{2938da25 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940978, Int=0
,I/bt-btm  ( 3101): Received oneshot timer event complete
I/bt-btm  ( 3101): btm_ble_timeout
I/bt-btm  ( 3101): btm_gen_resolvable_private_addr
,D/PMS     (  941): acquireWL(3d4a57fa): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3101 1002 null
,D/bt-btm  ( 3101): btm_ble_rand_enc_complete
I/bt-btm  ( 3101): btm_gen_resolve_paddr_low
D/bt-smp  ( 3101): smp_encrypt_data
W/bt-smp  ( 3101): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 3101): Plain text(LSB ~ MSB) = 98 3f 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3101): Encrypted text(LSB ~ MSB) = ed 69 9c d8 b6 6a 9c d0 20 4d 49 b4 54 b4 6f 6f 
I/bt-btm  ( 3101): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3101): Stopping oneshot timer
D/bt-btm  ( 3101): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  941): releaseWL(27f60b8f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  941): releaseWL(3d4a57fa): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(4d1d1ab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(4d1d1ab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  941): plugged=true pluggin=true
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  941): runPSCheck
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(107a9008): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{1613cb56: PendingIntentRecord{8e5f7d7 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804990, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{213f09bf: PendingIntentRecord{2589888c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=955215, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{a41f3a1: PendingIntentRecord{5d5f9c6 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448881493208, Int=1800000
V/AlarmManager(  941): sending alarm PendingIntent{2359dd87: PendingIntentRecord{c2ca4b4 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448881200000, Int=86400000,
,V/AlarmManager(  941): sending alarm PendingIntent{206928dd: PendingIntentRecord{39f14391 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448881510848, Int=0
,D/PMS     (  941): acquireWL(f27ec52): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4441 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  941): acquireWL(3f495820): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4441 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  941): releaseWL(f27ec52): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  941): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=7128 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/EventLogService( 4441): Aggregate from 1448880646227 (log), 1448879693141 (data),
,D/PMS     (  941): releaseWL(3f495820): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 7128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  941): releaseWL(107a9008): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 7128): MY_DEBUG = false,
,D/PowerUsageService( 7128): repeat time = 1448882411169,
,I/PowerUsageList:PowerUsageHelper( 7128): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 7128): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 7128): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 7128): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 7128): calcPower(), no data
,D/Process (  941): killProcessQuiet, pid=6415
I/ActivityManager(  941): Killing 6415:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  941): Recipient 6415
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(f0d9695): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{18e8b3aa: PendingIntentRecord{214e7b9b com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448881557668, Int=0
,D/SmartSyncUtils( 7128): isEpsOn(), nState = 0
,D/PMS     (  941): acquireWL(cf60b38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7128 1000 null
,D/PMS     (  941): releaseWL(f0d9695): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  941): releaseWL(cf60b38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  941): acquireWL(217e0711): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7128 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 7128): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 7128): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 7128): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 7128): SettingOnTime = 1448949600000, randomSettingOnTime = 1448946986000
,D/SmartSyncScreenOnOffTimeReceiver( 7128): SettingOffTime = 1448928000000, randomSettingOffTime = 1448928178000
,D/SmartSyncScreenOnOffTimeReceiver( 7128): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 7128): bNightMode = true,
D/SmartSyncScreenOnOffTimeReceiver( 7128): bNightModeTurnOffOnce = false
,D/PMS     (  941): releaseWL(217e0711): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(30f66076): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): releaseWL(30f66076): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PMS     (  941): runPSCheck
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  941): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  941): >> updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: E msg.what=155652
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1888): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1888): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1888): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1888): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1888): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1888): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1888): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 6988): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6988): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6988): ,	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6988): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6988): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 6988): Ignoring header User-Agent because its value was null.
,D/libc    ( 6988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6988): [NET] android_getaddrinfofornet-, err=8
I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,D/libc    ( 6988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6988): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6988): [NET] android_getaddrinfo_proxy+
D/libc    ( 6988): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6988): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(3e9eb268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(3e9eb268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  941): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  941): runPSCheck
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  941): processMsg: DefaultState
,I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(285dd681): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(285dd681): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PMS     (  941): runPSCheck
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): processMsg: DeviceActiveState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/UsageStatsService(  941): User[0] Flushing usage stats to disk
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(3015d326): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{213f09bf: PendingIntentRecord{2589888c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1015215, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{1504ab67: PendingIntentRecord{17e08d14 android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1272953, Int=0
D/HtcSystemUPManager(  941): UPAlarmListener onAlarmArrival
D/HtcSystemUPManager(  941): UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1448881817745, last = 1448860217738, freq = 21600000
,D/HtcSystemUPManager(  941): AlarmScheduler_INEXACT [onReceive] end
D/HtcSystemUPManager(  941): com.htc.upm.AlarmScheduler$SchedulerBase$1@1890fcc0
,D/PMS     (  941): releaseWL(3015d326): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/HtcSystemUPManager(  941): HtcSystemUPHandler sendService() has been called,
,D/HtcSystemUPManager(  941): HtcSystemUPDataStore [sendToService] No data needs to be sent to service
D/HtcSystemUPManager(  941): HtcSystemUPHandler send to UPService takes: 2 ms
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(71059bd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(71059bd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PMS     (  941): runPSCheck
D/WifiController(  941): handleMessage: E msg.what=155652
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1888): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1888): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1888): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1888): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1888): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1888): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1888): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 6988): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6988): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6988): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6988): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 6988): Ignoring header User-Agent because its value was null.
,D/libc    ( 6988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6988): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6988): [NET] android_getaddrinfofornet-, pass to proxy
,I/RemoteViews( 1223): reapply : com.google.android.gms 4 40
D/libc    ( 6988): [NET] android_getaddrinfo_proxy+
D/libc    ( 6988): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6988): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(3df93c57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(3df93c57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  941): battery changed pluggedType: 2
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
,D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PMS     (  941): runPSCheck
D/WifiController(  941): handleMessage: E msg.what=155652
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(15cb6344): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/PMS     (  941): releaseWL(15cb6344): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  941): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  941): plugged=true pluggin=true
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): >> updateStatus
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(a702c2d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(a702c2d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  941): updateBatteryInfo
D/NotificationService(  941): plugged=true pluggin=true
,D/PMS     (  941): runPSCheck
D/HtcPowerSaver(  941): Checking...
I/HtcPowerSaver(  941): >> updateStatus
,D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3101): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 3101): Disconnected process message: 11, size: 0
D/PowerUI ( 1223): closing low battery warning: level=98
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderNotification, total:1
I/HtcPowerSaver(  941): updateStatus (8000,98,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/HtcPowerSaver(  941): << updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
,D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: X
W/ContextImpl( 7128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5922): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5922): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5922): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5922): Cust_ConnectToPC   : spcsc>false
D/        ( 5922): Cust_ConnectToPC   : IPT>true
D/        ( 5922): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5922): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5922): Index of the first 1 = -1
,W/ContextImpl( 5922): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5922): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5922): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5922): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5922): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1223): status:2 level:98 unsupport:false plugged:true
,D/SmartNS_Utility( 5922): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 5922): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/PMS     (  941): acquireWL(24eb46f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null,
,I/BatteryService(  941): n_update end
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): releaseWL(24eb46f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/NotificationService(  941): plugged=true pluggin=true
D/WifiController(  941): handleMessage: E msg.what=155652
D/PMS     (  941): runPSCheck
D/WifiController(  941): processMsg: DeviceActiveState
D/HtcPowerSaver(  941): Checking...
D/WifiController(  941): processMsg: StaEnabledState
I/HtcPowerSaver(  941): >> updateStatus
,D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): battery changed pluggedType: 2
D/WifiController(  941): handleMessage: X
D/PowerUI ( 1223): closing low battery warning: level=98
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  941): updateStatus (8000,98,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/HtcPowerSaver(  941): << updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/BatteryController( 1223): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(3abd6fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
,D/PMS     (  941): releaseWL(3abd6fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  941): updateBatteryInfo
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
,D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/PMS     (  941): runPSCheck
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): onReceive BATTERY_CHANGED
,D/PowerUI ( 1223): closing low battery warning: level=98
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  941): battery changed pluggedType: 2
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: E msg.what=155652
I/HtcPowerSaver(  941): updateStatus (8000,98,-1,false,false,false,-1)
D/WifiController(  941): processMsg: DeviceActiveState
I/HtcPowerSaver(  941): << updateStatus
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1223): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1888): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1888): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1888): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1888): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1888): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1888): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1888): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6988): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6988): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6988): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6988): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6988): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6988): Ignoring header User-Agent because its value was null.
,D/libc    ( 6988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6988): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6988): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6988): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6988): [NET] android_getaddrinfo_proxy+
D/libc    ( 6988): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
,I/RemoteViews( 1223): reapply : com.google.android.gms 2 40
D/libc    ( 6988): [NET] android_getaddrinfo_proxy-, NODATA
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(144b3b12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
I/BatteryService(  941): n_update end
,D/PMS     (  941): releaseWL(144b3b12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  941): plugged=true pluggin=true
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  941): updateBatteryInfo
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/PMS     (  941): runPSCheck
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  941): Checking...
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  941): >> updateStatus
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/WifiController(  941): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=99
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/WifiController(  941): handleMessage: E msg.what=155652
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  941): handleMessage: X
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  941): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  941): << updateStatus
,I/BatteryController( 1223): status:2 level:99 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6692): 
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(2da424e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 941 1000 WorkSource{1000}
,V/AlarmManager(  941): sending alarm PendingIntent{213f09bf: PendingIntentRecord{2589888c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1315215, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{17602399: PendingIntentRecord{201df65e com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1840993, Int=0
I/bt-btm  ( 3101): Received oneshot timer event complete
I/bt-btm  ( 3101): btm_ble_timeout
I/bt-btm  ( 3101): btm_gen_resolvable_private_addr
,D/PMS     (  941): acquireWL(3886ba3f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3101 1002 null
,I/ProcessStatsService(  941): Prepared write state in 8ms
,D/bt-btm  ( 3101): btm_ble_rand_enc_complete
I/bt-btm  ( 3101): btm_gen_resolve_paddr_low
D/bt-smp  ( 3101): smp_encrypt_data
,W/bt-smp  ( 3101): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3101): Plain text(LSB ~ MSB) = 14 24 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3101): Encrypted text(LSB ~ MSB) = 7d 35 73 96 e1 64 ee f9 27 31 54 99 4b 09 88 56 
I/bt-btm  ( 3101): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3101): Stopping oneshot timer
D/bt-btm  ( 3101): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  941): releaseWL(2da424e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/ProcessStatsService(  941): Pruning old procstats: /data/system/procstats/state-2015-11-29-12-33-14.bin
,D/PMS     (  941): releaseWL(3886ba3f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(29d6af0c): PARTIAL_WAKE_LOCK  *alarm* 0x1 941 1000 WorkSource{1000}
V/AlarmManager(  941): sending alarm PendingIntent{1613cb56: PendingIntentRecord{8e5f7d7 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1686097, Int=0
,V/AlarmManager(  941): sending alarm PendingIntent{3417f678: PendingIntentRecord{141cb151 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1824926, Int=1800000
V/AlarmManager(  941): sending alarm PendingIntent{213f09bf: PendingIntentRecord{2589888c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1855215, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{29066055: PendingIntentRecord{3fcf1a6a com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1852900, Int=0
V/AlarmManager(  941): sending alarm PendingIntent{1d36bb5b: PendingIntentRecord{39f14391 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448882411169, Int=0
D/PMS     (  941): acquireWL(20c5aff8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 941 1000 null
,D/WeatherUtility( 1223): Weather sync is On,
D/PMS     (  941): releaseWL(20c5aff8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
V/NetworkPolicy(  941): updateNetworkEnabledLocked()
V/NetworkPolicy(  941): updateNotificationsLocked()
,W/ContextImpl( 7128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  941): releaseWL(29d6af0c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 7128): MY_DEBUG = false,
,D/PowerUsageService( 7128): repeat time = 1448883311245
D/LocationManagerService(  941): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 7128): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 7128): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 7128): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 7128): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 7128): calcPower(), no data,
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,D/PMS     (  941): acquireWL(e615e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 941 1000 null
,I/BatteryService(  941): n_update end
D/PMS     (  941): releaseWL(e615e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  941): updateBatteryInfo
D/PMS     (  941): runPSCheck
D/HtcPowerSaver(  941): Checking...
I/HtcPowerSaver(  941): >> updateStatus
I/HtcPowerSaver(  941): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  941): << updateStatus
D/DotMatrix( 1309): [EventService] reorderNotification, total:0
D/NotificationService(  941): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  941): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 3101): Disconnected process message: 10, size: 0
D/UsbnetService(  941): BroadcastReceiver::onReceive+
D/UsbnetService(  941): onReceive BATTERY_CHANGED
D/UsbnetService(  941):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
W/ContextImpl( 7128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
D/UsbnetService(  941): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetPhoneState( 3101): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/WifiController(  941): handleMessage: E msg.what=155652
D/HeadsetStateMachine( 3101): Disconnected process message: 11, size: 0
D/WifiController(  941): processMsg: DeviceActiveState
D/WifiController(  941): processMsg: StaEnabledState
D/WifiController(  941): processMsg: DefaultState
D/WifiController(  941): handleMessage: X
,D/TetherSettings( 5922): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5922): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5922): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5922): Cust_ConnectToPC   : spcsc>false
D/        ( 5922): Cust_ConnectToPC   : IPT>true
D/        ( 5922): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5922): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5922): Index of the first 1 = -1
W/ContextImpl( 5922): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 ,
,W/Settings( 5922): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5922): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5922): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5922): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,I/jxcore-log( 6692): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6692): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 7174): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7174): ====startRecUseTime====
D/htc.customization.log.level( 7174):  is 
W/CustomizationLogLevel( 7174): Level value is invalid, use default level 2
D/CustomizationManager( 7174):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 7174): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7174): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7174): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7174): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7174): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7174): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7174): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7174): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7174): Parsing tag category name = system
I/CustomizationCIDLoader( 7174): Parsing tag category name = application
I/CustomizationCIDLoader( 7174): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7174): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7174): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7174): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7174): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7174): add string-array item, value = 42507
I/CustomizationCIDLoader( 7174): add string-array item, value = 21902
I/CustomizationCIDLoader( 7174): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7174): add string-array item, value = 23420
I/CustomizationCIDLoader( 7174): add string-array item, value = 22299
I/CustomizationCIDLoader( 7174): add string-array item, value = 24002
I/CustomizationCIDLoader( 7174): add string-array item, value = 23210
I/CustomizationCIDLoader( 7174): add string-array item, value = 23205
I/CustomizationCIDLoader( 7174): add string-array item, value = 23806
I/CustomizationCIDLoader( 7174): add string-array item, value = 23430
I/CustomizationCIDLoader( 7174): add string-array item, value = 23408
I/CustomizationCIDLoader( 7174): add string-array item, value = 27205
I/CustomizationCIDLoader( 7174): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7174): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7174):  Read CID file spent 0.106 (s)
D/CustomizationManager( 7174):  All configurations done spent 0.107 (s)
D/PackageManager(  941): deletePackageAsUser: pkg=com.test.thalitest, pid=7174, uid=2000 userid=0
I/ActivityManager(  941): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  941): killProcessQuiet, pid=6692
I/ActivityManager(  941): Killing 6692:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  941): Skipping PackageSetting{ebba02d com.example.hello/10373} due to missing metadata
I/ActivityManager(  941): Recipient 6692
I/WindowState(  941): WIN DEATH: Window{1eef9e22 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  941): Client connection lost with reason: 4
E/InputEventReceiver( 1383): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{148d7a6e uid 10366 pid 6692} (c)'
D/Process (  941): killProcessQuiet, pid=6465
I/ActivityManager(  941): Killing 6465:com.google.android.talk/u0a112 (adj 13): empty for 1803s
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  941): Recipient 6465
D/Process (  941): killProcessQuiet, pid=6886
I/ActivityManager(  941): Killing 6886:com.android.chrome/u0a96 (adj 15): empty for 1803s
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  941): Recipient 6886
D/Process (  941): killProcessQuiet, pid=6828
I/ActivityManager(  941): Killing 6828:com.google.android.apps.magazines/u0a161 (adj 15): empty for 1804s
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  941): Recipient 6828
I/ActivityManager(  941):   Force finishing activity ActivityRecord{178132f u0 com.test.thalitest/.MainActivity t10}
I/ActivityManager(  941): Killing 6786:com.google.android.music:main/u0a159 (adj 13): empty for 1800s
D/Process (  941): killProcessQuiet, pid=6786
D/Process (  941): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  941): Recipient 6786
D/MediaRouterService(  941): Client com.google.android.music (pid 6786): Died!
W/ActivityManager(  941): Spurious death for ProcessRecord{2f36dd4 6692:com.test.thalitest/u0a366}, curProc for 6692: null
I/ActivityManager(  941): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
W/BroadcastQueue(  941): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  941): android.os.RemoteException: app.thread must not be null
W/BroadcastQueue(  941): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:467)
W/BroadcastQueue(  941): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:568)
W/BroadcastQueue(  941): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:645)
W/BroadcastQueue(  941): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:152)
W/BroadcastQueue(  941): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  941): 	at android.os.Looper.loop(Looper.java:155)
W/BroadcastQueue(  941): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  941): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/DotMatrix( 1309): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1309): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1725): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  941): Cannot find grip_rejection_width, use default value instead
D/PMS     (  941): acquireWL(224c7ec3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1812 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1812): Ignoring removeGeofence because network location is disabled.
D/PMS     (  941): releaseWL(224c7ec3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1725): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/InputMethodManagerService(  941): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/VoicemailCleanupService( 1696): Cleaning up data for package: com.test.thalitest
I/[PluginManager]RegisterService( 1577): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/art     ( 1498): Explicit concurrent mark sweep GC freed 23206(1360KB) AllocSpace objects, 7(604KB) LOS objects, 34% free, 29MB/45MB, paused 1.883ms total 118.959ms
D/Prism.PackageStateRece_( 1498): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1498): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1498): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1498): Deferring update until onResume
I/ActivityManager(  941): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7194 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Launcher( 1498): waitUntilResume // bindAppsRemoved
D/PhoneApp( 1444): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1577): handle notify Blinkfeed plugin client changed
D/AccTypeManager( 1725): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/ResourcesManager(  941): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/ExternalAccountType( 1725): Unsupported attribute readOnly
I/art     (  941): Explicit concurrent mark sweep GC freed 48398(2MB) AllocSpace objects, 19(1992KB) LOS objects, 33% free, 16MB/25MB, paused 1.748ms total 281.726ms
I/art     (  941): WaitForGcToComplete blocked for 259.476ms for cause Explicit
D/StatusBarManagerService(  941): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
D/StatusBarManagerService(  941): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  941): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  941): hiding MENU key
D/FindExtension( 1498): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1498): Defer allocateBuffers to drawing time
W/ContextImpl( 7194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
W/InputMethodManagerService(  941): Got RemoteException sending setActive(false) notification to pid 6692 uid 10366
D/StatusBarManagerService(  941): swetImeWindowStatus vis=0 backDisposition=0
E/NetworkScheduler.SchedulerReceiver( 1888): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1888): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  941): acquireWL(1f2814b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1888 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  941): releaseWL(1f2814b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
W/PackageManager(  941): Unable to load service info ResolveInfo{11091dce com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  941): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  941): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  941): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  941): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  941): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  941): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  941): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  941): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  941): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  941): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/ChimeraCfgMgr( 4441): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4441): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 4441): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4441): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4441): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4441): Module APK com.google.android.play.games already loaded
I/ActivityManager(  941): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7225 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
I/art     (  941): Explicit concurrent mark sweep GC freed 9877(546KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 3.112ms total 270.038ms
W/asset   (  941): Copying FileAsset 0x55b2b45ac0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/LocationSettingsChecker( 4441): Removing dialog suppression flag for package com.test.thalitest
D/GOOGLEHELP_CompatibleDatabase( 4441): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4441): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4441): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4441): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4441): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4441): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4441): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4441): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4441): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4441): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4441): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4441): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4441): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/JobSchedulerService(  941): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  941): removeObsoleteFile: deleting file=10_task.xml
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/PMS     (  941): acquireWL(1368db66): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4441 10024 null
I/ConfigService( 1888): onCreate
I/ConfigFetchService( 4441): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/PMS     (  941): releaseWL(1368db66): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
W/BaseAppContext( 4441): Using Auth Proxy for data requests.
I/PeopleContactsSync( 4441): CP2 sync disabled
D/PMS     (  941): acquireWL(c24cb9f): PARTIAL_WAKE_LOCK  Icing 0x1 4441 10024 WorkSource{10024 com.google.android.gms}
I/PackageManager(  941):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4441, uid=10024, userID:0
W/BaseAppContext( 4441): Using Auth Proxy for data requests.
I/Icing   ( 4441): doRemovePackageData com.test.thalitest
D/PMS     (  941): releaseWL(c24cb9f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
W/DriveInitializer( 4441): Awaiting to be initialized
W/DriveInitializer( 4441): Background init thread started
D/VoldConnector(  941): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.gms/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
W/ContextImpl( 4441): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
I/GAv4    ( 7225): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7225):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7225):   adb logcat -s GAv4
W/GAv4    ( 7225): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 1888): Explicit concurrent mark sweep GC freed 17981(1042KB) AllocSpace objects, 11(796KB) LOS objects, 49% free, 4MB/8MB, paused 801us total 51.676ms
W/DriveInitializer( 4441): Background init thread ended
W/GAv4    ( 7225): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7225): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 7225): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
E/SQLiteLog( 7225): (3850) statement aborts at 2: [PRAGMA journal_mode=WAL] 
E/SQLiteDBG( 7225): func: executeOneRowQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/DocList.db, handle: 0x55b25e0d20
D/VoldConnector(  941): SND -> {39 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
W/ContextImpl( 7225): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
E/SQLiteLog( 7225): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 7225): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0x55b264b0e0
E/GAv4    ( 7225): Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 7225): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7225): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 7225): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 7225): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0x55b264b0e0
E/GAv4    ( 7225): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
D/PMS     (  941): acquireWL(2e33b2fa): PARTIAL_WAKE_LOCK  AsyncService 0x1 6016 10167 null
E/AbstractDatabaseInstance( 7225): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 7225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7225): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AbstractDatabaseInstance( 7225): 	at android.database.sqlite.SQLiteDatabase.enableWriteAheadLogging(SQLiteDatabase.java:2036)
E/AbstractDatabaseInstance( 7225): 	at aev.getWritableDatabase(PG:20264)
E/AbstractDatabaseInstance( 7225): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7225): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7225): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7225): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 7225): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 7225): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 7225): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 7225): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7225): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7225): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7225): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 7225): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/PMS     (  941): releaseWL(2e33b2fa): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  941): acquireWL(16eee308): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6016 10167 null
E/CAKEMIX_CRASHED( 7225): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/CAKEMIX_CRASHED( 7225): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForString(Native Method)
E/CAKEMIX_CRASHED( 7225): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:669)
E/CAKEMIX_CRASHED( 7225): 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:351)
E/CAKEMIX_CRASHED( 7225): 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:319)
E/CAKEMIX_CRASHED( 7225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:241)
E/CAKEMIX_CRASHED( 7225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 7225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7225): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/CAKEMIX_CRASHED( 7225): 	at android.database.sqlite.SQLiteDatabase.enableWriteAheadLogging(SQLiteDatabase.java:2036)
E/CAKEMIX_CRASHED( 7225): 	at aev.getWritableDatabase(PG:20264)
E/CAKEMIX_CRASHED( 7225): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7225): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7225): 	at aen.run(PG:536)
W/ResourcesManager( 7225): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7225): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  941): releaseWL(16eee308): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
I/UpdateIcingCorporaServi( 7058): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DeviceManagement( 6953): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/ActivityManager(  941): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 7225 on display 0
I/DeviceManagement( 6953): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
E/SQLiteLog( 7058): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 7058): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55b2638c90
V/JNIHelp ( 7225): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/OpenGLRenderer( 1498): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
D/Process ( 7225): killProcess, pid=7225
I/DeviceManagement( 6953): WorkflowService: Starting workflow service
I/DeviceManagement( 6953): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@d7f3dd0] args=[Bundle[mParcelledData.dataSize=112]]
I/DeviceManagement( 6953): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 6953): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 6953): PackageUpdateWorkflow: ==================================================
D/Process ( 7225): vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 6953): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/ActivityManager(  941): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7287 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
I/DeviceManagement( 6953): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 6953): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 6953): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0x55b263d6a0
I/ActivityManager(  941): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=7300 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
W/DeviceManagement( 6953): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@d7f3dd0]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 6953): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 6953): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 6953): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 6953): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 6953): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 6953): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 6953): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 6953): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 6953): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 6953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 6953): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 6953): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 6953): WorkflowService: Stopping workflow service
E/SharedPreferencesImpl( 7058): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 7058): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 7058): Process: com.google.android.googlequicksearchbox:search, PID: 7058
E/AndroidRuntime( 7058): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7058): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 7058): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 7058): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 7058): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 7058): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 7058): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 7058): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 7058): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 7058): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 7058): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 7058): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 7058): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 7058): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 7058): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 7058): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 7058): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 7058): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7058): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7058): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7058): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  941): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 7058): killProcess, pid=7058
I/art     (  451): Explicit concurrent mark sweep GC freed 8671(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 190us total 21.904ms
D/Process ( 7058): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  941): Can't write: system_app_crash
E/DropBoxManagerService(  941): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  941): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  941): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  941): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  941): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  941): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  941): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  941): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  941): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  941): 	... 5 more
I/art     (  451): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 159us total 17.110ms
I/ActivityManager(  941): Recipient 7225
I/ActivityManager(  941): Process com.google.android.apps.docs (pid 7225) has died
W/HtcSystemUPManager(  941): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/art     (  451): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 131us total 18.012ms
I/ActivityManager(  941): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=7332 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
E/lowmemorykiller(  383): Error writing /proc/7058/oom_score_adj; errno=22
E/SQLiteDatabase( 7287): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7287): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7287): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7287): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7287): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7287): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 7287): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 7287): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 7287): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 7287): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 7287): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 7287): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 7287): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 7287): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7287): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7287): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7287): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7287): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7287): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7287): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7287): FATAL EXCEPTION: main
E/AndroidRuntime( 7287): Process: com.android.documentsui, PID: 7287
E/AndroidRuntime( 7287): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7287): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 7287): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 7287): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 7287): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7287): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7287): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7287): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7287): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7287): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7287): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7287): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7287): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7287): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7287): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7287): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 7287): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 7287): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 7287): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 7287): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 7287): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 7287): 	... 9 more
I/ActivityManager(  941): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=7354 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
E/lowmemorykiller(  383): Error writing /proc/7058/oom_score_adj; errno=22
E/ActivityManager(  941): App crashed! Process: com.android.documentsui
D/ErrorReport(  941): HtcErrorReportManager Begin---add error logs to dropbox
W/System.err(  941): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  941): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  941): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  941): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  941): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  941): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  941): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  941): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  941): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  941): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  941): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  941): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  941): 	at libcore.io.Posix.open(Native Method)
W/System.err(  941): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  941): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  941): 	... 12 more
W/System.err(  941): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  941): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  941): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  941): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  941): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  941): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  941): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  941): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  941): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  941): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  941): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  941): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  941): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  941): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  941): 	at libcore.io.Posix.open(Native Method)
W/System.err(  941): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  941): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  941): 	... 14 more
I/ActivityManager(  941): Recipient 7058
I/ActivityManager(  941): Process com.google.android.googlequicksearchbox:search (pid 7058) has died
W/ActivityManager(  941): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
W/System.err(  941): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  941): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  941): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  941): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  941): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  941): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)

```
