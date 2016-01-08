#### Test 549702610b97681_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  932): Killing 5522:com.htc.musicenhancer/u0a49 (adj 15): empty #17
--------- beginning of main
D/Process (  932): killProcessQuiet, pid=5522
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  932): Recipient 5522
E/cutils-trace( 6646): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6646): ====startRecUseTime====
D/htc.customization.log.level( 6646):  is 
W/CustomizationLogLevel( 6646): Level value is invalid, use default level 2
D/CustomizationManager( 6646):  Read ACC file spent 0.041 (s)
D/CIDMapFileReader( 6646): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6646): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6646): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6646): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6646): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6646): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6646): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6646): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6646): Parsing tag category name = system
I/CustomizationCIDLoader( 6646): Parsing tag category name = application
I/CustomizationCIDLoader( 6646): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6646): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6646): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6646): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6646): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6646): add string-array item, value = 42507
I/CustomizationCIDLoader( 6646): add string-array item, value = 21902
I/CustomizationCIDLoader( 6646): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6646): add string-array item, value = 23420
I/CustomizationCIDLoader( 6646): add string-array item, value = 22299
I/CustomizationCIDLoader( 6646): add string-array item, value = 24002
I/CustomizationCIDLoader( 6646): add string-array item, value = 23210
I/CustomizationCIDLoader( 6646): add string-array item, value = 23205
I/CustomizationCIDLoader( 6646): add string-array item, value = 23806
I/CustomizationCIDLoader( 6646): add string-array item, value = 23430
I/CustomizationCIDLoader( 6646): add string-array item, value = 23408
I/CustomizationCIDLoader( 6646): add string-array item, value = 27205
I/CustomizationCIDLoader( 6646): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6646): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6646):  Read CID file spent 0.085 (s)
D/CustomizationManager( 6646):  All configurations done spent 0.085 (s)
D/wpa_supplicant( 1356): Wireless event: cmd=0x8c02 len=23
I/wpa_supplicant( 1356): WEXT: Custom wireless event: 'TX_FAIL'
D/wpa_supplicant( 1356): wlan0: Event UNKNOWN (50) received
I/wpa_supplicant( 1356): Got ENV Dirty
I/wpa_supplicant( 1356): WifiHtcOffload Got ENV Dirty, enabled = 0
I/wpa_supplicant( 1356): WifiHtcOffload bt-a2dp-status = 0  bt-sco-status = 0  isConcurrentMode = 0
E/wpa_supplicant( 1356): wlan0: TX_FAIL_NOTIFICATION
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  932): Event [IFNAME=wlan0 TX_FAIL_NOTIFICATION]
D/Tethering(  932): interfaceLinkStateChanged wlan0, true
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=39 dispatchEvent: TX_FAIL_NOTIFICATION
D/Tethering(  932): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
I/ActivityManager(  932): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6646 on display 0
D/PMS     (  932): acquireHCC(e949fa6): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 932 1000 null
D/PMS     (  932): acquireHCC(1e50bde7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 932 1000 null
I/ActivityManager(  932): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6664 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1310): [EventService]  onDisplayChanged: 0
V/ActivityManager(  932): Display changed displayId=0
D/DotMatrix( 1310): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1543): [trimMemory] 20
I/WebViewFactory( 6664): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6664): Time to load native libraries: 9 ms (timestamps 8822-8831)
,I/LibraryLoader( 6664): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6664): Binding Chromium to main looper Looper (main, tid 1) {788ef46}
,I/LibraryLoader( 6664): Expected native library version number "",actual native library version number ""
,I/chromium( 6664): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6664): Initializing chromium process, singleProcess=true
,W/art     ( 6664): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6664): ApplicationContext is null in ApplicationStatus
,W/chromium( 6664): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6664): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6664): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6664): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6664): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6664): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6664): Local Branch: 
I/Adreno-EGL( 6664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6664): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6664):                  d74aa161a12b9c6fc6332151
,W/System.err(  932): java.lang.Throwable: stack dump
,W/System.err(  932): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  932): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  932): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  932): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  932): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  932): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@312adb2c:true
,D/BluetoothAdapter( 6664): 886356434: getState(). Returning 12
,W/art     ( 6664): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6664): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6664): CordovaWebView is running on device made by: HTC
,W/art     ( 6664): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6664): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  932): Activity pause timeout for ActivityRecord{9e76d94 u0 com.test.thalitest/.MainActivity t8},
,W/HtcSystemUPManager(  932): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/chromium( 6664): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  932): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  932): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  932): hiding MENU key
,D/StatusBarManagerService(  932): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  932): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  932): hiding MENU key
,D/FindExtension( 6664): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6664): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@797b2d0, mServedView=org.apache.cordova.engine.SystemWebView{10f2b2c9 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3a458dce
I/InputMethodManagerService(  932): Disable input method client, pid=1543
I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
D/StatusBarManagerService(  932): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6664): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  932): Displayed com.test.thalitest/.MainActivity: +653ms (total +696ms),
,W/BindingManager( 6664): Cannot call determinedVisibility() - never saw a connection for the pid: 6664,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/JsMessageQueue( 6664): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6664): JniHelper::setJavaVM(0xab2108f8), pthread_self() = -1405004104
D/JX-Cordova( 6664): jxcore cordova android initializing
,I/art     ( 6664): Background sticky concurrent mark sweep GC freed 27288(2MB) AllocSpace objects, 0(0B) LOS objects, 5% free, 11MB/12MB, paused 5.796ms total 30.380ms
,W/jxcore-log( 6664): Initializing JXcore engine,
W/jxcore-log( 6664): JXcore engine is ready
,W/jxcore-log( 6664): Starting JXcore engine
,W/jxcore-log( 6664): Platform android
W/jxcore-log( 6664): 
W/jxcore-log( 6664): Process ARCH arm
W/jxcore-log( 6664): 
,D/PMS     (  932): releaseHCC(e949fa6): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  932): releaseHCC(1e50bde7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6664): JXcore Cordova bridge is ready!,
I/jxcore-log( 6664): 
W/jxcore-log( 6664): JXcore engine is started
,I/chromium( 6664): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6664): Toggling radios to true,
I/jxcore-log( 6664): 
,D/BluetoothAdapter( 6664): enable(): BT is already enabled..!,
,D/WifiService(  932): New client listening to asynchronous messages,
E/WifiTrafficPoller(  932): ADD_CLIENT: 8
D/WifiManager( 6664): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  932): MONITOR_LOG
D/WifiService(  932): setWifiEnabled: true pid=6664, uid=10366
W/Settings:Agent(  932): name: wifi_on
E/WifiService(  932): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  932): value: 2
,I/WifiService(  932): isSprintWifiRestricted(): false
W/Settings:Agent(  932): >> traceCallingStack()
I/WifiService(  932): isMdmWifiRestricted(): false
W/Settings:Agent(  932): Process.myPid(): 932
W/Settings:Agent(  932): Process.myTid(): 2042
W/Settings:Agent(  932): Process.myUid(): 1000
W/Settings:Agent(  932): 
,W/Settings:Agent(  932): 
W/System.err(  932): java.lang.Throwable: stack dump
,W/System.err(  932): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  932): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  932): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  932): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  932): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  932): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  932): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
,W/System.err(  932): ,	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  932): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  932): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  932): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  932): 
W/Settings:Agent(  932): << traceCallingStack(): 13(ms)
D/WifiController(  932): handleMessage: E msg.what=155656
D/WifiController(  932): processMsg: DeviceActiveState
D/WifiController(  932): processMsg: StaEnabledState
D/WifiController(  932): handleMessage: X
D/WifiManager( 6664): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  932): handleMessage: E msg.what=131145
D/WifiManager( 6664): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  932): processMsg: ConnectedState
E/WifiStateMachine(  932):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  932): processMsg: L2ConnectedState
,E/WifiStateMachine(  932):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
D/wpa_supplicant( 1356): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1356): TDLS: Tear down peers
D/wpa_supplicant( 1356): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6664): Radios toggled
I/jxcore-log( 6664): 
I/jxcore-log( 6664): My device name is: HTC-HTC One M8s
I/jxcore-log( 6664): 
,D/wpa_supplicant( 1356): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1356): wlan0: Deauthentication notification
D/wpa_supplicant( 1356): wlan0:  * reason 3 (locally generated)
,D/wpa_supplicant( 1356): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1356): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1356): enter disconnect check
,I/wpa_supplicant( 1356): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/PMS     (  932): acquireWL(2f145f4): PARTIAL_WAKE_LOCK  NetworkStats 0x1 932 1000 null
D/WifiMonitor(  932): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
,D/UsbDeviceManager(  932): [USBNET] bCheckSuppFunc: cdc_network
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiDisplayAdapter(  932): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  932):     Client/Owner: Client
D/WifiDisplayAdapter(  932):     GroupId: 
D/WifiDisplayAdapter(  932):     Passphrase: 
D/WifiDisplayAdapter(  932):     SessionId: 0
D/WifiDisplayAdapter(  932):     IP Address: }
E/WifiMonitor(  932): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  932): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  932): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1356): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1356): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  932): interfaceLinkStateChanged wlan0, false
D/Tethering(  932): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  932): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  932): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  932): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  932): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  932): BroadcastReceiver::onReceive+
D/UsbnetService(  932): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  932): BroadcastReceiver::onReceive-
D/Tethering(  932): interfaceLinkStateChanged wlan0, false
D/Tethering(  932): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
D/TetherSettings( 5869): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5869): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5869): Cust_ConnectToPC   : Modem_Link>false
D/wpa_supplicant( 1356): TDLS: Remove peers on disassociation
D/        ( 5869): Cust_ConnectToPC   : spcsc>false
D/        ( 5869): Cust_ConnectToPC   : IPT>true
D/wpa_supplicant( 1356): wlan0: Disconnect event - remove keys
D/        ( 5869): Cust_ConnectToPC   : Singel_USB>false
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
W/Settings( 5869): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/SmartNS_Utility( 5869): hasRemovableStorageSlot: true
D/WifiP2pService(  932): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/SmartNS_Utility( 5869): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/WifiP2pService(  932): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5593b41f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1356):    addr=c0:ff:d4:d3:aa:48
D/SmartNS_NSReceiver( 5869): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/wpa_supplicant( 1356): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplic,ant( 1356): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1356): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1356): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1356): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1356): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1356): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1356): wlan0: State: DISCONNECTED -> DISCONNECTED
D/WifiMonitor(  932): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1356): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=0
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  932): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/PMS     (  932): acquireWL(12c3511d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1356): Wireless event: cmd=0x8b15 len=24
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1356): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1356): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  932): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  932): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  932): handleMessage: new destination call exit/enter
E/WifiStateMachine(  932): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  932): invokeExitMethods: ConnectedState
E/WifiStateMachine(  932): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  932): release()
E/WifiStateMachine(  932): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  932): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  932): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  932): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
D/ConnectivityService(  932): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  932): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  932): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  932): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/WifiHW  (  932): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  932): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/ConnectivityService(  932): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED connected
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  932): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1356): Power_Mode_Type mode = 0
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1356): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  932): setDhcpActive: false
V/NativeCrypto( 1919): Read error: ssl=0x558241a8a0: I/O error during system call, Connection timed out
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  932): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  932): setDetailed state send new extra info<unknown ssid>
V/NativeCrypto( 1919): SSL shutdown failed: ssl=0x558241a8a0: I/O error during system call, Broken pipe
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  932): NetworkAgent != null
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  932): NETWORK_STATE_CHANGED_ACTION: mIsWifiCon,nected=false
D/WifiDataStallTracker(  932): stopDataStallAlarm 
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  932): ENABLE_DATA_MONITOR_POLL false Token 3
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  932): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  932): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): Forcing reevaluation
W/WifiHW  (  932): QCOM Debug skip set_network part for security concern!
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): Validated
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/PMS     (  932): releaseWL(12c3511d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  932): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  932): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  932): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  932):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  932): Start Disconnecting Watchdog 1
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=131146
E/WifiStateMachine(  932): processMsg: DisconnectingState
E/WifiStateMachine(  932):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
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
D/PMS     (  932): releaseWL(2f145f4): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1356): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1356): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1356): wlan0: Add radio work 'scan'@0x5593b24860
D/wpa_supplica,nt( 1356): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1356): wlan0: Starting radio work 'scan'@0x5593b24860 after 0.000034 second wait
D/wpa_supplicant( 1356): wlan0: nl80211: scan request
D/wpa_supplicant( 1356): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1356): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1356): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1356): wlan0: Own scan request started a scan in 0.000072 seconds
I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  932): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  932): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  932): handleMessage: X
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange(): SSID
E/WifiStateMachine(  932): handleMessage: E msg.what=147460
E/WifiStateMachine(  932): processMsg: DisconnectingState
D/WifiMonitor(  932): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  932): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  932): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  932): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  932):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=131254
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=131254
E/WifiStateMachine(  932): ConnectModeState: Network connection lost 
E/WifiStateMachine(  932): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  932): handleMessage: new destination call exit/enter
E/WifiStateMachine(  932): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  932): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  932): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  932): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  932): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  932): DisconnectedState call setCountryCode()
E/WifiStateMachine(  932):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1356): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ContextImpl( 5869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
V/NetworkPolicy(  932): updateNetworkEnabledLocked()
V/NetworkPolicy(  932): updateNotificationsLocked()
I/SmartNS_Utility( 5869): setISNotification
D/SmartNS_Utility( 5869): usb_cable_connect = 1
D/SmartNS_Utility( 5869): usb_denied = 0
,I/SmartNS_PSService( 5869): usb notificaiton:true
,E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 5869): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/wpa_supplicant( 1356): wlan0: nl80211: sched_scan request
,D/ConnectivityService(  932): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/SmartNS_Utility( 5869): usb_cable_connect = 1
,D/SmartNS_Utility( 5869): usb_denied = 0
I/SmartNS_PSService( 5869): usb notificaiton:true
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
,D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1216): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 5869): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1216): reapply : com.android.settings 1 36
,D/wpa_supplicant( 1356): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1356): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Sched scan started
E/WifiStateMachine(  932): handleMessage: X
D/wpa_supplicant( 1356): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1356): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1356): wlan0: Event SCAN_RESULTS (3) received
,I/wpa_supplicant( 1356): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1356): wlan0: Scan completed in 0.046300 seconds
D/wpa_supplicant( 1356): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1356): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1356): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1356): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1356): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1356): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1356): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1356): wlan0: Radio work 'scan'@0x5593b24860 done in 0.047272 seconds
D/wpa_supplicant( 1356): wlan0: Selecting BSS from priority group 463
D/wpa_supplicant( 1356): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 1356): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1356): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1356): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1356):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1356): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1356): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x5593b43c00  current_ssid=0x0
D/wpa_supplicant( 1356): wlan0: Request association with c0:ff:d4:d3:aa:48
E/WifiMonitor(  932): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/wpa_supplicant( 1356): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/WifiMonitor(  932): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 1356): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1356): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=45 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1356): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1356): wlan0: Add radio work 'connect'@0x5593b24860
W/WifiMonitor(  932): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1356): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1356): wlan0: Starting radio work 'connect'@0x5593b24860 after 0.000068 second wait
I/wpa_supplicant( 1356): check if in concurrent case
I/wpa_supplicant( 1356): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  932): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=46 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  932): handleMessage: E msg.what=131101
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  932): processMsg: DriverStartedState
E/WifiStateMachine(  932):  DriverStart,edState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
I/QuickSettingWifi( 1216): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
E/WifiStateMachine(  932):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  932): processMsg: DefaultState
D/wpa_supplicant( 1356): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
E/WifiStateMachine(  932):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  932): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  932): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=147462
E/WifiStateMachine(  932): processMsg: DisconnectedState
D/wpa_supplicant( 1356): wlan0: Cancelling sched scan
E/WifiStateMachine(  932):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=131304  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/wpa_supplicant( 1356): nl80211: Sched scan stop sent (ret=0)
E/WifiStateMachine(  932): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
E/WifiStateMachine(  932): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/wpa_supplicant( 1356): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1356): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1356): wpas_start_assoc_cb, 1910
E/WifiStateMachine(  932): processMsg: ConnectModeState
D/wpa_supplicant( 1356): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1356): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1356): RSN: PMKSA cache search - network_ctx=0x5593b43c00 try_opportunistic=0
D/wpa_supplicant( 1356): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1356): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1356): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1356): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1356): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1356): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1356): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1356): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1356): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1356): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  932):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=131304  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/wpa_supplicant( 1356): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1356): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1356): nl80211: Unsubscribe mgmt frames handle 0x888888dd1b3cb989 (mode change)
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=131212
E/WifiStateMachine(  932): processMsg: DisconnectedState
D/wpa_supplicant( 1356): nl80211: Subscribe to mgmt frames with non-AP handle 0x5593b43100
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=0104
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=040a
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=040b
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=040c
E/WifiStateMachine(  932):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=040d
E/WifiStateMachine(  932): processMsg: ConnectModeState
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=090a
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=090b
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=090c
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=090d
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=0409506f9a09
E/WifiStateMachine(  932):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=7f506f9a09
E/WifiStateMachine(  932): processMsg: DriverStartedState
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=0801
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=040e
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=06
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=0a07
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=0a11
E/WifiStateMachine(  932):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
D/wpa_supplicant( 1356): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5593b43100 match=0a1a
D/wpa_supplicant( 1356): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1356):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356):   * freq=2412
D/wpa_supplicant( 1356):   * freq_hint=2412
D/wpa_supplicant( 1356):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1356):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1356):   * WPA Versions 0x2
D/wpa_supplicant( 1356):   * pairwise=0xfac04
D/wpa_supplicant( 1356):   * group=0xfac04
D/wpa_supplicant( 1356):   * akm=0xfac02
D/wpa_supplicant( 1356):   * Auth Type 0
D/wpa_supplicant( 1356): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5593b43c3a
E/WifiStateMachine(  932):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: DefaultState
E/WifiStateMachine(  932):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  932): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=131212
E/WifiStateMachine(  932): processMsg: DisconnectedState
D/wpa_supplicant( 1356): nl80211: Connect request send successfully
D/wpa_supplicant( 1356): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1356): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1356): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1356): EAPOL: External notification - portControl=Auto
E/WifiStateMachine(  932):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: ConnectModeState
D/wpa_supplicant( 1356): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1356): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1356): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  932):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: DriverStartedState
D/WifiMonitor(  932): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  932): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  932):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  932): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  932):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: DefaultState
E/WifiStateMachine(  932):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  932): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
W/ContextImpl(  932): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  932): handleMessage: X
D/WifiNetworkAgent(  932): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  932): handleMessage: E msg.what=147462
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=131308  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  932): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  932): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  932): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  932): NetworkAgent == null
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=131312  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=147461
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 dur:6380 bcn=0
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 dur:6380 bcn=0
E/WifiStateMachine(  932): processMsg: DriverStartedState
E/WifiStateMachine(  932):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 dur:6380 bcn=0
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  932):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 dur:6380 bcn=0
D/WifiStateMachine(  932): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1356): wlan0: Control interface command 'LIST_DONGLES'
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  932): [1,452,294,353,538 ms] noteScanEnd no scan source
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1356): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  932): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1897617f sup_state=SCANNING debouncing=false
D/WISPrService( 5869): >>>>>WISPrService start isConnected = true<<<<<
E/WifiAutoJoinController (  932): NG7005g c0:ff:d4:d3:aa:4a rssi=-48 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  932): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  932): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  932): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  932):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
E/WifiAutoJoinController (  932): 01ABC c2:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  932): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  932): UPC243894600 a0:c5:62:7a:49:96 rssi=-90 cap [WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  932): UPC5999698 64:7c:34:12:7f:81 rssi=-91 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  932): Gonzos 38:f8:89:11:e9:11 rssi=-91 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  932): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-92 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  932): ageScanResultsOut delay 40000 size 8 now 1452294353541
E/WifiAutoJoinController (  932): newSupplicantResults size=8 known=1 true
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1356): wlan0: Control interface command 'STATUS-NO_EVENTS'
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiAutoJoinController (  932): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  932): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  932): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  932): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiAutoJoinController (  932): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiConfigStore(  932):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=131213
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState CMD_TARGET_BSSID 46 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=131321
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState CMD_TARGET_BSSID 46 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=131321
E/WifiStateMachine(  932): processMsg: DriverStartedState
E/WifiStateMachine(  932):  DriverStartedState CMD_TARGET_BSSID 46 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=131322
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
E/WifiStateMachine(  932):  SupplicantStartedState CMD_TARGET_BSSID 46 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=131322
D/WifiService(  932): New client listening to asynchronous messages
E/WifiTrafficPoller(  932): ADD_CLIENT: 9
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=147462
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=131328  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  932): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  932): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  932): setDetailed state send new extra info0x
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  932): NetworkAgent == null
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=131333  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  932): handleMessage: X
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  932): handleMessage: E msg.what=131131
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  932): handleMessage: X
W/WISPrService( 5869): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5869): trigger connection
,D/WISPrService( 5869): continue
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5869): start DataConnection
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5869): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5869): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5869): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5869): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5869): [NET] android_getaddrinfo_proxy+
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5869): [NET] android_getaddrinfo_proxy get netid:0
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/ConnectivityService(  932): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524292
D/ConnectivityService(  932):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  932):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  932): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): Disconnected - quitting
D/Nat464Xlat(  932): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/usbnet  (  932): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  932): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SecurityController( 1216): onLost 100
D/ConnectivityService(  932): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  932):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  932): Removing idletimer
D/usbnet  (  932): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI    (  932): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  932):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  932): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
E/WifiStateMachine(  932): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/libc    ( 5869): [NET] android_getaddrinfo_proxy-, NODATA
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/PMS     (  932): acquireWL(131dcd63): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 932 1000 null
,D/Tethering(  932): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/CSLegacyTypeTracker(  932): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/Tethering(  932): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  932): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  932): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  932): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy(  932): ensureActiveMobilePolicyLocked()
D/PMS     (  932): acquireWL(35d6cd60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 932 1000 null
E/ConnectivityService(  932): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/PMS     (  932): releaseWL(35d6cd60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,D/DATA_ICON( 1216): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
,D/NetworkPolicy(  932): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  932): updateNetworkEnabledLocked()
V/NetworkPolicy(  932): updateIfacesLocked()
V/NetworkPolicy(  932): updateNotificationsLocked()
,I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
V/NetworkPolicy(  932): updateNetworkEnabledLocked()
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
V/NetworkPolicy(  932): updateNotificationsLocked()
D/DATA_ICON( 1216): dataConnected: false/false
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/libc    ( 5869): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/NetworkManagementService(  932): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/libc    ( 5869): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  932): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6728 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/FlexNetS( 6531): updateSvcAllowedInSettings:false
,D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WISPrService( 5869): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false,
,D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/wpa_supplicant( 1356): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1356): WEXT: Custom wireless event: 'BEACONIEs=',
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1356): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1356): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1356): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/UsbDeviceManager(  932): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1356): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1356): nl80211: Connect event
D/PMS     (  932): acquireWL(155585db): PARTIAL_WAKE_LOCK  NetworkStats 0x1 932 1000 null
D/wpa_supplicant( 1356): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1356): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1356): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1356): wlan0: Association info event
D/wpa_supplicant( 1356): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): wlan0: freq=2412 MHz
D/FlexNetS( 6531): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1356): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1356): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1356): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1356): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1356): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1356): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1356): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1356): TDLS: Remove peers on association
D/wpa_supplicant( 1356): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1356): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1356): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1356): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1356): EAPOL: enable timer tick
D/wpa_supplicant( 1356): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1356): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1356): wlan0: Cancelling scan request
I/wpa_supplicant( 1356): htc_wext_set_keepalive +
I/wpa_supplicant( 1356): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1356): getPrivFuncNum +	
I/wpa_supplicant( 1356): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1356): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1356): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1356): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/WifiMonitor(  932): Event [IFNAM,E=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1356): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1356): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1356): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1356): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  932): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1356): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1356):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1356):   key_nonce - hexdump(len=32): 20 c4 85 ca c6 a0 8e 86 d6 98 4f 2b 6a 57 a9 e2 1e da 19 e0 cc 2f 8d 5e 3e 7b ac a4 3c c4 64 91
D/wpa_supplicant( 1356):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1356): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1356): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1356): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  932): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  932): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=49 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  932): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  932): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  932): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  932): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  932): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  932): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  932): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  932): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  932): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  932): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  932): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  932): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/wpa_supplicant( 1356): WPA: Renewed SNonce - hexdump(len=32): c8 f6 b0 cf 88 03 44 74 d8 4c 2a ec be 9f f8 ec 57 65 c5 30 53 63 35 5d d5 cf a8 b1 85 b8 a2 9a
D/wpa_supplicant( 1356): WPA: Nonce1 - hexdump(len=32): c8 f6 b0 cf 88 03 44 74 d8 4c 2a ec be 9f f8 ec 57 65 c5 30 53 63 35 5d d5 cf a8 b1 85 b8 a2 9a
D/wpa_supplicant( 1356): WPA: Nonce2 - hexdump(len=32): 20 c4 85 ca c6 a0 8e 86 d6 98 4f 2b 6a 57 a9 e2 1e da 19 e0 cc 2f 8d 5e 3e 7b ac a4 3c c4 64 91
D/wpa_supplicant( 1356): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1356,): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1356): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1356): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1356): WPA: KCK - hexdump(len=16): [REMOVED]
E/WifiStateMachine(  932): handleMessage: E msg.what=147462
D/wpa_supplicant( 1356): WPA: Derived Key MIC - hexdump(len=16): fe 4b a9 99 de bf 96 1d cb fe af 8b 29 fe 60 bc
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=131431  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  932): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  932): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  932): processMsg: ConnectModeState
D/Tethering(  932): interfaceLinkStateChanged wlan0, false
D/Tethering(  932): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  932):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=131432  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  932): interfaceLinkStateChanged wlan0, false
D/Tethering(  932): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=147500
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState what:147500 0 0
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  932): Enter handleAssociatedWithEvent
D/WifiStateMachine(  932): Associated
D/Tethering(  932): interfaceLinkStateChanged wlan0, false
D/Tethering(  932): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiStateMachine(  932): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  932): Exit handleAssociatedWithEvent
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=147462
E/WifiStateMachine(  932): processMsg: DisconnectedState
D/Tethering(  932): interfaceLinkStateChanged wlan0, true
D/Tethering(  932): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  932):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=131434  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  932): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  932): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  932): setDetailed state send new extra info"NG700"
V/Tethering(  932): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1356): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1356): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1356): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1356): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1356):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1356):   key_nonce - hexdump(len=32): 20 c4 85 ca c6 a0 8e 86 d6 98 4f 2b 6a 57 a9 e2 1e da 19 e0 cc 2f 8d 5e 3e 7b ac a4 3c c4 64 91
D/wpa_supplicant( 1356):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_rsc - hexdump(len=8): 62 84 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356):   key_mic - hexdump(len=16): 70 79 bc 6f 2e 5d e9 5d fd b9 36 ab 07 8d 64 ae
D/wpa_supplicant( 1356): RSN: encrypted key data - hexdump(len=56): 2c 35 d0 e7 91 a1 8d a2 98 30 c2 ad 57 37 25 bf 99 81 5f 14 b8 e9 fb 65 04 07 c6 2b ce 84 0a fe ...
D/wpa_supplicant( 1356): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1356): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1356): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1356): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 22 85 ...
D/wpa_supplicant( 1356): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1356): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1356): wlan0: WPA: Sending EAPOL-Key 4/4
E/WifiStateMachine(  932): NetworkAgent == null
D/wpa_supplicant( 1356): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1356): WPA: Derived Key MIC - hexdump(len=16): 81 e9 d4 c5 21 3d 7c 40 65 b1 98 71 0f 50 96 5b
D/wpa_supplicant( 1356): wlan0: WPA: Installing PTK to the driver
D/Tethering(  932): sendTetherStateChangedBroadcast 1, 0, 0
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5593b44390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1356): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1356): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1356):    addr=c0:ff:d4:d3:aa:48
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/UsbnetService(  932): BroadcastReceiver::onReceive+
D/UsbnetService(  932): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  932): releaseWL(155585db): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/UsbnetService(  932): BroadcastReceiver::onReceive-
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1356): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1356): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1356): WPA: Group Key - hexdump(len=16): [REMOVED]
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1356): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1356): WPA: RSC - hexdump(len=6): 62 84 00 00 00 00
E/WifiStateMachine(  932): processMsg: ConnectModeState
D/wpa_supplicant( 1356): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5574cdde68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1356): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1356): nl80211: KEY_SEQ - hexdump(len=6): 62 84 00 00 00 00
D/wpa_supplicant( 1356):    broadcast key
D/WifiMonitor(  932): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  932):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=131439  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  932): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1356): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine(  932): handleMessage: X
D/wpa_supplicant( 1356): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1356): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1356): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1356): wlan0: Radio work 'connect'@0x5593b24860 done in 0.138712 seconds
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1356): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1356): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1356): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1356): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1356): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 1356): set send_ind_to_ndc = 0
I/wpa_supplicant( 1356): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1356): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1356): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1356): EAPOL: External notification - EAP success=1
V/NetworkPolicy(  932): updateNetworkEnabledLocked()
D/wpa_supplicant( 1356): EAPOL: SUPP_PAE entering state AUTHENTICATING
V/NetworkPolicy(  932): updateNotificationsLocked()
D/wpa_supplicant( 1356): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1356): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1356): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1356): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1356): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1356): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1356): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1356): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WifiMonitor(  932): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1356): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  932): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=52 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  932): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  932): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=53 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  932): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  932): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor(  932): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=55 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  932): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  932): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  932): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  932): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  932): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/FlexNetS( 6531): updateSvcAllowedInSettings:false
D/Tethering(  932): interfaceLinkStateChanged wlan0, true
D/Tethering(  932): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  932): handleMessage: E msg.what=131101
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  932): processMsg: ConnectModeState
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  932):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  932): processMsg: DriverStartedState
E/WifiStateMachine(  932):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
E/WifiStateMachine(  932):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  932): processMsg: DefaultState
E/WifiStateMachine(  932):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  932): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  932): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  932): handleMessage: X
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 21
E/WifiStateMachine(  932): handleMessage: E msg.what=147462
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=131452  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  932): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  932): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=131453  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=147459
E/WifiStateMachine(  932): processMsg: DisconnectedState
E/WifiStateMachine(  932):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=131454
E/WifiStateMachine(  932): processMsg: ConnectModeState
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
E/WifiStateMachine(  932):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=131455
E/WifiStateMachine(  932): Network connection established
D/WifiStateMachine(  932): fetchFrequency(), freq = 2412
E/WifiStateMachine(  932): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  932): NetworkAgent == null
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 22
D/FlexNetS( 6531): updateSvcAllowedInSettings:false
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  932): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  932): handleMessage: new destination call exit/enter
E/WifiStateMachine(  932): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  932): invokeExitMethods: DisconnectedState
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1356): CTRL_IFACE SET 'pno'='0'
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 23
E/WifiStateMachine(  932): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  932): moveTempStackToStateStack: i=1,j=4
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  932): moveTempStackToStateStack: i=0,j=5
D/WifiDisplayAdapter(  932): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  932):     Client/Owner: Client
D/WifiDisplayAdapter(  932):     GroupId: 
D/WifiDisplayAdapter(  932):     Passphrase: 
D/WifiDisplayAdapter(  932):     SessionId: 0
D/WifiDisplayAdapter(  932):     IP Address: }
E/WifiStateMachine(  932): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  932): invokeEnterMethods: L2ConnectedState
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  932): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  932): NetworkAgent == null
E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 24
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  932): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  932): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  932): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  932): Got NetworkAgent Messenger
E/WifiConfigStore(  932): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  932): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
W/WifiHW  (  932): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  932): NetworkAgent connected
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  932): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  932): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  932): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  932): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  932): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  932): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1356): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1356): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1356): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1356): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1356): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1356): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1356): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  932): Start Dhcp Watchdog 2
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=147462
E/WifiStateMachine(  932): processMsg: ObtainingIpState
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  932):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=131477  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  932): processMsg: L2ConnectedState
E/WifiStateMachine(  932):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=131478  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=131479  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=131212
E/WifiStateMachine(  932): processMsg: ObtainingIpState
E/WifiStateMachine(  932):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: L2ConnectedState
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  932):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: ConnectModeState
,E/WifiStateMachine(  932):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: DriverStartedState
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
E/WifiStateMachine(  932):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
E/WifiStateMachine(  932):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: DefaultState
E/WifiStateMachine(  932):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  932): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  932): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  932): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=196612
E/WifiStateMachine(  932): processMsg: ObtainingIpState
E/WifiStateMachine(  932):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  932): processMsg: L2ConnectedState
D/WISPrService( 5869): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  932):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiStateMachine(  932): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  932): acquireWL(27abc3bc): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 932 1000 null
D/WifiStateMachine(  932): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  932): setDhcpActive: true
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WISPrService( 5869): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  932): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  932): do suspend false
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/wpa_supplicant( 1356): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1356): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1356): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1356): wlan0: Event DRIVER_GTK_REKEY (37) received
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1356): INFO - Deny active power mode because already has gateway
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  932): Unexpected BatchedScanResults :null
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/FlexNetS( 6531): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  932): noteBatchedScanstop()
E/WifiStateMachine(  932): handleMessage: X
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiP2pService(  932): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@33196b00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  932): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@33196b00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/TetherSettings( 5869): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5869): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5869): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5869): Cust_ConnectToPC   : spcsc>false
D/        ( 5869): Cust_ConnectToPC   : IPT>true
D/        ( 5869): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5869): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5869): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5869): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5869): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5869): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/SmartNS_Utility( 5869): setISNotification
D/SmartNS_Utility( 5869): usb_cable_connect = 1
D/SmartNS_Utility( 5869): usb_denied = 0
I/SmartNS_PSService( 5869): usb notificaiton:true
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
D/SmartNS_Utility( 5869): usb_cable_connect = 1
D/SmartNS_Utility( 5869): usb_denied = 0
I/SmartNS_PSService( 5869): usb notificaiton:true
E/WifiStateMachine(  932): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  932): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 5869): Tethered state change:false isNSOpening:false
I/RemoteViews( 1216): reapply : com.android.settings 1 36
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false
,I/RemoteViews( 1216): reapply : com.android.settings 1 36
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6728): [57a.2.]  listen tmrbb8,
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false
,D/FlexNetS( 6531): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6595): remove item 101 (p2d27in239) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6728): [57a.2.] summary 118:p2 ignore
,I/ActivityManager(  932): Killing 6182:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  932): killProcessQuiet, pid=6182
E/dhcpcd  ( 6760): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/dhcpcd  ( 6760): version 5.5.6 starting
,E/dhcpcd  ( 6760): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6760): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6760): autoip env[11]:autoip=DISABLE
,I/ActivityManager(  932): Recipient 6182
,I/dhcpcd  ( 6760): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6760): wlan0: sending REQUEST (xid 0x583b4fcc), next in 0.97 seconds
,D/wpa_supplicant( 1356): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1356): EAPOL: disable timer tick
,I/dhcpcd  ( 6760): wlan0: sending REQUEST (xid 0x583b4fcc), next in 2.63 seconds,
,I/dhcpcd  ( 6760): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6760): wlan0: leased 192.168.1.130 for 86400 seconds,
D/ConnectivityService(  932): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/dhcpcd  ( 6760): autoip env[11]:autoip=DISABLE
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  932): handleMessage: E msg.what=131212
E/WifiStateMachine(  932): processMsg: ObtainingIpState
E/WifiStateMachine(  932):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: L2ConnectedState,
E/WifiStateMachine(  932):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: DriverStartedState
E/WifiStateMachine(  932):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
E/WifiStateMachine(  932):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  932): processMsg: DefaultState
E/WifiStateMachine(  932):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  932): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  932): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  932): handleMessage: X
,D/libc    (  932): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  932): handleMessage: E msg.what=131212
E/WifiStateMachine(  932): processMsg: ObtainingIpState
E/WifiStateMachine(  932):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  932): processMsg: L2ConnectedState
E/WifiStateMachine(  932):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  932): processMsg: ConnectModeState
,E/WifiStateMachine(  932):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  932): processMsg: DriverStartedState
E/WifiStateMachine(  932):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
,I/dhcpcd  ( 6760): bind_interface: daemonise
E/WifiStateMachine(  932):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine(  932): processMsg: DefaultState
E/WifiStateMachine(  932):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine(  932): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  932): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  932): handleMessage: X
D/ConnectivityService(  932): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/libc    (  932): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  932): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  932): handleMessage: E msg.what=196613
E/WifiStateMachine(  932): processMsg: ObtainingIpState
E/WifiStateMachine(  932):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  932): processMsg: L2ConnectedState
E/WifiStateMachine(  932):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  932): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiP2pService(  932): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER POWERMODE 0'
D/WifiP2pService(  932): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1356): Power_Mode_Type mode = 0
D/PMS     (  932): releaseWL(27abc3bc): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1356): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1356): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  932): setDhcpActive: false
E/WifiStateMachine(  932): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  932): WifiStateMachine DHCP successful
E/WifiStateMachine(  932): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
,E/WifiStateMachine(  932): link address 192.168.1.130/24
D/ConnectivityService(  932): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  932): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  932): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  932): gateway: /192.168.1.1
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1356): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1356): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1356): htc_wext_set_keepalive +
I/wpa_supplicant( 1356): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1356): getPrivFuncNum +	
I/wpa_supplicant( 1356): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1356): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1356): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1356): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1356): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  932): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  932): handleMessage: X
E/WifiStateMachine(  932): handleMessage: E msg.what=131210
E/WifiStateMachine(  932): processMsg: ObtainingIpState
E/WifiStateMachine(  932):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  932): processMsg: L2ConnectedState
,E/WifiStateMachine(  932):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1356): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1356): environment dirty rate=22 [9][2][0]
E/WifiStateMachine(  932): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  932): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
,E/WifiConfigStore(  932): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
W/WifiHW  (  932): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1356): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1356): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  932): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  932): WifiMonitor:wlan0 cnt=57 dispatchEvent: BLACKLIST CLEAR 
,D/WifiWatchdogStateMachine(  932): RSSI current: 3 new: -59, 3
E/WifiStateMachine(  932): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/WIFI_ICON( 1216): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  932): NetworkAgent != null
,E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  932): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  932): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  932): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/ConnectivityService(  932): Adding iface wlan0 to network 101
,E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/HtcWifiWanDetect(  932): WAN detection
E/WifiDataStallTracker(  932): ENABLE_DATA_MONITOR_POLL true Token 4
D/HtcWifiWanDetect(  932): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiDataStallTracker(  932): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
V/NetworkPolicy(  932): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  932): transitionTo: destState=ConnectedState
V/NetworkPolicy(  932): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  932): handleMessage: new destination call exit/enter
E/WifiStateMachine(  932): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  932): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  932): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  932): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  932): invokeEnterMethods: ConnectedState
,E/WifiTrafficPoller(  932): ENABLE_TRAFFIC_STATS_POLL false Token 26
,D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED connected
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  932): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  932): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/WifiStateMachine(  932): handleMessage: X
D/WISPrService( 5869): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  932): handleMessage: E msg.what=131131
E/WifiStateMachine(  932): processMsg: ConnectedState
,E/WifiStateMachine(  932):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  932): processMsg: L2ConnectedState
E/WifiStateMachine(  932):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/ConnectivityService(  932): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  932): handleMessage: X
D/ConnectivityService(  932): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  932): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/WISPrService( 5869): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  932): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  932): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/Nat464Xlat(  932): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  932): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  932): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  932): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  932):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  932):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  932): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  932):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  932):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  932): currentScore = 0, newScore = 20
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  932):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): Connected
D/ConnectivityService(  932): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/usbnet  (  932): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): Validated
D/WIFI    (  932): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  932):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  932): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/CSLegacyTypeTracker(  932): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  932): sendGeneralBroadcast, restrictEnable=false
,D/Tethering(  932): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  932): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  932): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  932): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  932): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  932): acquireWL(3de11ac1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 932 1000 null
V/NetworkPolicy(  932): ensureActiveMobilePolicyLocked()
D/ConnectivityService(  932): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  932): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  932):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  932): Validated
D/ConnectivityService(  932):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  932): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  932): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  932): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkPolicy(  932): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/ConnectivityService(  932):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  932): updateNetworkEnabledLocked()
D/ConnectivityService(  932):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  932): updateIfacesLocked()
D/ConnectivityService(  932): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  932): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  932):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  932):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  932): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  932): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  932):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  932): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  932): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  932): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  932): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ C,apabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  932): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  932):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  932): updateNotificationsLocked()
D/WIFI    (  932): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  932): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524290
D/ConnectivityService(  932): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  932):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  932):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1216): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  932): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  932): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  932):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  932):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  932): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkManagementService(  932): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/SecurityController( 1216): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524290
,D/DATA_ICON( 1216): dataConnected: false/false
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/SecurityController( 1216): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524290
D/DATA_ICON( 1216): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,I/SecurityController( 1216): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1216): dataConnected: false/false
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  932): releaseWL(3de11ac1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  932): updateNetworkEnabledLocked()
V/NetworkPolicy(  932): updateNotificationsLocked()
,I/QuickSettingWifi( 1216): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/QuickSettingWifi( 1216): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/PMS     (  932): releaseWL(131dcd63): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
,D/ConnectivityService(  932): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network,
,D/ConnectivityService(  932): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  932): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  932): acquireWL(21456266): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 932 1000 null
D/GpsLocationProvider(  932): [handleMessage] UPDATE_NETWORK_STATE
I/AlarmManager(  932): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  932): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  932): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/ConnectivityHelper( 1543): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  932): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6792 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  932): No APN found to select.,
,D/PMS     (  932): releaseWL(21456266): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  932): acquireWL(70ece54): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 932 1000 null
,D/PMS     (  932): releaseWL(70ece54): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/art     (  412): Explicit concurrent mark sweep GC freed 8640(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 424us total 31.992ms
,I/art     (  412): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 189us total 19.433ms
,D/MdScPhnSt( 6728): [f18.1.]  listen tmrbb8
,I/art     (  412): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 160us total 21.305ms
,D/MdScDataSum( 6728): [f18.1.] summary 118:p1 ignore
,I/MusicStore( 6792): Database version: 120
,D/VoldConnector(  932): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6792): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  932): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6792): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  932): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6792): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6792): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6792): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6792): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6792): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6792): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e37cf9a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6792): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6792): GMSCore installation verified
,I/ConfigStore( 6792): Config Database version: 1
,I/PackageManager(  932):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6792, uid=10159, userID:0,
,D/WifiDisplayAdapter(  932): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  932):     Client/Owner: Client
D/WifiDisplayAdapter(  932):     GroupId: 
D/WifiDisplayAdapter(  932):     Passphrase: 
D/WifiDisplayAdapter(  932):     SessionId: 0
D/WifiDisplayAdapter(  932):     IP Address: }
,D/MediaRouterService(  932): Client com.google.android.music (pid 6792): Registered,
,D/WifiDisplayAdapter(  932): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  932):     Client/Owner: Client
D/WifiDisplayAdapter(  932):     GroupId: 
D/WifiDisplayAdapter(  932):     Passphrase: 
D/WifiDisplayAdapter(  932):     SessionId: 0
D/WifiDisplayAdapter(  932):     IP Address: }
,I/MediaRouter( 6792): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6792): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6792): type=WIFI subType= reason=null isConnected=true
,D/AutoSetting( 1589): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/PackageManager(  932):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6792, uid=10159, userID:0,
D/MobileConnectivityChangeReceiver( 6386): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6386): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1589): service - onCreate(),
,I/GHttpClientFactory( 6792): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6792): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1589): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate,
,D/AutoSetting( 1589): service - onStartCommand() screen is off, don't request location
D/LocationManagerService(  932): request 20a01a9c passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  932): provider request: passive ProviderRequest[ON interval=0]
,D/ChimeraCfgMgr( 4389): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4389): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  932): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6836 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6414): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 6414): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6414): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6414): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6414): [NET] android_getaddrinfo_proxy+,
D/libc    ( 6414): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/GLSUser ( 1919): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1919): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1919): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1919): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6414): [NET] android_getaddrinfo_proxy-, success
,I/Babel   ( 6414): connection state changed from UNKNOWN to CONNECTED,
,I/art     (  932): Explicit concurrent mark sweep GC freed 58509(3MB) AllocSpace objects, 4(584KB) LOS objects, 33% free, 16MB/25MB, paused 2.012ms total 145.481ms
,W/Kids    ( 4389): [AccountUtils] Account not ready
W/Kids    ( 4389): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,W/Kids    ( 4389): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4389): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4389): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4389): 	at com.google.android.gms.auth.p.b(SourceFile:477)
,W/Kids    ( 4389): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4389): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4389): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4389): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4389): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4389): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4389): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1216): reapply : com.google.android.gms 2 40
,D/VoldConnector(  932): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  932): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6836): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6836):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6836):   adb logcat -s GAv4
,D/VoldConnector(  932): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  932): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6836): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6836): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6836): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6836): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/global  ( 6836): [apache-http] Connection GC has been deprecated!
,W/global  ( 6836): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 6836): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6836): Time to load native libraries: 3 ms (timestamps 5427-5430),
I/LibraryLoader( 6836): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6836): Binding Chromium to main looper Looper (main, tid 1) {16d030eb},
,I/LibraryLoader( 6836): Expected native library version number "",actual native library version number ""
,I/chromium( 6836): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6836): Initializing chromium process, singleProcess=true
W/art     ( 6836): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6836): ApplicationContext is null in ApplicationStatus
,W/chromium( 6836): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6836): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6836): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6836): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6836): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6836): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6836): Local Branch: 
I/Adreno-EGL( 6836): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6836): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6836):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6836): Requires BLUETOOTH permission,
,I/NSApplication( 6836): Starting up...
,I/ActivityManager(  932): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6897 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  932): killProcessQuiet, pid=6342
I/ActivityManager(  932): Killing 6342:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  932): Recipient 6342
,D/Process (  932): killProcessQuiet, pid=5893,
I/ActivityManager(  932): Killing 5893:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  932): Recipient 5893
,D/Process (  932): killProcessQuiet, pid=5605,
,I/ActivityManager(  932): Killing 5605:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  932): Recipient 5605
,E/WifiStateMachine(  932): handleMessage: E msg.what=131168,
E/WifiStateMachine(  932): processMsg: ConnectedState
E/WifiStateMachine(  932):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  932): processMsg: L2ConnectedState
E/WifiStateMachine(  932):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  932): processMsg: DriverStartedState,
E/WifiStateMachine(  932):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
E/WifiStateMachine(  932):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  932): processMsg: DefaultState
E/WifiStateMachine(  932):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  932): handleMessage: X
,D/libc    (  932): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
,D/libc    (  932): [NET] android_getaddrinfofornet-, err=8
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  932): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  932): [NET] android_getaddrinfo_proxy+
D/libc    (  932): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605,
,D/ConnectivityService(  932): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/AlarmManager(  932): [AlarmQueuing] connectivity wifi: true,
D/GpsLocationProvider(  932): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  932): acquireWL(359fa43f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 932 1000 null
D/GpsLocationProvider(  932): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  932): acquireWL(be510c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 932 1000 null
D/GpsLocationProvider(  932): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  932): releaseWL(be510c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/htcCheckinService(  932): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/NetworkMonitor( 6792): type=WIFI subType= reason=null isConnected=true
,I/ConnectivityHelper( 1543): [onReceive] WIFI(1): CONNECTED
,V/MusicLeanback( 6792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  932): No APN found to select.,
,D/PMS     (  932): releaseWL(359fa43f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,D/AutoSetting( 1589): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6386): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 6386): onReceive CONNECTIVITY_CHANGE networkType=1
D/MdScPhnSt( 6728): [206.1.]  listen tmrbb8
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/HtcWifiWanDetect(  932): Find DNS Address www.htc.com/104.81.130.175
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  932): [NET] android_getaddrinfo_proxy-, success
D/AutoSetting( 1589): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1589): service - onStartCommand() screen is off, don't request location
,I/PackageManager(  932):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4389, uid=10024, userID:0
,D/MdScDataSum( 6728): [206.1.] summary 118:p1 ignore
,D/ChimeraCfgMgr( 4389): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4389): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1919): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1919): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1919): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1919): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
I/RemoteViews( 1216): reapply : com.google.android.gms 2 40
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Kids    ( 4389): [AccountUtils] Account not ready,
W/Kids    ( 4389): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4389): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4389): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4389): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4389): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4389): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4389): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4389): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4389): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4389): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4389): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4389): 	at java.lang.Thread.run(Thread.java:818)
,D/PMS     (  932): acquireWL(21901b2f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 932 1000 WorkSource{1000}
,V/AlarmManager(  932): sending alarm PendingIntent{102ccdec: PendingIntentRecord{3a59c5b5 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=137777, Int=0
,V/AlarmManager(  932): sending alarm PendingIntent{27fe153c: PendingIntentRecord{1a0f82c5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=138225, Int=0
,D/PMS     (  932): acquireWL(3bd0e41a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1919): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1919): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1919): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1919): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1919): [NET] android_getaddrinfo_proxy+
D/libc    ( 1919): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
D/PMS     (  932): releaseWL(21901b2f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1216): Weather sync is On
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1919): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1919): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1919): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1919): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1919): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  932): acquireWL(238d3b4b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1919 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1919): Connected
,D/PMS     (  932): releaseWL(3bd0e41a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): releaseWL(238d3b4b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): acquireWL(12354928): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1919 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1919): Message class com.google.f.a.a.p
,D/PMS     (  932): releaseWL(12354928): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6664): Test app app.js loaded
I/jxcore-log( 6664): 
,I/chromium( 6664): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PMS     (  932): acquireWL(350927e6): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6792 10159 null,
,I/PackageManager(  932):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6792, uid=10159, userID:0,
,I/ActivityManager(  932): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6941 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
D/PMS     (  932): releaseWL(350927e6): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 6792): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6792): Stop autocaching.
,W/ResourcesManager( 6941): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6941): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6941): VM with version 2.1.0 has multidex support
,I/MultiDex( 6941): install
I/MultiDex( 6941): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6941): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6941): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6941): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22f4d930: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6941): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1919): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1919): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4389): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 6941): callingUid 10024, callindPid: 6941
,I/PackageManager(  932):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4389, uid=10024, userID:0
,D/LocationInitializer( 4389): Restart initialization of location
,E/MDM     ( 1834): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6792): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6792): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  932): acquireWL(2ca14e70): PARTIAL_WAKE_LOCK  *alarm* 0x1 932 1000 WorkSource{10024}
V/AlarmManager(  932): sending alarm PendingIntent{134b5e9: PendingIntentRecord{2e14a26e com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142009, Int=0
,D/PMS     (  932): releaseWL(2ca14e70): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/Process (  932): killProcessQuiet, pid=5808,
I/ActivityManager(  932): Killing 5808:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  932): Recipient 5808,
,D/GpsLocationProvider(  932): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  932): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  932): acquireWL(375add0f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 932 1000 null
,D/libc    (  932): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  932): [NET] android_getaddrinfofornet-, err=8
D/libc    (  932): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024,
,D/libc    (  932): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  932): [NET] android_getaddrinfo_proxy+
D/libc    (  932): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  932): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  932): [NET] android_getaddrinfofornet+,hn 12(0x35342e3233392e),sn(),hints(known),family 0,flags 4,
D/libc    (  932): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  932): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  932): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  932): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  932):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  932): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
D/PMS     (  932): acquireWL(37723b2b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 932 1000 null
D/PMS     (  932): releaseWL(375add0f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  932): releaseWL(37723b2b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1489): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1489): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  932): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  932): acquireWL(17ec7b88): PARTIAL_WAKE_LOCK  *alarm* 0x1 932 1000 WorkSource{1000},
V/AlarmManager(  932): sending alarm PendingIntent{10843921: PendingIntentRecord{223a9146 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452294387012, Int=0
D/PMS     (  932): acquireWL(d575f07): PARTIAL_WAKE_LOCK  *backup* 0x1 932 1000 null
D/PMS     (  932): releaseWL(17ec7b88): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  932): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  932): Requested init for com.google.android.gms.backup.BackupTransportService but not found,
D/PMS     (  932): releaseWL(d575f07): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/AutoSetting( 1589): service - handleMessage() stop self
,D/AutoSetting( 1589): service - handleMessage() quit looper
,D/AutoSetting( 1589): service - onDestroy() END
,D/PMS     (  932): acquireWL(1391c834): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 932 1000 null,
I/BatteryService(  932): n_update end
D/UsbnetService(  932): BroadcastReceiver::onReceive+
D/UsbnetService(  932): onReceive BATTERY_CHANGED
D/PMS     (  932): releaseWL(1391c834): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  932):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  932): plugged=true pluggin=true
D/UsbnetService(  932): BroadcastReceiver::onReceive-
D/WifiController(  932): battery changed pluggedType: 2
D/WifiController(  932): handleMessage: E msg.what=155652
,D/PowerUI ( 1216): closing low battery warning: level=100
D/WifiController(  932): processMsg: DeviceActiveState
D/HtcPowerSaver(  932): updateBatteryInfo
D/WifiController(  932): processMsg: StaEnabledState
D/PMS     (  932): runPSCheck
D/WifiController(  932): processMsg: DefaultState
D/HtcPowerSaver(  932): Checking...
D/WifiController(  932): handleMessage: X
I/HtcPowerSaver(  932): >> updateStatus
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  932): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  932): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,E/WifiStateMachine(  932): handleMessage: E msg.what=131165,
E/WifiStateMachine(  932): processMsg: ConnectedState
E/WifiStateMachine(  932):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  932): processMsg: L2ConnectedState
E/WifiStateMachine(  932):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  932): processMsg: ConnectModeState
E/WifiStateMachine(  932):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  932): processMsg: DriverStartedState
E/WifiStateMachine(  932):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  932): processMsg: SupplicantStartedState
E/WifiStateMachine(  932):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  932): processMsg: DefaultState
,E/WifiStateMachine(  932):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  932): handleMessage: X
,D/TelephonyReceiver( 1489): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5
,E/WifiStateMachine(  932): handleMessage: E msg.what=131326,
E/WifiStateMachine(  932): processMsg: ConnectedState
E/WifiStateMachine(  932):  ConnectedState what:131326 2 0
E/WifiStateMachine(  932): processMsg: L2ConnectedState
E/WifiStateMachine(  932):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  932): handleMessage: X
,D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1589): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@6eb9bde
,I/ActivityManager(  932): Killing 6482:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  932): killProcessQuiet, pid=6482
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  932): Recipient 6482
,D/PMS     (  932): acquireWL(c4a465d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 932 1000 WorkSource{1000},
V/AlarmManager(  932): sending alarm PendingIntent{102ccdec: PendingIntentRecord{3a59c5b5 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=197777, Int=0
V/AlarmManager(  932): sending alarm PendingIntent{25fe7bd2: PendingIntentRecord{d80e4a3 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=211315, Int=0
V/AlarmManager(  932): sending alarm PendingIntent{3e9d33a0: PendingIntentRecord{1c69eb59 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=188680, Int=0,
,D/PMS     (  932): acquireWL(3ea4831e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): releaseWL(c4a465d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1216): Weather sync is On
,W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/PMS     (  932): acquireWL(133327ff): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): releaseWL(3ea4831e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  932): releaseWL(133327ff): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  932): acquireWL(1d9cac91): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  932): releaseWL(1d9cac91): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  932): acquireWL(216fd7f6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  932): releaseWL(216fd7f6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): acquireWL(eb017f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): acquireWL(2851a664): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  932): acquireWL(eb97d82): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): releaseWL(eb017f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1919): Vacuum at: now=1452294433837 tag=VacuumService,
,I/GoogleURLConnFactory( 1919): Using platform SSLCertificateSocketFactory
,D/PMS     (  932): releaseWL(2851a664): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  932): acquireWL(23b4c4d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  932): releaseWL(23b4c4d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  932): acquireWL(10cf5cc9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1919): No account for auth token provided,
,D/PMS     (  932): releaseWL(10cf5cc9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1919): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1919): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1919): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1919): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1919): [NET] android_getaddrinfo_proxy+
D/libc    ( 1919): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1919): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1919): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1919): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1919): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1919): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1919): No account for auth token provided,
,W/Uploader( 1919): No account for auth token provided,
,W/Uploader( 1919):  no longer exists, so no auth token.,
,W/Uploader( 1919): No account for auth token provided,
,I/GLSUser ( 1919): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1919): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1919): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1919): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1216): reapply : com.google.android.gms 2 40
,E/Uploader( 1919): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1919): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1919): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1919): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1919): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1919): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1919): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1919): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1919): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1919): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1919): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1919): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1919): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1919): No account for auth token provided,
,D/PMS     (  932): releaseWL(eb97d82): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  932): acquireWL(202b0200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): releaseWL(202b0200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): acquireWL(18ec0a39): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  932): releaseWL(18ec0a39): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  932): acquireWL(28b3e87e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 932 1000 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  932): n_update end
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  932): releaseWL(28b3e87e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1216): closing low battery warning: level=100
,D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
D/NotificationService(  932): plugged=true pluggin=true
D/UsbnetService(  932): BroadcastReceiver::onReceive+
D/WifiController(  932): battery changed pluggedType: 2
D/UsbnetService(  932): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  932): updateBatteryInfo
D/UsbnetService(  932):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  932): runPSCheck
D/UsbnetService(  932): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  932): Checking...
D/WifiController(  932): handleMessage: E msg.what=155652
I/HtcPowerSaver(  932): >> updateStatus
,D/WifiController(  932): processMsg: DeviceActiveState
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  932): processMsg: StaEnabledState
D/WifiController(  932): processMsg: DefaultState
D/WifiController(  932): handleMessage: X
,I/HtcPowerSaver(  932): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  932): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6664): --= Surplus to requirements =--
I/jxcore-log( 6664): 
,I/jxcore-log( 6664): ****TEST TOOK:  ms ****,
I/jxcore-log( 6664): 
,I/jxcore-log( 6664): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6664): 
,E/cutils-trace( 6989): Error opening trace file: Permission denied (13),
,D/CustomizationManager( 6989): ====startRecUseTime====,
D/htc.customization.log.level( 6989):  is 
W/CustomizationLogLevel( 6989): Level value is invalid, use default level 2
,D/CustomizationManager( 6989):  Read ACC file spent 0.053 (s),
,D/CIDMapFileReader( 6989): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 6989): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6989): Parsing tag item name = HTC__Y13,
D/CIDMapFileReader( 6989): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6989): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 6989): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6989): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 6989): full path : /system/customize/CID/HTC__102.xml,
,I/CustomizationCIDLoader( 6989): Parsing tag category name = system
,I/CustomizationCIDLoader( 6989): Parsing tag category name = application,
,I/CustomizationCIDLoader( 6989): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 6989): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6989): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6989): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6989): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 6989): add string-array item, value = 42507,
I/CustomizationCIDLoader( 6989): add string-array item, value = 21902
I/CustomizationCIDLoader( 6989): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6989): add string-array item, value = 23420
I/CustomizationCIDLoader( 6989): add string-array item, value = 22299
I/CustomizationCIDLoader( 6989): add string-array item, value = 24002
,I/CustomizationCIDLoader( 6989): add string-array item, value = 23210
I/CustomizationCIDLoader( 6989): add string-array item, value = 23205
I/CustomizationCIDLoader( 6989): add string-array item, value = 23806
I/CustomizationCIDLoader( 6989): add string-array item, value = 23430
I/CustomizationCIDLoader( 6989): add string-array item, value = 23408,
I/CustomizationCIDLoader( 6989): add string-array item, value = 27205
I/CustomizationCIDLoader( 6989): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6989): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6989): add string-array item, value = 26006:D:1:0,
I/CustomizationCIDLoader( 6989): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6989): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6989): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6989): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6989): add string-array item, value = 23205:D:0:0
,I/CustomizationCIDLoader( 6989): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6989): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6989): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6989): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6989):  Read CID file spent 0.110 (s)
,D/CustomizationManager( 6989):  All configurations done spent 0.110 (s)
,D/PackageManager(  932): deletePackageAsUser: pkg=com.test.thalitest, pid=6989, uid=2000 userid=0,
,I/ActivityManager(  932): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
,D/Process (  932): killProcessQuiet, pid=6664
,I/ActivityManager(  932): Killing 6664:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  932): Skipping PackageSetting{25efbece com.example.hello/10374} due to missing metadata,
,I/ActivityManager(  932): Recipient 6664
I/WindowState(  932): WIN DEATH: Window{31c5cbeb u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  932): Client connection lost with reason: 4,
,E/InputEventReceiver( 1390): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{6333bc7 uid 10366 pid 6664} (c)'
,I/ActivityManager(  932):   Force finishing activity ActivityRecord{9e76d94 u0 com.test.thalitest/.MainActivity t8}
,W/ActivityManager(  932): Spurious death for ProcessRecord{34e491df 6664:com.test.thalitest/u0a366}, curProc for 6664: null,
I/ActivityManager(  932): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
,D/DotMatrix( 1310): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
D/DotMatrix( 1310): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/PMS     (  932): acquireWL(127a10f5): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms},
W/SystemReader(  932): Cannot find grip_rejection_width, use default value instead
,W/GeofencerStateMachine( 1834): Ignoring removeGeofence because network location is disabled.
D/PMS     (  932): releaseWL(127a10f5): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 1736): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,D/AccTypeManager( 1736): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/InputMethodManagerService(  932): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/PhoneApp( 1489): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1589): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,D/VoicemailCleanupService( 1678): Cleaning up data for package: com.test.thalitest
,I/art     ( 1543): Explicit concurrent mark sweep GC freed 1818(113KB) AllocSpace objects, 4(268KB) LOS objects, 35% free, 29MB/45MB, paused 1.069ms total 106.442ms
,D/Prism.PackageStateRece_( 1543): action: android.intent.action.PACKAGE_REMOVED,
,I/Prism.ItemManager( 1543): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1543): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1736): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/ResourcesManager(  932): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Launcher( 1543): Deferring update until onResume
D/Launcher( 1543): waitUntilResume // bindAppsRemoved
,I/ActivityManager(  932): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7009 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,E/ExternalAccountType( 1736): Unsupported attribute readOnly
I/[PluginManager]RegisterService( 1589): handle notify Blinkfeed plugin client changed
,D/PMS     (  932): acquireWL(3cec8aeb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 932 1000 null,
I/BatteryService(  932): n_update end
D/PMS     (  932): releaseWL(3cec8aeb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/art     (  932): Explicit concurrent mark sweep GC freed 37851(2MB) AllocSpace objects, 6(324KB) LOS objects, 33% free, 16MB/25MB, paused 1.691ms total 227.467ms,
I/art     (  932): WaitForGcToComplete blocked for 199.739ms for cause Explicit
,W/ContextImpl( 7009): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 ,
,D/StatusBarManagerService(  932): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  932): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  932): hiding MENU key
D/StatusBarManagerService(  932): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  932): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  932): hiding MENU key
,D/FindExtension( 1543): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/ThreadedRenderer( 1543): Defer allocateBuffers to drawing time,
,I/ActivityManager(  932): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7033 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/InputMethodManagerService(  932): Got RemoteException sending setActive(false) notification to pid 6664 uid 10366
D/StatusBarManagerService(  932): swetImeWindowStatus vis=0 backDisposition=0
,D/Process (  932): killProcessQuiet, pid=6444
I/ActivityManager(  932): Killing 6444:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  932): Unable to load service info ResolveInfo{2171dacb com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  932): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  932): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  932): 	,at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  932): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  932): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  932): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  932): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  932): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  932): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  932): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  932): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  932): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  932): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  932): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  932): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  932): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  932): Recipient 6444
,D/JobSchedulerService(  932): Receieved: android.intent.action.PACKAGE_REMOVED,
,I/art     (  932): Explicit concurrent mark sweep GC freed 9942(664KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 2.253ms total 208.721ms
,D/HtcPowerSaver(  932): updateBatteryInfo
D/NotificationService(  932): plugged=true pluggin=true
D/UsbnetService(  932): BroadcastReceiver::onReceive+
,D/UsbnetService(  932): onReceive BATTERY_CHANGED
,D/UsbnetService(  932):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  932): runPSCheck
,D/UsbnetService(  932): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  932): Checking...
D/WifiController(  932): handleMessage: E msg.what=155652
I/HtcPowerSaver(  932): >> updateStatus
,D/WifiController(  932): processMsg: DeviceActiveState
D/WifiController(  932): battery changed pluggedType: 2
D/WifiController(  932): processMsg: StaEnabledState
I/HtcPowerSaver(  932): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  932): processMsg: DefaultState
I/HtcPowerSaver(  932): << updateStatus
D/WifiController(  932): handleMessage: X
D/TaskPersister(  932): removeObsoleteFile: deleting file=8_task.xml
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3120): Disconnected process message: 10, size: 0
,I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
,D/PowerUI ( 1216): closing low battery warning: level=100
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,I/PackageManager(  932):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7033, uid=10072, userID:0,
,W/global  ( 7033): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 7033): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 7033): [apache-http] Connection GC has been deprecated!
,W/global  ( 7033): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7033): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  932): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7072 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7033): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7033): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  932):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7033, uid=10072, userID:0
,W/ResourcesManager( 7072): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7072): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7072): VM with version 2.1.0 has multidex support
I/MultiDex( 7072): install
,I/MultiDex( 7072): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  932): Killing 6562:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  932): killProcessQuiet, pid=6562
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  932): Recipient 6562,
D/WifiService(  932): Client connection lost with reason: 4
,D/Finsky  ( 7033): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7033): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7033): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/SQLiteLog( 1919): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1919): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x5582341b90
,E/AndroidRuntime( 1919): FATAL EXCEPTION: main
E/AndroidRuntime( 1919): Process: com.google.process.gapps, PID: 1919
E/AndroidRuntime( 1919): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1919): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1919): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1919): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1919): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1919): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1919): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1919): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1919): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1919): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1919): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1919): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1919): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1919): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1919): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1919): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1919): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1919): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1919): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1919): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1919): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1919): 	... 9 more
E/ActivityManager(  932): App crashed! Process: com.google.process.gapps
V/JNIHelp ( 7072): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Process ( 1919): killProcess, pid=1919,
,D/Process ( 1919): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 ,
,E/DropBoxManagerService(  932): Can't write: system_app_crash
E/DropBoxManagerService(  932): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  932): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  932): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  932): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  932): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  932): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  932): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  932): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  932): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  932): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  932): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  932): 	... 5 more
,D/Finsky  ( 7033): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,W/ActivityThread( 7072): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7072): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22f4d930: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7072): Installed default security provider GmsCore_OpenSSL
,E/JavaBinder( 7072): !!! FAILED BINDER TRANSACTION !!!
,W/NativeLibraryUtils( 7072): Failed to open lock file,
W/NativeLibraryUtils( 7072): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7072): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7072): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7072): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7072): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7072): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7072): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7072): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/NativeLibraryUtils( 7072): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7072): 	... 3 more
I/ActivityManager(  932): Recipient 1919
,I/ActivityManager(  932): Process com.google.process.gapps (pid 1919) has died
W/ActivityManager(  932): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,W/ActivityManager(  932): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 11000ms
W/ActivityManager(  932): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 21000ms
W/ActivityManager(  932): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
,I/ActivityManager(  932): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=7109 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/ActivityThread( 7072): Removing dead content provider:android.content.ContentProviderProxy@5500b2e
,W/ResourcesManager( 7109): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7109): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7109): VM with version 2.1.0 has multidex support,
I/MultiDex( 7109): install
I/MultiDex( 7109): VM has multidex support, MultiDex support library is disabled.
,I/GservicesProvider( 7109): Gservices pushing to system: true; secure/global: true,
,E/SQLiteDatabase( 7109): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.,
,E/SQLiteDatabase( 7109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/SQLiteDatabase( 7109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7109): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7109): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7109): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7109): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7109): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7109): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7109): 	at android.app.ActivityThread.install,Provider(ActivityThread.java:5421)
E/SQLiteDatabase( 7109): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7109): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7109): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7109): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7109): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7109): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7109): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7109): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7109): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7109): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7109): FATAL EXCEPTION: main
E/AndroidRuntime( 7109): Process: com.google.process.gapps, PID: 7109
E/AndroidRuntime( 7109): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7109): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7109): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7109): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7109): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7109): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7109): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7109): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7109): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7109): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7109): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7109): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7109): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7109): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7109): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/Andro,idRuntime( 7109): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7109): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7109): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7109): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7109): 	... 11 more
E/ActivityManager(  932): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  932): Can't write: system_app_crash
E/DropBoxManagerService(  932): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  932): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  932): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  932): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  932): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  932): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  932): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  932): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  932): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  932): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  932): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  932): 	... 5 more
D/Process ( 7109): killProcess, pid=7109
D/Process ( 7109): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/ActivityManager(  932): Recipient 7109
I/ActivityManager(  932): Process com.google.process.gapps (pid 7109) has died
W/ActivityManager(  932): Service crashed 2 times, stopping: ServiceRecord{25675594 u0 com.google.android.gms/.gcm.GcmService}
W/ActivityManager(  932): Service crashed 2 times, stopping: ServiceRecord{231b3a36 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
W/ActivityManager(  932): Service crashed 2 times, stopping: ServiceRecord{1e616077 u0 com.google.android.gms/.gcm.http.GoogleHttpService}
W/ActivityManager(  932): Service crashed 2 times, stopping: ServiceRecord{dafa6ea u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,I/ActivityManager(  932): Start proc com.google.process.gapps for restart com.google.process.gapps: pid=7131 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 7131): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7131): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1543): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1543): loadItems() com.htc.launcher.pageview.WidgetManager@17e7b13b +
I/Prism.WidgetManager( 1543): onLoadItems() +
,I/MultiDex( 7131): VM with version 2.1.0 has multidex support
,I/MultiDex( 7131): install
I/MultiDex( 7131): VM has multidex support, MultiDex support library is disabled.
,I/GservicesProvider( 7131): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7131): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
,E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7131): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7131): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7131): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7131): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7131): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7131): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7131): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7131): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7131): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7131): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7131): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7131): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7131): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7131): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7131): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7131): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7131): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/ResourcesManager( 1543): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/AndroidRuntime( 7131): FATAL EXCEPTION: main
E/AndroidRuntime( 7131): Process: com.google.process.gapps, PID: 7131
E/AndroidRuntime( 7131): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7131): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7131): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7131): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7131): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7131): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7131): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7131): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7131): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7131): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7131): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7131): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7131): 	at com.android.internal.os.ZygoteInit.main(Z,ygoteInit.java:824)
E/AndroidRuntime( 7131): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7131): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7131): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7131): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7131): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7131): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7131): 	... 11 more
W/ActivityManager(  932): Process com.google.android.gms has crashed too many times: killing!
E/ActivityManager(  932): App crashed! Process: com.google.process.gapps
I/ActivityManager(  932): Killing 7131:com.google.process.gapps/u0a24 (adj 0): crash
D/Process (  932): killProcessQuiet, pid=7131
E/DropBoxManagerService(  932): Can't write: system_app_crash
E/DropBoxManagerService(  932): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  932): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  932): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  932): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  932): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  932): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  932): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  932): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  932): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  932): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  932): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  932): 	... 5 more
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12134 
,W/ResourcesManager( 1543): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  932): Recipient 7131
,D/Process (  932): killProcessQuiet, pid=7072
I/ActivityManager(  932): Killing 7072:com.google.android.gms:car/u0a24 (adj 0): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
D/Process (  932): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:15264 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:15341 
W/ActivityManager(  932): Unable to launch app com.google.android.gsf/10024 for provider com.google.android.gsf.gservices: launching app became null
,W/asset   ( 1543): Copying FileAsset 0x5582964440 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/ActivityManager(  932): Recipient 7072
,E/Prism.WidgetManager( 1543): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1543): onLoadItems() -
I/Prism.ItemManager( 1543): loadItems() com.htc.launcher.pageview.WidgetManager@17e7b13b -
,E/SQLiteLog( 1543): (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=75] disk I/O error
,E/SQLiteDBG( 1543): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0x55822b7cf0
,E/AndroidRuntime( 1543): FATAL EXCEPTION: TaskWorker
E/AndroidRuntime( 1543): Process: com.htc.launcher, PID: 1543
E/AndroidRuntime( 1543): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1543): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1543): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1543): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1543): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1543): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1543): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1543): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 1543): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 1543): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1543): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1543): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1543): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1543): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1543): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
