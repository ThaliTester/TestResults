#### Test 62560673a3c76e9_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1535): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@6d88166
--------- beginning of system
I/ActivityManager(  972): Killing 5776:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=5776
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  972): Recipient 5776
E/cutils-trace( 6452): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6452): ====startRecUseTime====
D/htc.customization.log.level( 6452):  is 
W/CustomizationLogLevel( 6452): Level value is invalid, use default level 2
D/CustomizationManager( 6452):  Read ACC file spent 0.048 (s)
D/CIDMapFileReader( 6452): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6452): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6452): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6452): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6452): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6452): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6452): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6452): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6452): Parsing tag category name = system
I/CustomizationCIDLoader( 6452): Parsing tag category name = application
I/CustomizationCIDLoader( 6452): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6452): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6452): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6452): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6452): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6452): add string-array item, value = 42507
I/CustomizationCIDLoader( 6452): add string-array item, value = 21902
I/CustomizationCIDLoader( 6452): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6452): add string-array item, value = 23420
I/CustomizationCIDLoader( 6452): add string-array item, value = 22299
I/CustomizationCIDLoader( 6452): add string-array item, value = 24002
I/CustomizationCIDLoader( 6452): add string-array item, value = 23210
I/CustomizationCIDLoader( 6452): add string-array item, value = 23205
I/CustomizationCIDLoader( 6452): add string-array item, value = 23806
I/CustomizationCIDLoader( 6452): add string-array item, value = 23430
I/CustomizationCIDLoader( 6452): add string-array item, value = 23408
I/CustomizationCIDLoader( 6452): add string-array item, value = 27205
I/CustomizationCIDLoader( 6452): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6452): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6452):  Read CID file spent 0.100 (s)
D/CustomizationManager( 6452):  All configurations done spent 0.101 (s)
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6452 on display 0
D/PMS     (  972): acquireHCC(20f742ca): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 972 1000 null
D/PMS     (  972): acquireHCC(11dd2c3b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 972 1000 null
I/ActivityManager(  972): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6470 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  972): Display changed displayId=0
D/DotMatrix( 1340): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1340): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1632): [trimMemory] 20
I/WebViewFactory( 6470): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6470): Time to load native libraries: 13 ms (timestamps 3512-3525),
,I/LibraryLoader( 6470): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6470): Binding Chromium to main looper Looper (main, tid 1) {1d042085},
I/LibraryLoader( 6470): Expected native library version number "",actual native library version number ""
,I/chromium( 6470): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6470): Initializing chromium process, singleProcess=true,
,W/art     ( 6470): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6470): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6470): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6470): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6470): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6470): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6470): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6470): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6470): Local Branch: 
I/Adreno-EGL( 6470): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6470): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6470):                  d74aa161a12b9c6fc6332151
,W/System.err(  972): java.lang.Throwable: stack dump
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33cb6170:true
,D/BluetoothAdapter( 6470): 331469288: getState(). Returning 12
,W/art     ( 6470): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6470): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6470): CordovaWebView is running on device made by: HTC
,W/art     ( 6470): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6470): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  972): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
W/chromium( 6470): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000600),
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key,
D/StatusBarManagerService(  972): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
,D/FindExtension( 6470): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6470): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2374b8e2, mServedView=org.apache.cordova.engine.SystemWebView{9d3c473 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@18f7df30
,I/InputMethodManagerService(  972): Disable input method client, pid=1632
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6470): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  972): Displayed com.test.thalitest/.MainActivity: +678ms (total +723ms)
,W/BindingManager( 6470): Cannot call determinedVisibility() - never saw a connection for the pid: 6470,
,D/JsMessageQueue( 6470): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6470): JniHelper::setJavaVM(0xab1898f8), pthread_self() = -1404302488
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6470):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6470):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6470):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6470):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6470): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21877cf4 added. We now have 1 listener(s)
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6470): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6470): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb6b063 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6470): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  972): New client listening to asynchronous messages
E/WifiTrafficPoller(  972): ADD_CLIENT: 8
,D/BluetoothAdapter( 6470): 331469288: getState(). Returning 12
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6470): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6470): setScanMode: 1 -> 2
,D/BluetoothAdapter( 6470): 331469288: getState(). Returning 12
,I/chromium( 6470): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6470): Initializing JXcore engine,
W/jxcore-log( 6470): JXcore engine is ready
,W/jxcore-log( 6470): Starting JXcore engine
,D/PMS     (  972): releaseHCC(20f742ca): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  972): releaseHCC(11dd2c3b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6470): Platform android,
W/jxcore-log( 6470): 
W/jxcore-log( 6470): Process ARCH arm,
W/jxcore-log( 6470): 
,I/jxcore-log( 6470): JXcore Cordova bridge is ready!,
I/jxcore-log( 6470): 
W/jxcore-log( 6470): JXcore engine is started
I/org.thaliproject.p2p.ThaliPermissions( 6470): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/BluetoothAdapter( 6470): 331469288: getState(). Returning 12,
V/io.jxcore.node.JXcoreExtension( 6470): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log( 6470): WARN testUtils BLE multiple advertisement issue: null,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): INFO testUtils Toggling radios to: true
I/jxcore-log( 6470): 
,D/BluetoothAdapter( 6470): enable(): BT is already enabled..!,
I/jxcore-log( 6470): Unit Test app is loaded
I/jxcore-log( 6470): 
,D/WifiManager( 6470): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10195
,D/WifiService(  972): setWifiEnabled: true pid=6470, uid=10195
E/WifiService(  972): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  972): isSprintWifiRestricted(): false
I/WifiService(  972): isMdmWifiRestricted(): false
W/Settings:Agent(  972): MONITOR_LOG
W/Settings:Agent(  972): name: wifi_on
W/Settings:Agent(  972): value: 2
W/Settings:Agent(  972): >> traceCallingStack()
W/Settings:Agent(  972): Process.myPid(): 972
W/Settings:Agent(  972): Process.myTid(): 1627
W/Settings:Agent(  972): Process.myUid(): 1000
W/Settings:Agent(  972): 
W/Settings:Agent(  972): 
W/System.err(  972): java.lang.Throwable: stack dump
,I/chromium( 6470): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56),
W/System.err(  972): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  972): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  972): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  972): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  972): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  972): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  972): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  972): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  972): 
W/Settings:Agent(  972): << traceCallingStack(): 19(ms)
D/WifiController(  972): handleMessage: E msg.what=155656
D/WifiManager( 6470): disconnect: Base Package Name=com.test.thalitest, uid=10195
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131145
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState CMD_DISCONNECT 0 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1330): wlan0: Cancelling scan request
D/wpa_supplicant( 1330): wlan0: Request to deauthenticate - bssid=f4:f2:6d:22:99:3e pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1330): TDLS: Tear down peers
D/wpa_supplicant( 1330): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiManager( 6470): reconnect: Base Package Name=com.test.thalitest, uid=10195
,D/wpa_supplicant( 1330): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1330): wlan0: Deauthentication notification
D/wpa_supplicant( 1330): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1330): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
,I/wpa_supplicant( 1330): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422
E/wpa_supplicant( 1330): enter disconnect check
I/wpa_supplicant( 1330): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1330): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1330): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422
E/WifiMonitor(  972): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422
D/HTCRequest(  972): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422
E/WifiMonitor(  972): WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  972): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  972): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  972): TetherInterfaceSM: wlan0: enter UnavailableState
,D/Tethering(  972): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  972): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbDeviceManager(  972): [USBNET] bCheckSuppFunc: cdc_network,
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
,D/PMS     (  972): acquireWL(13609b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
D/UsbnetService(  972): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1330): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1330): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1330): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1330): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1330): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55cab69f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 1330):    addr=f4:f2:6d:22:99:3e
D/wpa_supplicant( 1330): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1330): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1330): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1330): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1330): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1330): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1330): nl80211: Skip set_supp_port(unauthorized) while not associated
,D/wpa_supplicant( 1330): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1330): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1330): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1330): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1330): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1330): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1330): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1330): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1330): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1330): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1330): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
,D/wpa_supplicant( 1330): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1330): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  972): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  972): invokeExitMethods: ConnectedState
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiStateMachine(  972): WifiStateMachine: Leaving Connected state
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,D/WifiPerfLock(  972): release()
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
E/WifiStateMachine(  972): PerfLock released for exiting ConnectedState
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  972): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  972): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  972): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
,E/WifiStateMachine(  972): handleNetworkDisconnect f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  972): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1330): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/TetherSettings( 5862): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5862): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5862): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5862): Cust_ConnectToPC   : spcsc>false
D/        ( 5862): Cust_ConnectToPC   : IPT>true
,D/        ( 5862): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5862): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5862): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5862): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 5862): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,W/ContextImpl( 5862): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 ,
I/SmartNS_Utility( 5862): setISNotification
,D/SmartNS_Utility( 5862): usb_cable_connect = 1
,D/SmartNS_Utility( 5862): usb_denied = 0
,I/SmartNS_PSService( 5862): usb notificaiton:true
D/PMS     (  972): releaseWL(13609b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
,I/ActionCombine( 5862): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/wpa_supplicant( 1330): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1330): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  972): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1330): Power_Mode_Type mode = 0
I/wpa_supplicant( 1330): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1330): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  972): setDhcpActive: false
D/WifiP2pService(  972): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 1863): Read error: ssl=0x55b01c90c0: I/O error during system call, Connection timed out
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  972): acquireWL(37486391): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1863 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  972): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  972): setDetailed state send new extra info<unknown ssid>
,E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  972): NetworkAgent != null
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  972): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/SmartNS_Utility( 5862): usb_cable_connect = 1
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/SmartNS_Utility( 5862): usb_denied = 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
I/SmartNS_PSService( 5862): usb notificaiton:true
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  972): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
V/NativeCrypto( 1863): SSL shutdown failed: ssl=0x55b01c90c0: I/O error during system call, Broken pipe
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/WifiDataStallTracker(  972): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  972): stopDataStallAlarm 
D/wpa_supplicant( 1330): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1330): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/wpa_supplicant( 1330): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
,D/wpa_supplicant( 1330): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  972): invokeEnterMethods: DisconnectingState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiDataStallTracker(  972): ENABLE_DATA_MONITOR_POLL false Token 3
E/WifiStateMachine(  972):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  972): Start Disconnecting Watchdog 1
E/WifiStateMachine(  972): handleMessage: X
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  972): handleMessage: E msg.what=131146
E/WifiStateMachine(  972): processMsg: DisconnectingState
D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  972):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1330): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1330): Fast associate: Old scan results
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1330): WPS:  * UUID-E
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1330): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1330): WPS:  * Manufacturer
D/wpa_supplicant( 1330): WPS:  * Model Name
D/wpa_supplicant( 1330): WPS:  * Model Number
,D/wpa_supplicant( 1330): WPS:  * Device Name
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1330): P2P: * P2P IE header
D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 11
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x55cab6c680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/ConnectivityService(  972): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x55cab6c680 after 0.000049 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000094 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=147460
E/WifiStateMachine(  972): processMsg: DisconnectingState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  972):  DisconnectingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=228652
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=228652
E/WifiStateMachine(  972): ConnectModeState: Network connection lost 
E/WifiStateMachine(  972): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  972): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  972): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  972): DisconnectedState call setCountryCode()
E/WifiStateMachine(  972):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1330): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1330): wlan0: Cancelling scan request
D/PMS     (  972): releaseWL(37486391): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/SmartNS_NSReceiver( 5862): Tethered state change:false isNSOpening:false
D/wpa_supplicant( 1330): wlan0: nl80211: sched_scan request
D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/RemoteViews( 1223): reapply : com.android.settings 1 36
I/RemoteViews( 1223): reapply : com.android.settings 1 36
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Validated
,I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/wpa_supplicant( 1330): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1330): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Sched scan started
D/WifiP2pService(  972): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/WifiP2pService(  972): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 0.044004 seconds
D/wpa_supplicant( 1330): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1330): BSS: last_scan_res_used=0/32
D/wpa_supplicant( 1330): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55cab6c680 done in 0.044722 seconds
D/wpa_supplicant( 1330): wlan0: No suitable network found
D/wpa_supplicant( 1330): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1330): wlan0: Cancelling sched scan
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131101
D/wpa_supplicant( 1330): nl80211: Sched scan stop sent (ret=0)
E/WifiStateMachine(  972): processMsg: DisconnectedState
D/wpa_supplicant( 1330): wlan0: Cancelling scan request
D/wpa_supplicant( 1330): p2p0: Updating scan results from sibling
D/wpa_supplicant( 1330): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1330): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 1330): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1330): p2p0: New scan results available (own=0 ext=0)
D/wpa_supplicant( 1330): p2p0: No suitable network found
D/wpa_supplicant( 1330): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1330): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  972): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  972):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
D/WifiMonitor(  972): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor(  972): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  972): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  972):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  972): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=228698  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
E/WifiStateMachine(  972): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  972): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=228698  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
E/WifiStateMachine(  972): handleMessage: X
D/WifiNetworkAgent(  972): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  972): handleMessage: E msg.what=131212
E/WifiStateMachine(  972): processMsg: DisconnectedState
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  972):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  972): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131212
E/WifiStateMachine(  972): processMsg: DisconnectedState
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  972):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  972): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131212
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  972): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  972): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=228710  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  972): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  972): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  972): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  972): NetworkAgent == null
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=228715  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=147461
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 dur:2357 bcn=0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 dur:2357 bcn=0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 dur:2357 bcn=0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  972):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 dur:2357 bcn=0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  972): [1,457,954,343,261 ms] noteScanEnd no scan source
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/WISPrService( 5862): >>>>>WISPrService start isConnected = true<<<<<
,E/WifiStateMachine(  972): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@304a3467 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  972): NG700_GUEST f0:f2:6d:22:99:3e rssi=-46 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  972): NG700 f4:f2:6d:22:99:3e rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  972): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  972): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  972):         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-52 freq=2422
E/WifiAutoJoinController (  972): TEST_KTW01 00:1f:27:54:70:c1 rssi=-54 cap [WPA2-EAP-TKIP][ESS] is not scored
E/WifiAutoJoinController (  972): ktwtestwifi 00:1f:27:54:70:c0 rssi=-54 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  972):  00:1f:27:54:e0:44 rssi=-77 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  972): RA-WINGS 00:1f:27:54:dd:e3 rssi=-75 cap [ESS] is not scored
E/WifiAutoJoinController (  972): RA-WINGS 00:1f:27:54:e0:43 rssi=-77 cap [ESS] is not scored
E/WifiAutoJoinController (  972):  00:1f:27:54:e0:40 rssi=-77 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  972):  00:16:a6:1f:06:5c rssi=-78 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  972):  00:1f:27:54:e0:42 rssi=-79 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  972): DELL S320wi INTERACTIVE 00:12:0e:f8:c9:a1 rssi=-86 cap [ESS] is not scored
E/WifiAutoJoinController (  972): ageScanResultsOut delay 40000 size 11 now 1457954343271
E/WifiAutoJoinController (  972): newSupplicantResults size=11 known=1 true
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  972): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  972): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  972): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  972): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  972): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  972): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-52,-127) num=(1,0)
E/WifiAutoJoinController (  972): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  972): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
E/WifiStateMachine(  972): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  972): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
E/WifiAutoJoinController (  972): attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-52 freq=2422
D/HtcWifiControlRoamOffload: (  972): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  972): Done attemptAutoJoin status=3
E/WifiConfigStore(  972):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131215
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-52 ;0 ,-127] any roam=0 rt=228733
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-52 ;0 ,-127] any roam=0 rt=228734
E/WifiStateMachine(  972): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  972): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  972): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
D/WifiService(  972): New client listening to asynchronous messages
E/WifiTrafficPoller(  972): ADD_CLIENT: 9
D/ConnectivityService(  972): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  972): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Disconnected - quitting
D/ConnectivityService(  972): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524292
D/ConnectivityService(  972): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkManagementService(  972): Removing idletimer
I/SecurityController( 1223): onLost 100
D/usbnet  (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  972):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/PMS     (  972): acquireWL(303426f7): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 972 1000 null
D/CSLegacyTypeTracker(  972): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
,D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,E/ConnectivityService(  972): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiConfigStore(  972): Setting BSSID for "NG700"WPA_PSK to any
,E/ConnectivityService(  972): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  972): ensureActiveMobilePolicyLocked()
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/PMS     (  972): acquireWL(41e0964): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/Tethering(  972): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/NetworkPolicy(  972): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/Tethering(  972): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  972): updateIfacesLocked()
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
V/NetworkPolicy(  972): updateNotificationsLocked()
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/DATA_ICON( 1223): dataConnected: false/false
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/NetworkManagementService(  972): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/PMS     (  972): releaseWL(41e0964): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  972): updateNotificationsLocked()
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
,D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1330): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  972): will read network variables netId=0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1330): Do not allow key_data field to be exposed
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant,( 1330): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
,D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/FlexNetS( 6327): updateSvcAllowedInSettings:false
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  972): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  972):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  972): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1330): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1330): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1330): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  972): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 1330): ENABLE_NETWORK (0)
D/wpa_supplicant( 1330): CTRL_IFACE: ENABLE_NETWORK id=0
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1330): WPS:  * UUID-E
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1330): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1330): WPS:  * Manufacturer
D/wpa_supplicant( 1330): WPS:  * Model Name
D/wpa_supplicant( 1330): WPS:  * Model Number
D/wpa_supplicant( 1330): WPS:  * Device Name
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1330): P2P: * P2P IE header
D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 11
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x55cab6c680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x55cab6c680 after 0.000036 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (re,t=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000076 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  972): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 1330): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  972): will read network variables netId=0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 1330): Do not allow key_data field to be exposed
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 13,30): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 1330): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 1330): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  972): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  972):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1330): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1330): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1330): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 1330): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Already scanning - Reschedule the incoming scan req
D/wpa_supplicant( 1330): wlan0: Setting scan request: 1.000000 sec
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1330): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  972): setLastSelectedConfiguration -1
E/WifiStateMachine(  972): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  972): invokeExitMethods: DisconnectedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1330): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  972): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  972): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  972): DisconnectedState call setCountryCode()
E/WifiStateMachine(  972):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1330): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1330): wlan0: Cancelling scan request
D/wpa_supplicant( 1330): wlan0: nl80211: sched_scan request
D/FlexNetS( 6327): updateSvcAllowedInSettings:false
I/ActivityManager(  972): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6536 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/wpa_supplicant( 1330): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1330): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 0.044656 seconds
D/wpa_supplicant( 1330): nl80211: Received scan results (0 BSSes)
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 8
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to no match in scan
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 1 BSSID f4:f2:6d:22:99:3e SSID 'NG700' due to no match in scan
E/WifiStateMachine(  972): handleMessage: X
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to no match in scan
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to no match in scan
D/WIFI    (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:e0:44 SSID '\x00' due to no match in scan
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:e0:40 SSID '\x00' due to no match in scan
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 8 BSSID 00:16:a6:1f:06:5c SSID '' due to no match in scan
D/WIFI    (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  972): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 9 BSSID 00:1f:27:54:e0:42 SSID '\x00' due to no match in scan
E/WifiStateMachine(  972): handleMessage: E msg.what=131131
E/WifiStateMachine(  972): processMsg: DisconnectedState
D/WifiP2pService(  972): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 5 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to no match in scan
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e]
D/WifiP2pService(  972): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 6 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to no match in scan
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 10 BSSID 00:12:0e:f8:c9:a1 SSID 'DELL S320wi INTERACTIVE' due to no match in scan
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 f4:f2:6d:22:99:3e]
D/wpa_supplicant( 1330): BSS: last_scan_res_used=0/32
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 f4:f2:6d:22:99:3e
D/wpa_supplicant( 1330): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55cab6c680 done in 0.046088 seconds
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1]
D/wpa_supplicant( 1330): wlan0: No suitable network found
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1
D/wpa_supplicant( 1330): wlan0: Setting scan request: 15.000000 sec
D/wpa_supplicant( 1330): wlan0: Cancelling sched scan
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0
D/FlexNetS( 6327): updateSvcAllowedInSettings:false
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:e0:44]
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:e0:44
E/WifiStateMachine(  972):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  972): processMsg: ConnectModeState
D/wpa_supplicant( 1330): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1330): wlan0: Cancelling scan request
D/wpa_supplicant( 1330): p2p0: Updating scan results from sibling
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:e0:40]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:e0:40
D/wpa_supplicant( 1330): nl80211: Received scan results (0 BSSes)
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:16:a6:1f:06:5c]
D/wpa_supplicant( 1330): p2p0: BSS: Start scan result update 2
D/wpa_supplicant( 1330): BSS: last_scan_res_used=0/0
D/wpa_supplicant( 1330): p2p0: New scan results available (own=0 ext=0)
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:16:a6:1f:06:5c
D/wpa_supplicant( 1330): p2p0: No suitable network found
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:e0:42]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:e0:42
E/WifiStateMachine(  972):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/wpa_supplicant( 1330): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:e3]
D/wpa_supplicant( 1330): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1330): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:e3
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:e0:43]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:e0:43
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:12:0e:f8:c9:a1]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:12:0e:f8:c9:a1
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  972): handleMessage: X
E/WifiMonitor(  972): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  972): handleMessage: E msg.what=147461
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiMonitor(  972): WifiMonitor:p2p0 cnt=62 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  972): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  972):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 dur:2357 bcn=0
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 dur:2357 bcn=0
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 dur:2357 bcn=0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 dur:2357 bcn=0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  972): [1,457,954,343,380 ms] noteScanEnd no scan source
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  972): handleMessage: X
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/FlexNetS( 6327): updateSvcAllowedInSettings:false
W/WISPrService( 5862): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5862): trigger connection
D/WISPrService( 5862): continue
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WISPrService( 5862): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5862): start DataConnection
D/WISPrService( 5862): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/FlexNetS( 6327): updateSvcAllowedInSettings:false
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/WISPrService( 5862): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5862): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5862): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5862): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5862): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5862): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    ( 5862): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/libc    ( 5862): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5862): [NET] android_getaddrinfo_proxy+
D/WISPrService( 5862): >>>>>WISPrService start isConnected = false<<<<<
D/libc    ( 5862): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5862): [NET] android_getaddrinfo_proxy-, NODATA
D/WISPrService( 5862): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false
,D/libc    ( 5862): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 5862): [NET] android_getaddrinfofornet-, err=8
,D/WISPrService( 5862): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false
,D/FlexNetS( 6327): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6536): [93.2.]  listen tmrbb8,
,D/MdProvGlob( 6394): remove item 101 (p2d27in244) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 6536): [93.2.] summary 118:p2 ignore
,D/Process (  972): killProcessQuiet, pid=5375
,I/ActivityManager(  972): Killing 5375:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5375
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  972): acquireWL(2f5af3c9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{391cc769: PendingIntentRecord{3a3915ee android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=225459, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{36773ace: PendingIntentRecord{e02fdef com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=231640, Int=0
,D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  972): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  972): [AlarmQueuing] connectivity wifi: false
D/PMS     (  972): acquireWL(367f20fc): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 972 1000 null
D/GpsLocationProvider(  972): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  972): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  972): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  972): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/ConnectivityHelper( 1632): [onReceive] WIFI(1): DISCONNECTED
,I/art     (  972): Explicit concurrent mark sweep GC freed 48925(2MB) AllocSpace objects, 8(816KB) LOS objects, 33% free, 16MB/24MB, paused 1.913ms total 209.982ms,
D/PMS     (  972): acquireWL(2f160385): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1863 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1863): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1863): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1863): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1863): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1863): [NET] android_getaddrinfo_proxy+
D/libc    ( 1863): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1863): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  972): acquireWL(2f160385): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1863 10024 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1863): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1863): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  972): releaseWL(2f160385): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
I/ActivityManager(  972): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6571 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  972): releaseWL(2f5af3c9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
E/GpsLocationProvider(  972): No APN found to select.
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  972): releaseWL(367f20fc): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6536): [1de.1.]  listen tmrbb8,
,D/MdScDataSum( 6536): [1de.1.] summary 118:p1 ignore
,I/MusicStore( 6571): Database version: 120
,D/VoldConnector(  972): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6571): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  972): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6571): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  972): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,W/ContextImpl( 6571): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 6571): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6571): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6571): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6571): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6571): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@9c9c33: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6571): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6571): GMSCore installation verified
,I/ConfigStore( 6571): Config Database version: 1,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6571, uid=10159, userID:0,
,D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
,D/MediaRouterService(  972): Client com.google.android.music (pid 6571): Registered,
,D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
,I/MediaRouter( 6571): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6571): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6571, uid=10159, userID:0
,D/MobileConnectivityChangeReceiver( 6265): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6265): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1535): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1535): Util - no network available!,
,D/AutoSetting( 1535): service - onCreate(),
,I/GHttpClientFactory( 6571): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1535): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,I/iu.Environment( 4402): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4402): num queued entries: 0
D/LocationManagerService(  972): request 1b5c562f passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052),
I/iu.UploadsManager( 4402): num updated entries: 0
,D/LocationManagerService(  972): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1535): service - mHandler: cancel location update
D/AutoSetting( 1535): service -           changes count: 0
I/iu.SyncManager( 4402): NEXT; no task
I/GoogleURLConnFactory( 6571): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 4402): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4402): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/Babel   ( 4506): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  972): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6613 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/VoldConnector(  972): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
I/GAv4    ( 6613): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6613):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6613):   adb logcat -s GAv4
,D/VoldConnector(  972): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6613): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,D/VoldConnector(  972): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  972): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6613): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6613): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6613): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 6613): [apache-http] Connection GC has been deprecated!
,W/global  ( 6613): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6613): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 6613): Time to load native libraries: 3 ms (timestamps 3018-3021)
,I/LibraryLoader( 6613): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6613): Binding Chromium to main looper Looper (main, tid 1) {f0a5042},
,I/LibraryLoader( 6613): Expected native library version number "",actual native library version number "",
,I/chromium( 6613): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6613): Initializing chromium process, singleProcess=true,
,W/art     ( 6613): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6613): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6613): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6613): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6613): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6613): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6613): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6613): Build Date: 03/09/15 Mon,
I/Adreno-EGL( 6613): Local Branch: 
I/Adreno-EGL( 6613): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6613): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6613):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6613): Requires BLUETOOTH permission,
,I/NSApplication( 6613): Starting up...
,I/ActivityManager(  972): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6672 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  972): Killing 6220:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=6220
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/PMS     (  972): acquireWL(2050d733): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2050d733): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  972): Recipient 6220,
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  972): Checking...
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6470): My device name is: HTC-HTC One M8s
I/jxcore-log( 6470): 
,I/ActivityManager(  972): Killing 6291:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
D/Process (  972): killProcessQuiet, pid=6291
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/WifiStateMachine(  972): handleMessage: E msg.what=131168,
E/WifiStateMachine(  972): processMsg: DisconnectedState
E/WifiStateMachine(  972):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  972): processMsg: ConnectModeState
E/WifiStateMachine(  972):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
,E/WifiStateMachine(  972):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  972): handleMessage: X
,I/ActivityManager(  972): Recipient 6291,
,D/PMS     (  972): acquireWL(2587361c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6571 10159 null,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6571, uid=10159, userID:0,
,I/MusicLeanback( 6571): Conditions not met for autocaching. okToAttempt=false,
D/PMS     (  972): releaseWL(2587361c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6571): Stop autocaching.
,D/WearableService( 5098): callingUid 10024, callindPid: 5098,
,E/GmsUtils( 6571): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 6571): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/PMS     (  972): acquireWL(15b29e7f): PARTIAL_WAKE_LOCK  *alarm* 0x1 972 1000 WorkSource{10024}
V/AlarmManager(  972): sending alarm PendingIntent{3e925e4c: PendingIntentRecord{e02fdef com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=237857, Int=0
,D/PMS     (  972): acquireWL(37d57e95): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1863 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(15b29e7f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/libc    ( 1863): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1863): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 1863): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1863): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1863): [NET] android_getaddrinfo_proxy+
D/libc    ( 1863): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1863): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  972): releaseWL(37d57e95): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/ActivityManager(  972): Waited long enough for: ServiceRecord{21bdf019 u0 com.htc.sense.hsp/.weather.location.AutoSettingService},
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 6470): 
,I/io.jxcore.node.ConnectivityInfo( 6470): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 6470):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6470):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6470):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 6470):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 6470):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 6470):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 6470):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 6470):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 6470): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 6470): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native,
I/jxcore-log( 6470): 
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/AutoSetting( 1535): service - handleMessage() stop self,
,D/AutoSetting( 1535): service - handleMessage() quit looper,
,I/ActivityManager(  972): Killing 5887:com.android.vending/u0a72 (adj 15): empty #17
D/AutoSetting( 1535): service - onDestroy() END
D/Process (  972): killProcessQuiet, pid=5887
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5887
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
I/jxcore-log( 6470): 
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  972): releaseWL(303426f7): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  972): Failed to find a new network - expiring NetTransition Wakelock
,D/PMS     (  972): acquireWL(eb67baa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(eb67baa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED,
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: E msg.what=155652
D/HtcPowerSaver(  972): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  972): runPSCheck
D/WifiController(  972): processMsg: DeviceActiveState
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  972): acquireWL(2cdca39b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2cdca39b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
,D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): runPSCheck
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  972): acquireWL(38ad1338): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
V/AlarmManager(  972): sending alarm PendingIntent{391cc769: PendingIntentRecord{3a3915ee android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=285458, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{9d8a876: PendingIntentRecord{35d7de77 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457954473947, Int=0,
,D/PMS     (  972): releaseWL(38ad1338): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  972): acquireWL(39bc2ae4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(39bc2ae4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
,D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): << updateStatus
,D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  972): acquireWL(3a87eb4d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(3a87eb4d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo,
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): acquireWL(201ed602): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  972): n_update end
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  972): releaseWL(201ed602): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
,D/NotificationService(  972): plugged=true pluggin=true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,W/bt_userial_mct( 3119): userial_device in reset 
E/        ( 3119): utils_delay : 2000 **
,D/ContactMessageStore( 1570): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1570): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1570): sku_id=118
D/ContactMessageStore( 1570): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1570): start background delete task...
,D/ContactMessageStore( 1570): size: 0 , 0
,D/ContactMessageStore( 1570): Background delete complete
,E/bt_mct  ( 3119): sending H/w error event to stack
E/bt_mct  ( 3119):  
,E/bt-hci  ( 3119): Ctlr H/w error event - code:0xa
D/bt-btm  ( 3119): btm_acl_device_down
D/PMS     (  972): acquireWL(19e1eb13): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3119 1002 null
,D/bt-btm  ( 3119): btm_acl_reset_paging
D/bt-btm  ( 3119): btm_acl_set_discing
E/bt-btif ( 3119): Received H/W Error. 
,I/ActivityManager(  972): Recipient 3119
,D/BluetoothManagerService(  972): BluetoothServiceConnection, disconnected: com.android.bluetooth.btservice.AdapterService
D/PMS     (  972): handleWLDeath(19e1eb13): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1
,D/BluetoothA2dp(  972): Proxy object disconnected
D/BluetoothHeadset(  972): Proxy object disconnected
D/BluetoothManagerService(  972): BluetoothServiceConnection, disconnected: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
E/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED: 1
,D/BluetoothManagerService(  972): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  972): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothAdapter( 2345): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1a3c222a
D/BluetoothAdapter( 2345): onBluetoothServiceDown: done
D/BluetoothAdapter( 1590): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@200eee39
D/BluetoothAdapter( 1590): onBluetoothServiceDown: done
D/BluetoothA2dp( 3684): Proxy object disconnected
D/BluetoothAdapter( 6470): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4b7d289
D/BluetoothAdapter( 6470): onBluetoothServiceDown: done
D/BluetoothHeadset( 1223): Proxy object disconnected
I/QuickSettingMiniLite( 1223): btListener.disconnect:HEADSET
D/NGFService( 3684): BluetoothA2dp onServiceDisconnected: main
D/BluetoothHeadset( 1570): Proxy object disconnected
D/BluetoothHeadset( 3684): Proxy object disconnected
D/NGFService( 3684): BluetoothHeadset onServiceDisconnected: main
D/BluetoothAdapter( 3684): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2ec32b71
D/BluetoothHeadset( 1570): Proxy object disconnected
D/BluetoothAdapter( 3684): onBluetoothServiceDown: done
D/BluetoothAdapter(  972): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3b0ca30e
D/BluetoothAdapter(  972): onBluetoothServiceDown: done
D/BluetoothAdapter( 1223): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@16766210
,D/BluetoothAdapter( 1223): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1570): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@519b748,
D/BluetoothAdapter( 1570): onBluetoothServiceDown: done
D/BluetoothAdapter( 1807): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3e2980b9
D/BluetoothAdapter( 1807): onBluetoothServiceDown: done
D/BluetoothManagerService(  972): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothPhoneService( 1570): BluetoothHeadset onServiceDisconnected,
D/BluetoothHeadset( 1570): Proxy object disconnected
,W/BluetoothHeadset( 1223): Proxy not attached to service
,I/QuickSettingMiniLite( 1223): updateLiteState:no connect device!
,E/libprocessgroup(  972): failed to kill 1 processes for processgroup 3119
I/ActivityManager(  972): Process com.android.bluetooth (pid 3119) has died
,W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
,W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 10999ms
,W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.hid.HidService in 20999ms
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.pan.PanService in 20999ms
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.gatt.GattService in 20999ms
,W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.a2dp.A2dpService in 30998ms
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.opp.BluetoothOppService in 30998ms
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 30998ms
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.hfp.HeadsetService in 30998ms
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.ftp.BluetoothFtpService in 30995ms
,W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 40994ms
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.hdp.HealthService in 40994ms
,D/BluetoothManagerService(  972): Broadcasting onBluetoothStateChange(false) to 8 receivers.,
D/BluetoothHeadset( 1223): onBluetoothStateChange: up=false
I/IntentController( 1223): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/NGFService( 3684): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,I/ActivityManager(  972): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6724 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a,
D/BluetoothHeadset(  972): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1570): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3684): onBluetoothStateChange: up=false
D/BluetoothHeadset( 3684): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1570): onBluetoothStateChange: up=false
D/BluetoothA2dp(  972): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1570): onBluetoothStateChange: up=false
D/BluetoothManagerService(  972): Bluetooth State Change Intent: 13 -> 10
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
E/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED: 2
D/BluetoothManagerService(  972): Message: UNKNOWN(42)
D/BluetoothManagerService(  972): MESSAGE_RESTART_BLUETOOTH_SERVICE: Restart IBluetooth service
D/NGFService( 3684): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3684): Bluetooth Adapter: OFF
I/QuickSettingBluetooth( 1223): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/NfcHandover( 1590): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
I/IntentController( 1223): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/art     (  416): Explicit concurrent mark sweep GC freed 8673(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 340us total 46.206ms
,W/ResourcesManager( 6724): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
,I/art     (  416): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 394us total 22.481ms
D/BluetoothAdapter( 1223): 180682956: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1223): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,I/art     (  416): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 298us total 23.754ms,
,D/AdapterServiceConfig( 6724): Adding HeadsetService,
,D/AdapterServiceConfig( 6724): Adding A2dpService
,D/AdapterServiceConfig( 6724): Adding HidService
D/AdapterServiceConfig( 6724): Adding HealthService
D/AdapterServiceConfig( 6724): Adding PanService
D/AdapterServiceConfig( 6724): Adding GattService
,W/linker  ( 6724): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  972): java.lang.Throwable: stack dump,
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24a8504e:true
D/BluetoothAdapterState( 6724): make,
,I/BluetoothAdapterState( 6724): Entering OffState,
,E/bt_osi_config( 6724): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
,D/BluetoothManagerService(  972): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 6724): Address is:90:E7:C4:F6:69:77
,V/BluetoothPbapReceiver( 6724): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6724): ***********state = 13
,D/BluetoothManagerService(  972): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  972): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothAdapter( 6724): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@13c1d1e8
D/BluetoothAdapter( 6724): onBluetoothServiceUp done
D/BluetoothAdapter( 2345): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@35a75db8
,D/BluetoothAdapter( 2345): onBluetoothServiceUp done
E/BluetoothMasService( 6724): BluetoothMasObexConnectionManager: mIsEmailEnabled: true,
D/BluetoothAdapter( 1590): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@275c15df
,D/BluetoothAdapter( 1590): onBluetoothServiceUp done
D/BluetoothAdapter( 6470): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2360928e
,D/BluetoothAdapter( 6470): onBluetoothServiceUp done
,D/BluetoothAdapter( 3684): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2abc1d56
D/BluetoothAdapter( 3684): onBluetoothServiceUp done
D/BluetoothAdapter(  972): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3b69a98b
D/BluetoothAdapter(  972): onBluetoothServiceUp done
D/BluetoothAdapter( 1223): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@32b1f2d
D/BluetoothAdapter( 1223): onBluetoothServiceUp done
D/BluetoothAdapter( 1570): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2e8847db
D/BluetoothAdapter( 1570): onBluetoothServiceUp done
D/BluetoothAdapter( 1807): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@24fa5cfe
D/BluetoothAdapter( 1807): onBluetoothServiceUp done
D/BluetoothManagerService(  972): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 6724): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6724): Setting state to 11
,I/BluetoothAdapterState( 6724): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  972): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  972): Bluetooth State Change Intent: 10 -> 11
D/BluetoothMasService( 6724): Add permission for SmsProvider.
,V/BluetoothMasService( 6724): Starting MAS instances
I/IntentController( 1223): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothAdapter( 6724): 863760615: getState(). Returning 11
,D/NGFService( 3684): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,I/MailMessageReceiver( 6724): reg:com.android.bluetooth.btservice.AdapterApp@28d62494 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@cadb3d
,D/PMS     (  972): acquireWL(2c7cc3b2): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5862 1000 null
I/MailManager( 6724): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@cadb3d
V/EmailUtils( 6724): Manager Instance is not NULL
,D/BluetoothBondStateMachine( 6724): make
,D/BluetoothAdapterService( 6724): checkA2dpState: isA2dpSinkEnabled = false
,W/ContextImpl( 5862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
E/BluetoothAdapterService( 6724): checkA2dpState: returning
D/BluetoothAdapterService( 6724): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 6724): checkHfpState: returning
I/BluetoothBondStateMachine( 6724): StableState(): Entering Off State
,I/ActivityManager(  972): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6750 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/PMS     (  972): releaseWL(2c7cc3b2): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  972): acquireWL(1b656e80): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5862 1000 null
,I/QuickSettingBluetooth( 1223): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,I/ActivityManager(  972): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6766 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,W/System.err(  972): java.lang.Throwable: stack dump
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER,
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3761485f:true
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
,I/BluetoothAdapterState( 6724): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapter( 5862): 952617179: getState(). Returning 11,
,D/BluetoothInputDevice( 5862): BluetoothInputDevice(),
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 9
,D/BluetoothPan( 5862): BluetoothPan(),
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 10
,D/BluetoothMap( 5862): Create BluetoothMap proxy object,
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 11
E/BluetoothMap( 5862): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  972): registerStateChangeCallback+
,D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 12
D/BluetoothSap( 5862): BluetoothSap() call bindService
,D/HtcBtWidget_BTWidgetProvider( 6766): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 6766): updateWidget(context) for widget: 
,W/ContextImpl( 5862): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/BluetoothPbap( 5862): BluetoothPbap()
,D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 13,
,D/LocalBluetoothProfileManager( 5862): LocalBluetoothProfileManager construction complete
,D/HtcAdjCursorFactory( 6750): Set CursorWindow size to: 4194304 KB, Tid: 6782
,D/DockEventReceiver( 5862): finishStartingService: stopping service
,D/PMS     (  972): releaseWL(1b656e80): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/Process (  972): killProcessQuiet, pid=5812
I/ActivityManager(  972): Killing 5812:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 5812
,D/EmailUtils( 6724): ============NULL aList========
V/EmailUtils( 6724): <-getEmailAccountIdList
V/BluetoothMasService( 6724): onCreate: mIsEmailEnabled: true
,D/BluetoothManagerService(  972): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothAdapter( 6724): 863760615: getState(). Returning 11
,V/BluetoothPbapService( 6724): Pbap Service onCreate
V/BluetoothPbapService( 6724): Starting PBAP service
,D/BluetoothAdapter( 6724): 863760615: getState(). Returning 11
,V/BluetoothPbapService( 6724): Pbap Service closeService in
V/BluetoothPbapService( 6724): successfully stopped pbap service
V/BluetoothPbapService( 6724): Pbap Service closeService out
,D/HeadsetService( 6724): Received start request. Starting profile...
D/HeadsetStateMachine( 6724): Version 1.5
D/HeadsetStateMachine( 6724): make
,D/HeadsetStateMachine( 6724): max_hf_connections = 2
,D/HeadsetPhoneState( 6724): listenForPhoneState..for service and signal 
,D/HeadsetDualPhoneStateListener_SLOT1( 6724): listen phone state by slot:SLOT1  id:-1
D/HeadsetDualPhoneStateListener_SLOT2( 6724): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 6724): Enter Disconnected: -2, size: 0
,D/HeadsetDualPhoneStateListener_SLOT1( 6724): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 6724): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 6724): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 6724): BTHF: set_current_device
,I/art     (  972): Explicit concurrent mark sweep GC freed 16840(888KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.106ms total 179.461ms
,D/BluetoothAdapterService( 6724): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f0f91fc
,D/A2dpService( 6724): Received start request. Starting profile...
,V/Avrcp   ( 6724): make
,E/RemoteController( 6724): Cannot set synchronization mode on an unregistered RemoteController
,D/A2dpStateMachine( 6724): make
,D/bt-btif ( 6724): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
D/A2dpService( 6724): setA2dpService(): set to: null
D/BluetoothAdapterService( 6724): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f0f91fc
D/A2dpStateMachine( 6724): Enter Disconnected: -2
,D/HidService( 6724): Received start request. Starting profile...
,D/BluetoothAdapterService( 6724): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f0f91fc
,D/HealthService( 6724): Received start request. Starting profile...
,D/BluetoothAdapterService( 6724): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f0f91fc
,D/PanService( 6724): Received start request. Starting profile...
,D/PanService( 6724): HTC_CUSTOMIZATION_MHS_ENABLE = false,
D/BluetoothAdapterService( 6724): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f0f91fc
,D/BtGatt.DebugUtils( 6724): handleDebugAction() action=null
D/BtGatt.GattService( 6724): Received start request. Starting profile...
D/BtGatt.GattService( 6724): start()
,D/BtGatt.AdvertiseManager( 6724): advertise manager created
,D/BluetoothAdapterService( 6724): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f0f91fc
,D/BluetoothInputDevice( 5862): Proxy object connected
,D/HidProfile( 5862): Bluetooth service connected
,D/BluetoothAdapter( 5862): 952617179: getState(). Returning 11
,D/BluetoothPan( 5862): BluetoothPAN Proxy object connected
D/PanProfile( 5862): Bluetooth service connected
,V/BluetoothPbapService( 6724): Pbap Service onBind
,D/Process (  972): killProcessQuiet, pid=6359
I/ActivityManager(  972): Killing 6359:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  972): Recipient 6359
D/WifiService(  972): Client connection lost with reason: 4
,V/BluetoothPbapService( 6724): Pbap Service onDestroy
V/BluetoothPbapService( 6724): Pbap Service closeService in
V/BluetoothPbapService( 6724): Pbap Service closeService out
,I/HeadsetPhoneState( 6724): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 6724): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 6724): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
D/BluetoothAdapterState( 6724): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/HeadsetPhoneState( 6724): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6724): Disconnected process message: 11, size: 0
I/bt-btu  ( 6724): btu_task pending for preload complete event
D/BluetoothFtpService( 6724): ACTION_STATE_CHANGED: state: 13mHasStarted: false
,D/BluetoothMasReceiver( 6724): Bluetooth STATE CHANGED to 13
,E/bt_vendor( 6724): get_bt_soc_type: Failed to get soc type
,V/BluetoothSapReceiver( 6724): SapReceiver onReceive 
,V/BluetoothSapReceiver( 6724): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6724):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6724): startService = false
,D/AuthorizationBluetoothService( 1863): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/BluetoothPbapReceiver( 6724): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6724): ***********state = 10
,D/PMS     (  972): acquireWL(18895ba4): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5862 1000 null
,W/ContextImpl( 5862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,I/qcom-bluetooth( 6810): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,D/PMS     (  972): releaseWL(18895ba4): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/HtcBtWidget_BTWidgetProvider( 6766): onBTStateChanged() for widget: 
,D/PMS     (  972): acquireWL(b1b54c2): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5862 1000 null
D/HtcBtWidget_BTWidgetProvider( 6766): updateWidget(context) for widget: 
,D/DockEventReceiver( 5862): finishStartingService: stopping service
D/PMS     (  972): releaseWL(b1b54c2): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothMasReceiver( 6724): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 6724): onDestroy: mIsEmailEnabled: true
,V/BluetoothSapReceiver( 6724): SapReceiver onReceive 
,V/BluetoothSapReceiver( 6724): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6724):  Bluetooth Adapter state = 10
,V/BluetoothSapReceiver( 6724): startService = false
,D/AuthorizationBluetoothService( 1863): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/BluetoothPbapReceiver( 6724): ***********action = android.bluetooth.adapter.action.STATE_CHANGED,
V/BluetoothPbapReceiver( 6724): ***********state = 11
,D/HtcBtWidget_BTWidgetProvider( 6766): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 6766): updateWidget(context) for widget: 
I/qcom-bluetooth( 6817): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,D/BluetoothMasReceiver( 6724): Bluetooth STATE CHANGED to 11
,V/BluetoothSapReceiver( 6724): SapReceiver onReceive 
V/BluetoothSapReceiver( 6724): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6724):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 6724): startService = false
,I/qcom-bluetooth( 6818): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/AuthorizationBluetoothService( 1863): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/qcom-bluetooth( 6820): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
I/qcom-bluetooth( 6821): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 6822): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
I/qcom-bluetooth( 6823): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 6826): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
,I/qcom-bluetooth( 6827): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 6724): btu_task received preload complete event
,W/bt-l2cap( 6724): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6724): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6724): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 6724): L2CAP - L2CA_Register() called for PSM: 0x1487
,D/PMS     (  972): acquireWL(1e8262d3): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6724 1002 null,
D/bt-btm  ( 6724): btm_acl_device_down
D/bt-btm  ( 6724): btm_acl_reset_paging
D/bt-btm  ( 6724): btm_acl_set_discing
,I/bt-btm  ( 6724): btm_reset_complete,
,I/bt-btm  ( 6724): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
D/bt-btm  ( 6724): Start reading local supported commands
D/bt-btm  ( 6724): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 6724): BTM reads next extended features page (1)
D/bt-btm  ( 6724): BTM reads next extended features page (2)
D/bt-btm  ( 6724): BTM reached last extended features page (2)
D/bt-btm  ( 6724): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
D/bt-btm  ( 6724): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
D/bt-btm  ( 6724): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 6724): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
D/bt-btm  ( 6724): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
I/bt-btm  ( 6724): btm_vendor_capability_vsc_cmpl_cback: status=0
D/bt-btm  ( 6724): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 6724): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 6724): btm_read_ble_wl_size 
D/bt-btm  ( 6724): btm_read_white_list_size_complete 
D/bt-btm  ( 6724): btm_get_ble_buffer_size 
D/bt-btm  ( 6724): btm_read_ble_buf_size_complete 
D/bt-btm  ( 6724): btm_read_ble_local_supported_states 
D/bt-btm  ( 6724): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 6724): btm_read_ble_local_supported_features 
D/bt-btm  ( 6724): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 6724): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 6724): btm_decode_ext_features_page page: 0
D/bt-btm  ( 6724): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 6724): Local supported SCO packet types: 0x038f
I/bt-btm  ( 6724): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 6724):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 6724): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 6724): BTM_SetInquiryMode
I/bt-btm  ( 6724): BTM_SetPageScanType
I/bt-btm  ( 6724): BTM_SetInquiryScanType
D/bt-btm  ( 6724): btm_decode_ext_features_page page: 1
W/bt-btm  ( 6724): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 6724): btm_decode_ext_features_page page: 2
W/bt-btm  ( 6724): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 6724): BTM_BleLoadLocalKeys
D/bt-btm  ( 6724): BTM_BleLoadLocalKeys
I/bt-btm  ( 6724): BTM_Sec: application registered
E/bt-btm  ( 6724): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf9f94d5 
I/bt-btm  ( 6724): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 6724): SMP_Register state=0
E/bt-btm  ( 6724): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf9f94d5 
I/bt-btm  ( 6724): BTM_Sec: application registered
D/bt-btm  ( 6724): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 6724): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 6724): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 6724): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 6724): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 6724): BTM_RegBusyLevelNotif
D/bt-btm  ( 6724): BTM_BleReadControllerFeatures
I/bt-btm  ( 6724): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 6724): GATT_Register
D/bt-att  ( 6724): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 6724): allocated gatt_if=3
I/bt-att  ( 6724): GATT_StartIf gatt_if=3
D/bt-att  ( 6724): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6724): gatt_find_the_connected_bda found=0 found_idx=16
D/bt-btm  ( 6724): btm_ble_vendor_capability_vsc_cmpl_cback
D/bt-btm  ( 6724): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 6724): BTM Register For VSEvents is successfully
D/bt-btm  ( 6724): BTM_BleGetVendorCapabilities
I/bt-btif ( 6724): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterProperties( 6724): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 6724): bta_dm_set_dev_name: name: HTC One M8s 
E/bt-btif ( 6724): Calling BTA_HhEnable
I/bt-btif ( 6724): BTA_MceEnable
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
E/bt-btif ( 6724): btif_storage_get_adapter_property service_mask:0x2140040
I/bt-btif ( 6724): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 6724):  BTM_BleConfigPrivacy
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
D/BluetoothAdapterProperties( 6724): Address is:90:E7:C4:F6:69:77
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
,I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 6724): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 6724): BTM_AllocateSCN
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 6724): BTM_AllocateSCN
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btm  ( 6724): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6724):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6724):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 6724): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 6724): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6724):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6724):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 6724): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 6724): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6724):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6724):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6724):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6724):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6724):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6724): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6724):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6724): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 6724): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6724):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6724):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 6724): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 6724): A2D_AddRecord uuid: 110a
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
D/bt-btif ( 6724):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 6724): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btm  ( 6724): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6724):                : sec: 0x86, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6724): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6724):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6724):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6724):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6724): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6724):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6724):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6724): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6724): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 6724): GATT_Register
,D/bt-att  ( 6724): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 6724): allocated gatt_if=4
I/bt-att  ( 6724): GATT_StartIf gatt_if=4
D/bt-att  ( 6724): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6724): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 6724): Scan Mode:21
D/BluetoothAdapterProperties( 6724): Discoverable Timeout:120
I/bt-btif ( 6724): BTA_JvEnable
I/bt-btif ( 6724): BTA_JvRegisterL2cCback
I/bt-btm  ( 6724): BTM_ReadConnectability
I/bt-btm  ( 6724): BTM_ReadDiscoverability
I/bt-btm  ( 6724): BTM_SetDiscoverability
I/bt-btm  ( 6724): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 6724): disc_mode 0002
D/bt-btm  ( 6724): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 6724): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6724): BTM_SetConnectability
I/bt-btm  ( 6724): btm_ble_set_connectability mode=0x0 combined_mode=0x1
,D/bt-btm  ( 6724): disc_mode 0002
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 6724): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 6724): BTM_SetDiscoverability
I/bt-btm  ( 6724): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6724): disc_mode 0000
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6724): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 6724): BTM_SetConnectability
I/bt-btm  ( 6724): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6724): disc_mode 0000
D/bt-btm  ( 6724): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 6724): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
I/bt-btm  ( 6724): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6724): bta_pan_co_init
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:8
,I/bt-btm  ( 6724): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6724):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6724):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btm  ( 6724): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6724):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6724): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6724):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_gen_resolve_paddr_low
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 66 b3 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 27 d5 e9 aa 15 22 00 82 88 78 fa 3c d3 71 98 f1 
I/bt-btm  ( 6724): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6724): Stopping oneshot timer
D/bt-btm  ( 6724): Starting oneshot timer type:103 timeout:900s
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btif ( 6724): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 6724): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6724): smp_encrypt_data
D/BluetoothAdapterProperties( 6724): ScanMode =  21
D/BluetoothAdapterProperties( 6724): State =  11
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = ac 58 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 70 02 f7 94 b6 41 95 de 6d 83 d9 d1 6d b0 7a 81 
D/BluetoothAdapterProperties( 6724): Setting state to 12
I/BluetoothAdapterState( 6724): Bluetooth adapter state changed: 11-> 12
D/bt-btif ( 6724): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 6724): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
,D/bt-btif ( 6724): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6724): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 6724): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
E/bt_mct  ( 6724): hci lib postload completed
I/bt-btif ( 6724): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  972): +onBluetoothStateChange prev=11 new=12
D/BluetoothAdapterProperties( 6724): Discoverable Timeout:120
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  972): Broadcasting onBluetoothStateChange(true) to 13 receivers.
,I/BluetoothAdapterState( 6724): Entering On State
D/BluetoothHeadset( 1223): onBluetoothStateChange: up=true
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = bd d1 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 52 27 fe 48 bb 9b 48 9b a7 57 99 08 cb 8b 75 97 
D/BluetoothHeadset(  972): onBluetoothStateChange: up=true
D/BluetoothPbap( 5862): onBluetoothStateChange: up=true
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 2e 30 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 91 33 9c 7d 6a ed bf f5 b2 ae 0a 80 c8 cb 74 22 
D/BluetoothHeadset( 1570): onBluetoothStateChange: up=true
D/BluetoothHeadset(  972): Proxy object connected
D/BluetoothHeadset( 1223): Proxy object connected
I/QuickSettingMiniLite( 1223): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@aa8d109
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6724): smp_encrypt_data
D/BluetoothAdapter(  972): 100982228: getState(). Returning 12
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 13 88 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 3e 1d 3a 08 0c a2 e1 8d d8 9d e6 97 c5 35 ea 8d 
D/BluetoothHeadset( 1570): Proxy object connected
D/BluetoothMap( 5862): onBluetoothStateChange: up=true
E/BluetoothMap( 5862): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothA2dp( 3684): onBluetoothStateChange: up=true
,D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
,D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 01 4b 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = df 30 d1 19 20 4e cf 97 d1 10 eb b1 94 d2 9a 2e 
,D/BluetoothHeadset( 3684): onBluetoothStateChange: up=true
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 22 f2 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = ff d0 5f 81 52 5e 2e 46 43 52 78 aa 18 48 57 b4 
D/BluetoothA2dp( 3684): Proxy object connected
D/NGFService( 3684): BluetoothA2dp onServiceConnected: main
D/BluetoothHeadset( 1570): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 3684): 1010497024: getState(). Returning 12
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = ff 8f 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 07 86 04 05 2f 85 c6 86 08 6f 93 e8 3e 99 5b 8c 
,W/NGFService( 3684): A2dp deviceList = 0
D/BluetoothHeadset( 3684): Proxy object connected,
D/NGFService( 3684): BluetoothHeadset onServiceConnected: main
,D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = f1 e6 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 25 c9 39 15 12 45 9a 97 57 60 e8 c4 9b 42 e7 46 
D/BluetoothHeadset( 1570): Proxy object connected
,D/BluetoothPhoneService( 1570): BluetoothHeadset onServiceConnected
D/BluetoothAdapter( 3684): 1010497024: getState(). Returning 12
D/BluetoothPan( 5862): onBluetoothStateChange on: true
D/BluetoothSap( 5862): onBluetoothStateChange on: true
D/BluetoothSap( 5862): onBluetoothStateChange call bindService
,W/NGFService( 3684): Headset deviceList = 0
W/ContextImpl( 5862): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap$1.onBluetoothStateChange:154 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 86 53 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 6b 0f dc 2e 32 5b 43 22 30 07 8b c5 06 58 35 c1 
D/BluetoothSap( 5862): BluetoothSap(), bindService called
,D/BluetoothA2dp(  972): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  972): Proxy object connected,
D/BluetoothInputDevice( 5862): onBluetoothStateChange: up=true
D/BluetoothAdapter(  972): 100982228: getState(). Returning 12
D/BluetoothHeadset( 1570): onBluetoothStateChange: up=true
,D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_gen_resolve_paddr_low
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 2e c8 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = d7 a4 cc de e1 f7 c7 0f c6 40 54 3f 64 f2 97 e7 
,I/bt-btm  ( 6724): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6724): Stopping oneshot timer
D/bt-btm  ( 6724): Starting oneshot timer type:103 timeout:900s
D/BluetoothHeadset( 1570): Proxy object connected
D/BluetoothManagerService(  972): Bluetooth State Change Intent: 11 -> 12
,I/IntentController( 1223): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/NGFService( 3684): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3684): Bluetooth Adapter: ON
V/BluetoothPbapReceiver( 6724): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6724): ***********state = 12,
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_gen_resolve_paddr_low
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 5c 2e 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 38 70 e7 96 3a 2a 82 d7 cc 5c 5c ec b1 f0 a3 7f 
I/bt-btm  ( 6724): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6724): Stopping oneshot timer
,D/bt-btm  ( 6724): Starting oneshot timer type:103 timeout:900s
V/BluetoothPbapService( 6724): Pbap Service onCreate
V/BluetoothPbapService( 6724): Starting PBAP service
D/BluetoothAdapter( 6724): 863760615: getState(). Returning 12
V/BluetoothPbapService( 6724): Pbap Service onBind
,V/BluetoothPbapService( 6724): Handler(): got msg=1
D/LocalBluetoothProfileManager( 5862): setBluetoothStateOn
V/BluetoothPbapService( 6724): Pbap Service startRfcommSocketListener
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_gen_resolve_paddr_low
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 70 2a 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 6a 0a 2a 52 19 ae 63 8e e0 83 9a 80 d2 2e d5 c9 
I/bt-btm  ( 6724): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6724): Stopping oneshot timer
D/bt-btm  ( 6724): Starting oneshot timer type:103 timeout:900s
D/BluetoothAdapter( 5862): 952617179: getState(). Returning 12
,V/BluetoothPbapService( 6724): Pbap Service initSocket
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 14
,W/BluetoothAdapter( 6724): getBluetoothService() called with no BluetoothManagerCallback
D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_gen_resolve_paddr_low
D/bt-smp  ( 6724): smp_encrypt_data
I/bt-btif ( 6724): BTA_JvCreateRecordByUser
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = 47 cb 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
I/bt-btif ( 6724): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = cf f4 63 df e7 8c 14 06 30 70 b9 7a 2b 32 83 fe 
I/bt-btm  ( 6724): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6724): Stopping oneshot timer
D/bt-btm  ( 6724): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 6724): BTM_SetDiscoverability
I/bt-btm  ( 6724): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6724): disc_mode 0000
I/bt-btm  ( 6724): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6724): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 6724): Scan Mode:21
I/bt-btm  ( 6724): BTM_SetConnectability
,I/bt-btm  ( 6724): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6724): disc_mode 0000
D/bt-btm  ( 6724): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 6724): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 6724): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:10
,I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btif ( 6724): BTA_JvRfcommStartServer
I/bt-btm  ( 6724): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 6724):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 6724): Succeed to create listening socket 
V/BluetoothPbapService( 6724): Accepting socket connection...
D/BluetoothHeadset( 5862): BluetoothHeadset()
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  972): Registered receivers: 15
,D/BluetoothAdapter( 5862): 952617179: getState(). Returning 12,
,D/PMS     (  972): acquireWL(5d35ed): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5862 1000 null
W/ContextImpl( 5862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/BluetoothPbap( 5862): Proxy object connected
D/PbapServerProfile( 5862): Bluetooth service connected
D/BluetoothA2dp( 5862): Proxy object connected
,D/A2dpProfile( 5862): Bluetooth service connected
,D/BluetoothAdapter( 5862): 952617179: getState(). Returning 12
,D/BluetoothAdapter( 1223): 180682956: getState(). Returning 12
D/HtcBtWidget_BTWidgetProvider( 6766): onBTStateChanged() for widget: 
,D/BluetoothHeadset( 5862): Proxy object connected
,D/HtcBtWidget_BTWidgetProvider( 6766): updateWidget(context) for widget: 
D/BluetoothAdapter( 1223): 180682956: getState(). Returning 12
I/QuickSettingBluetooth( 1223): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1223): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/HeadsetProfile( 5862): Bluetooth service connected
D/BluetoothAdapter( 5862): 952617179: getState(). Returning 12
D/BluetoothAdapter( 1223): 180682956: getState(). Returning 12
,I/QuickSettingMiniLite( 1223): updateLiteState:no connect device!
,D/PMS     (  972): releaseWL(5d35ed): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null,
D/PMS     (  972): acquireWL(313e5470): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5862 1000 null
,D/DockEventReceiver( 5862): finishStartingService: stopping service
,D/PMS     (  972): releaseWL(313e5470): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothAdapter( 6724): 863760615: getState(). Returning 12
D/BluetoothFtpService( 6724): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothMasReceiver( 6724): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 6724):  call MAP start service
,W/BluetoothAdapter( 6724): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothFtpService( 6724): htc sense version is 6.0
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6724): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6724): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btif ( 6724): BTA_JvRfcommStartServer
I/bt-btm  ( 6724): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
,I/bt-btm  ( 6724):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/bt-btif ( 6724): BTA_JvCreateRecordByUser
I/BtOppRfcommListener( 6724): Accept thread started.
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btif ( 6724): BTA_JvRfcommStartServer
I/bt-btm  ( 6724): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 6724):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,E/BluetoothMasService( 6724): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 6724): Add permission for SmsProvider.
V/BluetoothFtpService:RfcommSocketAcceptThread( 6724): Run Accept thread
V/BluetoothMasService( 6724): Starting MAS instances
D/BluetoothAdapter( 6724): 863760615: getState(). Returning 12
V/EmailUtils( 6724): Manager Instance is not NULL
,D/EmailUtils( 6724): ============NULL aList========
,V/EmailUtils( 6724): <-getEmailAccountIdList
V/BluetoothMasService( 6724): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 6724): 863760615: getState(). Returning 12
,V/BluetoothMasService( 6724): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 6724): Manager Instance is not NULL
,D/EmailUtils( 6724): ============NULL aList========
,V/EmailUtils( 6724): <-getEmailAccountIdList
,V/BluetoothSapReceiver( 6724): SapReceiver onReceive 
V/BluetoothSapReceiver( 6724): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6724):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6724): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 6724): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 6724): BluetoothMns: isEmailEnabled: true
,D/AuthorizationBluetoothService( 1863): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6724): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6724): BTA_JvCreateRecordByUser
D/bt-btm  ( 6724): BTM_AllocateSCN
,D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btif ( 6724): BTA_JvRfcommStartServer
I/bt-btm  ( 6724): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 6724):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6724): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6724): BTA_JvCreateRecordByUser
D/bt-btm  ( 6724): BTM_AllocateSCN
D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btif ( 6724): BTA_JvRfcommStartServer
I/bt-btm  ( 6724): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 6724):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothSapService( 6724): Sap Service onCreate
,V/BluetoothSapService( 6724): initBinder
,V/BluetoothSapService( 6724): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@3ee7e68d
V/BluetoothSapService( 6724): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@20e47853
,V/BluetoothSapService( 6724): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 6724): state: 12
D/SapServerProfile( 5862): Bluetooth service connected
V/BluetoothSapService( 6724): Starting SAP server process
,V/BluetoothSapService( 6724): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 6724): Sap Service initRfcommSocket
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6724): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6724): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 6724): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 6724): Write Extended Inquiry Response to controller
I/bt-btif ( 6724): BTA_JvRfcommStartServer
I/bt-btm  ( 6724): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 6724):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 6724): Succeed to create listening socket 
V/BluetoothSapService( 6724): Accepting socket connection...
,D/A2dpService( 6724): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@c795e89
,D/A2dpSinkService( 6724): getA2dpSinkService(): service is NULL,
,D/PMS     (  972): releaseWL(1e8262d3): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  972): acquireWL(1bd78721): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(1bd78721): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100,
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  972): runPSCheck
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(2a76c746): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2a76c746): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): processMsg: DeviceActiveState
,D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(2b6e5d07): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(2b6e5d07): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo,
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  972): plugged=true pluggin=true
,D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): >> updateStatus
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
,D/WifiController(  972): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(18bfee34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(18bfee34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+
,D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
,D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(3484745d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
,D/PMS     (  972): releaseWL(3484745d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  972): Checking...
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(14c811d2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000},
V/AlarmManager(  972): sending alarm PendingIntent{391cc769: PendingIntentRecord{3a3915ee android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=405458, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{39d97c37: PendingIntentRecord{2efcd5a4 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806045, Int=0
V/AlarmManager(  972): sending alarm PendingIntent{2909c2a3: PendingIntentRecord{11f2be33 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457955080586, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{1f87b9a0: PendingIntentRecord{3918f959 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457955127862, Int=0
,I/ActivityManager(  972): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6848 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  972): sending alarm PendingIntent{1f71791e: PendingIntentRecord{16be5ff com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457954842733, Int=0
,I/ActivityManager(  972): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6868 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/WeatherUtility( 1223): Weather sync is On,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/art     (  415): Explicit concurrent mark sweep GC freed 8646(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 217us total 30.434ms
,I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 204us total 22.308ms,
,I/art     (  415): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 164us total 21.693ms
,W/ContextImpl( 6868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 6868): isEpsOn(), nState = 0,
D/PowerUsageList:PowerUsageHelper( 6868): MY_DEBUG = false
,D/PMS     (  972): acquireWL(32b8092a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6868 1000 null,
,D/PMS     (  972): releaseWL(14c811d2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PowerUsageService( 6868): repeat time = 1457956028165
,D/PMS     (  972): releaseWL(32b8092a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  972): acquireWL(2ba2e31b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6868 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6868): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6868): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6868): AlarmOnTime = -1,
,D/SmartSyncScreenOnOffTimeReceiver( 6868): SettingOnTime = 1458021600000, randomSettingOnTime = 1458019377000
,D/SmartSyncScreenOnOffTimeReceiver( 6868): SettingOffTime = 1458000000000, randomSettingOffTime = 1458004896000
,D/SmartSyncScreenOnOffTimeReceiver( 6868): bDayMode = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6868): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6868): bNightModeTurnOffOnce = false
,D/PMS     (  972): releaseWL(2ba2e31b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,E/cutils-trace( 6896): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6896): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6896): dex2oat: override thread count:4
,I/PowerUsageList:PowerUsageHelper( 6868): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6868): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 6868): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6868): gen(), null == sipper.uidObj, userId = 0,
,I/ActivityManager(  972): Killing 6418:com.htc.calendar/u0a10 (adj 15): empty #17,
D/Process (  972): killProcessQuiet, pid=6418
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6418,
,I/dex2oat ( 6896): dex2oat took 897.403ms (threads: 4),
,I/PushClient( 6848): ApplicationMonitor {38eb4001}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6848): ApplicationMonitor {38eb4001}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6848): ApplicationMonitor {38eb4001}: logBasicAppInfo(): VersionName:             1.2.853019,
,I/PushClient( 6848): ApplicationMonitor {38eb4001}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6848): ApplicationMonitor {38eb4001}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6848): ApplicationMonitor {38eb4001}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
,I/PushClient( 6848): ApplicationMonitor {38eb4001}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6848): ApplicationMonitor {38eb4001}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6848): ApplicationMonitor {38eb4001}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6848): PnsModel {13c1d1e8}: update(): Update registration caused by: alarm,
,I/PushClient( 6848): PnsConfigModel {275c15df}: <init>(): Use dm-client for provisioning.
,W/System.err( 6848): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6848): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6848): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6848): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  972): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6904 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6904): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6904 dbg=false s=true
,I/DeviceManagement( 6904): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6904): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6904): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6904): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6904): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@13c1d1e8] args=[Bundle[mParcelledData.dataSize=88]]
I/DeviceManagement( 6904): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6904): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6904): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6904): SessionStateController: Checking invariants...
,I/DeviceManagement( 6904): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,D/PMS     (  972): acquireWL(f4ccad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
,I/BatteryService(  972): n_update end
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  972): battery changed pluggedType: 2
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): onReceive BATTERY_CHANGED
,D/PMS     (  972): releaseWL(f4ccad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: DeviceActiveState
,D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,I/DeviceManagement( 6904): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6904): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6904): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@13c1d1e8]
,I/DeviceManagement( 6904): WorkflowService: Stopping workflow service,
,I/ActivityManager(  972): Killing 6394:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=6394
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6394,
,I/PushClient( 6848): PnsModel {13c1d1e8}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  972): Killing 6536:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=6536
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 6536,
,D/PMS     (  972): acquireWL(13fbc3fc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
,D/PMS     (  972): releaseWL(13fbc3fc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  972): Checking...
,I/HtcPowerSaver(  972): >> updateStatus
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): handleMessage: E msg.what=155652
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): << updateStatus
D/WifiController(  972): handleMessage: X
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(8d16a85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null,
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(8d16a85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  972): updateBatteryInfo,
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  972): BroadcastReceiver::onReceive+,
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
,D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: StaEnabledState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(377d10da): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
,I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(377d10da): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  972): updateBatteryInfo
D/PMS     (  972): runPSCheck
D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  972): User[0] Flushing usage stats to disk
,D/PMS     (  972): acquireWL(1dfec90b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(1dfec90b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  972): plugged=true pluggin=true
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  972): runPSCheck
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): Checking...
,D/UsbnetService(  972): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  972): >> updateStatus
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(303f23e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/PMS     (  972): releaseWL(303f23e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PMS     (  972): runPSCheck
D/WifiController(  972): handleMessage: E msg.what=155652
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): processMsg: DeviceActiveState
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): handleMessage: X
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  972): acquireWL(35432a01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
I/BatteryService(  972): n_update end
,D/PMS     (  972): releaseWL(35432a01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  972): updateBatteryInfo
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-,
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: StaEnabledState
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  972): processMsg: DefaultState
I/HtcPowerSaver(  972): << updateStatus
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
D/WifiController(  972): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(222b60a6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
,I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(222b60a6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
,D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/WifiController(  972): battery changed pluggedType: 2
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  972): updateBatteryInfo
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  972): runPSCheck
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  972): Checking...
D/WifiController(  972): handleMessage: E msg.what=155652
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): processMsg: DeviceActiveState
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
D/HeadsetStateMachine( 6724): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  972): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  972): acquireWL(2a4eeae7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 972 1000 WorkSource{1000}
,V/AlarmManager(  972): sending alarm PendingIntent{391cc769: PendingIntentRecord{3a3915ee android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1065458, Int=0
,V/AlarmManager(  972): sending alarm PendingIntent{24d69694: PendingIntentRecord{1bb7653d com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1533059, Int=0
I/bt-btm  ( 6724): Received oneshot timer event complete
,I/bt-btm  ( 6724): btm_ble_timeout
I/bt-btm  ( 6724): btm_gen_resolvable_private_addr
,D/PMS     (  972): acquireWL(381ce132): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6724 1002 null
,D/bt-btm  ( 6724): btm_ble_rand_enc_complete
I/bt-btm  ( 6724): btm_gen_resolve_paddr_low
D/bt-smp  ( 6724): smp_encrypt_data
W/bt-smp  ( 6724): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6724): Plain text(LSB ~ MSB) = f3 c0 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6724): Encrypted text(LSB ~ MSB) = 87 fb 4e b3 83 51 68 2c 24 d2 2d 0a 7b 40 9f a4 
I/bt-btm  ( 6724): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6724): Stopping oneshot timer
D/bt-btm  ( 6724): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  972): releaseWL(2a4eeae7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  972): releaseWL(381ce132): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,TIME-OUT KILL (timeout was 1400000ms),E/cutils-trace( 6934): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6934): ====startRecUseTime====
D/htc.customization.log.level( 6934):  is 
W/CustomizationLogLevel( 6934): Level value is invalid, use default level 2
D/CustomizationManager( 6934):  Read ACC file spent 0.054 (s)
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
D/CustomizationManager( 6934):  Read CID file spent 0.111 (s)
D/CustomizationManager( 6934):  All configurations done spent 0.112 (s)
D/PackageManager(  972): deletePackageAsUser: pkg=com.test.thalitest, pid=6934, uid=2000 userid=0
I/ActivityManager(  972): Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
D/Process (  972): killProcessQuiet, pid=6470
I/ActivityManager(  972): Killing 6470:com.test.thalitest/u0a195 (adj 0): stop com.test.thalitest
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  972): Skipping PackageSetting{1199ae56 com.example.hello/10374} due to missing metadata
I/ActivityManager(  972): Recipient 6470
I/WindowState(  972): WIN DEATH: Window{282056ff u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  972): Client connection lost with reason: 4
I/ActivityManager(  972):   Force finishing activity ActivityRecord{2f47ff58 u0 com.test.thalitest/.MainActivity t12}
W/ActivityManager(  972): Spurious death for ProcessRecord{f954e83 6470:com.test.thalitest/u0a195}, curProc for 6470: null
I/ActivityManager(  972): Force stopping com.test.thalitest appid=10195 user=0: pkg removed
V/NetworkPolicy(  972): ACTION_UID_REMOVED for uid=10195
D/PMS     (  972): acquireWL(1cd08800): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
D/DotMatrix( 1340): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1340): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1340): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  972): acquireWL(3e3a1839): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1807 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1807): Ignoring removeGeofence because network location is disabled.
D/PMS     (  972): releaseWL(3e3a1839): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1776): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  972): Cannot find grip_rejection_width, use default value instead
I/InputMethodManagerService(  972): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1776): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/art     ( 1632): Explicit concurrent mark sweep GC freed 4170(215KB) AllocSpace objects, 5(380KB) LOS objects, 34% free, 29MB/45MB, paused 944us total 94.001ms
I/Prism.ItemManager( 1632): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1632): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  972): releaseWL(1cd08800): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  972): writePolicyLocked()
I/Launcher( 1632): Deferring update until onResume
D/Launcher( 1632): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1715): Cleaning up data for package: com.test.thalitest
D/PhoneApp( 1570): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/AccTypeManager( 1776): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
D/Prism.PackageStateRece_( 1632): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1535): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/ResourcesManager(  972): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/[PluginManager]RegisterService( 1535): handle notify Blinkfeed plugin client changed
E/ExternalAccountType( 1776): Unsupported attribute readOnly
I/ActivityManager(  972): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6954 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/art     (  972): Explicit concurrent mark sweep GC freed 32817(2MB) AllocSpace objects, 10(544KB) LOS objects, 33% free, 16MB/24MB, paused 1.978ms total 242.761ms
I/art     (  972): WaitForGcToComplete blocked for 222.125ms for cause Explicit
W/ContextImpl( 6954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  972): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
I/ActivityManager(  972): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6979 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/FindExtension( 1632): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1632): Defer allocateBuffers to drawing time
D/Process (  972): killProcessQuiet, pid=6327
I/ActivityManager(  972): Killing 6327:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/InputMethodManagerService(  972): Got RemoteException sending setActive(false) notification to pid 6470 uid 10195
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
W/PackageManager(  972): Unable to load service info ResolveInfo{179400af com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  972): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  972): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  972): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  972): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  972): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  972): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  972): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  972): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  972): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  972): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  972): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/art     (  972): Explicit concurrent mark sweep GC freed 5702(305KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.831ms total 197.461ms
I/ActivityManager(  972): Recipient 6327
D/JobSchedulerService(  972): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  972): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7002 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=arm64-v8a
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/TaskPersister(  972): removeObsoleteFile: deleting file=12_task.xml
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6979, uid=10072, userID:0
W/global  ( 6979): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 6979): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 6979): [apache-http] Connection GC has been deprecated!
I/ActivityManager(  972): Killing 6265:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=6265
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  972): Recipient 6265
W/global  ( 6979): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 6979): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  972): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7043 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 6979): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6979): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 6979): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 6979): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 6979): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6979): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6979): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6979): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6979): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 6979): Process: com.android.vending, PID: 6979
E/AndroidRuntime( 6979): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6979): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 6979): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 6979): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 6979): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6979): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6979): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6979): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 6979): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6979): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 6979): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6979): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6979): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 6979): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 6979): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 6979): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 6979): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 6979): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 6979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 6979): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 6979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 6979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 6979): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 6979): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 6979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 6979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 6979): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 6979): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 6979): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 6979): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 6979): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 6979): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 6979): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 6979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 6979): 	... 4 more
E/ActivityManager(  972): App crashed! Process: com.android.vending
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6979, uid=10072, userID:0
E/SQLiteDatabase( 6979): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6979): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 6979): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 6979): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6979): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6979): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 6979): killProcess, pid=6979
W/ResourcesManager( 7043): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7043): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/AndroidRuntime_3_crash( 6979): crash in the same process: AsyncTask #3
E/AndroidRuntime_3_crash( 6979): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 6979): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 6979): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 6979): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 6979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 6979): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 6979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 6979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 6979): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 6979): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 6979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 6979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 6979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 6979): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 6979): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 6979): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 6979): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 6979): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 6979): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 6979): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 6979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 6979): 	... 4 more
E/DropBoxManagerService(  972): Can't write: system_app_crash
E/DropBoxManagerService(  972): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  972): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  972): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  972): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  972): 	... 5 more
D/Process ( 6979): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
I/MultiDex( 7043): VM with version 2.1.0 has multidex support
I/MultiDex( 7043): install
I/MultiDex( 7043): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7043): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  972): Recipient 6979
I/ActivityManager(  972): Process com.android.vending (pid 6979) has died
W/ActivityThread( 7043): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7043): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d373651: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7043): Installed default security provider GmsCore_OpenSSL
E/SQLiteLog( 1863): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1863): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x55b0044820
W/NativeLibraryUtils( 7043): Failed to open lock file
W/NativeLibraryUtils( 7043): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7043): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7043): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7043): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7043): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7043): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7043): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7043): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7043): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7043): 	... 3 more
E/AndroidRuntime( 1863): FATAL EXCEPTION: main
E/AndroidRuntime( 1863): Process: com.google.process.gapps, PID: 1863
E/AndroidRuntime( 1863): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1863): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1863): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1863): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1863): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1863): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1863): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1863): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1863): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1863): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1863): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1863): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1863): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1863): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1863): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1863): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1863): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1863): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1863): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1863): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1863): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1863): 	... 9 more
E/ActivityManager(  972): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  972): Can't write: system_app_crash
E/DropBoxManagerService(  972): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  972): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  972): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  972): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  972): 	... 5 more
D/Process ( 1863): killProcess, pid=1863
D/Process ( 1863): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  972): Recipient 1863
I/ActivityThread( 7043): Removing dead content provider:android.content.ContentProviderProxy@77017b7
I/ActivityManager(  972): Process com.google.process.gapps (pid 1863) has died
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 1000ms
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 20999ms
W/ActivityManager(  972): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
I/ActivityManager(  972): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=7077 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 7077): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7077): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7077): VM with version 2.1.0 has multidex support
I/MultiDex( 7077): install
I/MultiDex( 7077): VM has multidex support, MultiDex support library is disabled.
I/GservicesProvider( 7077): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 7077): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7077): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7077): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7077): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7077): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7077): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7077): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7077): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7077): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7077): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7077): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7077): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7077): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7077): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7077): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7077): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7077): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7077): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7077): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7077): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7077): FATAL EXCEPTION: main
E/AndroidRuntime( 7077): Process: com.google.process.gapps, PID: 7077
E/AndroidRuntime( 7077): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7077): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7077): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7077): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7077): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7077): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7077): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7077): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7077): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7077): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7077): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7077): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7077): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7077): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7077): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7077): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7077): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7077): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7077): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7077): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7077): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7077): 	... 11 more
E/ActivityManager(  972): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  972): Can't write: system_app_crash
E/DropBoxManagerService(  972): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  972): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  972): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  972): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  972): 	... 5 more
D/Process ( 7077): killProcess, pid=7077
D/Process ( 7077): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  972): Recipient 7077
I/ActivityManager(  972): Process com.google.process.gapps (pid 7077) has died
W/ActivityManager(  972): Service crashed 2 times, stopping: ServiceRecord{367b55b6 u0 com.google.android.gms/.gcm.http.GoogleHttpService}
W/ActivityManager(  972): Service crashed 2 times, stopping: ServiceRecord{feb0284 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
W/ActivityManager(  972): Service crashed 2 times, stopping: ServiceRecord{f065252 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
W/ActivityManager(  972): Service crashed 2 times, stopping: ServiceRecord{7004d92 u0 com.google.android.gms/.gcm.GcmService}
I/Prism.ItemManager( 1632): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1632): loadItems() com.htc.launcher.pageview.WidgetManager@29fc3d2a +
I/Prism.WidgetManager( 1632): onLoadItems() +
I/ActivityManager(  972): Start proc com.google.process.gapps for restart com.google.process.gapps: pid=7099 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 1632): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 7099): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7099): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7099): VM with version 2.1.0 has multidex support
I/MultiDex( 7099): install
I/MultiDex( 7099): VM has multidex support, MultiDex support library is disabled.
I/GservicesProvider( 7099): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 7099): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7099): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7099): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7099): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7099): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7099): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7099): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7099): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7099): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7099): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7099): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7099): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7099): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7099): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7099): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7099): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7099): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7099): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7099): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7099): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7099): FATAL EXCEPTION: main
E/AndroidRuntime( 7099): Process: com.google.process.gapps, PID: 7099
E/AndroidRuntime( 7099): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7099): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7099): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7099): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7099): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7099): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7099): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7099): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7099): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7099): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7099): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7099): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7099): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7099): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7099): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7099): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7099): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7099): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7099): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7099): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7099): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7099): 	... 11 more
E/ActivityManager(  972): App crashed! Process: com.google.process.gapps
W/ActivityManager(  972): Process com.google.android.gms has crashed too many times: killing!
D/Process (  972): killProcessQuiet, pid=7099
I/ActivityManager(  972): Killing 7099:com.google.process.gapps/u0a24 (adj 0): crash
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12134 
E/DropBoxManagerService(  972): Can't write: system_app_crash
E/DropBoxManagerService(  972): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  972): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  972): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  972): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  972): 	... 5 more
I/ActivityManager(  972): Recipient 7099
W/ResourcesManager( 1632): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Process (  972): killProcessQuiet, pid=7043
I/ActivityManager(  972): Killing 7043:com.google.android.gms:car/u0a24 (adj 0): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:15264 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:15341 
W/ActivityManager(  972): Unable to launch app com.google.android.gsf/10024 for provider com.google.android.gsf.gservices: launching app became null
W/asset   ( 1632): Copying FileAsset 0x55b05fd1d0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.

```
