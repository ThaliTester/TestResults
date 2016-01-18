#### Test 5635717154d1b6f_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Process (  922): killProcessQuiet, pid=5621
--------- beginning of system
I/ActivityManager(  922): Killing 5621:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  922): Recipient 5621
,E/cutils-trace( 6686): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6686): ====startRecUseTime====
D/htc.customization.log.level( 6686):  is 
W/CustomizationLogLevel( 6686): Level value is invalid, use default level 2
D/CustomizationManager( 6686):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 6686): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6686): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6686): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6686): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6686): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6686): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6686): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6686): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6686): Parsing tag category name = system
I/CustomizationCIDLoader( 6686): Parsing tag category name = application
I/CustomizationCIDLoader( 6686): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6686): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6686): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6686): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6686): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6686): add string-array item, value = 42507
I/CustomizationCIDLoader( 6686): add string-array item, value = 21902
I/CustomizationCIDLoader( 6686): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6686): add string-array item, value = 23420
I/CustomizationCIDLoader( 6686): add string-array item, value = 22299
I/CustomizationCIDLoader( 6686): add string-array item, value = 24002
I/CustomizationCIDLoader( 6686): add string-array item, value = 23210
I/CustomizationCIDLoader( 6686): add string-array item, value = 23205
I/CustomizationCIDLoader( 6686): add string-array item, value = 23806
I/CustomizationCIDLoader( 6686): add string-array item, value = 23430
I/CustomizationCIDLoader( 6686): add string-array item, value = 23408
I/CustomizationCIDLoader( 6686): add string-array item, value = 27205
I/CustomizationCIDLoader( 6686): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6686): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6686):  Read CID file spent 0.096 (s)
D/CustomizationManager( 6686):  All configurations done spent 0.097 (s)
I/ActivityManager(  922): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6686 on display 0
D/PMS     (  922): acquireHCC(1381c6b6): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 922 1000 null
D/PMS     (  922): acquireHCC(3f913fb7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 922 1000 null
W/asset   (  922): Copying FileAsset 0x559ca4e300 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  922): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6704 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  922): Display changed displayId=0
D/DotMatrix( 1333): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1333): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6704): Copying FileAsset 0xabf97ac0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1625): [trimMemory] 20
I/WebViewFactory( 6704): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6704): Time to load native libraries: 10 ms (timestamps 192-202)
I/LibraryLoader( 6704): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6704): Binding Chromium to main looper Looper (main, tid 1) {39f19534}
I/LibraryLoader( 6704): Expected native library version number "",actual native library version number ""
I/chromium( 6704): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6704): Initializing chromium process, singleProcess=true
W/art     ( 6704): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6704): ApplicationContext is null in ApplicationStatus
W/chromium( 6704): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6704): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6704): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6704): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6704): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6704): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6704): Local Branch: 
I/Adreno-EGL( 6704): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6704): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6704):                  d74aa161a12b9c6fc6332151
W/System.err(  922): java.lang.Throwable: stack dump
W/System.err(  922): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  922): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  922): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  922): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  922): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  922): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39e146cb:true
D/BluetoothAdapter( 6704): 531419296: getState(). Returning 12
W/art     ( 6704): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6704): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6704): CordovaWebView is running on device made by: HTC
W/art     ( 6704): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6704): Attempt to remove local handle scope entry from IRT, ignoring
W/HtcSystemUPManager(  922): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/chromium( 6704): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/StatusBarManagerService(  922): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  922): hiding MENU key
D/StatusBarManagerService(  922): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  922): hiding MENU key
D/FindExtension( 6704): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6704): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@108294ce, mServedView=org.apache.cordova.engine.SystemWebView{36444fef VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2d4b0afc
I/InputMethodManagerService(  922): Disable input method client, pid=1625
D/StatusBarManagerService(  922): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
W/IInputConnectionWrapper( 6704): reportFullscreenMode on inactive InputConnection
I/ActivityManager(  922): Displayed com.test.thalitest/.MainActivity: +645ms (total +693ms)
W/BindingManager( 6704): Cannot call determinedVisibility() - never saw a connection for the pid: 6704
D/JsMessageQueue( 6704): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6704): JniHelper::setJavaVM(0xaae2c8f8), pthread_self() = -1407900352
D/JX-Cordova( 6704): jxcore cordova android initializing
W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2
,W/jxcore-log( 6704): Initializing JXcore engine,
W/jxcore-log( 6704): JXcore engine is ready
,W/jxcore-log( 6704): Starting JXcore engine
,D/PMS     (  922): releaseHCC(1381c6b6): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  922): releaseHCC(3f913fb7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null,
,W/jxcore-log( 6704): Platform android
W/jxcore-log( 6704): 
W/jxcore-log( 6704): Process ARCH arm,
W/jxcore-log( 6704): 
,I/jxcore-log( 6704): JXcore Cordova bridge is ready!,
I/jxcore-log( 6704): 
W/jxcore-log( 6704): JXcore engine is started
I/Choreographer( 6704): Skipped 105 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 6704): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6704): Toggling radios to true
I/jxcore-log( 6704): 
,D/BluetoothAdapter( 6704): enable(): BT is already enabled..!
,D/WifiService(  922): New client listening to asynchronous messages
,E/WifiTrafficPoller(  922): ADD_CLIENT: 8
D/WifiManager( 6704): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/WifiService(  922): setWifiEnabled: true pid=6704, uid=10366
E/WifiService(  922): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  922): isSprintWifiRestricted(): false
I/WifiService(  922): isMdmWifiRestricted(): false
W/Settings:Agent(  922): MONITOR_LOG
W/Settings:Agent(  922): name: wifi_on
W/Settings:Agent(  922): value: 2
W/Settings:Agent(  922): >> traceCallingStack()
W/Settings:Agent(  922): Process.myPid(): 922
W/Settings:Agent(  922): Process.myTid(): 1162
W/Settings:Agent(  922): Process.myUid(): 1000
W/Settings:Agent(  922): 
W/Settings:Agent(  922): 
W/System.err(  922): java.lang.Throwable: stack dump
,W/System.err(  922): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  922): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  922): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  922): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  922): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  922): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  922): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  922): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  922): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  922): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  922): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  922): 
W/Settings:Agent(  922): << traceCallingStack(): 14(ms)
D/WifiController(  922): handleMessage: E msg.what=155656
D/WifiController(  922): processMsg: DeviceActiveState
D/WifiController(  922): processMsg: StaEnabledState
D/WifiController(  922): handleMessage: X
D/WifiManager( 6704): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  922): handleMessage: E msg.what=131145
D/WifiManager( 6704): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  922): processMsg: ConnectedState
E/WifiStateMachine(  922):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/jxcore-log( 6704): Radios toggled
I/jxcore-log( 6704): 
D/wpa_supplicant( 1325): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1325): wlan0: Cancelling scan request
D/wpa_supplicant( 1325): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1325): TDLS: Tear down peers
D/wpa_supplicant( 1325): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6704): My device name is: HTC-HTC One M8s
I/jxcore-log( 6704): 
,D/wpa_supplicant( 1325): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1325): wlan0: Deauthentication notification
D/wpa_supplicant( 1325): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1325): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1325): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1325): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1325): enter disconnect check
I/wpa_supplicant( 1325): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1325): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1325): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  922): interfaceLinkStateChanged wlan0, false
D/Tethering(  922): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/PMS     (  922): acquireWL(8f7f384): PARTIAL_WAKE_LOCK  NetworkStats 0x1 922 1000 null
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  922): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  922): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  922): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  922): TetherInterfaceSM: wlan0: exit InitialState
E/WifiMonitor(  922): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
V/Tethering(  922): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  922): interfaceLinkStateChanged wlan0, false
D/Tethering(  922): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  922): sendTetherStateChangedBroadcast 0, 0, 0
D/wpa_supplicant( 1325): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1325): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55b7a6df88 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 1325):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1325): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1325): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1325): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1325): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1325): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1325): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1325): wlan0: State: DISCONNECTED -> DISCONNECTED
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbDeviceManager(  922): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1325): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=0
D/WifiDisplayAdapter(  922): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  922):     Client/Owner: Client
D/WifiDisplayAdapter(  922):     GroupId: 
D/WifiDisplayAdapter(  922):     Passphrase: 
D/WifiDisplayAdapter(  922):     SessionId: 0
D/WifiDisplayAdapter(  922):     IP Address: }
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1325): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/WifiMonitor(  922): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/wpa_supplicant( 1325): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1325): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  922): transitionTo: destState=DisconnectingState
D/UsbnetService(  922): BroadcastReceiver::onReceive+
E/WifiStateMachine(  922): handleMessage: new destination call exit/enter
E/WifiStateMachine(  922): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  922): invokeExitMethods: ConnectedState
E/WifiStateMachine(  922): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  922): release()
E/WifiStateMachine(  922): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  922): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  922): invokeExitMethods: L2ConnectedState
,D/UsbnetService(  922): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  922): BroadcastReceiver::onReceive-
E/WifiStateMachine(  922): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  922): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  922): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1325): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1325): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1325): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/TetherSettings( 5950): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5950): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5950): Cust_ConnectToPC   : Modem_Link>false
D/WifiP2pService(  922): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/        ( 5950): Cust_ConnectToPC   : spcsc>false
D/WifiP2pService(  922): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/        ( 5950): Cust_ConnectToPC   : IPT>true
D/        ( 5950): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5950): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5950): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5950): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 5950): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/wpa_supplicant( 1325): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1325): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  922): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1325): Power_Mode_Type mode = 0
I/wpa_supplicant( 1325): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  922): setDhcpActive: false
V/NativeCrypto( 1793): Read error: ssl=0x559c87df70: I/O error during system call, Connection timed out
W/ContextImpl( 5950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  922): acquireWL(39dd176d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
V/NetworkPolicy(  922): updateNetworkEnabledLocked()
E/WifiStateMachine(  922): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
V/NetworkPolicy(  922): updateNotificationsLocked()
E/WifiStateMachine(  922): setDetailed state send new extra info<unknown ssid>
D/PMS     (  922): releaseWL(8f7f384): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  922): NetworkAgent != null
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 13
V/NetworkPolicy(  922): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiDataStallTracker(  922): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  922): stopDataStallAlarm 
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  922): ENABLE_DATA_MONITOR_POLL false Token 3
V/NativeCrypto( 1793): SSL shutdown failed: ssl=0x559c87df70: I/O error during system call, Broken pipe
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  922): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
,D/wpa_supplicant( 1325): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1325): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
I/SmartNS_Utility( 5950): setISNotification
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 15
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
D/wpa_supplicant( 1325): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1325): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1325): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1325): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  922): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  922): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  922): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  922):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
,E/WifiStateMachine(  922): Start Disconnecting Watchdog 1
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=131146
E/WifiStateMachine(  922): processMsg: DisconnectingState
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  922): processMsg: ConnectModeState
,E/WifiStateMachine(  922):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/SmartNS_Utility( 5950): usb_cable_connect = 1
D/SmartNS_Utility( 5950): usb_denied = 0
,I/SmartNS_PSService( 5950): usb notificaiton:true
,D/ConnectivityService(  922): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1325): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1325): Fast associate: Old scan results
D/wpa_supplicant( 1325): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1325): wpa_supplicant_scan enter
D/wpa_supplicant( 1325): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1325): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1325): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1325): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1325): WPS:  * Request Type
D/wpa_supplicant( 1325): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1325): WPS:  * UUID-E
D/wpa_supplicant( 1325): WPS:  * Primary Device Type
D/wpa_supplicant( 1325): WPS:  * RF Bands (3)
D/wpa_supplicant( 1325): WPS:  * Association State
D/wpa_supplicant( 1325): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1325): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1325): WPS:  * Manufacturer
D/wpa_supplicant( 1325): WPS:  * Model Name
D/wpa_supplicant( 1325): WPS:  * Model Number
D/wpa_supplicant( 1325): WPS:  * Device Name
D/wpa_supplicant( 1325): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1325): P2P: * P2P IE header
D/wpa_supplicant( 1325): P2P: * Capability dev=25 group=00
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1325): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  922): handleMessage: X
D/wpa_supplicant( 1325): wlan0: Add radio work 'scan'@0x55b7a50aa0
D/wpa_supplicant( 1325): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  922): handleMessage: E msg.what=147460
E/WifiStateMachine(  922): processMsg: DisconnectingState
D/wpa_supplicant( 1325): wlan0: Starting radio work 'scan'@0x55b7a50aa0 after 0.000057 second wait
,D/wpa_supplicant( 1325): wlan0: nl80211: scan request
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): Scan requested (ret=0) - scan timeout 30 seconds
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1325): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1325): wlan0: nl80211: Scan trigger
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1325): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1325): wlan0: Own scan request started a scan in 0.000226 seconds
,I/wpa_supplicant( 1325): wlan0: CTRL-EVENT-SCAN-STARTED 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Forcing reevaluation
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  922): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Validated
E/WifiStateMachine(  922):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132812
E/WifiStateMachine(  922): processMsg: ConnectModeState
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  922): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
D/PMS     (  922): releaseWL(39dd176d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  922): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  922):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132812
E/WifiMonitor(  922): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  922): ConnectModeState: Network connection lost 
E/WifiStateMachine(  922): transitionTo: destState=DisconnectedState
,E/WifiStateMachine(  922): handleMessage: new destination call exit/enter
E/WifiStateMachine(  922): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  922): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  922): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  922): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  922): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  922): DisconnectedState call setCountryCode()
E/WifiStateMachine(  922):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1325): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1325): wlan0: Cancelling scan request
I/ActionCombine( 5950): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 5950): usb_cable_connect = 1
,D/SmartNS_Utility( 5950): usb_denied = 0
I/SmartNS_PSService( 5950): usb notificaiton:true
,D/wpa_supplicant( 1325): wlan0: nl80211: sched_scan request
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_NSReceiver( 5950): Tethered state change:false isNSOpening:false
,I/RemoteViews( 1216): reapply : com.android.settings 1 36
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1216): reapply : com.android.settings 1 36,
,I/QuickSettingWifi( 1216): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
,D/wpa_supplicant( 1325): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1325): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1325): wlan0: nl80211: Sched scan started
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:2
E/WifiStateMachine(  922): handleMessage: X
,E/WifiStateMachine(  922): handleMessage: E msg.what=131101
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine(  922): processMsg: DefaultState
E/WifiStateMachine(  922):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  922): [MLHD] enter handleMediaLinkEvent DefaultState,
D/WifiStateMachine(  922): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=147462
D/wpa_supplicant( 1325): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
E/WifiStateMachine(  922): processMsg: DisconnectedState
D/wpa_supplicant( 1325): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1325): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1325): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1325): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1325): wlan0: Scan completed in 0.042237 seconds
D/wpa_supplicant( 1325): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1325): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
D/wpa_supplicant( 1325): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1325): BSS: last_scan_res_used=1/32
E/WifiStateMachine(  922):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=132853  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/wpa_supplicant( 1325): wlan0: New scan results available (own=1 ext=0)
E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  922): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  922): processMsg: ConnectModeState
D/wpa_supplicant( 1325): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1325): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1325): wlan0: Radio work 'scan'@0x55b7a50aa0 done in 0.043401 seconds
D/wpa_supplicant( 1325): wlan0: Selecting BSS from priority group 526
D/wpa_supplicant( 1325): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-61 wps
D/wpa_supplicant( 1325): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1325): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1325): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1325):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1325): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
E/WifiStateMachine(  922):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=132854  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/wpa_supplicant( 1325): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55b7a6fc00  current_ssid=0x0
W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1325): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
E/WifiStateMachine(  922): handleMessage: X
D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/WifiNetworkAgent(  922): NetworkAgent: NetworkAgent channel lost
,D/wpa_supplicant( 1325): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
E/WifiStateMachine(  922): handleMessage: E msg.what=147462
E/WifiStateMachine(  922): processMsg: DisconnectedState
D/wpa_supplicant( 1325): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1325): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1325): wlan0: Add radio work 'connect'@0x55b7a50aa0
D/wpa_supplicant( 1325): wlan0: First radio work item in the queue - schedule start immediately
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1325): wlan0: Starting radio work 'connect'@0x55b7a50aa0 after 0.000064 second wait
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 1325): check if in concurrent case
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1325): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  922):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=132854  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  922): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  922): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  922): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  922): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=38 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  922): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  922): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiStateMachine(  922): NetworkAgent == null
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=39 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  922): processMsg: ConnectModeState
D/wpa_supplicant( 1325): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1325): wlan0: Cancelling sched scan
D/wpa_supplicant( 1325): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1325): wlan0: Cancelling scan request
D/WifiService(  922): New client listening to asynchronous messages
D/wpa_supplicant( 1325): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1325): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1325): wpas_start_assoc_cb, 1910
E/WifiStateMachine(  922):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=132856  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/wpa_supplicant( 1325): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1325): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1325): RSN: PMKSA cache search - network_ctx=0x55b7a6fc00 try_opportunistic=0
D/wpa_supplicant( 1325): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1325): wlan0: RSN: using IEEE 802.11i/D9.0
E/WifiStateMachine(  922): handleMessage: X
D/wpa_supplicant( 1325): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1325): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1325): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1325): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1325): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1325): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1325): wlan0: WPA: not using MGMT group cipher
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/wpa_supplicant( 1325): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1325): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1325): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1325): nl80211: Unsubscribe mgmt frames handle 0x888888dd3f2e7989 (mode change)
D/wpa_supplicant( 1325): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b7a6f100
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=0104
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=040a
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=040b
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  922): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=040c
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=040d
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=090a
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=090b
D/WifiMonitor(  922): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=090c
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=090d
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=0409506f9a09
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=7f506f9a09
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=0801
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=040e
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=06
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=0a07
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=0a11
D/wpa_supplicant( 1325): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b7a6f100 match=0a1a
D/wpa_supplicant( 1325): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1325):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325):   * freq=2412
D/wpa_supplicant( 1325):   * freq_hint=2412
D/wpa_supplicant( 1325):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1325):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1325):   * WPA Versions 0x2
D/wpa_supplicant( 1325):   * pairwise=0xfac04
D/wpa_supplicant( 1325):   * group=0xfac04
D/wpa_supplicant( 1325):   * akm=0xfac02
D/wpa_supplicant( 1325):   * Auth Type 0
D/wpa_supplicant( 1325): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55b7a6fc3a
D/wpa_supplicant( 1325): nl80211: Connect request send successfully
D/wpa_supplicant( 1325): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1325): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1325): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1325): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1325): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1325): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1325): wlan0: Event SCHED_SCAN_STOPPED (38) received
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922): handleMessage: E msg.what=147461
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:2103 bcn=0
E/WifiStateMachine(  922): processMsg: ConnectModeState
D/WISPrService( 5950): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  922):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:2103 bcn=0
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:2103 bcn=0
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 dur:2103 bcn=0
D/WifiStateMachine(  922): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1325): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  922): [1,453,132,583,337 ms] noteScanEnd no scan source
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
D/wpa_supplicant( 1325): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  922): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3279844c sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  922): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  922): NG700 c0:ff:d4:d3:aa:48 rssi=-61 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  922): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  922): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  922):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-61 freq=2412
E/WifiAutoJoinController (  922): Gonzos 38:f8:89:11:e9:11 rssi=-79 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiAutoJoinController (  922): 01ABC c2:ff:d4:d3:aa:48 rssi=-61 cap [WPA2-PSK-CCMP][ESS] is not scored
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiAutoJoinController (  922): UPC503894600 a0:c5:62:7a:49:97 rssi=-86 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  922): ageScanResultsOut delay 40000 size 5 now 1453132583339
E/WifiAutoJoinController (  922): newSupplicantResults size=5 known=1 true
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
E/WifiTrafficPoller(  922): ADD_CLIENT: 9
D/wpa_supplicant( 1325): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  922): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  922): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  922): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  922): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  922): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  922):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=131213
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState CMD_TARGET_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132870
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState CMD_TARGET_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132870
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState CMD_TARGET_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132870
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState CMD_TARGET_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132871
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=147462
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=132871  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  922): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  922): setDetailed state send new extra info0x
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  922): NetworkAgent == null
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiStateMachine(  922):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=132876  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=131131
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  922): processMsg: ConnectModeState
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  922): handleMessage: X
W/WISPrService( 5950): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5950): trigger connection
D/WISPrService( 5950): continue
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5950): start DataConnection
D/libc    ( 5950): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5950): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5950): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5950): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5950): [NET] android_getaddrinfo_proxy+
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5950): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  922): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/libc    (  401): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc    (  401): [NET] android_getaddrinfofornet-, err=7
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5950): [NET] android_getaddrinfo_proxy-, NODATA
D/ConnectivityService(  922): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  922): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  922): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Disconnected - quitting
D/ConnectivityService(  922): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  922): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  922):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  922): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/NetworkManagementService(  922): Removing idletimer
E/WifiStateMachine(  922): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/usbnet  (  922): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  922):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  922): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524292
I/SecurityController( 1216): onLost 100
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/PMS     (  922): acquireWL(3c9c4433): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 922 1000 null
D/FlexNetS( 6473): updateSvcAllowedInSettings:false
D/CSLegacyTypeTracker(  922): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  922): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  922): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/ConnectivityService(  922): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  922): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  922): acquireWL(1dc2c3f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 922 1000 null
E/ConnectivityService(  922): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/DATA_ICON( 1216): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
V/NetworkPolicy(  922): ensureActiveMobilePolicyLocked()
D/DATA_ICON( 1216): dataConnected: false/false
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkPolicy(  922): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  922): updateNetworkEnabledLocked()
V/NetworkPolicy(  922): updateIfacesLocked()
V/NetworkPolicy(  922): updateNotificationsLocked()
D/NetworkManagementService(  922): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
D/FlexNetS( 6473): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
D/libc    ( 5950): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5950): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  922): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6767 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WISPrService( 5950): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname,
D/PMS     (  922): releaseWL(1dc2c3f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  922): updateNetworkEnabledLocked()
V/NetworkPolicy(  922): updateNotificationsLocked()
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/FlexNetS( 6473): updateSvcAllowedInSettings:false,
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/FlexNetS( 6473): updateSvcAllowedInSettings:false
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri,
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/wpa_supplicant( 1325): Wireless event: cmd=0x8c02 len=271
D/UsbDeviceManager(  922): [USBNET] bCheckSuppFunc: cdc_network
I/wpa_supplicant( 1325): WEXT: Custom wireless event: 'BEACONIEs='
D/PMS     (  922): acquireWL(2172108): PARTIAL_WAKE_LOCK  NetworkStats 0x1 922 1000 null
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1325): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1325): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1325): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1325): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/wpa_supplicant( 1325): nl80211: Connect event
D/wpa_supplicant( 1325): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1325): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
,D/wpa_supplicant( 1325): wlan0: Event ASSOC (0) received
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/wpa_supplicant( 1325): wlan0: Association info event
D/wpa_supplicant( 1325): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 1325): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/Tethering(  922): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1325): wlan0: freq=2412 MHz
D/Tethering(  922): interfaceStatusChanged wlan0, false,
D/wpa_supplicant( 1325): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/PMS     (  922): releaseWL(2172108): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1325): wlan0: State: ASSOCIATING -> ASSOCIATED
,V/NetworkPolicy(  922): updateNetworkEnabledLocked()
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 0->0 (DORMANT)
V/NetworkPolicy(  922): updateNotificationsLocked()
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1325): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1325): wlan0: WPA: clearing AP WPA IE
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1325): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1325): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1325): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1325): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1325): TDLS: Remove peers on association
D/wpa_supplicant( 1325): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1325): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1325): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1325): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1325): EAPOL: enable timer tick
D/wpa_supplicant( 1325): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1325): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1325): wlan0: Cancelling scan request
I/wpa_supplicant( 1325): htc_wext_set_keepalive +
D/FlexNetS( 6473): updateSvcAllowedInSettings:false
I/wpa_supplicant( 1325): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1325): getPrivFuncNum +	
I/wpa_supplicant( 1325): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1325): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1325): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1325): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1325): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1325): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1325): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/Tethering(  922): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1325): wlan0:   key_length=16 key_data_length=0
D/Tethering(  922): interfaceStatusChanged wlan0, false
,D/wpa_supplicant( 1325):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1325):   key_nonce - hexdump(len=32): fc 88 15 3b 9f c7 14 33 4b 45 13 6d d3 7a d1 0f b0 9e 03 8b 58 4c f9 2d 10 f6 63 40 c8 eb 45 5c
D/wpa_supplicant( 1325):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1325): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1325): RSN: msg 1/4 key data - hexdump(len=0):
D/Tethering(  922): interfaceLinkStateChanged wlan0, false
D/Tethering(  922): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): WPA: Renewed SNonce - hexdump(len=32): 8f 9a 9c 5d ad 25 cd a0 74 cb de aa 1d cc 8d 37 0e 00 c2 7e 0b 18 c7 2b 9d 63 6b 00 e2 f5 c3 e2
D/Tethering(  922): interfaceLinkStateChanged wlan0, true
D/Tethering(  922): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1325): WPA: Nonce1 - hexdump(len=32): 8f 9a 9c 5d ad 25 cd a0 74 cb de aa 1d cc 8d 37 0e 00 c2 7e 0b 18 c7 2b 9d 63 6b 00 e2 f5 c3 e2
D/wpa_supplicant( 1325): WPA: Nonce2 - hexdump(len=32): fc 88 15 3b 9f c7 14 33 4b 45 13 6d d3 7a d1 0f b0 9e 03 8b 58 4c f9 2d 10 f6 63 40 c8 eb 45 5c
D/wpa_supplicant( 1325): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1325): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1325): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1325): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1325): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): WPA: Derived Key MIC - hexdump(len=16): 8d 17 6d 85 8e 20 30 4b 5d d1 d7 83 14 8e 88 83
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
V/Tethering(  922): TetherInterfaceSM: wlan0: enter InitialState
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  922): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  922): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  922): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=42 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  922): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  922): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  922): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  922): handleMessage: E msg.what=147462
E/WifiStateMachine(  922): processMsg: DisconnectedState
D/HTCRequest(  922): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2,412
D/HTCRequest(  922): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  922): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  922):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=132987  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  922): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/WifiMonitor(  922): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  922): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  922): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  922): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  922): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  922): processMsg: ConnectModeState
D/UsbnetService(  922): BroadcastReceiver::onReceive+
D/UsbnetService(  922): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  922): BroadcastReceiver::onReceive-
E/WifiStateMachine(  922):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=132988  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=147500
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  922): Enter handleAssociatedWithEvent
D/WifiStateMachine(  922): Associated
D/wpa_supplicant( 1325): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1325): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1325): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1325): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1325):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1325):   key_nonce - hexdump(len=32): fc 88 15 3b 9f c7 14 33 4b 45 13 6d d3 7a d1 0f b0 9e 03 8b 58 4c f9 2d 10 f6 63 40 c8 eb 45 5c
D/wpa_supplicant( 1325):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_rsc - hexdump(len=8): 36 34 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325):   key_mic - hexdump(len=16): c6 d6 09 0a 85 ad 7c e1 24 10 74 8a 3f 1b f7 75
D/wpa_supplicant( 1325): RSN: encrypted key data - hexdump(len=56): 73 7d bd df 6e ba 86 cc dc 60 04 a1 2b 7e 21 cb 1f 18 93 73 a3 74 32 a9 b8 d2 6a 51 41 1d 33 80 ...
D/wpa_supplicant( 1325): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1325): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1325): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1325): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 2f c5 ...
D/wpa_supplicant( 1325): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1325): WPA: GTK in EAPOL-Key - he,xdump(len=24): [REMOVED]
D/wpa_supplicant( 1325): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1325): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): WPA: Derived Key MIC - hexdump(len=16): 0b 65 17 39 69 a3 dd b1 49 b6 3f 8b 89 e7 af 0d
D/wpa_supplicant( 1325): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55b7a70390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1325): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1325):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1325): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1325): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1325): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1325): WPA: RSC - hexdump(len=6): 36 34 00 00 00 00
D/wpa_supplicant( 1325): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5578fc5e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1325): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1325): nl80211: KEY_SEQ - hexdump(len=6): 36 34 00 00 00 00
D/wpa_supplicant( 1325):    broadcast key
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  922): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiStateMachine(  922): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  922): Exit handleAssociatedWithEvent
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=147462
E/WifiStateMachine(  922): processMsg: DisconnectedState
I/wpa_supplicant( 1325): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1325): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1325): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1325): wlan0: Radio work 'connect'@0x55b7a50aa0 done in 0.138466 seconds
I/wpa_supplicant( 1325): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine(  922):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=132993  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 1325): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  922): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  922): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/wpa_supplicant( 1325): wlan0: Connect to SSID: NG700
D/WifiMonitor(  922): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 1325): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1325): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=45 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  922): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  922): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=46 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
I/wpa_supplicant( 1325): set send_ind_to_ndc = 0
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  922): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1325): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1325): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1325): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1325): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1325): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1325): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1325): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1325): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1325): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1325): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  922): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=48 dispatchEvent: Connect to SSID: NG700
D/wpa_supplicant( 1325): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1325): EAPOL authentication completed - result=SUCCESS
W/WifiMonitor(  922): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1325): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/WifiStateMachine(  922): NetworkAgent == null
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1325): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/HTCRequest(  922): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  922): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/Tethering(  922): interfaceLinkStateChanged wlan0, true
D/Tethering(  922): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  922): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 20
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=132997  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=131101
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: ConnectModeState
D/FlexNetS( 6473): updateSvcAllowedInSettings:false
E/WifiStateMachine(  922):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  922): processMsg: DefaultState
E/WifiStateMachine(  922):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  922): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  922): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  922): handleMessage: X
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922): handleMessage: E msg.what=147462
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=133007  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  922): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=133008  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=147459
E/WifiStateMachine(  922): processMsg: DisconnectedState
E/WifiStateMachine(  922):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133009
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=133009
E/WifiStateMachine(  922): Network connection established
D/WifiStateMachine(  922): fetchFrequency(), freq = 2412
E/WifiStateMachine(  922): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  922): NetworkAgent == null
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 22
E/WifiStateMachine(  922): transitionTo: destState=ObtainingIpState
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  922): handleMessage: new destination call exit/enter
E/WifiStateMachine(  922): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  922): invokeExitMethods: DisconnectedState
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1325): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  922): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  922): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  922):     Client/Owner: Client
D/WifiDisplayAdapter(  922):     GroupId: 
D/WifiDisplayAdapter(  922):     Passphrase: 
D/WifiDisplayAdapter(  922):     SessionId: 0
D/WifiDisplayAdapter(  922):     IP Address: }
E/WifiStateMachine(  922): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  922): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  922): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  922): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  922): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  922): NetworkAgent == null
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 23
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 24
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/FlexNetS( 6473): updateSvcAllowedInSettings:false
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/ConnectivityService(  922): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  922): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  922): Got NetworkAgent Messenger
E/WifiStateMachine(  922): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  922): NetworkAgent connected
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1325): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1325): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1325): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1325): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1325): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  922): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  922): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  922): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  922): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  922): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1325): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1325): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1325): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1325): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1325): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1325): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  922): Start Dhcp Watchdog 2
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=147462
E/WifiStateMachine(  922): processMsg: ObtainingIpState
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  922):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=133028  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=133029  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=133029  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  922): handleMessage: X
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  922): handleMessage: E msg.what=131212
E/WifiStateMachine(  922): processMsg: ObtainingIpState
E/WifiStateMachine(  922):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): processMsg: DriverStartedState
D/FlexNetS( 6473): updateSvcAllowedInSettings:false
E/WifiStateMachine(  922):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): processMsg: DefaultState
E/WifiStateMachine(  922):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  922): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=196612
E/WifiStateMachine(  922): processMsg: ObtainingIpState
E/WifiStateMachine(  922):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/ConnectivityService(  922): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  922): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  922): acquireWL(3ae3974c): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 922 1000 null
D/WifiDataStallTracker(  922): setDhcpActive: true
D/WifiStateMachine(  922): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WISPrService( 5950): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  922): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  922): do suspend false
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/WISPrService( 5950): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
,D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER POWERMODE 1'
D/WifiP2pService(  922): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c0b0330 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1325): INFO - Deny active power mode because already has gateway
D/WifiP2pService(  922): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c0b0330 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  922): Unexpected BatchedScanResults :null
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1325): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
E/WifiStateMachine(  922): noteBatchedScanstop()
D/wpa_supplicant( 1325): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1325): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1325): wlan0: Event DRIVER_GTK_REKEY (37) received
E/WifiStateMachine(  922): handleMessage: X
D/FlexNetS( 6473): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiService(  922): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
D/TetherSettings( 5950): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5950): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5950): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5950): Cust_ConnectToPC   : spcsc>false
D/        ( 5950): Cust_ConnectToPC   : IPT>true
D/        ( 5950): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5950): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5950): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5950): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5950): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5950): setISNotification
D/SmartNS_Utility( 5950): usb_cable_connect = 1
D/SmartNS_Utility( 5950): usb_denied = 0
I/SmartNS_PSService( 5950): usb notificaiton:true
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/SmartNS_Utility( 5950): usb_cable_connect = 1
D/SmartNS_Utility( 5950): usb_denied = 0
I/SmartNS_PSService( 5950): usb notificaiton:true
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  922): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1216): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 5950): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/FlexNetS( 6473): updateSvcAllowedInSettings:false
,I/RemoteViews( 1216): reapply : com.android.settings 2 36
,D/MdScPhnSt( 6767): [c2b.2.]  listen tmrbb8,
,D/FlexNetS( 6473): updateSvcAllowedInSettings:false
,D/FlexNetS( 6473): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6473): updateSvcAllowedInSettings:false
,D/FlexNetS( 6473): updateSvcAllowedInSettings:false
,D/FlexNetS( 6473): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6539): remove item 101 (p2d27in229) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6767): [c2b.2.] summary 118:p2 ignore
,D/Process (  922): killProcessQuiet, pid=6379
I/ActivityManager(  922): Killing 6379:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/dhcpcd  ( 6799): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6799): version 5.5.6 starting
,E/dhcpcd  ( 6799): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6799): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6799): autoip env[11]:autoip=DISABLE
,I/ActivityManager(  922): Recipient 6379,
,I/dhcpcd  ( 6799): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6799): wlan0: sending REQUEST (xid 0x12ae4b6b), next in 1.30 seconds
,D/wpa_supplicant( 1325): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1325): EAPOL: disable timer tick
,I/dhcpcd  ( 6799): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6799): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6799): autoip env[11]:autoip=DISABLE
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  922): handleMessage: E msg.what=131212
E/WifiStateMachine(  922): processMsg: ObtainingIpState
,E/WifiStateMachine(  922):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): processMsg: DefaultState
E/WifiStateMachine(  922):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  922): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  922): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  922): handleMessage: X
,D/ConnectivityService(  922): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/libc    (  922): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  922): handleMessage: E msg.what=131212
E/WifiStateMachine(  922): processMsg: ObtainingIpState
,E/WifiStateMachine(  922):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  922): processMsg: ConnectModeState
,E/WifiStateMachine(  922):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  922): processMsg: DefaultState
E/WifiStateMachine(  922):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  922): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  922): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  922): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  922): handleMessage: X
,I/dhcpcd  ( 6799): bind_interface: daemonise,
,D/libc    (  922): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  922): handleMessage: E msg.what=196613
,E/WifiStateMachine(  922): processMsg: ObtainingIpState
E/WifiStateMachine(  922):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  922): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER POWERMODE 0'
D/WifiP2pService(  922): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1325): Power_Mode_Type mode = 0
D/PMS     (  922): releaseWL(3ae3974c): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1325): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WifiP2pService(  922): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/ConnectivityService(  922): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1325): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  922): setDhcpActive: false
E/WifiStateMachine(  922): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  922): WifiStateMachine DHCP successful
E/WifiStateMachine(  922): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  922): link address 192.168.1.130/24
E/WifiStateMachine(  922): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  922): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  922): gateway: /192.168.1.1
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1325): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1325): WiFi gateway: 0x101a8c0
,I/wpa_supplicant( 1325): htc_wext_set_keepalive +
I/wpa_supplicant( 1325): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1325): getPrivFuncNum +	
I/wpa_supplicant( 1325): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1325): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1325): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1325): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1325): htc_wext_set_keepalive - ret = 0
,D/WifiStateMachine(  922): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=131210
E/WifiStateMachine(  922): processMsg: ObtainingIpState
,E/WifiStateMachine(  922):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1325): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1325): environment dirty rate=0 [6][0][0]
E/WifiStateMachine(  922): fetchRssiLinkSpeedAndFrequencyNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  922): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72
E/WifiConfigStore(  922): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  922): RSSI current: 3 new: -61, 3
W/WifiHW  (  922): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1325): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1325): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  922): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=50 dispatchEvent: BLACKLIST CLEAR 
,E/WifiStateMachine(  922): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/WIFI_ICON( 1216): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  922): NetworkAgent != null
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -61, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  922): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -61, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
V/NetworkPolicy(  922): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  922): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/ConnectivityService(  922): Adding iface wlan0 to network 101
D/HtcWifiWanDetect(  922): WAN detection
D/HtcWifiWanDetect(  922): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
,E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiDataStallTracker(  922): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  922): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  922): transitionTo: destState=ConnectedState
E/WifiStateMachine(  922): handleMessage: new destination call exit/enter
,E/WifiStateMachine(  922): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  922): invokeExitMethods: ObtainingIpState
V/NetworkPolicy(  922): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  922): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  922): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  922): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  922): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  922): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiTrafficPoller(  922): ENABLE_TRAFFIC_STATS_POLL false Token 26
,I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5950): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  922): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine(  922): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiStateMachine(  922): handleMessage: X
E/WifiStateMachine(  922): handleMessage: E msg.what=131131
E/WifiStateMachine(  922): processMsg: ConnectedState
,E/WifiStateMachine(  922):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  922): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  922): processMsg: ConnectModeState
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  922):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  922): handleMessage: X
,D/ConnectivityService(  922): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  922): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/WISPrService( 5950): >>>>>WISPrService start isConnected = true<<<<<
,D/libc    (  401): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  922): Setting Dns servers for network 101 to [/192.168.1.1]
,D/libc    (  922): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  401): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  922): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Connected
D/ConnectivityService(  922): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  922): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Validated
D/ConnectivityService(  922): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  922):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  922): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  922):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  922): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  922): currentScore = 0, newScore = 20
D/usbnet  (  922): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922):    accepting network in place of null
D/usbnet  (  922):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  922): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/QuickSettingWifi( 1216): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/CSLegacyTypeTracker(  922): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  922): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  922): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  922): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  922): ensureActiveMobilePolicyLocked()
D/Tethering(  922): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  922): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  922): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
,D/PMS     (  922): acquireWL(33f0411): PARTIAL_WAKE_LOCK  NetworkStats 0x1 922 1000 null
D/DATA_ICON( 1216): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  922): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): ValidatedState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Validated
D/ConnectivityService(  922): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524290
D/ConnectivityService(  922): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  922): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  922):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  922): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
I/SecurityController( 1216): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  922): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524290
,D/WIFI    (  922):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  922): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/usbnet  (  922): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  922):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  922): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  922): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  922): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  922):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  922): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1216): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524290
,D/NetworkPolicy(  922): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  922): updateNetworkEnabledLocked()
D/DATA_ICON( 1216): dataConnected: false/false
V/NetworkPolicy(  922): updateIfacesLocked()
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  922): releaseWL(33f0411): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  922): updateNotificationsLocked()
,I/QuickSettingWifi( 1216): receive.wifiConnect:true wifiAPname:NG700 elapse:2
I/SecurityController( 1216): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,V/NetworkPolicy(  922): updateNetworkEnabledLocked()
V/NetworkPolicy(  922): updateNotificationsLocked()
D/DATA_ICON( 1216): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/NetworkManagementService(  922): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DATA_ICON( 1216): dataConnected: false/false
,D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 6704): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6704): 
,D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  922): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  922): [AlarmQueuing] connectivity wifi: false
,D/htcCheckinService(  922): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  922): acquireWL(b381976): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 922 1000 null
D/PMS     (  922): acquireWL(5e8fb77): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 922 1000 null,
D/GpsLocationProvider(  922): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  922): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  922): releaseWL(5e8fb77): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ConnectivityHelper( 1625): [onReceive] WIFI(1): CONNECTED
,D/PMS     (  922): releaseWL(3c9c4433): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  922): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  922): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6831 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  922): No APN found to select.
,I/art     (  457): Explicit concurrent mark sweep GC freed 8633(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 209us total 44.676ms,
D/PMS     (  922): releaseWL(b381976): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/MdScPhnSt( 6767): [71.1.]  listen tmrbb8
,D/MdScDataSum( 6767): [71.1.] summary 118:p1 ignore
,I/art     (  457): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 135us total 19.432ms
,I/art     (  457): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 145us total 16.202ms
,I/MusicStore( 6831): Database version: 120,
,D/VoldConnector(  922): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6831): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  922): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6831): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  922): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6831): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6831): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6831): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6831): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6831): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6831): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3fc62bcb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6831): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6831): GMSCore installation verified
,I/ConfigStore( 6831): Config Database version: 1,
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6831, uid=10159, userID:0,
,D/WifiDisplayAdapter(  922): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  922):     Client/Owner: Client
D/WifiDisplayAdapter(  922):     GroupId: 
D/WifiDisplayAdapter(  922):     Passphrase: 
D/WifiDisplayAdapter(  922):     SessionId: 0
D/WifiDisplayAdapter(  922):     IP Address: }
,D/MediaRouterService(  922): Client com.google.android.music (pid 6831): Registered
,D/WifiDisplayAdapter(  922): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  922):     Client/Owner: Client
D/WifiDisplayAdapter(  922):     GroupId: 
D/WifiDisplayAdapter(  922):     Passphrase: 
D/WifiDisplayAdapter(  922):     SessionId: 0
D/WifiDisplayAdapter(  922):     IP Address: }
,I/MediaRouter( 6831): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/jxcore-log( 6704): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6704): 
,I/jxcore-log( 6704): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6704): 
,V/MusicLeanback( 6831): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6831): type=WIFI subType= reason=null isConnected=true
,I/jxcore-log( 6704): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6704): 
,I/jxcore-log( 6704): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 6704): 
,I/jxcore-log( 6704): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6704): 
,I/jxcore-log( 6704): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6704): 
,I/NetworkMonitor( 6831): type=WIFI subType= reason=null isConnected=true
,D/AutoSetting( 1540): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,D/MobileConnectivityChangeReceiver( 6446): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6446): onReceive CONNECTIVITY_CHANGE networkType=1
I/PackageManager(  922):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6831, uid=10159, userID:0
,D/AutoSetting( 1540): service - onCreate(),
,D/AutoSetting( 1540): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1540): service - onStartCommand() screen is off, don't request location,
D/LocationManagerService(  922): request 655132f passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,I/GHttpClientFactory( 6831): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/LocationManagerService(  922): provider request: passive ProviderRequest[ON interval=0]
,I/GoogleURLConnFactory( 6831): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4295): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4295): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/ActivityManager(  922): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6875 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 6565): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6565): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6565): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6565): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6565): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6565): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024,
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1793): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1793): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1793): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1793): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1793): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6565): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4295): [AccountUtils] Account not ready
W/Kids    ( 4295): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4295): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4295): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4295): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4295): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4295): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4295): ,	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4295): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4295): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4295): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4295): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4295): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1216): reapply : com.google.android.gms 2 40
,I/Babel   ( 6565): connection state changed from UNKNOWN to CONNECTED,
,I/art     (  922): Explicit concurrent mark sweep GC freed 53640(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/25MB, paused 1.503ms total 149.488ms,
,D/VoldConnector(  922): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
W/ContextImpl( 6875): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,I/GAv4    ( 6875): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6875):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6875):   adb logcat -s GAv4
D/VoldConnector(  922): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
W/ContextImpl( 6875): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,D/VoldConnector(  922): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6875): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  922): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
,W/GAv4    ( 6875): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6875): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6875): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6875): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 6704): Test app app.js loaded,
I/jxcore-log( 6704): 
,I/chromium( 6704): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/global  ( 6875): [apache-http] Connection GC has been deprecated!
,W/global  ( 6875): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6875): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6875): Time to load native libraries: 6 ms (timestamps 7095-7101)
,I/LibraryLoader( 6875): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6875): Binding Chromium to main looper Looper (main, tid 1) {199eed48}
,I/LibraryLoader( 6875): Expected native library version number "",actual native library version number "",
,I/chromium( 6875): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6875): Initializing chromium process, singleProcess=true,
,W/art     ( 6875): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6875): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6875): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6875): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6875): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6875): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6875): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6875): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6875): Local Branch: 
,I/Adreno-EGL( 6875): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6875): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6875):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6875): Requires BLUETOOTH permission,
,I/NSApplication( 6875): Starting up...,
,I/ActivityManager(  922): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6936 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  922): killProcessQuiet, pid=6503
,I/ActivityManager(  922): Killing 6503:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  922): Recipient 6503
,D/WifiService(  922): Client connection lost with reason: 4
,I/ActivityManager(  922): Killing 6402:com.google.android.gms.unstable/u0a24 (adj 15): empty #18
,D/Process (  922): killProcessQuiet, pid=6402
,D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  922): Recipient 6402
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6704): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6704): BLE advertisement is supported
I/jxcore-log( 6704): 
,E/WifiStateMachine(  922): handleMessage: E msg.what=131168,
E/WifiStateMachine(  922): processMsg: ConnectedState
E/WifiStateMachine(  922):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  922): processMsg: SupplicantStartedState
E/WifiStateMachine(  922):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  922): processMsg: DefaultState
E/WifiStateMachine(  922):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  922): handleMessage: X
,I/ActivityManager(  922): Killing 5850:com.htc.calendar/u0a10 (adj 15): empty #17,
D/Process (  922): killProcessQuiet, pid=5850
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/libc    (  922): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
,D/libc    (  922): [NET] android_getaddrinfofornet-, err=8
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  922): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  922): [NET] android_getaddrinfo_proxy+
D/libc    (  922): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  401): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/HtcWifiWanDetect(  922): Find DNS Address www.htc.com/104.81.130.175
D/libc    (  922): [NET] android_getaddrinfo_proxy-, success
,E/libprocessgroup(  922): failed to kill 1 processes for processgroup 5850
,D/GpsLocationProvider(  922): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
I/AlarmManager(  922): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  922): Recipient 5850
D/PMS     (  922): acquireWL(be7580f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 922 1000 null
D/PMS     (  922): acquireWL(38ef409c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 922 1000 null
,D/PMS     (  922): releaseWL(38ef409c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  922): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  922): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/NetworkMonitor( 6831): type=WIFI subType= reason=null isConnected=true
I/ConnectivityHelper( 1625): [onReceive] WIFI(1): CONNECTED
,D/htcCheckinService(  922): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,V/MusicLeanback( 6831): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  922): No APN found to select.
,D/PMS     (  922): releaseWL(be7580f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6767): [bc7.1.]  listen tmrbb8,
D/AutoSetting( 1540): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6446): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6446): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1540): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate,
D/AutoSetting( 1540): service - onStartCommand() screen is off, don't request location
,D/MdScDataSum( 6767): [bc7.1.] summary 118:p1 ignore,
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4295, uid=10024, userID:0
,D/ChimeraCfgMgr( 4295): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4295): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1793): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1793): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1793): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1793): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1793): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4295): [AccountUtils] Account not ready,
W/Kids    ( 4295): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4295): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4295): ,	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4295): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4295): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4295): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4295): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4295): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4295): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4295): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4295): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4295): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1216): reapply : com.google.android.gms 3 40,
,D/PMS     (  922): acquireWL(1d5462ff): PARTIAL_WAKE_LOCK  *alarm* 0x1 922 1000 WorkSource{10024},
,V/AlarmManager(  922): sending alarm PendingIntent{35208cc: PendingIntentRecord{2641715 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=140790, Int=0
D/PMS     (  922): acquireWL(32e46a2a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  922): releaseWL(1d5462ff): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1793): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1793): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1793): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1793): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1793): [NET] android_getaddrinfo_proxy+
D/libc    ( 1793): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  401): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1793): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1793): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1793): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 1793): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1793): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  922): acquireWL(a16301b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1793): Connected,
D/PMS     (  922): releaseWL(32e46a2a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): releaseWL(a16301b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): acquireWL(1dfce5b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1793 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1793): Message class com.google.f.a.a.p,
D/PMS     (  922): releaseWL(1dfce5b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(1136fef6): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6831 10159 null,
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6831, uid=10159, userID:0
,D/PMS     (  922): acquireWL(15cf3cfc): PARTIAL_WAKE_LOCK  *alarm* 0x1 922 1000 WorkSource{10024}
V/AlarmManager(  922): sending alarm PendingIntent{14b9ef85: PendingIntentRecord{3b1da com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141482, Int=0
D/PMS     (  922): releaseWL(1136fef6): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6831): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6831): Stop autocaching.
,D/WearableService( 5230): callingUid 10024, callindPid: 5230
,D/PMS     (  922): releaseWL(15cf3cfc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,E/GmsUtils( 6831): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6831): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  922): [handleMessage] DOWNLOAD_XTRA_DATA,
,D/GpsLocationProvider(  922): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  922): acquireWL(c802f94): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 922 1000 null,
,D/libc    (  922): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  922): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  922): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  922): [NET] android_getaddrinfo_proxy+
D/libc    (  922): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
,D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  922): [NET] android_getaddrinfo_proxy-, success
D/libc    (  922): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  922): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  922): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  922): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  922): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  922):  [handleDownloadXtraData]inject done.
D/PMS     (  922): acquireWL(37fab100): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 922 1000 null
D/GpsLocationProvider(  922): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  922): releaseWL(c802f94): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null,
D/PMS     (  922): releaseWL(37fab100): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1557): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1557): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/AutoSetting( 1540): service - handleMessage() stop self
,D/AutoSetting( 1540): service - onDestroy() END,
D/AutoSetting( 1540): service - handleMessage() quit looper
,D/PMS     (  922): acquireWL(1dab8d39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 922 1000 null
I/BatteryService(  922): n_update end
D/PMS     (  922): releaseWL(1dab8d39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1216): closing low battery warning: level=100
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  922): updateBatteryInfo
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 2977): Disconnected process message: 10, size: 0
D/NotificationService(  922): plugged=true pluggin=true
D/UsbnetService(  922): BroadcastReceiver::onReceive+
D/PMS     (  922): runPSCheck
D/UsbnetService(  922): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  922): Checking...
D/UsbnetService(  922):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  922): >> updateStatus
D/UsbnetService(  922): BroadcastReceiver::onReceive-
D/WifiController(  922): handleMessage: E msg.what=155652
D/WifiController(  922): processMsg: DeviceActiveState
D/WifiController(  922): processMsg: StaEnabledState
D/WifiController(  922): battery changed pluggedType: 2
D/WifiController(  922): processMsg: DefaultState
D/WifiController(  922): handleMessage: X
,I/HtcPowerSaver(  922): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  922): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,E/WifiStateMachine(  922): handleMessage: E msg.what=131165,
E/WifiStateMachine(  922): processMsg: ConnectedState
E/WifiStateMachine(  922):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  922): processMsg: ConnectModeState
E/WifiStateMachine(  922):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  922): processMsg: DriverStartedState
E/WifiStateMachine(  922):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  922): processMsg: SupplicantStartedState,
E/WifiStateMachine(  922):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  922): processMsg: DefaultState
E/WifiStateMachine(  922):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  922): handleMessage: X
,D/TelephonyReceiver( 1557): switchBindHtcMsgCursor: null
,D/PMS     (  922): acquireWL(1a28af7e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 922 1000 WorkSource{1000},
V/AlarmManager(  922): sending alarm PendingIntent{25e7ab46: PendingIntentRecord{37f77107 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=169528, Int=0
V/AlarmManager(  922): sending alarm PendingIntent{23f4cdf: PendingIntentRecord{11d9dd2c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1453132627064, Int=0
,V/AlarmManager(  922): sending alarm PendingIntent{372ec3f5: PendingIntentRecord{31c458a com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189745, Int=0
D/PMS     (  922): acquireWL(2f5d7fb): PARTIAL_WAKE_LOCK  *backup* 0x1 922 1000 null
,D/PMS     (  922): acquireWL(319da018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  922): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
,E/BackupManagerService(  922): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  922): releaseWL(2f5d7fb): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  922): releaseWL(1a28af7e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1216): Weather sync is On
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/PMS     (  922): acquireWL(1174aa71): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): releaseWL(319da018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1793): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  922): releaseWL(1174aa71): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(3ea14b73): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): releaseWL(3ea14b73): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): acquireWL(1d9c5a30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(302d36a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): acquireWL(323b2bcf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): releaseWL(1d9c5a30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(1d799465): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): releaseWL(1d799465): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1793): Vacuum at: now=1453132640506 tag=VacuumService
,D/PMS     (  922): releaseWL(302d36a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(319253a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  922): releaseWL(323b2bcf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): releaseWL(319253a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(3fe8b5eb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): releaseWL(3fe8b5eb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): acquireWL(3c453f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): releaseWL(3c453f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(3c7411e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(fe45b06): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): releaseWL(3c7411e1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1793): Using platform SSLCertificateSocketFactory
,W/Uploader( 1793): No account for auth token provided,
,D/libc    ( 1793): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1793): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1793): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1793): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1793): [NET] android_getaddrinfo_proxy+
D/libc    ( 1793): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  401): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  401): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  401): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  401): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1793): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1793): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1793): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1793): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1793): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1793): No account for auth token provided
,W/Uploader( 1793): No account for auth token provided,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/GLSUser ( 1793): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1793): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1793): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1793): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1793): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1216): reapply : com.google.android.gms 3 40,
D/DotMatrix( 1333): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1793): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1793): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1793): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1793): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1793): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1793): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1793): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1793): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1793): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1793): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1793): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1793): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1793): No account for auth token provided,
,W/Uploader( 1793): No account for auth token provided,
,W/Uploader( 1793):  no longer exists, so no auth token.,
,W/Uploader( 1793): No account for auth token provided,
,D/PMS     (  922): releaseWL(fe45b06): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): acquireWL(2f06efdb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): releaseWL(2f06efdb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  922): acquireWL(16b0a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1793 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  922): releaseWL(16b0a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiStateMachine(  922): handleMessage: E msg.what=131326,
E/WifiStateMachine(  922): processMsg: ConnectedState
E/WifiStateMachine(  922):  ConnectedState what:131326 2 0
E/WifiStateMachine(  922): processMsg: L2ConnectedState
E/WifiStateMachine(  922):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  922): handleMessage: X,
,D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
D/HtcAppUPService( 1540): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1de7e2de,
D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  922): killProcessQuiet, pid=5974
I/ActivityManager(  922): Killing 5974:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  922): Recipient 5974
,D/PMS     (  922): acquireWL(8943551): PARTIAL_WAKE_LOCK  *alarm* 0x1 922 1000 WorkSource{1000}
,V/AlarmManager(  922): sending alarm PendingIntent{1cff91b6: PendingIntentRecord{1ffaaeb7 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=212819, Int=0
,D/PMS     (  922): releaseWL(8943551): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  922): acquireWL(17825624): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 922 1000 null,
I/BatteryService(  922): n_update end
D/PMS     (  922): releaseWL(17825624): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  922): updateBatteryInfo
D/PMS     (  922): runPSCheck
,D/HtcPowerSaver(  922): Checking...
I/HtcPowerSaver(  922): >> updateStatus
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1216): closing low battery warning: level=100
,D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetStateMachine( 2977): Disconnected process message: 10, size: 0
,D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  922): updateStatus (8000,100,-1,false,false,false,-1),
D/UsbnetService(  922): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  922): << updateStatus
D/UsbnetService(  922): onReceive BATTERY_CHANGED
D/NotificationService(  922): plugged=true pluggin=true
D/UsbnetService(  922):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  922): battery changed pluggedType: 2
D/UsbnetService(  922): BroadcastReceiver::onReceive-
D/WifiController(  922): handleMessage: E msg.what=155652
D/WifiController(  922): processMsg: DeviceActiveState
D/WifiController(  922): processMsg: StaEnabledState
D/WifiController(  922): processMsg: DefaultState
D/WifiController(  922): handleMessage: X
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1325): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1325): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1325): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1325): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  922): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
E/WifiMonitor(  922): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97
,D/PMS     (  922): acquireWL(3c95d58d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 922 1000 null
I/BatteryService(  922): n_update end
,D/PMS     (  922): releaseWL(3c95d58d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  922): BroadcastReceiver::onReceive+
D/NotificationService(  922): plugged=true pluggin=true
D/UsbnetService(  922): onReceive BATTERY_CHANGED
,D/WifiController(  922): battery changed pluggedType: 2
D/UsbnetService(  922):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  922): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  922): updateBatteryInfo
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  922): handleMessage: E msg.what=155652
D/PMS     (  922): runPSCheck
D/WifiController(  922): processMsg: DeviceActiveState
,D/HtcPowerSaver(  922): Checking...
D/WifiController(  922): processMsg: StaEnabledState
I/HtcPowerSaver(  922): >> updateStatus
D/WifiController(  922): processMsg: DefaultState
D/HeadsetStateMachine( 2977): Disconnected process message: 10, size: 0
D/WifiController(  922): handleMessage: X
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1333): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  922): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  922): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6704): --= Surplus to requirements =--
I/jxcore-log( 6704): 
,I/jxcore-log( 6704): ****TEST TOOK:  ms ****,
I/jxcore-log( 6704): 
I/jxcore-log( 6704): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6704): 
,E/cutils-trace( 7002): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 7002): ====startRecUseTime====
D/htc.customization.log.level( 7002):  is 
W/CustomizationLogLevel( 7002): Level value is invalid, use default level 2
,D/CustomizationManager( 7002):  Read ACC file spent 0.032 (s),
,D/CIDMapFileReader( 7002): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7002): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7002): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7002): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7002): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7002): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7002): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 7002): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 7002): Parsing tag category name = system,
,I/CustomizationCIDLoader( 7002): Parsing tag category name = application
I/CustomizationCIDLoader( 7002): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7002): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7002): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7002): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7002): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7002): add string-array item, value = 42507
,I/CustomizationCIDLoader( 7002): add string-array item, value = 21902
I/CustomizationCIDLoader( 7002): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7002): add string-array item, value = 23420
I/CustomizationCIDLoader( 7002): add string-array item, value = 22299
I/CustomizationCIDLoader( 7002): add string-array item, value = 24002
I/CustomizationCIDLoader( 7002): add string-array item, value = 23210
I/CustomizationCIDLoader( 7002): add string-array item, value = 23205
I/CustomizationCIDLoader( 7002): add string-array item, value = 23806
,I/CustomizationCIDLoader( 7002): add string-array item, value = 23430
I/CustomizationCIDLoader( 7002): add string-array item, value = 23408
I/CustomizationCIDLoader( 7002): add string-array item, value = 27205
I/CustomizationCIDLoader( 7002): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 21902:C:1:0
,I/CustomizationCIDLoader( 7002): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7002): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7002):  Read CID file spent 0.069 (s)
D/CustomizationManager( 7002):  All configurations done spent 0.069 (s)
,D/PackageManager(  922): deletePackageAsUser: pkg=com.test.thalitest, pid=7002, uid=2000 userid=0,
,I/ActivityManager(  922): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
,D/Process (  922): killProcessQuiet, pid=6704
,I/ActivityManager(  922): Killing 6704:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
,D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 ,
,W/PackageSettings(  922): Skipping PackageSetting{10cd2cef com.example.hello/10374} due to missing metadata,
,E/InputEventReceiver( 1397): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1538e597 uid 10366 pid 6704} (c)'
I/ActivityManager(  922): Recipient 6704
,I/WindowState(  922): WIN DEATH: Window{263578bb u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  922): Client connection lost with reason: 4
,I/ActivityManager(  922):   Force finishing activity ActivityRecord{10cc1324 u0 com.test.thalitest/.MainActivity t8},
,I/ActivityManager(  922): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
,I/ActivityManager(  922):   Force finishing activity ActivityRecord{10cc1324 u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  922): Duplicate finish request for ActivityRecord{10cc1324 u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  922): Spurious death for ProcessRecord{2aeb1342 6704:com.test.thalitest/u0a366}, curProc for 6704: null,
,D/DotMatrix( 1333): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1333): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1333): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/AccTypeManager( 1773): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  922): Cannot find grip_rejection_width, use default value instead
,D/PMS     (  922): acquireWL(ba0b090): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1861 10024 WorkSource{10024 com.google.android.gms}
,W/GeofencerStateMachine( 1861): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  922): releaseWL(ba0b090): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 1773): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,D/VoicemailCleanupService( 1723): Cleaning up data for package: com.test.thalitest,
I/[PluginManager]RegisterService( 1540): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/art     ( 5887): Explicit concurrent mark sweep GC freed 18761(1193KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 356us total 76.533ms
,D/PhoneApp( 1557): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1540): handle notify Blinkfeed plugin client changed
W/Atfwd_Sendcmd(  472): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/AccTypeManager( 1773): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/art     ( 1625): Explicit concurrent mark sweep GC freed 2589(139KB) AllocSpace objects, 1(20KB) LOS objects, 34% free, 29MB/45MB, paused 946us total 94.836ms
,D/Prism.PackageStateRece_( 1625): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1625): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1625): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1625): Deferring update until onResume
D/Launcher( 1625): waitUntilResume // bindAppsRemoved
,I/InputMethodManagerService(  922): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,E/ExternalAccountType( 1773): Unsupported attribute readOnly,
,I/ActivityManager(  922): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,W/ResourcesManager(  922): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  922): Explicit concurrent mark sweep GC freed 40442(2MB) AllocSpace objects, 6(324KB) LOS objects, 33% free, 16MB/25MB, paused 1.809ms total 220.108ms
I/art     (  922): WaitForGcToComplete blocked for 183.214ms for cause Explicit
,D/StatusBarManagerService(  922): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  922): hiding MENU key
,D/StatusBarManagerService(  922): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  922): hiding MENU key
D/FindExtension( 1625): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1625): Defer allocateBuffers to drawing time
W/ContextImpl( 7022): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
W/InputMethodManagerService(  922): Got RemoteException sending setActive(false) notification to pid 6704 uid 10366
D/StatusBarManagerService(  922): swetImeWindowStatus vis=0 backDisposition=0
,W/PackageManager(  922): Unable to load service info ResolveInfo{a009d9 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
,W/PackageManager(  922): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data,
W/PackageManager(  922): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  922): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  922): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  922): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  922): ,	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  922): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  922): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  922): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  922): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  922): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  922): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  922): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  922): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  922): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  922): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  922): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7049 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  922): Killing 5887:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
D/Process (  922): killProcessQuiet, pid=5887
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/JobSchedulerService(  922): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  922): Explicit concurrent mark sweep GC freed 8113(476KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.978ms total 273.349ms
,W/asset   (  922): Copying FileAsset 0x559cb8eae0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/ActivityManager(  922): Recipient 5887,
,I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
,D/TaskPersister(  922): removeObsoleteFile: deleting file=8_task.xml
,I/PackageManager(  922):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7049, uid=10072, userID:0,
,W/global  ( 7049): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7049): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 7049): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7049): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7049): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  922): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7089 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7049): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7049): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SQLiteDatabase( 7049): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7049): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7049): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7049): 	,at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 7049): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7049): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7049): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7049): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7049): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7049): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 7049): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 7049): Process: com.android.vending, PID: 7049
E/AndroidRuntime( 7049): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 7049): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 7049): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 7049): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 7049): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242),
E/AndroidRuntime( 7049): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 7049): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 7049): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 7049): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 7049): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7049): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288),
E/AndroidRuntime( 7049): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime( 7049): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime( 7049): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime( 7049): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime( 7049): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime( 7049): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 7049): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 7049): ,	... 4 more
I/PackageManager(  922):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7049, uid=10072, userID:0
E/ActivityManager(  922): App crashed! Process: com.android.vending
E/DropBoxManagerService(  922): Can't write: system_app_crash
E/DropBoxManagerService(  922): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  922): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  922): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  922): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  922): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  922): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  922): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  922): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  922): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  922): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  922): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  922): 	... 5 more
W/ResourcesManager( 7089): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7089): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Process ( 7049): killProcess, pid=7049
,E/SQLiteDatabase( 7049): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7049): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 7049): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 7049): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7049): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7049): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7049): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7049): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7049): 	at java.lang.Thread.run(Thread.java:818)
,E/AndroidRuntime_2_crash( 7049): crash in the same process: AsyncTask #2
E/AndroidRuntime_2_crash( 7049): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 7049): 	,at android.os.AsyncTask$3.done(AsyncTask.java:300)
,E/AndroidRuntime_2_crash( 7049): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 7049): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 7049): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 7049): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 7049): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 7049): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 7049): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 7049): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 7049): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 7049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 7049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 7049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 7049): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 7049): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 7049): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 7049): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 7049): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_2_crash( 7049): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_2_crash( 7049): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 7049): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 7049): 	... 4 more
,D/Process ( 7049): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
,I/MultiDex( 7089): VM with version 2.1.0 has multidex support
,I/MultiDex( 7089): install
I/MultiDex( 7089): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  922): Recipient 7049
,I/ActivityManager(  922): Process com.android.vending (pid 7049) has died
,V/JNIHelp ( 7089): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7089): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 7089): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1bab8ca9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 7089): Installed default security provider GmsCore_OpenSSL
,E/SQLiteLog( 1793): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error,
E/SQLiteDBG( 1793): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x559c5bcd50
,W/NativeLibraryUtils( 7089): Failed to open lock file
W/NativeLibraryUtils( 7089): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7089): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7089): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7089): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7089): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7089): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7089): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7089): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7089): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7089): 	... 3 more
,E/AndroidRuntime( 1793): FATAL EXCEPTION: main
E/AndroidRuntime( 1793): Process: com.google.process.gapps, PID: 1793
E/AndroidRuntime( 1793): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1793): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1793): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1793): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1793): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1793): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1793): ,	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1793): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1793): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1793): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1793): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1793): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1793): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1793): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1793): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1793): 	... 9 more
E/ActivityManager(  922): App crashed! Process: com.google.process.gapps
D/Process ( 1793): killProcess, pid=1793
D/Process ( 1793): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  922): Can't write: system_app_crash,
E/DropBoxManagerService(  922): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  922): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  922): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  922): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  922): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  922): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  922): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  922): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  922): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  922): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  922): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  922): 	... 5 more
,I/ActivityManager(  922): Recipient 1793
,I/ActivityManager(  922): Process com.google.process.gapps (pid 1793) has died
W/ActivityManager(  922): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
W/ActivityManager(  922): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 10999ms
W/ActivityManager(  922): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 20999ms
,W/ActivityManager(  922): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
I/ActivityThread( 7089): Removing dead content provider:android.content.ContentProviderProxy@34c871cf
,I/ActivityManager(  922): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=7123 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 7123): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7123): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7123): VM with version 2.1.0 has multidex support,
I/MultiDex( 7123): install
I/MultiDex( 7123): VM has multidex support, MultiDex support library is disabled.
,I/GservicesProvider( 7123): Gservices pushing to system: true; secure/global: true,
,E/SQLiteDatabase( 7123): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7123): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7123): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7123): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
,E/SQLiteDatabase( 7123): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7123): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7123): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7123): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7123): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7123): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7123): FATAL EXCEPTION: main
E/AndroidRuntime( 7123): Process: com.google.process.gapps, PID: 7123
E/AndroidRuntime( 7123): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7123): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7123): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7123): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7123): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7123): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/A,ndroidRuntime( 7123): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7123): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7123): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7123): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7123): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7123): 	... 11 more
E/ActivityManager(  922): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  922): Can't write: system_app_crash
E/DropBoxManagerService(  922): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  922): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  922): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  922): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  922): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  922): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  922): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  922): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  922): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  922): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  922): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  922): 	... 5 more
D/Process ( 7123): killProcess, pid=7123
D/Process ( 7123): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/Prism.ItemManager( 1625): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/ActivityManager(  922): Recipient 7123
I/Prism.ItemManager( 1625): loadItems() com.htc.launcher.pageview.WidgetManager@2b5ce904 +
I/Prism.WidgetManager( 1625): onLoadItems() +
,I/ActivityManager(  922): Process com.google.process.gapps (pid 7123) has died
W/ActivityManager(  922): Service crashed 2 times, stopping: ServiceRecord{1a57cbf7 u0 com.google.android.gms/.gcm.GcmService}
W/ActivityManager(  922): Service crashed 2 times, stopping: ServiceRecord{12ca8885 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
,W/ActivityManager(  922): Service crashed 2 times, stopping: ServiceRecord{af78099 u0 com.google.android.gms/.gcm.http.GoogleHttpService}
W/ActivityManager(  922): Service crashed 2 times, stopping: ServiceRecord{3c37565 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,I/ActivityManager(  922): Start proc com.google.process.gapps for restart com.google.process.gapps: pid=7146 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 1625): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 7146): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7146): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7146): VM with version 2.1.0 has multidex support
I/MultiDex( 7146): install
I/MultiDex( 7146): VM has multidex support, MultiDex support library is disabled.
,I/GservicesProvider( 7146): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7146): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7146): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7146): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7146): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7146): ,	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7146): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7146): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7146): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7146): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7146): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7146): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7146): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7146): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7146): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7146): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7146): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7146): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7146): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7146): FATAL EXCEPTION: main
E/AndroidRuntime( 7146): Process: com.google.process.gapps, PID: 7146
E/AndroidRuntime( 7146): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7146): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7146): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7146): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7146): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7146): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7146): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7146): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7146): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7146): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7146): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7146): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7146): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7146): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7146): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7146): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7146): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7146): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7146): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7146): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7146): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7146): 	... 11 more
W/ActivityManager(  922): Process com.google.android.gms has crashed too many times: killing!
E/ActivityManager(  922): App crashed! Process: com.google.process.gapps
I/ActivityManager(  922): Killing 7146:com.google.process.gapps/u0a24 (adj 0): crash
D/Process (  922): killProcessQuiet, pid=7146
E/DropBoxManagerService(  922): Can't write: system_app_crash
E/DropBoxManagerService(  922): java.io.FileNotFou,ndException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  922): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  922): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  922): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  922): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  922): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  922): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  922): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  922): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  922): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  922): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  922): 	... 5 more
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12134 
,I/ActivityManager(  922): Recipient 7146
,W/ResourcesManager( 1625): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Process (  922): killProcessQuiet, pid=7089
W/ActivityManager(  922): Unable to launch app com.google.android.gsf/10024 for provider com.google.android.gsf.gservices: launching app became null
D/Process (  922): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:15264 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:15341 
I/ActivityManager(  922): Killing 7089:com.google.android.gms:car/u0a24 (adj 0): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
,I/ActivityManager(  922): Recipient 7089
,W/asset   ( 1625): Copying FileAsset 0x559cc90860 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,

```
