#### Test 506502781c2754f_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Process (  970): killProcessQuiet, pid=5574
--------- beginning of system
I/ActivityManager(  970): Killing 5574:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5574
E/cutils-trace( 6547): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6547): ====startRecUseTime====
D/htc.customization.log.level( 6547):  is 
W/CustomizationLogLevel( 6547): Level value is invalid, use default level 2
D/CustomizationManager( 6547):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6547): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6547): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6547): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6547): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6547): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6547): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6547): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6547): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6547): Parsing tag category name = system
I/CustomizationCIDLoader( 6547): Parsing tag category name = application
I/CustomizationCIDLoader( 6547): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6547): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6547): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6547): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6547): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6547): add string-array item, value = 42507
I/CustomizationCIDLoader( 6547): add string-array item, value = 21902
I/CustomizationCIDLoader( 6547): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6547): add string-array item, value = 23420
I/CustomizationCIDLoader( 6547): add string-array item, value = 22299
I/CustomizationCIDLoader( 6547): add string-array item, value = 24002
I/CustomizationCIDLoader( 6547): add string-array item, value = 23210
I/CustomizationCIDLoader( 6547): add string-array item, value = 23205
I/CustomizationCIDLoader( 6547): add string-array item, value = 23806
I/CustomizationCIDLoader( 6547): add string-array item, value = 23430
I/CustomizationCIDLoader( 6547): add string-array item, value = 23408
I/CustomizationCIDLoader( 6547): add string-array item, value = 27205
I/CustomizationCIDLoader( 6547): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6547): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6547):  Read CID file spent 0.109 (s)
D/CustomizationManager( 6547):  All configurations done spent 0.109 (s)
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6547 on display 0
D/PMS     (  970): acquireHCC(cd15f09): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
D/PMS     (  970): acquireHCC(a10650e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
W/asset   (  970): Copying FileAsset 0x5568d6cb60 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  970): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6565 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  970): Display changed displayId=0
D/DotMatrix( 1309): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1309): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6565): Copying FileAsset 0xab6b19f0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1491): [trimMemory] 20
I/WebViewFactory( 6565): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6565): Time to load native libraries: 11 ms (timestamps 8489-8500)
,I/LibraryLoader( 6565): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6565): Binding Chromium to main looper Looper (main, tid 1) {b1cffc5}
,I/LibraryLoader( 6565): Expected native library version number "",actual native library version number ""
,I/chromium( 6565): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6565): Initializing chromium process, singleProcess=true
,W/art     ( 6565): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6565): ApplicationContext is null in ApplicationStatus
,W/chromium( 6565): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6565): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6565): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6565): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6565): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6565): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6565): Local Branch: 
I/Adreno-EGL( 6565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6565): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6565):                  d74aa161a12b9c6fc6332151
,W/System.err(  970): java.lang.Throwable: stack dump
W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): ,	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29c7a127:true
,D/BluetoothAdapter( 6565): 831171112: getState(). Returning 12
,W/art     ( 6565): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6565): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6565): CordovaWebView is running on device made by: HTC
,W/art     ( 6565): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6565): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,W/chromium( 6565): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  970): hiding MENU key
D/StatusBarManagerService(  970): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
,D/FindExtension( 6565): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6565): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@26009717, mServedView=org.apache.cordova.engine.SystemWebView{f138704 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@f8be4ed
,I/InputMethodManagerService(  970): Disable input method client, pid=1491
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6565): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  970): Displayed com.test.thalitest/.MainActivity: +642ms (total +686ms)
,W/BindingManager( 6565): Cannot call determinedVisibility() - never saw a connection for the pid: 6565,
,D/JsMessageQueue( 6565): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6565): JniHelper::setJavaVM(0xab6158f8), pthread_self() = -1399480592
D/JX-Cordova( 6565): jxcore cordova android initializing
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2
,W/jxcore-log( 6565): Initializing JXcore engine,
W/jxcore-log( 6565): JXcore engine is ready
,W/jxcore-log( 6565): Starting JXcore engine,
,W/jxcore-log( 6565): Platform android
W/jxcore-log( 6565): 
W/jxcore-log( 6565): Process ARCH arm
W/jxcore-log( 6565): 
,D/PMS     (  970): releaseHCC(cd15f09): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  970): releaseHCC(a10650e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6565): JXcore Cordova bridge is ready!,
I/jxcore-log( 6565): 
W/jxcore-log( 6565): JXcore engine is started
,I/chromium( 6565): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6565): Toggling radios to true,
I/jxcore-log( 6565): 
D/BluetoothAdapter( 6565): enable(): BT is already enabled..!
,E/WifiTrafficPoller(  970): ADD_CLIENT: 8,
D/WifiService(  970): New client listening to asynchronous messages
D/WifiManager( 6565): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/WifiService(  970): setWifiEnabled: true pid=6565, uid=10366
E/WifiService(  970): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  970): MONITOR_LOG
I/WifiService(  970): isSprintWifiRestricted(): false
W/Settings:Agent(  970): name: wifi_on
I/WifiService(  970): isMdmWifiRestricted(): false
W/Settings:Agent(  970): value: 2
W/Settings:Agent(  970): >> traceCallingStack()
W/Settings:Agent(  970): Process.myPid(): 970
W/Settings:Agent(  970): Process.myTid(): 1745
W/Settings:Agent(  970): Process.myUid(): 1000
W/Settings:Agent(  970): 
W/Settings:Agent(  970): 
,W/System.err(  970): java.lang.Throwable: stack dump
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
W/Settings:Agent(  970): << traceCallingStack(): 21(ms)
D/WifiController(  970): handleMessage: E msg.what=155656
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): handleMessage: X
D/WifiManager( 6565): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  970): handleMessage: E msg.what=131145
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
D/wpa_supplicant( 1348): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1348): TDLS: Tear down peers
D/wpa_supplicant( 1348): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiManager( 6565): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 6565): Radios toggled
I/jxcore-log( 6565): 
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6565): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6565): 
I/jxcore-log( 6565): Perf Test app loaded loaded
I/jxcore-log( 6565): 
,I/jxcore-log( 6565): check test folder
I/jxcore-log( 6565): 
,I/jxcore-log( 6565): found test : ./testFindPeers.js
I/jxcore-log( 6565): 
,D/wpa_supplicant( 1348): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1348): wlan0: Deauthentication notification
D/wpa_supplicant( 1348): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1348): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1348): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1348): enter disconnect check
I/wpa_supplicant( 1348): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1348): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1348): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
,E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  970): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  970): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
,D/Tethering(  970): interfaceStatusChanged wlan0, false
D/Tethering(  970): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/PMS     (  970): acquireWL(14943d0f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
V/Tethering(  970): TetherInterfaceSM: wlan0: exit InitialState
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  970): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/TetherSettings( 4553): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4553): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4553): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4553): Cust_ConnectToPC   : spcsc>false
D/        ( 4553): Cust_ConnectToPC   : IPT>true
D/        ( 4553): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4553): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4553): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4553): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4553): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 1348): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1348): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55b0f30f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 1->0 (DORMANT)
,D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1348): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1348): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1348): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1348): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1348): EAPOL: External notification - EAP success=0
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1348): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=0
D/WifiP2pService(  970): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1348): Wireless event: cmd=0x8b15 len=24
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
W/ContextImpl( 4553): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1348): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/PMS     (  970): acquireWL(3652c19c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1348): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  970): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: ConnectedState
E/WifiStateMachine(  970): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  970): release()
E/WifiStateMachine(  970): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  970): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  970): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  970): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMet,hods
E/WifiStateMachine(  970): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  970): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1348): Power_Mode_Type mode = 0
I/wpa_supplicant( 1348): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  970): setDhcpActive: false
V/NativeCrypto( 1938): Read error: ssl=0x556853c3c0: I/O error during system call, Connection timed out
I/SmartNS_Utility( 4553): setISNotification
D/SmartNS_Utility( 4553): usb_cable_connect = 1
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/SmartNS_Utility( 4553): usb_denied = 0
I/SmartNS_PSService( 4553): usb notificaiton:true
,E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): NetworkAgent != null
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED connected,
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiDataStallTracker(  970): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  970): stopDataStallAlarm 
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  970):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  970): Start Disconnecting Watchdog 1
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131146
E/WifiStateMachine(  970): processMsg: DisconnectingState
E/WifiStateMachine(  970):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
,E/WifiStateMachine(  970):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1348): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1348): Fast associate: Old scan results
D/wpa_supplicant( 1348): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1348): wpa_supplicant_scan enter
D/wpa_supplicant( 1348): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1348): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1348): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1348): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1348): WPS:  * Request Type
D/wpa_supplicant( 1348): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1348): WPS:  * UUID-E
D/wpa_supplicant( 1348): WPS:  * Primary Device Type
D/wpa_supplicant( 1348): WPS:  * RF Bands (3)
D/wpa_supplicant( 1348): WPS:  * Association State
D/wpa_supplicant( 1348): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1348): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1348): WPS:  * Manufacturer
D/wpa_supplicant( 1348): WPS:  * Model Name
D/wpa_supplicant( 1348): WPS:  * Model Number
D/wpa_supplicant( 1348): WPS:  * Device Name
D/wpa_supplicant( 1348): WPS:  * Version2 (0x20)
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1348): P2P: * P2P IE header
D/wpa_supplicant( 1348): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1348): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1348): wlan0: Add radio work 'scan'@0x55b0f33680
D/wpa_supplicant( 1348): wlan0: First radio work item in the queue - schedule start immediately,
D/wpa_supplicant( 1348): wlan0: Starting radio work 'scan'@0x55b0f33680 after 0.000042 second wait
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1348): wlan0: nl80211: scan request
D/wpa_supplicant( 1348): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1348): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1348): wlan0: nl80211: Scan trigger
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1348): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1348): wlan0: Own scan request started a scan in 0.000139 seconds
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147460
E/WifiStateMachine(  970): processMsg: DisconnectingState
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/PMS     (  970): releaseWL(14943d0f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  970):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132138
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=132138
E/WifiStateMachine(  970): ConnectModeState: Network connection lost 
E/WifiStateMachine(  970): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: DisconnectingState
D/ConnectivityService(  970): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
V/NetworkPolicy(  970): updateNotificationsLocked()
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  970): DisconnectedState call setCountryCode()
E/WifiStateMachine(  970):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1348): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_Utility( 4553): usb_cable_connect = 1
D/SmartNS_Utility( 4553): usb_denied = 0
I/SmartNS_PSService( 4553): usb notificaiton:true
V/NativeCrypto( 1938): SSL shutdown failed: ssl=0x556853c3c0: I/O error during system call, Broken pipe
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 15
,D/PMS     (  970): releaseWL(3652c19c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/SmartNS_NSReceiver( 4553): Tethered state change:false isNSOpening:false
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/jxcore-log( 6565): found test : ./testSendData.js
I/jxcore-log( 6565): 
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/wpa_supplicant( 1348): wlan0: nl80211: sched_scan request
,I/RemoteViews( 1215): reapply : com.android.settings 1 36
,I/RemoteViews( 1215): reapply : com.android.settings 1 36
,I/QuickSettingWifi( 1215): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1,
,D/wpa_supplicant( 1348): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1348): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1348): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1348): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1348): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1348): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1348): wlan0: Scan completed in 0.050630 seconds
D/wpa_supplicant( 1348): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1348): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1348): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1348): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1348): wlan0: New scan results available (own=1 ext=0)
E/WifiStateMachine(  970): handleMessage: X
D/wpa_supplicant( 1348): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1348): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
,D/wpa_supplicant( 1348): wlan0: Radio work 'scan'@0x55b0f33680 done in 0.051624 seconds,
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/wpa_supplicant( 1348): wlan0: Selecting BSS from priority group 389
D/wpa_supplicant( 1348): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-57 wps
D/wpa_supplicant( 1348): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1348): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1348): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1348):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1348): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1348): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55b0f32c00  current_ssid=0x0
D/wpa_supplicant( 1348): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1348): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1348): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1348): wlan0: Add radio work 'connect'@0x55b0f33680
E/WifiStateMachine(  970):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1348): wlan0: First radio work item in the queue - schedule start immediately
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/wpa_supplicant( 1348): wlan0: Starting radio work 'connect'@0x55b0f33680 after 0.000056 second wait
I/wpa_supplicant( 1348): check if in concurrent case
I/wpa_supplicant( 1348): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  970):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
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
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=132190  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=132191  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  970): handleMessage:, X
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/wpa_supplicant( 1348): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1348): wlan0: Cancelling sched scan
D/wpa_supplicant( 1348): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
E/WifiStateMachine(  970):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1348): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1348): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1348): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1348): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1348): wlan0: Automatic auth_alg selection: 0x1
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/wpa_supplicant( 1348): RSN: PMKSA cache search - network_ctx=0x55b0f32c00 try_opportunistic=0
D/wpa_supplicant( 1348): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1348): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1348): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1348): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1348): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1348): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1348): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1348): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1348): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1348): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  970):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1348): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1348): nl80211: Set mode ifindex 29 iftype 2 (STATION)
E/WifiStateMachine(  970): processMsg: DriverStartedState
D/wpa_supplicant( 1348): nl80211: Unsubscribe mgmt frames handle 0x888888dd387ba989 (mode change)
D/wpa_supplicant( 1348): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b0f32100
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=0104
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=040a
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=040b
E/WifiStateMachine(  970):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=040c
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=040d
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=090a
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=090b
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=090c
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=090d
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=0409506f9a09
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=7f506f9a09
E/WifiStateMachine(  970):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=0801
E/WifiStateMachine(  970): processMsg: DefaultState
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=040e
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=06
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=0a07
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=0a11
D/wpa_supplicant( 1348): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b0f32100 match=0a1a
D/wpa_supplicant( 1348): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1348):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348):   * freq=2412
D/wpa_supplicant( 1348):   * freq_hint=2412
D/wpa_supplicant( 1348):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1348):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1348):   * WPA Versions 0x2
D/wpa_supplicant( 1348):   * pairwise=0xfac04
D/wpa_supplicant( 1348):   * group=0xfac04
D/wpa_supplicant( 1348):   * akm=0xfac02
D/wpa_supplicant( 1348):   * Auth Type 0
D/wpa_supplicant( 1348): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55b0f32c3a
E/WifiStateMachine(  970):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
D/WifiNetworkAgent(  970): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/wpa_supplicant( 1348): nl80211: Connect request send successfully
D/wpa_supplicant( 1348): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1348): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1348): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1348): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1348): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1348): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1348): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  970):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=132197  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/jxcore-log( 6565): found test : ./testSendData2.js
I/jxcore-log( 6565): 
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  970): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  970): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  970): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=40 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/jxcore  ( 6565): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 6565): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=132207  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  970): handleMessage: X
I/chromium( 6565): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:84 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:84 bcn=0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:84 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:84 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1348): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  970): [1,450,658,020,510 ms] noteScanEnd no scan source
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1348): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@35ae6ef2 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  970): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2412
E/WifiAutoJoinController (  970): 01ABC c2:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 3 now 1450658020513
E/WifiAutoJoinController (  970): newSupplicantResults size=3 known=1 true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1348): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  970): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  970): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  970): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  970): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  970): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131213
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132220
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132221
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132222
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_TARGET_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=132222
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=132222  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info0x
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4553): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=132225  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  970): handleMessage: X
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 18
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 9
,I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  970): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524292
D/Nat464Xlat(  970): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  970): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  970): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SecurityController( 1215): onLost 100
D/ConnectivityService(  970): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  970): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  970): Removing idletimer
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  970): acquireWL(20fd577a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 970 1000 null
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/CSLegacyTypeTracker(  970): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
E/WifiStateMachine(  970): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/ConnectivityService(  970): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  970): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  970): acquireWL(1ee19b2b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/Tethering(  970): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  970): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
V/NetworkPolicy(  970): ensureActiveMobilePolicyLocked()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/DATA_ICON( 1215): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Disconnected - quitting
D/NetworkPolicy(  970): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateIfacesLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
D/DATA_ICON( 1215): dataConnected: false/false
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/PMS     (  970): releaseWL(1ee19b2b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  970): handleMessage: E msg.what=131131
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): handleMessage: X
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
W/WISPrService( 4553): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4553): trigger connection
D/WISPrService( 4553): continue
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,D/WISPrService( 4553): start DataConnection
D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 4553): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4553): [NET] android_getaddrinfofornet-, err=8,
D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
D/libc    ( 4553): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4553): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4553): [NET] android_getaddrinfo_proxy+
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/libc    ( 4553): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4553): [NET] android_getaddrinfo_proxy-, NODATA
,I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:5,
,I/ActivityManager(  970): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6626 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon,
,D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 4553): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4553): [NET] android_getaddrinfofornet-, err=8
,D/WISPrService( 4553): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false,
,D/wpa_supplicant( 1348): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1348): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1348): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1348): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1348): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/Tethering(  970): interfaceLinkStateChanged wlan0, false
,D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1348): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1348): nl80211: Connect event
D/wpa_supplicant( 1348): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1348): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1348): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1348): wlan0: Association info event
D/wpa_supplicant( 1348): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): wlan0: freq=2412 MHz
D/wpa_supplicant( 1348): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1348): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/Tethering(  970): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1348): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 1348): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1348): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1348): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1348): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1348): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1348): TDLS: Remove peers on association
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1348): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1348): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1348): EAPOL: enable timer tick
D/wpa_supplicant( 1348): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1348): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1348): wlan0: Cancelling scan request
I/wpa_supplicant( 1348): htc_wext_set_keepalive +
I/wpa_supplicant( 1348): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1348): getPrivFuncNum +	
I/wpa_supplicant( 1348): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1348): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
I/wpa_supplicant( 1348): htc_wext_set_keepalive - ret = 0
,E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1348): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1348): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1348): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1348): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1348): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1348): wlan0:   key_length=16 key_data_length=0,
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1348):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/PMS     (  970): acquireWL(274b5bd2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/Tethering(  970): interfaceStatusChanged wlan0, false
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1348):   key_nonce - hexdump(len=32): 5f 24 b3 46 04 6c 8b 24 d3 0e be 6a 23 69 4e a7 e8 8d 8b 58 c4 aa 3f 15 e2 9e 45 d3 23 46 94 24
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  970): releaseWL(274b5bd2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1348):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1348): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1348): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  970): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=43 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
V/NetworkPolicy(  970): updateNotificationsLocked()
D/WifiMonitor(  970): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
D/WifiMonitor(  970): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/HTCRequest(  970): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  970): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  970): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  970): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  970): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=132315  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=132316  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/wpa_supplicant( 1348): WPA: Renewed SNonce - hexdump(len=32): a8 f5 45 17 a3 12 2d 26 65 1c be 14 f7 2f e6 dc c6 80 5e 86 54 96 be 4d 47 da 9c 8a 14 c3 39 dd
D/Tethering(  970): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970): handleMessage: X
D/wpa_supplicant( 1348): WPA: Nonce1 - hexdump(len=32): a8 f5 45 17 a3 12 2d 26 65 1c be 14 f7 2f e6 dc c6 80 5e 86 54 96 be 4d 47 da 9c 8a 14 c3 39 dd
E/WifiStateMachine(  970): handleMessage: E msg.what=147500
D/wpa_supplicant( 1348): WPA: Nonce2 - hexdump(len=32): 5f 24 b3 46 04 6c 8b 24 d3 0e be 6a 23 69 4e a7 e8 8d 8b 58 c4 aa 3f 15 e2 9e 45 d3 23 46 94 24
D/wpa_supplicant( 1348): WPA: PMK - hexdump(len=32): [REMOVED]
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/wpa_supplicant( 1348): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1348): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1348): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1348): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1348): WPA: Derived Key MIC - hexdump(len=16): 19 4a 2a ed 8b 20 4e f5 5c ba e1 30 e9 22 b7 03
V/Tethering(  970): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  970):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  970): Enter handleAssociatedWithEvent
D/WifiStateMachine(  970): Associated
D/Tethering(  970): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine(  970): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  970): Exit handleAssociatedWithEvent
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/wpa_supplicant( 1348): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1348): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1348): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1348): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1348):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1348):   key_nonce - hexdump(len=32): 5f 24 b3 46 04 6c 8b 24 d3 0e be 6a 23 69 4e a7 e8 8d 8b 58 c4 aa 3f 15 e2 9e 45 d3 23 46 94 24
D/w,pa_supplicant( 1348):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_rsc - hexdump(len=8): f0 72 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348):   key_mic - hexdump(len=16): 5b 57 57 1b 20 77 cf 9f 42 57 a5 6a 56 09 c8 8c
D/wpa_supplicant( 1348): RSN: encrypted key data - hexdump(len=56): 6d 1d e6 a5 45 e8 31 9d 59 43 2c 65 f0 77 4d 19 b7 80 6b 11 86 3f 0c 90 f6 76 8c 13 36 58 5c 18 ...
D/wpa_supplicant( 1348): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1348): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1348): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1348): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 4b 0f ...
D/wpa_supplicant( 1348): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1348): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1348): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1348): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1348): WPA: Derived Key MIC - hexdump(len=16): ce f0 96 ca f0 c9 b7 c6 0b e2 11 ef d6 4c b1 0f
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=132322  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/wpa_supplicant( 1348): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55b0f33390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1348): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1348): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1348):    addr=c0:ff:d4:d3:aa:48
E/WifiStateMachine(  970): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1348): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1348): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1348): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1348): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1348): WPA: RSC - hexdump(len=6): f0 72 00 00 00 00
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x558ce06e68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1348): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1348): nl80211: KEY_SEQ - hexdump(len=6): f0 72 00 00 00 00
D/wpa_supplicant( 1348):    broadcast key
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1348): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1348): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1348): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateCha,nge(): SSIDNG700
D/wpa_supplicant( 1348): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1348): wlan0: Radio work 'connect'@0x55b0f33680 done in 0.134794 seconds
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1348): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/WifiStateMachine(  970): NetworkAgent == null
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  970): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=46 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  970): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  970): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
E/wpa_supplicant( 1348): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 1348): set send_ind_to_ndc = 0
I/wpa_supplicant( 1348): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1348): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1348): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1348): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1348): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1348): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1348): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1348): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1348): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1348): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1348): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1348): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  970): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=49 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  970): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/UsbnetService(  970): BroadcastReceiver::onReceive-
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/Tethering(  970): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=132329  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970): handleMessage: X
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=132333  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=132334  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147459
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=132337
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=132338
E/WifiStateMachine(  970): Network connection established
D/WifiStateMachine(  970): fetchFrequency(), freq = 2412
E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 22
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  970): invokeExitMethods: DisconnectedState
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 23
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1348): CTRL_IFACE SET 'pno'='0'
D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  970): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  970): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  970): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/FlexNetS( 6432): updateSvcAllowedInSettings:false
E/WifiStateMachine(  970): NetworkAgent == null
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ContactMessageStore( 1441): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1441): MSG_NOTIFY_CS_TO_SYNC <<
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 24
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  970): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  970): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  970): Got NetworkAgent Messenger
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  970): NetworkAgent connected
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  970): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  970): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  970): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  970): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/TetherSettings( 4553): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4553): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4553): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4553): Cust_ConnectToPC   : spcsc>false
D/        ( 4553): Cust_ConnectToPC   : IPT>true
D/        ( 4553): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4553): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4553): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4553): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4553): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): Start Dhcp Watchdog 2
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=132363  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=132364  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=132365  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
W/ContextImpl( 4553): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
I/SmartNS_Utility( 4553): setISNotification
E/WifiStateMachine(  970):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=196612
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  970): handlePreDhcpSetup Held wake lock during DHCP
D/SmartNS_Utility( 4553): usb_cable_connect = 1
D/PMS     (  970): acquireWL(29cd77f7): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 970 1000 null
D/WifiStateMachine(  970): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  970): setDhcpActive: true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/SmartNS_Utility( 4553): usb_denied = 0
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
I/SmartNS_PSService( 4553): usb notificaiton:true
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  970): do suspend false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER POWERMODE 1'
,I/wpa_supplicant( 1348): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1348): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1348): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1348): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  970): Unexpected BatchedScanResults :null
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  970): noteBatchedScanstop()
E/WifiStateMachine(  970): handleMessage: X
D/WifiP2pService(  970): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29916d27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  970): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29916d27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
D/SmartNS_Utility( 4553): usb_cable_connect = 1
D/SmartNS_Utility( 4553): usb_denied = 0
I/SmartNS_PSService( 4553): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
I/RemoteViews( 1215): reapply : com.android.settings 1 36
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 4553): Tethered state change:false isNSOpening:false
D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WISPrService( 4553): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4553): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/FlexNetS( 6432): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1
I/RemoteViews( 1215): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6626): [c09.2.]  listen tmrbb8
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/FlexNetS( 6432): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6495): remove item 101 (p2d27in246) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 6626): [c09.2.] summary 118:p2 ignore
,E/dhcpcd  ( 6656): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6656): version 5.5.6 starting
E/dhcpcd  ( 6656): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6656): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6656): autoip env[11]:autoip=DISABLE
,D/Process (  970): killProcessQuiet, pid=6103
I/ActivityManager(  970): Killing 6103:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6656): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6656): wlan0: sending REQUEST (xid 0x50efeb09), next in 1.96 seconds
,I/ActivityManager(  970): Recipient 6103
,D/wpa_supplicant( 1348): EAPOL: startWhen --> 0
D/wpa_supplicant( 1348): EAPOL: disable timer tick
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
,D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=131212,
,E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
,I/dhcpcd  ( 6656): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6656): wlan0: leased 192.168.1.130 for 86400 seconds,
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
I/dhcpcd  ( 6656): autoip env[11]:autoip=DISABLE
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
,E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  970): handleMessage: X
,I/dhcpcd  ( 6656): bind_interface: daemonise
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  970): handleMessage: E msg.what=196613,
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiP2pService(  970): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
D/WifiP2pService(  970): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1348): Power_Mode_Type mode = 0
D/PMS     (  970): releaseWL(29cd77f7): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1348): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  970): setDhcpActive: false
E/WifiStateMachine(  970): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  970): WifiStateMachine DHCP successful
E/WifiStateMachine(  970): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  970): link address 192.168.1.130/24
,E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): gateway: /192.168.1.1
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1348): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1348): htc_wext_set_keepalive +
I/wpa_supplicant( 1348): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1348): getPrivFuncNum +	
I/wpa_supplicant( 1348): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1348): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1348): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1348): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1348): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131210
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1348): environment dirty rate=0 [7][0][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72,
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
,D/wpa_supplicant( 1348): wlan0: Control interface command 'BLACKLIST clear'
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED -1 -> 3
E/wpa_supplicant( 1348): wlan0: BLACKLIST CLEAR 
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=51 dispatchEvent: BLACKLIST CLEAR 
D/ConnectivityService(  970): Adding iface wlan0 to network 101
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  970): NetworkAgent != null
,E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  970): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  970): WAN detection
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 25
,D/HtcWifiWanDetect(  970): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 4
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
,E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor ,
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  970): transitionTo: destState=ConnectedState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  970): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  970): invokeEnterMethods: ConnectedState
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  970): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  970): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 26
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 4553): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  970): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine(  970): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  970): Adding Route [fe80::/64 -> :: wlan0] to network 101
,E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131131
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: L2ConnectedState
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine(  970): handleMessage: X
,D/ConnectivityService(  970): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  970): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/WISPrService( 4553): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  970): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  970): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Connected
D/ConnectivityService(  970): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): currentScore = 0, newScore = 20
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):    accepting network in place of null
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/CSLegacyTypeTracker(  970): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  970): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  970): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  970): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  970): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  970): ensureActiveMobilePolicyLocked()
D/PMS     (  970): acquireWL(3cb4a4d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/ConnectivityService(  970): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I,/QuickSettingWifi( 1215): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/NetworkPolicy(  970): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 101]
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
V/NetworkPolicy(  970): updateIfacesLocked()
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1215): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524290
D/ConnectivityService(  970): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
V/NetworkPolicy(  970): updateNotificationsLocked()
D/WIFI    (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/usbnet  (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1215): dataConnected: false/false
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SecurityController( 1215): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524290
D/DATA_ICON( 1215): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,D/PMS     (  970): releaseWL(3cb4a4d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/SecurityController( 1215): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524290
D/DATA_ICON( 1215): dataConnected: false/false
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SecurityController( 1215): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QuickSettingWifi( 1215): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
,D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  970): [AlarmQueuing] connectivity wifi: false
D/PMS     (  970): acquireWL(2c01bcc9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - original mNetworkConnected = true,
,D/PMS     (  970): acquireWL(10b8cfce): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
D/GpsLocationProvider(  970): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  970): releaseWL(10b8cfce): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  970): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ConnectivityHelper( 1491): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  970): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6688 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  970): No APN found to select.
,D/PMS     (  970): releaseWL(2c01bcc9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6626): [cff.1.]  listen tmrbb8,
,D/MdScDataSum( 6626): [cff.1.] summary 118:p1 ignore,
,I/MusicStore( 6688): Database version: 120,
,D/VoldConnector(  970): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6688): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  970): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6688): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  970): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6688): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6688): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6688): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 6688): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6688): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6688): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@131620a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6688): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6688): GMSCore installation verified
,I/ConfigStore( 6688): Config Database version: 1
,D/PMS     (  970): releaseWL(20fd577a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  970): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6688, uid=10159, userID:0
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,D/MediaRouterService(  970): Client com.google.android.music (pid 6688): Registered,
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,I/MediaRouter( 6688): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6688): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6688): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6688): type=WIFI subType= reason=null isConnected=true
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6688, uid=10159, userID:0,
,D/AutoSetting( 1573): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 5852): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5852): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1573): service - onCreate()
,I/GHttpClientFactory( 6688): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6688): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1573): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/LocationManagerService(  970): request 3d72d241 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  970): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1573): service - onStartCommand() screen is off, don't request location
,I/iu.SyncManager( 4208): SYNC; picasa accounts
,D/NetworkLogImpl( 4208): Loaded NetworkSpeedPredictor,
,I/iu.Environment( 4208): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4208): num queued entries: 0
,I/iu.UploadsManager( 4208): num updated entries: 0
,I/iu.SyncManager( 4208): NEXT; no task
,D/ChimeraCfgMgr( 4208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  970): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6734 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6312): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 6312): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 6312): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6312): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6312): [NET] android_getaddrinfo_proxy+
D/libc    ( 6312): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 6312): [NET] android_getaddrinfo_proxy-, success
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 6312): connection state changed from UNKNOWN to CONNECTED
,W/Kids    ( 4208): [AccountUtils] Account not ready
W/Kids    ( 4208): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4208): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4208): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4208): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4208): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4208): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4208): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4208): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4208): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4208): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4208): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4208): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1215): reapply : com.google.android.gms 2 40,
,D/VoldConnector(  970): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6734): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  970): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6734): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files,
,I/GAv4    ( 6734): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6734):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6734):   adb logcat -s GAv4
,D/VoldConnector(  970): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6734): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  970): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,W/ContextImpl( 6734): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/GAv4    ( 6734): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6734): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6734): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Process (  970): killProcessQuiet, pid=6264
I/ActivityManager(  970): Killing 6264:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6264
,W/global  ( 6734): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6734): [apache-http] Connection GC has been deprecated!,
,I/art     (  970): Explicit concurrent mark sweep GC freed 59456(3MB) AllocSpace objects, 4(368KB) LOS objects, 33% free, 16MB/25MB, paused 1.660ms total 194.482ms,
,I/WebViewFactory( 6734): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/BluetoothAdapter( 6565): 831171112: getState(). Returning 12,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6565): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6565): BLE supported!!
I/jxcore-log( 6565): 
,I/LibraryLoader( 6734): Time to load native libraries: 28 ms (timestamps 7082-7110),
I/LibraryLoader( 6734): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6734): Binding Chromium to main looper Looper (main, tid 1) {22998ce}
,I/LibraryLoader( 6734): Expected native library version number "",actual native library version number "",
,I/chromium( 6734): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/WifiStateMachine(  970): handleMessage: E msg.what=131168
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
,E/WifiStateMachine(  970):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  970): handleMessage: X
,I/BrowserStartupController( 6734): Initializing chromium process, singleProcess=true
,W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6734): ApplicationContext is null in ApplicationStatus
,W/chromium( 6734): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6734): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6734): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6734): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6734): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6734): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6734): Local Branch: 
I/Adreno-EGL( 6734): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6734): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6734):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6734): Requires BLUETOOTH permission
,I/NSApplication( 6734): Starting up...
,I/ActivityManager(  970): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6794 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  970): killProcessQuiet, pid=5104
I/ActivityManager(  970): Killing 5104:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  970): Recipient 5104
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
D/HtcWifiWanDetect(  970): Find DNS Address www.htc.com/104.81.130.175
,D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  970): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  970): [AlarmQueuing] connectivity wifi: true
D/PMS     (  970): acquireWL(114bfaab): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/PMS     (  970): acquireWL(efc0508): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,I/ConnectivityHelper( 1491): [onReceive] WIFI(1): CONNECTED,
,D/PMS     (  970): releaseWL(efc0508): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  970): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  970): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/NetworkMonitor( 6688): type=WIFI subType= reason=null isConnected=true
D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,E/GpsLocationProvider(  970): No APN found to select.,
,D/PMS     (  970): releaseWL(114bfaab): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  970): acquireWL(1350f6c6): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024}
V/AlarmManager(  970): sending alarm PendingIntent{7cd9687: PendingIntentRecord{29d069b4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=137743, Int=0,
,D/MdScPhnSt( 6626): [985.1.]  listen tmrbb8,
,D/MdScDataSum( 6626): [985.1.] summary 118:p1 ignore
,D/Process (  970): killProcessQuiet, pid=5627
I/ActivityManager(  970): Killing 5627:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  970): Recipient 5627
,V/MusicLeanback( 6688): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5852): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1573): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 5852): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1573): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1573): service - onStartCommand() screen is off, don't request location
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4208, uid=10024, userID:0,
,D/ChimeraCfgMgr( 4208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PMS     (  970): acquireWL(35aa9d76): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1938 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(1350f6c6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1938): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1938): [NET] android_getaddrinfofornet-, err=8,
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/libc    ( 1938): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 1938): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1938): [NET] android_getaddrinfo_proxy+
D/libc    ( 1938): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,W/Kids    ( 4208): [AccountUtils] Account not ready
W/Kids    ( 4208): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4208): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4208): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4208): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4208): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4208): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4208): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4208): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4208): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4208): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4208): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4208): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1938): [NET] android_getaddrinfo_proxy-, success
,I/RemoteViews( 1215): reapply : com.google.android.gms 2 40
,D/libc    ( 1938): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1938): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1938): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1938): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  970): acquireWL(2f9b1b02): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1938 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1938): Connected
,D/PMS     (  970): releaseWL(35aa9d76): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2f9b1b02): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(2cd14c13): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1938): Message class com.google.f.a.a.p
D/PMS     (  970): releaseWL(2cd14c13): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(277db849): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6688 10159 null,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6688, uid=10159, userID:0
,I/ActivityManager(  970): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6838 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/PMS     (  970): releaseWL(277db849): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6688): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6688): Stop autocaching.
,W/ResourcesManager( 6838): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6838): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6838): VM with version 2.1.0 has multidex support,
I/MultiDex( 6838): install
,I/MultiDex( 6838): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6838): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6838): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6838): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39676cf7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6838): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1938): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1938): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4208): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 6838): callingUid 10024, callindPid: 6838,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4208, uid=10024, userID:0,
,D/LocationInitializer( 4208): Restart initialization of location
,E/MDM     ( 1830): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6688): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6688): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  970): acquireWL(3e78cc7b): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 970 1000 null
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605,
,D/Process (  970): killProcessQuiet, pid=6342
I/ActivityManager(  970): Killing 6342:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6342
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233392e),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  970): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  970): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  970): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  970):  [handleDownloadXtraData]inject done.,
D/PMS     (  970): acquireWL(ebdb557): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  970): releaseWL(3e78cc7b): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  970): releaseWL(ebdb557): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,D/PMS     (  970): acquireWL(2c50e844): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024},
V/AlarmManager(  970): sending alarm PendingIntent{2dcfcd2d: PendingIntentRecord{2fcc4262 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=146861, Int=0
,D/PMS     (  970): releaseWL(2c50e844): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/PMS     (  970): acquireWL(ffe4ff3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{226f0df4: PendingIntentRecord{3e41791d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=151704, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{149644b0: PendingIntentRecord{1d090f29 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1450658048302, Int=0
D/PMS     (  970): acquireWL(23022ae): PARTIAL_WAKE_LOCK  *backup* 0x1 970 1000 null
,W/BackupManagerService(  970): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
,E/BackupManagerService(  970): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  970): releaseWL(23022ae): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  970): releaseWL(ffe4ff3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/AutoSetting( 1573): service - handleMessage() stop self
,D/AutoSetting( 1573): service - handleMessage() quit looper
,D/AutoSetting( 1573): service - onDestroy() END
,E/WifiStateMachine(  970): handleMessage: E msg.what=131165
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState,
E/WifiStateMachine(  970):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): handleMessage: X
,D/PMS     (  970): acquireWL(19a3f84f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(19a3f84f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-,
,D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
,D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1441): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5
,E/WifiStateMachine(  970): handleMessage: E msg.what=131326,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState what:131326 2 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  970): handleMessage: X
,D/PMS     (  970): acquireWL(3c92fbdc): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024},
,V/AlarmManager(  970): sending alarm PendingIntent{3b7a74e5: PendingIntentRecord{30dfbbba com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190520, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{2651ca6b: PendingIntentRecord{3641f9c8 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=210215, Int=0
,D/PMS     (  970): acquireWL(2ce27a61): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(3c92fbdc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  970): acquireWL(25bdd986): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2ce27a61): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  970): releaseWL(25bdd986): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1ddc39e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1ddc39e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(33a71499): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(33a71499): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(2dc0935e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(99933f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(214b6155): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2dc0935e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1938): Vacuum at: now=1450658098796 tag=VacuumService
,D/PMS     (  970): releaseWL(99933f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(161e245b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1938): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1938): No account for auth token provided,
,D/PMS     (  970): releaseWL(161e245b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(134b64f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(134b64f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1938): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1938): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1938): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1938): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1938): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1938): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1938): [NET] android_getaddrinfo_proxy-, success,
,D/libc    ( 1938): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1938): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1938): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1938): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1938): No account for auth token provided
,W/Uploader( 1938): No account for auth token provided,
,W/Uploader( 1938): No account for auth token provided,
,W/Uploader( 1938):  no longer exists, so no auth token.,
,W/Uploader( 1938): No account for auth token provided,
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
,E/Uploader( 1938): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1938): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1938): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1938): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1938): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1938): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1938): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1938): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1938): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1938): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1938): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1938): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1938): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  970): releaseWL(214b6155): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(1b71983c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1b71983c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(62849c5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(62849c5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcAppUPService( 1573): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@153a432
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  970): killProcessQuiet, pid=5682
I/ActivityManager(  970): Killing 5682:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5682
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  970): acquireWL(38ff9f1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(38ff9f1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+,
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  970): updateBatteryInfo
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/PMS     (  970): runPSCheck
,D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
,D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): << updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1348): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
,D/PMS     (  970): acquireWL(f6cda4b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(f6cda4b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
,D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  970): battery changed pluggedType: 2
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  970): acquireWL(1cddfc28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): releaseWL(1cddfc28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/NotificationService(  970): plugged=true pluggin=true
D/PMS     (  970): runPSCheck
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
,D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: StaEnabledState
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): processMsg: DefaultState
,I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(1c48bd41): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{226f0df4: PendingIntentRecord{3e41791d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=211705, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{34acd027: PendingIntentRecord{3a2ab2d4 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1450658249578, Int=0
,D/PMS     (  970): releaseWL(1c48bd41): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1215): Weather sync is On,
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  970): acquireWL(2aa2ec7d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(2aa2ec7d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): updateBatteryInfo
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652,
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  970): acquireWL(311af772): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(311af772): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+,
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
,D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(340c47c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(340c47c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): closing low battery warning: level=100
,D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): << updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1441): MSG_CHECK_DELETION >>,
,D/ContactMessageStore( 1441): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1441): sku_id=118,
,D/ContactMessageStore( 1441): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1441): start background delete task...
,D/ContactMessageStore( 1441): size: 0 , 0
,D/ContactMessageStore( 1441): Background delete complete
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
,D/PMS     (  970): acquireWL(2aea2840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/UsbnetService(  970): onReceive BATTERY_CHANGED
,I/BatteryService(  970): n_update end
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): releaseWL(2aea2840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  970): updateBatteryInfo
D/NotificationService(  970): plugged=true pluggin=true
D/WifiController(  970): handleMessage: E msg.what=155652
D/PMS     (  970): runPSCheck
D/WifiController(  970): processMsg: DeviceActiveState
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: StaEnabledState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): << updateStatus
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(3f76d379): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3f76d379): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo,
D/UsbnetService(  970): BroadcastReceiver::onReceive+
,D/NotificationService(  970): plugged=true pluggin=true,
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(29d18be): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(29d18be): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  970): updateBatteryInfo
,D/PowerUI ( 1215): closing low battery warning: level=100,
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
,D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): << updateStatus
,D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(1b619d1f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{226f0df4: PendingIntentRecord{3e41791d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=391704, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{b69886c: PendingIntentRecord{33082e35 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=944667, Int=0,
I/bt-btm  ( 3370): Received oneshot timer event complete
I/bt-btm  ( 3370): btm_ble_timeout
I/bt-btm  ( 3370): btm_gen_resolvable_private_addr
,D/PMS     (  970): acquireWL(2a8e02ca): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3370 1002 null
,D/bt-btm  ( 3370): btm_ble_rand_enc_complete
I/bt-btm  ( 3370): btm_gen_resolve_paddr_low
D/bt-smp  ( 3370): smp_encrypt_data
W/bt-smp  ( 3370): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3370): Plain text(LSB ~ MSB) = f6 4e 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3370): Encrypted text(LSB ~ MSB) = 65 60 08 58 77 7b 73 37 af f8 84 2b 5e 78 88 56 
I/bt-btm  ( 3370): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3370): Stopping oneshot timer
D/bt-btm  ( 3370): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  970): releaseWL(1b619d1f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  970): releaseWL(2a8e02ca): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  970): acquireWL(158cec3b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(158cec3b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(d9cbf58): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{226f0df4: PendingIntentRecord{3e41791d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=991704, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{241a78b1: PendingIntentRecord{39f18196 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450658905028, Int=0
,D/SmartSyncUtils( 6463): isEpsOn(), nState = 0
,D/PMS     (  970): acquireWL(11541117): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6463 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6463): [updateNmRange] bManual = false,
,D/WeatherUtility( 1215): Weather sync is On
D/SmartSyncScreenOnOffTimeReceiver( 6463): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  970): releaseWL(d9cbf58): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6463): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6463): SettingOnTime = 1450677600000, randomSettingOnTime = 1450676260000
D/SmartSyncScreenOnOffTimeReceiver( 6463): SettingOffTime = 1450742400000, randomSettingOffTime = 1450742904000
D/SmartSyncScreenOnOffTimeReceiver( 6463): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6463): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6463): bNightModeTurnOffOnce = false
,D/PMS     (  970): acquireWL(cca7904): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{2ceeed: PendingIntentRecord{3c3c2122 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450658905078, Int=0
,D/PMS     (  970): releaseWL(11541117): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncDataLinkTurnOffService( 6463): SMARTSYNC_TURN_OFF_NETWORK, current time = 1450658905097, randomOffTime = 1450742904000, newRandomOffTime = 1450742904000
,D/SmartSyncDataLinkTurnOffService( 6463): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 1450676260000, randomMobileOnTime = 1450676260000
,I/ActivityManager(  970): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=6886 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
V/AlarmManager(  970): sending alarm PendingIntent{2ff82170: PendingIntentRecord{25eee9b6 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450658574935, Int=0
,I/ActivityManager(  970): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6902 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  970): sending alarm PendingIntent{13768ce9: PendingIntentRecord{d9f2d6e com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1450658611168, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{28a6ce7b: PendingIntentRecord{10119498 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=809630, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{1db20c0f: PendingIntentRecord{268c916b com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450658854068, Int=0,
I/art     (  444): Explicit concurrent mark sweep GC freed 8653(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 250us total 35.114ms
,W/ContextImpl( 6463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  970): releaseWL(cca7904): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6463): MY_DEBUG = false
,D/PowerUsageService( 6463): repeat time = 1450659805186,
I/art     (  444): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 162us total 31.968ms
,D/SmartSyncUtils( 6463): getMobilePolicyEnabled, result = true
D/SmartSyncDataLinkTurnOffService( 6463): turnOffMobile bPolicyEnabled = true
,D/SmartSyncUtils( 6463): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 6463): turnOffMobile bCheckMobileData = false
,I/art     (  444): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 159us total 20.724ms
,D/LocationManagerService(  970): getProviders()=[gps, network]
,D/LocationManagerService(  970): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  970): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 6463): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6463): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 6463): turnOffWifi ui setting = true
D/SmartSyncUtils( 6463): isWifiHotSpotEnabled = false
I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi
D/SmartSyncUtils( 6463): state = 0
E/ActivityThread( 6463): Failed to find provider info for com.htc.vowifi,
D/SmartSyncDataLinkTurnOffService( 6463): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 6463): turnOffWifi bWifiConnected = true
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6886, uid=10072, userID:0
,W/global  ( 6886): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 6886): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 6886): [apache-http] Connection GC has been deprecated!
,I/PowerUsageList:PowerUsageHelper( 6463): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6463): gen(), null == sipper.uidObj, userId = 0,
,E/cutils-trace( 6936): Error opening trace file: Permission denied (13)
,W/global  ( 6886): [apache-http] Connection GC has been deprecated!,
,I/dex2oat ( 6936): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6936): dex2oat: override thread count:4
,D/Finsky  ( 6886): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  970): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6947 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 6886): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6886): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6886, uid=10072, userID:0,
,W/ResourcesManager( 6947): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6947): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6886): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
I/MultiDex( 6947): VM with version 2.1.0 has multidex support
I/MultiDex( 6947): install
I/MultiDex( 6947): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6886): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6886): [1] 2.run: Finished loading 1 libraries.
V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6886): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 6947): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/Finsky  ( 6886): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ActivityThread( 6947): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6947): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39676cf7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6947): Installed default security provider GmsCore_OpenSSL
,I/art     (  970): Explicit concurrent mark sweep GC freed 33262(1698KB) AllocSpace objects, 6(708KB) LOS objects, 33% free, 16MB/25MB, paused 1.644ms total 165.080ms
,D/GCM     ( 1938): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1938): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4208): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 6838): callingUid 10024, callindPid: 6838
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4208, uid=10024, userID:0
,E/MDM     ( 1830): [131] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/LocationInitializer( 4208): Restart initialization of location
,W/Finsky  ( 6886): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1938): Explicit concurrent mark sweep GC freed 35473(1979KB) AllocSpace objects, 10(668KB) LOS objects, 47% free, 4MB/8MB, paused 1.234ms total 84.379ms
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6886): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,I/dex2oat ( 6936): dex2oat took 759.730ms (threads: 4)
,I/PushClient( 6902): ApplicationMonitor {188bd627}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6902): ApplicationMonitor {188bd627}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6902): ApplicationMonitor {188bd627}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6902): ApplicationMonitor {188bd627}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6902): ApplicationMonitor {188bd627}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6902): ApplicationMonitor {188bd627}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6902): ApplicationMonitor {188bd627}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6902): ApplicationMonitor {188bd627}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6902): ApplicationMonitor {188bd627}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6902): PnsModel {d67f0e6}: update(): Update registration caused by: alarm
,V/Finsky  ( 6886): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/PushClient( 6902): PnsConfigModel {31966435}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6902): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 6902): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6902): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.,
,W/ContextImpl( 6902): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  970): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6990 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,E/AndroidHttpClient( 6886): Leak found
E/AndroidHttpClient( 6886): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 6886): 	,at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 6886): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 6886): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 6886): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 6886): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 6886): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 6886): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 6886): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 6886): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 6886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 6886): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 6886): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 6886): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 6886): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 6886): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 6886): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/DeviceManagement( 6990): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6990 dbg=false s=true,
,I/DeviceManagement( 6990): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6990): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,D/Finsky  ( 6886): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  970): acquireWL(19b62348): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10072}
V/AlarmManager(  970): sending alarm PendingIntent{2fd25e1: PendingIntentRecord{25eee9b6 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450658906386, Int=0
D/PMS     (  970): releaseWL(19b62348): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,I/DeviceManagement( 6990): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6990): WorkflowService: Starting workflow service
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/DeviceManagement( 6990): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@d67f0e6] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6990): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6990): ModelRegistry: Loading model meta data from resources...
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6886): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DeviceManagement( 6990): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6990): SessionStateController: Checking invariants...
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6886): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6886): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6886): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6886): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 6886): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2),
,I/DeviceManagement( 6990): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,D/DeviceConnectionService( 1830): client connected with version: 7571000
,I/DeviceManagement( 6990): SessionStateController: Checking invariants...,
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 6886): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 6886): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,I/DeviceManagement( 6990): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,D/Finsky  ( 6886): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6886): [1] DailyHygiene.reschedule: Scheduling new run in 89 minutes (failures=3),
,I/DeviceManagement( 6990): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@d67f0e6],
,D/DeviceConnectionService( 1830): client connected with version: 7571000
,I/DeviceManagement( 6990): WorkflowService: Stopping workflow service
,D/Process (  970): killProcessQuiet, pid=6407,
I/ActivityManager(  970): Killing 6407:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6902): PnsModel {d67f0e6}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  970): Recipient 6407,
,D/Process (  970): killProcessQuiet, pid=6520
I/ActivityManager(  970): Killing 6520:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  970): acquireWL(7db738f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(7db738f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  970): Recipient 6520
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  970): runPSCheck
,D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X,
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  970): Killing 4553:com.android.settings/1000 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=4553
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4553,
D/WifiService(  970): Client connection lost with reason: 4
,D/Process (  970): killProcessQuiet, pid=6626
I/ActivityManager(  970): Killing 6626:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6626
,D/PMS     (  970): acquireWL(ee08225): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10072},
,V/AlarmManager(  970): sending alarm PendingIntent{adcdffa: PendingIntentRecord{21a5b9ab com.android.vending startService}}, i=null, t=0, cnt=1, w=1450658921653, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{17645808: PendingIntentRecord{26bc1ba1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1038766, Int=0
D/PMS     (  970): acquireWL(e0901c6): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(ee08225): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/PMS     (  970): releaseWL(e0901c6): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(1d844587): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(2beaecb4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(1b837452): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1d844587): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(2465e7f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1938): Message class com.google.f.a.a.i
,D/PMS     (  970): releaseWL(2465e7f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1938): Using platform SSLCertificateSocketFactory
,D/PMS     (  970): releaseWL(1b837452): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(25e1d338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(25e1d338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(2beaecb4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/Finsky  ( 6886): [682] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 6886): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  970): acquireWL(4d22f11): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(4d22f11): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(ffb6876): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(ffb6876): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(29239e77): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(29239e77): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(257ceae4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(257ceae4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: StaEnabledState
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(1619ab4d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{226f0df4: PendingIntentRecord{3e41791d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1051704, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{5ad9602: PendingIntentRecord{1629ab13 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450659085239, Int=0
,W/ContextImpl( 6463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncDataLinkTurnOffService( 6463): turnOffWifi ui setting = true
,D/SmartSyncUtils( 6463): isWifiHotSpotEnabled = false
,I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 6463): Failed to find provider info for com.htc.vowifi
,D/SmartSyncUtils( 6463): state = 0
D/SmartSyncDataLinkTurnOffService( 6463): turnOffWifi bCheckWifiData = false
D/PMS     (  970): releaseWL(1619ab4d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/SmartSyncDataLinkTurnOffService( 6463): turnOffWifi bWifiConnected = true
D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
D/LocationManagerService(  970): getProviders()=[gps, network]
D/LocationManagerService(  970): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  970): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 6463): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0,
D/SmartSyncUtils( 6463): isCharging status = 5
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  970): User[0] Flushing usage stats to disk,
,D/PMS     (  970): acquireWL(23e2af49): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(23e2af49): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): updateBatteryInfo
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
,D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,I/art     (  970): Explicit concurrent mark sweep GC freed 25657(1300KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 16MB/24MB, paused 1.616ms total 178.178ms,
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1215): reapply : com.google.android.gms 2 40,
,W/GLSActivity( 1938): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1938): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1938): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1938): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1938): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1938): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1938): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6886): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 6886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6886): 	at android.os.Binder.execTransact(Binder.java:454)
,W/ResourcesManager( 1309): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/ResourcesManager( 1309): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/ResourcesManager( 1309): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1309): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/System  ( 6886): Ignoring header User-Agent because its value was null.,
D/libc    ( 6886): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6886): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6886): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6886): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6886): [NET] android_getaddrinfo_proxy+
D/libc    ( 6886): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6886): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  970): acquireWL(1f222e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(1f222e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  970): updateBatteryInfo
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(22b8fcb9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(22b8fcb9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652,
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  970): << updateStatus
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(15da28fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(15da28fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  970): acquireWL(38d5085f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(38d5085f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(33bbb2ac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
,I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(33bbb2ac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
,D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  970): handleMessage: X
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): << updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  970): acquireWL(1e2bd70a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{226f0df4: PendingIntentRecord{3e41791d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1231705, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{febcb7b: PendingIntentRecord{3b874d98 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1844680, Int=0
,I/bt-btm  ( 3370): Received oneshot timer event complete,
I/bt-btm  ( 3370): btm_ble_timeout
,I/bt-btm  ( 3370): btm_gen_resolvable_private_addr
,D/PMS     (  970): acquireWL(2dd089f1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3370 1002 null
,D/bt-btm  ( 3370): btm_ble_rand_enc_complete,
I/bt-btm  ( 3370): btm_gen_resolve_paddr_low
D/bt-smp  ( 3370): smp_encrypt_data
W/bt-smp  ( 3370): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3370): Plain text(LSB ~ MSB) = 0f 21 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3370): Encrypted text(LSB ~ MSB) = ec 7e c5 11 68 2d 76 fe 15 a6 5b b0 90 fc b3 1e 
I/bt-btm  ( 3370): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3370): Stopping oneshot timer
D/bt-btm  ( 3370): Starting oneshot timer type:103 timeout:900s
,I/ProcessStatsService(  970): Prepared write state in 28ms,
,I/ProcessStatsService(  970): Prepared write state in 13ms
,I/ProcessStatsService(  970): Prepared write state in 11ms,
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
D/PMS     (  970): releaseWL(1e2bd70a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/ProcessStatsService(  970): Pruning old procstats: /data/system/procstats/state-2015-12-20-04-12-29.bin,
,D/PMS     (  970): releaseWL(2dd089f1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  970): acquireWL(2d3859d6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(2d3859d6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1215): closing low battery warning: level=100
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
,D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/HtcPowerSaver(  970): updateBatteryInfo
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/PMS     (  970): runPSCheck
,D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(3de1a457): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): releaseWL(3de1a457): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/HeadsetStateMachine( 3370): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): processMsg: DeviceActiveState
,I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1800000ms),D/PMS     (  970): acquireWL(b6fab44): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{28a6ce7b: PendingIntentRecord{10119498 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1736887, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{850a338: PendingIntentRecord{1160bf11 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825556, Int=1800000
D/Process (  970): killProcessQuiet, pid=6312
I/ActivityManager(  970): Killing 6312:com.google.android.talk/u0a112 (adj 13): empty for 1800s
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/PMS     (  970): acquireWL(1f52d42d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
I/ActivityManager(  970): Recipient 6312
D/Process (  970): killProcessQuiet, pid=5752
I/ActivityManager(  970): Killing 5752:com.google.android.apps.plus/u0a167 (adj 13): empty for 1800s
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  970): Recipient 5752
D/Process (  970): killProcessQuiet, pid=6794
I/ActivityManager(  970): Killing 6794:com.android.chrome/u0a96 (adj 13): empty for 1800s
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  970): Recipient 6794
D/Process (  970): killProcessQuiet, pid=6734
I/ActivityManager(  970): Killing 6734:com.google.android.apps.magazines/u0a161 (adj 13): empty for 1800s
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  970): Recipient 6734
D/Process (  970): killProcessQuiet, pid=5852
I/ActivityManager(  970): Killing 5852:com.google.android.setupwizard/u0a77 (adj 15): empty for 1800s
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  970): Recipient 5852
D/Process (  970): killProcessQuiet, pid=6432
I/ActivityManager(  970): Killing 6432:com.htc.bgp/u0a11 (adj 15): empty for 1800s
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  970): Recipient 6432
V/AlarmManager(  970): sending alarm PendingIntent{226f0df4: PendingIntentRecord{3e41791d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1891705, Int=0
D/PMS     (  970): releaseWL(1f52d42d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/AlarmManager(  970): sending alarm PendingIntent{1ab83d62: PendingIntentRecord{1ef22ef3 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450659538020, Int=1800000
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
V/AlarmManager(  970): sending alarm PendingIntent{3a5e37b0: PendingIntentRecord{11358629 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1856703, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{f60cdae: PendingIntentRecord{26bc1ba1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1938990, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{d76c74f: PendingIntentRecord{268c916b com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450659805186, Int=0
D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
D/PMS     (  970): acquireWL(22671edc): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4208 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(37f016ba): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4208 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(22671edc): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(313e5147): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(313e5147): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 6463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  970): releaseWL(b6fab44): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
I/EventLogService( 4208): Aggregate from 1450657978227 (log), 1450657737959 (data)
D/PowerUsageList:PowerUsageHelper( 6463): MY_DEBUG = false
D/PowerUsageService( 6463): repeat time = 1450660728376
D/LocationManagerService(  970): getAllProviders()=[passive, gps, network]
D/PMS     (  970): acquireWL(23e223f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
D/GCM     ( 1938): Message class com.google.f.a.a.i
D/PMS     (  970): releaseWL(23e223f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(37f016ba): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
I/GLSUser ( 1938): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1938): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1938): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1938): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1938): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PowerUsageList:PowerUsageHelper( 6463): PowerProfile::POWER_SCREEN_FULL = 154.8
D/PowerUsageList:BatterySipperExt( 6463): gen(), null == sipper.uidObj, userId = 0
E/cutils-trace( 7037): Error opening trace file: Permission denied (13)
D/CustomizationManager( 7037): ====startRecUseTime====
D/htc.customization.log.level( 7037):  is 
W/CustomizationLogLevel( 7037): Level value is invalid, use default level 2
D/CustomizationManager( 7037):  Read ACC file spent 0.043 (s)
D/CIDMapFileReader( 7037): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7037): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7037): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7037): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7037): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7037): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7037): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7037): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7037): Parsing tag category name = system
I/CustomizationCIDLoader( 7037): Parsing tag category name = application
I/CustomizationCIDLoader( 7037): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7037): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7037): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7037): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7037): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7037): add string-array item, value = 42507
I/CustomizationCIDLoader( 7037): add string-array item, value = 21902
I/CustomizationCIDLoader( 7037): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7037): add string-array item, value = 23420
I/CustomizationCIDLoader( 7037): add string-array item, value = 22299
I/CustomizationCIDLoader( 7037): add string-array item, value = 24002
I/CustomizationCIDLoader( 7037): add string-array item, value = 23210
I/CustomizationCIDLoader( 7037): add string-array item, value = 23205
I/CustomizationCIDLoader( 7037): add string-array item, value = 23806
I/CustomizationCIDLoader( 7037): add string-array item, value = 23430
I/CustomizationCIDLoader( 7037): add string-array item, value = 23408
I/CustomizationCIDLoader( 7037): add string-array item, value = 27205
I/CustomizationCIDLoader( 7037): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7037): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7037):  Read CID file spent 0.089 (s)
D/CustomizationManager( 7037):  All configurations done spent 0.089 (s)
D/PackageManager(  970): deletePackageAsUser: pkg=com.test.thalitest, pid=7037, uid=2000 userid=0
I/ActivityManager(  970): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  970): killProcessQuiet, pid=6565
I/ActivityManager(  970): Killing 6565:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  970): Skipping PackageSetting{3dee69ed com.example.hello/10374} due to missing metadata
I/ActivityManager(  970): Recipient 6565
I/WindowState(  970): WIN DEATH: Window{2d292622 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  970): Client connection lost with reason: 4
E/InputEventReceiver( 1384): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{d7826e uid 10366 pid 6565} (c)'
I/ActivityManager(  970):   Force finishing activity ActivityRecord{3e997b2f u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  970): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  970):   Force finishing activity ActivityRecord{3e997b2f u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  970): Duplicate finish request for ActivityRecord{3e997b2f u0 com.test.thalitest/.MainActivity t8 f}
D/DotMatrix( 1309): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
W/ActivityManager(  970): Spurious death for ProcessRecord{38581a37 6565:com.test.thalitest/u0a366}, curProc for 6565: null
D/DotMatrix( 1309): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  970): acquireWL(3d6a14c2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1830 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1830): Ignoring removeGeofence because network location is disabled.
W/SystemReader(  970): Cannot find grip_rejection_width, use default value instead
D/PMS     (  970): releaseWL(3d6a14c2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1708): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/InputMethodManagerService(  970): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/VoicemailCleanupService( 1682): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1708): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/art     ( 1491): Explicit concurrent mark sweep GC freed 6110(317KB) AllocSpace objects, 7(600KB) LOS objects, 34% free, 29MB/45MB, paused 1.231ms total 95.059ms
I/Prism.ItemManager( 1491): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1491): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/Prism.PackageStateRece_( 1491): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1573): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/Launcher( 1491): Deferring update until onResume
D/Launcher( 1491): waitUntilResume // bindAppsRemoved
I/[PluginManager]RegisterService( 1573): handle notify Blinkfeed plugin client changed
I/ActivityManager(  970): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7059 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  970): killProcessQuiet, pid=6688
I/ActivityManager(  970): Killing 6688:com.google.android.music:main/u0a159 (adj 15): empty for 1800s
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager(  970): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/AccTypeManager( 1708): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PhoneApp( 1441): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ExternalAccountType( 1708): Unsupported attribute readOnly
I/art     (  970): Explicit concurrent mark sweep GC freed 29449(2031KB) AllocSpace objects, 9(868KB) LOS objects, 33% free, 16MB/25MB, paused 1.505ms total 240.866ms
I/art     (  970): WaitForGcToComplete blocked for 226.356ms for cause Explicit
I/ActivityManager(  970): Recipient 6688
D/MediaRouterService(  970): Client com.google.android.music (pid 6688): Died!
W/PackageManager(  970): Unable to load service info ResolveInfo{33a6345d com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  970): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  970): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  970): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  970): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  970): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/JobSchedulerService(  970): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  970): Explicit concurrent mark sweep GC freed 6591(392KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.967ms total 178.175ms
W/asset   (  970): Copying FileAsset 0x5568760a60 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/TaskPersister(  970): removeObsoleteFile: deleting file=8_task.xml
D/StatusBarManagerService(  970): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/StatusBarManagerService(  970): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/FindExtension( 1491): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/ContextImpl( 7059): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
I/ThreadedRenderer( 1491): Defer allocateBuffers to drawing time
W/InputMethodManagerService(  970): Got RemoteException sending setActive(false) notification to pid 6565 uid 10366
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
I/ActivityManager(  970): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7083 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7083): -onCreate()
V/Settings:HtcSettingsApplication( 7083): [7083/7083] onCreate()
E/NetworkScheduler.SchedulerReceiver( 1938): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1938): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  970): acquireWL(24f9aef4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1938 10024 WorkSource{10024 com.google.android.gms}
D/Settings:HtcWirelessFeatureFlags( 7083): id/is att sku: 118/false
D/PMS     (  970): releaseWL(24f9aef4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/ChimeraCfgMgr( 4208): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4208): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 4208): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
E/Settings:HtcWrapHeaderInfo( 7083): no such activity!
D/AccountUtils( 4208): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4208): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4208): Module APK com.google.android.play.games already loaded
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7083): The wrap header doesn't exist in header list.
E/SQLiteLog( 4208): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4208): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/games_3a3529a.db, handle: 0x5568540970
I/ActivityManager(  970): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7118 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
E/AndroidRuntime( 4208): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 4208): Process: com.google.android.gms, PID: 4208
E/AndroidRuntime( 4208): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4208): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4208): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 4208): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4208): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4208): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 4208): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:512)
E/AndroidRuntime( 4208): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 4208): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 4208): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 4208): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 4208): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 4208): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 4208): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 4208): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 4208): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 4208): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4208): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4208): 	at java.lang.Thread.run(Thread.java:818)
E/ActivityManager(  970): App crashed! Process: com.google.android.gms
E/Settings:HtcWrapHeaderInfo( 7083): updateDevelopment, bPrefShow = true
D/Process ( 4208): killProcess, pid=4208
E/Settings:HtcUmcWidgetEnabler( 7083): isSupportMusicChannel(): false
D/Process ( 4208): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  970): Can't write: system_app_crash
E/DropBoxManagerService(  970): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  970): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  970): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  970): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  970): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  970): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  970): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  970): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  970): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  970): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  970): 	... 5 more
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]support         :false
I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7083): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7083): isSupportVoWifi: null
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7083): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 7083): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 7083): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7083): [supportHomeButton]support         :false
I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 7083): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7083): isSupportVoWifi: null
I/ActivityManager(  970): Recipient 4208
D/WifiService(  970): Client connection lost with reason: 4
I/ActivityManager(  970): Process com.google.android.gms (pid 4208) has died
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  970): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
I/GAv4    ( 7118): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7118):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7118):   adb logcat -s GAv4
W/GAv4    ( 7118): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7118): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 7118): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7118): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7118): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 7118): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 7118): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
E/SQLiteDatabase( 7118): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7118): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7118): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7118): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7118): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7118): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7118): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7118): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7118): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7118): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7118): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7118): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7118): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7118): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7118): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7118): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7118): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 7118): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 7118): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7118): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7118): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7118): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7118): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7118): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7118): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7118): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7118): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7118): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7118): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7118): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7118): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7118): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7118): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7118): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7118): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7118): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7118): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7118): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7118): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7118): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 7118): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7118): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7118): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7118): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7118): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7118): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7118): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7118): 	at aen.run(PG:536)
I/ActivityManager(  970): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=7154 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 7154): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7154): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/VoldConnector(  970): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 7118): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
E/SQLiteDatabase( 7118): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7118): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7118): 	
```
