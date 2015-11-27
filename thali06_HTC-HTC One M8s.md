#### Test 51986340bb0815b_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
E/cutils-trace( 6934): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6934): ====startRecUseTime====
D/htc.customization.log.level( 6934):  is 
W/CustomizationLogLevel( 6934): Level value is invalid, use default level 2
D/CustomizationManager( 6934):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 6934): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6934): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6934): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6934): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6934): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6934): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6934): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6934): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6934): Parsing tag category name = system
I/CustomizationCIDLoader( 6934): Parsing tag category name = application
I/CustomizationCIDLoader( 6934): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6934): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6934): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6934): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6934): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6934): add string-array item, value = 42507
I/CustomizationCIDLoader( 6934): add string-array item, value = 21902
I/CustomizationCIDLoader( 6934): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6934): add string-array item, value = 23420
I/CustomizationCIDLoader( 6934): add string-array item, value = 22299
I/CustomizationCIDLoader( 6934): add string-array item, value = 24002
I/CustomizationCIDLoader( 6934): add string-array item, value = 23210
I/CustomizationCIDLoader( 6934): add string-array item, value = 23205
I/CustomizationCIDLoader( 6934): add string-array item, value = 23806
I/CustomizationCIDLoader( 6934): add string-array item, value = 23430
I/CustomizationCIDLoader( 6934): add string-array item, value = 23408
I/CustomizationCIDLoader( 6934): add string-array item, value = 27205
I/CustomizationCIDLoader( 6934): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6934): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6934):  Read CID file spent 0.108 (s)
D/CustomizationManager( 6934):  All configurations done spent 0.109 (s)
--------- beginning of system
D/PMS     (  989): acquireHCC(16740079): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 989 1000 null
D/PMS     (  989): acquireHCC(3e1f41be): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 989 1000 null
I/ActivityManager(  989): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6934 on display 0
I/ActivityManager(  989): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6952 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1351): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1351): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  989): Display changed displayId=0
I/TrimMemoryManager( 1606): [trimMemory] 20
I/WebViewFactory( 6952): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6952): Time to load native libraries: 10 ms (timestamps 425-435),
,I/LibraryLoader( 6952): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6952): Binding Chromium to main looper Looper (main, tid 1) {ad71489}
,I/LibraryLoader( 6952): Expected native library version number "",actual native library version number ""
,I/chromium( 6952): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6952): Initializing chromium process, singleProcess=true
,W/art     ( 6952): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6952): ApplicationContext is null in ApplicationStatus
,W/chromium( 6952): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6952): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6952): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6952): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6952): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6952): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6952): Local Branch: 
I/Adreno-EGL( 6952): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6952): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6952):                  d74aa161a12b9c6fc6332151
,W/System.err(  989): java.lang.Throwable: stack dump
W/System.err(  989): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  989): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  989): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  989): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  989): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  989): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32d5fa22:true
,D/BluetoothAdapter( 6952): 454258757: getState(). Returning 12
,W/art     ( 6952): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6952): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6952): CordovaWebView is running on device made by: HTC
,W/art     ( 6952): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6952): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  989): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
W/chromium( 6952): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  989): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  989): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  989): hiding MENU key
,D/StatusBarManagerService(  989): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  989): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  989): hiding MENU key
,D/FindExtension( 6952): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6952): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1f056bb, mServedView=org.apache.cordova.engine.SystemWebView{1d6417d8 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@bf22731
,I/InputMethodManagerService(  989): Disable input method client, pid=1606
I/PhoneStatusBar( 1233): setImeWindowStatus(false,false)
D/StatusBarManagerService(  989): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6952): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  989): Displayed com.test.thalitest/.MainActivity: +605ms (total +650ms)
,W/BindingManager( 6952): Cannot call determinedVisibility() - never saw a connection for the pid: 6952
,D/JsMessageQueue( 6952): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6952): JniHelper::setJavaVM(0xab2658f8), pthread_self() = -1403543048
,D/JX-Cordova( 6952): jxcore cordova android initializing
,I/ActivityManager(  989): Killing 5812:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  989): killProcessQuiet, pid=5812
,D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 5812
,W/jxcore-log( 6952): Initializing JXcore engine
W/jxcore-log( 6952): JXcore engine is ready
,W/jxcore-log( 6952): Starting JXcore engine,
,W/jxcore-log( 6952): Platform android
W/jxcore-log( 6952): 
W/jxcore-log( 6952): Process ARCH arm
W/jxcore-log( 6952): 
,D/PMS     (  989): releaseHCC(16740079): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  989): releaseHCC(3e1f41be): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6952): JXcore Cordova bridge is ready!
I/jxcore-log( 6952): 
,W/jxcore-log( 6952): JXcore engine is started
I/Choreographer( 6952): Skipped 93 frames!  The application may be doing too much work on its main thread.
I/chromium( 6952): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6952): Toggling radios to true
I/jxcore-log( 6952): 
,D/BluetoothAdapter( 6952): enable(): BT is already enabled..!
,D/WifiService(  989): New client listening to asynchronous messages
,E/WifiTrafficPoller(  989): ADD_CLIENT: 8
,D/WifiManager( 6952): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366,
W/Settings:Agent(  989): MONITOR_LOG
D/WifiService(  989): setWifiEnabled: true pid=6952, uid=10366
W/Settings:Agent(  989): name: wifi_on
E/WifiService(  989): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  989): value: 2
I/WifiService(  989): isSprintWifiRestricted(): false
W/Settings:Agent(  989): >> traceCallingStack()
I/WifiService(  989): isMdmWifiRestricted(): false
W/Settings:Agent(  989): Process.myPid(): 989
W/Settings:Agent(  989): Process.myTid(): 1602
W/Settings:Agent(  989): Process.myUid(): 1000
W/Settings:Agent(  989): 
W/Settings:Agent(  989): 
W/System.err(  989): java.lang.Throwable: stack dump
,W/System.err(  989): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  989): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  989): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  989): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  989): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  989): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  989): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  989): ,	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  989): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  989): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  989): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  989): 
W/Settings:Agent(  989): << traceCallingStack(): 16(ms)
D/WifiController(  989): handleMessage: E msg.what=155656
D/WifiManager( 6952): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  989): processMsg: DeviceActiveState
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131145
D/WifiManager( 6952): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  989): processMsg: ConnectedState
E/WifiStateMachine(  989):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  989): processMsg: L2ConnectedState
E/WifiStateMachine(  989):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/jxcore-log( 6952): Radios toggled
I/jxcore-log( 6952): 
D/wpa_supplicant( 1367): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1367): wlan0: Cancelling scan request
D/wpa_supplicant( 1367): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1367): TDLS: Tear down peers
D/wpa_supplicant( 1367): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 1367): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1367): wlan0: Deauthentication notification
D/wpa_supplicant( 1367): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1367): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1367): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1367): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1367): enter disconnect check
,I/wpa_supplicant( 1367): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  989): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  989): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1367): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1367): wlan0: Ignore connection failure indication since interface has been put into disconnected state
E/WifiMonitor(  989): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  989): interfaceLinkStateChanged wlan0, false
D/Tethering(  989): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  989): interfaceLinkStateChanged wlan0, false
D/UsbDeviceManager(  989): [USBNET] bCheckSuppFunc: cdc_network
D/Tethering(  989): interfaceStatusChanged wlan0, false
D/PMS     (  989): acquireWL(dfc0bff): PARTIAL_WAKE_LOCK  NetworkStats 0x1 989 1000 null
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiDisplayAdapter(  989): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  989):     Client/Owner: Client
D/WifiDisplayAdapter(  989):     GroupId: 
D/WifiDisplayAdapter(  989):     Passphrase: 
D/WifiDisplayAdapter(  989):     SessionId: 0
D/WifiDisplayAdapter(  989):     IP Address: }
D/Tethering(  989): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  989): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  989): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  989): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/UsbnetService(  989): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1367): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1367): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 1367): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1367): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1367): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a797df88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1367):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1367): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1367): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1367): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1367): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1367): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1367): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1367): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1367): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1367): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1367): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1367): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 1367): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1367): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1367): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1367): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1367): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1367): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1367): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1367): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
E/WifiStateMachine(  989): transitionTo: destState=DisconnectingState
D/wpa_supplicant( 1367): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/HTCRequest(  989): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  989): invokeExitMethods: ConnectedState
,E/WifiStateMachine(  989): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  989): release()
E/WifiStateMachine(  989): PerfLock released for exiting ConnectedState
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  989): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
D/WifiMonitor(  989): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  989): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  989): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  989): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  989): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  989): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SAVE_CONFIG'
D/WifiP2pService(  989): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1367): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1367): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1367): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1367): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1367): Power_Mode_Type mode = 0
I/wpa_supplicant( 1367): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1367): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1367): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  989): setDhcpActive: false
D/PMS     (  989): releaseWL(dfc0bff): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/TetherSettings( 6104): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
V/NetworkPolicy(  989): updateNetworkEnabledLocked()
D/        ( 6104): Cust_ConnectToPC   : Internet_Sharing>true
V/NetworkPolicy(  989): updateNotificationsLocked()
D/        ( 6104): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6104): Cust_ConnectToPC   : spcsc>false
D/        ( 6104): Cust_ConnectToPC   : IPT>true
D/        ( 6104): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 6104): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 6104): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6104): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6104): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
V/NativeCrypto( 1979): Read error: ssl=0x55aa0d7410: I/O error during system call, Connection timed out
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
,D/PMS     (  989): acquireWL(632fdcc): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1979 10024 WorkSource{10024 com.google.android.gms}
,D/libc    (  989): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  989): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false,
D/ConnectivityService(  989): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  989): setDetailed state send new extra info<unknown ssid>
W/ContextImpl( 6104): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NetworkPolicy(  989): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  989): NetworkAgent != null
D/WIFI_ICON( 1233): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1233): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 13
V/NativeCrypto( 1979): SSL shutdown failed: ssl=0x55aa0d7410: I/O error during system call, Broken pipe
I/IntentController( 1233): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  989): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  989): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  989): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WIFI_ICON( 1233): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/StatusBar.NetworkController( 1233): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/PMS     (  989): releaseWL(632fdcc): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1367): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1367): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/ConnectivityService(  989): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1367): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/WifiDataStallTracker(  989): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  989): stopDataStallAlarm 
E/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=4
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  989): ENABLE_DATA_MONITOR_POLL false Token 3
,I/SmartNS_Utility( 6104): setISNotification
I/IntentController( 1233): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  989): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  989):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  989): Start Disconnecting Watchdog 1
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131146
E/WifiStateMachine(  989): processMsg: DisconnectingState
,I/IntentController( 1233): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  989):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1367): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1367): Fast associate: Old scan results
D/wpa_supplicant( 1367): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1367): wpa_supplicant_scan enter
D/wpa_supplicant( 1367): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1367): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1367): WPS: Building WPS IE for Probe Request
,D/wpa_supplicant( 1367): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1367): WPS:  * Request Type
D/wpa_supplicant( 1367): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1367): WPS:  * UUID-E
D/wpa_supplicant( 1367): WPS:  * Primary Device Type
D/wpa_supplicant( 1367): WPS:  * RF Bands (3)
D/wpa_supplicant( 1367): WPS:  * Association State
D/wpa_supplicant( 1367): WPS:  * Configuration Error (0)
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1367): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1367): WPS:  * Manufacturer
,D/wpa_supplicant( 1367): WPS:  * Model Name
D/wpa_supplicant( 1367): WPS:  * Model Number
D/wpa_supplicant( 1367): WPS:  * Device Name
D/wpa_supplicant( 1367): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1367): P2P: * P2P IE header
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1367): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1367): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1367): wlan0: Add radio work 'scan'@0x55a7980680
D/HTCRequest(  989): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1367): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1367): wlan0: Starting radio work 'scan'@0x55a7980680 after 0.000079 second wait
D/wpa_supplicant( 1367): wlan0: nl80211: scan request
D/HTCRequest(  989): WifiMonitor:handleSupplicantStateChange(): SSID
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiMonitor(  989): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  989): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/wpa_supplicant( 1367): Scan requested (ret=0) - scan timeout 30 seconds
D/libc    (  989): [NET] android_getaddrinfofornet-, SUCCESS
D/wpa_supplicant( 1367): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1367): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1367): wlan0: Own scan request started a scan in 0.000153 seconds
D/WIFI_ICON( 1233): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1367): wlan0: CTRL-EVENT-SCAN-STARTED 
D/StatusBar.NetworkController( 1233): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): ValidatedState{ when=-6ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): DefaultState{ when=-6ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): Validated
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  989): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  989): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=147460
E/WifiStateMachine(  989): processMsg: DisconnectingState
,E/WifiStateMachine(  989):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132837
E/WifiStateMachine(  989): processMsg: ConnectModeState
D/SmartNS_Utility( 6104): usb_cable_connect = 1
E/WifiStateMachine(  989):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132838
E/WifiStateMachine(  989): ConnectModeState: Network connection lost 
E/WifiStateMachine(  989): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  989): handleMessage: new destination call exit/enter
E/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  989): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  989): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  989): DisconnectedState call setCountryCode()
E/WifiStateMachine(  989):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
D/SmartNS_Utility( 6104): usb_denied = 0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1367): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1367): wlan0: Cancelling scan request
I/SmartNS_PSService( 6104): usb notificaiton:true
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
I/ActionCombine( 6104): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/wpa_supplicant( 1367): wlan0: nl80211: sched_scan request
D/SmartNS_Utility( 6104): usb_cable_connect = 1
D/SmartNS_Utility( 6104): usb_denied = 0
I/SmartNS_PSService( 6104): usb notificaiton:true
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1233): reapply : com.android.settings 1 36
D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 6104): Tethered state change:false isNSOpening:false
D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/QuickSettingWifi( 1233): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
I/RemoteViews( 1233): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1233): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1367): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec,
D/wpa_supplicant( 1367): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: Sched scan started
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131101
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  989): processMsg: ConnectModeState
D/wpa_supplicant( 1367): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1367): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1367): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1367): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1367): wlan0: Scan completed in 0.052991 seconds
E/WifiStateMachine(  989):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  989): processMsg: DriverStartedState
D/wpa_supplicant( 1367): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1367): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1367): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1367): wlan0: New scan results available (own=1 ext=0)
E/WifiStateMachine(  989):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1367): wlan0: Radio work 'scan'@0x55a7980680 done in 0.054058 seconds
D/WifiP2pService(  989): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiP2pService(  989): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1367): wlan0: No suitable network found
,D/WifiP2pService(  989): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1367): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1367): wlan0: Cancelling sched scan
D/wpa_supplicant( 1367): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1367): wlan0: Cancelling scan request
D/wpa_supplicant( 1367): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1367): nl80211: Received scan results (1 BSSes)
E/WifiStateMachine(  989):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  989): processMsg: DefaultState
I/wpa_supplicant( 1367): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1367): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1367): p2p0: BSS: Add new id 0 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 1367): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1367): p2p0: New scan results available (own=0 ext=0)
I/wpa_supplicant( 1367): clear disabled list - type=1
D/wpa_supplicant( 1367): p2p0: No suitable network found
D/wpa_supplicant( 1367): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: Sched scan stopped
E/WifiStateMachine(  989):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1367): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WifiStateMachine(  989): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  989): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=147462
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=132886  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  989): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=132887  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WIFI_ICON( 1233): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  989): handleMessage: X
D/StatusBar.NetworkController( 1233): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNetworkAgent(  989): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  989): handleMessage: E msg.what=147462
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  989): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  989): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  989): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine(  989):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132887  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  989): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/WifiMonitor(  989): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 0 38:f8:89:11:e9:11]
E/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiMonitor(  989): WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  989): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  989): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  989): NetworkAgent == null
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 16,
E/WifiStateMachine(  989): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6104): >>>>>WISPrService start isConnected = true<<<<<
I/IntentController( 1233): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=132895  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=147461
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:79 bcn=0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:79 bcn=0
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:79 bcn=0
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
I/QuickSettingWifi( 1233): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  989):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:79 bcn=0
D/WifiStateMachine(  989): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1367): wlan0: Control interface command 'LIST_DONGLES'
D/WIFI_ICON( 1233): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  989): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/StatusBar.NetworkController( 1233): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1233): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  989): [1,448,626,300,104 ms] noteScanEnd no scan source
W/ContextImpl(  989): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1367): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiService(  989): New client listening to asynchronous messages
E/WifiTrafficPoller(  989): ADD_CLIENT: 9
E/WifiStateMachine(  989): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@301560e6 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  989): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  989): 01ABC c2:ff:d4:d3:aa:48 rssi=-55 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  989): NG700 c0:ff:d4:d3:aa:48 rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  989): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  989): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  989):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-55 freq=2462
E/WifiAutoJoinController (  989): UPC503894600 a0:c5:62:7a:49:97 rssi=-86 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  989): Gonzos 38:f8:89:11:e9:11 rssi=-87 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  989): ageScanResultsOut delay 40000 size 5 now 1448626300107
E/WifiAutoJoinController (  989): newSupplicantResults size=5 known=1 true
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1367): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  989): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  989): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  989): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  989): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  989): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  989): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-55,-127) num=(1,0)
E/WifiAutoJoinController (  989): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  989): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  989): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  989): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  989): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-55 freq=2462
D/HtcWifiControlRoamOffload: (  989): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  989): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  989): Done attemptAutoJoin status=3
E/WifiConfigStore(  989):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  989): handleMessage: X
E/WifiStateMachine(  989): handleMessage: E msg.what=131215
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiStateMachine(  989):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-55 ;0 ,-127] any roam=0 rt=132907
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-55 ;0 ,-127] any roam=0 rt=132907
E/WifiStateMachine(  989): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  989): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  989): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
,E/WifiConfigStore(  989): Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1367): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  989): will read network variables netId=0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/ConnectivityService(  989): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/ConnectivityService(  989):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/ConnectivityService(  989): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/Nat464Xlat(  989): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/ConnectivityService(  989): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/ConnectivityService(  989): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/NetworkManagementService(  989): Removing idletimer
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1367): Do not allow key_data field to be exposed
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/WifiDisplayAdapter(  989): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  989):     Client/Owner: Client
D/WifiDisplayAdapter(  989):     GroupId: 
D/WifiDisplayAdapter(  989):     Passphrase: 
D/WifiDisplayAdapter(  989):     SessionId: 0
D/WifiDisplayAdapter(  989):     IP Address: }
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  989): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  989):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  989): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1367): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1367): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1367): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  989): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1367): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1367): ENABLE_NETWORK (0)
D/wpa_supplicant( 1367): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1367): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1367): wpa_supplicant_scan enter
D/wpa_supplicant( 1367): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1367): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1367): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1367): WPS:  * Request Type
D/wpa_supplicant( 1367): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1367): WPS:  * UUID-E
D/wpa_supplicant( 1367): WPS:  * Primary Device Type
D/wpa_supplicant( 1367): WPS:  * RF Bands (3)
D/wpa_supplicant( 1367): WPS:  * Association State
D/wpa_supplicant( 1367): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1367): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1367): WPS:  * Manufacturer
D/wpa_supplicant( 1367): WPS:  * Model Name
D/wpa_supplicant( 1367): WPS:  * Model Number
D/wpa_supplicant( 1367): WPS:  * Device Name
D/wpa_supplicant( 1367): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1367): P2P: * P2P IE header
D/wpa_supplicant( 1367): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1367): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1367): wlan0: Add radio work 'scan'@0x55a7980680
D/wpa_supplicant( 1367): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1367): wlan0: Starting radio work 'scan'@0x55a7980680 after 0.000025 second wait
D/wpa_supplicant( 1367): wlan0: nl80211: scan request
D/wpa_supplicant( 1367): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1367): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1367): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1367): wlan0: Own scan request started a scan in 0.000057 seconds
I/wpa_supplicant( 1367): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  989): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  989): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  989): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1367): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1367): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1367): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  989): will read network variables netId=0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): ValidatedState{ when=0 what=5324,87 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  989): Disconnected - quitting
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/PMS     (  989): acquireWL(3e8ae72a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 989 1000 null
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/CSLegacyTypeTracker(  989): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/ConnectivityService(  989): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/wpa_supplicant( 1367): Do not allow key_data field to be exposed
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/usbnet  (  989): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/usbnet  (  989):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/ConnectivityManager.CallbackHandler( 1233): CM callback handler got msg 524292
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/ConnectivityService(  989): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/SecurityController( 1233): onLost 100
E/ConnectivityService(  989): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/usbnet  (  989): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
E/ConnectivityService(  989): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 phase2'
V/NetworkPolicy(  989): ensureActiveMobilePolicyLocked()
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/PMS     (  989): acquireWL(280f691b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 989 1000 null
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='identity'
I/QuickSettingWifi( 1233): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/DATA_ICON( 1233): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1367): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1367): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  989): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  989):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1367): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1367): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1367): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1367): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1367): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1367): wpa_supplicant_scan enter
D/wpa_supplicant( 1367): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1367): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1367): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  989): setLastSelectedConfiguration -1
E/WifiStateMachine(  989): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  989): handleMessage: new destination call exit/enter
E/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  989): invokeExitMethods: DisconnectedState
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1367): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  989): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  989): invokeEnterMethods: DisconnectedState
D/NetworkPolicy(  989): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
E/WifiStateMachine(  989): DisconnectedState call setCountryCode()
V/NetworkPolicy(  989): updateNetworkEnabledLocked()
E/WifiStateMachine(  989):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
V/NetworkPolicy(  989): updateIfacesLocked()
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
V/NetworkPolicy(  989): updateNotificationsLocked()
D/wpa_supplicant( 1367): wlan0: Control interface command 'SET pno 1'
D/PMS     (  989): releaseWL(280f691b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1367): CTRL_IFACE SET 'pno'='1'
D/NetworkManagementService(  989): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/wpa_supplicant( 1367): wlan0: Cancelling scan request
D/DATA_ICON( 1233): dataConnected: false/false
D/wpa_supplicant( 1367): wlan0: nl80211: sched_scan request
D/StatusBar.NetworkController( 1233): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1233): receive.wifiConnect:false wifiAPname:null elapse:0
V/NetworkPolicy(  989): updateNetworkEnabledLocked()
D/Tethering(  989): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkPolicy(  989): updateNotificationsLocked()
D/Tethering(  989): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/FlexNetS( 6818): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1367): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1367): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1367): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1367): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1367): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1367): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1367): wlan0: Scan completed in 0.039472 seconds
D/wpa_supplicant( 1367): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1367): wlan0: BSS: Start scan result update 8
D/wpa_supplicant( 1367): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to no match in scan
E/WifiStateMachine(  989): handleMessage: X
D/wpa_supplicant( 1367): wlan0: BSS: Remove id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to no match in scan
E/WifiStateMachine(  989): handleMessage: E msg.what=131131
E/WifiStateMachine(  989): processMsg: DisconnectedState
D/wpa_supplicant( 1367): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to no match in scan
D/wpa_supplicant( 1367): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to no match in scan
D/wpa_supplicant( 1367): wlan0: BSS: Remove id 4 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to no match in scan
D/wpa_supplicant( 1367): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1367): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1367): wlan0: Radio work 'scan'@0x55a7980680 done in 0.040365 seconds
D/wpa_supplicant( 1367): wlan0: No suitable network found
D/wpa_supplicant( 1367): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1367): wlan0: Cancelling sched scan
E/WifiStateMachine(  989):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  989): processMsg: ConnectModeState
D/wpa_supplicant( 1367): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1367): wlan0: Cancelling scan request
D/wpa_supplicant( 1367): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1367): nl80211: Received scan results (1 BSSes)
E/WifiStateMachine(  989):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
I/wpa_supplicant( 1367): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/WifiP2pService(  989): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1367): p2p0: BSS: Start scan result update 2
D/WifiP2pService(  989): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1367): BSS: last_scan_res_used=1/32
D/WifiP2pService(  989): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1367): p2p0: New scan results available (own=0 ext=0)
I/wpa_supplicant( 1367): clear disabled list - type=1
D/wpa_supplicant( 1367): p2p0: No suitable network found
E/WifiStateMachine(  989): handleMessage: X
D/wpa_supplicant( 1367): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1367): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1367): wlan0: Event SCHED_SCAN_STOPPED (38) received
D/WIFI    (  989): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  989):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  989): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiStateMachine(  989): enter WifiNetworkFactory startNetwork. mIPTStart:false
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
W/ContextImpl(  989): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  989): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11]
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11
E/WifiMonitor(  989): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  989): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  989): handleMessage: E msg.what=147461
E/WifiMonitor(  989): WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  989): processMsg: DisconnectedState
E/WifiMonitor(  989): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  989):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:79 bcn=0
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:79 bcn=0
E/WifiStateMachine(  989): processMsg: DriverStartedState
E/WifiStateMachine(  989):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:79 bcn=0
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
E/WifiStateMachine(  989):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:79 bcn=0
D/WifiStateMachine(  989): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1367): wlan0: Control interface command 'LIST_DONGLES'
I/ActivityManager(  989): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=7013 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
W/WISPrService( 6104): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6104): trigger connection
E/WifiStateMachine(  989): [1,448,626,300,199 ms] noteScanEnd no scan source
W/WifiHW  (  989): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1367): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  989): handleMessage: X
D/WISPrService( 6104): continue
D/WISPrService( 6104): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6104): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6104): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6104): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6104): start DataConnection
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/libc    ( 6104): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6104): [NET] android_getaddrinfofornet-, err=8
D/FlexNetS( 6818): updateSvcAllowedInSettings:false
D/WISPrService( 6104): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6104): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6104): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6104): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/libc    ( 6104): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6104): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6104): [NET] android_getaddrinfo_proxy+
D/libc    ( 6104): [NET] android_getaddrinfo_proxy get netid:0
D/FlexNetS( 6818): updateSvcAllowedInSettings:false
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6104): [NET] android_getaddrinfo_proxy-, NODATA
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/FlexNetS( 6818): updateSvcAllowedInSettings:false
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/FlexNetS( 6818): updateSvcAllowedInSettings:false
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms,
,D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs,
,D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/libc    ( 6104): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6104): [NET] android_getaddrinfofornet-, err=8
,D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/WISPrService( 6104): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/WifiService(  989): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 7013): [c8d.2.]  listen tmrbb8,
D/FlexNetS( 6818): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6882): remove item 101 (p2d27in194) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 7013): [c8d.2.] summary 118:p2 ignore
,D/Process (  989): killProcessQuiet, pid=6449
I/ActivityManager(  989): Killing 6449:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6449,
,D/BluetoothManagerService(  989): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/jxcore-log( 6952): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6952): 
I/jxcore-log( 6952): my name is : HTC-HTC One M8s_PT9563
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): attempting to connect to test coordinator,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): check test folder,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): found test : ./testFindPeers.js,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): found test : ./testReConnect.js,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): found test : ./testSendData.js,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): Test app app.js loaded,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/chromium( 6952): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/ConnectivityService(  989): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  989): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
I/AlarmManager(  989): [AlarmQueuing] connectivity wifi: false
,D/PMS     (  989): acquireWL(11e13a64): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 989 1000 null
D/htcCheckinService(  989): ConnectivityReceiver - onReceive() - original mNetworkConnected = true,
D/htcCheckinService(  989): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/GpsLocationProvider(  989): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  989): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ConnectivityHelper( 1606): [onReceive] WIFI(1): DISCONNECTED,
,I/ActivityManager(  989): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7046 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  989): No APN found to select.
,D/PMS     (  989): releaseWL(11e13a64): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 7013): [e23.1.]  listen tmrbb8
,D/MdScDataSum( 7013): [e23.1.] summary 118:p1 ignore
,I/MusicStore( 7046): Database version: 120,
,D/VoldConnector(  989): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 7046): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  989): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 7046): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  989): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,W/ContextImpl( 7046): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 7046): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7046): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 7046): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,W/ActivityThread( 7046): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 7046): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e80672d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7046): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7046): GMSCore installation verified
,I/ConfigStore( 7046): Config Database version: 1
,I/PackageManager(  989):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=7046, uid=10159, userID:0,
,D/WifiDisplayAdapter(  989): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  989):     Client/Owner: Client
D/WifiDisplayAdapter(  989):     GroupId: 
D/WifiDisplayAdapter(  989):     Passphrase: 
D/WifiDisplayAdapter(  989):     SessionId: 0
D/WifiDisplayAdapter(  989):     IP Address: }
,D/MediaRouterService(  989): Client com.google.android.music (pid 7046): Registered,
,D/WifiDisplayAdapter(  989): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  989):     Client/Owner: Client
D/WifiDisplayAdapter(  989):     GroupId: 
D/WifiDisplayAdapter(  989):     Passphrase: 
D/WifiDisplayAdapter(  989):     SessionId: 0
D/WifiDisplayAdapter(  989):     IP Address: }
,I/MediaRouter( 7046): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 7046): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/AutoSetting( 1649): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,D/AutoSetting( 1649): Util - no network available!
,D/MobileConnectivityChangeReceiver( 6673): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6673): onReceive CONNECTIVITY_CHANGE networkType=1,
I/PackageManager(  989):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=7046, uid=10159, userID:0
,D/AutoSetting( 1649): service - onCreate()
,I/GHttpClientFactory( 7046): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1649): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  989): request 1de43dbb passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  989): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1649): service - mHandler: cancel location update
D/AutoSetting( 1649): service -           changes count: 0
,I/iu.Environment( 4572): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*,
,I/GoogleURLConnFactory( 7046): Using platform SSLCertificateSocketFactory
I/iu.UploadsManager( 4572): num queued entries: 0
,I/iu.UploadsManager( 4572): num updated entries: 0
I/iu.SyncManager( 4572): NEXT; no task
,D/ChimeraCfgMgr( 4572): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  989): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7088 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/Babel   ( 6723): connection state changed from UNKNOWN to DISCONNECTED
,D/Process (  989): killProcessQuiet, pid=6629,
I/ActivityManager(  989): Killing 6629:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6629
,D/VoldConnector(  989): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
W/ContextImpl( 7088): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
I/GAv4    ( 7088): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7088):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7088):   adb logcat -s GAv4
,D/VoldConnector(  989): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 7088): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  989): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/ContextImpl( 7088): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,W/GAv4    ( 7088): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/VoldConnector(  989): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 7088): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7088): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7088): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/art     ( 1979): Explicit concurrent mark sweep GC freed 12755(688KB) AllocSpace objects, 7(588KB) LOS objects, 49% free, 4MB/8MB, paused 609us total 36.034ms
W/global  ( 7088): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7088): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 7088): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 7088): Time to load native libraries: 2 ms (timestamps 7228-7230)
,I/LibraryLoader( 7088): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7088): Binding Chromium to main looper Looper (main, tid 1) {173d69e4},
,I/LibraryLoader( 7088): Expected native library version number "",actual native library version number "",
,I/chromium( 7088): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 7088): Initializing chromium process, singleProcess=true,
,W/art     ( 7088): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 7088): ApplicationContext is null in ApplicationStatus
,W/chromium( 7088): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 7088): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7088): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7088): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7088): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7088): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7088): Local Branch: 
I/Adreno-EGL( 7088): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7088): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7088):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 7088): Requires BLUETOOTH permission
,I/NSApplication( 7088): Starting up...,
,I/ActivityManager(  989): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7146 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  989): killProcessQuiet, pid=6699,
I/ActivityManager(  989): Killing 6699:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  989): Recipient 6699,
,I/art     (  989): Explicit concurrent mark sweep GC freed 37144(1997KB) AllocSpace objects, 2(324KB) LOS objects, 33% free, 16MB/25MB, paused 2.144ms total 214.093ms,
,E/WifiStateMachine(  989): handleMessage: E msg.what=131168,
,E/WifiStateMachine(  989): processMsg: DisconnectedState
,E/WifiStateMachine(  989):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  989): processMsg: ConnectModeState
E/WifiStateMachine(  989):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  989): processMsg: DriverStartedState
,E/WifiStateMachine(  989):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  989): processMsg: SupplicantStartedState
E/WifiStateMachine(  989):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  989): processMsg: DefaultState
E/WifiStateMachine(  989):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  989): handleMessage: X
,I/ActivityManager(  989): Killing 6191:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  989): killProcessQuiet, pid=6191
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  989): Recipient 6191
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(15229131): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10024},
V/AlarmManager(  989): sending alarm PendingIntent{4daf016: PendingIntentRecord{d631d97 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=139792, Int=0
,D/PMS     (  989): acquireWL(2001cb84): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1979 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  989): releaseWL(15229131): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1979): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1979): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1979): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1979): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1979): [NET] android_getaddrinfo_proxy+
D/libc    ( 1979): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1979): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  989): releaseWL(2001cb84): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,I/jxcore-log( 6952): BLE advertisement not supported: Not supported,
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(1a8df7a2): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7046 10159 null,
,I/PackageManager(  989):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7046, uid=10159, userID:0,
,D/PMS     (  989): releaseWL(1a8df7a2): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
,I/MusicLeanback( 7046): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 7046): Stop autocaching.
,D/WearableService( 5895): callingUid 10024, callindPid: 5895
,E/GmsUtils( 7046): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7046): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC <<,
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(29aeaddd): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10024},
V/AlarmManager(  989): sending alarm PendingIntent{e478d52: PendingIntentRecord{f25823 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144002, Int=0
,D/PMS     (  989): releaseWL(29aeaddd): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  989): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  989): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/ContextImpl(  989): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  989): acquireWL(c1c6120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
,I/BatteryService(  989): n_update end
,D/PMS     (  989): releaseWL(c1c6120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  989): updateBatteryInfo
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/NotificationService(  989): plugged=true pluggin=true
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1233): closing low battery warning: level=100
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/WifiController(  989): battery changed pluggedType: 2
D/WifiController(  989): handleMessage: E msg.what=155652
D/PMS     (  989): runPSCheck
D/WifiController(  989): processMsg: DeviceActiveState
D/HtcPowerSaver(  989): Checking...
D/WifiController(  989): processMsg: StaEnabledState
I/HtcPowerSaver(  989): >> updateStatus
D/WifiController(  989): processMsg: DefaultState
D/PowerUI ( 1233): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  989): handleMessage: X
I/IntentController( 1233): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1233): status:5 level:100 unsupport:false plugged:true,
,D/AutoSetting( 1649): service - handleMessage() stop self,
,D/AutoSetting( 1649): service - onDestroy() END,
D/AutoSetting( 1649): service - handleMessage() quit looper
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/TelephonyReceiver( 1560): switchBindHtcMsgCursor: null,
,D/PMS     (  989): acquireWL(c6d4ad9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000}
,V/AlarmManager(  989): sending alarm PendingIntent{516ba3b: PendingIntentRecord{1c0d7558 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=152796, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{142d2c9e: PendingIntentRecord{3b08537f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1448626337314, Int=0
,V/AlarmManager(  989): sending alarm PendingIntent{3f366f4c: PendingIntentRecord{20debb95 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191874, Int=0,
,D/PMS     (  989): acquireWL(63b74aa): PARTIAL_WAKE_LOCK  *backup* 0x1 989 1000 null
,D/PMS     (  989): acquireWL(2a58a89b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1979 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  989): releaseWL(c6d4ad9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
W/BackupManagerService(  989): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  989): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  989): releaseWL(63b74aa): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  989): releaseWL(2a58a89b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1233): Weather sync is On
W/WeatherTimeKeeper( 1233): [refreshWeatherData] no weather data
,D/PMS     (  989): releaseWL(3e8ae72a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  989): Failed to find a new network - expiring NetTransition Wakelock
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): ,
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(2f8f3377): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{1000}
V/AlarmManager(  989): sending alarm PendingIntent{26b15be4: PendingIntentRecord{39dbc84d android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=210729, Int=0
,D/PMS     (  989): releaseWL(2f8f3377): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/HtcUPManager( 1233): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1649): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@18b4c968
,D/HtcUPManager( 1233): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  989): killProcessQuiet, pid=6139,
I/ActivityManager(  989): Killing 6139:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6139
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(1229ef02): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
D/UsbnetService(  989): BroadcastReceiver::onReceive+
I/BatteryService(  989): n_update end
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/PMS     (  989): releaseWL(1229ef02): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  989): plugged=true pluggin=true
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/WifiController(  989): battery changed pluggedType: 2
D/WifiController(  989): handleMessage: E msg.what=155652
D/WifiController(  989): processMsg: DeviceActiveState
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
,I/IntentController( 1233): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  989): updateBatteryInfo
D/PMS     (  989): runPSCheck
D/HtcPowerSaver(  989): Checking...
,D/PowerUI ( 1233): closing low battery warning: level=100
I/HtcPowerSaver(  989): >> updateStatus
D/PowerUI ( 1233): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1233): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(20399013): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null,
I/BatteryService(  989): n_update end
D/PMS     (  989): releaseWL(20399013): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  989): updateBatteryInfo
D/PowerUI ( 1233): closing low battery warning: level=100
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  989): plugged=true pluggin=true
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  989): runPSCheck
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  989): Checking...
D/UsbnetService(  989): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  989): >> updateStatus
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  989): BroadcastReceiver::onReceive-
I/IntentController( 1233): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1233): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
,D/WifiController(  989): handleMessage: E msg.what=155652
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  989): processMsg: DeviceActiveState
I/HtcPowerSaver(  989): << updateStatus
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): battery changed pluggedType: 2
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
,I/BatteryController( 1233): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,D/wpa_supplicant( 1367): p2p0: BSS: Remove id 0 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/WifiMonitor(  989): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 0 38:f8:89:11:e9:11]
E/WifiMonitor(  989): WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 38:f8:89:11:e9:11
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(41a5250): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000}
,V/AlarmManager(  989): sending alarm PendingIntent{516ba3b: PendingIntentRecord{1c0d7558 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=212797, Int=0
,V/AlarmManager(  989): sending alarm PendingIntent{ecbf94e: PendingIntentRecord{13231a6f com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1448626509331, Int=0
,D/PMS     (  989): releaseWL(41a5250): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1233): Weather sync is On
,W/WeatherTimeKeeper( 1233): [refreshWeatherData] no weather data
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): ,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,D/ContactMessageStore( 1560): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1560): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1560): sku_id=118
D/ContactMessageStore( 1560): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1560): start background delete task...
,D/ContactMessageStore( 1560): size: 0 , 0
,D/ContactMessageStore( 1560): Background delete complete
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(38da437c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
I/BatteryService(  989): n_update end
D/PMS     (  989): releaseWL(38da437c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  989): updateBatteryInfo
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/NotificationService(  989): plugged=true pluggin=true
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/PMS     (  989): runPSCheck
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  989): Checking...
D/UsbnetService(  989): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  989): >> updateStatus
D/WifiController(  989): handleMessage: E msg.what=155652
D/WifiController(  989): battery changed pluggedType: 2
,D/WifiController(  989): processMsg: DeviceActiveState
D/WifiController(  989): processMsg: StaEnabledState
,D/PowerUI ( 1233): closing low battery warning: level=100
D/WifiController(  989): processMsg: DefaultState
D/PowerUI ( 1233): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  989): handleMessage: X
D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
,I/IntentController( 1233): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1233): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/bt-btm  ( 3228): Received oneshot timer event complete
D/PMS     (  989): acquireWL(2366b405): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000}
I/bt-btm  ( 3228): btm_ble_timeout
V/AlarmManager(  989): sending alarm PendingIntent{516ba3b: PendingIntentRecord{1c0d7558 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=392797, Int=0
I/bt-btm  ( 3228): btm_gen_resolvable_private_addr
V/AlarmManager(  989): sending alarm PendingIntent{1e725c5a: PendingIntentRecord{1670ee8b com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941972, Int=0
D/PMS     (  989): acquireWL(1461b68): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3228 1002 null
,D/bt-btm  ( 3228): btm_ble_rand_enc_complete
I/bt-btm  ( 3228): btm_gen_resolve_paddr_low
D/bt-smp  ( 3228): smp_encrypt_data
W/bt-smp  ( 3228): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3228): Plain text(LSB ~ MSB) = 8c d4 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3228): Encrypted text(LSB ~ MSB) = d3 dd 8d f1 aa 3f ae 9c a8 63 5d 70 b4 c4 84 cf 
I/bt-btm  ( 3228): btm_gen_resolve_paddr_cmpl
,W/bt-btm  ( 3228): Stopping oneshot timer
,D/bt-btm  ( 3228): Starting oneshot timer type:103 timeout:900s
D/WeatherUtility( 1233): Weather sync is On
W/WeatherTimeKeeper( 1233): [refreshWeatherData] no weather data
,D/PMS     (  989): releaseWL(2366b405): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  989): releaseWL(1461b68): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/ActivityManager(  989): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7187 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/PMS     (  989): acquireWL(1a38b81): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10072}
V/AlarmManager(  989): sending alarm PendingIntent{2de9e426: PendingIntentRecord{2634718a com.android.vending startService}}, i=null, t=0, cnt=1, w=1448626791197, Int=0,
,I/ActivityManager(  989): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7201 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  989): sending alarm PendingIntent{2b7de867: PendingIntentRecord{8158614 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1448626811614, Int=0
,V/AlarmManager(  989): sending alarm PendingIntent{14716673: PendingIntentRecord{3171d930 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805953, Int=0
,V/AlarmManager(  989): sending alarm PendingIntent{77c5ebd: PendingIntentRecord{35614ed4 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448627136009, Int=0,
W/ContextImpl( 6848): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  989): releaseWL(1a38b81): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 6848): MY_DEBUG = false
,D/PowerUsageService( 6848): repeat time = 1448628036094,
,I/PackageManager(  989):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7187, uid=10072, userID:0
,W/global  ( 7187): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7187): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 7187): [apache-http] Connection GC has been deprecated!
,I/PowerUsageList:PowerUsageHelper( 6848): PowerProfile::POWER_SCREEN_FULL = 154.8,
,W/global  ( 7187): [apache-http] Connection GC has been deprecated!
,D/PowerUsageList:BatterySipperExt( 6848): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6848): gen(), null == sipper.uidObj, userId = 0
D/PowerUsageList:BatterySipperExt( 6848): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 7237): Error opening trace file: Permission denied (13)
I/dex2oat ( 7237): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7237): dex2oat: override thread count:4
,D/Finsky  ( 7187): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,D/PowerUsageService( 6848): calcPower(), no data,
,I/ActivityManager(  989): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7251 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7187): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7187): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     (  406): Explicit concurrent mark sweep GC freed 8635(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 282us total 35.273ms
,I/PackageManager(  989):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7187, uid=10072, userID:0
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 267us total 32.951ms,
,D/Finsky  ( 7187): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
W/ResourcesManager( 7251): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7251): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 200us total 24.727ms
,D/Finsky  ( 7187): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7187): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7187): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MultiDex( 7251): VM with version 2.1.0 has multidex support,
I/MultiDex( 7251): install
I/MultiDex( 7251): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 7187): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,V/JNIHelp ( 7251): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 7187): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ActivityThread( 7251): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7251): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a7ce9b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7251): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1979): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1979): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4572): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WearableService( 5895): callingUid 10024, callindPid: 5895,
I/PackageManager(  989):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4572, uid=10024, userID:0
V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1867): [131] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4572): Restart initialization of location
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 7187): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/Finsky  ( 7187): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/dex2oat ( 7237): dex2oat took 678.485ms (threads: 4)
,I/PushClient( 7201): ApplicationMonitor {3608a4cb}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 7201): ApplicationMonitor {3608a4cb}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 7201): ApplicationMonitor {3608a4cb}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 7201): ApplicationMonitor {3608a4cb}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7201): ApplicationMonitor {3608a4cb}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 7201): ApplicationMonitor {3608a4cb}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 7201): ApplicationMonitor {3608a4cb}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 7201): ApplicationMonitor {3608a4cb}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7201): ApplicationMonitor {3608a4cb}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 7201): PnsModel {dda039a}: update(): Update registration caused by: alarm
,I/PushClient( 7201): PnsConfigModel {33131f9}: <init>(): Use dm-client for provisioning.
,W/System.err( 7201): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 7201): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 7201): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7201): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,E/AndroidHttpClient( 7187): Leak found,
E/AndroidHttpClient( 7187): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 7187): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 7187): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 7187): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 7187): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 7187): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 7187): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 7187): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 7187): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 7187): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 7187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 7187): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 7187): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 7187): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 7187): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 7187): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 7187): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  989): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7292 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7292): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7292 dbg=false s=true
,I/DeviceManagement( 7292): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 7292): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7292): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 7292): WorkflowService: Starting workflow service,
,I/DeviceManagement( 7292): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@dda039a] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 7292): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,D/PMS     (  989): acquireWL(1357211f): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10072}
,V/AlarmManager(  989): sending alarm PendingIntent{52abc6c: PendingIntentRecord{2634718a com.android.vending startService}}, i=null, t=0, cnt=1, w=1448627137294, Int=0
,D/Finsky  ( 7187): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  989): releaseWL(1357211f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
I/DeviceManagement( 7292): ModelRegistry: Loading model meta data from resources...
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DeviceManagement( 7292): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7292): SessionStateController: Checking invariants...
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7187): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7187): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7187): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7187): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7187): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 7187): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2),
,I/art     (  989): Explicit concurrent mark sweep GC freed 22831(1100KB) AllocSpace objects, 3(628KB) LOS objects, 33% free, 16MB/25MB, paused 1.875ms total 152.966ms
,I/DeviceManagement( 7292): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
D/DeviceConnectionService( 1867): client connected with version: 7571000
,I/DeviceManagement( 7292): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7292): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7292): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@dda039a],
,I/DeviceManagement( 7292): WorkflowService: Stopping workflow service,
,I/ActivityManager(  989): Killing 6753:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  989): killProcessQuiet, pid=6753
,D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6753
,I/PushClient( 7201): PnsModel {dda039a}: update(): The registration record has not expired yet. No need to update.,
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  989): Killing 6906:com.htc.calendar/u0a10 (adj 15): empty #17,
D/Process (  989): killProcessQuiet, pid=6906
,D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/ActivityManager(  989): Recipient 6906
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7187): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7187): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7187): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7187): [1] DailyHygiene.reschedule: Scheduling new run in 86 minutes (failures=3)
,D/DeviceConnectionService( 1867): client connected with version: 7571000
,D/Process (  989): killProcessQuiet, pid=6104
I/ActivityManager(  989): Killing 6104:com.android.settings/1000 (adj 15): empty #17
,D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6104
,D/WifiService(  989): Client connection lost with reason: 4
,D/Process (  989): killProcessQuiet, pid=6882,
I/ActivityManager(  989): Killing 6882:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  989): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  989): Recipient 6882,
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(167a3383): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10072},
,V/AlarmManager(  989): sending alarm PendingIntent{280c0900: PendingIntentRecord{6d7fa46 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448627152545, Int=0
D/PMS     (  989): releaseWL(167a3383): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 7187): [732] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 7187): [1] 5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(2dde0539): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000}
V/AlarmManager(  989): sending alarm PendingIntent{516ba3b: PendingIntentRecord{1c0d7558 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=992796, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{3035c77e: PendingIntentRecord{332284df com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448627181519, Int=0
,D/SmartSyncUtils( 6848): isEpsOn(), nState = 0
,D/PMS     (  989): acquireWL(2da8b52c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6848 1000 null
,D/PMS     (  989): releaseWL(2dde0539): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1233): Weather sync is On
,W/WeatherTimeKeeper( 1233): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 6848): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6848): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6848): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6848): SettingOnTime = 1448690400000, randomSettingOnTime = 1448688333000,
D/SmartSyncScreenOnOffTimeReceiver( 6848): SettingOffTime = 1448668800000, randomSettingOffTime = 1448671749000
,D/SmartSyncScreenOnOffTimeReceiver( 6848): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6848): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6848): bNightModeTurnOffOnce = false
,D/PMS     (  989): releaseWL(2da8b52c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/UsageStatsService(  989): User[0] Flushing usage stats to disk
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1351): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1233): reapply : com.google.android.gms 2 40
,W/GLSActivity( 1979): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1979): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1979): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1979): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1979): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1979): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1979): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 7187): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 7187): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7187): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7187): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7187): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7187): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7187): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 7187): Ignoring header User-Agent because its value was null.
,D/libc    ( 7187): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7187): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7187): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7187): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7187): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7187): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 7187): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,I/RemoteViews( 1233): reapply : com.google.android.gms 2 40
D/DotMatrix( 1351): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1979): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1979): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1979): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1979): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1979): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1979): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1979): 	at android.os.Binder.execTransact(Binder.java:454),
,E/PlayEventLogger( 7187): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7187): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7187): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7187): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7187): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7187): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69),
E/PlayEventLogger( 7187): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 7187): Ignoring header User-Agent because its value was null.
D/libc    ( 7187): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 7187): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7187): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 7187): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7187): [NET] android_getaddrinfo_proxy+
D/libc    ( 7187): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 7187): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(20f00760): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 989 1000 WorkSource{1000}
,V/AlarmManager(  989): sending alarm PendingIntent{516ba3b: PendingIntentRecord{1c0d7558 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1052797, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{3cb29419: PendingIntentRecord{257edcde com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1841984, Int=0
I/bt-btm  ( 3228): Received oneshot timer event complete
I/bt-btm  ( 3228): btm_ble_timeout
,I/bt-btm  ( 3228): btm_gen_resolvable_private_addr
,D/PMS     (  989): acquireWL(1003debf): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3228 1002 null
,D/bt-btm  ( 3228): btm_ble_rand_enc_complete,
I/bt-btm  ( 3228): btm_gen_resolve_paddr_low
D/bt-smp  ( 3228): smp_encrypt_data
W/bt-smp  ( 3228): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3228): Plain text(LSB ~ MSB) = 92 51 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3228): Encrypted text(LSB ~ MSB) = 3b 16 76 3a 46 2a 10 e8 3b a4 5b c7 72 10 fc 33 
I/bt-btm  ( 3228): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3228): Stopping oneshot timer
D/bt-btm  ( 3228): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  989): Prepared write state in 24ms,
,D/WeatherUtility( 1233): Weather sync is On
D/PMS     (  989): releaseWL(20f00760): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1233): [refreshWeatherData] no weather data
,I/ProcessStatsService(  989): Pruning old procstats: /data/system/procstats/state-2015-11-26-11-38-56.bin,
,D/PMS     (  989): releaseWL(1003debf): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): ,
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(63e398c): PARTIAL_WAKE_LOCK  *alarm* 0x1 989 1000 WorkSource{10024}
V/AlarmManager(  989): sending alarm PendingIntent{2c4f58d5: PendingIntentRecord{1497e8ea com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448627764760, Int=1800000
V/AlarmManager(  989): sending alarm PendingIntent{1ca1a7db: PendingIntentRecord{205b6278 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1854603, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{14716673: PendingIntentRecord{3171d930 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1688887, Int=0
V/AlarmManager(  989): sending alarm PendingIntent{110edbd0: PendingIntentRecord{1d2d27c9 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825883, Int=1800000
V/AlarmManager(  989): sending alarm PendingIntent{3fb9ad51: PendingIntentRecord{35614ed4 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448628036094, Int=0
,D/PMS     (  989): acquireWL(1283a9b6): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4572 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): acquireWL(31202e24): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4572 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): releaseWL(1283a9b6): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  989): acquireWL(1098ab42): PARTIAL_WAKE_LOCK  NetworkStats 0x1 989 1000 null,
,D/PMS     (  989): releaseWL(1098ab42): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  989): updateNetworkEnabledLocked()
V/NetworkPolicy(  989): updateNotificationsLocked()
,W/ContextImpl( 6848): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  989): releaseWL(63e398c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6848): MY_DEBUG = false
,D/PowerUsageService( 6848): repeat time = 1448628936190
,I/EventLogService( 4572): Aggregate from 1448626266927 (log), 1448625964692 (data)
,D/LocationManagerService(  989): getAllProviders()=[passive, gps, network]
,D/PMS     (  989): releaseWL(31202e24): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 1979): Explicit concurrent mark sweep GC freed 26120(1521KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 1.202ms total 82.027ms,
,I/PowerUsageList:PowerUsageHelper( 6848): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PowerUsageList:BatterySipperExt( 6848): gen(), null == sipper.uidObj, userId = 0
D/PowerUsageList:BatterySipperExt( 6848): gen(), null == sipper.uidObj, userId = 0,
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PowerUsageList:BatterySipperExt( 6848): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 6848): calcPower(), no data
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1979): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1979): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1979): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1979): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1979): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1979): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1979): 	,at com.google.android.gms.auth.p.e(SourceFile:1268),
,W/GLSActivity( 1979): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1979): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1979): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1979): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1979): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1351): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1351): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1233): reapply : com.google.android.gms 3 40
E/PlayEventLogger( 7187): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7187): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7187): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7187): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7187): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7187): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7187): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 7187): Ignoring header User-Agent because its value was null.
D/libc    ( 7187): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 7187): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7187): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7187): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7187): [NET] android_getaddrinfo_proxy+
D/libc    ( 7187): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 7187): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,D/PMS     (  989): acquireWL(25100c97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
I/BatteryService(  989): n_update end
D/PMS     (  989): releaseWL(25100c97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1233): closing low battery warning: level=100
D/UsbnetService(  989): BroadcastReceiver::onReceive+
D/NotificationService(  989): plugged=true pluggin=true
D/UsbnetService(  989): onReceive BATTERY_CHANGED
D/WifiController(  989): battery changed pluggedType: 2
D/UsbnetService(  989):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1233): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  989): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  989): updateBatteryInfo
I/IntentController( 1233): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  989): runPSCheck
D/WifiController(  989): handleMessage: E msg.what=155652
D/HtcPowerSaver(  989): Checking...
D/WifiController(  989): processMsg: DeviceActiveState
I/HtcPowerSaver(  989): >> updateStatus
D/WifiController(  989): processMsg: StaEnabledState
D/WifiController(  989): processMsg: DefaultState
D/WifiController(  989): handleMessage: X
D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
D/DotMatrix( 1351): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1351): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  989): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  989): << updateStatus
,I/BatteryController( 1233): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6952): 
,TIME-OUT KILL (timeout was 1800000ms)
```
