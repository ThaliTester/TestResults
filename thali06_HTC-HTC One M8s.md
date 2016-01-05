#### Test 549702617d40def_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Process (  967): killProcessQuiet, pid=5511
--------- beginning of system
I/ActivityManager(  967): Killing 5511:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  967): Recipient 5511
,E/cutils-trace( 6468): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6468): ====startRecUseTime====
D/htc.customization.log.level( 6468):  is 
W/CustomizationLogLevel( 6468): Level value is invalid, use default level 2
D/CustomizationManager( 6468):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6468): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6468): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6468): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6468): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6468): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6468): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6468): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6468): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6468): Parsing tag category name = system
I/CustomizationCIDLoader( 6468): Parsing tag category name = application
I/CustomizationCIDLoader( 6468): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6468): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6468): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6468): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6468): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6468): add string-array item, value = 42507
I/CustomizationCIDLoader( 6468): add string-array item, value = 21902
I/CustomizationCIDLoader( 6468): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6468): add string-array item, value = 23420
I/CustomizationCIDLoader( 6468): add string-array item, value = 22299
I/CustomizationCIDLoader( 6468): add string-array item, value = 24002
I/CustomizationCIDLoader( 6468): add string-array item, value = 23210
I/CustomizationCIDLoader( 6468): add string-array item, value = 23205
I/CustomizationCIDLoader( 6468): add string-array item, value = 23806
I/CustomizationCIDLoader( 6468): add string-array item, value = 23430
I/CustomizationCIDLoader( 6468): add string-array item, value = 23408
I/CustomizationCIDLoader( 6468): add string-array item, value = 27205
I/CustomizationCIDLoader( 6468): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6468): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6468):  Read CID file spent 0.104 (s)
D/CustomizationManager( 6468):  All configurations done spent 0.104 (s)
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6468 on display 0
D/PMS     (  967): acquireHCC(21886d8a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 967 1000 null
D/PMS     (  967): acquireHCC(1b32dffb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 967 1000 null
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6486 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  967): Display changed displayId=0
D/DotMatrix( 1307): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1307): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1487): [trimMemory] 20
W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2
I/WebViewFactory( 6486): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6486): Time to load native libraries: 11 ms (timestamps 9487-9498)
,I/LibraryLoader( 6486): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6486): Binding Chromium to main looper Looper (main, tid 1) {3acd4520}
,I/LibraryLoader( 6486): Expected native library version number "",actual native library version number ""
,I/chromium( 6486): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6486): Initializing chromium process, singleProcess=true
,W/art     ( 6486): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6486): ApplicationContext is null in ApplicationStatus
,W/chromium( 6486): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6486): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6486): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6486): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6486): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6486): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6486): Local Branch: 
I/Adreno-EGL( 6486): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6486): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6486):                  d74aa161a12b9c6fc6332151
,W/System.err(  967): java.lang.Throwable: stack dump
D/BluetoothManagerService(  967): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f69b3cf:true
W/System.err(  967): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  967): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  967): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6486): 840012620: getState(). Returning 12
,I/art     (  967): Explicit concurrent mark sweep GC freed 45192(2MB) AllocSpace objects, 6(944KB) LOS objects, 33% free, 16MB/25MB, paused 1.494ms total 137.146ms
,W/ActivityManager(  967): Activity pause timeout for ActivityRecord{c0a0818 u0 com.test.thalitest/.MainActivity t8},
W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/art     ( 6486): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6486): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6486): CordovaWebView is running on device made by: HTC
,W/art     ( 6486): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6486): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6486): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  967): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
D/StatusBarManagerService(  967): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
,D/FindExtension( 6486): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6486): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3df5205a, mServedView=org.apache.cordova.engine.SystemWebView{30d6628b VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1fd07f68
,I/InputMethodManagerService(  967): Disable input method client, pid=1487
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6486): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +784ms (total +829ms)
,W/BindingManager( 6486): Cannot call determinedVisibility() - never saw a connection for the pid: 6486,
,D/JsMessageQueue( 6486): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6486): JniHelper::setJavaVM(0xab2598f8), pthread_self() = -1403515696
,D/JX-Cordova( 6486): jxcore cordova android initializing
,W/jxcore-log( 6486): Initializing JXcore engine
W/jxcore-log( 6486): JXcore engine is ready
,W/jxcore-log( 6486): Starting JXcore engine
,D/PMS     (  967): releaseHCC(21886d8a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  967): releaseHCC(1b32dffb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6486): Platform android,
W/jxcore-log( 6486): 
W/jxcore-log( 6486): Process ARCH arm
W/jxcore-log( 6486): 
,I/jxcore-log( 6486): JXcore Cordova bridge is ready!,
I/jxcore-log( 6486): 
W/jxcore-log( 6486): JXcore engine is started
,I/Choreographer( 6486): Skipped 97 frames!  The application may be doing too much work on its main thread.
I/chromium( 6486): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6486): Toggling radios to true,
I/jxcore-log( 6486): 
,D/BluetoothAdapter( 6486): enable(): BT is already enabled..!
,D/WifiService(  967): New client listening to asynchronous messages
E/WifiTrafficPoller(  967): ADD_CLIENT: 8
,D/WifiManager( 6486): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  967): setWifiEnabled: true pid=6486, uid=10366,
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  967): isSprintWifiRestricted(): false
I/WifiService(  967): isMdmWifiRestricted(): false
W/Settings:Agent(  967): MONITOR_LOG
,W/Settings:Agent(  967): name: wifi_on
W/Settings:Agent(  967): value: 2
W/Settings:Agent(  967): >> traceCallingStack()
W/Settings:Agent(  967): Process.myPid(): 967
W/Settings:Agent(  967): Process.myTid(): 1512
W/Settings:Agent(  967): Process.myUid(): 1000
,W/Settings:Agent(  967): 
W/Settings:Agent(  967): 
W/System.err(  967): java.lang.Throwable: stack dump
,W/System.err(  967): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  967): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  967): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,W/System.err(  967): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  967): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  967): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  967): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
,W/System.err(  967): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  967): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  967): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  967): 	,at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  967): 
W/Settings:Agent(  967): << traceCallingStack(): 12(ms)
D/WifiController(  967): handleMessage: E msg.what=155656
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): handleMessage: X
,D/WifiManager( 6486): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiManager( 6486): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1385): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1385): wlan0: Cancelling scan request
,D/wpa_supplicant( 1385): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1385): TDLS: Tear down peers
D/wpa_supplicant( 1385): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6486): Radios toggled
I/jxcore-log( 6486): 
,D/wpa_supplicant( 1385): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1385): wlan0: Deauthentication notification
D/wpa_supplicant( 1385): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1385): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1385): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1385): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1385): enter disconnect check
I/wpa_supplicant( 1385): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1385): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1385): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  967): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  967): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,E/WifiMonitor(  967): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  967): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  967): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  967): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  967): sendTetherStateChangedBroadcast 0, 0, 0
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  967): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  967): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  967): acquireWL(3a2b7278): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1385): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1385): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1385): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1385): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1385): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55bd34df88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1385):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1385): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1385): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1385): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1385): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1385): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1385): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1385): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1385): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1385): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1385): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1385): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1385): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1385): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1385): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1385): EAPOL: External notification - portValid=0
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1385): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1385): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1385): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1385): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1385): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: ConnectedState
E/WifiStateMachine(  967): WifiStateMachine: Leaving Connected state
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiPerfLock(  967): release()
E/WifiStateMachine(  967): PerfLock released for exiting ConnectedState
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  967): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
E/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  967): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  967): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  967): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1385): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1385): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1385): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1385): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1385): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1385): Power_Mode_Type mode = 0
I/wpa_supplicant( 1385): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1385): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1385): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDataStallTracker(  967): setDhcpActive: false
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1898): Read error: ssl=0x558e32a5e0: I/O error during system call, Connection timed out
,D/PMS     (  967): acquireWL(2307d51): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
,V/NativeCrypto( 1898): SSL shutdown failed: ssl=0x558e32a5e0: I/O error during system call, Broken pipe
,E/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  967): setDetailed state send new extra info<unknown ssid>
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/TetherSettings( 5799): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5799): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5799): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5799): Cust_ConnectToPC   : spcsc>false
D/        ( 5799): Cust_ConnectToPC   : IPT>true
D/        ( 5799): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  967): NetworkAgent != null
,D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/ConnectivityService(  967): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Forcing reevaluation
D/PMS     (  967): releaseWL(3a2b7278): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
W/Settings( 5799): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  967): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  967): stopDataStallAlarm 
,E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL false Token 3
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
,V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateNotificationsLocked()
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  967): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1385): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1385): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 1385): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1385): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  967): invokeEnterMethods: DisconnectingState
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  967):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  967): Start Disconnecting Watchdog 1
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131146
E/WifiStateMachine(  967): processMsg: DisconnectingState
,E/WifiStateMachine(  967):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1385): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1385): Fast associate: Old scan results
D/wpa_supplicant( 1385): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1385): wpa_supplicant_scan enter
D/wpa_supplicant( 1385): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1385): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1385): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1385): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1385): WPS:  * Request Type
D/wpa_supplicant( 1385): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1385): WPS:  * UUID-E
D/wpa_supplicant( 1385): WPS:  * Primary Device Type
D/wpa_supplicant( 1385): WPS:  * RF Bands (3)
D/wpa_supplicant( 1385): WPS:  * Association State
D/wpa_supplicant( 1385): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1385): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1385): WPS:  * Manufacturer
D/wpa_supplicant( 1385): WPS:  * Model Name
D/wpa_supplicant( 1385): WPS:  * Model Number
D/wpa_supplicant( 1385): WPS:  * Device Name
D/wpa_supplicant( 1385): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1385): P2P: * P2P IE header
D/wpa_supplicant( 1385): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1385): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1385): wlan0: Add radio work 'scan'@0x55bd330860
E/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 1385): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/wpa_supplicant( 1385): wlan0: Starting radio work 'scan'@0x55bd330860 after 0.000056 second wait
E/WifiStateMachine(  967): processMsg: DisconnectingState
D/wpa_supplicant( 1385): wlan0: nl80211: scan request
D/wpa_supplicant( 1385): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1385): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1385): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1385): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1385): wlan0: Own scan request started a scan in 0.000112 seconds
I/wpa_supplicant( 1385): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSID
E/WifiStateMachine(  967):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132072
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132072
E/WifiStateMachine(  967): ConnectModeState: Network connection lost 
E/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
,E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  967): DisconnectedState call setCountryCode()
E/WifiStateMachine(  967):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/SmartNS_Utility( 5799): hasRemovableStorageSlot: true
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/SmartNS_Utility( 5799): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
E/WifiMonitor(  967): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  967): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/SmartNS_NSReceiver( 5799): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1385): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1385): wlan0: Cancelling scan request
D/wpa_supplicant( 1385): wlan0: nl80211: sched_scan request
D/PMS     (  967): releaseWL(2307d51): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5799): setISNotification
,D/SmartNS_Utility( 5799): usb_cable_connect = 1
D/SmartNS_Utility( 5799): usb_denied = 0
,I/SmartNS_PSService( 5799): usb notificaiton:true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
I/ActionCombine( 5799): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/SmartNS_Utility( 5799): usb_cable_connect = 1
,D/SmartNS_Utility( 5799): usb_denied = 0
I/SmartNS_PSService( 5799): usb notificaiton:true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5799): Tethered state change:false isNSOpening:false
,D/wpa_supplicant( 1385): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec,
D/wpa_supplicant( 1385): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1385): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1385): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1385): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1385): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1385): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1385): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1385): wlan0: Scan completed in 0.035698 seconds
D/wpa_supplicant( 1385): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1385): wlan0: BSS: Start scan result update 7
D/WifiP2pService(  967): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1385): BSS: last_scan_res_used=0/32
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1385): wlan0: New scan results available (own=1 ext=0)
D/WifiP2pService(  967): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1385): wlan0: Radio work 'scan'@0x55bd330860 done in 0.036479 seconds
D/wpa_supplicant( 1385): wlan0: No suitable network found
D/wpa_supplicant( 1385): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1385): wlan0: Cancelling sched scan
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131101
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/wpa_supplicant( 1385): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1385): wlan0: Cancelling scan request
,D/wpa_supplicant( 1385): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1385): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1385): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1385): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1385): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1385): p2p0: No suitable network found
D/wpa_supplicant( 1385): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1385): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1385): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  967):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
,E/WifiStateMachine(  967):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  967): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132109  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiMonitor(  967): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=42 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor(  967): WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS ,
E/WifiMonitor(  967): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/DotMatrix( 1307): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132110  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
D/WifiNetworkAgent(  967): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=132119  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=132123  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147461
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:87 bcn=0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:87 bcn=0
E/WifiStateMachine(  967): processMsg: DriverStartedState
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:87 bcn=0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:87 bcn=0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1385): wlan0: Control interface command 'LIST_DONGLES'
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  967): [1,451,956,900,177 ms] noteScanEnd no scan source
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,D/wpa_supplicant( 1385): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
E/WifiStateMachine(  967): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@147ee791 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  967): NG7005g c0:ff:d4:d3:aa:4a rssi=-49 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiAutoJoinController (  967): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  967): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  967): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  967):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
,E/WifiAutoJoinController (  967): UPC243894600 a0:c5:62:7a:49:96 rssi=-84 cap [WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiAutoJoinController (  967): UPC503894600 a0:c5:62:7a:49:97 rssi=-78 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiAutoJoinController (  967): UPC5999698 64:7c:34:12:7f:81 rssi=-91 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiAutoJoinController (  967): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-92 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiAutoJoinController (  967): Gonzos 38:f8:89:11:e9:11 rssi=-89 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  967): ageScanResultsOut delay 40000 size 7 now 1451956900182
E/WifiAutoJoinController (  967): newSupplicantResults size=7 known=1 true
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1385): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  967): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  967): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  967): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  967): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  967): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  967): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-58,-127) num=(1,0)
E/WifiAutoJoinController (  967): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  967): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  967): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  967): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  967): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-58 freq=2412
D/HtcWifiControlRoamOffload: (  967): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  967): Done attemptAutoJoin status=3
,E/WifiConfigStore(  967):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131215
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-58 ;0 ,-127] any roam=0 rt=132135
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-58 ;0 ,-127] any roam=0 rt=132135
E/WifiStateMachine(  967): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  967): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  967): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
,D/WISPrService( 5799): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiService(  967): New client listening to asynchronous messages,
E/WifiTrafficPoller(  967): ADD_CLIENT: 9
,D/ConnectivityService(  967): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat(  967): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  967): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
D/ConnectivityService(  967): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkManagementService(  967): Removing idletimer
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Disconnected - quitting
I/SecurityController( 1221): onLost 100
,D/usbnet  (  967): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/PMS     (  967): acquireWL(146436b7): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 967 1000 null
D/CSLegacyTypeTracker(  967): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,E/ConnectivityService(  967): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,E/ConnectivityService(  967): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/Tethering(  967): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
V/NetworkPolicy(  967): ensureActiveMobilePolicyLocked()
D/PMS     (  967): acquireWL(3fe13e24): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null,
,D/Tethering(  967): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/WifiConfigStore(  967): Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/NetworkPolicy(  967): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  967): updateIfacesLocked()
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
V/NetworkPolicy(  967): updateNotificationsLocked()
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/PMS     (  967): releaseWL(3fe13e24): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/DATA_ICON( 1221): dataConnected: false/false
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='group'
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
V/NetworkPolicy(  967): updateNotificationsLocked()
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1385): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  967): will read network variables netId=0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplica,nt( 1385): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1385): Do not allow key_data field to be exposed
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='eap'
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='password'
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  967): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  967):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  967): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1385): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1385): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1385): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1385): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  967): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1385): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1385): ENABLE_NETWORK (0)
D/wpa_supplicant( 1385): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1385): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1385): wpa_supplicant_scan enter
D/wpa_supplicant( 1385): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1385): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1385): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1385): WPS:  * Request Type
D/wpa_supplicant( 1385): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1385): WPS:  * UUID-E
D/wpa_supplicant( 1385): WPS:  * Primary Device Type
D/wpa_supplicant( 1385): WPS:  * RF Bands (3)
D/wpa_supplicant( 1385): WPS:  * Association State
D/wpa_supplicant( 1385): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1385): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1385): WPS:  * Manufacturer
D/wpa_supplicant( 1385): WPS:  * Model Name
D/wpa_supplicant( 1385): WPS:  * Model Number
D/wpa_supplicant( 1385): WPS:  * Device Name
D/wpa_supplicant( 1385): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1385): P2P: * P2P IE header
D/wpa_supplicant( 1385): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1385): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1385): wlan0: Add radio work 'scan'@0x55bd330860
D/wpa_supplicant( 1385): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1385): wlan0: Starting radio work 'scan'@0x55bd330860 after 0.000032 second wait
D/wpa_supplicant( 1385): wlan0: nl80211: scan request
D/wpa_supplicant( 1385): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1385): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1385): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1385): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1385): wlan0: Own scan request started a scan in 0.000068 seconds
I/wpa_supplicant( 1385): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  967): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  967): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1385): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1385): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1385): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  967): will read network variables netId=0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1385): Do not allow key_data field to be exposed
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1385): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1385): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  967): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  967):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1385): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1385): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1385): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1385): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1385): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1385): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1385): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1385): wpa_supplicant_scan enter
D/wpa_supplicant( 1385): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1385): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1385): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  967): setLastSelectedConfiguration -1
E/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1385): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  967): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  967): DisconnectedState call setCountryCode()
E/WifiStateMachine(  967):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1385): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1385): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1385): wlan0: Cancelling scan request
D/wpa_supplicant( 1385): wlan0: nl80211: sched_scan request
D/FlexNetS( 6353): updateSvcAllowedInSettings:false
I/ActivityManager(  967): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6549 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/FlexNetS( 6353): updateSvcAllowedInSettings:false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/wpa_supplicant( 1385): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1385): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0,
D/wpa_supplicant( 1385): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1385): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1385): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1385): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1385): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1385): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1385): wlan0: Scan completed in 0.040421 seconds
D/wpa_supplicant( 1385): nl80211: Received scan results (0 BSSes)
E/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 1385): wlan0: BSS: Start scan result update 8
D/WifiP2pService(  967): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1385): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  967): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiP2pService(  967): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1385): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/wpa_supplicant( 1385): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to no match in scan
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1385): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to no match in scan
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
E/WifiStateMachine(  967): enter WifiNetworkFactory startNetwork. mIPTStart:false
E/WifiStateMachine(  967): handleMessage: E msg.what=131131
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/wpa_supplicant( 1385): wlan0: BSS: Remove id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to no match in scan
D/wpa_supplicant( 1385): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to no match in scan
D/wpa_supplicant( 1385): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to no match in scan
D/wpa_supplicant( 1385): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1385): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1385): wlan0: Radio work 'scan'@0x55bd330860 done in 0.041471 seconds
D/wpa_supplicant( 1385): wlan0: No suitable network found
D/wpa_supplicant( 1385): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1385): wlan0: Cancelling sched scan
E/WifiStateMachine(  967):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/wpa_supplicant( 1385): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1385): wlan0: Cancelling scan request
D/wpa_supplicant( 1385): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1385): nl80211: Received scan results (0 BSSes)
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 1385): p2p0: BSS: Start scan result update 2
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1385): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1385): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1385): p2p0: No suitable network found
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
E/WifiStateMachine(  967):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/wpa_supplicant( 1385): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
D/wpa_supplicant( 1385): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1385): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:96]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:96
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81
E/WifiStateMachine(  967): handleMessage: X
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  967): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  967): handleMessage: E msg.what=147461
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiMonitor(  967): WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  967): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  967):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:87 bcn=0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:87 bcn=0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:87 bcn=0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 dur:87 bcn=0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1385): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  967): [1,451,956,900,278 ms] noteScanEnd no scan source
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1385): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  967): handleMessage: X
D/FlexNetS( 6353): updateSvcAllowedInSettings:false
W/WISPrService( 5799): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5799): trigger connection
D/WISPrService( 5799): continue
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/FlexNetS( 6353): updateSvcAllowedInSettings:false
D/WISPrService( 5799): start DataConnection
D/WISPrService( 5799): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/libc    ( 5799): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5799): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5799): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/FlexNetS( 6353): updateSvcAllowedInSettings:false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/libc    ( 5799): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5799): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5799): [NET] android_getaddrinfo_proxy+
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/WISPrService( 5799): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5799): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5799): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5799): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5799): >>>>>WISPrService start isConnected = false<<<<<,
,D/FlexNetS( 6353): updateSvcAllowedInSettings:false
D/WISPrService( 5799): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5799): >>>>>WISPrService start isConnected = false<<<<<,
D/WISPrService( 5799): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/FlexNetS( 6353): updateSvcAllowedInSettings:false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/FlexNetS( 6353): updateSvcAllowedInSettings:false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/FlexNetS( 6353): updateSvcAllowedInSettings:false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
D/FlexNetS( 6353): updateSvcAllowedInSettings:false
D/libc    ( 5799): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5799): [NET] android_getaddrinfofornet-, err=8
,D/WISPrService( 5799): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/FlexNetS( 6353): updateSvcAllowedInSettings:false
,D/FlexNetS( 6353): updateSvcAllowedInSettings:false
,D/FlexNetS( 6353): updateSvcAllowedInSettings:false,
,D/MdScPhnSt( 6549): [1b4.2.]  listen tmrbb8,
,D/FlexNetS( 6353): updateSvcAllowedInSettings:false
,D/FlexNetS( 6353): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6417): remove item 101 (p2d27in201) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6549): [1b4.2.] summary 118:p2 ignore,
,D/Process (  967): killProcessQuiet, pid=6197
,I/ActivityManager(  967): Killing 6197:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6197,
,D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,D/PMS     (  967): acquireWL(748589): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
,D/GpsLocationProvider(  967): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  967): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true,
I/AlarmManager(  967): [AlarmQueuing] connectivity wifi: false
,D/htcCheckinService(  967): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  967): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1487): [onReceive] WIFI(1): DISCONNECTED,
,I/ActivityManager(  967): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6581 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  967): No APN found to select.
,D/PMS     (  967): releaseWL(748589): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,D/MdScPhnSt( 6549): [a62.1.]  listen tmrbb8
,D/MdScDataSum( 6549): [a62.1.] summary 118:p1 ignore
,I/MusicStore( 6581): Database version: 120,
,D/VoldConnector(  967): SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6581): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  967): SND -> {29 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6581): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  967): SND -> {30 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6581): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6581): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6581): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6581): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6581): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6581): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@235a0ad4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6581): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6581): GMSCore installation verified
,I/ConfigStore( 6581): Config Database version: 1,
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6581, uid=10159, userID:0,
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
,D/MediaRouterService(  967): Client com.google.android.music (pid 6581): Registered
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
,I/MediaRouter( 6581): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6581): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6581, uid=10159, userID:0,
,D/MobileConnectivityChangeReceiver( 6291): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/AutoSetting( 1568): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6291): onReceive CONNECTIVITY_CHANGE networkType=1
,I/GHttpClientFactory( 6581): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1568): Util - no network available!
,I/GoogleURLConnFactory( 6581): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1568): service - onCreate()
,D/AutoSetting( 1568): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
I/iu.Environment( 4416): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4416): num queued entries: 0
,I/iu.UploadsManager( 4416): num updated entries: 0
,I/iu.SyncManager( 4416): NEXT; no task
,D/LocationManagerService(  967): request 18541452 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1568): service - mHandler: cancel location update
D/AutoSetting( 1568): service -           changes count: 0
,D/ChimeraCfgMgr( 4416): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/Babel   ( 4519): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6623 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  967): Killing 6083:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=6083
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6083,
,D/VoldConnector(  967): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/ContextImpl( 6623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6623): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6623):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6623):   adb logcat -s GAv4
D/VoldConnector(  967): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  967): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
,W/GAv4    ( 6623): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 6623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  967): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/,
,W/ContextImpl( 6623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6623): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6623): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/global  ( 6623): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6623): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6623): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6623): Time to load native libraries: 2 ms (timestamps 6217-6219)
,I/LibraryLoader( 6623): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6623): Binding Chromium to main looper Looper (main, tid 1) {bfa5a47},
,I/LibraryLoader( 6623): Expected native library version number "",actual native library version number "",
I/chromium( 6623): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6623): Initializing chromium process, singleProcess=true,
,W/art     ( 6623): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6623): ApplicationContext is null in ApplicationStatus
,W/chromium( 6623): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6623): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6623): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6623): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6623): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6623): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6623): Local Branch: 
I/Adreno-EGL( 6623): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6623): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6623):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6623): Requires BLUETOOTH permission,
,I/NSApplication( 6623): Starting up...,
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6681 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  967): killProcessQuiet, pid=6248
I/ActivityManager(  967): Killing 6248:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  414): Explicit concurrent mark sweep GC freed 8638(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 373us total 53.454ms
,I/art     (  414): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 132us total 20.451ms
,I/art     (  414): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 132us total 16.384ms
,I/ActivityManager(  967): Recipient 6248
,D/Process (  967): killProcessQuiet, pid=5823,
I/ActivityManager(  967): Killing 5823:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/art     ( 5892): Suspending all threads took: 6.450ms
,I/ActivityManager(  967): Recipient 5823
,E/WifiStateMachine(  967): handleMessage: E msg.what=131168,
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): handleMessage: X
,I/jxcore-log( 6486): Test app app.js loaded
I/jxcore-log( 6486): 
,I/chromium( 6486): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PMS     (  967): acquireWL(32f8a162): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024}
V/AlarmManager(  967): sending alarm PendingIntent{28d4c2f3: PendingIntentRecord{30ef3bb0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=140349, Int=0
,D/PMS     (  967): acquireWL(142c3a29): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(32f8a162): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1898): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1898): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1898): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1898): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1898): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1898): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1898): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  967): releaseWL(142c3a29): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(14ee9b4f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6581 10159 null
,D/WearableService( 4778): callingUid 10024, callindPid: 4778,
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6581, uid=10159, userID:0,
,D/PMS     (  967): releaseWL(14ee9b4f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 6581): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6581): Stop autocaching.
,E/GmsUtils( 6581): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 6581): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  967): acquireWL(3fc5a25e): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024}
V/AlarmManager(  967): sending alarm PendingIntent{1152f63f: PendingIntentRecord{1b143b0c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142736, Int=0
,D/PMS     (  967): releaseWL(3fc5a25e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  967): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  967): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1568): service - handleMessage() stop self,
,D/AutoSetting( 1568): service - onDestroy() END
,D/AutoSetting( 1568): service - handleMessage() quit looper
,D/PMS     (  967): acquireWL(28e2fc55): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(28e2fc55): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  967): updateBatteryInfo
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): runPSCheck
,D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  967): << updateStatus
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1429): switchBindHtcMsgCursor: null,
,D/PMS     (  967): acquireWL(1045866a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
,V/AlarmManager(  967): sending alarm PendingIntent{1d8a6054: PendingIntentRecord{123ccbfd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=151950, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{3c8ab75b: PendingIntentRecord{364ffbf8 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1451956934981, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{18a408d1: PendingIntentRecord{1b2d9f36 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=188566, Int=0
,D/PMS     (  967): acquireWL(12b36e37): PARTIAL_WAKE_LOCK  *backup* 0x1 967 1000 null,
,D/PMS     (  967): acquireWL(1784dfa4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1898 10024 WorkSource{10024 com.google.android.gms}
D/WeatherUtility( 1221): Weather sync is On
W/BackupManagerService(  967): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  967): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  967): releaseWL(1045866a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
D/PMS     (  967): releaseWL(12b36e37): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,I/art     ( 1898): Explicit concurrent mark sweep GC freed 12519(666KB) AllocSpace objects, 7(588KB) LOS objects, 49% free, 4MB/8MB, paused 789us total 49.580ms,
,D/PMS     (  967): releaseWL(1784dfa4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  967): releaseWL(146436b7): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  967): Failed to find a new network - expiring NetTransition Wakelock
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
I/ActivityManager(  967): Killing 5748:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/HtcAppUPService( 1568): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@19aa5c5b
D/Process (  967): killProcessQuiet, pid=5748
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5748
,D/PMS     (  967): acquireWL(7025210): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000},
,V/AlarmManager(  967): sending alarm PendingIntent{395e0109: PendingIntentRecord{274d5f0e android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=211292, Int=0
D/PMS     (  967): releaseWL(7025210): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  967): acquireWL(21bbed2f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(21bbed2f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  967): updateBatteryInfo,
,D/PMS     (  967): runPSCheck
D/HtcPowerSaver(  967): Checking...,
,I/HtcPowerSaver(  967): >> updateStatus
,D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  967): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  967): << updateStatus
,D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): battery changed pluggedType: 2,
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  967): acquireWL(a27f3c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{1d8a6054: PendingIntentRecord{123ccbfd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=211951, Int=0,
,I/art     (  967): Explicit concurrent mark sweep GC freed 39478(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 2.051ms total 238.028ms
,V/AlarmManager(  967): sending alarm PendingIntent{13045e1a: PendingIntentRecord{fa42d4b com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1451957109311, Int=0
,D/PMS     (  967): releaseWL(a27f3c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  967): acquireWL(1b65328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
,I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(1b65328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  967): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  967): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  967): Checking...
,D/UsbnetService(  967): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  967): acquireWL(e7c841): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(e7c841): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  967): updateBatteryInfo
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): Checking...
,D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  967): >> updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  967): handleMessage: E msg.what=155652
I/HtcPowerSaver(  967): << updateStatus
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: StaEnabledState,
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  967): acquireWL(24fa41e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(24fa41e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  967): plugged=true pluggin=true
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo,
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): handleMessage: E msg.what=155652
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): << updateStatus
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  967): acquireWL(1c865327): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(1c865327): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/PMS     (  967): runPSCheck
D/WifiController(  967): handleMessage: E msg.what=155652
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): processMsg: DeviceActiveState
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): << updateStatus
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1429): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1429): mDeleteTask = null, bDeleting = false,
D/AccFlag ( 1429): sku_id=118
,D/ContactMessageStore( 1429): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1429): start background delete task...,
,D/ContactMessageStore( 1429): size: 0 , 0
,D/ContactMessageStore( 1429): Background delete complete
,D/PMS     (  967): acquireWL(9b179d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end,
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  967): releaseWL(9b179d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  967): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  967): plugged=true pluggin=true
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): Checking...
,D/UsbnetService(  967): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  967): processMsg: StaEnabledState
I/HtcPowerSaver(  967): << updateStatus
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  967): acquireWL(1a7a77d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(1a7a77d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  967): updateBatteryInfo
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  967): runPSCheck
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): << updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
,D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  967): acquireWL(11189672): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
,D/PMS     (  967): releaseWL(11189672): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: E msg.what=155652
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): processMsg: DeviceActiveState
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
,D/WifiController(  967): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  967): << updateStatus
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  967): acquireWL(137afac3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{1d8a6054: PendingIntentRecord{123ccbfd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=391950, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{39965f40: PendingIntentRecord{18c3e79 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940984, Int=0
I/bt-btm  ( 3144): Received oneshot timer event complete
I/bt-btm  ( 3144): btm_ble_timeout
I/bt-btm  ( 3144): btm_gen_resolvable_private_addr
,D/PMS     (  967): acquireWL(2e55a7be): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3144 1002 null
,D/bt-btm  ( 3144): btm_ble_rand_enc_complete
I/bt-btm  ( 3144): btm_gen_resolve_paddr_low
D/bt-smp  ( 3144): smp_encrypt_data
W/bt-smp  ( 3144): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3144): Plain text(LSB ~ MSB) = 6e 6a 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3144): Encrypted text(LSB ~ MSB) = 99 13 7c d8 09 92 d6 c5 1e b2 d7 a8 2e 31 6c 49 
I/bt-btm  ( 3144): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3144): Stopping oneshot timer
,D/bt-btm  ( 3144): Starting oneshot timer type:103 timeout:900s
D/WeatherUtility( 1221): Weather sync is On
D/PMS     (  967): releaseWL(137afac3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  967): releaseWL(2e55a7be): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  967): acquireWL(e88801f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(e88801f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  967): updateBatteryInfo
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): runPSCheck
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): >> updateStatus
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): << updateStatus
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  967): acquireWL(3e222f6c): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{2f3871b2: PendingIntentRecord{2f58d503 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804890, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{1d8a6054: PendingIntentRecord{123ccbfd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=991950, Int=0
,I/ActivityManager(  967): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6726 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,V/AlarmManager(  967): sending alarm PendingIntent{38894935: PendingIntentRecord{3ac081ca com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1451957502609, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{17beff3b: PendingIntentRecord{65e44ca com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451957734215, Int=0
,W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  967): releaseWL(3e222f6c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PowerUsageList:PowerUsageHelper( 6386): MY_DEBUG = false
,D/PowerUsageService( 6386): repeat time = 1451958660086,
,I/art     (  415): Explicit concurrent mark sweep GC freed 8675(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 389us total 49.705ms,
,I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 252us total 16.678ms
,I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 245us total 17.535ms
,I/PowerUsageList:PowerUsageHelper( 6386): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6386): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 6748): Error opening trace file: Permission denied (13)
I/dex2oat ( 6748): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6748): dex2oat: override thread count:4
,I/dex2oat ( 6748): dex2oat took 941.401ms (threads: 4),
,I/PushClient( 6726): ApplicationMonitor {3dc538aa}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6726): ApplicationMonitor {3dc538aa}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6726): ApplicationMonitor {3dc538aa}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6726): ApplicationMonitor {3dc538aa}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6726): ApplicationMonitor {3dc538aa}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6726): ApplicationMonitor {3dc538aa}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6726): ApplicationMonitor {3dc538aa}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6726): ApplicationMonitor {3dc538aa}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6726): ApplicationMonitor {3dc538aa}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6726): PnsModel {25250f95}: update(): Update registration caused by: alarm,
,I/PushClient( 6726): PnsConfigModel {2cc3650}: <init>(): Use dm-client for provisioning.
,W/System.err( 6726): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6726): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6726): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6726): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  967): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6755 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6755): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6755 dbg=false s=true
,I/DeviceManagement( 6755): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6755): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6755): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6755): WorkflowService: Starting workflow service
,I/DeviceManagement( 6755): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@25250f95] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6755): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6755): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6755): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6755): SessionStateController: Checking invariants...
,I/DeviceManagement( 6755): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6755): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6755): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6755): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@25250f95],
,I/DeviceManagement( 6755): WorkflowService: Stopping workflow service,
,I/ActivityManager(  967): Killing 6329:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=6329
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6329,
I/PushClient( 6726): PnsModel {25250f95}: update(): The registration record has not expired yet. No need to update.
,D/Process (  967): killProcessQuiet, pid=6441
I/ActivityManager(  967): Killing 6441:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6441
,D/PMS     (  967): acquireWL(e1fe9a5): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{1764f17a: PendingIntentRecord{35ea2d2b com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1451957781176, Int=0
,D/SmartSyncUtils( 6386): isEpsOn(), nState = 0,
,D/PMS     (  967): releaseWL(e1fe9a5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  967): acquireWL(28ba8588): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6386 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6386): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6386): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6386): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6386): SettingOnTime = 1451973600000, randomSettingOnTime = 1451972412000
,D/SmartSyncScreenOnOffTimeReceiver( 6386): SettingOffTime = 1452038400000, randomSettingOffTime = 1452042127000
,D/SmartSyncScreenOnOffTimeReceiver( 6386): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6386): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6386): bNightModeTurnOffOnce = false
,D/PMS     (  967): acquireWL(3b4a7b21): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{cc0ab46: PendingIntentRecord{205c7107 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1451957781213, Int=0
,D/PMS     (  967): releaseWL(28ba8588): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncDataLinkTurnOffService( 6386): SMARTSYNC_TURN_OFF_NETWORK, current time = 1451957781246, randomOffTime = 1452042127000, newRandomOffTime = 1452042127000
,D/SmartSyncDataLinkTurnOffService( 6386): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 1451972412000, randomMobileOnTime = 1451972412000
,D/SmartSyncUtils( 6386): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 6386): turnOffMobile bPolicyEnabled = true
,D/SmartSyncUtils( 6386): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 6386): turnOffMobile bCheckMobileData = false,
,D/LocationManagerService(  967): getProviders()=[gps, network]
D/LocationManagerService(  967): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 6386): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6386): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 6386): turnOffWifi ui setting = true,
D/SmartSyncUtils( 6386): isWifiHotSpotEnabled = false
I/ActivityManager(  967): Cannot resolve ContentProvider=com.htc.vowifi
D/SmartSyncUtils( 6386): state = 0
E/ActivityThread( 6386): Failed to find provider info for com.htc.vowifi
,D/SmartSyncDataLinkTurnOffService( 6386): turnOffWifi bCheckWifiData = false
D/PMS     (  967): releaseWL(3b4a7b21): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 6386): turnOffWifi bWifiConnected = false
,D/LocationManagerService(  967): getProviders()=[gps, network]
D/LocationManagerService(  967): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 6386): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6386): isCharging status = 5
,D/PMS     (  967): acquireWL(a32a85d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(a32a85d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  967): plugged=true pluggin=true
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,D/HtcPowerSaver(  967): updateBatteryInfo
D/PMS     (  967): runPSCheck
D/HtcPowerSaver(  967): Checking...
I/HtcPowerSaver(  967): >> updateStatus
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100,
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(1bcc35d2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
,I/BatteryService(  967): n_update end
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PMS     (  967): releaseWL(1bcc35d2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): handleMessage: E msg.what=155652
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: StaEnabledState
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): << updateStatus
D/WifiController(  967): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  967): acquireWL(c516a3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(c516a3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/NotificationService(  967): plugged=true pluggin=true
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  967): runPSCheck
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  967): >> updateStatus
,D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  967): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  967): << updateStatus
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  967): acquireWL(5e27da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(5e27da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  967): plugged=true pluggin=true,
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  967): >> updateStatus
,D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
,D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5799): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5799): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5799): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5799): Cust_ConnectToPC   : spcsc>false
D/        ( 5799): Cust_ConnectToPC   : IPT>true
D/        ( 5799): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5799): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 5799): Index of the first 1 = -1
,W/ContextImpl( 5799): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5799): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 5799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
E/SmartNS_Utility( 5799): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5799): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5799): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
D/SmartNS_Utility( 5799): [ACC]android_networking:tethering_guard_support=false
W/SystemReader( 5799): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  967): User[0] Flushing usage stats to disk,
,D/PMS     (  967): acquireWL(3c93dd1e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(3c93dd1e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/NotificationService(  967): plugged=true pluggin=true
D/WifiController(  967): handleMessage: E msg.what=155652
D/PMS     (  967): runPSCheck
D/WifiController(  967): processMsg: DeviceActiveState
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): processMsg: StaEnabledState
,I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): << updateStatus
,D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(3b8879ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
,I/BatteryService(  967): n_update end
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  967): releaseWL(3b8879ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  967): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  967): Checking...
I/HtcPowerSaver(  967): >> updateStatus
D/PowerUI ( 1221): closing low battery warning: level=100
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  967): BroadcastReceiver::onReceive+
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  967): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  967): << updateStatus
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  967): plugged=true pluggin=true
,D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  967): acquireWL(9978615): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{1d8a6054: PendingIntentRecord{123ccbfd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1051950, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{99cad2a: PendingIntentRecord{2cf4b71b com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1840999, Int=0
,I/bt-btm  ( 3144): Received oneshot timer event complete
D/PMS     (  967): acquireWL(2dde60b8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3144 1002 null
I/bt-btm  ( 3144): btm_ble_timeout
I/bt-btm  ( 3144): btm_gen_resolvable_private_addr
D/bt-btm  ( 3144): btm_ble_rand_enc_complete
I/bt-btm  ( 3144): btm_gen_resolve_paddr_low
D/bt-smp  ( 3144): smp_encrypt_data
W/bt-smp  ( 3144): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3144): Plain text(LSB ~ MSB) = be 16 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3144): Encrypted text(LSB ~ MSB) = 10 b4 dd d2 b5 5b eb 94 6c 85 a2 b1 1a 13 f8 b4 
I/bt-btm  ( 3144): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3144): Stopping oneshot timer
D/bt-btm  ( 3144): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  967): Prepared write state in 15ms
,D/PMS     (  967): releaseWL(9978615): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/ProcessStatsService(  967): Pruning old procstats: /data/system/procstats/state-2016-01-04-03-46-02.bin
,D/PMS     (  967): releaseWL(2dde60b8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  967): acquireWL(f776e91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
,I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(f776e91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): handleMessage: E msg.what=155652
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
,D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): << updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  967): acquireWL(eb071f6): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000}
V/AlarmManager(  967): sending alarm PendingIntent{2f3871b2: PendingIntentRecord{2f58d503 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1711981, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{11e0422e: PendingIntentRecord{e3a61cf android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1824831, Int=1800000
D/PMS     (  967): acquireWL(1e1da9f7): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
V/AlarmManager(  967): sending alarm PendingIntent{1d8a6054: PendingIntentRecord{123ccbfd android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1891950, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{874d064: PendingIntentRecord{29362cd com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1853241, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{3869b782: PendingIntentRecord{3d64f23a com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1451958664618, Int=1800000
V/AlarmManager(  967): sending alarm PendingIntent{2b78ee93: PendingIntentRecord{65e44ca com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451958660086, Int=0
,D/PMS     (  967): releaseWL(1e1da9f7): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateNotificationsLocked()
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  967): acquireWL(7005ec9): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4416 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/PMS     (  967): acquireWL(2807c7fc): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4416 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): releaseWL(eb071f6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  967): releaseWL(7005ec9): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 6386): MY_DEBUG = false
,D/PowerUsageService( 6386): repeat time = 1451959564712
,I/EventLogService( 4416): Aggregate from 1451956864612 (log), 1451956864576 (data)
,I/GLSUser ( 1898): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1898): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1898): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1898): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  967): releaseWL(2807c7fc): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1898): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/PowerUsageList:PowerUsageHelper( 6386): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6386): gen(), null == sipper.uidObj, userId = 0
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  967): acquireWL(24cb282c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PMS     (  967): releaseWL(24cb282c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967): onReceive BATTERY_CHANGED
,D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1307): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  967): runPSCheck
D/DotMatrix( 1307): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): handleMessage: E msg.what=155652
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DeviceActiveState
,D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
D/HeadsetStateMachine( 3144): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1800000ms)
```
